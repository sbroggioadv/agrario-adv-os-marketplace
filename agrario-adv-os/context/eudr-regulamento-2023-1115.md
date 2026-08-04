# EUDR — Regulamento (UE) 2023/1115 · desmatamento zero na exportação para a União Europeia 🔴

> Anexo de referência do plugin **agrario-adv-os**, exclusivo da skill **`compliance-eudr`** (camada C6).
> **Fonte-mestra:** EUR-Lex, **texto consolidado PT de 26/12/2025** — CELEX **02023R1115-20251226**. Captura em **02/08/2026**.
> **Legenda:** ✅ lido no EUR-Lex, na versão consolidada vigente em português · 🟡 documento identificado mas não aberto, **ou** consequência que **decorre** do texto sem estar escrita nele · 🔴 ato adotado e **ainda não vigente**, ou pós-corte de treino.
> **Como usar:** `grep` pelo artigo (`art. 9.º`, `art. 4.º-A`, `art. 38.º`) e leia **a faixa**. Nunca despeje o arquivo inteiro.

---

## 0. 🚩 ARMADILHA Nº 1 — LEIA ANTES DE QUALQUER COISA

> # ⛔ O BRASIL É **RISCO PADRÃO**. O REGIME SIMPLIFICADO NÃO SE APLICA.
>
> O Reg. (UE) 2025/2650 criou dois atalhos sedutores — o **art. 4.º-A** (declaração simplificada única e, sobretudo, **endereço postal no lugar da geolocalização**) e o **art. 13.º** (dispensa dos arts. 10.º e 11.º). **NENHUM DOS DOIS ALCANÇA O BRASIL.**
>
> **Por quê, com âncora:** ambos exigem **país de BAIXO RISCO**. O **Reg. Exec. (UE) 2025/1093** classifica os países, e o Brasil **não consta de nenhuma das duas listas** — nem alto risco (que tem **exatamente 4 países**: Bielorrússia, Coreia do Norte, Mianmar/Birmânia, Rússia) nem baixo risco. Pelo **art. 1.º, n.º 2** ("mantém-se o nível padrão para todos os países não enumerados no anexo"), **o Brasil é RISCO PADRÃO**.
>
> **O que isso proíbe a skill de dizer:**
> - ❌ que pequeno produtor brasileiro é «micro ou pequeno operador primário» — **não é**, a definição exige estabelecimento em país de baixo risco;
> - ❌ que ele pode **substituir geolocalização por endereço postal** — **não pode**;
> - ❌ que ele pode apresentar **declaração simplificada** (art. 4.º-A) ou usar a **diligência simplificada** (art. 13.º);
> - ❌ que dá para **triangular por país de baixo risco** — a **cláusula antievasão do art. 13.º fecha essa rota expressamente**, "incluindo nos casos em que os produtos produzidos num país de **risco padrão ou alto** sejam **subsequentemente transformados num país de baixo risco**".
>
> **O que vale para o Brasil:** diligência devida **COMPLETA** (arts. 8.º a 11.º) · **geolocalização obrigatória** em ponto (6 decimais) até 4 ha e **polígono** acima de 4 ha, **bovinos sempre por estabelecimento** · **data-corte 31/12/2020, fixa** · controlos sobre **pelo menos 3%** dos operadores.
>
> **Aplicar o regime simplificado ao pequeno cafeicultor de Minas ou ao produtor familiar do Cerrado é conselho ERRADO E PREJUDICIAL.** Desenvolvimento completo em **§8**; lista fechada de proibições em **§12**.
>
> ⚠️ **Risco padrão NÃO é rebaixamento.** É o nível *default* atribuído a todos os países em 2023 — Argentina, Indonésia, Malásia e México também são. O Brasil está no mesmo nível dos concorrentes diretos.

---

## 0.1 ⛔ AS TRÊS TRAVAS DE FONTE

1. **É NORMA ESTRANGEIRA.** Nenhuma linha da skill pode vir de memória do modelo, de notícia setorial ou do dossiê de mercado. **Só o texto consolidado do EUR-Lex.**
2. **A versão que vale é a CONSOLIDADA de 26/12/2025.** O Regulamento foi alterado **duas vezes**, e a segunda alteração reescreveu ~40 dispositivos, criou o **art. 4.º-A**, criou o **Anexo III** e mudou o desenho das obrigações da cadeia. **Citar a redação original de 2023 de qualquer artigo tocado é citar norma revogada.**
3. **Marcadores do consolidado:** `▼B` = redação de base (2023) · `▼M1` = Reg. (UE) 2024/3234 · `▼M2` = Reg. (UE) 2025/2650. Onde a citação carrega `▼M2`, é redação de **dezembro de 2025** — provavelmente ausente de qualquer base de treino.

---

## 1. A norma e as duas alterações ✅

| Ato | O que é | Estado |
|---|---|---|
| **Regulamento (UE) 2023/1115**, de 31/05/2023 | A norma-base. JO L 150 de 9.6.2023, p. 206. Entrada em vigor **29/06/2023**. Revoga o Reg. (UE) n.º 995/2010 (EUTR) | Em vigor, na redação consolidada |
| **Regulamento (UE) 2024/3234** | **1.º adiamento** — alterou os arts. 29.º(2), 37.º, 38.º(2) e 38.º(3). Consolidação de 26/12/2024 | **Superado quanto às datas** |
| **Regulamento (UE) 2025/2650**, de 19/12/2025 | **2.º adiamento (+12 meses) + simplificação.** Alterou ~40 dispositivos (arts. 2.º, 3.º, 4.º, 5.º, 6.º, 8.º, 9.º, 15.º a 28.º, 31.º a 35.º, 37.º, 38.º), **inseriu o art. 4.º-A**, alterou os Anexos I e II e **acrescentou o Anexo III**. Entrada em vigor **26/12/2025** | **É a redação que vale** |

**Considerando (15) do Reg. 2025/2650 (literal):** "A data de aplicação das disposições do Regulamento (UE) 2023/1115 que preveem obrigações para os operadores, comerciantes e autoridades competentes (…) deverá ser **adiada por 12 meses**."

