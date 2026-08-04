---
name: app-reserva-legal-e-areas-consolidadas
description: "Dimensiona o passivo ambiental do imovel rural: o que tem de ser recomposto em APP e Reserva Legal e o que nao tem, pelo regime das areas rurais consolidadas ate 22/07/2008. Entrega o mapa do passivo com a faixa de recomposicao por modulo fiscal, o teto do art. 61-B, as tres isencoes que mais resolvem (arts. 15, 67 e 68) e a redacao correta — a da Lei 12.727/2012, nunca a da MP 571/2012, que muda a metragem. Use quando o operador disser quanto tenho que recompor, a fazenda tem APP ocupada, area consolidada, faixa de nascente, reserva legal em deficit, compensacao de reserva legal, o IBAMA quer recomposicao integral, /car-pra."
---

# APP-RESERVA-LEGAL-E-AREAS-CONSOLIDADAS — o mapa do passivo

> Camada 6. Skill de dimensionamento: nao ataca o auto nem adere ao PRA — **calcula o passivo real** que as demais skills usam como premissa. Errar a metragem aqui contamina defesa, termo de compromisso, *due diligence* e preco de compra.

## Quando ativa / trilha
Precisa-se saber **quanto** recompor: proposta de PRA, defesa que alega excesso na exigencia, laudo de passivo em aquisicao, ou conflito com o orgao sobre a faixa. Vem da `car-pra-e-termo-de-compromisso` ou da `due-diligence-de-terras-rurais`. **Diferenca das vizinhas:** aqui e a **medida** do passivo; **elegibilidade e prazo** do PRA sao da `car-pra-e-termo-de-compromisso`; **nulidade do auto**, da `defesa-em-auto-de-infracao-ambiental`.

## Anexos obrigatorios (context/)
- `context/codigo-florestal-12651.md` (**art. 3º II/XVII-XIX · art. 4º · art. 7º · arts. 61-A a 61-C · arts. 12-15 · arts. 66-68** — **grep o artigo e leia a faixa**).
- `context/jurisprudencia-agraria.md` (ADC 42 de 28/02/2018 e os **ED de 24/10/2024**; interpretacao conforme sobre nascentes intermitentes).

## Base legal ancorada ✅

### ⛔ Regra de redacao — a unica que vale e a da Lei 12.727/2012
Use sempre a redacao "(Incluido pela Lei nº 12.727, de 2012)". A da **MP 571/2012** circula em material antigo e **muda a metragem** dos arts. 61-A e 61-B. Citar a metragem da MP entrega ao cliente faixa errada.

