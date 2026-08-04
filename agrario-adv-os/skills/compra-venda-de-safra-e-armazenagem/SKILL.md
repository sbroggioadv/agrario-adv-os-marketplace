---
name: compra-venda-de-safra-e-armazenagem
description: "Venda de safra futura, entrega, deposito e armazenagem — com o conceito de produto rural ampliado pela Lei 14.421/2022 (industrializacao, insumos, maquinas e ARMAZENAGEM dentro da CPR) e com CDA e Warrant Agropecuario agora ANCORADOS (Lei 11.076/2004). Cobre quem pode emitir, entrega antecipada so com anuencia, impenhorabilidade dos bens vinculados, o crime do art. 17 na safra vendida duas vezes, a NAO CONFUSAO do produto depositado na falencia do depositante, a excussao do penhor do WA em leilao de bolsa e a via de execucao correta. Use quando o operador disser contrato de venda de safra, venda antecipada de soja, o produtor vendeu a mesma safra duas vezes, contrato de deposito de graos, armazem nao devolveu o produto, CDA, warrant agropecuario, posso penhorar a safra."
---

# COMPRA-VENDA-DE-SAFRA-E-ARMAZENAGEM

> Camada 2. A Lei 14.421/2022 **ampliou o produto rural** e trouxe **armazenagem** para dentro do sistema da CPR — quem usa a redacao pre-2022 subestima o instrumento.

## Quando ativa / trilha
Pela `triagem-agraria` na trilha contrato. Roda depois de `base-credito-rural-e-lei-do-agro`.

**Fronteiras:** **insumo por safra** -> `contrato-barter` (art. 11, com efeito na RJ) · **integracao** com aves ou suinos -> `contrato-integracao-vertical` · emissao e registro da CPR -> `cpr-emissao-e-formalizacao` · executar o titulo -> `execucao-de-cpr-e-cedula-rural`.

## Anexos obrigatorios (context/)
- `context/lei-do-agro-e-cpr.md` (**§1 — grep "art. 1º" e leia o §2º inteiro**; arts. 2º, 3º, 8º, 12, 13, 14, 15, 17 e 18).
- `context/titulos-do-agronegocio-11076.md` — **CDA, WA, CDCA, LCA e CRA** (Planalto 02/08/2026). 🔴 **O anexo mais minado do plugin: 239 blocos riscados ao lado do texto vivo.** **Grep o artigo e leia a faixa**, conferindo o rotulo de vigencia antes de transcrever.
- `context/cpc-agrario.md` (§10.2 entrega de coisa **incerta** · §2.1 art. 53, III, "d" · §2.4 foro de eleicao — **grep o artigo e leia a faixa**).
- `context/jurisprudencia-agraria.md` (§4 credito e CPR; **§12 garantias sobre a mesma safra, sem numero confirmado**).

## Base legal ancorada

### 🔴 O conceito de PRODUTO RURAL mudou em 2022 — Lei 8.929/94, art. 1º, §2º ✅
Quatro incisos, **dois deles de 2022** (redacao literal no anexo — **grep "art. 1º"**):
- **I** (red. **14.421/2022**) — agricola, pecuaria, **florestal**, **extrativismo vegetal**, pesca e aquicultura, derivados, subprodutos e residuos, **inclusive sob beneficiamento ou primeira industrializacao**;
- **II** (red. **14.421/2022**) — conservacao, recuperacao e manejo de florestas nativas, recuperacao de areas degradadas e **servicos ambientais** na propriedade rural;
- **III** (**incluido em 2022**) — **industrializacao** dos produtos do inciso I;
- **IV** (**incluido em 2022**) — **insumos agricolas, maquinas e implementos e equipamentos de ARMAZENAGEM**.

⚠️ A redacao de 2020 dos incisos I e II aparece **riscada** no compilado — leia a vigente. E **III e IV nao existiam antes de 2022**.

**Quem pode emitir — art. 2º ✅ (red. 14.421/2022):** **I** produtor rural PF ou PJ (inclusive com objeto social **nao exclusivamente** rural), cooperativa agropecuaria e associacao; **II** quem **beneficia ou promove a primeira industrializacao**, ou empreende as atividades dos **incisos II, III e IV** do art. 1º, §2º. **§2º:** IOF sobre a CPR emitida pelos do inciso II.