---

## 2. ⭐ OS PRAZOS VIGENTES — art. 38.º ✅

**N.º 2 (literal):** "Sem prejuízo do disposto no n.º 3 (…), **os artigos 3.º a 13.º, os artigos 16.º a 24.º e os artigos 26.º, 31.º e 32.º são aplicáveis a partir de 30 de dezembro de 2026**."

**N.º 3 (literal):** "**Com exceção dos produtos abrangidos pelo anexo do Regulamento (UE) n.º 995/2010**, para os operadores — quer sejam **pessoas singulares**, ou **microempresas ou pequenas empresas** (…) da Diretiva 2013/34/UE, independentemente da sua forma jurídica — **criados até 31 de dezembro de 2024**, os artigos a que se refere o n.º 2 (…) **são aplicáveis a partir de 30 de junho de 2027**."

| Regime | Data |
|---|---|
| **Regra geral** (grandes e médios operadores) | **30 de dezembro de 2026** |
| **Pessoas singulares, micro e pequenas empresas criadas até 31/12/2024** | **30 de junho de 2027** |

### 🚨 Três precisões que o par "30/12/2026 · 30/06/2027" esconde

1. **O prazo de 30/06/2027 tem CORTE DE DATA DE CRIAÇÃO.** Só alcança micro/pequenas empresas e pessoas singulares **criadas até 31/12/2024**. Uma microempresa constituída **em 2025 ou 2026** aplica-se **desde 30/12/2026**, como as grandes. Erro fácil e caro.
2. **MADEIRA NÃO TEM O PRAZO ESTENDIDO.** O n.º 3 exclui "os produtos abrangidos pelo anexo do Regulamento (UE) n.º 995/2010" (a antiga EUTR). Micro/pequena empresa que lide com **madeira entra em 30/12/2026**, não em 30/06/2027.
3. **Nem todo o regulamento está adiado.** O n.º 2 lista **arts. 3.º a 13.º, 16.º a 24.º, 26.º, 31.º e 32.º**. Ficam **fora da lista** — notoriamente — o **art. 25.º (sanções)**, o **art. 29.º (avaliação dos países)** e o **art. 33.º (sistema de informação)**.
   🟡 **Limite do que se pode afirmar:** a skill pode dizer que **esses artigos não constam da lista de diferimento**; **não** pode afirmar categoricamente uma data de aplicação que a fonte não fixa.

---

## 3. Objeto, âmbito e os 7 produtos de base ✅

**Art. 1.º (literal):** o regulamento estabelece regras relativas à **colocação e disponibilização no mercado da União, bem como à exportação para fora do mercado**, dos "**produtos derivados em causa, enumerados no anexo I**, que contenham ou tenham sido alimentados ou fabricados com produtos de base em causa, a saber **bovinos, cacau, café, palmeira-dendém, borracha, soja e madeira**".

**Duas leituras que a skill precisa fazer certo:**
1. São **7 produtos de base** e o **rol é FECHADO**. **Milho e biocombustíveis NÃO estão** — o art. 34.º manda apenas *avaliar* a inclusão numa revisão futura.
2. O regulamento alcança a **exportação para fora da União** — isto é, o exportador **europeu**. **Não é a base jurídica das obrigações do exportador brasileiro** (ver §5).

### Anexo I — o que da pauta brasileira está DENTRO hoje ✅

| Produto de base | Códigos relevantes |
|---|---|
| **Bovinos** | `0102 21`, `0102 29` vivos · `ex 0201` carnes frescas/refrigeradas · `ex 0202` congeladas · `ex 0206 10`, `ex 0206 22`, `ex 0206 29` miudezas · `ex 1602 50` preparações · **`ex 4101` couros e peles em bruto** · **`ex 4104` curtidos ou *crust*** · **`ex 4107` preparados após curtimenta** |
| **Cacau** | `1801` a `1806` |
| **Café** | `0901` (mesmo torrado ou descafeinado; cascas, películas e sucedâneos com café em qualquer proporção) |
| **Palmeira-dendém** | `1207 10` · `1511` · `1513 21`/`1513 29` · `2306 60` · `ex 2905 45` · `2915 70`, `2915 90` · `3823 11/12/19/70` |
| **Borracha** | `4001` natural · `ex 4005` a `ex 4010` · **`ex 4011` pneumáticos novos** · `ex 4012` recauchutados/usados · `ex 4013`, `ex 4015`, `ex 4016`, `ex 4017` |
| **Soja** | **`1201` soja, mesmo triturada** · `1208 10` farinha · `1507` óleo e frações · **`2304` bagaços (o farelo)** |
| **Madeira** | `4401` a `4421` · **pasta e papel dos Capítulos 47 e 48**, exceto bambu e papel/cartão reciclados (`▼M2`) · `ex 9401` assentos · `9403 30/40/50/60/91` móveis · `9406 10` pré-fabricadas |

**Da pauta exportadora brasileira, está dentro hoje:** soja em grão e farelo, carne bovina fresca e congelada, **couros e peles bovinos**, café, cacau, celulose e papel, madeira e móveis, pneus. **É a espinha dorsal do agro exportador — por isso a skill existe.**

⚠️ **Ver §11** — há ato delegado **adotado e não vigente** que altera este anexo.

---

## 4. A proibição e a data-corte ✅

### Art. 3.º — as TRÊS condições CUMULATIVAS

**Literal:** "Os produtos de base em causa e os produtos derivados em causa **não podem ser colocados nem disponibilizados no mercado, nem exportados**, a menos que estejam preenchidas **TODAS** as seguintes condições:
**a)** **Não estarem associados à desflorestação**;
**b)** **Terem sido produzidos em conformidade com a legislação aplicável do país de produção**; e
**c)** *(`▼M2`)* **Estarem abrangidos por uma declaração de diligência devida ou por uma declaração simplificada** (…)."

> **Falhar UMA só já proíbe.** E a alínea **b)** é o gancho que puxa o direito brasileiro para dentro do regulamento europeu (§10).

### Art. 2.º, ponto 13 — «Não associado à desflorestação»: **31/12/2020** ✅

