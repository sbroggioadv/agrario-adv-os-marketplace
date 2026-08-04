---
name: cpr-emissao-e-formalizacao
description: "Emite e audita a Cedula de Produto Rural — fisica e financeira — pelos requisitos formais do art. 3º da Lei 8.929/94, pelo regime de garantias em clausula aberta e pelo registro obrigatorio em entidade autorizada pelo BCB, cujo descumprimento faz a CPR perder validade e eficacia. Aponta os dispositivos revogados que ainda circulam (art. 5º, I a III) e o artigo que nao existe (12-A). Use quando o operador disser vou emitir uma CPR, conferir a CPR, a CPR e valida, registro da CPR, CPR fisica ou financeira, barter, o titulo tem vicio, auditar cedula de produto rural."
---

# CPR-EMISSAO-E-FORMALIZACAO — emitir e auditar o titulo

> Camada 3. Porta de entrada do titulo: **emite** a CPR blindada e **audita** a CPR recebida, achando o vicio antes de ele virar embargos.

## Quando ativa / trilha
Antes de assinar (lado emitente ou credor) ou ao receber um titulo para conferir. Apoia-se na `base-credito-rural-e-lei-do-agro`.

**Diferenca da vizinha:** a `base-credito-rural-e-lei-do-agro` diz **qual e a lei vigente** sobre o titulo; esta skill **emite e audita o documento**. Execucao e `execucao-de-cpr-e-cedula-rural`; defesa, `embargos-a-execucao-de-cpr`.

## Anexos obrigatorios (context/)
- `context/lei-do-agro-e-cpr.md` (**§1 CPR arts. 1º-19** · §5 armadilhas de citacao — **grep o artigo e leia a faixa**).
- `context/cpc-agrario.md` (**§9 art. 784**, e o **§4º** que dispensa testemunhas em titulo eletronico).
- `context/jurisprudencia-agraria.md` (REsp 2.178.558-MT, para a CPR barter) · `context/mp-1376-2026.md` (art. 6º, aquisicao de CPR financeira) — ⚠️ **MP 1.376/2026 em Comissao Mista, pendente de conversao/alteracao/caducidade**.

## Base legal ancorada ✅

### O que a CPR pode representar — art. 1º
Promessa de entrega de produto rural. ⚠️ **O §2º foi ampliado em 2022**: os incisos **III (industrializacao)** e **IV (insumos, maquinas e armazenagem)** sao da **Lei 14.421/2022** e alargaram o alcance do titulo. Emissores (**art. 2º**): **I** produtor rural (PF/PJ), cooperativa agropecuaria e associacao de produtores; **II** pessoas naturais ou juridicas que beneficiam ou promovem a **primeira industrializacao** dos produtos rurais, ou que empreendem as atividades dos **incisos II, III e IV do §2º do art. 1º**.

### ⭐ Art. 3º — os DEZ requisitos formais (onde nasce a nulidade)
Sao dez incisos. Dois pontos que a pratica ignora:
- ⚠️ **Inciso IV — o local onde sera desenvolvido o produto rural.** Exigencia de 2020 e **gancho de nulidade subutilizado**: descricao generica ("fazenda do emitente", municipio sem matricula) e vicio arguivel.
- **§4º:** no registro de **garantia real**, a assinatura eletronica tem de ser **avancada ou qualificada** — a simples nao serve.

**Arts. 3º-A a 3º-E:** cartular x escritural, escrituracao sob o BCB, certidoes. 🚨 **NAO existe art. 12-A** na Lei 8.929/94 — a materia esta nos 3º-A a 3º-E. **Art. 3º-B, §3º:** os requisitos de seguranca da certidao da escrituradora **lhe conferem liquidez, certeza e exigibilidade** — e o que instrui a execucao da CPR escritural.

### 🚨 Art. 5º — garantias em CLAUSULA ABERTA
Texto vigente (red. Lei 13.986/2020): a CPR admite **quaisquer dos tipos de garantia previstos na legislacao**. 🚨 **Os incisos I, II e III (hipoteca, penhor, alienacao fiduciaria) estao REVOGADOS desde 2020** — cita-los e citar dispositivo morto, e e uma das armadilhas mais frequentes do dominio. **§2º** (2022): garantias cedulares por **instrumento publico ou particular, independentemente do valor**. **§3º:** a CPR financeira pode **fixar limite de credito e garantir divida futura** de outras CPRs vinculadas.

### ⭐ Lei 8.929, art. 12 — o REGISTRO que decide a validade
"Para **nao perder validade e eficacia**", a CPR e seus aditamentos vao a registro ou deposito em **entidade autorizada pelo BCB**: **10 dias uteis** se emitida ate **10/08/2022**; **30 dias uteis** se emitida a partir de **11/08/2022** (red. Lei 14.421/2022). **Vale a redacao da data da emissao** — datar a emissao e o primeiro ato da auditoria.
- **§1º e §4º:** hipoteca, penhor rural e **AF sobre bem imovel** (e a AF de produtos agropecuarios do art. 8º) vao ao **cartorio de registro de imoveis** da localizacao dos bens.
- **§2º:** "a validade e eficacia da CPR **nao dependem de registro em cartorio, que fica dispensado**" — ao RI vao **as garantias reais**, que para valer contra terceiros sao averbadas em **3 dias uteis** da apresentacao.
- **§6º:** a dispensa de registro que o CMN pode conceder **nao se aplica a CPR emitida apos 31/12/2023**.

