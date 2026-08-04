# Anexo — Lei 11.076/2004 (CDA · WA · CDCA · LCA · CRA)

> **15º anexo do plugin.** Fecha o **gap declarado em letra vermelha pela `compra-venda-de-safra-e-armazenagem`**: até aqui a Lei 11.076/2004 **não existia em `context/`** — varredura confirmava que nenhum dos 13 anexos anteriores continha uma linha sobre **CDA** ou **Warrant Agropecuário**, e a única menção à lei era uma célula de tabela em `lei-do-agro-e-cpr.md` registrando que a Lei 13.986/2020 a alterou. A skill era obrigada a dizer "🔴 não cite artigo da Lei 11.076/2004". **A partir deste anexo, pode — nos limites do Guard.**
>
> **Fonte:** **Texto compilado** do Planalto capturado em **02/08/2026** — `https://www.planalto.gov.br/ccivil_03/_ato2004-2006/2004/lei/l11076.htm` (HTTP 200, 243.880 bytes). Transcrição **verbatim**, não paráfrase.
>
> **Legenda:** ✅ conferido verbatim, **redação vigente** · 🟡 não confirmado (não citar sem checar) · 🔴 pegadinha / redação revogada que a página **exibe ao lado** da vigente.

---

## ⚠️ AVISO 1 — 🔴 ESTE É O ANEXO MAIS MINADO DO PLUGIN. LEIA ANTES DE CITAR

A página do Planalto desta lei exibe **239 blocos de texto riscado** (revogado ou superado) **lado a lado com o texto vigente** — contados por comando na captura, com as tags `<strike>` balanceadas (239 aberturas / 239 fechamentos). São **~43 KB de texto morto** convivendo com **~45 KB de texto vivo** na mesma página.

Nenhuma outra norma do plugin chega perto disso. Para efeito de comparação: a **Lei 13.288/2016** (anexo irmão, `integracao-vertical-13288.md`) tem **zero** blocos riscados.

**Por que isso morde tanto aqui:** vários dispositivos aparecem **três e quatro vezes** na página — a redação original, a de uma Medida Provisória, e a da Lei que converteu a MP. O art. 15, por exemplo, aparece **cinco vezes** (quatro riscadas). Um modelo que leia a página "de cima para baixo" tende a fixar a **primeira** ocorrência, que é quase sempre a **mais antiga e revogada**.

**Método usado nesta captura (e que o `validador-agrario` deve repetir em qualquer reconferência):** a vigência de cada dispositivo foi determinada pela **profundidade de aninhamento da tag `<strike>` no HTML** naquele exato deslocamento — profundidade 0 = vigente, profundidade > 0 = riscado. **Não** por leitura visual, que é onde o erro nasce.

## ⚠️ AVISO 2 — as 8 leis que alteraram esta e o que cada uma fez

| Alterou a Lei 11.076/2004 | Peso na captura |
|---|---|
| Lei 11.524/2007 | inclui §§ 2º-4º do art. 17 (execução do penhor do WA) e reescreve o art. 1º, §2º |
| Lei 13.331/2016 (conv. MP 725/2016) | reestrutura o art. 23 (p.ú. → §§) |
| Lei 13.606/2018 | art. 23, §2º (depois revogado) |
| **Lei 13.986/2020 — a Lei do Agro (art. 43)** | **a maior**: 37 redações novas + 52 inclusões + 7 revogações. Converte a **MP 897/2019**, cujo texto **continua exibido riscado** |
| Lei 14.317/2022 | revoga o art. 52 e anexos (Taxa de Fiscalização CVM) |
| Lei 14.421/2022 | art. 5º, XVII (assinatura eletrônica); art. 23, §5º (VETADO) |
| **Lei 14.430/2022 — marco da securitização (conv. MP 1.103/2022)** | **destrói o regime do CRA nesta lei** — ver §6 |
| Lei 14.937/2024 | revoga o art. 23, §2º e seus incisos |

🔴 **A "Lei 13.986/2020, art. 43" é o dispositivo DA LEI DO AGRO que alterou esta lei** — não confundir com o **art. 43 desta Lei 11.076/2004**, que existe, é vigente e trata de **distribuição pública do CDCA, da LCA e do CRA** (§7). A tabela de `lei-do-agro-e-cpr.md` registra a primeira; este anexo transcreve a segunda.

## ⚠️ AVISO 3 — grep o artigo e leia a faixa. Nunca despeje o anexo inteiro

Material de consulta pontual. **Faça `grep` do número do artigo e leia só a faixa.**

## ⚠️ AVISO 4 — os 6 artigos SEM TEXTO VIGENTE (a página os exibe inteiros, riscados)

Verificado por comando, profundidade de `<strike>` em cada ocorrência:

| Artigo | Situação | Revogado por |
|---|---|---|
| **art. 20** | sem texto vigente | Lei 13.986/2020 (conv. MP 897/2019) |
| **art. 37** (requisitos do CRA) | sem texto vigente | **Lei 14.430/2022** (conv. MP 1.103/2022) |
| **art. 38** (companhias securitizadoras) | sem texto vigente | **Lei 14.430/2022** |
| **art. 39** (regime fiduciário) | sem texto vigente | **Lei 14.430/2022** |
| **art. 40** (termo de securitização) | sem texto vigente | **Lei 14.430/2022** |
| **art. 52** (Taxa de Fiscalização CVM) + Anexos I e II | sem texto vigente | Lei 14.317/2022 (conv. MP 1.072/2021) |

⛔ **Não cite nenhum deles.** Todos aparecem com texto completo e legível na página.

🔴 **Armadilha específica do art. 38:** a página **também** exibe um "**Art. 38.**" **não riscado** — mas ele **não pertence a esta lei**. É o texto novo do **art. 38 da Lei 9.514/97**, citado entre aspas dentro do **art. 53** desta lei (que altera a Lei 9.514/97). Verificado no contexto: vem logo após `"Art. 22. ..."` e termina com `(NR)`. Quem fizer `grep "Art. 38"` acha o dispositivo vivo **de outra lei** e conclui, errado, que o art. 38 da 11.076 sobreviveu.

---

## 1. CDA e WA — instituição, natureza e o que cada um é

