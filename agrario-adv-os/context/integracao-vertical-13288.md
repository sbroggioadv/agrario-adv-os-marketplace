# Anexo — Lei 13.288/2016 (contratos de integração vertical na agropecuária)

> **14º anexo do plugin.** Fecha o gap declarado pela camada C2: a `contrato-integracao-vertical` é a única skill do plugin cuja **lei inteira** era citada de cabeça — nenhum anexo de `context/` continha uma linha da Lei 13.288/2016. Aqui está o texto, **verbatim**.
>
> **Fonte:** texto do Planalto capturado em **02/08/2026** — `https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2016/lei/l13288.htm` (HTTP 200, 52.372 bytes). Transcrição **verbatim**, não paráfrase.
>
> **Legenda:** ✅ conferido verbatim na fonte oficial · 🟡 não confirmado (não citar sem checar) · 🔴 pegadinha / afirmação corrente que o texto **não** sustenta.

---

## ⚠️ AVISO 1 — esta lei NÃO TEM alterações. A pegadinha aqui é a inversa

Verificado por comando na captura: a página do Planalto exibe **zero** ocorrências de `Redação dada`, `Incluído`, `Revogado` e **zero** tags de texto riscado. A Lei 13.288/2016 está, em 02/08/2026, **na redação original de 16/05/2016**, com **14 artigos**.

🔴 **Consequência operacional:** ao contrário da Lei 11.076/2004 (anexo irmão, com 239 blocos riscados), aqui **não existe "redação anterior" nem "redação dada pela Lei X"**. Se a peça atribuir a algum artigo desta lei uma alteração posterior, a alteração **foi inventada** — não há o que conferir, há o que apagar.

**A única mutilação do texto é um veto:** o **parágrafo único do art. 14 está (VETADO)**. O corpo da lei nunca teve esse dispositivo em vigor.

## ⚠️ AVISO 2 — grep o artigo e leia a faixa. Nunca despeje o anexo inteiro

Material de consulta pontual, não leitura de contexto. **Faça `grep` do número do artigo e leia só a faixa.** Cada bloco traz: **artigo · texto literal · para que serve · qual skill usa**.

## ⚠️ AVISO 3 — os três números que a skill afirma estão CERTOS (contados por comando)

| Afirmação da `contrato-integracao-vertical` | Contagem na fonte | Situação |
|---|---|---|
| art. 4º — "16 cláusulas obrigatórias" | **16** (I a XVI) | ✅ confere |
| art. 6º, §4º — "7 funções da CADEC" | **7** (I a VII) | ✅ confere |
| art. 9º — "DIPC com 13 informações" | **13** (I a XIII) | ✅ confere |

Demais contagens conferidas: art. 2º = **5** definições · art. 6º, §1º = **4** representações · art. 9º, VI = **4** alíneas (a–d) · art. 10, §3º = **4** deveres · art. 13 = **2** incisos.

---

## 1. Âmbito, exclusões e o que NÃO é integração

- **Art. 1º** ✅ — "Esta Lei dispõe sobre os **contratos de integração vertical nas atividades agrossilvipastoris**, estabelece obrigações e responsabilidades gerais para os produtores integrados e os integradores, institui mecanismos de transparência na relação contratual, cria fóruns nacionais de integração e as Comissões para Acompanhamento, Desenvolvimento e Conciliação da Integração - CADEC, ou similar, respeitando as estruturas já existentes."
  - **Parágrafo único** ✅ — "A integração vertical **entre cooperativas e seus associados ou entre cooperativas constitui ato cooperativo**, regulado por legislação específica aplicável às sociedades cooperativas."
  - **No agrário:** o p.ú. é a **primeira porta de exclusão**. Relação cooperativa–associado **não é** contrato de integração desta lei; é ato cooperativo (Lei 5.764/71). Qualificar errado aqui contamina tudo o que vem depois.
  - **Usa:** `contrato-integracao-vertical` · `triagem-agraria` · `descaracterizacao-e-figuras-atipicas`.

