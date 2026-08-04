---
description: Conduz o despejo agrario — acao de despejo cumulada com cobranca e rescisao, tutela de urgencia, e a distincao entre extincao do contrato e direito de permanecer ate o fim da colheita.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [lado (arrendador ou arrendatario), fundamento da retomada e situacao da lavoura]
---

Voce foi acionado pelo comando `/despejo-agrario` do plugin agrario-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** retomar (ou resistir a retomada) sem atropelar a colheita nem o rito.

## PROTOCOLO
1. **Acionar a skill `despejo-agrario`**. Anexos: `estatuto-e-decreto-contratos-agrarios.md` e `cpc-agrario.md`.
2. **Fixar a hipotese ANTES da peca — e a distincao que decide o caso:**
   - **Alienacao voluntaria** ou onus real: **sub-rogacao**, o contrato segue com o adquirente (ET 92, §5º + Dec. 15) — **nao cabe despejo por esse fundamento**.
   - **PERDA da propriedade** (decisao judicial, execucao, eviccao, expropriacao): **extingue** o arrendamento, sem sub-rogacao (Dec. art. **26, VIII** + **REsp 2.187.412-MT**, 3a T, 10/02/2026, Info 879).
3. 🔴 **Extincao nao e saida imediata.** O **art. 28 do Dec. 59.566** assegura a permanencia "ate o **termino dos trabalhos que forem necessarios a colheita**" — formula mais larga que "ate o fim da colheita", e e exatamente o tempo extra que o arrendatario compra. Pedir ou deferir desocupacao imediata contra lavoura em pe e erro.
4. **Se houver posse disputada por coletivo**, a acao muda de rito: `possessorias-rurais-e-conflito-coletivo`. **CPC art. 178, III** — o **MP intervem obrigatoriamente** em litigios coletivos pela posse de **terra rural**. **Art. 565:** §4º os orgaos da politica agraria (INCRA, orgao fundiario estadual) podem ser intimados para a mediacao; §1º liminar nao executada em 1 ano volta a mediacao; **§5º o rito coletivo alcanca o litigio sobre PROPRIEDADE** — nao se escapa dele convertendo em reivindicatoria.
5. Se o arrendatario estiver em RJ ou execucao, encadear por `protocolo-p4-agrario` antes de ajuizar.
6. Fechar pela `suprema-corte-agraria` + `validador-agrario`.

**Skill a acionar:** `despejo-agrario`.
