---
name: renegociacao-mp-1376
description: "Enquadra o produtor na composicao de dividas da MP 1.376/2026 e entrega parecer de enquadramento, requerimento ao agente financeiro e roteiro do dossie de perda. Trata os DOIS regimes com gatilhos cumulativos (geral: 2+ safras E queda >=30%; excepcional: 3+ safras E queda >=40% por evento climatico), a segunda linha do art. 2º, a revisao de garantias nos dois sentidos e a responsabilidade solidaria do tecnico do laudo. Janela de 120 dias. Use quando o operador disser MP 1376, renegociacao de divida rural, composicao de dividas, o banco nao quer renegociar, perdi safra e preciso renegociar, enquadramento na nova linha, ate quando da pra contratar, /mp1376."
---

> **🖱️ Escolhas = botoes:** em pergunta de **lista fechada** (regime, linha, faixa, origem da perda) use **AskUserQuestion** — botoes clicaveis, max. 4 por pergunta.

# RENEGOCIACAO-MP-1376 — composicao de dividas na janela de 120 dias

> Camada 3, nucleo comercial. Entrega **parecer de enquadramento + requerimento ao agente financeiro + roteiro do dossie de perda**.

## Quando ativa / trilha
Divida rural ainda **componivel**. Entra pela `triagem-agraria`, apoia-se na `base-credito-rural-e-lei-do-agro`, consome o dossie de `prova-de-frustracao-de-safra-e-vistoria`.

⛔ **Filtro que vem ANTES de tudo:** operacao **encaminhada a Divida Ativa da Uniao** fica **FORA** (**art. 1º, §9º**). Pergunte primeiro — nao queime a janela num caso que a lei ja excluiu.

**Tres institutos distintos, nunca sinonimos:** **prorrogacao/alongamento** (MCR + Sumula 298) = `prorrogacao-de-divida-rural` · **composicao de dividas por nova linha** = esta skill · **securitizacao** = legislacao propria, 🟡 nao conferida. A **prorrogacao de 30 dias sem aditivo (art. 4º)** e desta MP e fica aqui.

## Anexos obrigatorios (context/)
- `context/mp-1376-2026.md` (§0 vigencia · §1 janela · §2 os dois regimes · §3 valvulas · §4-5 dividas e vedacoes · §6 art. 2º · §7 alavancas · §9 art. 9º — **grep o artigo e leia a faixa**).
- `context/lei-do-agro-e-cpr.md` (**art. 12 da Lei 8.929/94** — registro no BCB, requisito fatal do art. 6º desta MP).
- `context/rj-produtor-rural.md` (quadro de insolvencia) · `context/metodologia-agraria.md` (relogio do agro).

## Base legal ancorada ✅🔴

### Os DOIS regimes — gatilhos CUMULATIVOS, nunca "OU"
| | **Geral** (art. 1º, §1º + §4º) | **Excepcional** (art. 1º, §7º) |
|---|---|---|
| Safras com perda (2019-2025) | **2 ou mais** | **3 ou mais** |
| Queda da renda bruta esperada | **>= 30%** | **>= 40%** |
| Causa admitida | clima **ou** queda de **preco** (§2º) | **somente clima** |
| Pronaf / Pronamp / demais | **400 mil / 2 mi / 4 mi** | **500 mil / 2,5 mi / 8 mi** |
| Encargos financeiros da linha (a.a. sobre a operacao, art. 1º §4º II / §7º II) | **6 / 9 / 12%** | **5 / 8 / 11%** |
| Reembolso | ate **8 anos** | ate **10 anos** |

Ambos: perda **comprovada por laudo de profissional habilitado**; juros na carencia; **1ª amortizacao do principal 2 anos apos a contratacao**. **§7º, VI:** os limites do excepcional sao **cumulativos aos do §4º, I**.

🚨 **Queda de PRECO nao entra no §7º** — o rol do excepcional e exclusivamente climatico. "3 anos OU 40%" destroi o enquadramento: o conectivo e **E** nos dois regimes.

**Estourou o teto, ha valvula** (limites adicionais + **encargos financeiros a.a. da operacao adicional**): §5º Pronaf +**600 mil a 9% a.a.** · §6º Pronamp +**2 mi a 12% a.a.** · §7º IV Pronaf exc. +**500 mil a 8% a.a.** · §7º V Pronamp exc. +**1,5 mi a 11% a.a.**

### Quais dividas entram — art. 1º, caput
**I** custeio, comercializacao e industrializacao **renegociadas ou prorrogadas ate 31/05/2026** e **adimplentes na contratacao** · **II** as mesmas modalidades **contratadas ate 31/12/2025**, inadimplentes **desde 01/01/2024** e ainda em **31/05/2026** · **III** **parcelas de INVESTIMENTO** vencidas ou vincendas entre **01/01/2024 e 31/12/2026**, com dois requisitos **cumulativos** (contrato ate 31/12/2025 **e** a mesma janela de inadimplencia) · **IV** outras definidas pelo Executivo.

**Vedacoes (§8º):** **I** Fundo Social (art. 47-A da Lei 12.351/2010) · **II** MP 1.314/2025 — **com EXCECAO EXPRESSA** para operacoes com **recursos livres e direcionados**, preservado o **credito presumido** do art. 6º daquela MP. 🔴 **A vedacao da MP 1.314 nao e absoluta**; afirmar que e faz o cliente desistir de enquadramento viavel.

