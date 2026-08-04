---
name: defesa-na-vistoria-e-laudo-de-produtividade
description: "Defesa do proprietario na fase administrativa da vistoria e do laudo do INCRA — a etapa em que a desapropriacao se derruba antes do decreto e antes da acao. Testa a insuscetibilidade (pequena e media propriedade, propriedade produtiva), recalcula GUT e GEE com a area aproveitavel correta, aciona o direito subjetivo a atualizacao do laudo com mais de 5 anos e o projeto tecnico aprovado 6 meses antes da comunicacao. Entrega impugnacao administrativa, requerimento de atualizacao do laudo e roteiro de contra-laudo. Use quando o operador disser o INCRA notificou vistoria, veio laudo de improdutividade, meu imovel e produtivo, o laudo esta velho, GUT e GEE, pequena propriedade nao desapropria, quero derrubar a desapropriacao antes do decreto, /desapropriacao."
---

# DEFESA-NA-VISTORIA-E-LAUDO-DE-PRODUTIVIDADE

> Camada 5. A desapropriacao se ganha barato **antes do decreto** — depois dele a discussao vira preco. Aqui: qualificacao do imovel, indices e laudo.

## Quando ativa / trilha
O INCRA comunicou a vistoria, ja vistoriou, ou apresentou laudo de improdutividade — e **ainda nao ha decreto declaratorio nem acao**. Roda depois da `base-funcao-social-e-reforma-agraria`, que entrega os indices e a redacao vigente.

**Diferenca das vizinhas:** `nulidades-do-processo-expropriatorio` ataca o **procedimento**; esta ataca o **merito da produtividade e a insuscetibilidade**; `rito-lc-76-93-e-contestacao` so entra **depois de ajuizada** a acao. As tres se somam.

Fixe a fase por **AskUserQuestion** (lista fechada): **comunicacao recebida** · **vistoria feita, sem laudo** · **laudo entregue** · **decreto publicado** (esta ultima vira `rito-lc-76-93-e-contestacao`).

## Anexos obrigatorios (context/)
- **`context/lei-8629-93-e-cf-184-191.md`** (§1 art. 6º §9º · §2 GUT e GEE · §3 art. 7º · §5 art. 4º · §8 arts. 10 a 12 · §9 CF 184-191 · §10 lista 🟡 · §11 armadilhas — **grep o artigo e leia a faixa**).
- `context/jurisprudencia-agraria.md` (§6 **ADI 2.332** e o §2º do art. 15-A · Sumula 354 · §10 rachas — **grep o numero e leia a faixa**).
- **`context/lc-76-93-desapropriacao.md`** (§3 **art. 5º, IV, "b"** · §8 **art. 9º, §1º** · §2 **art. 4º** · §1 **art. 2º, §2º** — **grep o artigo e leia a faixa**).
- `context/cpc-agrario.md` (§6 **art. 381**) · `context/codigo-florestal-12651.md` (APP e RL fora da area aproveitavel) — **grep o artigo e leia a faixa**.

## Base legal ancorada

### 🔴 Art. 6º, §9º — laudo com mais de 5 anos: direito subjetivo, nao retorica
Red. **Lei 14.757/2023**: os laudos que indiquem o **grau de utilizacao da terra e o grau de eficiencia na exploracao** produzidos **ha mais de 5 anos** devem, **a pedido do proprietario**, ser **atualizados** conforme as condicoes atuais da propriedade.

E a **alteracao mais recente da Lei 8.629** (nada de 2024-2026 a alterou): transforma "o laudo esta velho" de retorica em **direito expresso**, exercivel por requerimento protocolado.

⚠️ **Armadilha do compilado:** ha **duas entradas de §9º**, uma **(VETADO)** e a **redacao vigente**, ambas da Lei 14.757/2023. Cite a vigente; leia a faixa antes.

### Propriedade produtiva — os dois indices, simultaneos ✅
**GUT >= 80%** (art. 6º, §1º — area efetivamente utilizada sobre area aproveitavel total) e **GEE >= 100%** (§2º), exigidos **ao mesmo tempo**. As formulas estao no anexo, §2. O **§3º** define area efetivamente utilizada e inclui (**V**) areas **em formacao ou recuperacao tecnicamente conduzidas e comprovadas por documentacao e ART**.

