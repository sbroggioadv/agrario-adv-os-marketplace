---
name: rj-produtor-defesa-do-credor
description: "Lado credor na recuperacao judicial do produtor rural: impugnacao ao processamento por ausencia dos requisitos do art. 48, ataque a intempestividade da escrituracao exigida (LCDPR, DIRPF e balanco na pessoa fisica; ECF na juridica) e pedido de constatacao previa e de monitoramento com base no Provimento CNJ 216/2026 e no ACT CNJ-MAPA 013/2026, que autoriza satelite e georreferenciamento. Use quando o operador disser sou o credor na RJ, impugnar o processamento, o produtor nao tem os documentos, pedir constatacao previa, o produtor comprou terra e agora pediu RJ, defender o banco na recuperacao."
---

# RJ-PRODUTOR-DEFESA-DO-CREDOR — impugnar o processamento e pedir constatacao

> Camada 3, lado **credor** (banco, trading, cerealista, fornecedor de insumos). Espelho de `rj-produtor-rural-inicial`. A janela util e **curta**: o ataque mais eficaz e ao **processamento**, antes do deferimento consolidar o *stay*.

## Quando ativa / trilha
Um produtor rural pediu RJ e o cliente e credor. **Primeiro passo, sempre:** rodar `rj-sujeicao-de-creditos-agro` — se o credito **nao se sujeita**, a estrategia nao e impugnar o processamento, e afirmar a extraconcursalidade e **prosseguir na cobranca**. Impugnar o que nao te atinge e gastar prazo.

## Anexos obrigatorios (context/)
- `context/rj-produtor-rural.md` (**§1 art. 48 e paragrafos** · **§3 Prov. CNJ 216/2026** · §4 Tema 1.145 · §6 armadilhas — **grep o artigo e leia a faixa**).
- `context/jurisprudencia-agraria.md` (**Tema Repetitivo 1.145/STJ** — o que ele **impede** de alegar).
- `context/lei-do-agro-e-cpr.md` (art. 11 da L8929 · art. 10 da L13986) · `context/registral-terras-e-estrangeiros.md` (registro do imovel em nome da recuperanda).

## Base legal ancorada ✅

### O que se ataca no art. 48
- **Caput e incisos I a IV**, cumulativos: falencia nao extinta (I) · **concessao de RJ ha menos de 5 anos** (II) · **concessao com base no plano especial ha menos de 5 anos** (III) · condenacao por crime da Lei 11.101/05 (IV). ⚠️ **O inciso III e de 5 anos** (LC 147/2014) — alegar "8 anos" e citar redacao revogada e entregar o argumento.
- **O bienio de exercicio da atividade** — mas leia antes o Tema 1.145 abaixo, porque a tese obvia esta fechada.

### ⭐ O ataque que efetivamente funciona: a PROVA do bienio
E aqui que o pedido do produtor mais frequentemente falha, porque a lei exige **documento e tempestividade**, nao alegacao:
- **§2º — pessoa juridica:** comprovacao pela **ECF**, ou obrigacao legal que a substitua, **entregue tempestivamente**. ⚠️ "DIPJ" e redacao revogada.
- ⭐ **§3º — pessoa fisica:** **LCDPR + DIRPF + balanco patrimonial**, **CUMULATIVOS**, "**todos entregues tempestivamente**". **Faltando um, ou entregue fora do prazo, o requisito nao se comprova.** E o vetor de impugnacao mais direto — e o mais verificavel documentalmente.
- **§5º:** as informacoes contabeis seguem o padrao vigente, em **regime de competencia**, com **balanco elaborado por contador habilitado**. Balanco sem responsavel tecnico habilitado e peca imprestavel.
- **§4º — antecipe a resposta:** no periodo em que **nao era exigivel** o LCDPR, admite-se o **livro-caixa** usado para a DIRPF. Nao adianta impugnar so a ausencia do LCDPR sem verificar se a exigibilidade ja existia no periodo.
- 🚨 **Nao exija DAP.** O art. 48 **nao a menciona em nenhum paragrafo** — DAP/CAF e do **Pronaf**. Impugnacao fundada na falta de DAP e erro de subsuncao e desqualifica a peca.

### ⛔ O que o credor NAO pode alegar — Tema Repetitivo 1.145/STJ
**Tese (verbatim):** ao produtor que exerca a atividade de forma empresarial **ha mais de dois anos** e facultado requerer RJ, "**desde que esteja inscrito na Junta Comercial no momento em que formalizar o pedido recuperacional, independentemente do tempo de seu registro**". **2ª Secao**, Rel. Min. **Luis Felipe Salomao**, **julgado em 22/06/2022**, tese firmada e transitada.
🚨 **A tese de que "o registro na Junta precisa ter dois anos" esta MORTA** — o bienio e de **exercicio da atividade**, e o tempo anterior ao registro **conta**. Sustenta-la e perder credibilidade num precedente **qualificado**. O que **resta** verificar e a inscricao **no momento do pedido** — essa sim e condicao de procedibilidade.

### ⭐ A porta de 2026: constatacao previa e monitoramento 🔴
O **Provimento CNJ 216, de 09/03/2026** transformou a RJ rural em **dossie probatorio territorial**, e deu ao credor dois instrumentos:
- **constatacao previa** — verificacao *in loco* antes do deferimento do processamento;
- **monitoramento continuo** — acompanhamento ao longo do processo.

