---
name: jurisprudencia-agraria
description: "Corpus de jurisprudencia agraria conferido em fonte oficial: entrega sumulas, temas repetitivos, repercussoes gerais e REsp com numero e teor verificados, separando o que esta vigente do que foi CANCELADO ou SUPERADO, do que e RACHA entre tribunais e do que continua PENDENTE de julgamento. Barra a armadilha de homonimo do REsp 1.870.836-RS e impede que tese pendente seja vendida como decidida. Use antes de citar qualquer precedente agrario, ou quando o operador disser tem sumula sobre isso, qual o tema, esse REsp serve, o STF ja decidiu, existe repetitivo, a Sumula 408 vale, cita um precedente de preferencia do arrendatario."
---

# JURISPRUDENCIA-AGRARIA — Corpus ✅-only, com cancelados, rachas e pendentes

> Camada 1. E de onde a citacao **sai**. Regra do anexo: **so entra o que foi conferido em fonte oficial** (STJ, STF, CNJ). O que nao esta la nao e "provavelmente valido" — e **nao confirmado**, e nao entra com numero.

## Quando ativa / trilha
Consultada por **todas as camadas**, sempre que uma peca for citar precedente. Roda junto das demais de C1.

**Diferenca da vizinha:** o `validador-agrario` **audita o rascunho pronto**; esta skill e a **fonte de onde a citacao sai** antes de existir rascunho. E o `anti-alucinacao-agraria` opera na geracao — os tres se somam, nao se substituem.

## Anexos obrigatorios (context/)
- `context/jurisprudencia-agraria.md` (§0 as quatro travas · §1 indice ✅ · §2 armadilha de homonimo · §§3-8 por tema · **§9 CANCELADOS** · **§10 RACHAS** · **§11 PENDENTES** · §12 nao confirmados · §13 obice — **grep o numero e leia a faixa**).
- Para conferir o dispositivo interpretado: `estatuto-e-decreto-contratos-agrarios.md` · `lei-do-agro-e-cpr.md` · `lei-8629-93-e-cf-184-191.md` · `rj-produtor-rural.md` · `registral-terras-e-estrangeiros.md`.

## Base legal ancorada

### As quatro travas (antes de qualquer citacao)
1. Nada de **CANCELADOS/SUPERADOS** como vigente.
2. Nada de **PENDENTES** como decidido — **isso perde a causa e a credibilidade**.
3. Nada marcado **🟡** entra em peca **com numero**. Roteie ao `validador-agrario`.
4. **Regra de transcricao:** ao **transcrever enunciado entre aspas**, use **exatamente** a grafia e a pontuacao da fonte oficial (ex.: Sumula 5 grafa "clausula" sem acento; Sumula 298 traz virgula depois de "mas"). Ao **parafrasear**, tanto faz.

### Indice ✅ — o completo esta no **§1 do anexo**. Aqui so os que se citam errado:
- **Tema 961/STF** e **pluralidade de terrenos** — **nao** e a tese da garantia real (essa e do **REsp 2.233.886-RS**).
- **Tema 1.145/STJ**: basta estar **inscrito na Junta ao formalizar o pedido**; nao se exige tempo de registro.
- **Sumula 93**: as cedulas rurais **admitem o pacto** de capitalizacao — **nao fixa periodicidade**. **Sumula 354** e **INVASAO** como suspensao, nao notificacao da vistoria.
- **Sumula 623 + Tema 1.204 andam juntos**: a sumula isolada nao abre a defesa do alienante; o Tema, sim. **Sumulas 12, 70 e 102** so ate **12/01/2000**.
- Citaveis direto: Temas **1.234 · 1.019 · 126 · 184 · 999/STF** · Sumulas **618/STF · SV 17 · 141 · 131 · 56 · 629** · **ADI 2.332** · **Res. CNJ 510/2023**. *(Temas 399 e 647 ficam fora: art. 243, penal-adjacente.)*