🎯 **§7º — a valvula:** **nao perde a qualificacao de produtiva** o imovel que, por **forca maior, caso fortuito ou renovacao de pastagens tecnicamente conduzida**, deixar de atingir o **GEE** no ano. Seca, geada e frustracao documentada entram aqui — com laudo e ART, nao com alegacao.

### Art. 7º — o projeto tecnico que afasta a desapropriacao ✅
Nao e passivel de desapropriacao o imovel que comprove implantar projeto (**I**) de profissional habilitado e identificado, (**II**) cumprindo o **cronograma fisico-financeiro original, sem prorrogacoes**, (**III**) com **no minimo 80% da area aproveitavel** utilizada em ate **3 anos** (culturas anuais) ou **5** (permanentes), (**IV**) **aprovado pelo orgao federal no minimo 6 meses antes da COMUNICACAO** dos §§2º e 3º do art. 2º. **Paragrafo unico:** os prazos do inciso III admitem prorrogacao **de ate 50%**, com aprovacao anual.

⚠️ **Marco temporal trocado derruba a tese:** a redacao **original** falava em 6 meses antes do **decreto**; a **MPv 2.183-56/2001** antecipou para a **comunicacao da vistoria**. Escrever "antes do decreto" e citar redacao superada — e **encurta indevidamente a janela do cliente**.

### Art. 10 **da Lei 8.629/93** — a area nao aproveitavel e alavanca de GUT ✅
Cinco categorias saem do calculo: instalacoes **nao** produtivas · areas imprestaveis · **exploracao mineral** · **preservacao permanente** e demais protegidas por lei ambiental · **vegetacao nativa conservada** nao protegida por lei e nao explorada (**inciso V, Lei 14.119/2021**). Texto no anexo, §8. Cada hectare corretamente excluido **reduz o denominador e eleva o GUT**. ⚠️ **Nao e o art. 10 da LC 76/93** (acordo homologado).

### Insuscetibilidade — teste antes de discutir indice ✅🔴
**Lei 8.629/93, art. 4º:** pequena = **ate 4 modulos fiscais**; media = **acima de 4 e ate 15**. **§1º:** ambas **insuscetiveis** **se o proprietario nao possuir outra propriedade rural**. **CF 185** acrescenta a **propriedade produtiva**.

🔴 **A mudanca de 2017 que o senso comum nao acompanhou:** a pequena era "**entre 1 e 4**"; a **Lei 13.465/2017 eliminou o piso de 1**. Imovel **abaixo de 1 modulo fiscal e pequena propriedade insuscetivel**.

### 🔴🔴 A impugnacao de hoje define a pericia de amanha — LC 76/93, art. 9º, §1º ✅
Ajuizada a acao, a **pericia e ADSTRITA aos pontos impugnados** do laudo administrativo. **Ponto nao impugnado e ponto que a pericia nao alcanca** — e a impugnacao que esta skill produz e o rascunho da que ira na contestacao.

🔴 **Impugnar "genericamente o valor" fecha a porta** para discutir depois area, cobertura florestal, benfeitorias por especie, pastos e semoventes. **Impugne por ITEM**, espelhando o **art. 5º, IV**: (**a**) plantas e memorial · (**b**) benfeitorias, culturas, **pastos**, **cobertura florestal**, **semoventes** · (**c**) valores **discriminados**. **Cada alinea nao impugnada e um capitulo perdido**, e a "b" e municao: **laudo que ignora pasto artificial, cobertura florestal ou rebanho descumpre o inciso IV, "b"**.

⚠️ **Dois avisos de momento:** o **assistente tecnico se indica na resposta a citacao** (art. 6º, II), e a **extensao da parcial para total so cabe na contestacao** (art. 4º) — imovel parcialmente atingido, avise o cliente **ja nesta fase**, antes que o prazo passe.

🎯 **Art. 2º, §2º:** apos o decreto, vistoria **com forca policial exige previa autorizacao judicial**, e o expropriante **responde por perdas e danos** de seus agentes — aparato policial sem autorizacao nos autos e **fato a documentar**.

