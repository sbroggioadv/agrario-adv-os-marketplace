---
name: regularizacao-fundiaria-rural
description: "Conduz a regularizacao fundiaria de ocupacao em terra publica federal pela Lei 11.952/2009 e, principalmente, a EXTINCAO das clausulas resolutivas de titulos antigos pelo art. 16-A (Lei 14.757/2023), com o roteiro de averbacao do Provimento CNJ 214/2026. Fixa os tres numeros que o mercado erra: marco temporal 22/07/2008, limite de 2.500 ha sem criterio de modulos fiscais, e o fato de que o STF NAO derrubou esse limite. Use quando o operador disser meu titulo tem clausula resolutiva, quero liberar a fazenda do INCRA, posso vender area titulada, ocupo terra da Uniao ha anos, quanto posso regularizar, preciso de vistoria, o STF nao derrubou os 2.500 hectares."
---

# REGULARIZACAO-FUNDIARIA-RURAL — titulo publico, clausula resolutiva e a liberacao

> Camada 4. Duas frentes: **titular a ocupacao** em terra publica federal, e **liberar do gravame** quem ja foi titulado e nao consegue vender nem dar em garantia. A segunda e a de maior demanda hoje — e a mais recente.

## Quando ativa / trilha
Trilha **terra/registral**, depois que a `due-diligence-de-terras-rurais` encontrar **titulo com clausula resolutiva**, **inalienabilidade averbada** ou **ocupacao sem titulo em area publica federal**.

**Fronteira que evita a skill errada:** aqui a origem e **publica e o caminho e administrativo**. Posse em area **particular** ou de origem desconhecida vai para `usucapiao-rural-judicial-e-extrajudicial`; duvida sobre **devoluta** vai para `terras-devolutas-e-discriminatoria`; REURB **urbana** nao e deste plugin.

## Anexos obrigatorios (context/)
- `context/registral-terras-e-estrangeiros.md` (**§3 Lei 11.952/2009 — grep "16-A" e leia a faixa**; §1 georreferenciamento; §8 armadilhas).
- `context/codigo-florestal-12651.md` (§5 CAR art. 29 — o CAR e **condicao** do art. 16-A — **grep "art. 29" e leia a faixa**).
- `context/tributacao-rural.md` (§11 art. 21) · `context/jurisprudencia-agraria.md` (§11 pendentes — selo ✅ antes de citar).

## Base legal ancorada

### 🔴 Os tres numeros que o mercado erra ✅
| Tema | Vigente | O erro que circula |
|---|---|---|
| **Marco temporal** | **22 de julho de 2008** (art. 5º, IV, red. **Lei 13.465/2017**) | "01/12/2004" (redacao original, superada) e "05/05/2014" (era da **MP 910/2019, vigencia ENCERRADA** — nunca virou direito) |
| **Limite de area** | **APENAS 2.500 ha** (art. 6º, §1º, red. Lei 13.465/2017) | "ate 15 modulos fiscais e 1.500 ha" — redacao **original**, revogada; a lei vigente **nao menciona modulo fiscal** neste dispositivo |
| **Constitucionalidade** | **art. 6º, §1º CONTINUA VIGENTE** | "o STF ja derrubou os 2.500 ha" — **NAO derrubou** (ver abaixo) |

### 🟡 ADIs contra a Lei 13.465/2017 — o julgamento NAO terminou / PENDENTE
⚠️ **ADIs 5.771, 5.787, 5.883 e 6.787** — **quatro** acoes, **PENDENTES / sem transito**. O **voto-vista do Min. Flavio Dino** (maio/2025) declarando inconstitucional o limite de 2.500 ha foi seguido de **destaque do Min. Gilmar Mendes**; o destaque foi **cancelado em 18/06/2026**, **incluido para 25/06/2026** e **RETIRADO DE PAUTA em 23/06/2026**.

> ⛔ Imprensa juridica e escritorios noticiaram o **voto** como se fosse **resultado**. **Repetir isso e erro grave.** Declare como **pendente** e trabalhe com o dispositivo **vigente** (art. 6º, §1º da Lei 11.952/2009 **continua vigente**).