- **Art. 1º** ✅ — "Ficam instituídos o **Certificado de Depósito Agropecuário - CDA** e o **Warrant Agropecuário - WA**."
  - **§ 1º** ✅ — "O **CDA** é título de crédito representativo de **promessa de ENTREGA de produtos agropecuários**, seus derivados, subprodutos e resíduos de valor econômico, **depositados em conformidade com a Lei nº 9.973, de 29 de maio de 2000**."
  - **§ 2º — REDAÇÃO VIGENTE (Lei nº 11.524, de 2007)** ✅ — "O **WA** é título de crédito **representativo de promessa de PAGAMENTO EM DINHEIRO** que confere **direito de penhor sobre o CDA correspondente, assim como sobre o produto nele descrito**."
  - **§ 3º** ✅ — "O CDA e o WA são **títulos unidos, emitidos simultaneamente pelo depositário, a pedido do depositante**, podendo ser transmitidos **unidos ou separadamente, mediante endosso**."
  - **§ 4º** ⭐ ✅ — "**O CDA e o WA são títulos executivos extrajudiciais.**"
  - 🔴 **PEGADINHA DE PLANALTO (§2º):** a página exibe a redação **original** riscada — "O WA é título de crédito que confere direito de penhor **sobre o produto** descrito no CDA correspondente". A vigente é **mais larga**: o penhor recai **sobre o CDA** *e* sobre o produto, e o WA passou a ser **promessa de pagamento em dinheiro**. Citar a de 2004 estreita a garantia do cliente.
  - **No agrário — o achado que muda a peça:** o **§4º diz, com todas as letras, "títulos executivos extrajudiciais"**. Isso é o **oposto** do que vale para a CPR: a Lei 8.929/94 **nunca** usa essa expressão (diz "título líquido e certo"), regra dura que a `compra-venda-de-safra-e-armazenagem` e o `anti-alucinacao-agraria` guardam. **A distinção agora é textual e citável:** para **CDA/WA, CDCA, LCA e CRA** a qualificação de título executivo extrajudicial **está na lei**; para a **CPR, não está**. Não uniformize os dois regimes.
  - **Usa:** `compra-venda-de-safra-e-armazenagem` · `execucao-de-cpr-e-cedula-rural` · `garantias-do-credito-rural` · `validador-agrario`.

- **Art. 2º** ✅ — "Aplicam-se ao CDA e ao WA as **normas de direito cambial** no que forem cabíveis e o seguinte: **I** - os **endossos devem ser completos**; **II** - os **endossantes não respondem pela entrega do produto**, mas, tão-somente, **pela existência da obrigação**; **III** - é **dispensado o protesto cambial** para assegurar o direito de regresso contra endossantes e avalistas." (**3 incisos**, contados na fonte)
  - **No agrário:** o **II** é decisivo em cadeia de endossos — quem endossou **não garante que o produto será entregue**. Cobrar entrega do endossante é errar o polo passivo.

- **Art. 3º — REDAÇÃO VIGENTE (Lei nº 13.986, de 2020)** ✅ — "O CDA e o WA **poderão ser emitidos sob a forma cartular ou escritural**." — **I - (revogado); II - (revogado).**
  - **§ 1º** ✅ (Lei 13.986/2020) — "A emissão na forma escritural ocorrerá por meio do lançamento em **sistema eletrônico de escrituração** gerido por entidade autorizada pelo **Banco Central do Brasil** a exercer atividade de escrituração."
  - **§ 2º** ✅ (Lei 13.986/2020) — "O CDA e o WA emitidos sob a forma **cartular assumirão a forma escritural enquanto permanecerem depositados em depositário central**."
  - 🔴 **PEGADINHA DE PLANALTO (art. 3º — TRÊS camadas):** a página exibe (a) a redação **original de 2004** ("O CDA e o WA **serão**: I - cartulares, antes de seu registro...; II - escriturais ou eletrônicos, enquanto permanecerem registrados..."), (b) a redação da **MP 897/2019**, e (c) a vigente, da **Lei 13.986/2020**. **Só a (c) vale**, e nela os **incisos I e II estão expressamente "(revogado)"**. Citar "o CDA será cartular antes do registro e escritural depois" é citar a redação de 2004 — a lógica hoje é **cartular OU escritural, por opção**, com conversão automática pelo §2º.
  - ⚠️ **A página traz o erro de digitação do próprio Planalto** — "(**Redação da** pela Lei nº 13.986, de 2020", sem o "d" de "dada" e sem parêntese de fechamento. É defeito da fonte, não do texto legal.
  - **Usa:** `compra-venda-de-safra-e-armazenagem` · `cpr-emissao-e-formalizacao`.

- **Arts. 3º-A, 3º-B e 3º-C** ✅ (todos **Incluídos pela Lei 13.986/2020**) — competências do **Banco Central** sobre a atividade de escrituração (3º-A), **liquidação do pagamento** em favor do legítimo credor no âmbito do SPB (3º-B) e conteúdo obrigatório do **sistema eletrônico de escrituração** (3º-C).
  - 🟡 **Transcritos aqui apenas pela função.** Os incisos desses três artigos **não foram transcritos verbatim** neste anexo — são matéria regulatória de baixo uso em peça agrária. **Cite pelo artigo e pela função; não reproduza redação literal de inciso sem conferência ao vivo**, e roteie ao `validador-agrario`.

## 2. Definições e requisitos do CDA/WA

- **Art. 4º** ✅ — "Para efeito desta Lei, entende-se como:" (**5 definições vigentes**, contadas na fonte)
  - **I** — "**depositário**: pessoa jurídica apta a exercer as atividades de **guarda e conservação** dos produtos especificados no § 1º do art. 1º desta Lei, de terceiros e, no caso de cooperativas, de terceiros e de associados, sem prejuízo do disposto nos **arts. 82 e 83 da Lei nº 5.764**, de 16 de dezembro de 1971";
  - **II** — "**depositante**: pessoa física ou jurídica **responsável legal** pelos produtos especificados no § 1º do art. 1º desta Lei entregues a um depositário para guarda e conservação";
  - **III — (Incluído pela Lei nº 13.986, de 2020)** — "**entidade registradora autorizada**: entidade autorizada pelo **Banco Central do Brasil ou pela Comissão de Valores Mobiliários**, no âmbito de suas competências, a exercer a atividade de **registro** de ativos financeiros e de valores mobiliários de que trata a **Lei nº 12.810, de 15 de maio de 2013**";
  - **IV — (Incluído pela Lei nº 13.986, de 2020)** — "**depositário central**: entidade autorizada pelo Banco Central do Brasil ou pela Comissão de Valores Mobiliários, no âmbito de suas competências, a exercer a atividade de **depósito centralizado** de ativos financeiros e de valores mobiliários de que trata a Lei nº 12.810, de 15 de maio de 2013; e";
  - **V — (Incluído pela Lei nº 13.986, de 2020)** — "**produtos agropecuários**: produtos agropecuários, seus derivados, subprodutos e resíduos de valor econômico de que trata a **Lei nº 9.973, de 29 de maio de 2000**."
  - 🔴 **PEGADINHA:** a redação **original de 2004** do inciso III — "entidade registradora autorizada: **sistema** de registro e de liquidação financeira de ativos autorizado pelo Banco Central" — está riscada na página. A vigente diz **entidade**, não sistema, e inclui a **CVM**. E os incisos **IV e V não existiam antes de 2020**: são eles que introduzem a figura do **depositário central**, que reorganiza todo o capítulo.
  - **Usa:** `compra-venda-de-safra-e-armazenagem` · `garantias-do-credito-rural`.