- **Art. 2º** ✅ — "Para os efeitos desta Lei, entende-se por:" (**5 definições**, contadas na fonte)
  - **I** — "**integração vertical ou integração**: relação contratual entre produtores integrados e integradores que visa a planejar e a realizar a produção e a industrialização ou comercialização de matéria-prima, bens intermediários ou bens de consumo final, com responsabilidades e obrigações recíprocas estabelecidas em contratos de integração";
  - **II** — "**produtor integrado ou integrado**: produtor agrossilvipastoril, pessoa física ou jurídica, que, individualmente ou de forma associativa, **com ou sem a cooperação laboral de empregados**, se vincula ao integrador por meio de contrato de integração vertical, recebendo bens ou serviços para a produção e para o fornecimento de matéria-prima, bens intermediários ou bens de consumo final";
  - **III** — "**integrador**: pessoa física ou jurídica que se vincula ao produtor integrado por meio de contrato de integração vertical, fornecendo bens, insumos e serviços e recebendo matéria-prima, bens intermediários ou bens de consumo final utilizados no processo industrial ou comercial";
  - **IV** — "**contrato de integração vertical ou contrato de integração**: contrato, firmado entre o produtor integrado e o integrador, que estabelece a sua finalidade, as respectivas atribuições no processo produtivo, os compromissos financeiros, os deveres sociais, os requisitos sanitários, as responsabilidades ambientais, entre outros que regulem o relacionamento entre os sujeitos do contrato";
  - **V** — "**atividades agrossilvipastoris**: atividades de **agricultura, pecuária, silvicultura, aquicultura, pesca ou extrativismo vegetal**."
  - **§ 1º** ✅ — "Para os efeitos desta Lei, **equiparam-se ao integrador os comerciantes e exportadores** que, para obterem matéria-prima, bens intermediários ou bens de consumo final, celebram contratos de integração com produtores agrossilvipastoris."
  - **§ 2º** ✅ — "**A simples obrigação do pagamento do preço estipulado contra a entrega de produtos** à agroindústria ou ao comércio **não caracteriza contrato de integração**."
  - **§ 3º** ✅ — "A integração, **relação civil** definida nos termos desta Lei, **não configura prestação de serviço ou relação de emprego** entre integrador e integrado, seus prepostos ou empregados."
  - 🔴 **A lei NUNCA escreve "aves", "avicultura", "suíno", "frango" ou "granja".** Verificado por comando: **zero ocorrências** de cada um. O rol legal é o do inciso V, e ali só existe "**pecuária**". A associação "Lei da Integração = frango e suíno" é **prática de mercado**, não texto. Em peça: enquadre pelo **inciso V + art. 2º, I**, nunca por "a lei trata de avicultura".
  - **No agrário:** o **§2º** é a segunda porta de exclusão (mera compra e venda → `compra-venda-de-safra-e-armazenagem`) e o **§3º** é a blindagem trabalhista/consumerista do arranjo. O **§1º** impede que trading e exportador fujam da lei alegando não ser agroindústria.
  - **Usa:** `contrato-integracao-vertical` · `triagem-agraria` · `descaracterizacao-e-figuras-atipicas` · `compra-venda-de-safra-e-armazenagem`.

## 2. O princípio interpretativo — art. 3º

- **Art. 3º** ✅ — "É **princípio orientador da aplicação e interpretação desta Lei** que a relação de integração se caracterize pela **conjugação de recursos e esforços** e pela **distribuição justa dos resultados**."
  - **No agrário:** é a norma que o integrado invoca contra cláusula desequilibrada — e, por ser **princípio de interpretação declarado pelo próprio legislador**, entra na fundamentação sem depender de doutrina. Casa com o art. 4º, V (fórmula de eficiência explicada) e VIII (custo dos insumos).
  - **Usa:** `contrato-integracao-vertical` · `suprema-corte-agraria` (R2).

## 3. 🔴 Art. 4º — ESCRITO SOB PENA DE NULIDADE, com 16 incisos

- **Art. 4º** ✅ — "O contrato de integração, **sob pena de nulidade, deve ser escrito** com clareza, precisão e ordem lógica, e deve dispor sobre as seguintes questões, **sem prejuízo de outras** que as partes contratantes considerem mutuamente aceitáveis:"

  **Os 16 incisos, verbatim** (contados por comando):

  - **I** — "as características gerais do sistema de integração e as exigências técnicas e legais para os contratantes";
  - **II** — "as responsabilidades e as obrigações do integrador e do produtor integrado no sistema de produção";
  - **III** — "os parâmetros técnicos e econômicos indicados ou anuídos pelo integrador com base no **estudo de viabilidade econômica e financeira do projeto**";
  - **IV** — "os padrões de qualidade dos insumos fornecidos pelo integrador para a produção animal e dos produtos a serem entregues pelo integrado";
  - **V** ⭐ — "as **fórmulas para o cálculo da eficiência da produção, com explicação detalhada dos parâmetros e da metodologia** empregados na obtenção dos resultados";
  - **VI** — "as formas e os prazos de distribuição dos resultados entre os contratantes";
  - **VII** — "visando a assegurar a viabilidade econômica, o equilíbrio dos contratos e a continuidade do processo produtivo, **será cumprido pelo integrador o valor de referência** para a remuneração do integrado, **definido pela Cadec na forma do art. 12** desta Lei, desde que atendidas as obrigações contidas no contrato";
  - **VIII** ⭐ — "os custos financeiros dos insumos fornecidos em adiantamento pelo integrador, **não podendo ser superiores às taxas de juros captadas, devendo ser comprovadas pela Cadec**";
  - **IX** — "as condições para o acesso às áreas de produção por preposto ou empregado do integrador e às instalações industriais ou comerciais diretamente afetas ao objeto do contrato de integração pelo produtor integrado, seu preposto ou empregado";
  - **X** — "as responsabilidades do integrador e do produtor integrado quanto ao **recolhimento de tributos** incidentes no sistema de integração";
  - **XI** — "as obrigações do integrador e do produtor integrado no cumprimento da **legislação de defesa agropecuária e sanitária**";
  - **XII** — "as obrigações do integrador e do produtor integrado no cumprimento da **legislação ambiental**";
  - **XIII** — "os custos e a extensão de sua cobertura, em caso de obrigatoriedade de contratação de **seguro** de produção e do empreendimento, devendo eventual subsídio sobre o prêmio concedido pelo poder público ser direcionado **proporcionalmente a quem arcar com os custos**";
  - **XIV** ⭐ — "o **prazo para aviso prévio**, no caso de rescisão unilateral e antecipada do contrato de integração, deve levar em consideração o **ciclo produtivo** da atividade e o **montante dos investimentos realizados**, devidamente **pactuado entre as partes**";
  - **XV** — "a instituição de Comissão de Acompanhamento, Desenvolvimento e Conciliação da Integração - CADEC, a quem as partes poderão recorrer para a interpretação de cláusulas contratuais ou outras questões inerentes ao contrato de integração";
  - **XVI** — "as sanções para os casos de inadimplemento e rescisão unilateral do contrato de integração."

  - **No agrário:** **forma escrita é requisito de validade**, não recomendação — é o único dispositivo do plugin inteiro que comina **nulidade** à falta de instrumento escrito num contrato agrário. O inciso **V** derruba "a fórmula é segredo de negócio": explicar parâmetros e metodologia é **cláusula obrigatória**. O **VIII** é o gancho contra insumo caro embutido, e traz um teto objetivo (**taxas de juros captadas**) com prova a cargo da CADEC.
  - **Usa:** `contrato-integracao-vertical` · `estilo-agrario` · `suprema-corte-agraria` (R1, R2) · `validador-agrario`.

