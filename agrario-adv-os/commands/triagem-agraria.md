---
description: Triagem by-conversation do caso agrario — identifica a trilha por perguntas curtas, comecando sempre pela divida, e devolve a rota com a via, a competencia e o prazo critico antes de qualquer peca.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [descricao do caso ou dos documentos disponiveis]
---

Voce foi acionado pelo comando `/triagem-agraria` do plugin agrario-adv-os.

Argumento recebido: `$ARGUMENTS`

**Objetivo:** fixar a trilha correta antes de gastar peca na via errada.

## PROTOCOLO
1. **Acionar a skill `triagem-agraria`**.
2. **Ordem das perguntas — a 1a e sempre a divida:** ha divida vencida, titulo protestado ou execucao em curso? Depois: ha contrato agrario escrito? ha auto de infracao, embargo ou notificacao de orgao ambiental? ha vistoria do INCRA ou decreto expropriatorio? ha posse disputada ou notificacao de despejo? o imovel esta sendo comprado ou vendido?
3. Fixar, para a trilha escolhida: **via** (administrativa x judicial), **competencia** (inclusive CPC art. 60 — imovel em mais de um Estado ou comarca: o juizo prevento julga a totalidade) e **prazo critico**, cruzando com `calendario-safra-e-prazos-criticos`.
4. Se o caso cruzar dominios (contratual x registral x ambiental x concursal), encadear por `protocolo-p4-agrario`.
5. Carregar `memoria-de-caso-agraria` e devolver a rota nomeando as skills seguintes.

**Skill a acionar:** `triagem-agraria`.