- **Art. 5º** ✅ — "O CDA e o WA devem conter as seguintes informações:" (**18 incisos vigentes**, contados na fonte)
  - **I** denominação do título · **II** **número de controle, idêntico para cada conjunto de CDA e WA** · **III** menção de que o depósito se sujeita à Lei 9.973/2000, a esta Lei e, no caso de cooperativas, à Lei 5.764/71 · **IV** identificação, qualificação e endereços do **depositante e do depositário** · **V** identificação comercial do depositário · **VI** **cláusula à ordem** · **VII** **endereço completo do local do armazenamento** · **VIII** descrição e especificação do produto · **IX** **peso bruto e líquido** · **X** forma de acondicionamento · **XI** número de volumes, quando cabível · **XII** **valor dos serviços de armazenagem, conservação e expedição**, periodicidade da cobrança e indicação do responsável pelo pagamento · **XIII** **identificação do segurador e do valor do seguro** · **XIV** qualificação da garantia oferecida pelo depositário, quando for o caso · **XV** **data do recebimento do produto e prazo do depósito** · **XVI** data de emissão do título · **XVIII** **identificação precisa dos direitos que conferem**.
  - **XVII — REDAÇÃO VIGENTE (Lei nº 14.421, de 2022)** ✅ — "identificação, qualificação e assinatura dos representantes legais do depositário, **que poderá ser feita de forma eletrônica, conforme legislação aplicável**;"
  - **Parágrafo único** ✅ — "O depositante e o depositário poderão acordar que a **responsabilidade pelo pagamento** do valor dos serviços a que se refere o **inciso XII** do caput deste artigo **será do endossatário do CDA**."
  - 🔴 A redação **original** do inciso XVII (sem a assinatura eletrônica) está riscada na página. A abertura para assinatura eletrônica é **de 2022**.
  - **No agrário:** o **p.ú.** é cláusula de negociação frequente e mal redigida — define **quem paga a armazenagem** ao final da cadeia de endossos. O **inciso VII** (endereço do armazém) e o **XV** (prazo) são os que sustentam a discussão de **onde** e **até quando** o produto deveria estar.

## 3. Emissão, responsabilidade e a blindagem do produto depositado

- **Art. 6º** ✅ — "A **solicitação de emissão** do CDA e do WA será feita **pelo depositante ao depositário**."
  - **§ 1º** ✅ — "Na solicitação, o depositante: **I** - **declarará, sob as penas da lei, que o produto é de sua propriedade e está livre e desembaraçado de quaisquer ônus**; **II** - **outorgará, em caráter irrevogável, poderes ao depositário para transferir a propriedade do produto ao endossatário do CDA**."
  - **§ 2º — REDAÇÃO VIGENTE (Lei 13.986/2020)** ✅ — "Os documentos mencionados no § 1º deste artigo serão arquivados pelo depositário junto com as **suas respectivas vias** do CDA e do WA."
  - **No agrário:** o **§1º, I** é o gêmeo funcional do **art. 17 da Lei 8.929/94** (declaração falsa sobre ônus na CPR) — mesma arquitetura de risco, na safra **já depositada**. É a cláusula que se ataca quando a mesma mercadoria foi comprometida duas vezes.

- **Art. 7º** ✅ (red. Lei 13.986/2020) — "É **facultada a formalização do contrato de depósito**, nos termos do art. 3º da Lei nº 9.973, de 29 de maio de 2000, quando forem emitidos o CDA e o WA."
- **Art. 8º — REDAÇÃO VIGENTE (Lei 13.986/2020)** ✅ — "O CDA e o WA, **quando emitidos sob a forma cartular**, o serão em, no mínimo, **2 (duas) vias**, com as seguintes destinações: **I** - primeiras vias, ao **depositante**; **II** - segundas vias, ao **depositário**, nas quais constarão os recibos de entrega dos originais ao depositante." — **Parágrafo único:** "Os títulos terão **numeração seqüencial, idêntica em ambos os documentos, em série única, vedada a subsérie**."
  - 🔴 A redação original ("O CDA e o WA **serão** emitidos em, no mínimo, 2 vias") está riscada: hoje a regra das duas vias **só alcança a forma cartular**.

- **Art. 9º** ✅ — "O **depositário que emitir** o CDA e o WA é responsável, **civil e criminalmente, inclusive perante terceiros**, pelas irregularidades e inexatidões neles lançadas."
  - **§ 1º** ✅ (Lei 13.986/2020) — "**O emitente é responsável pela existência, liquidez, certeza e exigibilidade dos direitos indicados no CDA e no WA.**"
  - **§ 2º** ⭐ ✅ (Lei 13.986/2020) — "**Fica vedado ao emitente opor ao terceiro titular do CDA ou do WA as exceções pessoais oponíveis ao depositante.**"
  - **No agrário:** o **§2º é a inoponibilidade de exceções pessoais em texto expresso** — trava a defesa do armazém que tenta descontar do endossatário final pendências que tinha com o depositante original. Ambos os §§ são **de 2020**; antes disso a mesma tese dependia de construção cambial.
  - **Usa:** `compra-venda-de-safra-e-armazenagem` · `garantias-do-credito-rural`.

- **Art. 10** ✅ — "O depositante tem o direito de pedir ao depositário a **divisão do produto em tantos lotes quantos lhe convenha** e solicitar a emissão do CDA e do WA correspondentes a cada um dos lotes."
- **Art. 11** ✅ — "O depositário assume a obrigação de **guardar, conservar, manter a qualidade e a quantidade** do produto recebido em depósito e de **entregá-lo ao credor na quantidade e qualidade consignadas** no CDA e no WA."
  - **No agrário:** é a **obrigação nuclear do armazém** e a âncora da ação por produto não devolvido ou devolvido fora de especificação — quantidade **e** qualidade, ambas medidas pelo que está **no título**.