### 3.1 🔴 NÃO EXISTE prazo legal de aviso prévio nesta lei — verificado por comando

O inciso XIV impõe **critérios** (ciclo produtivo + investimentos), **não número**. Varredura por comando em todo o texto: as **únicas duas menções a prazo numérico** da Lei 13.288/2016 são

1. **15 dias** — art. 7º, §4º (esclarecimentos sobre o RIPI, sem custo);
2. **6 meses** — art. 12, §3º (prazo do FONIAGRO para as metodologias).

Fora delas, só o ritmo **trimestral/anual** do DIPC (art. 9º, p.ú.), que não é prazo de aviso prévio. **Zero ocorrências** de "aviso prévio de", "trinta dias", "90 (noventa)".

⛔ Quem afirmar "a lei exige X dias de aviso prévio" está inventando. A peça **constrói** o prazo com laudo de ciclo produtivo e demonstrativo de investimento não amortizado, ancorada no inciso XIV.

⛔ **A lei também não promete dinheiro:** **zero ocorrências** de "indenização" e de "multa" em todo o texto. O art. 4º, XVI manda o **contrato** prever sanções — a lei não as fixa. "Indenização automática por rescisão" é venda do que o texto não dá.

### 3.2 O foro do art. 4º, parágrafo único — e o que ele realmente resolve no CPC 63, §1º

- **Art. 4º, parágrafo único** ✅ — "**O fórum do lugar onde se situa o empreendimento do produtor integrado é competente** para ações fundadas no contrato de integração, **devendo ser indicado no contrato**."

🔴 **Precisão de leitura, em três camadas — a C2 acertou o resultado e errou o caminho:**

1. **A palavra é "fórum", não "foro".** Verificado por comando: **zero ocorrências** de "foro " no texto da lei. Transcrição que escreva "o foro do lugar..." entre aspas **não é verbatim**.
2. **Isto é regra legal de competência, não cláusula de eleição de foro.** O CPC art. 63 governa a **modificação convencional** da competência pelas partes, e o **§1º** (red. Lei 14.879/2024) exige pertinência territorial **da eleição**. Um foro fixado **pela lei** não é eleição — logo o §1º **não lhe é requisito**: não há o que "satisfazer". Dizer "o art. 4º, p.ú. satisfaz a pertinência do art. 63, §1º" trata a regra legal como se fosse cláusula, e é atacável.
3. **O efeito prático, porém, é o que a C2 concluiu, por outra via:** como a lei já indica o foro do empreendimento do integrado, **cláusula que puxe o litígio para a sede da integradora é convenção que desloca a competência legal** — e aí, sim, entra o art. 63: precisa de pertinência com domicílio/residência de uma das partes ou com o local da obrigação (**§1º**), e o "juízo aleatório" é **declinável de ofício** (**§5º**). O ataque tem, portanto, **duas pernas independentes**: o art. 4º, p.ú. desta lei **e** o art. 63, §§1º e 5º do CPC.

🟡 **A lei não diz se essa competência é absoluta ou relativa.** O texto só diz "é competente". Sendo territorial, o padrão é **relativa** — sujeita a prorrogação se não alegada (CPC 65) e à preclusão do **art. 63, §4º** (alegar na contestação). **Não afirme competência absoluta**: nada no dispositivo autoriza. Confira em `context/cpc-agrario.md` (**grep "art. 63"** e **"art. 65"**) e roteie ao `validador-agrario`.

