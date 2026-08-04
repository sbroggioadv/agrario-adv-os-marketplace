---
name: base-credito-rural-e-lei-do-agro
description: "Fundacao dos titulos do credito rural: mapeia CPR (Lei 8.929/94 pos-14.421/2022), cedulas rurais (DL 167/67) e os instrumentos da Lei do Agro (13.986/2020 — patrimonio rural em afetacao, CIR, FGS), dizendo quem alterou o que, qual dispositivo esta revogado e qual e a via de execucao de cada especie. Nao redige peca: entrega a base que a camada de credito, divida e insolvencia usa. Use antes de skill de CPR, cedula, garantia, execucao, embargos, revisional ou RJ do produtor, ou quando o operador disser emiti uma CPR, o banco executou, cedula rural, barter, penhor agricola, patrimonio de afetacao, CIR, o Marco das Garantias mudou a CPR, a CPR e titulo executivo."
---

# BASE-CREDITO-RURAL-E-LEI-DO-AGRO — CPR x cedulas x CIR

> Camada 1. Fundacao da **C3, o nucleo comercial do plugin**. Nao redige peca: fixa **qual lei alterou o que** e **qual dispositivo esta morto** — onde mora metade dos erros de citacao do dominio.

## Quando ativa / trilha
Antes de toda skill de **C3** (titulo, garantia, execucao, embargos, revisional, alongamento, MP 1.376 e as tres de RJ). Alimenta tambem `contrato-barter` (C2).

**Diferenca da vizinha:** `cpr-emissao-e-formalizacao` **emite e audita o titulo**; esta skill diz **qual e a lei vigente sobre ele**. E **prorrogacao (MCR) x composicao de dividas da MP 1.376/2026 x securitizacao sao institutos distintos** — cada um tem skill propria.

## Anexos obrigatorios (context/)
- `context/lei-do-agro-e-cpr.md` (§0 mapa de alteracoes · §1 CPR arts. 1º-19 · §2 afetacao, CIR e FGS · §3 DL 167/67 · §4 lista 🟡 · §5 armadilhas — **grep o artigo e leia a faixa**).
- `context/jurisprudencia-agraria.md` (Sumula 93, REsp 2.178.558-MT, REsp 2.233.886-RS, Temas 961 e 1.234, §10 rachas — **grep o numero e leia a faixa**).
- `context/rj-produtor-rural.md` (sujeicao) · `context/mp-1376-2026.md` (composicao de dividas).

## Base legal ancorada

### Mapa — quem alterou o que ✅
**Lei 8.929/94 (CPR)**: alterada pela 10.200/2001, pela **13.986/2020 (art. 42)** e pela **14.421/2022** — a mais recente. Mas o **art. 11** (extraconcursalidade) foi reescrito pela **Lei 14.112/2020**, a reforma da RJ, **nao pela Lei do Agro**. **DL 167/67**: alterado pela **13.986/2020 (art. 45)**, 14.421/2022, 13.506/2017 e 12.873/2013.

🔴 **O que a Lei 14.711/2023 (Marco das Garantias) alterou nesses dois diplomas: NADA.** Verificado em dupla via — o compilado do DL 167/67 nao a menciona, e a ementa da 14.711 lista as leis alteradas sem nenhum dos dois. "O Marco mexeu nas cedulas rurais" e **premissa falsa**. Ela importa no agro por **outra porta**: a execucao extrajudicial da hipoteca, **art. 9º**.