### Natureza, via e os demais dispositivos
- **Arts. 4º e 4º-A:** a CPR e **titulo liquido e certo**; a **financeira** e exigivel no vencimento (§1º) e cobra-se **por quantia certa** (§2º). **Art. 15: a CPR fisica cobra-se por execucao para ENTREGA DE COISA INCERTA.**
- ⚠️ **A Lei 8.929/94 NUNCA chama a CPR de "titulo executivo extrajudicial"** — leitura integral do compilado: ela diz **"titulo liquido e certo"**. Quem a lei chama assim e a **CIR** (Lei 13.986/2020, art. 21).
- **Art. 10 — normas cambiais:** os **endossos devem ser completos**; ⭐ os **endossantes nao respondem pela entrega do produto, apenas pela existencia da obrigacao**; **dispensado o protesto** para o regresso contra avalistas. Na CPR **escritural**, a transferencia de titularidade **produz os efeitos do endosso**.
- **Lei 8.929, art. 13:** a **entrega antecipada depende de anuencia do credor**. **Art. 14:** vencimento pelo **inadimplemento de qualquer** obrigacao do emitente.
- ⚠️ **Art. 17 — crime de estelionato:** declaracao falsa ou inexata sobre a propria qualificacao ou sobre os bens em garantia, **inclusive omitir que ja estao gravados**. Adverte-se o cliente por escrito antes da emissao.
- **Art. 18:** os bens vinculados **nao sao penhorados ou sequestrados por outras dividas** — cabe a qualquer interessado denunciar a cedula, sob pena de responder pelos prejuizos.
- **Art. 19 integralmente revogado** (a materia migrou para o **art. 3º-D**); **art. 19-A consta VETADO**.
- ⭐ **CPC 784, §4º** (Lei 14.620/2023): em titulo constituido por meio eletronico admite-se **qualquer modalidade de assinatura eletronica prevista em lei, dispensada a assinatura de testemunhas** quando a integridade for conferida por **provedor de assinatura**. Derruba a objecao "documento particular sem duas testemunhas" contra CPR digital.

## Passo a passo / o que produzir
**Ao EMITIR — clausulado minimo:** qualificacao completa (art. 3º) · **local onde sera desenvolvido o produto rural** (inciso IV), com matricula e coordenadas · produto, quantidade, qualidade e padrao · local e prazo de entrega · **garantia pelo art. 5º em clausula aberta**, jamais pelos incisos revogados · nivel de assinatura eletronica compativel (§4º) · previsao de registro no BCB no prazo.

**Ao AUDITAR — laudo do titulo, nesta ordem:**
1. **Datar a emissao** — define o prazo do art. 12 da Lei 8.929 (10 x 30 dias uteis) e a redacao aplicavel.
2. **Especie**: fisica x financeira x barter (art. 11) — decide a via e a sujeicao a RJ.
3. **Rodar os dez incisos do art. 3º**, com foco no **IV**; conferir o **§4º** se ha garantia real registrada.
4. **Conferir o registro no BCB** e a data — fora do prazo, a CPR **perde validade e eficacia**.
5. **Conferir as garantias**: averbacao no RI (§§1º, 2º e 4º), existencia de onus preexistente (art. 17), e se ha vinculacao dupla sobre a mesma safra.
6. **Fechar o quadro:** especie · dispositivo vigente · via de cobranca · vicio encontrado · selo (✅ / 🟡 / 🔴).

## Postura honesta
- 🚫 **GAP INTRANSPONIVEL — prescricao da CPR.** Nao ha dispositivo de prescricao ancorado na Lei 8.929/94. **Nao deduza prazo cambial nem do CC por memoria** — marque "a confirmar" e roteie ao `validador-agrario`.
- 🟡 **Cite o CPC 784 pelo ARTIGO, nunca pelo inciso** — nenhum dos doze incisos nomeia CPR; a executividade vem de **lei especial**.
- 🟡 **Sem numero confirmado** (lista integral no `validador-agrario`): **conflito de garantias sobre a mesma safra** (penhor x CPR x AF) · **boa-fe do terceiro adquirente de safra gravada** · **penhor rural sem registro** (CC 1.438; DL 167/67 art. 30).
- ⚠️ **FGS:** os percentuais **4% + 4% + 2%**, a cota terciaria e o credor como integrante foram **revogados pela Lei 14.421/2022**. Nao reproduza clausula antiga.
- ⚔️ **Racha declarado:** CPR fisica e barter sao **extraconcursais** (art. 11 + **REsp 2.178.558-MT**, 3ª Turma, 09/09/2025, Info 867) — **mas** ha decisao do **TJ/GO** tratando a cedula rural financeira como **concursal**, e o **ACT CNJ-MAPA 013/2026 reconhece divergencias entre tribunais**. O REsp e **de Turma, nao repetitivo**. Declare os dois lados ao cliente antes de estruturar a operacao.

## Cross-link e fechamento
Lei vigente sobre o titulo -> `base-credito-rural-e-lei-do-agro`. Cedulas -> `cedulas-de-credito-rural`. Garantias e leilao -> `garantias-do-credito-rural`. Afetacao e CIR -> `patrimonio-rural-em-afetacao-e-cir`. Cobranca -> `execucao-de-cpr-e-cedula-rural`; defesa -> `embargos-a-execucao-de-cpr`. Barter -> `contrato-barter`. Sujeicao a RJ -> `rj-sujeicao-de-creditos-agro`. Troca de CPR na janela da **MP 1.376/2026** (⚠️ **pendente em Comissao Mista**) -> `renegociacao-mp-1376`.

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