- **Usa:** `contrato-integracao-vertical` · `base-processual-agraria` · `suprema-corte-agraria` (R4).

## 4. FONIAGRO — art. 5º (e por que ele pode legitimamente não existir)

- **Art. 5º** ✅ — "Cada setor produtivo ou cadeia produtiva regidos por esta Lei **deverão constituir um Fórum Nacional de Integração - FONIAGRO**, de composição **paritária**, composto pelas entidades representativas dos produtores integrados e dos integradores, **sem personalidade jurídica**, com a atribuição de definir diretrizes para o acompanhamento e desenvolvimento do sistema de integração e de promover o fortalecimento das relações entre o produtor integrado e o integrador."
  - **§ 1º** ⭐ ✅ — "Para setores produtivos em que **já exista fórum ou entidade similar em funcionamento, será OPCIONAL a sua criação**."
  - **§ 2º** ✅ — "**O regulamento desta Lei** definirá o número de participantes do fórum e as entidades dos integrados e dos integradores que indicarão os representantes, seu regime e localidade de funcionamento e outros aspectos de sua organização."
  - **No agrário — achado que muda a postura:** o §1º **desarma** a leitura de que "a lei manda criar, logo tem de existir". Onde já houvesse fórum ou entidade similar em funcionamento em 2016, a criação do FONIAGRO é **facultativa por lei**. Portanto, a ausência de FONIAGRO num setor **não é, por si, ilegalidade da integradora** — e alegar isso como descumprimento é tese frágil. O ataque real continua sendo o **art. 4º, VII + art. 6º, §4º, VII** (a CADEC determina e faz cumprir o valor de referência), não a inexistência do fórum nacional.
  - **Usa:** `contrato-integracao-vertical` · `validador-agrario`.

## 5. CADEC — art. 6º (7 funções, contadas na fonte)

- **Art. 6º** ✅ — "**Cada unidade da integradora E os produtores a ela integrados devem constituir** Comissão para Acompanhamento, Desenvolvimento e Conciliação da Integração - **CADEC**."
  - **§ 1º** ✅ — "A Cadec será composta **paritariamente** por representantes: **I** - escolhidos diretamente pelos produtores integrados à unidade integradora; **II** - indicados pela integradora; **III** - indicados pelas entidades representativas dos produtores integrados; **IV** - indicados pelas entidades representativas das empresas integradoras." (**4**, contados na fonte)
  - **§ 2º** ⭐ ✅ — "A **falta de indicação dos representantes previstos nos incisos III e IV do § 1º** deste artigo **não impede a instalação e funcionamento da Cadec**."
  - **§ 3º** ✅ — "A constituição da Cadec **respeitará as estruturas com função similar às constituídas até a data de publicação desta Lei**."
  - **§ 4º** ✅ — "A Cadec terá os seguintes objetivos e funções, entre outros estabelecidos nesta Lei **e no regulamento**:" (**7 funções**, contadas na fonte)
    - **I** — "elaborar estudos e análises econômicas, sociais, tecnológicas, ambientais e dos aspectos jurídicos das cadeias produtivas e seus segmentos e do contrato de integração";
    - **II** — "acompanhar e avaliar o atendimento dos **padrões mínimos de qualidade** exigidos para os insumos recebidos pelos produtores integrados e para os produtos fornecidos ao integrador";
    - **III** — "estabelecer sistema de acompanhamento e avaliação do cumprimento dos encargos e obrigações contratuais pelos contratantes";
    - **IV** ⭐ — "**dirimir questões e solucionar, mediante acordo, litígios** entre os produtores integrados e a integradora";
    - **V** — "definir o intervalo de tempo e os requisitos técnicos e financeiros a serem empregados para **atualização dos indicadores de desempenho** das linhagens de animais e das cultivares de plantas utilizadas nas fórmulas de cálculo da eficiência de criação ou de cultivo";
    - **VI** — "formular o **plano de modernização tecnológica** da integração, estabelecer o prazo necessário para sua implantação e definir a participação dos integrados e do integrador no financiamento dos bens e ações previstas";
    - **VII** ⭐ — "**determinar e fazer cumprir o valor de referência** a que alude o inciso VII do art. 4º desta Lei."
  - **§ 5º** ✅ — "Toda e qualquer despesa da Cadec deverá ser **aprovada pelas partes contratantes, por demanda específica**."
  - ⛔ **É CADEC, nunca "CODEC".** Verificado por comando: **zero ocorrências** de "CODEC" no texto oficial. "CODEC" é erro de fonte secundária e queima a peça.
  - **No agrário:** o **§2º** é a resposta pronta à integradora que alega não ser possível constituir a comissão por falta de indicação das entidades — **não impede**. O **§4º, VII** é o dispositivo que dá dente ao valor de referência do art. 4º, VII.
  - **Usa:** `contrato-integracao-vertical` · `validador-agrario` · `suprema-corte-agraria` (R2).

