---
description: Conduz a recuperacao judicial do produtor rural — inicial com o dossie probatorio territorial do Provimento CNJ 216/2026, defesa do credor, e a sujeicao ou extraconcursalidade dos creditos do agro (CPR fisica, barter, cedula rural).
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [lado (devedor ou credor), bienio do art. 48, dividas e garantias]
---

Voce foi acionado pelo comando `/rj-produtor` do plugin agrario-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** posicionar o cliente no lado certo da RJ rural, com prova, nao com alegacao.

## PROTOCOLO
1. **Fixar o lado.** Devedor -> **`rj-produtor-rural-inicial`**. Credor -> **`rj-produtor-defesa-do-credor`**. Classificacao do credito -> **`rj-sujeicao-de-creditos-agro`**. Anexo: `rj-produtor-rural.md`.
2. **A RJ rural de 2026 nao e pedido documental, e dossie probatorio territorial.** **Provimento CNJ 216, de 09/03/2026**: bienio do art. 48 por documentos enumerados, admitido periodo **anterior ao registro mercantil** (art. 3º, §1º); laudo das condicoes operacionais; declaracao das garantias sobre safras presentes e futuras e sobre semoventes; perspectiva de colheita; o perito esclarece se a propriedade esta **formalmente registrada em nome da recuperanda**; **constatacao previa** (art. 10) e **monitoramento continuo** (art. 12). Some **ACT CNJ-MAPA 013/2026** (Infraestrutura VMG: satelite, clima, georreferenciamento) e **Prov. CNJ 231/2026**.
3. ⚠️ **Gap declarado:** a **numeracao dos artigos dos Provimentos CNJ 214/2026 e 216/2026 nao foi conferida** — o conteudo e seguro, o numero do artigo **nao entra em peca**.
4. **Declare o racha, nao escolha lado como pacifico:** CPR fisica e barter **extraconcursais** (L8929 art. 11, red. Lei 14.112/2020; REsp 2.178.558-MT, 3a T, 09/09/2025, Info 867) **x** decisao do **TJ/GO** reconhecendo a cedula rural financeira como **concursal**; o proprio ACT 013/2026 reconhece que persistem divergencias entre tribunais.
5. **Diagnostico honesto:** menos de 1/4 dos planos aprovados sao efetivamente cumpridos 🟡 — isso entra no `parecer-agrario`, nao se esconde do cliente.
6. Cruzar com `protocolo-p4-agrario` quando houver despejo, execucao de CPR ou embargo ambiental em curso.
7. Fechar pela `suprema-corte-agraria` + `validador-agrario`.

**Skill a acionar:** `rj-produtor-rural-inicial` (devedor), `rj-produtor-defesa-do-credor` (credor) ou `rj-sujeicao-de-creditos-agro` (classificacao), conforme o lado.
