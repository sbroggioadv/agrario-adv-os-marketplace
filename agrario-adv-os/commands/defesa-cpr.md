---
description: Defende o produtor executado em CPR e cedula de credito rural — embargos a execucao com a municao do CPC 917, excecao de pre-executividade, impenhorabilidade da pequena propriedade e do maquinario agricola, e a distincao entre CPR fisica e financeira.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [titulo executado, valor, garantias e fase da execucao]
---

Voce foi acionado pelo comando `/defesa-cpr` do plugin agrario-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** defender na via correta, no prazo, com os embargos ja instruidos.

## PROTOCOLO
1. Conferir a fase e a via com `execucao-de-cpr-e-cedula-rural`; a defesa vai por **`embargos-a-execucao-de-cpr`**. Anexos: `lei-do-agro-e-cpr.md` e `cpc-agrario.md`.
2. **Municao do CPC (grep o artigo no anexo):** **art. 917, §2º, III** (execucao por quantia certa de CPR **fisica** = "modo diferente do titulo") e **IV** (financiador que **nao liberou o custeio** e executa). **Armadilha do mesmo artigo: §§3º-4º — alegar excesso sem planilha e rejeicao liminar.**
3. **Impenhorabilidade — a excecao que atinge a fazenda e o §1º do art. 833, NAO o §2º.** O §2º excepciona so os incisos IV e X (salarios e poupanca) e nao toca a pequena propriedade rural. **Pequena propriedade e ATE 4 modulos fiscais, sem piso** — nao existe "de 1 a 4". O **§3º** protege equipamentos, implementos e maquinas agricolas de **pessoa fisica ou empresa individual produtora rural** (sociedade empresaria fica de fora), e a excecao e **CUMULATIVA**: financiado **E** vinculado em garantia — ler "E" como "ou" entrega o maquinario do cliente. **Art. 834:** terra protegida nao e safra protegida — frutos e rendimentos (safra, renda do arrendamento) podem ser penhorados a falta de outros bens.
4. **Tema 1.234/STJ pos o onus de provar a exploracao familiar no EXECUTADO** — os embargos nascem instruidos: CCIR/CAR e modulos fiscais, prova de exploracao familiar, e o contrato de credito para mostrar que a divida nao e de aquisicao. Garantia real sem divida de aquisicao sai do §1º e vira jurisprudencia: a ancora e o **REsp 2.233.886-RS**, **nunca o Tema 961/STF** (que resolve pluralidade de terrenos).
5. **Art. 784 do CPC segue 🟡:** nenhum inciso nomeia cedula, CPR ou rural — a executividade vem de lei especial (8.929/94 e DL 167/67). **Cite o artigo, nunca o inciso.**
6. Se houver concurso, cruzar com `rj-sujeicao-de-creditos-agro` e declarar o racha (CPR fisica e barter extraconcursais x TJ/GO reconhecendo cedula rural financeira como concursal).
7. Fechar pela `suprema-corte-agraria` + `validador-agrario`.

**Skill a acionar:** `embargos-a-execucao-de-cpr`.