**Literal:** "(…) **a)** Que os produtos derivados em causa contêm, foram alimentados ou fabricados com produtos de base em causa **produzidos em terras que não foram objeto de desflorestação após 31 de dezembro de 2020**; e **b)** No caso de (…) madeira, que **a madeira foi extraída da floresta após 31 de dezembro de 2020 sem provocar a degradação florestal**."

> ⛔ **A data-corte NÃO foi alterada pelos dois adiamentos.** Os adiamentos moveram a data de **aplicação**; **não** moveram a data-corte. **31/12/2020 é fixa.**

**«Desflorestação» (literal):** "a **conversão de florestas para uso agrícola**, quer tenha origem humana ou não".
> ⚠️ **"quer tenha origem humana ou não" — desmatamento por causa NATURAL conta.** A tese "não fui eu, foi o fogo / foi a natureza" **não afasta a não conformidade** perante o EUDR (embora possa ser relevante no direito brasileiro).

🟡 **«Degradação florestal»:** a captura devolveu o *caput* e **não as alíneas**. **A skill NÃO deve enunciar o rol de cabeça — deve remeter ao art. 2.º.**

---

## 5. ⭐ QUEM CARREGA A OBRIGAÇÃO — o ponto onde a skill mal calibrada erra feio

### Art. 7.º — o artigo mais importante para o cliente brasileiro ✅

**Literal:** "Se uma pessoa singular ou coletiva **estabelecida fora da União** colocar produtos derivados em causa no mercado, **a primeira pessoa singular ou coletiva estabelecida na União que disponibilize no mercado esses produtos derivados em causa é considerada um operador** na aceção do presente regulamento."

> ⭐ **A obrigação legal de exercer a diligência devida e apresentar a declaração recai sobre o IMPORTADOR / primeiro disponibilizador na UE.** O produtor ou a trading brasileira **não é destinatário direto** do regulamento — salvo se ele próprio colocar o produto no mercado da União por estabelecimento na UE.

🟡 **Consequência prática (decorre do texto, não está escrita nele):** o que chega ao produtor brasileiro é **exigência CONTRATUAL do comprador europeu** (geolocalização, prova de legalidade, rastreabilidade), porque o importador não consegue cumprir o art. 9.º sem esses dados. **A skill deve dizer isso como consequência COMERCIAL, nunca como "obrigação legal do produtor brasileiro perante a UE".**

### Definições da cadeia ✅

- **«Operador»** — "qualquer pessoa singular ou coletiva que, no âmbito de uma atividade comercial, **coloque no mercado ou exporte** os produtos derivados em causa, **com exceção dos operadores a jusante**" (`▼M2`).
- **«Comerciante»** — "qualquer pessoa na cadeia de abastecimento **que não seja o operador ou o operador a jusante** e que (…) **disponibilize** produtos derivados em causa no mercado" (`▼M2`).

### Art. 4.º — obrigações do operador ✅

- Exerce a **diligência devida do art. 8.º ANTES** de colocar no mercado ou exportar.
- **Não pode colocar nem exportar sem apresentação prévia da declaração de diligência devida**, via **sistema de informação do art. 33.º**, com as informações do **Anexo II** e declaração de que **"não foi detetado nenhum risco, ou apenas foi detetado um risco negligenciável"**.
- Ao apresentar a declaração, "**assume a responsabilidade pela conformidade**". **Conserva registo das declarações durante 5 anos.**
- **Não pode colocar/exportar se:** a) forem não conformes; **b) a diligência revelou RISCO NÃO NEGLIGENCIÁVEL**; c) não cumpriu as obrigações dos n.os 1 e 2.
- Nas exportações, informa a autoridade competente do Estado-Membro que é o país de produção.
- **Comunica aos operadores e comerciantes a jusante** os **números de referência das declarações** ou os **identificadores de declaração**.

> ⚠️ **O padrão de decisão é binário:** "risco **nulo ou negligenciável**" é a **única** porta de saída. **Não existe "risco aceitável", "risco mitigado a contento" ou juízo de proporcionalidade.**

### Art. 5.º — operadores a jusante e comerciantes ✅ (`▼M2` — **artigo inteiramente reescrito**)

- Só podem colocar/disponibilizar/exportar **se estiverem na posse das informações do n.º 3**.
- Os **NÃO-PME** (operadores a jusante e comerciantes) **registam-se no sistema de informação** do art. 33.º antes de colocar/disponibilizar/exportar.
- Informações a recolher e **conservar por, pelo menos, 5 anos**: identificação completa de quem forneceu (nome, denominação, endereço postal, e-mail, endereço Web se disponível) e, sendo o fornecedor um operador, **os números de referência das declarações ou os identificadores**; e a **quantidade**.
- Dever de **informar imediatamente** as autoridades competentes ao tomar conhecimento de informação — **incluindo preocupações fundamentadas** — que indique risco de não conformidade.
- Os **não-PME** têm dever de **verificar antes de colocar** e de **não colocar** "a menos que a verificação demonstre que o risco de não conformidade é inexistente ou apenas negligenciável".

> **Assimetria PME × não-PME:** o registo e a verificação prévia pesam sobre os **não-PME**. Os PME a jusante recolhem e conservam, mas não se registam nem verificam nos mesmos termos.
> ⛔ **A redação de 2023 do art. 5.º (que tratava só de "comerciantes") está MORTA.**

### Art. 6.º — mandatários ✅ (`▼M2`)

Os operadores podem **mandatar um representante** para apresentar a declaração; "**o operador continua a ser responsável** pela conformidade". Operador **pessoa singular ou microempresa** pode mandatar o operador ou comerciante **imediatamente a jusante** que não seja pessoa singular nem microempresa — e mesmo assim "**continua a ser responsável**".

> **Mandato desloca a EXECUÇÃO, nunca a RESPONSABILIDADE.** O texto repete isso duas vezes.

---

## 6. O dever de diligência — arquitetura de 3 etapas ✅

