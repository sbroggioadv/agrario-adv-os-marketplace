---
description: Defende o produtor no auto de infracao ambiental e no embargo — defesa administrativa, recurso, levantamento do embargo e a tese de que o embargo nao alcanca o imovel inteiro, so a area do ilicito.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [auto de infracao, orgao autuante, area embargada e prazo]
---

Voce foi acionado pelo comando `/embargo-ibama` do plugin agrario-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** defender no prazo, na esfera certa, sem citar dispositivo morto.

## PROTOCOLO
1. **Acionar a skill `defesa-em-auto-de-infracao-ambiental`**. Levantamento do embargo -> `embargo-e-desembargo`. Acordo -> `tac-e-responsabilidade-ambiental-rural`. Anexo: `ambiental-administrativo.md`.
2. 🔴 **NAO cite o art. 130 do Dec. 6.514/2008 nem seu paragrafo unico — foi REVOGADO inteiro pelo Dec. 11.080/2022.** A fonte de pesquisa lista o prazo de 10 dias do art. 130 **com selo ✅** e, no mesmo arquivo, declara o artigo revogado: **quando um item ✅ conflita com uma revogacao declarada, a revogacao vence e o item ✅ e o defeito.** Consequencia pratica a dizer ao cliente: **nao cabe recurso ao CONAMA**.
3. **Tese do embargo limitado a area do ilicito:** a ancora e **NORMATIVA — art. 15-A do Decreto 6.514/2008**, nao jurisprudencial. ⛔ **Nao citar o REsp 1.816.808/SP** (nao confirmado). E **enfrente o art. 16-A/2024**, que esta em tensao direta: sustente pela especialidade, proporcionalidade e correlacao com a infracao, mas **declare a existencia do art. 16-A** — ignora-lo entrega a peca a uma contestacao facil.
4. ⚠️ **Homonimo travado — existem TRES "art. 15-A" no corpus:** Dec. 6.514/2008 (embargo ambiental), **DL 3.365/41** (juros compensatorios na desapropriacao, via ADI 2.332) e **Lei 11.952/2009** (adimplemento financeiro na regularizacao fundiaria). Nomeie o diploma na propria linha; um grep cru devolve o ambiental primeiro.
5. **Tese de defesa de maior alcance hoje:** o **PRA** — o prazo de adesao deixou de ser data de calendario (Lei 12.651/2012, art. 59, §2º, red. Lei 14.595/2023: 1 ano contado da **notificacao** pelo orgao competente). **Sem notificacao valida, o prazo nao corre**, e a protecao do §4º continua de pe. Detalhar por `car-pra-e-termo-de-compromisso`.
6. Fechar pela `suprema-corte-agraria` + `validador-agrario`.

**Skill a acionar:** `defesa-em-auto-de-infracao-ambiental`.
