---
description: Diagnostica CAR e PRA e monta o termo de compromisso — adesao ao Programa de Regularizacao Ambiental pela regra da notificacao, areas consolidadas, APP e reserva legal, e a dispensa de licenciamento da agropecuaria.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [situacao do CAR, passivo de APP ou reserva legal e notificacao recebida]
---

Voce foi acionado pelo comando `/car-pra` do plugin agrario-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** regularizar pelo caminho vigente, sem entregar prazo que ja nao corre.

## PROTOCOLO
1. **Acionar a skill `car-pra-e-termo-de-compromisso`**. APP, reserva legal e area consolidada -> `app-reserva-legal-e-areas-consolidadas`. Licenciamento -> `licenciamento-e-dispensa-agropecuaria`. Anexo: `codigo-florestal-12651.md`.
2. 🔴 **O prazo de adesao ao PRA deixou de ser data de calendario.** Lei 12.651/2012, **art. 59, §2º, red. Lei 14.595/2023**: a adesao e requerida no prazo de **1 ano contado da NOTIFICACAO** pelo orgao competente, que previamente valida o cadastro e identifica passivos. **Sem notificacao valida, o prazo nao corre** — e a protecao do **§4º** (nao pode ser autuado por infracoes anteriores a **22/07/2008** em APP, reserva legal ou uso restrito) continua de pe.
3. **Nao confundir com o art. 29, §4º**, que fixa 31/12/2023 (acima de 4 MF) e 31/12/2025 (ate 4 MF) como limites de **inscricao no CAR** para ter **direito** a adesao — ambos ja vencidos. Sao coisas diferentes: um e inscricao, o outro e adesao.
4. **Licenciamento:** existe Lei Geral do Licenciamento em vigor e ela **dispensa a agropecuaria** — **Lei 15.190/2025**, art. 9º (cultivo agricola, pecuaria extensiva e semi-intensiva, pecuaria intensiva de pequeno porte e pesquisa agropecuaria), **condicionado a imovel "regular ou em regularizacao"**; a alinea que inclui **CAR pendente de homologacao** foi vetada e **restabelecida pela derrubada do veto** em 27/11/2025. ⚠️ **Quatro acoes no STF (ADIs 7913, 7916, 7919 e ADC 102), SEM liminar** — declarar a pendencia e rechecar na data do atendimento.
5. Se ja houver autuacao ou embargo, a via muda: `defesa-em-auto-de-infracao-ambiental` e `embargo-e-desembargo`.
6. Fechar pela `suprema-corte-agraria` + `validador-agrario`.

**Skill a acionar:** `car-pra-e-termo-de-compromisso`.
