---
name: triagem-agraria
description: "Classifica a demanda agraria e roteia para as skills certas. A pergunta CRITICA e a primeira: ha divida vencida ou execucao em curso? Se sim, a trilha entra pela camada de credito, divida e insolvencia antes de qualquer outra. Depois define uma das seis trilhas (divida/insolvencia, contrato, terra/registral, ambiental, desapropriacao, possessoria), o lado (produtor x credor x adquirente), a hipotese (alienacao voluntaria x perda da propriedade) e o prazo em curso. Use quando o operador descrever uma situacao rural e nao souber o caminho, ou disser triagem, qual o caminho, que peca eu uso, por onde comeco, recebi uma citacao, o banco executou, /triagem-agraria."
---

> **🖱️ Escolhas = botoes:** nas perguntas de **lista fechada** (ha divida? trilha, lado, hipotese, via) use a ferramenta **AskUserQuestion** para mostrar **botoes clicaveis** (max. 4 por pergunta; se houver mais, divida em 2).

# TRIAGEM-AGRARIA

> Camada 0. Porta de classificacao, chamada pelo `agrario-master` no inicio de todo caso. Define **divida primeiro**, depois trilha, lado, hipotese e prazo.

## Anexos obrigatorios (context/)
- `context/metodologia-agraria.md` — mapa das camadas + arvore de triagem — **grep + ler a faixa**.
- `context/mp-1376-2026.md` — janela de 120 dias da **MP 1.376/2026** 🟡 **pendente** em Comissao Mista (**pode caducar ou ser alterada**).

## Objetivo
Em poucas perguntas devolver: **trilha + lado + hipotese + skill(s) alvo + prazo em curso**, e passar o handoff para o `agrario-master`.

## Quando ativar
O operador descreve o caso sem saber o caminho, pergunta "que peca eu uso", "por onde comeco", "vale a pena entrar", ou o `agrario-master` abre um caso novo.

## Primeira definicao — a DIVIDA (sempre, e critica)
**Pergunta 1 (botoes): ha divida rural vencida, titulo protestado, execucao, busca e apreensao ou consolidacao extrajudicial em curso?**
- **Sim, ja ha acao/execucao** -> entra pela **C3** imediatamente: `embargos-a-execucao-de-cpr` (produtor) ou `execucao-de-cpr-e-cedula-rural` (credor); apoio de `garantias-do-credito-rural` e `patrimonio-rural-em-afetacao-e-cir`.
- **Sim, mas ainda extrajudicial** -> **filtrar ANTES: a operacao ja foi encaminhada a Divida Ativa da Uniao?** Se sim, a linha da MP 1.376 **nao se aplica** (art. 1º, §9º) — nao queimar a janela de 120 dias num caso que a lei ja excluiu; seguir por `prorrogacao-de-divida-rural` e `revisional-de-credito-rural`. Se nao -> `prorrogacao-de-divida-rural` · `renegociacao-mp-1376` (janela de **120 dias**, ~11/11/2026; 🟡 MP 1.376 **pendente** em Comissao Mista — **pode caducar ou ser alterada**) · `revisional-de-credito-rural` · `prova-de-frustracao-de-safra-e-vistoria` (o dossie de perda alimenta as tres).
- **Sim, e o quadro e de insolvencia** -> `rj-produtor-rural-inicial` (devedor) · `rj-produtor-defesa-do-credor` (credor) · `rj-sujeicao-de-creditos-agro` (quem entra e quem fica de fora).
- **Nao ha divida** -> seguir para a trilha (tabela abaixo).
> Errar essa pergunta custa prazo: execucao, purgacao e a janela da **MP 1.376/2026** 🟡 **pendente** (Comissao Mista; **pode caducar ou ser alterada**) correm enquanto se discute contrato.