### CPR — Lei 8.929/1994 ✅
- **Art. 1º, §2º**: os incisos **III (industrializacao) e IV (insumos, maquinas e armazenagem) sao de 2022** e ampliaram o alcance do titulo.
- **Art. 3º — os 10 requisitos formais.** ⚠️ O **inciso IV** exige o **local onde sera desenvolvido o produto rural**: e de 2020 e e **gancho de nulidade subutilizado**. **§4º**: no registro de **garantia real** a assinatura eletronica tem de ser **avancada ou qualificada**.
- **Arts. 3º-A a 3º-E** cartular x escritural, escrituracao sob o BCB. ⚠️ **NAO existe art. 12-A**.
- **Arts. 4º e 4º-A** — a CPR e **titulo liquido e certo**; a **financeira** cobra-se por **quantia certa** (§2º).
- 🚨 **Art. 5º e CLAUSULA ABERTA.** **Os incisos I, II e III — hipoteca, penhor e alienacao fiduciaria — estao REVOGADOS desde 2020.** Cita-los e citar dispositivo morto.
- **Arts. 6º a 8º:** a AF alcanca bens **presentes ou futuros, fungiveis ou infungiveis**; **art. 8º, §2º: beneficiamento e transformacao NAO extinguem o vinculo real**; §3º DL 911/69.
- ⭐ **Art. 11 (red. Lei 14.112/2020)** — **nao se sujeitam a RJ** os creditos e garantias cedulares da **CPR com liquidacao fisica** com **antecipacao do preco** ou **troca por insumos (barter)**, com direito a restituicao, **salvo caso fortuito ou forca maior comprovado**. 🔴 A redacao anterior dizia o **oposto**: hoje o caso fortuito e a **unica excecao** que devolve o credito a RJ.
- **Art. 12 — registro em entidade autorizada pelo BCB** sob pena de perder validade e eficacia: **10 dias uteis** ate 10/08/2022, **30 dias uteis** desde **11/08/2022**. **§2º: o cartorio e DISPENSADO para o titulo**; ao RI vao as **garantias reais imobiliarias**.
- **Art. 15: CPR fisica -> execucao para ENTREGA DE COISA INCERTA** · ⭐ **art. 18: os bens vinculados nao sao penhorados por outras dividas** · **art. 19 revogado** (migrou para o 3º-D).

⚠️ **A Lei 8.929/94 NUNCA chama a CPR de "titulo executivo extrajudicial"** (leitura integral do compilado): ela diz **"titulo liquido e certo"**. Quem a lei chama assim e a **CIR** (L13986, **art. 21**). A via esta nos arts. 15 e 4º-A §2º acima e no anexo §1; o rito fica em `base-processual-agraria`.

### Lei do Agro — Lei 13.986/2020 ✅
- **Afetacao — art. 8º, as 4 vedacoes** (o ataque mais direto): onus real preexistente · pequena propriedade · area inferior ao modulo ou a FMP · bem de familia.
- **Art. 10:** a impenhorabilidade vale **so na medida da garantia vinculada** (§3º, II); ⭐ **§5º — a blindagem NAO alcanca trabalhista, previdenciario e fiscal**. "Afetacao blinda contra tudo" e falso.
- **CIR:** **art. 19, §1º** registro em **5 dias uteis** como condicao de eficacia executiva; **art. 21** e quem a lei chama de **titulo executivo extrajudicial**; ⭐ **art. 28, §2º** puxa os **arts. 26 e 27 da Lei 9.514/97** — **purgacao da mora e DOIS LEILOES**, embora o caput pareca autorizar tomada imediata.
- **FGS** pos-14.421/2022: **sem percentuais, sem cota terciaria, credor nao e integrante** — "4% + 4% + 2%" esta revogado.

### Cedulas de credito rural — DL 167/1967 ✅
**Art. 9º — as 4 especies:** Pignoraticia · Hipotecaria · Pignoraticia e Hipotecaria · **Nota de Credito Rural**. **Art. 10** titulo civil liquido e certo; ⭐ **§1º: a parcela nao levantada e os pagamentos parciais SE DESCONTAM — exigivel so o saldo** (base do excesso de execucao). ⭐ **Art. 14, IV: finalidade ruralista e forma de utilizacao sao REQUISITO ESSENCIAL** — base do desvio de finalidade; **§§3º-4º** vedam ao registrador exigir avaliacao, ART ou CND.

