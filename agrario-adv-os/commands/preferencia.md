---
description: Trabalha a preferencia do arrendatario nos dois lados — adjudicacao compulsoria para quem tinha o direito e foi preterido, e defesa do adquirente contra a pretensao de quem nao preenche o perfil de homem do campo.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [lado (arrendatario preterido ou adquirente) e perfil de exploracao do imovel]
---

Voce foi acionado pelo comando `/preferencia` do plugin agrario-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** medir o direito antes de afirma-lo — a preferencia perdida por excesso de confianca custa a causa.

## PROTOCOLO
1. Arrendatario preterido -> **`preferencia-do-arrendatario`**. Adquirente ou vendedor -> **`defesa-na-preferencia-adquirente`**. Anexo: `estatuto-e-decreto-contratos-agrarios.md`.
2. 🔴 **A preferencia NAO e automatica.** Exige o perfil de **"homem do campo"** — exploracao direta e pessoal, residencia no imovel, atividade familiar, funcao social (**Dec. 59.566/66, art. 38**). **REsp 1.447.082-TO** (3a T, 10/05/2016) afastou empresa rural de grande porte; **REsp 2.140.209** (3a T, Villas Boas Cueva, acordao publicado 08/09/2025) reafirmou e excluiu recorrentes que **nao residiam no imovel, tinham outros bens e eram empresarios agricolas**.
3. ⚠️ **O modelo treinado tende a afirmar a preferencia como direito quase incondicional — esse erro perde a causa.** Levante a prova do perfil (ou a falta dela) antes de escolher o polo.
4. **Em contrapartida, o registro do contrato na matricula e DISPENSAVEL** para exercer a preferencia (**AgRg no REsp 717.860-RS**, 3a T, 18/12/2014). Nao aceite a tese contraria como obstaculo.
5. Cruzar com `due-diligence-de-terras-rurais` quando houver aquisicao em curso, e com `usucapiao-rural-judicial-e-extrajudicial` se a posse for anterior ao contrato.
6. Fechar pela `suprema-corte-agraria` + `validador-agrario`.

**Skill a acionar:** `preferencia-do-arrendatario` (arrendatario) ou `defesa-na-preferencia-adquirente` (adquirente), conforme o lado.