- **Art. 12** ⭐ ✅ — "**Emitidos o CDA e o WA, o produto a que se referem não poderá sofrer embargo, penhora, seqüestro ou qualquer outro embaraço que prejudique a sua livre e plena disposição.**"
  - **Parágrafo único — REDAÇÃO VIGENTE (Incluído pela Lei 13.986/2020)** ✅ — "**Na hipótese de o titular do CDA e do correspondente WA diferir do depositante, o produto objeto desses títulos não poderá ser confundido com bem de propriedade do depositante ou sujeitar-se aos efeitos de sua recuperação judicial ou falência**, prevalecendo os direitos de propriedade sobre a coisa ao endossatário final que se apresentar ao depositário, nos termos do inciso II do § 1º do art. 6º e do § 5º do art. 21 desta Lei."
  - 🔴 **PEGADINHA DE PLANALTO — a mais perigosa deste anexo.** A página exibe, riscada, a versão da **MP 897/2019**: "*Subsiste ao titular do CDA e do WA, na hipótese de recuperação judicial ou de falência do depositante, o direito à **RESTITUIÇÃO** dos produtos que se encontrarem em poder do depositário...*". **Essa redação NÃO vigora.** O mecanismo vigente é **mais forte e juridicamente diverso**: não é pedir restituição de um bem que entrou no acervo — é **NÃO CONFUSÃO**, o bem **não integra** o patrimônio do depositante nem se sujeita aos efeitos da RJ/falência dele.
  - ⚠️ **Por que o erro é atraente:** "restituição" é exatamente o vocabulário do **art. 13 da Lei 13.288/2016** (integração vertical — anexo irmão) e do regime da Lei 11.101/2005. O modelo tende a uniformizar. **Não uniformize:** na integração vertical, **restituição**; no CDA/WA, **não confusão**. Pedir "restituição" com base no art. 12, p.ú. é pedir menos do que a lei dá, com fundamento revogado.
  - **Usa:** `compra-venda-de-safra-e-armazenagem` · `rj-produtor-rural` · `rj-sujeicao-de-creditos-agro` · `garantias-do-credito-rural` · `validador-agrario`.

- **Art. 13** ✅ — "O **prazo do depósito** a ser consignado no CDA e no WA será de **até 1 (um) ano, contado da data de sua emissão**, podendo ser **prorrogado pelo depositário a pedido do credor**, os quais, na oportunidade, ajustarão, se for necessário, as condições de depósito do produto."
  - **Parágrafo único — REDAÇÃO VIGENTE (Lei 13.986/2020)** ✅ — "As prorrogações serão anotadas nas **segundas vias em poder do depositário do produto agropecuário** e **eletronicamente nos registros do depositário central**."

- **Art. 14** ✅ (red. Lei 13.986/2020) — "**Incorre na pena prevista no art. 178 do Decreto-Lei nº 2.848, de 7 de dezembro de 1940 — Código Penal — aquele que emitir o CDA e o WA em desacordo com as disposições desta Lei.**"
  - **No agrário:** é o **espelho penal** do art. 17 da Lei 8.929/94 no depósito. O CP art. 178 é *emissão irregular de conhecimento de depósito ou warrant*. 🟡 **O texto do art. 178 do CP não está ancorado neste plugin** — cite o **reenvio** desta lei, não a redação do tipo penal.

## 4. Depósito centralizado, circulação e a execução do penhor do WA

- **Art. 15 — REDAÇÃO VIGENTE (Lei 13.986/2020)** ✅ — "É obrigatório o **DEPÓSITO do CDA e do WA em DEPOSITÁRIO CENTRAL** autorizado pelo Banco Central do Brasil, **no prazo de 30 (trinta) dias**, contado da data de emissão dos títulos, do qual constará o número de controle do título de que trata o inciso II do caput do art. 5º desta Lei."
  - 🔴 **PEGADINHA DE PLANALTO — o artigo aparece CINCO vezes, quatro riscadas.** A página exibe, em sequência: (a) original de 2004 — "**registro** ... em sistema de registro e de liquidação financeira ... no prazo de até **10 (dez) dias**"; (b) MP 372/2007 — "**trinta dias**"; (c) Lei 11.524/2007 — "**30 (trinta) dias**", ainda como **registro**; (d) MP 897/2019 — já como **depósito em depositário central**; (e) **vigente, Lei 13.986/2020**. **Dois erros distintos podem sair daí:** o **prazo** (10 dias é de 2004) e o **instituto** (mudou de *registro em sistema* para **depósito em depositário central**). Citar "registro em 10 dias" erra os dois.
  - **§ 1º** ✅ (red. Lei 13.986/2020) — "O depósito de CDA e de WA **emitidos sob a forma cartular** em depositário central será **precedido da entrega dos títulos à custódia** de instituição legalmente autorizada para esse fim, **por meio de endosso-mandato**."
  - **Usa:** `compra-venda-de-safra-e-armazenagem` · `cpr-emissao-e-formalizacao` · `calendario-safra-e-prazos-criticos`.

- **Art. 16** ✅ (red. Lei 13.986/2020) — "O CDA e o WA serão **negociados nos mercados de bolsa e de balcão como ativos financeiros**."

