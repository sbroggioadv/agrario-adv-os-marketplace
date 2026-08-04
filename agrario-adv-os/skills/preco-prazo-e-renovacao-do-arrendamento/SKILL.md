---
name: preco-prazo-e-renovacao-do-arrendamento
description: "O bloco do arrendamento onde mais se erra: preco dentro do teto legal (15% do valor da terra nua, 30% no parcial, sobre valor CADASTRAL), prazos minimos 3/5/7 do art. 13, II, 'a' do Dec. 59.566/66 — nunca o art. 21 —, renovacao e retomada com os 6 meses + 30 dias, e as DUAS vias de notificacao do art. 22, §3º (RTD da comarca do imovel ou requerimento judicial). Trava o contrato em sacas, vedado pelo art. 18, p.u. Declara a divergencia viva do sujeito dos 30 dias sem resolve-la. Use quando o operador disser qual o preco maximo do arrendamento, posso cobrar em sacas de soja, qual o prazo minimo, o contrato renovou sozinho, quero retomar a fazenda, como notifico o arrendatario, perdi o prazo da notificacao, o arrendatario quer renovar e eu nao quero."
---

# PRECO-PRAZO-E-RENOVACAO-DO-ARRENDAMENTO

> Camada 2. As tres variaveis que o mercado ajusta livremente e a lei **nao deixa**: preco tem **teto**, prazo tem **piso** e a renovacao tem **rito com forma**. Errar qualquer uma nao gera "clausula discutivel" — gera nulidade parcial ou renovacao automatica indesejada.

## Quando ativa / trilha
Roda **junto** com `contrato-arrendamento-rural` na redacao (a minuta e de la; os numeros sao daqui) e **sozinha** quando o caso ja e de renovacao, retomada ou revisao de preco em contrato vigente.

**Fronteiras:** cobrar preco acima do teto ja pago -> `revisao-e-consignacao-do-arrendamento` (revisional e consignacao) · falta de pagamento -> `despejo-agrario` · quota de parceria (que **nao** e preco de arrendamento) -> `contrato-parceria-rural` · carga tributaria na precificacao -> `tributacao-dos-contratos-agrarios`.

## Anexos obrigatorios (context/)
- `context/estatuto-e-decreto-contratos-agrarios.md` (§5 Dec. arts. 16-22 e 30 · §3 ET 95 · **§6 a divergencia dos 30 dias** — **grep o artigo e leia a faixa**).
- `context/cpc-agrario.md` (§2.4 foro de eleicao apos a Lei 14.879/2024 — **grep "art. 63"**; §3 art. 335, prazo da contestacao).
- `context/jurisprudencia-agraria.md` (§3 contratos; §12 o que **nao** tem numero confirmado).

## Base legal ancorada

### Preco — teto duro, e sobre valor CADASTRAL ✅
- **ET 95, XII + Dec. 17, §1º:** ate **15% do valor da terra nua** no arrendamento da **area total**.
- **Dec. 17, §2º:** ate **30% do valor das areas arrendadas** no arrendamento **parcial** de gleba de alta rentabilidade.
- **Dec. 17, §5º:** o preco das **benfeitorias** que compoem o contrato nao excede **15% do valor delas**.
- **Dec. 16:** renda anual ajustada pelas partes dentro desse limite; **§1º correcao anual** a partir da assinatura, na parte referente ao valor da terra.
- ⚠️ A base e o **valor CADASTRAL**, nao o de mercado e nao o do ITR. Calcular sobre valor de mercado estoura o teto sem que ninguem perceba — e o vicio mais comum em contrato de fazenda valorizada.

### 🔴 A FORMA DO PRECO — o "contrato em sacas" e vedado por texto expresso
**Dec. art. 18, caput:** "O preco do arrendamento **so pode ser ajustado em quantia fixa de dinheiro**". O **pagamento** pode ser feito em **frutos**, cujo preco corrente no mercado local — **nunca inferior ao minimo oficial** — equivalha ao aluguel **na epoca da liquidacao**.

**Paragrafo unico, verbatim: "E VEDADO ajustar como preco de arrendamento quantidade fixa de frutos ou produtos, ou seu equivalente em dinheiro."** ✅🔴

Ou seja: **"20 sacas de soja por hectare/ano" como PRECO e nulo**; "renda de R$ X, pagavel em soja pela cotacao local na liquidacao" e valido. A distincao e entre **unidade de conta** (tem de ser dinheiro) e **meio de pagamento** (pode ser fruto equivalente). O **PL 3887/23**, que pretende autorizar a fixacao em produto, **nao e lei** — nao redija como se fosse.

**Dec. art. 19 + ET 92, §7º ✅:** assegurado ao arrendatario **pagar em moeda corrente** se o arrendador exigir equivalencia calculada sobre precos **inferiores aos vigentes na regiao**, ou se comprovada **simulacao ou fraude** — caso em que se paga pelas **taxas minimas da regiao**.

### Prazos minimos — art. 13, II, "a" ✅ (nao o art. 21)
- **3 anos** — lavoura temporaria e/ou pecuaria de pequeno e medio porte; **e toda parceria**.
- **5 anos** — lavoura permanente e/ou pecuaria de grande porte (cria, recria, engorda, extracao de materias-primas de origem animal).
- **7 anos** — **exploracao florestal**.