### 🔴 Acordaos pos-corte — de Turma, nao repetitivos
- **REsp 2.187.412-MT** — 3a T, Nancy Andrighi, **10/02/2026, Info 879**: a **perda da propriedade** pelo arrendador **extingue** o arrendamento. ⭐ **Nao afasta o art. 28 do Decreto**: ele fica **"ate o termino dos trabalhos que forem necessarios a colheita"**.
- **REsp 2.233.886-RS** — 3a T, **09/12/2025, Info 875**: impenhorabilidade da pequena propriedade **oponivel a AF e a consolidacao extrajudicial**.
- **REsp 2.178.558-MT** — 3a T, **09/09/2025, Info 867**: CPR fisica com antecipacao e barter **fora da RJ**; a conversao em quantia certa **nao** renuncia ao penhor. *(07/10/2025 e a noticia, nao outro caso.)*
- **REsp 2.140.209** — 3a T, **acordao publicado em 08/09/2025**: reafirma o teste do "homem do campo" e exclui quem **nao reside no imovel, tem outros bens e e empresario agricola**. **Cite "acordao publicado em"; nao afirme data de julgamento.** **REsp 1.447.082-TO** (2016) ✅ afastou empresa rural de grande porte; **AgRg no REsp 717.860-RS** (2014) ✅ firmou que **o registro na matricula e DISPENSAVEL**.

### 🚨 A armadilha de homonimo — leia antes de pesquisar "preferencia"
⛔ **O REsp 1.870.836-RS NAO e agrario. JAMAIS cite-o em peca agraria.** E de **preferencia de COERDEIRO** (**CC 1.795**, **180 dias**), e o buscador o oferece com destaque para qualquer consulta com "preferencia". Os quatro institutos que se confundem:

| Instituto | Prazo | Base |
|---|---|---|
| **Preferencia do ARRENDATARIO** | **30 dias** | ET 92 §3º + Dec. **45** ✅ |
| Adjudicacao por venda nao notificada | **6 meses da transcricao** | ET 92 §4º + Dec. **47** ✅ |
| Preempcao entre **CONDOMINOS** (coisa indivisivel) | 180 dias | CC **504** |
| Preferencia de **COERDEIRO** | 180 dias | CC **1.795** — o do REsp 1.870.836-RS |

❌ **Nao existe sumula do STJ nem repetitivo sobre preferencia do arrendatario.** A jurisprudencia e **de Turma**. **NAO INVENTE UM NUMERO.**

### 🚫 Cancelados e superados — nunca como vigentes
**Sumula 408/STJ CANCELADA em 28/10/2020 (Pet 12.344)** — dizia juros compensatorios de "6% ate 13/09/2001, depois 12%" **sobre o valor da indenizacao corrigido monetariamente**; o **Tema 126 foi reescrito: 12% a.a. ate 11/06/1997** (mesma base). **Tese 283** cancelada. **Sumula 119/STJ SUPERADA, nao "cancelada"** (20 anos, do CC/1916; superada pelo Tema 1.019 — **sem ato formal de cancelamento localizado**). **JT 46, tese 7** reproduz a Sumula 408: **nao usar**. ⚠️ **A ADI 2.332 MANTEVE os 6% a.a. sobre a indenizacao corrigida** — derrubou so a expressao "ate" (6% virou **piso**) e o **teto de honorarios** do art. 27, §1º. Dizer que "derrubou os 6%" inverte o julgado.

### ⚔️ Rachas declarados — nao escolha um lado como pacifico
**CPR e barter na RJ:** extraconcursais (L8929 art. 11 + REsp 2.178.558-MT, **de Turma**) **x** decisao do **TJ/GO** tratando a cedula rural financeira como **concursal** — o **ACT CNJ-MAPA 013/2026 reconhece as divergencias**. · **Tema 280/STJ x ADI 2.332**: improdutividade nao afasta juros **x** GUT e GEE zero afastam (art. 15-A, §§1º-2º). · **Sujeito dos 30 dias na renovacao** (ET 95, IV x Dec. 22, §1º). · **Georreferenciamento** — Executivo x CNJ x liminar noticiada. · 🟡 **menos de 1/4 dos planos de RJ sao cumpridos**: dado de mercado para o `parecer-agrario`, **nunca fundamento**.