- **Art. 17 — REDAÇÃO VIGENTE (Lei 13.986/2020)** ✅ — "**Por ocasião da primeira negociação do WA separado do CDA**, o **depositário central** consignará em seus registros o **valor da negociação do WA, a taxa de juros e a data de vencimento** ou, ainda, o **valor a ser pago no vencimento** ou o indicador que será utilizado para o cálculo do valor da dívida."
  - **§ 1º** ✅ (red. Lei 13.986/2020) — "Os **lançamentos** dos negócios realizados com o CDA e com o WA unidos ou separados serão **atualizados em meio eletrônico pelo depositário central**."
  - **§ 2º** ⭐ ✅ (Incluído pela Lei nº 11.524, de 2007) — "**Se, na data de vencimento do WA, o CDA e o WA não estiverem em nome do mesmo credor e o credor do CDA não houver consignado o valor da dívida**, na forma do inciso II do § 1º do art. 21 desta Lei, **o titular do WA poderá, a seu critério, promover a EXECUÇÃO DO PENHOR sobre: I** - **o produto, mediante sua venda em leilão a ser realizado em bolsa de mercadorias**; **ou II** - **o CDA correspondente, mediante a venda do título, em conjunto com o WA**, em bolsa de mercadorias ou de futuros, ou em mercado de balcão organizado."
  - **§ 3º** ✅ (Lei 11.524/2007) — "Nas hipóteses referidas nos incisos I e II do § 2º deste artigo, o produto da venda da mercadoria ou dos títulos, conforme o caso, será utilizado para **pagamento imediato do crédito representado pelo WA** ao seu respectivo titular na data do vencimento, devendo o **saldo remanescente ser entregue ao titular do CDA**, após debitadas as despesas comprovadamente incorridas com a realização do leilão."
  - **§ 4º** ✅ (Lei 11.524/2007) — "O adquirente dos títulos no leilão **poderá colocá-los novamente em circulação**, observando-se o disposto no caput deste artigo, no caso de negociação do WA separado do CDA."
  - ⭐ **No agrário — o dispositivo prático mais importante do capítulo:** os §§2º-4º dão ao titular do WA uma **via de excussão extrajudicial do penhor**, por **leilão em bolsa**, **sem ação judicial**, com **duas opções à sua escolha** (o produto **ou** o CDA em conjunto com o WA) e com **destino do saldo definido em lei**. Antes de propor execução judicial pelo WA, verifique esta porta — ela é mais rápida e está no texto.
  - **Usa:** `compra-venda-de-safra-e-armazenagem` · `execucao-de-cpr-e-cedula-rural` · `garantias-do-credito-rural`.

- **Art. 18** ✅ (red. Lei 13.986/2020) — "As **negociações do CDA e do WA são isentas do Imposto sobre Operações de Crédito, Câmbio e Seguro ou relativas a Títulos ou Valores Mobiliários**." (**IOF**)
  - **Usa:** `tributacao-dos-contratos-agrarios` · `compra-venda-de-safra-e-armazenagem`.
- **Art. 19** ✅ (red. Lei 13.986/2020) — "Os negócios ocorridos durante período em que o CDA e o WA **emitidos sob a forma cartular** estiverem **depositados em depositário central não serão transcritos no verso dos títulos**."
- **Art. 20** — 🔴 **REVOGADO** (Lei 13.986/2020). **Não citar.** A página exibe o texto inteiro, riscado.

## 5. Retirada do produto — art. 21 (e o seguro do art. 22)

- **Art. 21** ✅ — "Para a retirada do produto, o **credor do CDA providenciará a baixa do registro eletrônico do CDA** e requererá à instituição custodiante **o endosso na cártula e a sua entrega**."
  - **§ 1º** ✅ — "A baixa do registro eletrônico ocorrerá **somente se**: **I** - o **CDA e o WA estiverem em nome do mesmo credor**; **ou II** - o **credor do CDA consignar, em dinheiro, na instituição custodiante, o valor do principal e dos juros devidos até a data do vencimento do WA**."
  - **§ 2º** ✅ — "A consignação do valor da dívida do WA, na forma do inciso II do § 1º deste artigo, **equivale ao real e efetivo pagamento da dívida**, devendo a quantia consignada ser entregue ao credor do WA pela instituição custodiante."
  - **§ 3º** ✅ — na hipótese do inciso I, a custodiante entrega ao credor, **junto com a cártula do CDA, a cártula do WA**.
  - **§ 4º** ✅ — na hipótese do inciso II, entrega, junto com a cártula do CDA, **documento comprobatório do depósito consignado**.
  - **§ 5º — REDAÇÃO VIGENTE (MP 897/2019, mantida)** ✅ — "Com a entrega do CDA ao depositário, juntamente com o respectivo WA ou com o documento de que trata o § 4º, **extingue-se o mandato** a que se refere o inciso II do § 1º do art. 6º."
  - **§ 6º** ✅ — "São condições **para a retirada do produto**: **I** - o **pagamento dos serviços de armazenagem, conservação e expedição**, na forma do inciso XII e do parágrafo único do art. 5º desta Lei; **II** - o **cumprimento das obrigações tributárias**, principais e acessórias, relativas à operação."
  - 🔴 **PEGADINHA (§§5º e 6º):** as redações **originais** estão riscadas e diziam mais: o §5º antigo afirmava que o endossatário "**adquire a propriedade do produto**", e o §6º antigo condicionava "**a transferência da propriedade OU a retirada**". As vigentes falam apenas em **extinção do mandato** e em **retirada**. **Não escreva "a lei diz que o endossatário adquire a propriedade pelo §5º"** — essa oração está na redação revogada.
  - **No agrário:** o **§2º** é a saída do titular do CDA que não quer esperar o WA vencer — consigna e destrava. O **§6º** é o que o armazém opõe legitimamente contra a retirada: armazenagem paga **e** obrigações tributárias cumpridas.
  - **Usa:** `compra-venda-de-safra-e-armazenagem` · `tributacao-dos-contratos-agrarios`.

- **Art. 22 — REDAÇÃO VIGENTE (Lei 13.986/2020)** ✅ — "Para emissão de CDA e WA, o **seguro obrigatório** de que trata o § 6º do art. 6º da Lei nº 9.973, de 29 de maio de 2000, deverá ter cobertura contra **incêndio, raio, explosão de qualquer natureza, danos elétricos, vendaval, alagamento, inundação, furacão, ciclone, tornado, granizo, quedas de aeronaves, impacto de veículos terrestres e fumaça**."
  - **Parágrafo único** ✅ — "No caso de **armazéns públicos**, o seguro obrigatório de que trata o caput deste artigo **também conterá cláusula contra roubo e furto**."
  - 🔴 **PEGADINHA — a lista ENCOLHEU em 2020.** A redação original, riscada na página, terminava com "**quedas de aeronaves ou quaisquer outros engenhos aéreos ou espaciais**, impacto de veículos terrestres, fumaça **e quaisquer intempéries que destruam ou deteriorem o produto** vinculado àqueles títulos". A vigente **suprimiu a cláusula-varredura "quaisquer intempéries"** e o trecho "outros engenhos aéreos ou espaciais". **A cobertura legal mínima hoje é uma lista fechada.** Sustentar sinistro por "intempérie" genérica com base neste artigo é invocar texto revogado — o caminho passa a ser a apólice.
  - **Usa:** `compra-venda-de-safra-e-armazenagem` · `prova-de-frustracao-de-safra-e-vistoria`.

## 6. 🔴 CDCA, LCA e CRA — e a demolição do regime do CRA pela Lei 14.430/2022