### Lei 11.952/2009 — o que o anexo ancora (nao inventar o resto) ✅
Do corpus (`registral-terras-e-estrangeiros.md` §3) constam, com ancora:
- **Marco temporal:** **22/07/2008** (art. 5º, IV, red. Lei 13.465/2017).
- **Limite de area:** **apenas 2.500 ha** (art. 6º, §1º).
- **Vistoria previa:** **dispensada ate 4 modulos fiscais** (art. 13).
- **Clausulas resolutivas — art. 16-A** (Lei 14.757/2023): **extincao** das clausulas de titulos ate **25/06/2009**, **atendidas 3 condicoes** (o anexo **nao transcreve** o rol detalhado dos requisitos, vedacoes nem a liberacao ordinaria do art. 16 — **nao cite por memoria**; abra a lei e o `validador-agrario`).

> ⭐ **E de 2023 e e a via mais direta hoje** para destravar titulo antigo. O limite de **regularizacao** e por **area (2.500 ha)** — nao confunda com redacoes antigas em **modulos fiscais**.

### 🔴 A averbacao no Registro de Imoveis — Provimento CNJ 214/2026
Disciplina como averbar a extincao. O anexo ancora: requerimento ao Registrador com **5 documentos** e **registrador limitado a VERIFICACAO FORMAL** (sem analise de merito do cumprimento das obrigacoes). 🟡 **Os nomes dos cinco documentos e exigencias formais acessorias NAO estao no corpus** — confira no Provimento oficial antes de listar em peca.

🟡 **NAO cite numero de artigo do Provimento 214/2026** (nem do 216/2026): o **conteudo** (5 docs + verificacao formal) esta no anexo; a **numeracao de artigos, nao**. Cite o provimento pelo numero e ano.

## Passo a passo / o que produzir
1. **Qualificar** (AskUserQuestion, botoes): situacao — **ocupacao sem titulo · titulo com clausula resolutiva vigente · titulo ja liberado** · porte — **ate 4 MF · 4 a 15 MF · acima de 15 MF** · finalidade — **vender · dar em garantia · so regularizar**.
2. **Datar o titulo:** emitido **ate 25/06/2009**? Se sim, a rota preferencial e o **art. 16-A** (extincao das clausulas, com as **3 condicoes** da lei — confira o rol na fonte).
3. **Checar as 3 condicoes do art. 16-A** na lei/fonte primaria (o anexo so registra que sao tres). Falhando uma, a extincao **nao opera**.
4. **Sendo ocupacao sem titulo:** aplicar o **marco de 22/07/2008**, o teto de **2.500 ha** e a dispensa de vistoria ate **4 MF** (art. 13) — demais requisitos do ocupante: **abrir a lei**, nao inventar a partir do treino.
5. **Entregar:** parecer de viabilidade com quadro requisito -> documento -> selo · **requerimento de averbacao** com os **5 documentos** do Prov. 214/2026 (lista na fonte) · nota de pendencia sobre as **ADIs 5.771/5.787/5.883/6.787**.

## Postura honesta
- **A extincao das clausulas nao apaga, por si, todo passivo** — nao venda a liberacao registral como "ficha limpa" sem abrir a lei e o caso.
- ⚠️ **As ADIs 5.771, 5.787, 5.883 e 6.787 sao pendencia real / PENDENTE, nao formalidade.** O limite de 2.500 ha esta vigente **hoje** e pode nao estar amanha. Operacao de longo prazo apoiada nele registra o risco por escrito — e **reverifica antes de cada atendimento**.
- 🟡 **A confirmar, rotear ao `validador-agrario`:** **numeracao dos artigos dos Provimentos CNJ 214 e 216/2026** · o **§1º do art. 29 da Lei 6.383/76** (a redacao da MP 458/2009 nao prevaleceu — confira no compilado) · georreferenciamento **sub judice** (proc. **1086967-47.2025.4.01.3700**, JF/MA — fonte secundaria no corpus).
- ⛔ **Nunca escreva "15 modulos fiscais e 1.500 ha"** como limite, **nem** "o STF derrubou os 2.500 ha". Os dois derrubam a peca e a credibilidade do parecer.

## Cross-link soft + fechamento
Diagnostico do imovel -> `due-diligence-de-terras-rurais`. Memorial -> `georreferenciamento-e-certificacao`. Origem devoluta -> `terras-devolutas-e-discriminatoria`. Posse em area particular -> `usucapiao-rural-judicial-e-extrajudicial`. CAR e PRA -> C6. Garantia sobre a area liberada -> `garantias-do-credito-rural`. ITR -> `itr-e-tributacao-da-terra`. REURB **urbana** -> `direito-imobiliario-adv-os` (soft).

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