### 🟡 Pendentes — citar como decidido e erro grave
🟡 **PENDENTE** — **Tema 1429/STF** (coisa julgada de 12% pre-ADI 2.332): RG em 20/09/2025, **sem tese**. · 🟡 **PENDENTE** — **Merito da ADPF 828**: **so a cautelar referendada (nov/2022)** — cite "a decisao cautelar referendada", **nunca "o acordao de merito"**. · 🟡 **PENDENTE** — **ADIs 5.771, 5.787, 5.883 e 6.787** (Lei 13.465/2017): **nao julgadas** — houve **voto** do Min. Dino contra o limite de 2.500 ha, **seguido de destaque** do Min. Gilmar Mendes, e **retirada de pauta em 23/06/2026**. **O art. 6º, §1º da Lei 11.952/2009 continua vigente**; a imprensa noticiou o voto como resultado, e repetir isso e erro grave. · 🟡 **PENDENTE** — **ADIs 7913, 7916, 7919 + ADC 102** (Lei 15.190/2025): **sem liminar**, **merito em 12/08/2026 — rechecar**.

### Obice recursal ✅
**Sumulas 5 e 7 do STJ** sao o obice recorrente no agrario — travaram o **REsp 1.447.082-TO** na parte fatica. O excepcional se desenha sobre **prequestionamento e materia de direito**.

## Passo a passo / o que produzir
1. **Grep o numero** (`Tema 1.145`, `REsp 2.187.412`, `Sumula 408`) no anexo e **ler a faixa**. Nunca de memoria.
2. **Ler o selo:** ✅ cita · 🔴 de Turma, com qualificacao completa · 🟡 **sem numero** · cancelado, superado ou pendente -> barrar ou rotular.
3. **Testar a armadilha de homonimo** sempre que a pesquisa tocar "preferencia".
4. **Havendo racha, declarar os dois lados**; havendo pendencia, dizer que esta pendente.
5. **Entregar a ficha**: corte · instrumento e numero · tese em uma linha · data e informativo · selo · faixa.

## Postura honesta
- 🟡 **A lista dos nao confirmados vive no `validador-agrario` e no §12 do anexo** (termo inicial dos 6 meses e deposito do preco · notificacao ao arrendatario · parceria simulada · CDC integrado x integradora · conflito de garantias sobre a mesma safra · boa-fe do terceiro adquirente · prescricao da CPR · Sumula 355 · Prov. CNJ 149/2023 · ADPF 342 e ACO 2.463). **Nenhum entra em peca com numero.**
- ⛔ **Nao cite o REsp 1.816.808/SP** sobre embargo administrativo — nao confirmado. A ancora de "o embargo nao pega o imovel inteiro" e **NORMATIVA** (Dec. 6.514/2008, art. 15-A), nao jurisprudencial.
- 🟡 **"Terra devoluta nao se presume"**: orientacao localizada (**AREsp 888.195/PI**; **EDcl no REsp 617.428/SP**), **inteiros teores nao lidos**, **sem repetitivo** — nao afirme "consolidado". · **Arrendatario como sujeito passivo** ambiental entra por **subsuncao**. · **Nao ha outro repetitivo sobre RJ do produtor alem do Tema 1.145 localizado** — nao afirme existencia nem inexistencia.
- O selo 🔴 nao significa fraco: significa **recente e de Turma**. Cite com a qualificacao completa. Vender Turma como vinculante e exagero que a parte contraria desmonta em uma linha.

## Cross-link e fechamento
Auditoria do rascunho -> `validador-agrario` (hospeda as 50 citacoes erradas). Guard na geracao -> `anti-alucinacao-agraria`. Dispositivo interpretado -> as tres bases de C1. Prequestionamento -> `base-processual-agraria` e a C8. Busca ao vivo -> `juris-adv-os` (soft).

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