- **Art. 23** ✅ — "Ficam instituídos os seguintes títulos de crédito: **I** - **Certificado de Direitos Creditórios do Agronegócio - CDCA**; **II** - **Letra de Crédito do Agronegócio - LCA**; **III** - **Certificado de Recebíveis do Agronegócio - CRA**." (**3 incisos**)
  - **§ 1º** ✅ (Incluído pela Lei nº 13.331, de 2016) — "Os títulos de crédito de que trata este artigo são **vinculados a direitos creditórios originários de negócios realizados entre produtores rurais, ou suas cooperativas, e terceiros**, inclusive **financiamentos ou empréstimos**, relacionados com a **produção, a comercialização, o beneficiamento ou a industrialização de produtos ou insumos agropecuários ou de máquinas e implementos utilizados na atividade agropecuária**."
  - **§ 3º** ✅ (Lei 13.986/2020) — emissão com **cláusula de correção pela variação cambial**, desde que integralmente vinculados a direitos creditórios com cláusula de correção **na mesma moeda**. **§ 4º** ✅ (Lei 13.986/2020) — o **CMN poderá dispor** sobre essa emissão.
  - 🔴 **§ 2º — REVOGADO pela Lei nº 14.937, de 2024** (com seus incisos I e II). Tratava do lastro de LCA emitida por bancos cooperativos em repasse interfinanceiro. **Não citar.** A página exibe **quatro** versões dele (MP 725/2016, Lei 13.331/2016, Lei 13.606/2018 e a marcação de revogação).
  - 🔴 **§ 5º — (VETADO)** (red. Lei 14.421/2022). Não citar.
  - 🔴 **O parágrafo único original virou §1º.** A página exibe o **p.ú. de 2004** riscado, com "(Revogado pela Lei nº 13.331, de 2016)". **Citar "art. 23, parágrafo único" é citar dispositivo revogado** — hoje é **§1º**.

- **Art. 24** ✅ — "O **Certificado de Direitos Creditórios do Agronegócio - CDCA** é título de crédito **nominativo, de livre negociação, representativo de promessa de pagamento em dinheiro e constitui título executivo extrajudicial**."
  - **§ 1º — REDAÇÃO VIGENTE (Lei 13.986/2020)** ✅ — "O CDCA é de **emissão exclusiva de cooperativas agropecuárias e de outras pessoas jurídicas que exerçam a atividade de comercialização, beneficiamento ou industrialização de produtos, insumos, máquinas e implementos** [...]".
  - 🔴 **PEGADINHA:** a página exibe o **p.ú. original** e **duas** versões anteriores do §1º, todas riscadas, que diziam "**cooperativas de produtores rurais**". A vigente diz "**cooperativas agropecuárias**". Os **§§ 2º e 3º estão expressamente "(Revogado)"** pela Lei 13.986/2020.
  - ⛔ **O CDCA NÃO pode ser emitido por produtor rural pessoa física.** A exclusividade é de **pessoa jurídica** nas atividades listadas. Quem precisa de título emitido pelo produtor está falando de **CPR** (Lei 8.929/94), não de CDCA.

- **Art. 25** ✅ — "O CDCA terá os seguintes requisitos, lançados em seu contexto:" — **10 incisos vigentes** (contados na fonte). 🟡 **Os incisos não foram transcritos verbatim neste anexo.** Cite o artigo e a função; confira a redação de cada inciso ao vivo antes de transcrever.

- **Art. 26** ✅ — "A **Letra de Crédito do Agronegócio – LCA** é título de crédito **nominativo, de livre negociação, representativo de promessa de pagamento em dinheiro e constitui título executivo extrajudicial**."
  - **Parágrafo único** ✅ — "**A LCA é de emissão exclusiva de instituições financeiras públicas ou privadas.**"
  - ⛔ Nem produtor, nem cooperativa, nem trading emite LCA. **Só instituição financeira.** Confundir LCA com CDCA na peça inverte o polo emissor.

- **Art. 27** ✅ — "A LCA terá os seguintes requisitos, lançados em seu contexto:" — **9 incisos vigentes** (contados na fonte). 🟡 Não transcritos verbatim aqui; mesma regra do art. 25.

- **Arts. 28 a 35-D — disposições comuns ao CDCA e à LCA** ✅ (vigentes):
  - **Art. 28** — "O **valor do CDCA e da LCA não poderá exceder o valor total dos direitos creditórios** do agronegócio a eles vinculados."
  - **Art. 29** — "Os **emitentes** de CDCA e de LCA **respondem pela origem e autenticidade** dos direitos creditórios a eles vinculados."
  - **Art. 30** — a **identificação dos direitos creditórios** pode ser feita **em documento à parte**, assinado pelos representantes legais do emitente, com menção no certificado ou nos registros.
  - **Art. 31** — o CDCA e a LCA **podem conter outras cláusulas** em documento à parte, com menção no contexto.
  - **Art. 32** ⭐ — "O CDCA e a LCA **conferem direito de penhor sobre os direitos creditórios a eles vinculados, INDEPENDENTEMENTE DE CONVENÇÃO**" [...].
  - **Art. 33** ✅ (red. Lei 13.986/2020) — "Além do penhor constituído na forma do art. 32 desta Lei, o CDCA e a LCA poderão contar com **quaisquer garantias adicionais**" [...].
  - **Art. 34** ⭐ — "Os **direitos creditórios vinculados ao CDCA e à LCA não serão penhorados, seqüestrados ou arrestados em decorrência de outras dívidas do emitente** desses títulos, **a quem caberá informar ao juízo**, que tenha determinado tal medida, a respeito da vinculação de tais direitos aos respectivos títulos, **sob pena de responder pelos prejuízos resultantes de sua omissão**."
  - **Arts. 35, 35-A, 35-B, 35-C e 35-D** ✅ — forma **escritural**, sistema eletrônico de escrituração do CDCA, competências do **Banco Central** e conteúdo do sistema (todos com forte reescrita pela **Lei 13.986/2020**). 🟡 **Incisos não transcritos verbatim** — matéria regulatória; cite pela função.
  - **No agrário — o paralelo que a peça deve enxergar:** o **art. 34** é o **gêmeo do art. 18 da Lei 8.929/94** (CPR): impenhorabilidade por dívidas alheias ao título **+ dever de denunciar sob pena de responder pelos prejuízos**. Mesma arquitetura, objetos diferentes — lá a **safra vinculada**, aqui os **direitos creditórios vinculados**. E o **art. 32** dispensa convenção para o penhor.
  - **Usa:** `garantias-do-credito-rural` · `compra-venda-de-safra-e-armazenagem` · `embargos-a-execucao-de-cpr`.