⚠️ **Art. 4º-A, §4º:** nos produtos dos **incisos III e IV** a **liquidacao financeira e OBRIGATORIA** — nao cabe CPR fisica, e errar isso inviabiliza o titulo.

### Entrega, vencimento e a safra que nao pode ser tocada ✅
- **Art. 13** — a **entrega antecipada depende de anuencia do credor**. Comprador que exige embarque antes do prazo sem aditivo esta fora do titulo.
- **Art. 14** — a CPR pode ser considerada **vencida no inadimplemento de qualquer das obrigacoes** do emitente, nao so na falta de entrega.
- **Art. 18 ⭐** — os **bens vinculados a CPR nao serao penhorados nem sequestrados por outras dividas** do emitente ou do garantidor, cabendo a qualquer deles **denunciar a existencia da cedula, sob pena de responder pelos prejuizos**.
- **Art. 8º, §2º** — **beneficiamento e transformacao NAO extinguem o vinculo real**: ele se transfere aos produtos e subprodutos. Decisivo na armazenagem: grao que virou farelo ou oleo continua vinculado.

### 🚨 A safra vendida duas vezes — art. 17 ✅
**Crime de estelionato** na declaracao falsa ou inexata sobre a qualificacao **ou sobre os bens dados em garantia, inclusive omitindo onus preexistentes**. Some ao **art. 18** (dever de denunciar a cedula). Na consultiva vira **clausula de declaracao e garantia** com listagem de onus e consulta as registradoras. **Gemeo no deposito:** a declaracao do **art. 6º, §1º, I da Lei 11.076/2004**, cujo desacordo o **art. 14** pune com a pena do **CP art. 178**.

### ✅ CDA e WARRANT AGROPECUARIO — Lei 11.076/2004 (ancorado)
- **Art. 1º** — **CDA** = promessa de **ENTREGA** do produto depositado; **WA** (§2º, red. 2007) = promessa de **PAGAMENTO EM DINHEIRO**, com **penhor sobre o CDA e sobre o produto**. **§3º:** titulos **unidos**, transmissiveis unidos ou separados por endosso. **§4º ⭐: sao TITULOS EXECUTIVOS EXTRAJUDICIAIS** — dito na lei, ao contrario da CPR. **Art. 2º, II:** o **endossante nao responde pela entrega**, so pela existencia da obrigacao.
- **Art. 11 ⭐** — obrigacao nuclear do armazem: **guardar, conservar e entregar na quantidade e qualidade consignadas no titulo** — a ancora da acao por produto nao devolvido ou fora de especificacao. O **art. 9º, §2º** veda opor ao terceiro titular as **excecoes pessoais** do depositante.
- **Art. 12 ⭐** — emitidos os titulos, o produto **nao sofre penhora, sequestro** ou embaraco. **P.u. (2020): NAO CONFUSAO** — se o titular difere do depositante, o produto **nao se confunde com o patrimonio dele nem se sujeita a sua RJ ou falencia**.
- **Art. 17, §§2º-4º ⭐** — vencido o WA separado do CDA e nao consignado o valor, o titular do WA executa o penhor por **LEILAO EM BOLSA, sem acao judicial**, sobre **o produto** ou **o CDA junto com o WA**; o saldo vai ao titular do CDA. **Cheque esta porta antes da execucao judicial.**
- **Art. 21** — a baixa exige **CDA e WA no mesmo credor** ou **consignacao do valor** (**equivale a pagamento**, §2º); retirar exige **armazenagem paga e tributos em dia** (§6º).

🔴 **Travas de vigencia:** **art. 12, p.u. e NAO CONFUSAO, nunca "restituicao"** (redacao revogada da MP 897/2019) — na Lei 13.288/2016, art. 13, restituicao e o termo certo; aqui, pedir restituicao e pedir **menos**, com fundamento morto · **art. 15: depositario central em 30 dias**, jamais "registro em sistema em 10 dias" (erra prazo **e** instituto) · **art. 21, §5º: extincao do MANDATO** — "adquire a propriedade" e redacao revogada · **art. 22:** a varredura "**quaisquer intemperies**" foi **suprimida em 2020**; fora da lista fechada, resolve pela apolice · ⛔ **art. 20 nao tem texto vigente**.

