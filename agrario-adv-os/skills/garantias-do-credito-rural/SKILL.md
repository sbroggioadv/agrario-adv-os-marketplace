---
name: garantias-do-credito-rural
description: "Estrutura e ataca as garantias do credito rural — hipoteca, penhor e alienacao fiduciaria cedulares da Lei 8.929/94 — e trabalha a execucao extrajudicial da hipoteca do art. 9º da Lei 14.711/2023, com purgacao em 15 dias, leilao em 60 e piso de metade da avaliacao no segundo. Carrega a impenhorabilidade da pequena propriedade oponivel a alienacao fiduciaria pelo REsp 2.233.886-RS, que nao se confunde com o Tema 961/STF. Use quando o operador disser garantia da CPR, penhor agricola, alienacao fiduciaria de safra, hipoteca da fazenda, vao levar a fazenda a leilao, consolidacao extrajudicial, executaram a hipoteca sem processo."
---

> **🖱️ Escolhas = botoes:** em pergunta de **lista fechada** (especie de garantia, lado, fase da excussao) use **AskUserQuestion** — botoes clicaveis, max. 4 por pergunta.

# GARANTIAS-DO-CREDITO-RURAL — penhor, AF, hipoteca e o caminho ate o leilao

> Camada 3. Estrutura a garantia (lado credor) e ataca a excussao (lado produtor). E aqui que o **Marco das Garantias** encurtou o caminho ate o leilao da fazenda.

## Quando ativa / trilha
Ao constituir garantia num titulo rural, ou quando a excussao ja comecou — intimacao para purgar, averbacao de leilao, consolidacao extrajudicial. Apoia-se na `base-credito-rural-e-lei-do-agro`.

**Diferenca das vizinhas:** o **patrimonio rural em afetacao e a CIR** tem skill propria; a **penhora judicial** de bens do produtor entra por `embargos-a-execucao-de-cpr`.

## Anexos obrigatorios (context/)
- `context/lei-do-agro-e-cpr.md` (**arts. 5º a 8º, 12 e 18 da Lei 8.929/94** — **grep o artigo e leia a faixa**).
- `context/registral-terras-e-estrangeiros.md` (**Lei 14.711/2023, art. 9º** — execucao extrajudicial da hipoteca; **art. 19, I vetado**).
- `context/jurisprudencia-agraria.md` (**REsp 2.233.886-RS** · **Tema 961/STF** · **Tema 1.234/STJ** — grep o numero e leia a faixa).
- `context/cpc-agrario.md` (**§12 impenhorabilidade, arts. 832-834**) · `context/lei-8629-93-e-cf-184-191.md` (**art. 4º**, modulos fiscais).

## Base legal ancorada ✅

### 🚨 O regime mudou: art. 5º e CLAUSULA ABERTA
A CPR admite **quaisquer dos tipos de garantia previstos na legislacao** (red. Lei 13.986/2020). **Os incisos I, II e III — hipoteca, penhor e alienacao fiduciaria — estao REVOGADOS desde 2020.** Cita-los e citar dispositivo morto. **§2º** (2022): as garantias cedulares podem ser constituidas por **instrumento publico ou particular, independentemente do valor**.

### As tres garantias cedulares — arts. 6º a 8º
- **Art. 6º — hipoteca cedular**, sobre imoveis **rurais e urbanos**.
- **Art. 7º — penhor cedular**, sobre bens suscetiveis de penhor rural e mercantil. **§1º:** salvo titulos de credito, os bens apenhados **continuam na posse imediata do emitente ou do terceiro garantidor, como fiel depositario**. **§2º:** no penhor prestado por terceiro, o emitente responde **solidariamente** pela guarda.
- **Art. 8º — alienacao fiduciaria.** A **nao identificacao** dos bens **nao retira a eficacia** da garantia, que pode incidir sobre outros do mesmo genero, qualidade e quantidade. **§1º:** alcanca bens **presentes ou futuros, fungiveis ou infungiveis, consumiveis ou nao**. ⭐ **§2º: o beneficiamento ou a transformacao NAO extinguem o vinculo real**, que se transfere automaticamente aos produtos e subprodutos resultantes — a soja vira farelo e a garantia acompanha. **§3º:** busca e apreensao pelos arts. 3º e seguintes do **DL 911/1969**.

### Registro e oponibilidade — art. 12
As garantias reais imobiliarias vao ao **cartorio de registro de imoveis** da localizacao dos bens (§1º), e a **AF de produtos agropecuarios** tambem (§4º). **§2º:** a validade da **CPR** dispensa cartorio, mas as **garantias reais**, para valer **contra terceiros**, sao averbadas em **3 dias uteis** da apresentacao. **Art. 18:** os bens vinculados **nao sao penhorados ou sequestrados por outras dividas** do emitente ou do garantidor.