### 6.1 🔴 CRA — só o *caput* do art. 36 sobreviveu. Todo o resto foi revogado

- **Art. 36 — REDAÇÃO VIGENTE (Lei 13.986/2020), APENAS O CAPUT** ✅ — "O **Certificado de Recebíveis do Agronegócio – CRA** é título de crédito **nominativo, de livre negociação, representativo de promessa de pagamento em dinheiro e constitui título executivo extrajudicial**."

🔴 **O parágrafo único do art. 36 está REVOGADO (Lei 14.430/2022)** — e a página o exibe **três vezes**, todas riscadas (redação original de 2004, redação da MP 897/2019 e redação da Lei 13.986/2020), todas dizendo: "*O CRA é de emissão exclusiva das companhias securitizadoras de direitos creditórios do agronegócio...*".

⛔ **NÃO afirme "o CRA é de emissão exclusiva das companhias securitizadoras **nos termos da Lei 11.076/2004**".** Esse dispositivo **não vigora mais nesta lei**. É a frase mais provável de sair errado: ela aparece três vezes na página, é a definição que a doutrina anterior a 2022 repete, e está inteiramente riscada.

🔴 **Foi revogado, pela Lei 14.430/2022, TODO o regime do CRA nesta lei:** art. **37** (requisitos do CRA), art. **38** (companhias securitizadoras), art. **39** (regime fiduciário, que remetia aos arts. 9º a 16 da Lei 9.514/97), art. **40** (termo de securitização) — e, com eles, as **Subseções II e III** inteiras da Seção V.

🟡 **O que passou a reger o CRA e a securitização do agronegócio NÃO está ancorado neste plugin.** A **Lei 14.430/2022 não foi capturada**. Portanto: **não cite artigo da Lei 14.430/2022** e **não afirme qual é hoje o regime de emissão do CRA**. O que este anexo autoriza sobre CRA é **exclusivamente**: (a) o **caput** do art. 36 (natureza e executividade); (b) os arts. **41 a 44** (disposições comuns, §7 abaixo), que seguem vigentes. Tudo o mais → **🟡, rotear ao `validador-agrario`**.

## 7. Disposições comuns ao CDCA, à LCA e ao CRA — arts. 41 a 44 (vigentes)

- **Art. 41** ✅ — "É facultada a **cessão fiduciária em garantia** de direitos creditórios do agronegócio, em favor dos adquirentes do CDCA, da LCA e do CRA, nos termos do disposto nos **arts. 18 a 20 da Lei nº 9.514**, de 20 de novembro de 1997."
  - 🟡 Os arts. 18 a 20 da Lei 9.514/97 **não estão ancorados neste plugin**. Cite o **reenvio**, não o conteúdo deles.
- **Art. 42** ✅ — "O CDCA, a LCA e o CRA poderão conter **cláusula expressa de variação do seu valor nominal**, desde que seja **a mesma dos direitos creditórios a eles vinculados**."
- **Art. 43** ✅ — "O CDCA, a LCA e o CRA poderão ser **distribuídos publicamente e negociados em Bolsas de Valores e de Mercadorias e Futuros e em mercados de balcão organizados** autorizados a funcionar pela **Comissão de Valores Mobiliários**." — **Parágrafo único:** observa-se o disposto na **Lei nº 6.385, de 7 de dezembro de 1976**.
- **Art. 44** ✅ — "Aplicam-se ao CDCA, à LCA e ao CRA, **no que forem cabíveis, as normas de direito cambial**, com as seguintes modificações:" — **I** ✅ "os **endossos devem ser completos**;" · **II** ✅ "é **dispensado o protesto cambial** para assegurar o direito de regresso contra endossantes e avalistas." (**2 incisos**, contados na fonte)
  - 🔴 **Diferença real — NÃO transplante o art. 2º para cá.** O art. 2º (CDA/WA) tem **três** incisos e o do meio diz que "os **endossantes não respondem pela entrega do produto**, mas, tão-somente, pela existência da obrigação". **O art. 44 NÃO tem inciso equivalente**: ele salta dos endossos completos direto para a dispensa de protesto. Atribuir ao CDCA/LCA/CRA a não responsabilidade dos endossantes do art. 2º, II é **inventar inciso** — e a responsabilidade que a lei de fato impõe nesses títulos é a do **art. 29** (o emitente responde pela **origem e autenticidade** dos direitos creditórios).

## 8. Disposições finais úteis — e um dispositivo cujo efeito já se exauriu

- **Art. 45** ✅ (red. vigente) — autorizou a emissão do CDA e do WA **até 31 de dezembro de 2009** por armazéns sem a certificação prevista na Lei 9.973/2000. 🔴 **Regra de transição com prazo VENCIDO** — não invocar para operação atual.
- **Art. 46** ✅ — "Para os produtos especificados no § 1º do art. 1º desta Lei, fica **vedada a emissão do Conhecimento de Depósito e do Warrant** [do Decreto nº 1.102/1903]." — **No agrário:** é o dispositivo que **substituiu** os títulos antigos pelo par CDA/WA para produto agropecuário. Por força do **art. 55, II**, produziu efeitos **365 dias após a publicação**.
- **Art. 51** ⚠️ — "O art. 19 da Lei nº 8.929, de 22 de agosto de 1994, passa a vigorar acrescido dos seguintes §§ 3º e 4º" (características da CPR registrada; emissão em favor do garantidor com endosso-mandato).
  - 🔴 **EFEITO EXAURIDO — não cite esses §§ como vigentes.** O **art. 19 da Lei 8.929/94 foi REVOGADO pelo art. 61 da Lei 13.986/2020** (registrado em `context/lei-do-agro-e-cpr.md`, §0). Revogado o artigo hospedeiro, **os §§ 3º e 4º que este art. 51 nele inseriu não subsistem**. A escrituração da CPR hoje está nos **arts. 3º-A a 3º-E da Lei 8.929/94** — confira lá, não aqui.
- **Art. 52** 🔴 — **REVOGADO** (Lei 14.317/2022), com os **Anexos I e II**. Não citar.
- **Art. 53** ✅ — alterou os **arts. 22, p.ú., e 38 da Lei nº 9.514/97**. ⚠️ É daqui que vem o "**Art. 38.**" **não riscado** que engana o `grep` (Aviso 4).
- **Art. 54** ✅ — "Revoga-se o **art. 4º da Lei nº 9.973**, de 29 de maio de 2000."
- **Art. 55** ✅ — "Esta Lei **entra em vigor na data de sua publicação**, produzindo efeitos: **I** - quanto ao art. 52 e aos Anexos I e II, **a partir de 3 de janeiro de 2005**; **II** – quanto ao **art. 46**, a partir de **365 (trezentos e sessenta e cinco) dias após a data de publicação** desta Lei."
  - Sanção em **30/12/2004**; publicação no **D.O.U. de 31.12.2004** (nota oficial de rodapé).