⚠️ **O art. 21 traz apenas a presuncao de 3 anos** para o contrato por tempo **indeterminado**. Citar o art. 21 como sede dos prazos minimos e a armadilha nº 2 do dominio. **ET 95, I + Dec. 21, §1º:** o prazo termina sempre **apos ultimada a colheita** (ou a paricao, ou a safra de abate), e prorroga-se por forca maior. **Dec. 21, §3º:** cultura nova que exceda o prazo exige **ajuste previo**.

### Renovacao e retomada — rito com forma, e a forma tem DUAS vias ✅
**ET 95, IV + Dec. 22:** o arrendador que nao quiser renovar **notifica ate 6 meses antes** do vencimento, **instruindo a notificacao com copia autentica das propostas** recebidas de terceiros. Sem essa notificacao, o contrato **se renova automaticamente**, ressalvada manifestacao de desistencia ou nova proposta **nos 30 dias** seguintes ao termino do prazo para notificar.

**Dec. 22, §3º — FORMA (verbatim):** as notificacoes, a desistencia e a proposta "deverao ser feitas **por carta atraves do Cartorio de Registro de Titulos e Documentos da comarca da situacao do imovel**, **ou por requerimento judicial**".
⚠️ **Sao DUAS vias alternativas.** Tratar o RTD como caminho unico descarta a via judicial — util quando o arrendatario se oculta ou o RTD da comarca e inacessivel.

**Retomada — Dec. 22, §2º + ET 95, V ✅:** os direitos do arrendatario nao prevalecem se, **ate 6 meses antes** do vencimento, o arrendador declarar por notificacao a intencao de retomar para **explorar diretamente**, para **cultivo direto e pessoal** (Dec. arts. 7º e 8º — inclui **residir no imovel**) **ou por descendente**. **§4º: a insinceridade do pedido, provavel por qualquer meio, gera perdas e danos** — e no despejo o **art. 32, VIII** exige sinceridade **comprovada em Juizo**.

**Dec. art. 30 ✅:** desapropriacao **parcial** durante o contrato -> **reducao proporcional da renda OU rescisao**, a escolha **do arrendatario**.

### Foro da minuta — regra nova de 2024
Toda clausula de foro que esta skill ajudar a redigir segue o **CPC art. 63, §1º (red. Lei 14.879/2024)**: exige **pertinencia** com domicilio/residencia de uma das partes ou com o **local da obrigacao**; e o **§5º** torna o "juizo aleatorio" **declinavel de oficio**. Detalhe em `contrato-arrendamento-rural`.

## Passo a passo / o que produzir
1. **Identificar a fase** (AskUserQuestion, botoes): **redacao nova** · **renovacao a vencer** · **retomada** · **preco a revisar** · **notificacao ja perdida**.
2. **Classificar a exploracao** (temporaria / permanente / pecuaria de pequeno-medio / de grande porte / florestal) -> fixa o **prazo minimo**.
3. **Apurar o valor CADASTRAL** e calcular o teto (15% ou 30%); conferir se ha benfeitorias no contrato (mais 15% sobre elas).
4. **Auditar a forma do preco:** se o instrumento fixa **quantidade de frutos como preco**, sinalizar a vedacao do art. 18, p.u. e **reescrever** como quantia em dinheiro com pagamento equivalente em frutos.
5. **Montar o calendario da renovacao** — data-limite dos 6 meses, os 30 dias, e a via escolhida (RTD da comarca do imovel **ou** requerimento judicial), com prova de recebimento.
6. **Entregar:** clausulas de preco, correcao, prazo e renovacao + **minuta da notificacao** + calendario com as datas-limite; sinalizar prazos ao `calendario-safra-e-prazos-criticos`.

## Postura honesta
- 🔴 **Divergencia viva do sujeito dos 30 dias — o plugin NAO resolve, declara.** **ET 95, IV** atribui os 30 dias ao **"arrendador"**; **Dec. 22, §1º** ao **"arrendatario"**. A troca e **literal, verificada nos dois compilados**, e **nenhuma jurisprudencia pacificadora foi confirmada**. Na peca: declare a controversia, argumente com o texto que favorece o cliente e **sinalize o risco ao cliente por escrito**. Quem afirma qual dos dois prevalece esta inventando.
- **O teto do preco nao se renuncia** (Dec. 2º, p.u.). Contrato assinado acima do teto nao "convalida pelo pagamento": abre consignacao e repeticao — ver `revisao-e-consignacao-do-arrendamento`.
- **A retomada nao e formalidade.** Notificar em 6 meses **sem sinceridade real** (retomar e arrendar a terceiro) gera perdas e danos (§4º) e derruba o despejo (art. 32, VIII).
- 🟡 **Sem numero confirmado — "a confirmar" e rotear ao `validador-agrario`:** **requisitos formais minimos da notificacao** ao arrendatario · **preferencia na RENOVACAO** (ET art. 95) como precedente · quem prevalece na divergencia dos 30 dias.

## Cross-link soft + fechamento
Minuta -> `contrato-arrendamento-rural`. Preco cobrado a maior -> `revisao-e-consignacao-do-arrendamento`. Falta de pagamento e retomada judicial -> `despejo-agrario`. Venda no curso do contrato -> `preferencia-do-arrendatario`. Quota -> `contrato-parceria-rural`. Tributo -> `tributacao-dos-contratos-agrarios`. Datas -> `calendario-safra-e-prazos-criticos`.

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
