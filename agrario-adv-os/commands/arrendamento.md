---
description: Redige, revisa ou discute o contrato de arrendamento rural — prazos minimos, preco e reajuste, renovacao, sub-rogacao do adquirente, foro de eleicao pos-Lei 14.879/2024, acao revisional e consignacao em pagamento.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [contrato, prazo, preco, cultura e o que se pretende]
---

Voce foi acionado pelo comando `/arrendamento` do plugin agrario-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** entregar contrato ou peca de arrendamento sobre a lei vigente, sem clausula nula e sem prazo perdido.

## PROTOCOLO
1. **Acionar a skill `contrato-arrendamento-rural`** (redacao e analise). Preco, prazo e renovacao -> `preco-prazo-e-renovacao-do-arrendamento`. Revisional ou consignacao -> `revisao-e-consignacao-do-arrendamento`. Anexo: `estatuto-e-decreto-contratos-agrarios.md`.
2. **Sub-rogacao x extincao e HIPOTESE, nao escolha — identifique ANTES de responder:**
   - **Alienacao voluntaria** (venda, doacao) ou imposicao de onus real: **nao interrompe** o contrato, o adquirente fica **sub-rogado** (ET art. 92, §5º + Dec. art. 15).
   - **PERDA da propriedade** pelo arrendador (decisao judicial, execucao, eviccao, expropriacao): **extingue** o arrendamento, **sem** sub-rogacao (Dec. art. **26, VIII** + **REsp 2.187.412-MT**, 3a T, Nancy Andrighi, 10/02/2026, Info 879).
   - Nuance obrigatoria: **extincao nao e saida imediata** — o **art. 28 do Dec. 59.566** garante a permanencia "ate o **termino dos trabalhos que forem necessarios a colheita**".
3. **Renovacao — divergencia literal e viva, NAO resolver:** o ET 95, IV diz **"arrendador"** e o Dec. 22, §1º diz **"arrendatario"** como sujeito dos 30 dias. Declare como controverso na peca. E o **Dec. 22, §3º admite DUAS vias** de notificacao (RTD **ou** requerimento judicial) — a extrajudicial nao e a unica.
4. **Foro de eleicao:** o **CPC art. 63, §1º** (red. Lei 14.879/2024) exige **pertinencia territorial**, e o **§5º** tornou o juizo aleatorio **declinavel de oficio**. Clausula no padrao antigo e declinavel — reescrever.
5. **Tributacao:** IBS/CBS alcancam o arrendamento pela porta generica de "arrendamento de bem imovel"; o **redutor social de R$ 600/mes e SO residencial e nao socorre o arrendamento rural**. Detalhar por `tributacao-dos-contratos-agrarios`.
6. Fechar pela `suprema-corte-agraria` + `validador-agrario`.

**Skill a acionar:** `contrato-arrendamento-rural`.
