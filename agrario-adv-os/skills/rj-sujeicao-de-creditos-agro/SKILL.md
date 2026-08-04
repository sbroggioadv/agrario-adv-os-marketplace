---
name: rj-sujeicao-de-creditos-agro
description: "Define quem entra e quem fica de fora da recuperacao judicial do produtor rural. Carrega o duplo filtro do art. 49, §6º (credito exclusivamente da atividade rural E discriminado na escrituracao), a excecao da excecao do §8º (recursos controlados voltam se nao renegociados antes do pedido), a trava do §9º para divida de aquisicao de terra, a extraconcursalidade da CPR fisica e do barter e o racha declarado sobre a cedula rural financeira. Use quando o operador disser meu credito entra na RJ, esse credito e extraconcursal, habilitar credito, impugnar relacao de credores, barter na recuperacao, CPR na RJ."
---

# RJ-SUJEICAO-DE-CREDITOS-AGRO — quem entra e quem fica de fora

> Camada 3. A pergunta que decide **o tamanho do passivo concursal** — e, com ele, a viabilidade da RJ inteira. Deve ser respondida **antes** da inicial, nao depois da relacao de credores.

## Quando ativa / trilha
Ha RJ pedida, deferida ou em estudo, e e preciso classificar cada credito. Serve aos **dois lados**: o produtor mapeia o passivo real; o credor decide se **habilita** ou se **afirma extraconcursalidade** e prossegue na cobranca.

**Diferenca das vizinhas:** `rj-produtor-rural-inicial` monta a inicial; `rj-produtor-defesa-do-credor` ataca o **processamento**. Aqui se classifica **credito a credito**.

## Anexos obrigatorios (context/)
- `context/rj-produtor-rural.md` (**§2 sujeicao de creditos — art. 49, §§3º, 4º, 6º, 7º, 8º e 9º** · §4 jurisprudencia · §5 lista 🟡 — **grep o paragrafo e leia a faixa**).
- `context/lei-do-agro-e-cpr.md` (**art. 11 da L8929** — CPR fisica e barter · **art. 10, §4º da L13986** — patrimonio afetado) · `context/jurisprudencia-agraria.md` (**REsp 2.178.558-MT** · §10 rachas — grep o numero).

## Base legal ancorada ✅

### ⭐ O DUPLO FILTRO do produtor rural — art. 49, §6º
Nas hipoteses dos **§§2º e 3º do art. 48**, "**somente estarao sujeitos a recuperacao judicial os creditos que decorram EXCLUSIVAMENTE da atividade rural E estejam DISCRIMINADOS nos documentos** a que se referem os citados paragrafos, ainda que nao vencidos" *(incluido pela Lei 14.112/2020)*.

**Sao dois requisitos cumulativos:** (a) decorrer **exclusivamente** da atividade rural **e** (b) estar **discriminado** na **ECF** (PJ) ou no **LCDPR/DIRPF/balanco** (PF). 🚨 **Credito rural real mas nao escriturado fica FORA da RJ.** Isso inverte o onus documental para cima do produtor e e a **primeira linha de ataque do credor**. "Todo credito rural entra na RJ" e falso.

### ⭐ A EXCECAO DA EXCECAO — art. 49, §§7º e 8º
- **§7º:** **nao se sujeitam** a RJ os **recursos controlados** abrangidos pelos **arts. 14 e 21 da Lei 4.829/65**.
- ⭐ **§8º:** **estarao sujeitos** a RJ os recursos do §7º **que NAO tenham sido objeto de renegociacao entre o devedor e a instituicao financeira ANTES do pedido**, na forma de ato do Poder Executivo.

**E o dispositivo mais esquecido do bloco.** Recurso controlado **nao renegociado antes do pedido volta para dentro da RJ** — argumento forte do produtor, a testar em **toda** triagem: houve renegociacao formal, e quando, em relacao a data do pedido?

### A trava anti-abuso — art. 49, §9º
**Nao se enquadra** nos creditos do caput a divida **constituida nos 3 ultimos anos anteriores ao pedido**, contraida com a finalidade de **aquisicao de propriedades rurais**, **bem como as respectivas garantias**. Impede reestruturar compra recente de terra, e **alcanca tambem as garantias**. Para o credor, e indicio de blindagem; para o produtor, e passivo que continua exigivel fora do concurso.

### As exclusoes gerais que tambem valem no rural — art. 49, §3º
**§3º:** nao se submetem a RJ os creditos de **proprietario fiduciario** de bens moveis ou imoveis, **arrendador mercantil**, **promitente vendedor de imovel** com clausula de irrevogabilidade e **proprietario em venda com reserva de dominio** — prevalecendo os direitos de propriedade e as condicoes contratuais. **Trava:** durante a suspensao do art. 6º, §4º, **nao se permite a venda ou a retirada do estabelecimento dos BENS DE CAPITAL ESSENCIAIS**.
⭐ **Ponte com o rural:** a **alienacao fiduciaria** e a garantia dominante no agro (art. 8º da Lei 8.929/94) — o §3º e, na pratica, **o principal esvaziador do passivo concursal do produtor**. O contraponto e a trava dos **bens de capital essenciais**, reforcada pelo **art. 6º, §7º-A**, que admite ao juizo da RJ **suspender atos de constricao** sobre esses bens durante o *stay* (cooperacao, CPC art. 69).