**Art. 8.º** — a diligência devida inclui: **a)** **recolha** de informações, dados e documentos (art. 9.º); **b)** **avaliação do risco** (art. 10.º); **c)** **atenuação do risco** (art. 11.º). *(caput em `▼M2`: exercida "no que diz respeito a **todos** os produtos derivados em causa".)*

### Art. 9.º — requisitos de informação (o que o comprador vai pedir) ✅

O operador **recolhe, organiza e conserva durante 5 anos**, **acompanhadas de elementos de prova**:
- **a)** descrição, denominação comercial e tipo; para madeira, "a denominação comum da espécie e o seu **nome científico completo**";
- **b)** *(`▼M2`)* quantidade — "em **quilogramas de massa líquida**";
- **c)** "**O país de produção e, se for caso disso, as partes desse país**";
- **d)** **a geolocalização** (§7 abaixo);
- **e)** nome, endereço postal e e-mail de quem forneceu;
- **f)** *(`▼M2`)* identificação de "qualquer empresa, **operador a jusante ou comerciante** a quem tenham sido fornecidos";
- **g)** "Informações **devidamente conclusivas e verificáveis** que indiquem que os produtos derivados em causa **não estão associados à desflorestação**";
- **h)** "Informações devidamente conclusivas e verificáveis de que os produtos de base foram **produzidos em conformidade com a legislação aplicável do país de produção**, incluindo qualquer disposição que confira o **direito de utilização da respetiva zona** para efeitos de produção".

> ⭐ **O padrão probatório é "devidamente CONCLUSIVAS e VERIFICÁVEIS"** (alíneas g e h). **Não basta declaração do fornecedor** — tem de ser verificável por terceiro.

### Art. 10.º — avaliação do risco ✅

**Regra de decisão (literal):** os operadores "**não podem colocar no mercado nem exportar (…) a menos que a avaliação do risco revele a inexistência de risco ou apenas a existência de um risco negligenciável** de (…) não conformidade."

**Os 14 critérios (a a n)**, entre os quais: **a)** a **atribuição de risco ao país de produção** (art. 29.º); **f)** prevalência da desflorestação no país ou em partes dele; **h)** "o **nível de corrupção**, a prevalência de **falsificação de documentos e de dados**, a **falta de fiscalização** da aplicação das leis, as violações de direitos humanos internacionais, os conflitos armados ou a presença de sanções"; **i)** **complexidade da cadeia** e dificuldade de ligar o produto à parcela; **j)** **risco de evasão ou de combinação** com produtos de origem desconhecida ou de zonas desmatadas; **l)** **preocupações fundamentadas** (art. 31.º); **c) a e)** presença, consulta e **reivindicações fundamentadas de povos indígenas**.

**Alínea n) — certificação privada:** admite "informações fornecidas por **sistemas de certificação ou outros sistemas de verificação por terceiros** (…) **desde que as informações satisfaçam os requisitos previstos no artigo 9.º**".

> ⭐ **Certificação privada (RTRS, ProTerra, Rainforest Alliance, FSC…) é INFORMAÇÃO COMPLEMENTAR — NUNCA substituto do art. 9.º.** O texto é explícito na condicional.

**FLEGT:** madeira com **licença FLEGT válida** é considerada conforme com o **art. 3.º, alínea b)** — **só a alínea b) (legalidade)**. **Não presume ausência de desmatamento.**
**Documentação:** documentar e rever as avaliações **pelo menos anualmente**.

### Art. 11.º — atenuação dos riscos ✅

A menos que o risco seja **nulo ou negligenciável**, o operador adota, **antes da colocação**, medidas adequadas a alcançar risco nulo ou negligenciável: **a)** exigir **informações, dados ou documentos suplementares**; **b)** realizar **inquéritos ou auditorias independentes**; **c)** outras medidas do art. 9.º. Podem envolver "o **apoio ao cumprimento** (…) por parte dos fornecedores (…), **em especial os pequenos agricultores**, através do reforço das capacidades e de investimentos."

**Governança interna:** **responsável pela conformidade a nível de direção** e **auditoria independente** — ambos **para os operadores que não sejam PME**. Decisões documentadas e revistas **pelo menos anualmente**.

### Art. 13.º — diligência devida simplificada ⛔ NÃO ALCANÇA O BRASIL ✅

**Literal:** os operadores "**não são obrigados a cumprir as obrigações previstas nos artigos 10.º e 11.º** se (…) se tiverem certificado de que **TODOS** os produtos de base e derivados foram **produzidos em países ou em partes de países classificados como sendo de BAIXO RISCO**".

**Cláusula antievasão:** a autoridade toma medidas imediatas se houver risco de evasão, "**incluindo nos casos em que os produtos (…) produzidos num país de risco padrão ou alto (…) sejam subsequentemente transformados num país de baixo risco**".

> ⛔ **Não se aplica ao Brasil** — exige que **TODOS** os produtos venham de país de **baixo risco**, e o Brasil é **risco padrão** (§8). **E a cláusula antievasão fecha explicitamente a rota "triangular por país de baixo risco".**

---

## 7. ⭐ GEOLOCALIZAÇÃO — o coração operacional ✅

### Art. 2.º, ponto 28 — a definição

**Literal:** "a localização geográfica de uma parcela de terreno descrita pelas **coordenadas de latitude e longitude** (…) utilizando **pelo menos SEIS dígitos decimais**; a localização geográfica de parcelas de terreno com uma extensão **superior a QUATRO hectares** usadas para a produção dos produtos de base em causa **que não sejam bovinos**, é indicada utilizando **POLÍGONOS**, com pontos de latitude e longitude suficientes para descrever o perímetro de cada parcela."

**A regra em uma linha:** **ponto** (6 casas decimais) **até 4 ha** · **polígono acima de 4 ha** · **bovinos SEMPRE por estabelecimento**, sem limiar de polígono.
*(Redação de base — **não alterada** pelos dois regulamentos alteradores.)*

### Art. 9.º, n.º 1, alínea d) — a obrigação, e as três consequências duríssimas