## 6. RIPI — art. 7º (o relatório por ciclo, e os 15 dias sem custo)

- **Art. 7º** ✅ — "O integrador **deverá elaborar Relatório de Informações da Produção Integrada - RIPI** relativo a **cada ciclo produtivo** do produtor integrado."
  - **§ 1º** ✅ — "O Ripi deverá conter informações sobre os **insumos fornecidos** pelo integrador, os **indicadores técnicos** da produção integrada, as **quantidades produzidas**, os **índices de produtividade**, os **preços usados nos cálculos** dos resultados financeiros e os **valores pagos** aos produtores integrados relativos ao contrato de integração, entre outros a serem definidos pela Cadec."
  - **§ 2º** ✅ — "O Ripi deverá ser **consolidado até a data do acerto financeiro** entre integrador e produtor integrado, sendo fornecido ao integrado e, quando solicitado, à Cadec ou sua entidade representativa."
  - **§ 3º** ✅ — "Toda e qualquer informação relativa à produção do produtor integrado **solicitada por terceiros** só será fornecida pelo integrador **mediante autorização escrita** do produtor integrado."
  - **§ 4º** ⭐ ✅ — "É facultado ao produtor integrado, individualmente ou por intermédio de sua entidade representativa ou da Cadec, mediante autorização escrita, solicitar ao integrador **esclarecimentos ou informações adicionais sobre o Ripi**, os quais deverão ser fornecidos **sem custos e no prazo máximo de até quinze dias** após a solicitação."
  - **No agrário:** o §4º é **prazo pouco cobrado e fácil de provar** — pedido escrito + decurso de 15 dias monta descumprimento documental sem perícia. O §1º ("**preços usados nos cálculos**") é o que permite auditar a conta, e conecta ao art. 4º, V.
  - **Usa:** `contrato-integracao-vertical` · `calendario-safra-e-prazos-criticos`.

## 7. Máquinas, instalações e animais — art. 8º (o silêncio favorece o integrador)

- **Art. 8º** ✅ — "**Todas as máquinas e equipamentos fornecidos pelo integrador** ao produtor integrado em decorrência das necessidades da produção **permanecerão de propriedade do integrador**, devendo-lhe ser restituídos, **salvo estabelecimento em contrário no contrato** de integração."
  - **§ 1º** ✅ — "No caso de **instalações** financiadas ou integralmente custeadas pelo integrador, o contrato de integração **especificará se e quando** estas passarão a ser de propriedade do produtor integrado."
  - **§ 2º** ✅ — "No caso de **animais** fornecidos pelo integrador, o contrato de integração **especificará se e quando** passarão a ser de propriedade do produtor integrado."
  - **§ 3º** ✅ — "Poderá o contrato, ainda que por ajustes posteriores, estabelecer normas que permitam o **consumo próprio familiar**, salvo para os setores que necessitam de serviços de inspeção para o consumo do produto."
  - **No agrário:** regra supletiva **pró-integrador** — no silêncio, máquina e equipamento voltam para ele. Nos §§1º e 2º a lei **não fixa destino**: remete ao contrato. Na consultiva do integrado, é aqui que se negocia; no contencioso, é aqui que se mede o **investimento não amortizado** que alimenta o art. 4º, XIV.
  - **Usa:** `contrato-integracao-vertical`.

## 8. DIPC — art. 9º, o documento PRÉ-contratual (13 informações)