### Os extraconcursais de regime proprio
- ⭐ **Lei 8.929/94, art. 11** (red. **Lei 14.112/2020** — **nao** a Lei do Agro): **nao se sujeitam** a RJ os creditos e garantias cedulares da **CPR com liquidacao fisica** com **antecipacao parcial ou integral do preco**, ou representativa de **troca por insumos (barter)**, com direito a **restituicao** dos bens, "**salvo motivo de caso fortuito ou forca maior**". 🔴 A redacao **anterior dizia o oposto**: hoje o caso fortuito e a **unica excecao** que traz o credito de volta a RJ.
- **Lei 13.986/2020, art. 10, §4º:** o **patrimonio rural em afetacao** vinculado a CIR ou CPR **nao e atingido** por falencia, insolvencia civil ou RJ, e **nao integra a massa concursal**. ⚠️ Com os dois limites do mesmo artigo: **§3º, II** protege **so na medida da garantia**, e **§5º** nao alcanca **trabalhista, previdenciario e fiscal**.

### ⭐ REsp 2.178.558-MT — a conversao nao muda a natureza
**Destaque (verbatim):** "O credito decorrente de cedula de produto rural representativa de operacao *Barter* **nao se submete aos efeitos da recuperacao judicial** mesmo quando ha **conversao da execucao para entrega de coisa incerta em execucao por quantia certa**." **3ª Turma**, Rel. Min. **Ricardo Villas Boas Cueva**, unanime, **julgado em 09/09/2025**, **Info 867**.
**Ratio (verbatim):** "o **art. 11 da Lei n. 8.929/1994 constitui excecao expressa a regra geral do art. 49 da LREF**". **Anti-abuso (verbatim):** admitir a conversao como renuncia "seria deixar ao alvedrio exclusivo do devedor a submissao ou nao do credito", bastando **dar outra destinacao aos graos**.
⚠️ **E UM caso, nao dois.** "REsp 2.178.558/MT" e "STJ 3ª Turma 07/10/2025 (barter)" sao **o mesmo julgado** — **07/10/2025 e a data da NOTICIA** do STJ. Uma unica ancora.

### ⚔️ RACHA DECLARADO
De um lado, **CPR fisica e barter extraconcursais** (art. 11 + REsp 2.178.558-MT). De outro, 🟡 **pendente / pode mudar**: ha corrente que reconhece natureza **CONCURSAL da cedula rural financeira**, e o proprio **ACT CNJ-MAPA 013/2026** registra o racha. E o **REsp 2.178.558 e precedente de Turma, NAO repetitivo**.
**Regra do plugin: declare o racha; nao venda pacificacao que nao existe.** A peca ganha ao enfrentar o argumento contrario, e o cliente decide com o risco a vista.

## Passo a passo / o que produzir
1. **Listar cada credito** com: origem · titulo (CPR fisica, CPR financeira, cedula do DL 167/67, CIR, contrato bancario) · garantia · fonte de recursos · datas.
2. **Rodar o duplo filtro do §6º:** decorre **exclusivamente** da atividade rural? Esta **discriminado** na ECF ou no LCDPR/DIRPF/balanco? Faltando um dos dois, **fica fora**.
3. **Testar o §8º** em todo recurso controlado: **houve renegociacao antes do pedido?** Nao havendo, **volta para a RJ**.
4. **Aplicar a trava do §9º:** divida de **aquisicao de terra** nos 3 anos anteriores, com as garantias, **fica fora**.
5. **Separar os de regime proprio:** CPR fisica com antecipacao e **barter** (art. 11), **patrimonio afetado** (art. 10, §4º), e as exclusoes do **§3º** — com a trava dos **bens de capital essenciais**.
6. **Classificar e quantificar:** concursal x extraconcursal, com o **valor de cada bloco**. E esse numero que diz se a RJ e viavel.
7. **Entregar:** quadro de sujeicao credito a credito, com ancora e selo; e, conforme o lado, **peticao de exclusao ou de inclusao de credito** / **impugnacao a relacao de credores**, com o racha declarado no corpo.

## Postura honesta
- 🟡 **A materia nao esta pacificada (pendente / pode mudar):** REsp 2.178.558 e **de Turma**; ha corrente em sentido contrario (cedula rural financeira concursal); o **ACT 013/2026** registra o racha. Nao prometa resultado.
- 🟡 **O teor dos arts. 14 e 21 da Lei 4.829/65** (recursos controlados) **nao esta confirmado** — nao afirme o conteudo deles ao aplicar o §7º/§8º.
- 🟡 **Nao foi localizado repetitivo da 2ª Secao sobre sujeicao de CPR com garantia** — nao afirme existencia nem inexistencia. A materia segue decidida **em Turma**.
- ⚠️ **Art. 6º, §13 da LREF nao trata do produtor rural** — trata de **sociedades cooperativas**. Citacao errada frequente.
- ⚠️ **A blindagem do patrimonio afetado tem dois furos** (art. 10, §§3º, II e 5º) — nao a apresente como absoluta.

## Cross-link e fechamento
Inicial -> `rj-produtor-rural-inicial`. Lado credor no processamento -> `rj-produtor-defesa-do-credor`. Titulos e garantias -> `cpr-emissao-e-formalizacao` · `garantias-do-credito-rural` · `patrimonio-rural-em-afetacao-e-cir`. Barter -> `contrato-barter`. Cobranca fora do concurso -> `execucao-de-cpr-e-cedula-rural`. Cruzamento contratual x concursal -> `protocolo-p4-agrario`.

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