**Literal:** "A **geolocalização de todas as parcelas de terreno** em que foram produzidos os produtos de base (…), bem como **a data ou período de produção**; se o produto (…) contiver ou tiver sido fabricado com algum dos produtos de base produzidos em **diferentes parcelas de terreno, deve ser indicada a geolocalização de todas** as diferentes parcelas; **qualquer desflorestação ou degradação florestal nas parcelas de terreno em questão impede automaticamente a colocação ou disponibilização no mercado ou a exportação de TODOS os produtos de base em causa e produtos derivados em causa provenientes dessas parcelas de terreno**; para os produtos (…) que contenham ou que tenham sido fabricados com **bovinos**, e para os (…) que tenham sido **alimentados** com os produtos derivados em causa, a geolocalização refere-se a **todos os estabelecimentos onde os bovinos foram mantidos**; para todos os outros produtos (…) a geolocalização refere-se às parcelas de terreno."

**Três consequências, todas literais:**
1. 🚨 **CONTAMINAÇÃO DA PARCELA INTEIRA.** Havendo desmatamento na parcela, **TODOS** os produtos daquela parcela ficam bloqueados — **não só o lote específico**.
2. 🚨 **BOVINOS = TODOS os estabelecimentos onde o animal esteve.** É a base jurídica da exigência de rastrear **fornecedores indiretos** (cria, recria, engorda). O texto não usa a expressão "fornecedor indireto"; diz "**todos os estabelecimentos onde os bovinos foram mantidos**" — o que alcança **a cadeia inteira do animal**.
3. **Mistura de origens exige a lista completa.** Sem geolocalização de **todas** as parcelas, **não há como declarar**.

### «Parcela de terreno» e «Produzido» ✅

- **«Parcela de terreno»** (`▼M2`) — "um terreno **dentro de um único bem imóvel, reconhecido pela legislação do país de produção**, que beneficia de **condições suficientemente homogéneas** que permitam uma avaliação do nível agregado de risco (…)".
- **«Produzido»** — "cultivado, colhido, obtido ou criado em **parcelas de terreno em causa** ou, no caso de **bovinos, em estabelecimentos**".

### Anexo II — a declaração de diligência devida ✅

1. Nome e endereço do operador e, para produtos que entrem ou saiam do mercado, o **número EORI**;
2. **Código do Sistema Harmonizado**, descrição em texto livre, denominação comercial, se for o caso o **nome científico completo**, e a **quantidade**;
3. **País de produção e a geolocalização de todas as parcelas** — para bovinos, **todos os estabelecimentos onde os animais foram mantidos** (nos termos do art. 9.º, n.º 1, alínea d));
4. *(item suprimido pelo Reg. 2025/2650 — o consolidado mostra `▼M2 —————`)*;
5. Declaração-tipo: o operador confirma que "**foi exercida a diligência devida** (…) e que **não foi detetado qualquer risco ou apenas foi detetado um risco negligenciável**";
6. Assinatura, data, nome e função.

---

## 8. 🚩 O BRASIL É RISCO PADRÃO — e a armadilha do art. 4.º-A

### Art. 29.º — as três categorias ✅

**a) «De alto risco»** · **b) «De baixo risco»** — quando há "**garantias suficientes de que os casos de produção** (…) que não cumprem o disposto no artigo 3.º, alínea a), **são excecionais**" · **c) «De risco padrão»** — "países ou partes de países que **não se enquadram na categoria «de alto risco» nem na categoria «de baixo risco»**".

**Critérios principais:** taxa de desflorestação e degradação florestal · taxa de expansão das terras agrícolas · tendências de produção. **Complementares:** existência de leis nacionais e de "**medidas coercivas eficazes** (…) nomeadamente se são aplicadas **sanções suficientemente severas para anular os benefícios** decorrentes da desflorestação"; transparência dos dados; proteção dos direitos dos povos indígenas, comunidades locais e "outros titulares de **direitos consuetudinários de propriedade fundiária**".

### Regulamento de Execução (UE) 2025/1093 — o ato que classifica ✅

De **22/05/2025**, base no art. 29.º, n.º 2. **Regra operativa (literal):** "Os países que apresentam um risco baixo ou um risco alto são os **enumerados no anexo**." · "**Mantém-se o nível padrão para todos os países não enumerados no anexo**." **Considerando (3):** "A todos os países foi atribuído um **nível de risco padrão** aquando da entrada em vigor do Regulamento (UE) 2023/1115."
**Em vigor desde 26/05/2025**, **sem alterações, retificações ou revogação** (verificado na ficha EUR-Lex).

- **ALTO RISCO — a lista inteira (4 países):** **Bielorrússia, Coreia do Norte, Mianmar/Birmânia e Rússia.**
- **BAIXO RISCO** — lista extensa que inclui os Estados-Membros da UE, Estados Unidos, Canadá, China, Índia, Japão, Austrália, Chile, Costa Rica, Guiana, Uruguai, Suriname, entre outros.

> ### 🇧🇷 O BRASIL É **RISCO PADRÃO** — prova por exclusão dupla
>
> O Brasil **não consta** da lista de alto risco (4 países, todos nomeados) **nem** da lista de baixo risco. Pelo **art. 1.º, n.º 2** do Reg. Exec. 2025/1093 — "mantém-se o nível padrão para todos os países não enumerados no anexo" — **o Brasil é risco padrão**.
>
> **Risco padrão NÃO é rótulo negativo.** É o nível **default** atribuído a **todos** os países em 2023, do qual só saem os expressamente listados. Argentina, Indonésia, Malásia e México também não constam de nenhuma lista → também risco padrão. O Brasil está **no mesmo nível de todos os grandes produtores concorrentes**.
>
> **Consequências jurídicas diretas:**
> - Diligência devida **COMPLETA** — arts. 8.º, 9.º, 10.º e 11.º, **sem** o atalho do art. 13.º.
> - **SEM** o regime simplificado do art. 4.º-A.
> - **Geolocalização obrigatória** em ponto/polígono — **não** pode ser substituída por endereço postal.
> - Controlos das autoridades competentes sobre **pelo menos 3%** dos operadores.

### 🚨 Art. 4.º-A — O REGIME SIMPLIFICADO QUE O BRASIL NÃO ALCANÇA ✅ (`▼M2`, artigo NOVO)

