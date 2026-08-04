---
name: due-diligence-de-terras-rurais
description: "Monta o relatorio de due diligence de imovel rural antes de comprar, financiar, arrendar, hipotecar ou integralizar em holding: matricula, CCIR e CNIR, quitacao de ITR dos cinco exercicios, georreferenciamento, CAR e passivo ambiental, embargos, contratos agrarios vigentes e acoes. Fecha nos dois impeditivos que anulam o negocio de verdade — falta de CCIR (Lei 4.947/66 art. 22 §1º) e nacionalidade estrangeira no polo adquirente — e separa o que e NULIDADE do que e mera irregularidade administrativa. Use quando o operador disser due diligence de fazenda, vou comprar uma area rural, analise essa matricula, o cliente vai dar a fazenda em garantia, checklist de compra de terra, o que preciso pedir antes de assinar, essa fazenda tem pendencia, posso confiar no CCIR, a area do CAR nao bate com a matricula."
---

# DUE-DILIGENCE-DE-TERRAS-RURAIS — o relatorio que impede o negocio nulo

> Camada 4. Consultivo de ticket alto. Nao litiga: **fotografa o imovel** e devolve o que trava a assinatura. O erro que esta skill existe para impedir e o mais caro do agro: fechar a compra e descobrir depois que o ato **era nulo desde a origem** — nao caro de consertar, **impossivel**.

## Quando ativa / trilha
Primeira skill da trilha **terra/registral** da `triagem-agraria`, e pre-requisito de qualquer operacao dominial. Roda **antes** de `contrato-arrendamento-rural`, de `garantias-do-credito-rural` e de qualquer estruturacao patrimonial.

**Fronteira que evita a skill errada:** aqui se **diagnostica**; quem **conserta** e a skill do eixo — georreferenciamento pendente vai para `georreferenciamento-e-certificacao`, titulo com clausula resolutiva vai para `regularizacao-fundiaria-rural`, duvida de dominio publico vai para `terras-devolutas-e-discriminatoria`.

## Anexos obrigatorios (context/)
- `context/registral-terras-e-estrangeiros.md` (§2 CCIR/CNIR — **grep "22" e leia a faixa**; §1 georreferenciamento; §5 estrangeiros; §8 armadilhas).
- `context/tributacao-rural.md` (§11 **arts. 20 e 21** — **grep "art. 21" e leia a faixa**; §8 area tributavel).
- `context/codigo-florestal-12651.md` (§5 CAR art. 29 · §6 PRA art. 59 §2º — **grep o artigo e leia a faixa**).
- `context/ambiental-administrativo.md` (§6 embargo de area) · `context/cpc-agrario.md` (**art. 60**, imovel que cruza divisa — **grep "art. 60"**) · `context/jurisprudencia-agraria.md` (selo ✅ antes de citar precedente).

## Base legal ancorada

### 🚨 O impeditivo nº 1 — sem CCIR o ato e NULO, nao irregular ✅
**Lei 4.947/66, art. 22, §1º**, verbatim: sem apresentacao do Certificado de Cadastro nao se pode, **"sob pena de nulidade, desmembrar, arrendar, hipotecar, vender ou prometer em venda imoveis rurais"**. Redacao de 1966, **nunca alterada**. Espelho contratual no **art. 9º do Dec. 59.566/66**.
- **§2º** — em sucessao *causa mortis*, **nenhuma partilha** se homologa sem o Certificado.
- **§3º** — o CCIR se apresenta **sempre acompanhado da prova de quitacao do ITR dos ultimos CINCO exercicios** (red. Lei 10.267/2001).
- **§6º** — os servicos notariais mencionam na escritura **cinco dados** do CCIR: codigo do imovel, nome do detentor, ⭐ **nacionalidade do detentor**, denominacao e localizacao.
- **§§7º e 8º** — fluxo mensal registro <-> INCRA (inclusive reserva legal e RPPN), com averbacao de oficio do codigo.

⭐ **O inciso III do §6º e o gancho registral do controle de terras por estrangeiro** — e por isso que nacionalidade entra na DD, nao so no consultivo.

### O gemeo fiscal — ITR trava cartorio e credito ✅
**Lei 9.393/96, art. 21:** e **obrigatoria** a comprovacao do pagamento do ITR dos **cinco ultimos exercicios** para praticar os atos dos **arts. 167 e 168 da Lei 6.015/73**; o paragrafo unico impoe **responsabilidade solidaria dos serventuarios** (CTN 134). **Art. 20:** a concessao de **incentivos fiscais e de credito rural**, e a constituicao das garantias, ficam condicionadas a essa mesma quitacao — **dispensada no PRONAF**.

> ⭐ CCIR e quitacao de ITR **andam juntos no balcao**. Faltando um, o negocio nao passa.

### ⛔ Cadastro NAO e titulo — a confusao que sustenta fraude ✅
O **CCIR** comprova **regularidade cadastral**; os dados sao **declaratorios e exclusivamente cadastrais, nao legitimam dominio nem posse** (INCRA). O **CAR** idem: **Lei 12.651/2012, art. 29, §2º** — o cadastramento **"nao sera considerado titulo"**. Cadastro (INCRA/SNCR, RFB/CAFIR) e registro (folio real) sao universos distintos: quem apresenta CCIR e CAR **nao provou ser dono**. **CNIR** — Dec. 4.449/2002, **art. 7º, §6º**: o codigo unico do CNIR **e o codigo do CCIR**; **art. 4º**, comunicacao mensal do registrador ate o **trigesimo dia do mes subsequente**.