### A via de cobranca — nao erre a porta ✅
| Especie | Via | Ancora |
|---|---|---|
| CPR **fisica** | execucao para **entrega de coisa incerta** | art. **15** (Lei 8.929/94) |
| CPR **financeira** | execucao **por quantia certa** | art. **4º-A, §2º** |
| **CDA/WA** | titulo executivo extrajudicial; penhor do WA por **leilao em bolsa** | Lei 11.076/2004, arts. **1º, §4º** e **17, §§2º-4º** |

**Foro:** a acao **pessoal** de cumprimento vai ao **local da obrigacao** (**CPC 53, III, "d"**) ou ao domicilio do reu (art. 46). Clausula de eleicao segue o **art. 63, §1º (red. 14.879/2024)** — pertinencia territorial obrigatoria; o **§5º** torna o juizo aleatorio declinavel **de oficio**. Eleger o local de entrega satisfaz o requisito.

## Passo a passo / o que produzir
1. **Qualificar** (AskUserQuestion, botoes): **vendedor/produtor x comprador/trading/armazem** · **safra futura · safra colhida · deposito e armazenagem** · titulo **fisico x financeiro x CDA/WA**.
2. **Enquadrar o objeto** nos incisos do art. 1º, §2º — e checar o **art. 4º-A, §4º**: caindo nos incisos III ou IV, a **liquidacao e financeira por lei**.
3. **Conferir a legitimacao** do emitente (art. 2º) — trading e armazem so emitem na hipotese do inciso II. No CDA/WA quem emite e o **depositario**, a pedido do depositante (11.076/2004, art. 6º).
4. **Levantar onus preexistentes** e listar em clausula de declaracao e garantia; lembrar do dever de denunciar (art. 18) e do crime (art. 17).
5. **Fixar entrega, local, qualidade e a anuencia do art. 13**; definir o que ocorre em **quebra de safra** (forca maior) e em **variacao de preco**.
6. **No deposito:** prazo (ate 1 ano), **depositario central em 30 dias**, seguro da lista do art. 22 e quem paga a armazenagem (art. 5º, XII e p.u.).
7. **Entregar:** minuta + quadro "objeto -> inciso do art. 1º §2º -> especie do titulo -> via de cobranca -> onus declarados", **grepando o anexo** antes de transcrever.

## Postura honesta
- **Vender safra futura e assumir risco de preco e de producao.** Nenhuma clausula elimina os dois: ela apenas decide **quem** os suporta. Diga ao cliente qual dos dois ele esta comprando.
- 🔴 **Nao uniformize CPR e CDA/WA.** A Lei 8.929/94 **nunca** chama a CPR de "titulo executivo extrajudicial" — diz **"titulo liquido e certo"**; ja a Lei 11.076/2004 usa a expressao **com todas as letras**. Quem a 8.929 chama de titulo executivo e a **CIR** (Lei 13.986/2020, art. 21). E **nao existe art. 12-A** na 8.929/94: a escrituracao esta nos **arts. 3º-A a 3º-E**.
- 🟡 **Sem numero confirmado — rotear ao `validador-agrario`:** **conflito de garantias sobre a mesma safra** (penhor x CPR x alienacao fiduciaria) e **boa-fe do terceiro adquirente de safra gravada** — **bloco inteiro sem numero** · **penhor rural sem registro** perante terceiros (CC 1.438; DL 167/67, art. 30) · **prescricao da CPR e da cedula rural** — e tambem **do CDA e do WA**, que a Lei 11.076/2004 **nao fixa** · **inciso do CPC 784**: nenhum contem "cedula", "CPR" ou "produto rural" — **cite o artigo, nunca o inciso**.
- 🟡 **Normas so reenviadas pela Lei 11.076/2004** (9.973/2000, 5.764/71, 9.514/97, 12.810/2013 e o **CP art. 178**): cite o **reenvio**, nunca o conteudo delas.

## Cross-link soft + fechamento
Insumo por safra -> `contrato-barter`. Emissao -> `cpr-emissao-e-formalizacao`. Garantias -> `garantias-do-credito-rural`. Execucao -> `execucao-de-cpr-e-cedula-rural`. Defesa -> `embargos-a-execucao-de-cpr`. Integracao -> `contrato-integracao-vertical`. Quebra de safra -> `prova-de-frustracao-de-safra-e-vistoria`. Tributo -> `tributacao-dos-contratos-agrarios`.

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