### APP — o que e, antes de quanto e
- **Art. 3º, II:** APP e area protegida "**coberta ou nao por vegetacao nativa**". ⭐ Derruba a tese de balcao "ali nao tem mata, entao nao e APP".
- 🔴 **Nascentes e olhos d'agua INTERMITENTES sao APP** — interpretacao conforme do STF aos arts. 3º, XVII e 4º, IV, cuja **letra diz "perene"**. A leitura literal nao vale.
- **Art. 4º** — as faixas de APP **nao consolidada** (curso d'agua por largura, lagos, nascentes, encosta, chapada, topo de morro, vereda) estao na tabela do anexo: **grep `art. 4º` e leia a faixa**, nao cite de memoria. O que a peca erra esta nos paragrafos: **§1º** — **nao ha APP** em reservatorio artificial que **nao decorra de barramento ou represamento** (acude escavado nao gera APP); 🔴 **§2º REVOGADO** pela Lei 12.727/2012 — **a regra dos 15 m no entorno de reservatorio rural ate 20 ha NAO EXISTE MAIS.**
- **Art. 7º, §2º** — a obrigacao de recompor "**tem natureza real e e transmitida ao sucessor**" (base legal do *propter rem*). **§3º** — supressao nao autorizada apos **22/07/2008** veda novas autorizacoes ate a recomposicao.

### ⭐ Areas consolidadas em APP — Lei 12.651, art. 61-A (a faixa escalonada)

| Hipotese | Porte (MF) | Recomposicao |
|---|---|---|
| Curso d'agua (§§1º-3º) | ate 1 / >1 a 2 / >2 a 4 | **5 m · 8 m · 15 m** — da borda da calha, **qualquer que seja a largura do curso** |
| Curso d'agua (**§4º, II**) | **> 4 MF** | **conforme o PRA, minimo 20 e maximo 100 m** — 🔴 o **inciso I foi VETADO** |
| **Nascentes e olhos d'agua** (§5º) | **qualquer porte** | **raio minimo de 15 m — valor unico, NAO escalonado** |
| Lagos e lagoas (§6º) | ate 1 / >1 a 2 / >2 a 4 / >4 | **5 · 8 · 15 · 30 m** |
| Veredas (§7º) | ate 4 / > 4 | **30 m · 50 m** |

Nos §§5º a 7º **admite-se manter a atividade enquanto se recompoe**. **§8º ⭐:** considera-se "**a area detida pelo imovel rural em 22 de julho de 2008**" — **fracionar depois nao reduz a faixa**. **§12:** mantem-se residencia e infraestrutura associada, **inclusive o acesso**, salvo risco a vida. **§13:** metodos (regeneracao natural, plantio de nativas, conjugacao; exoticas ate **50% da area a recompor** so na pequena propriedade familiar). **§15:** atividade continua ate o **termino do prazo de adesao ao PRA**. **§16:** APP em **UC de protecao integral nao admite consolidacao**.

🚨 **Art. 61-B — o teto com buraco.** Para quem detinha **ate 10 MF em 22/07/2008**, a recomposicao somada de todas as APPs nao ultrapassa **10% da area total do imovel** (ate 2 MF) ou **20% da area total do imovel** (>2 a 4 MF). O **inciso III, que fixaria o teto da faixa de 4 a 10 MF, foi VETADO**: o *caput* menciona 10 MF, mas **nao ha percentual-teto vigente para 4 a 10 MF. NAO INVENTE UM.**

**Art. 61-C** — em assentamento, o modulo aplicavel e o do **lote individual demarcado**, nao o do assentamento inteiro. E o que viabiliza a faixa de 5 m.

### Reserva Legal — percentual, trava e as tres isencoes
- **Lei 12.651, art. 12 — RL sobre a area do imovel:** **80%** floresta na Amazonia Legal · **35%** cerrado na Amazonia Legal · **20%** campos gerais e **20%** demais regioes. **§1º ⭐:** no fracionamento a qualquer titulo, considera-se **a area do imovel ANTES do fracionamento**.
- 🎯 **Art. 14, §2º — a trava contra sancao:** "**Protocolada a documentacao exigida para a analise da localizacao da area de Reserva Legal**, ao proprietario ou possuidor rural **NAO PODERA SER IMPUTADA SANCAO ADMINISTRATIVA, inclusive restricao a direitos** (…) em razao da nao formalizacao da area de Reserva Legal." Protocolo feito, autuacao por RL nao formalizada e ilegal.
- **Art. 15 — computo da APP dentro da RL** (tres requisitos do caput; **§3º vale para todas as modalidades**: regeneracao, recomposicao e compensacao). ⭐ **E o dispositivo que mais reduz passivo** em imovel com muita APP.
- **Art. 66** — regularizacao **independentemente da adesao ao PRA**: recompor, regenerar ou compensar. **§1º** obrigacao real, transmitida ao sucessor. **§2º** recomposicao em **ate 20 anos, no minimo 1/10 da area a recompor a cada 2 anos**. **§4º** quem recompoe assim **tem direito a exploracao economica**. **§5º** compensacao (CRA, arrendamento sob servidao, doacao ao poder publico, cadastramento de area excedente) — sempre **no MESMO BIOMA**.
- 🔴 **ED da ADC 42, j. 24/10/2024:** caiu a exigencia de "**identidade ecologica**" na compensacao — **basta o BIOMA** (art. 66, §6º, II). A interpretacao conforme de 2018 nesse ponto **nao vale mais**.
- 🎯 **Lei 12.651, art. 67** — imovel que detinha **ate 4 MF em 22/07/2008** com remanescente inferior ao art. 12: **a RL e a vegetacao nativa existente em 22/07/2008, sem recomposicao**, vedadas novas conversoes. **Nao ha passivo de RL a recompor** — a tese mais forte da pequena propriedade.
- 🎯 **Art. 68** — quem suprimiu **respeitando o percentual da legislacao da epoca** e **dispensado** de recompor, compensar ou regenerar. **§1º: PROVA ABERTA** — fatos historicos de ocupacao, registros de comercializacao, dados agropecuarios, contratos e documentos bancarios, "**todos os outros meios de prova em direito admitidos**". E a resposta ao auto que aplica retroativamente o percentual de hoje.

## Passo a passo / o que produzir
**Entrega: mapa do passivo — faixa exigivel por area, com a ancora de cada numero — e o memorial de enquadramento que instrui o PRA ou a defesa.**
1. **Fixar o porte em modulos fiscais NA DATA DE 22/07/2008** (art. 61-A, §8º e art. 61-B), nao a area de hoje.
2. **Separar APP de RL** e, dentro da APP, **consolidada (ate 22/07/2008) x nao consolidada** — regimes diferentes.
3. **APP consolidada:** aplicar a tabela do art. 61-A; nascente sempre **15 m**; acima de 4 MF, **20 a 100 m pelo PRA**.
4. **Aplicar o teto do art. 61-B** quando cabivel — e **nao inventar teto** para 4 a 10 MF.
5. **RL: testar as tres isencoes na ordem (Lei 12.651)** — art. 67 (ate 4 MF: sem passivo) -> art. 68 (supressao legal a epoca, com a prova do §1º) -> art. 15 (computar APP na RL). So o que sobrar vira recomposicao ou compensacao do art. 66.
6. **Checar a trava do art. 14, §2º** — havendo protocolo, sustentar a nulidade de qualquer sancao por RL nao formalizada.

## Postura honesta
- **Consolidacao exige prova da ocupacao ate 22/07/2008.** Sem imagem historica, nota fiscal, contrato ou documento bancario, a faixa reduzida **nao se sustenta** — a prova aberta do art. 68, §1º ajuda, mas nao dispensa provar.
- 🔴 **Nao existe teto de recomposicao para 4 a 10 MF** (art. 61-B, III vetado). Prometer percentual ali e inventar norma.
- **Consolidacao nao alcanca UC de protecao integral** (§16) nem supressao **posterior** a 22/07/2008 (art. 7º, §3º).
- **A obrigacao e real e acompanha o imovel** (arts. 7º, §2º e 66, §1º): quem compra, compra o passivo — ver `tac-e-responsabilidade-ambiental-rural` para o recorte do alienante.
- **Estado e legislacao supletiva contam.** O anexo cobre a norma **federal**; regra estadual mais restritiva pode existir — checar antes de fechar o numero.

## Cross-link e fechamento
Elegibilidade e prazo do PRA -> `car-pra-e-termo-de-compromisso`. Auto de infracao -> `defesa-em-auto-de-infracao-ambiental`. Area embargada -> `embargo-e-desembargo`. Dispensa de licenciamento -> `licenciamento-e-dispensa-agropecuaria`. Passivo na compra -> `due-diligence-de-terras-rurais`. APP e RL fora da area tributavel -> `itr-e-tributacao-da-terra`. Exportacao a UE -> `compliance-eudr`.

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