### ⭐ Art. 2º — a SEGUNDA linha, quase sempre esquecida
Mesmo beneficiario do art. 1º, §1º, quando a divida **ultrapassa os limites do art. 1º**. Recursos livres ou direcionados (LCA, Poupanca Rural). **§2º, I: encargos NAO controlados, prefixados ou pos-fixados, conforme negociacao entre as partes** — some a faixa de 5% a 12%; reembolso ate 8 anos, juros na carencia, 1ª amortizacao em 2 anos, contratacao em 120 dias. **§3º, II veda a MP 1.314 SEM a excecao do art. 1º, §8º, II.**

### As alavancas
- **Art. 3º, I** — **nao gera cadastro restritivo nem impede novo credito rural**: o argumento central contra a resistencia do banco. **II** — **nao abrange** o ja liquidado antes da publicacao, **inclusive por Proagro ou seguro**. E a trava.
- **Art. 4º** — **prorrogacao de ate 30 dias sem aditivo** para operacoes adimplentes em **14/07/2026** com vencimento em ate 30 dias da publicacao, observados **cumulativamente** os incisos I a III (caput do art. 1º; mutuario do §1º ou §7º **que solicite** uma das linhas; encargos de normalidade).
- **Art. 5º, paragrafo unico — DOIS incisos:** **I** reducao da garantia **em excesso**; **II** **ampliacao quando insuficiente**. ⚠️ Vender so o inciso I e vender o que a lei nao da — o banco pode exigir **reforco**. Declare os dois, por escrito.
- **Art. 6º** — o banco pode **adquirir CPR financeira** para liquidar CPR inadimplente emitida ate 31/12/2025, se **cumulativamente**: inadimplencia desde 01/01/2024 mantida em 31/05/2026 **e** CPR original **contratada para liquidar outra CPR**. ⚠️ **Requisito fatal: CPR registrada em entidade autorizada pelo BCB.** Sem registro, nao entra por esta porta.

### 🚨 Art. 9º — quem assina o laudo responde
**Caput** (conduta **dolosa** do produtor): perda imediata do beneficio · restituicao integral com encargos · **impedimento de contratar credito subvencionado por ate 5 anos**. **§1º: o profissional habilitado que emitir, assinar, homologar ou validar laudo falso responde SOLIDARIAMENTE pelos danos ao erario**, com comunicacao ao conselho profissional e responsabilizacao civil.

### A janela
**120 dias da publicacao (15/07/2026)** — repetido em **art. 1º, §4º, IV**, **art. 2º, §2º, III** e **art. 6º, p.u.**. 🟡 O *dies a quo* **nao esta explicito**: trabalhe com **11/11/2026 como data de seguranca**; o dia 12 so vale se o prazo correr do dia seguinte. **Nunca prometa o dia 12.**

## Passo a passo / o que produzir
1. **Filtrar (botoes):** foi para a **Divida Ativa da Uniao**? Se sim, pare e va para `prorrogacao-de-divida-rural` / `revisional-de-credito-rural`.
2. **Classificar a divida** pelo art. 1º, caput, com as datas de corte conferidas no contrato.
3. **Enquadrar o regime (botoes):** contar **safras com perda** e medir a **queda percentual**. Causa = queda de preco ⇒ **so o regime geral**.
4. **Testar o teto** da faixa; estourando, aplicar a **valvula** (§§5º, 6º, 7º IV-V) **antes** de migrar para o art. 2º — e entao comparar as portas: art. 1º (encargos tabelados, vedacao **com** excecao) x art. 2º (**negociados**, vedacao **sem** excecao).
5. **Montar o dossie de perda** e **comunicar por escrito ao tecnico** a responsabilidade solidaria do art. 9º, §1º.
6. **Redigir o requerimento ao agente financeiro** (nao ao juizo): qualificacao · operacoes a compor com numero e data · inciso do caput · regime e faixa · limite, encargo e prazo · **revisao de garantias (art. 5º, p.u., I)** · **art. 3º, I** · **art. 4º** se ha vencimento em 30 dias. Fechar com o **calendario da janela**.

## Postura honesta
- 🟡 **A MP esta em Comissao Mista, com emendas — PENDENTE** — pode ter sido **convertida, rejeitada ou caducado**. Recheque no Congresso e no Planalto **a cada atendimento** e refaca a conta dos 120 dias. Convertida, **prevalece a lei de conversao**.
- ⚠️ **A MP nao cria direito subjetivo a contratacao.** O art. 5º, caput, submete a operacao as **politicas internas** da instituicao, com risco avaliado **como operacao nova**. O banco pode negar: a MP da o enquadramento e as alavancas, nao a assinatura.
- 🟡 **"R$ 100 bilhoes" nao esta no texto da MP** — sinal de mercado, nao ancora juridica.
- 🟡 **Nao invente numero de Resolucao CMN** (a MP delega ao CMN; nenhuma foi verificada) nem **capitulo do MCR**. **MP 1.314/2025** so foi confirmada **por remissao** nesta MP — abra antes de citar.
- 🟡 **O fundo garantidor do art. 8º depende de regulamento** — nao prometa cobertura.
- ⚠️ **A MP nao trata de recuperacao judicial** — efeito sobre RJ em curso e **leitura**, nao comando legal.

## Cross-link e fechamento
Dossie -> `prova-de-frustracao-de-safra-e-vistoria`. Alongamento -> `prorrogacao-de-divida-rural`. Juros -> `revisional-de-credito-rural`. Execucao ajuizada -> `embargos-a-execucao-de-cpr`. Insolvencia -> `rj-produtor-rural-inicial`. Titulo, registro no BCB e garantias -> `cpr-emissao-e-formalizacao` · `garantias-do-credito-rural`. Relogio -> `calendario-safra-e-prazos-criticos`.

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