- **Art. 9º** ✅ — "**Ao produtor interessado em aderir** ao sistema de integração **será apresentado pelo integrador** Documento de Informação Pré-Contratual - **DIPC**, contendo **obrigatoriamente** as seguintes informações **atualizadas**:" (**13**, contadas na fonte)

  - **I** — "razão social, forma societária, Cadastro Nacional da Pessoa Jurídica - CNPJ e endereços do integrador";
  - **II** — "descrição do sistema de produção integrada e das atividades a serem desempenhadas pelo produtor integrado";
  - **III** — "requisitos sanitários e ambientais e **riscos econômicos inerentes à atividade**";
  - **IV** ⭐ — "**estimativa dos investimentos** em instalações zootécnicas ou áreas de cultivo e dos **custos fixos e variáveis** do produtor integrado na produção";
  - **V** — "**obrigação ou não** do produtor integrado de adquirir ou contratar, apenas do integrador ou de fornecedores indicados formalmente pelo integrador, quaisquer bens, serviços ou insumos necessários à operação ou à administração de suas instalações zootécnicas ou áreas de cultivo";
  - **VI** — "relação do que será oferecido ao produtor integrado no que se refere a: **a)** suprimento de insumos; **b)** assistência técnica e supervisão da adoção das tecnologias de produção recomendadas cientificamente ou exigidas pelo integrador; **c)** treinamento do produtor integrado, de seus prepostos ou empregados, especificando duração, conteúdo e custos; **d)** projeto técnico do empreendimento e termos do contrato de integração"; (**4 alíneas**, contadas na fonte)
  - **VII** ⭐ — "**estimativa de remuneração** do produtor integrado por ciclo de criação de animais ou safra agrícola, utilizando-se, para o cálculo, **preços e índices de eficiência produtiva médios nos vinte e quatro meses anteriores, e validados pela respectiva Cadec**";
  - **VIII** — "alternativas de **financiamento** por instituição financeira ou pelo integrador e garantias do integrador para o cumprimento do contrato durante o período do financiamento";
  - **IX** — "os parâmetros técnicos e econômicos indicados pelo integrador e **validados pela respectiva Cadec** para uso no estudo de viabilidade econômico-financeira do projeto de financiamento do empreendimento";
  - **X** ⭐ — "**caráter e grau de exclusividade** da relação entre o produtor integrado e o integrador, se for o caso";
  - **XI** — "**tributos e seguros** incidentes na atividade e a responsabilidade das partes, segundo a legislação pertinente";
  - **XII** — "**responsabilidades ambientais** das partes, segundo o art. 10 desta Lei";
  - **XIII** — "**responsabilidades sanitárias** das partes, segundo legislação e normas infralegais específicas."
  - **Parágrafo único** ⭐ ✅ — "O DIPC deverá ser **atualizado trimestralmente para os setores de produção animal e anualmente para os setores de produção e extração vegetal**."
  - **No agrário:** o DIPC é **anterior à adesão** — logo, DIPC ausente, desatualizado (fora do ritmo do p.ú.) ou com projeção do inciso VII **fora da base de 24 meses validada pela CADEC** é **vício na formação do contrato**, não mero descumprimento. É o fundamento de quem aderiu com informação falsa sobre rentabilidade. O inciso **X** é a âncora contra exclusividade não revelada.
  - 🔴 **Atenção à assimetria:** a lei manda **apresentar** o DIPC, mas **não** comina nulidade pela sua falta (a nulidade do art. 4º é da **forma escrita do contrato**). Não transporte a nulidade do art. 4º para o art. 9º — o caminho do DIPC é vício de consentimento/informação, e é preciso construí-lo.
  - **Usa:** `contrato-integracao-vertical` · `descaracterizacao-e-figuras-atipicas` · `suprema-corte-agraria` (R2).

## 9. Responsabilidade ambiental (art. 10) e sanitária (art. 11)

- **Art. 10** ✅ — "Compete ao produtor integrado e à integradora **atender às exigências da legislação ambiental** para o empreendimento ou atividade desenvolvida no imóvel rural na execução do contrato de integração, bem como planejar e implementar medidas de prevenção dos potenciais impactos ambientais negativos e mitigar e recuperar os danos ambientais."
  - **§ 1º** ✅ — "Nas atividades de integração em que as **tecnologias empregadas sejam definidas e sua adoção supervisionada pelo integrador**, este e o integrado **responderão, até o limite de sua responsabilidade**, pelas ações relativas à proteção ambiental e à recuperação de danos ao meio ambiente ocorridos em decorrência do empreendimento."
  - **§ 2º** ⭐ ✅ — "A responsabilidade de recuperação de danos de que trata o § 1º deste artigo **deixa de ser concorrente quando o produtor integrado adotar conduta contrária ou diversa às recomendações técnicas** fornecidas pelo integrador ou estabelecidas no contrato de integração."
  - **§ 3º** ✅ — "Compete ao integrador, no sistema de integração em que as tecnologias empregadas sejam por ele definidas e supervisionadas: **I** - fornecer **projeto técnico** de instalações e de obras complementares, em conformidade com as exigências da legislação ambiental, e supervisionar sua implantação; **II** - auxiliar o produtor integrado no planejamento de medidas de prevenção, controle e mitigação dos potenciais impactos ambientais negativos e prestar-lhe assistência técnica na sua implementação; **III** - elaborar, em conjunto com o produtor integrado, **plano de descarte de embalagens de agrotóxicos, desinfetantes e produtos veterinários** e supervisionar sua implantação; **IV** - elaborar, em conjunto com o produtor integrado, **plano de manejo de outros resíduos** da atividade e de **disposição final dos animais mortos** e supervisionar sua implantação." (**4 deveres**, contados na fonte)
  - 🔴 **A concorrência ambiental do §1º é CONDICIONADA e tem escape.** Ela só existe onde as tecnologias são **definidas e supervisionadas pelo integrador**, é limitada "**até o limite de sua responsabilidade**", e **cessa** pelo §2º se o integrado agiu contra a recomendação técnica. Vender ao integrado "o integrador responde junto, sempre" é errado nos dois sentidos.
  - **Usa:** `contrato-integracao-vertical` · `tac-e-responsabilidade-ambiental-rural` · `defesa-em-auto-de-infracao-ambiental`.