---

## Guard

Todo dispositivo transcrito acima está marcado **✅ conferido verbatim na REDAÇÃO VIGENTE** do **texto compilado** da Lei 11.076/2004 capturado do Planalto em **02/08/2026**, com a vigência determinada por **profundidade de tag `<strike>` no HTML**, não por leitura visual. Isso **encerra o gap declarado** pela `compra-venda-de-safra-e-armazenagem`: **CDA e Warrant Agropecuário agora resolvem em anexo.**

**🔴 A regra vermelha da skill muda — e só até aqui:** a proibição "**não cite artigo da Lei 11.076/2004**" fica **substituída** por: cite **os dispositivos transcritos neste anexo**, na redação aqui fixada. Todo o resto da lei continua **🟡 candidato a verificação**.

**O que este anexo NÃO autoriza:**

- 🔴 **Citar os arts. 20, 37, 38, 39, 40 e 52** — **sem texto vigente**. A página os exibe inteiros e legíveis, riscados.
- 🔴 **Afirmar que "o CRA é de emissão exclusiva das companhias securitizadoras" com base nesta lei.** O art. 36, p.ú. foi **revogado pela Lei 14.430/2022** e aparece **três vezes riscado** na página. Sobre CRA, este anexo autoriza **apenas** o **caput do art. 36** e os arts. **41-44**.
- 🔴 **Citar a Lei 14.430/2022** (marco da securitização) — **não capturada, não ancorada**. Não afirme qual é hoje o regime do CRA.
- 🔴 **Usar "restituição" no art. 12, p.ú.** — é a redação **revogada** (MP 897/2019). A vigente é **não confusão** com o patrimônio do depositante. Não uniformizar com o art. 13 da Lei 13.288/2016, que é **restituição** de verdade.
- 🔴 **Dizer "registro do CDA/WA em sistema de registro, em 10 dias"** (art. 15) — são **duas** informações revogadas. Vigente: **depósito em depositário central, 30 dias**.
- 🔴 **Invocar cobertura securitária por "quaisquer intempéries"** (art. 22) — cláusula-varredura **suprimida em 2020**. A lista legal hoje é **fechada**.
- 🔴 **Dizer que o §5º do art. 21 transfere a propriedade** — a redação vigente fala em **extinção do mandato**; "adquire a propriedade" está na redação **revogada**.
- 🔴 **Citar "art. 23, parágrafo único"** (hoje é **§1º**), o **art. 23, §2º** (revogado — Lei 14.937/2024) ou o **art. 23, §5º** (**VETADO**).
- 🔴 **Citar os §§ 3º e 4º do art. 19 da Lei 8.929/94** inseridos pelo art. 51 desta lei — **o art. 19 hospedeiro foi revogado** pelo art. 61 da Lei 13.986/2020. Escrituração da CPR: **arts. 3º-A a 3º-E**, em `context/lei-do-agro-e-cpr.md`.
- 🔴 **Invocar o art. 45** — transição com prazo **vencido em 31/12/2009**.
- 🟡 **Incisos NÃO transcritos verbatim neste anexo:** art. **25** (10 incisos, CDCA), art. **27** (9 incisos, LCA), e os incisos dos arts. **3º-A, 3º-B, 3º-C, 35, 35-A a 35-D**. Deles, **cite o artigo e a função com segurança — não reproduza redação literal de inciso** sem conferência ao vivo. Roteie ao `validador-agrario`.
- 🟡 **Normas apenas REENVIADAS por esta lei, não ancoradas aqui:** Lei **9.973/2000** (armazenagem — inclusive o art. 6º, §6º do seguro), Lei **5.764/71** (arts. 82 e 83), Lei **9.514/97** (arts. 18 a 20 e 22/38), Lei **12.810/2013**, Lei **6.385/76**, Lei **13.506/2017** e o **art. 178 do Código Penal** (art. 14). **Cite o reenvio, nunca o conteúdo delas por memória.**
- 🟡 **Prescrição do CDA, do WA, do CDCA, da LCA e do CRA — não há prazo nesta lei.** Gap idêntico ao já declarado para a CPR e a cédula rural. Não afirmar prazo.
- 🟡 **Conflito de garantias sobre a mesma safra** (penhor × CPR × CDA/WA × alienação fiduciária) e **boa-fé do terceiro adquirente** — **bloco inteiro sem número confirmado** no plugin. Este anexo **não** o resolve: ele acrescenta as peças (arts. 12, 32 e 34), não a jurisprudência. Rotear ao `validador-agrario`.
- 🟡 **Jurisprudência sobre CDA/WA não foi levantada.** `context/jurisprudencia-agraria.md` **não cobre** estes títulos. Não sustentar entendimento como pacífico.

**Distinção que este anexo TRAVA (e que vale para todo o plugin):**

| Título | "Título executivo extrajudicial" está na lei? | Onde |
|---|---|---|
| **CDA e WA** | **SIM** | Lei 11.076/2004, **art. 1º, §4º** |
| **CDCA** | **SIM** | art. **24**, caput |
| **LCA** | **SIM** | art. **26**, caput |
| **CRA** | **SIM** | art. **36**, caput (única parte viva do artigo) |
| **CPR** | 🔴 **NÃO** — a Lei 8.929/94 diz "**título líquido e certo**" | `context/lei-do-agro-e-cpr.md` |
| **CIR** | SIM, por lei própria | Lei 13.986/2020, art. 21 |

⛔ **Não estenda à CPR a qualificação que a lei dá aos títulos desta lei.** A regra dura do `anti-alucinacao-agraria` continua valendo integralmente para a CPR.

**Fronteira do anexo:** este arquivo cobre **exclusivamente a Lei 11.076/2004**. CPR, Lei do Agro e cédulas rurais em `context/lei-do-agro-e-cpr.md`; CPC em `context/cpc-agrario.md`; recuperação judicial em `context/rj-produtor-rural.md`; integração vertical em `context/integracao-vertical-13288.md`. **Nenhum artigo dessas outras normas está ancorado aqui.**

Nenhum item deste anexo dispensa o fecho pela **`suprema-corte-agraria` (R1-R4)** e pelo **`validador-agrario`** antes da entrega.