### 🔴 Georreferenciamento — as 4 declaracoes, sem cravar 2029
O eixo mais perigoso do relatorio. **Nao afirme "2029" como incontroverso**: faca as **4 declaracoes** (Dec. 12.689/2025 unifica o prazo · 🟡 **sub judice** liminar noticiada no proc. **1086967-47.2025.4.01.3700** (JF/MA), fonte secundaria, **nao confirmada em primaria** · via do CNJ, **Prov. 195/2025**, em que no registral o levantamento **permanece exigivel** · **verificar na data do atendimento**). O bloco integral e da `georreferenciamento-e-certificacao` — **nao o reproduza aqui**.

### Os eixos do relatorio — 8 linhas, cada uma com sua ancora ✅
| # | Eixo | O que se pede | Ancora |
|---|---|---|---|
| 1 | **Dominial** | matricula atualizada, onus, penhoras, indisponibilidade | LRP; `terras-devolutas-e-discriminatoria` se houver duvida de origem |
| 2 | **Cadastral** | CCIR do exercicio corrente (validade **anual**), CNIR | L4947 art. 22 §1º ✅ |
| 3 | **Fiscal** | ITR **5 exercicios**, DIAT, area tributavel declarada | L9393 arts. 20 e 21 ✅ |
| 4 | **Geodesico** | memorial certificado no SIGEF; sobreposicao de poligonal | LRP 176 §§3º-5º 🔴 |
| 5 | **Ambiental** | CAR ativo, RL averbada ou no CAR, APP, PRA, embargos, autos | L12651 arts. 29 e 59 §2º |
| 6 | **Contratual** | arrendamento ou parceria vigentes, **preferencia** do arrendatario, comodato | ET 92 §§3º-5º |
| 7 | **Judicial** | acoes reais, possessorias, execucoes, discriminatoria, RJ do vendedor | CPC 47; **art. 60** se cruza divisa |
| 8 | **Subjetivo** | qualificacao das partes, **nacionalidade**, regime de bens, poderes | L5709 art. 15; L4947 art. 22 §6º, III |

⚠️ **Imovel em mais de um Estado ou comarca:** o juizo **prevento** estende a competencia sobre a **totalidade do imovel** (**CPC art. 60**). O dispositivo resolve **competencia territorial**, nao confunde matriculas com imoveis distintos no cartorio.

## Passo a passo / o que produzir
1. **Qualificar** (AskUserQuestion, botoes): lado do cliente — **comprador · vendedor · credor/financiador · investidor** · finalidade — **compra e venda · garantia real · arrendamento · integralizacao em holding**.
2. **Rodar os 8 eixos** e marcar cada um com **verde / amarelo / vermelho**, citando o documento lido (nao a suposicao).
3. **Separar NULIDADE de irregularidade:** falta de CCIR e aquisicao por estrangeiro fora da lei sao **nulidade de pleno direito**; CAR desatualizado, DIAT com erro e georreferenciamento pendente sao **saneaveis** — e essa distincao e o que define se o negocio para ou anda.
4. **Cruzar area:** matricula x CCIR x CAR x DIAT. Divergencia **nao e detalhe**: ela decide retificacao, ITR e limite de regularizacao.
5. **Rotear cada vermelho** a skill do eixo e fixar prazo de saneamento.
6. **Entregar o relatorio:** identificacao do imovel · quadro dos 8 eixos com semaforo e fonte · lista de impeditivos de nulidade · lista de saneaveis com prazo · condicoes precedentes sugeridas para o contrato · selo (✅ / 🟡 / 🔴) por item.

## Postura honesta
- **A DD nao cria dominio.** Ela mede risco: cadeia dominial viciada na origem nao se conserta com CCIR, CAR e ITR em dia — se a duvida for de **terra devoluta**, o eixo 1 e que manda, e a resposta pode ser "nao compre".
- **Certidao negativa nao e certidao de inexistencia.** Ela cobre o distribuidor consultado, no periodo consultado. Amplie comarcas quando o imovel cruza divisa (**CPC 60**) e quando o vendedor tem domicilio diverso.
- 🟡 **A confirmar, rotear ao `validador-agrario`:** **RPPN** como area nao tributavel do ITR · **IN RFB 2.330/2026** nao aberta · numero de artigo dos **Provimentos CNJ 214 e 216/2026** (conteudo seguro, **numeracao nao conferida**) · artigo do **Prov. CNJ 149/2023**.
- ⛔ **Nao trate CCIR ou CAR como prova de propriedade** e **nao prometa** que a DD "garante" o negocio: ela documenta o que foi visto na data em que foi visto.

## Cross-link soft + fechamento
Georreferenciamento -> `georreferenciamento-e-certificacao`. Titulo com clausula resolutiva -> `regularizacao-fundiaria-rural`. Origem duvidosa -> `terras-devolutas-e-discriminatoria`. Adquirente estrangeiro -> `aquisicao-de-terra-por-estrangeiro`. ITR e area tributavel -> `itr-e-tributacao-da-terra`. Posse sem titulo -> `usucapiao-rural-judicial-e-extrajudicial`. CAR, PRA e embargo -> C6. Arrendamento vigente e preferencia -> `contrato-arrendamento-rural` e `preferencia-do-arrendatario`. Garantia sobre o imovel -> `garantias-do-credito-rural`. Registral **urbano** -> `direito-imobiliario-adv-os`; estrutura societaria -> `holding-architect` (soft).

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