Some-se o **ACT CNJ-MAPA 013/2026** (26/03/2026), que autoriza o uso da **Infraestrutura VMG** — **imagens de satelite, dados climaticos e georreferenciamento** — **nos dois momentos**. Na pratica: o credor pode pedir constatacao instruida com **prova territorial objetiva**, e nao apenas com alegacao de insuficiencia documental.

**O que a constatacao expoe, e o Provimento exige do devedor:** laudo das **condicoes operacionais** (maquinario, instalacoes, pastos, granjas, silos) · **declaracao das garantias sobre safras presentes e futuras e sobre semoventes** · **perspectiva de colheita** no ciclo vigente · e o esclarecimento, pelo perito, sobre se a propriedade esta **formalmente registrada em nome da recuperanda**. ⭐ **Esse ultimo ponto e o de maior rendimento**: area explorada mas **nao registrada** em nome da recuperanda enfraquece a base patrimonial do plano — e frequentemente aparece em estrutura familiar de posse informal ou de imovel em nome de terceiro. Complementa o **Provimento CNJ 231/2026** (administradores judiciais).

### Indicios de blindagem — art. 49, §9º
**Nao se enquadra** nos creditos do caput a divida **constituida nos 3 anos anteriores ao pedido** para **aquisicao de propriedades rurais**, **bem como as respectivas garantias**. Compra recente de terra financiada **fica fora do concurso**: levante a cadeia de aquisicoes do trienio na matricula. Alem de manter o credito exigivel, e **indicio de reestruturacao patrimonial as vesperas do pedido** — argumento relevante no pedido de constatacao.

## Passo a passo / o que produzir
1. **Classificar o proprio credito** com `rj-sujeicao-de-creditos-agro` — nao se sujeitando (CPR fisica, barter, alienacao fiduciaria, patrimonio afetado, §9º), a rota e **afirmar extraconcursalidade e prosseguir**, nao impugnar.
2. **Auditar a instrucao do pedido:** para PF, os **tres** documentos do §3º e a **tempestividade de cada um**; para PJ, a **ECF tempestiva**. Testar o **§4º** antes de alegar ausencia de LCDPR.
3. **Conferir o balanco** — contador habilitado, regime de competencia (§5º).
4. **Rodar os incisos I a IV** do caput, com o **III em 5 anos**.
5. **Descartar a tese morta** do tempo de registro (Tema 1.145) e verificar apenas a **inscricao no momento do pedido**.
6. **Levantar a matricula e o trienio de aquisicoes** (§9º) e o registro do imovel em nome da recuperanda.
7. **Pedir constatacao previa e monitoramento** (Prov. 216/2026), requerendo expressamente o uso da **Infraestrutura VMG** do ACT 013/2026 — satelite, clima e georreferenciamento.
8. **Testar o teto do plano especial:** valor da causa acima de **R$ 4,8 milhoes** afasta o art. 70-A.
9. **Entregar:** impugnacao ao processamento (ou objecao) + pedido de constatacao previa instruido + quadro de sujeicao do proprio credito.

## Postura honesta
- ⛔ **Nao sustente que o registro na Junta precisa ser antigo.** O **Tema 1.145** e precedente **qualificado** e diz o contrario. Insistir custa credibilidade no resto da peca.
- 🟡 **A numeracao dos artigos do Prov. CNJ 216/2026 nao esta confirmada**: o **conteudo das exigencias e seguro**, a **numeracao nao**. **Nao cite numero de artigo do Provimento em peca** sem confirmar no portal de atos do CNJ. O mesmo vale para o **Prov. 231/2026**.
- ⚠️ **Impugnacao nao e indeferimento.** A ausencia de um documento pode ser sanada, e o **§4º** e valvula legitima do devedor. Dimensione a expectativa do cliente: o ganho pratico costuma ser **tempo, informacao e posicao negocial**, nao a extincao do pedido.
- ⚠️ **A trava dos bens de capital essenciais** (art. 49, §3º, parte final, e art. 6º, §7º-A) limita a retomada mesmo do credor extraconcursal durante o *stay*. Nao prometa retirada imediata de maquinario.
- 🟡 **O teor dos arts. 14 e 21 da Lei 4.829/65** (recursos controlados, art. 49, §§7º-8º) **nao esta confirmado** — nao afirme o conteudo deles.
- 🟡 **Nao houve varredura integral da Lei 11.101/05** (consultados os arts. 6º, 48, 48-A, 49, 50, 70-A, 71 e 72) — nao afirme ausencia de alteracao fora desses artigos.

## Cross-link e fechamento
Sujeicao do credito -> `rj-sujeicao-de-creditos-agro`. Lado devedor -> `rj-produtor-rural-inicial`. Cobranca fora do concurso -> `execucao-de-cpr-e-cedula-rural`. Garantias -> `garantias-do-credito-rural` · `patrimonio-rural-em-afetacao-e-cir`. Matricula e cadeia dominial -> `due-diligence-de-terras-rurais`. Cruzamento -> `protocolo-p4-agrario`.

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