### 🔴 Lei 14.711/2023, art. 9º — a hipoteca passa a executar EXTRAJUDICIALMENTE
O Marco das Garantias **nao alterou** a Lei 8.929/94 nem o DL 167/67 — importa no agro por esta porta. Os creditos garantidos por hipoteca podem ser **executados extrajudicialmente**:
- **§1º** — devedor e terceiro hipotecante sao **intimados pessoalmente pelo oficial do registro de imoveis** da situacao do imovel para **purgar a mora em 15 dias**, observado o art. 26 da Lei 9.514/97 no que couber.
- **§2º** — nao purgada, comeca a **excussao por leilao publico**, **previamente averbada na matricula**, nos **15 dias** seguintes ao termino do prazo de purgacao.
- **§3º** — **leilao em ate 60 dias** da averbacao, admitido o **eletronico**.
- **§5º** — se o lance do **primeiro leilao** nao alcancar o valor do imovel fixado no contrato **ou** o valor de avaliacao do orgao competente para o **ITBI**, **o que for maior**, o **segundo leilao** ocorre nos **15 dias seguintes**.
- **§6º** — no segundo, aceita-se lance **igual ou superior ao valor integral da divida** e despesas; nao havendo, o credor **pode, a seu exclusivo criterio**, aceitar lance de **pelo menos metade do valor de avaliacao**.
- **§7º** — antes da alienacao, o devedor ou o garantidor tem **direito de remir a execucao** pagando a totalidade da divida com as despesas do procedimento e dos leiloes.
- ⚠️ **Art. 19, I foi VETADO** ⇒ **vigencia na publicacao, sem vacatio escalonada**. Afirmar prazo de entrada em vigor escalonado e erro.
**Pontos de controle da defesa:** intimacao pessoal valida · contagem 15 / 15 / 60 / 15 · averbacao previa na matricula · o **maior** entre valor contratual e avaliacao do ITBI no 1º leilao · o piso da metade **so** no 2º leilao e **a criterio do credor**.

### ⭐ A impenhorabilidade e oponivel a garantia — e qual precedente usar
**REsp 2.233.886-RS** (3ª Turma, Nancy Andrighi, **09/12/2025**, **Info 875**): a **impenhorabilidade da pequena propriedade rural e oponivel a alienacao fiduciaria e a consolidacao extrajudicial** da propriedade. Precedente **de Turma, recente**.
🚨 **NAO atribua essa tese ao Tema 961/STF** — o 961 decide que e impenhoravel a pequena propriedade familiar ainda que composta de **mais de um terreno**, desde que **continuos** e com area total inferior a **4 modulos fiscais** (ARE 1.038.507). Trocar os dois e erro catalogado do plugin, e o `validador-agrario` trava.
**Limite:** o **CPC 833, §1º** exclui a protecao na **divida relativa ao proprio bem, inclusive a de aquisicao** — garantia real **sem** divida de aquisicao e que cai no REsp 2.233.886. E o **Tema 1.234/STJ** poe no **EXECUTADO** o onus de provar a exploracao familiar: a defesa nasce instruida com CCIR/CAR e modulos fiscais.

## Passo a passo / o que produzir
1. **Mapear a garantia (botoes):** hipoteca · penhor cedular · AF de produtos · AF de imovel · afetacao/CIR (esta ultima sai para a skill propria).
2. **Conferir constituicao e registro** — instrumento (art. 5º, §2º), averbacao no RI e os **3 dias uteis** do art. 12, §2º.
3. **Lado credor:** dimensionar a garantia ao credito, prever o §2º do art. 8º (beneficiamento) e evitar dupla vinculacao da mesma safra.
4. **Lado produtor, com excussao em curso:** reconstituir a **linha do tempo** (intimacao, purgacao, averbacao, 1º e 2º leilao) e conferir cada prazo e cada piso de lance; testar a **remicao** do §7º.
5. **Testar a impenhorabilidade** — modulos fiscais (Lei 8.629/93, art. 4º) · exploracao familiar · **destinacao do credito** (§1º do art. 833) · e so entao o REsp 2.233.886-RS.
6. **Entregar** o quadro de garantias ou a impugnacao a excussao, com a linha do tempo e o vicio apontado.

## Postura honesta
- ⚠️ **O REsp 2.233.886-RS e precedente de Turma**, nao repetitivo — nao prometa resultado como se fosse tese vinculante.
- ⚠️ **A impenhorabilidade nao alcanca frutos e rendimentos** (CPC 834): a **safra** e a **renda do arrendamento** sao penhoraveis a falta de outros bens. Terra protegida nao e safra protegida.
- 🟡 **Sem numero confirmado** (lista integral no `validador-agrario`): **conflito de garantias sobre a mesma safra** (penhor x CPR x AF) · **boa-fe do terceiro adquirente de safra gravada** · **eficacia do penhor rural sem registro** perante terceiros (CC 1.438; DL 167/67 art. 30). Bloco inteiro sem ancora — nao improvise.
- 🚫 **Prescricao da CPR e da cedula rural: GAP.** Nenhum prazo afirmado por nenhuma fonte confirmada.
- ⚠️ **FGS pos-14.421/2022:** sem percentuais, sem cota terciaria, credor **nao** e integrante — "4% + 4% + 2%" e direito revogado.

## Cross-link e fechamento
Titulos -> `cpr-emissao-e-formalizacao` · `cedulas-de-credito-rural`. Afetacao e CIR -> `patrimonio-rural-em-afetacao-e-cir`. Execucao judicial -> `execucao-de-cpr-e-cedula-rural`; defesa -> `embargos-a-execucao-de-cpr`. Revisao de garantias na janela da MP -> `renegociacao-mp-1376` (art. 5º, p.u., **os dois incisos**). Sujeicao a RJ -> `rj-sujeicao-de-creditos-agro`. Rito do leilao e arrematacao -> `leiloes-os` (soft, nos dois sentidos).

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