O art. 4.º-A dispensa micro/pequenos operadores primários de partes do art. 4.º, permite **declaração simplificada única** (Anexo III) com **identificador de declaração**, e — o ponto mais atraente — no **n.º 5**: "a **geolocalização** a que se refere o artigo 9.º, n.º 1, alínea d), **pode ser substituída pelo ENDEREÇO POSTAL** de todas as parcelas de terreno ou pelo endereço postal do estabelecimento".

**MAS a definição fecha a porta.** **«Micro ou pequeno operador primário» (literal, `▼M2`):** "um operador que seja uma pessoa individual ou uma micro empresa ou pequena empresa, na aceção (…) da **Diretiva 2013/34/UE** (…), independentemente da sua forma jurídica, **ESTABELECIDO NUM PAÍS CLASSIFICADO COMO DE BAIXO RISCO nos termos do artigo 29.º** (…) e que (…) coloca no mercado ou exporta produtos derivados em causa **por si próprio cultivados, colhidos, obtidos ou criados** em parcelas de terreno em causa ou, no caso de bovinos, em estabelecimentos **situados nesse país**".

> ### 🚩 A ARMADILHA CENTRAL DESTA SKILL
>
> O regime simplificado **só existe para operador estabelecido em país de BAIXO RISCO**. **O Brasil é risco padrão.** Logo:
>
> **⛔ NENHUM pequeno produtor brasileiro é «micro ou pequeno operador primário» para efeitos do EUDR, e NENHUM deles pode substituir a geolocalização por endereço postal.**
>
> Uma skill que leia "regime simplificado para pequenos produtores" e aplique ao pequeno cafeicultor de Minas ou ao produtor familiar do Cerrado dá conselho **errado e prejudicial**.

**Anexo III (declaração simplificada)** ✅ `▼M2` — nota de leitura: o verbo é **futuro** ("**exercerá** a diligência devida"), contra o passado do Anexo II ("**foi exercida**"). **O regime simplificado ANTECIPA a declaração; não dispensa a diligência.**

---

## 9. Controlos e sanções ✅

### Art. 16.º — percentuais de verificação por risco

| Classificação do país de produção | Verificações anuais mínimas |
|---|---|
| **Alto risco** | **9%** dos operadores, operadores a jusante não-PME e comerciantes não-PME **e 9% da quantidade** de cada produto |
| **Risco padrão** 🇧🇷 | **3%** dos operadores, operadores a jusante não-PME e comerciantes não-PME |
| **Baixo risco** | **1%** dos operadores |

**Metodologia:** os objetivos são alcançados **separadamente para cada produto de base**, calculados por referência ao **número total de operadores do ano anterior**. As verificações são efetuadas **sem aviso prévio**, exceto quando a notificação for necessária à eficácia.
> **Nota:** só o patamar de **alto risco** tem também percentual sobre a **quantidade**.

### Art. 25.º — sanções

Os **Estados-Membros** estabelecem as regras; as sanções são "**efetivas, proporcionadas e dissuasivas**" e incluem:
- *(`▼M2`)* **Coimas** proporcionais aos danos e ao valor do produto, calculadas de modo a **privar efetivamente os infratores dos benefícios económicos** e, em **infrações reiteradas**, aumentando gradualmente; para **pessoa coletiva**, o montante **máximo corresponde a pelo menos 4% do volume de negócios anual total a nível da União** no exercício anterior à decisão, "**aumentado, se necessário, para ultrapassar o potencial benefício económico**";
- **b) Confisco** dos produtos;
- **d) Exclusão temporária por até 12 meses** dos processos de contratação pública e do acesso ao financiamento público;
- **e) Proibição temporária de colocação/disponibilização/exportação**, em caso de **infração grave ou reiterada**;
- **Proibição do exercício da diligência devida simplificada** do art. 13.º, em caso de infração grave ou reiterada.

🟡 **Alínea c):** a captura devolveu o rótulo sem texto entre marcadores. **A skill NÃO deve enunciar seu conteúdo — deve remeter ao art. 25.º.**

> ⭐ **QUEM É PUNIDO:** as sanções recaem sobre **operadores, operadores a jusante e comerciantes** — entidades sujeitas à jurisdição dos Estados-Membros. **NÃO HÁ SANÇÃO DO EUDR APLICÁVEL AO PRODUTOR BRASILEIRO.** O que ele sofre é **perda de mercado e responsabilidade contratual**, não coima europeia.

---

## 10. ⭐ INTERFACE COM O DIREITO BRASILEIRO — o que a fonte permite dizer

**O regulamento europeu NUNCA menciona CAR, Código Florestal, SICAR, Lei 12.651/2012, ADA, SIGEF ou qualquer instituto brasileiro.** Ele remete, **três vezes**, à legislação do país de produção.

| Âncora ✅ | Remissão |
|---|---|
| **Art. 3.º, alínea b)** | "Terem sido **produzidos em conformidade com a legislação aplicável do país de produção**" |
| **Art. 2.º, «Legislação aplicável do país de produção»** | define o **escopo** dessa legalidade (8 alíneas) |
| **Art. 9.º, n.º 1, alínea h)** | prova "**devidamente conclusiva e verificável**" dessa conformidade, "incluindo qualquer disposição que confira o **direito de utilização da respetiva zona**" |

### As 8 alíneas da «legislação aplicável do país de produção» (literal) ✅

> "as leis aplicáveis no país de produção relativas ao **estatuto jurídico da zona de produção** em termos de:
> **a)** Direitos de **uso do solo**; **b)** **Proteção do ambiente**; **c)** **Normas relativas às florestas**, incluindo gestão florestal e conservação da biodiversidade, quando diretamente relacionadas com a exploração florestal; **d)** Direitos de **terceiros**; **e)** Direitos **laborais**; **f)** **Direitos humanos** protegidos pelo direito internacional; **g)** O princípio do **consentimento livre, prévio e informado**, conforme a **Declaração das Nações Unidas sobre os Direitos dos Povos Indígenas**; **h)** Regulamentação **fiscal, anticorrupção, comercial e aduaneira**."