**Sumula 93/STJ ✅:** as cedulas rurais **admitem o PACTO** de capitalizacao. **Ela nao fixa periodicidade** — dizer que "autoriza capitalizacao mensal" e ir alem do enunciado.

## Passo a passo / o que produzir
1. **Identificar a especie**: CPR fisica · CPR financeira · cedula do art. 9º · CIR · afetacao.
2. **Datar a emissao** — o registro muda em **11/08/2022** (10 -> 30 dias uteis); vale a redacao da emissao.
3. **Rodar o mapa de alteracoes**: 8.929 (14.421/2022) · art. 11 (14.112/2020) · DL 167/67 (13.986/2020) · **14.711/2023 nao alterou nenhum dos dois**.
4. **Fixar a via** pela especie (art. 15 x 4º-A, §2º). Errar a porta e vicio que a defesa explora.
5. **Testar os revogados**: art. 5º I-III · art. 19 · FGS 4+4+2 · art. 12-A (nao existe).
6. **Entregar o quadro**: especie · dispositivo vigente · lei alteradora · via · faixa lida · selo (✅ / 🟡 / 🔴).

## Postura honesta
- 🚫 **GAP INTRANSPONIVEL — a prescricao da CPR e da cedula rural NAO tem prazo afirmado no corpus do plugin.** Nenhum dispositivo de prescricao foi lido na 8.929/94 nem no DL 167/67; o tema depende da articulacao cambial do art. 10. **Nao preencha por memoria e nao deduza**: marque "a confirmar" e roteie ao `validador-agrario`. E onde o modelo alucina com mais confianca.
- 🟡 **Nao cite o inciso do CPC 784** — nao confirmado. Cite o artigo, nunca o inciso.
- 🟡 **Periodicidade da capitalizacao** (mensal x semestral, MP 1.963-17/2000 -> 2.170-36/2000): paradigma **nao confirmado — nao cite numero**.
- 🟡 **Bloco sem numero:** conflito de garantias sobre a **mesma safra** (penhor x CPR x AF) · **boa-fe do terceiro adquirente de safra gravada** · **penhor rural sem registro** (CC 1.438; DL 167/67 art. 30). Os artigos de penhor, prazo e sub-rogacao do DL 167/67 **nao foram lidos**.
- ⚔️ **Racha declarado, nao resolvido:** CPR fisica e barter sao **extraconcursais** (art. 11 + **REsp 2.178.558-MT**, 3a T, 09/09/2025, Info 867) — **mas ha decisao do TJ/GO** tratando a cedula rural financeira como **concursal**, e o **ACT CNJ-MAPA 013/2026 reconhece divergencias entre tribunais**. O REsp e **de Turma, nao repetitivo**. Declare os dois lados.
- ⚠️ **Nao atribua ao Tema 961/STF a tese da garantia real.** O 961 resolve **pluralidade de terrenos**; a impenhorabilidade **oponivel a alienacao fiduciaria e a consolidacao extrajudicial** e do **REsp 2.233.886-RS** (3a T, 09/12/2025, Info 875).
- 🟡 Os demais 🟡 do credito (Resolucoes CMN do Plano Safra, capitulo do MCR, MP 1.314/2025, securitizacao) estao no `validador-agrario` — consulte antes de citar numero.

## Cross-link e fechamento
Titulo, garantia e execucao -> C3. Alongamento -> `prorrogacao-de-divida-rural`; composicao de dividas -> `renegociacao-mp-1376`; sujeicao -> as tres de RJ. Barter -> `contrato-barter`. Precedentes -> `jurisprudencia-agraria`. Via -> `base-processual-agraria`. Leilao -> `leiloes-os`; consumo bancario -> `bancario-adv-os`; calculo -> `calculosjudiciais-adv-os` (soft).

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
