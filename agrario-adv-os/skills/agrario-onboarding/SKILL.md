---
name: agrario-onboarding
description: "Wizard de configuracao do plugin agrario ao perfil do escritorio. Cria a pasta agrario/ com identidade (nome, OAB, escritorio, cidade, e-mail), o LADO em que o escritorio atua (produtor x credor/trading x adquirente/investidor), UF, tipo de exploracao, porte em modulos fiscais, tom das pecas e modo de fluxo. Usa context/metodologia-agraria.md para explicar o que o plugin faz e qual a verdade vigente de 2026. Use quando o operador disser configurar agrario, instalar agrario, primeira vez, comecar, onboarding agrario, /start-agrario."
---

> **🖱️ Escolhas = botoes:** em campos de **lista fechada** (lado, UF, tipo de exploracao, porte, tom, modo de fluxo, atualizar/recriar, sim/nao) use a ferramenta **AskUserQuestion** para mostrar **botoes clicaveis** (max. 4 por pergunta; se houver mais opcoes, divida em 2 perguntas). **Texto livre** (nome, OAB, escritorio, cidade, e-mail) segue como pergunta digitada normal.

# AGRARIO ONBOARDING

> Camada 0. Wizard de configuracao inicial. Linguagem acolhedora, sem jargao. Configura o plugin ao perfil do escritorio e explica, em poucas frases, o que ele cobre.

## Anexos obrigatorios (context/)
- `context/metodologia-agraria.md` — para explicar o mapa das camadas, a arvore de triagem e as regras de ouro — **grep + ler a faixa**.

## Objetivo
Configurar o plugin ao escritorio em poucas perguntas e deixar claro, em linguagem simples, o que ele cobre: contratos agrarios, credito rural e CPR, divida e recuperacao judicial do produtor, terras e registral rural, desapropriacao, defesa ambiental administrativa e o contencioso possessorio — sempre com a lei **vigente 2026**.

## Quando ativar
`/start-agrario`, "configurar agrario", "instalar agrario", "primeira vez", "onboarding agrario". Cria ou atualiza `agrario/perfil.md` no diretorio de trabalho.

## Regras do wizard
Uma pergunta por vez, acolhedor. Lista fechada = **AskUserQuestion** (botoes). Texto livre = pergunta digitada. Ao fim, gravar e confirmar o que foi gravado.

## Blocos de pergunta
1. **Identidade (texto livre):** nome, OAB (numero/UF), escritorio, cidade, e-mail.
2. **Lado em que atua (botoes) — define a postura das pecas:** Produtor rural (devedor/arrendatario) · Credor, banco ou trading · Adquirente ou investidor em terra · Os tres, conforme o caso.
3. **UF principal (botoes, em 2 rodadas):** 1a rodada por regiao (Centro-Oeste · Sul · Sudeste · Norte/Nordeste); 2a rodada com as UFs da regiao escolhida. A UF importa para modulo fiscal, terras devolutas e orgao ambiental estadual.
4. **Tipo de exploracao (botoes, multi):** Lavoura (graos, cana, algodao) · Pecuaria · Integracao (aves/suinos, Lei 13.288/2016) · Misto/agroindustria.
5. **Porte em modulos fiscais (botoes):** Ate 4 MF (pequena propriedade) · Mais de 4 ate 15 MF · Acima de 15 MF · Nao sei / varia por cliente. **Explicar em 1 linha:** modulo fiscal e medida em hectares que muda por municipio; ate 4 MF muda regra de APP, RL, vistoria e impenhorabilidade.
6. **Tom das pecas (botoes):** Tecnico-formal · Direto e objetivo · Combativo.
7. **Modo de fluxo (botoes):** Checkpoint (confirma a cada etapa) · Continuo.

## Explicacao do plugin (apresentar ao fim, em 4 frases)
- **O que cobre:** do **contrato** (arrendamento, parceria, barter, integracao, safra) ao **credito e a divida** (CPR, cedula rural, garantias, execucao, embargos, revisional, prorrogacao, MP 1.376/2026 e recuperacao judicial do produtor), passando por **terra e registral** (due diligence, georreferenciamento, usucapiao rural, regularizacao fundiaria, ITR), **desapropriacao**, **ambiental do agro** (CAR/PRA, auto de infracao, embargo, licenciamento) e o **contencioso possessorio e do contrato** (despejo, preferencia, consignacao), com recursos ate STJ/STF.
- **A verdade vigente:** trabalha com a lei de 2026 — quotas de parceria do **ET art. 96, VI (2007)** e nao do decreto de 1966; **MP 1.376/2026** com os dois regimes e a janela de contratacao de **120 dias** 🟡 **PENDENTE (Comissao Mista)**; **PRA por notificacao**, nao por data de calendario; **Lei 15.190/2025** dispensando a agropecuaria do licenciamento 🟡 **ADIs 7913/7916/7919 + ADC 102 sem liminar, merito pautado**.
- **Postura honesta:** declara os rachas (CPR fisica x cedula financeira na recuperacao judicial; 🟡 **ADIs 5.771/5.787/5.883/6.787** da Lei 13.465/2017 **PENDENTES/nao julgadas**; ⚠️ georreferenciamento **sub judice** — JF/MA proc. **1086967-47.2025.4.01.3700**) e nunca vende "alongamento automatico" nem "preferencia como direito incondicional" — sao as duas promessas que fazem a peca perder.
- **Como usar:** a partir daqui basta descrever o caso — a porta unica (`agrario-master` -> `triagem-agraria`) roteia; a **1a pergunta sera sempre "ha divida vencida ou execucao em curso?"**, porque prazo de credito nao espera.

## Gravacao
Criar `agrario/perfil.md`. Se ja existir, perguntar por botoes: **Atualizar** ou **Recriar**.

## Entrega obrigatoria final
- `agrario/perfil.md` gravado + resumo da configuracao + sugestao do primeiro comando (`/triagem-agraria` ou `/agrario-master`).

## Guard
Nao inventar dado do operador (nome, OAB, escritorio, e-mail) — se nao foi respondido, deixar em branco. O lado escolhido e **preferencia, nao trava**: a `triagem-agraria` roteia qualquer caso que chegar, inclusive do lado oposto. Nao prometer resultado nem antecipar tese na explicacao — a postura honesta vale ja no onboarding.