### Art. 12, §3º da Lei 8.629/93 — o laudo tem autor, e ele responde ✅
O **Laudo de Avaliacao** e subscrito por **Engenheiro Agronomo com ART**, que responde **civil, penal e administrativamente** por superavaliacao ou fraude. Identificar subscritor e ART e passo de impugnacao, nao formalidade.

## Passo a passo / o que produzir
1. **Qualificar o imovel (R1)** — area em **modulos fiscais**, UF, exploracao e **se o proprietario possui outra propriedade rural**: e o que aciona o art. 4º, §1º e o art. 185, I. Menos de 1 modulo: pequena propriedade.
2. **Datar o laudo.** Mais de 5 anos ⇒ **requerimento de atualizacao do art. 6º, §9º**, protocolado com prova, antes de qualquer outra peca.
3. **Recalcular o GUT** atacando a **area aproveitavel** pelo art. 10.
4. **Recalcular o GEE** conferindo os indices de rendimento e lotacao aplicados. O **art. 11** manda ajusta-los periodicamente — e a base ✅ da tese de desatualizacao.
5. **Nao atingiu o GEE?** Testar o **§7º** antes de qualquer outra linha, com ART, boletins climaticos e serie historica.
6. **Conferir o projeto tecnico**: aprovado **6 meses antes da comunicacao**, cronograma cumprido **sem prorrogacao**, 80% da area aproveitavel na janela de 3 ou 5 anos.
7. **Congelar a prova que se perde**: **CPC 381**, quando a lavoura, o rebanho ou a pastagem do ano nao existirao mais na epoca da pericia judicial.
8. **Entregar:** impugnacao administrativa ao INCRA **por item** (art. 5º, IV, "a", "b", "c") + requerimento de atualizacao do laudo + roteiro de contra-laudo com ART + quadro final (indice · valor · dispositivo **com o diploma colado** · faixa · selo).

## Postura honesta
- 🟡 **Nao cite numero de IN do INCRA ou do MAPA.** Os indices de rendimento e lotacao vem de instrucoes normativas baseadas em dados dos anos 1970-80, e **nao foi verificado qual vigora em 08/2026**. A tese da desatualizacao se sustenta **pelo art. 11**, que e ✅ — e so por ele.
- 🟡 **Nao ha precedente confirmado** do STF ou do STJ sobre a insuscetibilidade do imovel produtivo (CF 185, II). A regra e **constitucional expressa**; sustente-a pelo texto e **nao invente mandado de seguranca emblematico**.
- ⚔️ **A tese da improdutividade corta contra o cliente na etapa seguinte.** A **ADI 2.332** declarou **constitucional** o §2º do art. 15-A: **GUT e GEE iguais a zero afastam os juros compensatorios**; o **Tema 280/STJ** diz que a improdutividade nao os afasta — **tensao declarada, nao resolvida**. Admitir baixa utilizacao tem preco: veja em `indenizacao-tda-juros-e-honorarios`.
- ⚠️ **Contra-laudo nao substitui pericia judicial.** Aqui ele impugna; ajuizada a acao, o justo preco se fixa por **perito do juizo**.
- ⚠️ **A Sumula 354/STJ e sobre INVASAO como causa de suspensao — nao sobre notificacao previa da vistoria.** Nenhuma sumula sobre notificacao foi localizada: **nao invente numero**.
- ⚠️ **A impugnacao administrativa nao e rascunho descartavel:** pelo **art. 9º, §1º da LC 76/93** ela define o objeto da pericia judicial. Generalidade aqui **preclui prova la**.

## Cross-link e fechamento
Vicio de procedimento -> `nulidades-do-processo-expropriatorio`. Acao ajuizada -> `rito-lc-76-93-e-contestacao`. Preco e TDA -> `indenizacao-tda-juros-e-honorarios`. Ocupacao sem processo -> `desapropriacao-indireta`. Dossie de perda -> `prova-de-frustracao-de-safra-e-vistoria`. Base -> `base-funcao-social-e-reforma-agraria`. APP e RL -> `app-reserva-legal-e-areas-consolidadas`. Precedentes -> `jurisprudencia-agraria`.

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
