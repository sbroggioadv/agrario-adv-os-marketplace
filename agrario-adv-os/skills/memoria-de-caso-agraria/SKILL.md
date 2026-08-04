---
name: memoria-de-caso-agraria
description: "Mantem o estado append-only de um caso agrario — partes e lado, imovel (matricula, area, modulos fiscais, CCIR, CAR, georreferenciamento, bioma, UF), contratos agrarios vigentes, safras perdidas e laudos, titulos de credito emitidos (CPR fisica/financeira, cedula rural, CIR, patrimonio em afetacao), garantias, autos de infracao e embargos ambientais, processos em curso, prazos fatais e proximo passo. Use quando o operador retomar um caso, perguntar onde paramos, pedir status, cronologia ou prazos, ou quando o agrario-master precisar carregar e atualizar o estado. Tambem ao iniciar caso novo."
---

# MEMORIA-DE-CASO-AGRARIA

> Camada 0. Registro **append-only** do caso. O `agrario-master` le no inicio e atualiza no fim de cada ato. Estado e fato, nao opiniao.

## Anexos obrigatorios (context/)
- `context/metodologia-agraria.md` — fluxo da porta unica e o que cada camada exige de estado — **grep + ler a faixa**.

## Objetivo
Nunca perder o fio do caso: quem sao as partes e de que lado o escritorio atua, qual e exatamente o imovel, o que ja foi contratado, o que foi emitido como titulo, o que ja foi autuado ou embargado, o que esta em juizo e **qual o proximo prazo fatal**.

## Quando ativar
Retomar caso, "onde paramos", "status", "cronologia", "quais prazos"; quando o `agrario-master` carrega ou atualiza o estado; ou ao abrir caso novo.

## Onde grava
`agrario/casos/<slug-do-caso>.md` no diretorio de trabalho. **Append-only:** cada ato vira nova linha no historico; nunca apagar o anterior.

## Estrutura do arquivo de caso
```markdown
# Caso: <titulo>
## Partes e lado
- Cliente: <nome/PJ> | lado: <produtor / credor-trading / adquirente>
- Contraparte: <nome/PJ> | qualificacao: <PF x PJ, produtor x empresario rural>
- Inscricao na Junta Comercial: <sim/nao> | data: <...> (Tema 1.145: vale a inscricao no momento do pedido)
## Imovel
- Matricula/RI: <nº e comarca> | area total: <ha> | modulos fiscais: <nº> | municipio/UF: <...>
- Pequena propriedade (ate 4 MF)? <sim/nao> | bioma: <...>
- CCIR: <nº / vencimento> | CAR: <nº / status: ativo, pendente, cancelado>
- Georreferenciado/certificado no INCRA? <sim/nao/parcial> — ⚠️ prazo **sub judice** (proc. **1086967-47.2025.4.01.3700**, JF/MA) — verificar na data
- APP/RL averbada ou inscrita no CAR? <...> | area consolidada em 22/07/2008? <sim/nao>
## Contratos agrarios
- Tipo: <arrendamento / parceria / barter / integracao / compra e venda de safra>
- Escrito ou verbal? <...> | prazo: <inicio-fim> | preco/quota: <...> | registrado no RTD/RI? <sim/nao>
- Hipotese de transferencia: <nenhuma / alienacao voluntaria (sub-rogacao) / perda da propriedade (extincao)>
## Credito e titulos
- Titulos emitidos: <CPR fisica / CPR financeira / cedula rural (especie) / CIR> | nº | data | valor
- Registro em entidade autorizada pelo BCB: <sim/nao/data> | garantias: <penhor / AF / hipoteca / afetacao>
- Patrimonio rural em afetacao: <sim/nao> | registro em 5 dias uteis? <sim/nao>
- Inadimplencia: <sim/nao> | vencimento: <...> | protesto/execucao: <...>
## Safra e frustracao
- Safras com perda (2019-2025): <lista por ano> | queda de renda bruta apurada: <%>
- Causa: <climatica / preco / mista> | laudo de profissional habilitado: <sim/nao> | ART/responsavel: <...>
- Enquadramento MP 1.376/2026 🟡 **PENDENTE** (Comissao Mista / conversao): <geral (2+ safras E >=30%) / excepcional (3+ safras E >=40% climatico) / nao enquadra>
## Ambiental
- Auto de infracao: <nº / orgao / data da ciencia / prazo de 20 dias> | embargo: <nº / poligono / coordenadas>
- Adesao ao PRA: <sim/nao> | **notificacao valida recebida? <sim/nao/data>** (o prazo de 1 ano so corre da notificacao)
- Termo de compromisso assinado: <sim/nao/data>
## Processos
- <nº CNJ> | <vara/comarca ou orgao> | <classe> | <polo> | <fase> | <ultima movimentacao>
## Prazos (fatais primeiro)
- <data fatal> | <ato> | <fonte: citacao, notificacao, transcricao, publicacao, auto> | <dias uteis [judicial] / corridos [adm]>
## Historico (append-only)
- <data> | <ato praticado> | <skill> | <resultado>
## Proximo passo
- <acao> ate <data>
```

## Metodologia
1. Ao abrir: preencher partes/lado, imovel, contratos, titulos e prazos conhecidos. Campo sem dado fica **"a confirmar"** — nunca preenchido por estimativa.
2. A cada ato: **acrescentar** linha no historico e atualizar Prazos e Proximo passo.
3. Nunca sobrescrever o historico (auditabilidade).
4. Devolver ao `agrario-master` um resumo de 3 a 5 linhas com o estado e o proximo prazo.

## Regras de ouro
- **Os quatro campos que mais decidem o caso:** modulos fiscais (mudam APP, RL, vistoria, impenhorabilidade e limite de credito), **hipotese de transferencia** (sub-rogacao x extincao), **data da notificacao do PRA** (sem ela o prazo de 1 ano nao corre) e **safras perdidas com percentual** (definem se a MP 1.376 se aplica e por qual regime).
- Registrar numero e data **exatamente como constam na fonte** (matricula, CCIR, CAR, CPR, auto de infracao, mandado).
- Modulo fiscal varia por municipio: registrar o numero de hectares usado **e a fonte**, nunca de memoria.

## Entrega obrigatoria final
- Arquivo de caso criado ou atualizado + resumo do estado (trilha ativa, proximo prazo fatal, pendencias documentais).

## Guard
Nao inventar dado do imovel, do titulo ou do processo. Area, modulos fiscais, numero de matricula e data de notificacao sao **fatos que sustentam ou derrubam a tese** — na ausencia, marcar "a confirmar" e rotear ao `validador-agrario`. Nao estimar prazo sem o marco inicial documentado.
