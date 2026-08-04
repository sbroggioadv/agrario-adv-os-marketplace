---
description: Conduz a desapropriacao para reforma agraria e a desapropriacao indireta — defesa na vistoria e no laudo de produtividade, rito da LC 76/93 e contestacao, indenizacao em TDA com juros e honorarios, e nulidades do processo expropriatorio.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [fase (vistoria, acao, indenizacao) e regime (reforma agraria ou apossamento comum)]
---

Voce foi acionado pelo comando `/desapropriacao` do plugin agrario-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** atacar na fase certa, sob o regime certo — regra de reforma agraria aplicada a apossamento comum e transplante indevido.

## PROTOCOLO
1. **Declare o REGIME antes de escolher a skill.** Reforma agraria (INCRA) e apossamento comum (ex.: estrada municipal) **nao seguem a mesma regua** — o **art. 12 da Lei 8.629/93 governa so a primeira**. Anexos: `lei-8629-93-e-cf-184-191.md`, `lc-76-93-desapropriacao.md`, `jurisprudencia-agraria.md`.
2. **Rota por fase:** vistoria e improdutividade -> `defesa-na-vistoria-e-laudo-de-produtividade`. Acao expropriatoria -> `rito-lc-76-93-e-contestacao`. Valor, TDA, juros e honorarios -> `indenizacao-tda-juros-e-honorarios`. Vicios do procedimento -> `nulidades-do-processo-expropriatorio`. Apossamento sem processo -> `desapropriacao-indireta`.
3. **Municao da vistoria:** **laudo de GUT/GEE com mais de 5 anos deve ser atualizado a pedido do proprietario** — Lei 8.629/93, **art. 6º, §9º, red. Lei 14.757/2023**, a alteracao mais recente da lei. Transforma "laudo antigo" em **direito subjetivo expresso**. Indices: **GUT >= 80%** (§1º) e **GEE >= 100%** (§2º); **art. 7º** exige projeto tecnico aprovado **6 meses antes da comunicacao da vistoria**.
4. **MP na desapropriacao — TRES regimes no mesmo dominio, nao troque:** **obrigatorio** na reforma agraria · **inexistente** na desapropriacao comum, direta ou indireta · e a hipotese propria do **CPC 178, III** (litigio coletivo pela posse). Trocar dois deles produz preliminar inexistente ou nulidade nao arguida.
5. **Juros compensatorios:** a ancora e o **art. 15-A do DL 3.365/41** (⚠️ homonimo — nao confundir com o art. 15-A do Dec. 6.514/2008, do embargo ambiental, nem com o da Lei 11.952/2009). **Declare a tensao** entre o **Tema 280/STJ** (improdutividade nao afasta juros) e a **ADI 2.332**, que declarou constitucionais os §§1º e 2º (**GUT e GEE iguais a zero afastam os juros**). As Sumulas 12, 70 e 102 valem so ate 12/01/2000.
6. ⚠️ **Gap declarado:** a **LC 76/93 nao foi lida integralmente** — a camada se apoia na CF 184, §3º e na jurisprudencia ✅. Nao invente artigo da LC.
7. Fechar pela `suprema-corte-agraria` + `validador-agrario`.

**Skill a acionar:** `defesa-na-vistoria-e-laudo-de-produtividade`, `rito-lc-76-93-e-contestacao`, `indenizacao-tda-juros-e-honorarios`, `nulidades-do-processo-expropriatorio` ou `desapropriacao-indireta`, conforme a fase e o regime.