*(Redação de base — não alterada.)*

### 🟡 O que DECORRE disso (inferência disciplinada, não texto)

- **Qual norma brasileira responde a cada alínea é SUBSUNÇÃO, não citação.** O Código Florestal e o CAR respondem tipicamente às alíneas **a)**, **b)** e **c)**; a **d)** alcança posse, domínio e conflitos fundiários; a **e)** alcança trabalho análogo ao de escravo e a fiscalização do MTE; a **g)** alcança terras indígenas e comunidades tradicionais; a **h)** alcança regularidade fiscal e aduaneira. **É o trabalho jurídico da skill — mas não está escrito no regulamento.**
- **O CAR não é exigido pelo EUDR, e nem sequer é mencionado.** Que ele seja o **instrumento brasileiro mais próximo** da prova de legalidade é **conclusão prática 🟡**, não comando europeu. E há um **descasamento estrutural**: o CAR é **declaratório e autodeclarado**, ao passo que o art. 9.º exige prova **verificável** — logo **o CAR isolado, sem análise/validação, é ponto de partida, não prova suficiente**.
- **A parcela do EUDR não é a unidade do CAR.** «Parcela de terreno» é "terreno **dentro** de um único bem imóvel (…) com condições suficientemente homogéneas" — **pode ser MENOR** que o imóvel rural do CAR (um talhão, uma gleba homogênea). **Não equipare automaticamente.**

### 🚨 O ATRITO MAIS IMPORTANTE ENTRE OS DOIS SISTEMAS

**A data-corte europeia (31/12/2020) NÃO é a data-corte brasileira (22/07/2008).** São regimes **independentes e cumulativos**:

- **Supressão AUTORIZADA pelo órgão ambiental brasileiro DEPOIS de 31/12/2020 é LÍCITA NO BRASIL e NÃO CONFORME no EUDR.**
- **A recíproca também vale:** ausência de desmatamento pós-2020 **não supre** ilegalidade brasileira — a **alínea b) continua exigível** de forma autônoma.

Ver `context/codigo-florestal-12651.md` para o lado brasileiro (área rural consolidada, APP, RL, PRA).

---

## 11. 🔴 O QUE ESTÁ EM MOVIMENTO (agosto/2026)

### Ato delegado C(2026) 4920 — altera o Anexo I e **AINDA NÃO ESTÁ EM VIGOR** 🔴

- **O que é:** regulamento delegado que altera o Reg. 2023/1115 "as regards the list of relevant commodities and relevant products". Base: art. 34.º, n.º 1.
- **Trâmite:** projeto em consulta de 04/05/2026 a 01/06/2026; **adotado em 13/07/2026**; entrada em vigor prevista "no dia seguinte ao da publicação no Jornal Oficial".
- **Estado hoje:** título ainda traz "**(EU) …/...**" — **sem número de JO atribuído**. A Comissão declara que o ato "will now be **sent to the European Parliament and the Council of the EU for scrutiny before entering into force**". O EUR-Lex **continua listando 26/12/2025** como a versão consolidada mais recente.
- **O que muda quando entrar em vigor:**
  - **SAEM:** **couros e peles bovinos**, pneus recauchutados, soja para semeadura, artigos de borracha vulcanizada, correias transportadoras e de transmissão, assentos de aeronaves e veículos.
  - **ENTRAM:** **café solúvel**, certos derivados de óleo de palma, línguas bovinas congeladas.
  - Os produtos **acrescentados** só se sujeitam **a partir de 30/12/2027**.
- **Impacto para o Brasil:** **couro bovino brasileiro sairia do EUDR** (hoje `ex 4101`, `ex 4104`, `ex 4107` estão expressamente no Anexo I) e **café solúvel entraria**. É a diferença entre um curtume estar dentro ou fora do regime.

> ⛔ **A skill trata o Anexo I CONSOLIDADO como vigente e sinaliza o ato delegado como PENDENTE — nunca o contrário.**

### Regulamento de Execução (UE) 2026/1565 — sistema de informação ✅ (JÁ EM VIGOR)

De **13/07/2026**, JO de **14.7.2026**. Altera o **Reg. Exec. (UE) 2024/3084** quanto à apresentação de declarações, declarações simplificadas, disposições de recurso e simplificação do uso do sistema de informação. Aplicação diferida de um dispositivo: "o **artigo 1.º, ponto 2, alínea c) é aplicável a partir de 15 de outubro de 2026**".
> **Não altera o Regulamento 2023/1115** — altera o regulamento técnico do sistema do art. 33.º.
> 🟡 O conteúdo do **Reg. Exec. 2024/3084 não foi aberto**. **A skill não deve descrever o funcionamento operacional do sistema de informação.**

### Art. 34.º — revisões calendarizadas ✅

- **n.º 1-A** (`▼M2`) — "**Até 30 de abril de 2026**, a Comissão procede à **revisão do presente regulamento com vista à sua simplificação**" e apresenta relatório, "acompanhado, se for caso disso, de uma **proposta legislativa**".
- **Revisão geral até 30/06/2030** e, depois, **de cinco em cinco anos** — avaliará, entre outros: alargamento da definição de **degradação florestal**; **o limiar para a utilização obrigatória de polígonos**; alargamento a **outros ecossistemas naturais** (prados, turfeiras, zonas húmidas); inclusão de **outros produtos de base, incluindo o milho**, e a eventual inclusão dos **biocombustíveis (SH 382600)**; o papel das **instituições financeiras**; e o eventual alargamento da **data-limite** do art. 2.º, ponto 13.

🟡 **COM(2026) 191 final** (relatório de simplificação, de 04/05/2026), **documento de orientação** (`C/2025/4524`) e **FAQ** da Comissão — **identificados, NÃO abertos**. São *soft law* (orientação, não norma). **A skill pode referenciá-los como fonte de consulta, nunca citar conteúdo específico.**

---

## 12. ⛔ LISTA DE PROIBIÇÕES DO GUARD

Cada proibição existe porque a fonte primária a contradiz ou não a sustenta.