## Tabela de roteamento (trilha -> skill alvo)
1. **CONTRATO** ("vou arrendar", "quero fazer parceria", "barter", "integracao de aves/suinos", "quanto posso cobrar", "quero renovar") -> `contrato-arrendamento-rural` · `preco-prazo-e-renovacao-do-arrendamento` · `contrato-parceria-rural` · `descaracterizacao-e-figuras-atipicas` · `contrato-integracao-vertical` · `contrato-barter` · `compra-venda-de-safra-e-armazenagem` · `tributacao-dos-contratos-agrarios` (IBS/CBS).
2. **TERRA E REGISTRAL** ("vou comprar fazenda", "matricula", "CCIR", "georreferenciamento", "usucapiao", "terra devoluta", "comprador estrangeiro", "ITR") -> `due-diligence-de-terras-rurais` · `georreferenciamento-e-certificacao` · `usucapiao-rural-judicial-e-extrajudicial` · `regularizacao-fundiaria-rural` · `terras-devolutas-e-discriminatoria` · `aquisicao-de-terra-por-estrangeiro` · `itr-e-tributacao-da-terra`.
3. **AMBIENTAL** ("recebi auto de infracao do IBAMA", "area embargada", "CAR pendente", "preciso aderir ao PRA", "reserva legal", "APP", "exigiram licenca") -> `defesa-em-auto-de-infracao-ambiental` (**prazo de 20 dias**) · `embargo-e-desembargo` · `car-pra-e-termo-de-compromisso` · `app-reserva-legal-e-areas-consolidadas` · `licenciamento-e-dispensa-agropecuaria` · `tac-e-responsabilidade-ambiental-rural`.
4. **DESAPROPRIACAO** ("o INCRA vistoriou", "publicaram decreto", "laudo de produtividade", "indenizacao em TDA", "ocuparam e nunca pagaram") -> `defesa-na-vistoria-e-laudo-de-produtividade` · `rito-lc-76-93-e-contestacao` · `indenizacao-tda-juros-e-honorarios` · `nulidades-do-processo-expropriatorio` · `desapropriacao-indireta`.
5. **POSSESSORIA E DO CONTRATO** ("quero retomar a area", "o arrendatario nao paga", "venderam e eu tinha preferencia", "invadiram", "a cota cobrada e abusiva") -> `despejo-agrario` · `preferencia-do-arrendatario` · `defesa-na-preferencia-adquirente` · `revisao-e-consignacao-do-arrendamento` · `possessorias-rurais-e-conflito-coletivo`.
6. **CONSULTIVO E RECURSO** ("vale entrar?", "qual a chance?", "o que vence primeiro?", "recorrer da sentenca") -> `parecer-agrario` · `calendario-safra-e-prazos-criticos` · `protocolo-p4-agrario` (cruzamento) · C8: `apelacao-e-agravo-agrario` · `embargos-de-declaracao-agrario` · `recursos-excepcionais-agro` · `contrarrazoes-e-agravos-excepcionais`.

## Perguntas de fechamento (botoes)
- **Lado:** produtor/arrendatario · credor, banco ou trading · adquirente/investidor.
- **Hipotese (so quando ha transferencia do imovel):** **alienacao voluntaria** (venda, doacao, onus real ⇒ sub-rogacao do adquirente) x **perda da propriedade** (decisao judicial, execucao, eviccao, expropriacao ⇒ **extincao** do arrendamento, sem sub-rogacao). Nunca aplicar uma pela outra.
- **Via:** administrativa (agente financeiro, orgao ambiental, INCRA, cartorio) x judicial.

## Gestao obrigatoria (sempre, antes da peca)
Toda peca passa pela fundacao C1 (`base-estatuto-da-terra` · `base-funcao-social-e-reforma-agraria` · `base-credito-rural-e-lei-do-agro` · `base-processual-agraria` · `jurisprudencia-agraria`) e o prazo e conferido em `calendario-safra-e-prazos-criticos`.

## Entrega obrigatoria final
- Trilha + lado + hipotese + via + skill(s) alvo + prazo em curso, em 3 a 5 linhas, e o handoff para o `agrario-master`.

## Guard
Nao redigir peca aqui — so classificar e rotear. Se houver divida vencida ou execucao, ela entra na frente, mesmo que o operador tenha perguntado sobre contrato. Demanda mista (ex.: despejo do arrendatario que pediu recuperacao judicial; embargo ambiental que trava o credito) sai como **lista ordenada** para o master encadear via `protocolo-p4-agrario`. Na duvida da hipotese, perguntar de novo — a hipotese manda na peca.