- **Art. 11** ✅ — "Compete ao produtor integrado e ao integrador, **concorrentemente**, zelar pelo cumprimento da **legislação sanitária** e planejar medidas de prevenção e controle de pragas e doenças, conforme regulamento estabelecido pelos órgãos competentes."
  - **Parágrafo único** ✅ — "Nos sistemas de integração em que os **medicamentos veterinários** utilizados sejam de propriedade do integrador, **o recolhimento e a destinação final das embalagens de antibióticos ou de outros produtos antimicrobianos deverão ser por ele realizados**."
  - **No agrário:** note a diferença de regime — a sanitária do art. 11 é **concorrente sem a condicionante** do art. 10, §1º; e o p.ú. põe um dever **exclusivo** no integrador quando o medicamento é dele.

## 10. Valor de referência — art. 12 (e o prazo que é prorrogável)

- **Art. 12** ✅ — "Compete ao **Fórum Nacional de Integração - FONIAGRO estabelecer metodologia para o cálculo do valor de referência** para a remuneração do integrado, que deverá observar os **custos de produção**, os **valores de mercado dos produtos in natura**, o **rendimento médio dos lotes**, dentre outras variáveis, **para cada cadeia produtiva**."
  - **§ 1º** ✅ — "Para estabelecer metodologia [...], o Foniagro **poderá contratar entidades ou instituições de notório reconhecimento técnico**, desde que requisitada por uma das partes e cuja escolha dar-se-á **por comum acordo**."
  - **§ 2º** ✅ — "A metodologia [...] será **reavaliada periodicamente**, conforme regulamentação específica do Foniagro."
  - **§ 3º** ✅ — "O Foniagro terá o prazo máximo de **seis meses contados da promulgação desta Lei** para apresentar as metodologias de cálculo para cada cadeia produtiva, **podendo esse prazo ser prorrogado, mediante justificativa aceita pelas partes**."
  - **§ 4º** ✅ — "Compete ao Foniagro o **envio das metodologias** para o cálculo do valor de referência para a remuneração dos integrados **às respectivas Cadecs**."
  - 🔴 **Correção de precisão:** dizer "o prazo do art. 12 venceu em novembro de 2016" é **meia-verdade**. A lei é de **16/05/2016**, e seis meses da promulgação cai em **16/11/2016** — mas o próprio §3º admite **prorrogação mediante justificativa aceita pelas partes**, sem teto. Portanto o descumprimento **não é automático pelo decurso**: depende de não ter havido prorrogação. Alegar preclusão do prazo sem apurar isso é alegação vulnerável.
  - **No agrário — a cadeia completa que a peça precisa desenhar:** art. 4º, VII (o integrador **cumpre** o valor de referência) ← art. 6º, §4º, VII (a **CADEC determina e faz cumprir**) ← art. 12 (o **FONIAGRO** fornece a **metodologia**) — com o art. 5º, §1º avisando que o FONIAGRO pode legitimamente não ter sido criado. **Onde a metodologia não existir, a obrigação do art. 4º, VII fica sem parâmetro** — e esse é o ponto honesto a informar ao cliente, não a esconder.
  - **Usa:** `contrato-integracao-vertical` · `validador-agrario`.

## 11. ⭐ Art. 13 — restituição na insolvência da integradora

- **Art. 13** ✅ — "**Sobrevindo pedido de recuperação judicial ou decretação da falência da integradora**, poderá o produtor rural integrado:
  - **I** - **pleitear a restituição dos bens desenvolvidos até o valor de seu crédito**;
  - **II** - requerer a **habilitação de seus créditos com privilégio especial sobre os bens desenvolvidos**."

  - 🔴 **A assimetria do gatilho é literal e decisiva:** na recuperação judicial o marco é o **PEDIDO** (não o deferimento do processamento, não a concessão); na falência é a **DECRETAÇÃO**. Escrever "deferido o processamento da recuperação" no lugar de "pedido" **atrasa o marco** e pode custar o momento da medida. Transcreva o gatilho como está.
  - ⚠️ **Restituição (I) não é habilitação (II), e nenhuma das duas é crédito quirografário.** O inciso II já vem com **privilégio especial** sobre os bens desenvolvidos. Quem habilita como quirografário abre mão **dos dois** incisos. Peça-modelo: **pedido de restituição** (I) instruído com contrato, RIPI do ciclo e prova dos bens em poder da recuperanda — com a habilitação com privilégio especial (II) como alternativa subsidiária.
  - 🟡 **"Bens desenvolvidos" não é definido pela lei.** O termo não aparece no art. 2º (definições) nem em nenhum outro dispositivo. Não afirme extensão ("são os animais alojados", "inclui a instalação") como se fosse texto — **delimite no caso concreto**, pela prova, e roteie ao `validador-agrario`.
  - 🟡 **A articulação com a Lei 11.101/2005 (restituição, extraconcursalidade, trava bancária) NÃO está ancorada neste anexo.** Este anexo cobre **apenas** a Lei 13.288/2016. Regime de RJ resolve em `context/rj-produtor-rural.md` — **grep o artigo e leia a faixa** — e o que não estiver lá não se cita de memória.
  - **Usa:** `contrato-integracao-vertical` · `rj-produtor-rural` · `rj-sujeicao-de-creditos-agro`.