1. **NÃO** dizer que a aplicação começa em **30/12/2024 ou 30/12/2025** — datas de redações **revogadas**.
2. **NÃO** dizer que houve "um adiamento". Houve **DOIS** (Reg. 2024/3234 e Reg. 2025/2650).
3. **NÃO** dizer que a **data-corte foi adiada** junto com a aplicação. **31/12/2020 é FIXA.**
4. **NÃO** aplicar o **regime simplificado do art. 4.º-A** a produtor brasileiro, **sob nenhuma hipótese**. Corolários igualmente proibidos: dizer que pequeno produtor brasileiro pode **substituir geolocalização por endereço postal**, ou apresentar **declaração simplificada**.
5. **NÃO** aplicar a **diligência devida simplificada do art. 13.º** a produto brasileiro.
6. **NÃO** afirmar que o Brasil é "**alto risco**". Alto risco tem **exatamente quatro países**: Bielorrússia, Coreia do Norte, Mianmar/Birmânia e Rússia.
7. **NÃO** afirmar que "risco padrão" é penalização ou rebaixamento. É o **nível default**.
8. **NÃO** afirmar que o **produtor rural brasileiro tem obrigação legal perante a UE** ou que "pode ser multado pelo EUDR". Ele responde **contratualmente ao comprador** e perde mercado — **não sofre coima europeia**.
9. **NÃO** afirmar que o **CAR satisfaz o EUDR**, nem que "o EUDR exige CAR". O regulamento **não menciona CAR nem o Código Florestal**.
10. **NÃO** equiparar «**parcela de terreno**» (EUDR) a «**imóvel rural**» (CAR/matrícula).
11. **NÃO** afirmar que supressão autorizada pelo órgão ambiental brasileiro **após 31/12/2020** é conforme ao EUDR.
12. **NÃO** afirmar que ausência de desmatamento pós-2020 basta — **a alínea b) permanece exigível**.
13. **NÃO** afirmar que **certificação** (RTRS, ProTerra, Rainforest Alliance, FSC, qualquer outra) **dispensa** diligência devida, geolocalização ou declaração.
14. **NÃO** dizer que **couro bovino está fora**. Hoje `ex 4101`, `ex 4104` e `ex 4107` estão **no Anexo I vigente**.
15. **NÃO** dizer que **café solúvel, derivados de óleo de palma ou línguas bovinas congeladas já estão** no âmbito.
16. **NÃO** afirmar que **milho ou biocombustíveis** estão abrangidos.
17. **NÃO** enunciar o conteúdo do rol de «**degradação florestal**» nem da **alínea c) do art. 25.º** — não capturados integralmente. **Remeter ao artigo.**
18. **NÃO** citar conteúdo do **documento de orientação**, do **FAQ** ou do **COM(2026) 191 final**.
19. **NÃO** descrever o funcionamento operacional do **sistema de informação** (art. 33.º).
20. **NÃO** afirmar data de aplicação para artigos **fora da lista do art. 38.º, n.º 2** (arts. 25.º, 29.º, 33.º). Pode-se dizer que **não constam da lista de diferimento**; a data é inferência.
21. **NÃO** citar o Regulamento (UE) n.º **995/2010 (EUTR)** como vigente — foi **revogado** pelo art. 37.º. Sobrevive apenas como **referência** no art. 38.º, n.º 3.
22. **NÃO** citar a redação de 2023 de nenhum artigo tocado pelo Reg. 2025/2650. **Se a citação não vier do consolidado de 26/12/2025, não vai para a peça.**

---

## 13. 🔄 REGRA DE ATUALIZAÇÃO — três gatilhos obrigam a rechecar o EUR-Lex

1. **Nova versão consolidada** do `32023R1115` posterior a **26/12/2025** — significa que houve nova alteração.
2. **Publicação no JO do ato delegado C(2026) 4920** — muda o **Anexo I** (couro sai, café solúvel entra).
3. **Alteração do Reg. Exec. (UE) 2025/1093** — mudaria a **classificação de risco do Brasil**. Hoje: sem alterações, em vigor desde 26/05/2025.

---

## 14. Fontes primárias

| # | Documento | URL |
|---|---|---|
| 1 | **Reg. (UE) 2023/1115 — consolidado PT, 26/12/2025** (fonte-mestra) | `eur-lex.europa.eu/legal-content/PT/TXT/HTML/?uri=CELEX:02023R1115-20251226` |
| 2 | Ficha, alterações e versões consolidadas | `eur-lex.europa.eu/legal-content/PT/ALL/?uri=CELEX%3A32023R1115` |
| 3 | **Reg. (UE) 2025/2650** — 2.º adiamento + simplificação | `eur-lex.europa.eu/legal-content/PT/TXT/?uri=CELEX:32025R2650` |
| 4 | **Reg. Exec. (UE) 2025/1093** — classificação por risco | `eur-lex.europa.eu/legal-content/PT/TXT/HTML/?uri=CELEX:32025R1093` |
| 5 | **Reg. Exec. (UE) 2026/1565** — sistema de informação | `eur-lex.europa.eu/legal-content/PT/TXT/HTML/?uri=CELEX:32026R1565` |
| 6 | 🔴 Ato delegado **C(2026) 4920** — Anexo I (adotado, em escrutínio) | `eur-lex.europa.eu/legal-content/EN/TXT/?uri=intcom:C%282026%294920` |
| 7 | Comissão Europeia — comunicação de 13/07/2026 | `environment.ec.europa.eu/news/commission-updates-product-scope-and-tools-support-eudr-2026-07-13_en` |

---

## 15. Onde continuar

| Tema | Anexo |
|---|---|
| Código Florestal, CAR, PRA, APP/RL — o lado brasileiro da alínea b) | `context/codigo-florestal-12651.md` |
| Embargos, autos de infração e prova de legalidade ambiental | `context/ambiental-administrativo.md` |
| Matrícula, CCIR, georreferenciamento (a geometria da parcela) | `context/registral-terras-e-estrangeiros.md` |
| Mapa das camadas e regra de leitura | `context/metodologia-agraria.md` |