## 12. Vigência — art. 14

- **Art. 14** ✅ — "Esta Lei **entra em vigor na data de sua publicação**. **Parágrafo único. (VETADO).**"
  - Sanção em **16/05/2016**; publicação no **DOU de 17.5.2016** (nota de rodapé oficial: "Este texto não substitui o publicado no DOU de 17.5.2016"). **Sem vacatio legis.**
  - 🔴 **Não cite o parágrafo único do art. 14**: ele foi **vetado** e nunca vigorou. Se alguma fonte secundária lhe atribuir conteúdo, a fonte está errada.

---

## Guard

Todo dispositivo transcrito acima está marcado **✅ conferido verbatim** no texto da **Lei 13.288/2016** capturado do Planalto em **02/08/2026**. Isso **encerra o gap** da `contrato-integracao-vertical`: a base legal da skill agora **resolve em anexo** e pode ser citada com redação literal.

**O que este anexo NÃO autoriza:**

- 🔴 **Afirmar prazo de aviso prévio em dias.** A lei tem **duas** menções a prazo numérico (15 dias do art. 7º, §4º; 6 meses do art. 12, §3º) e **nenhuma** delas é aviso prévio. O art. 4º, XIV dá **critérios**, não número.
- 🔴 **Prometer indenização ou multa por rescisão com base na lei.** **Zero ocorrências** de "indenização" e "multa" no texto. O art. 4º, XVI manda o **contrato** dispor sobre sanções — a lei não as fixa.
- 🔴 **Citar "aves", "suínos", "avicultura" ou "frango" como categorias legais.** **Zero ocorrências** de cada uma. O rol é o do **art. 2º, V** ("agricultura, pecuária, silvicultura, aquicultura, pesca ou extrativismo vegetal").
- 🔴 **Escrever "foro" entre aspas no art. 4º, p.ú.** O texto diz "**fórum**". E o dispositivo é **regra legal de competência**, não cláusula de eleição — não se diz que ele "satisfaz" o requisito do CPC 63, §1º, que é requisito **de eleição**. Ver §3.2.
- 🔴 **Atribuir a esta lei qualquer alteração posterior.** Ela está na **redação original**, sem um único "Redação dada"/"Incluído"/"Revogado" na fonte. Alteração citada = alteração inventada.
- 🔴 **Citar o parágrafo único do art. 14** — **(VETADO)**.
- 🟡 **Natureza (absoluta × relativa) da competência do art. 4º, p.ú.** — a lei não diz. Não afirmar absoluta. Conferir em `context/cpc-agrario.md` (arts. 63 e 65) e rotear ao `validador-agrario`.
- 🟡 **Extensão de "bens desenvolvidos" (art. 13)** — não definida em lei. Delimitar pela prova no caso concreto.
- 🟡 **REGULAMENTO FEDERAL DA LEI 13.288/2016 — NÃO LOCALIZADO.** Os arts. **5º, §2º** e **6º, §4º** remetem a "regulamento". Busca dirigida em 02/08/2026 **não localizou decreto regulamentador**; retornaram apenas o texto da lei, materiais de entidades de classe (CNA — "Programa CADEC Brasil"; Sistema FAEP — cartilha de CADECs no Paraná) e doutrina. **Não cite decreto regulamentador desta lei.** Gap mantido conforme declarado pela C2.
- 🟡 **Existência e funcionamento concretos de FONIAGRO e das metodologias do art. 12 — NÃO CONFIRMADOS.** E note que o **art. 5º, §1º torna a criação OPCIONAL** onde já houvesse fórum ou entidade similar: a ausência **não é**, por si, ilegalidade. Não sustente tese sobre isso sem apuração no caso.
- 🟡 **CDC entre integrado e integradora** — não é matéria deste anexo, e o **art. 2º, §3º** diz que a relação é **civil**. Jurisprudência resolve em `context/jurisprudencia-agraria.md`; a busca dirigida anterior no STJ voltou **vazia**. Não sustentar como pacífica.
- ⛔ **CADEC**, nunca "CODEC" (**zero ocorrências** de "CODEC" na fonte). **DIPC** é o pré-contratual (art. 9º); **RIPI** é o do ciclo (art. 7º). Não trocar.

**Fronteira do anexo:** este arquivo cobre **exclusivamente a Lei 13.288/2016**. CPC resolve em `context/cpc-agrario.md`; Estatuto da Terra e o **ET 96, §5º** (a porta de saída do art. 96 para esta lei) em `context/estatuto-e-decreto-contratos-agrarios.md`; recuperação judicial em `context/rj-produtor-rural.md`; jurisprudência em `context/jurisprudencia-agraria.md`. **Nenhum artigo dessas outras normas está ancorado aqui.**

Nenhum item deste anexo dispensa o fecho pela **`suprema-corte-agraria` (R1-R4)** e pelo **`validador-agrario`** antes da entrega.
