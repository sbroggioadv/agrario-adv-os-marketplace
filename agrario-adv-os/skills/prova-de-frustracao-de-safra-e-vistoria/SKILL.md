---
name: prova-de-frustracao-de-safra-e-vistoria
description: "Producao antecipada de prova (CPC 381-383) para documentar perda de safra antes que a lavoura desapareca, e o dossie de frustracao que alimenta prorrogacao de divida, MP 1.376 e recuperacao judicial. Traz o fundamento literal do inciso I, o arrolamento apenas DOCUMENTAL do §1º, a competencia do juizo estadual quando nao houver vara federal na localidade (§4º), e os dois limites que precisam ser ditos ao cliente: o juiz nao se pronuncia sobre a ocorrencia do fato nem sobre suas consequencias (382 §2º) e nao cabe defesa nem recurso salvo indeferimento total (§4º). Carrega a responsabilidade SOLIDARIA do profissional que assina o laudo. Use quando o operador disser perdi a safra, preciso provar a quebra, seca acabou com a lavoura, quero uma vistoria judicial, o banco pede laudo, como comprovo a perda pra renegociar, preciso de pericia antes de entrar com acao."
---

# PROVA-DE-FRUSTRACAO-DE-SAFRA-E-VISTORIA

> Camada 7, mas **serve o plugin inteiro**. E a unica skill cuja entrega e **prova**, nao pedido. Lavoura perdida **desaparece**: chuva, praga, replantio ou a propria colheita apagam o fato em semanas. Documentar cedo e a diferenca entre um dossie que sustenta tres pedidos e uma alegacao sem lastro.

## Quando ativa / trilha
Dispara **antes** das skills que consomem o dossie — `prorrogacao-de-divida-rural`, `renegociacao-mp-1376`, `rj-produtor-rural-inicial` e `defesa-na-vistoria-e-laudo-de-produtividade`. Roda logo apos a `triagem-agraria` sempre que houver **evento de perda em curso ou recente**, e antes de qualquer inicial que dependa da quebra.

**Fronteiras:** enquadramento nos dois regimes da MP 1.376 -> `renegociacao-mp-1376` · requisitos da Sumula 298 -> `prorrogacao-de-divida-rural` · dossie territorial da RJ -> `rj-produtor-rural-inicial` · laudo de **GUT/GEE** contra o INCRA (outra prova, outra lei) -> `defesa-na-vistoria-e-laudo-de-produtividade` · rito e competencia -> `base-processual-agraria`.

## Anexos obrigatorios (context/)
- **`context/cpc-agrario.md`** (§6 **arts. 381, 382 e 383** · §5 **art. 301** arrolamento e **arts. 305-310** cautelar antecedente · §2.1 competencia — **grep o artigo e leia a faixa**).
- `context/mp-1376-2026.md` (**art. 1º, §1º e §7º** laudo de profissional habilitado · **§9 art. 9º, §1º** responsabilidade solidaria — **grep o artigo e leia a faixa**).
- `context/rj-produtor-rural.md` (o dossie do **Prov. CNJ 216/2026** e o **ACT CNJ-MAPA 013/2026**).

## Base legal ancorada

### A via — CPC art. 381 ✅
A producao antecipada e admitida quando: **I** haja **fundado receio de que venha a tornar-se impossivel ou muito dificil a verificacao de certos fatos** na pendencia da acao · **II** a prova possa **viabilizar a autocomposicao** · **III** o **previo conhecimento dos fatos** possa **justificar ou evitar o ajuizamento** da acao.

⭐ **O inciso I e o fundamento literal da vistoria de safra** — nao ha necessidade de analogia. Os incisos **II e III** somam bem quando o proximo passo e **negociar com o agente financeiro**, nao litigar.

- **§1º** — o **arrolamento de bens** segue esta Secao quando a finalidade for apenas **documentacao**, e nao atos de apreensao. E a via para inventariar **rebanho, maquinario e produto estocado sem apreende-los**.
- **§2º** — competencia do **juizo do foro onde a prova deva ser produzida** ou do domicilio do reu.
- **§3º** — a producao antecipada **NAO previne a competencia** para a acao futura. Desarma a objecao de que antecipar prova "escolhe o juizo".
- **§4º** — o **juizo estadual** e competente para producao antecipada requerida **em face da Uniao**, de autarquia ou de empresa publica federal **se, na localidade, nao houver vara federal**. Decisivo em comarca do interior quando o adverso e o **INCRA**.
- **§5º** — alcanca quem pretenda **justificar a existencia de fato ou relacao juridica, para simples documento e sem carater contencioso**.

### A peticao e os dois limites que precisam ser ditos ao cliente ✅
**Art. 382:** o requerente apresenta as **razoes que justificam a antecipacao** e menciona **com precisao os fatos sobre os quais a prova ha de recair**. **§1º** citacao de interessados, salvo se inexistente carater contencioso. **§3º** os interessados podem requerer **outras provas no mesmo procedimento**, sobre o mesmo fato.

🔴 **§2º — o juiz NAO se pronuncia sobre a ocorrencia ou a inocorrencia do fato, nem sobre as consequencias juridicas.** O procedimento **documenta; nao declara** a frustracao nem condena ninguem. Vender a medida como "decisao judicial sobre a perda" e prometer o que a lei nega — alinhe a expectativa **por escrito, antes de peticionar**.

🔴 **§4º — nao se admite defesa nem recurso**, salvo contra decisao que **indeferir TOTALMENTE** a prova pleiteada pelo requerente originario. **Nao ha agravo do indeferimento parcial**: o que ficar de fora do objeto ficou de fora — por isso o objeto se desenha bem na primeira peticao.

**Art. 383:** os autos permanecem em cartorio por **1 mes** para extracao de copias e certidoes pelos interessados; findo o prazo, sao **entregues ao promovente**.

### ⚠️ Quem assina o laudo responde — MP 1.376/2026, art. 9º, §1º ✅
Os dois regimes da MP exigem perda **comprovada por laudo emitido por profissional habilitado** (art. 1º, §1º na regra geral; §7º na condicao excepcional). E o **art. 9º, §1º** (verbatim) determina que o profissional que **emitir, assinar, homologar ou validar** laudo, parecer, relatorio ou documento com informacoes **falsas, fraudulentas ou incompativeis com a realidade** da propriedade ou da perda **respondera SOLIDARIAMENTE pelos danos causados ao erario**, sem prejuizo de **I** sancoes administrativas, **II** comunicacao ao **conselho profissional** e **III** responsabilizacao civil.

⭐ **Isso muda o desenho do dossie.** O laudo **nao e peca de retorica**: contrate profissional habilitado com **ART** e base tecnica real, e **registre por escrito** que a responsabilidade do §1º foi comunicada ao cliente e ao tecnico.

### O que a RJ rural passou a exigir 🔴
A RJ do produtor deixou de ser pedido documental e virou **dossie probatorio territorial** (**Prov. CNJ 216/2026**): **laudo das condicoes operacionais** (maquinario, instalacoes, pastos, granjas, silos) · **declaracao das garantias sobre safras presentes e futuras e sobre semoventes** · **perspectiva de colheita** no ciclo vigente (fatores agronomicos, climaticos e logisticos) · **constatacao previa** e **monitoramento continuo**. O **ACT CNJ-MAPA 013/2026** (26/03/2026) autoriza a **Infraestrutura VMG** — **imagens de satelite, dados climaticos e georreferenciamento** — nos dois momentos.

🟡 **A numeracao dos artigos do Prov. 216/2026 nao foi conferida** — o **conteudo e seguro; o numero do artigo, nao**. **Nao cite numero de artigo do Provimento em peca**; descreva o conteudo e roteie ao `validador-agrario`.

### Medidas vizinhas ✅
**Art. 301** — arresto, sequestro, **arrolamento de bens** e protesto contra alienacao, como tutela cautelar. **Arts. 305-310** — cautelar antecedente: reu contesta em **5 dias**; **efetivada a cautelar, o pedido principal vai em 30 dias** nos mesmos autos, sem novas custas; **art. 309**: cessada a eficacia, **vedado renovar o pedido salvo sob novo fundamento**. 🔴 Esses 30 dias sao ponto de mortalidade da via — nao confunda a cautelar com a producao antecipada, que **nao** exige acao principal. ⚠️ **Os arts. 305-310 estao na faixa que o `cpc-agrario.md` declara CONDENSADA** (§§ resumidos, nao verbatim): use os numeros para orientar, mas **confira 5 dias e 30 dias no CPC direto antes de por na peticao** — o anexo, nessa faixa, nao e prova literal.

## Passo a passo / o que produzir
1. **Definir o destino da prova** (AskUserQuestion, botoes): **renegociar com o banco** (MP 1.376) · **prorrogacao judicial** · **recuperacao judicial** · **defesa em vistoria do INCRA** · **so preservar a prova agora**.
2. **Medir a janela agronomica** — quanto tempo a lavoura ainda documenta o dano? Se a colheita ou o replantio se aproxima, a antecipacao e urgente.
3. **Delimitar o objeto com precisao** (art. 382): talhoes, cultura, area, ciclo, evento (seca, geada, granizo, praga), comparacao com a produtividade esperada. **O que nao entrar aqui nao volta por recurso (§4º).**
4. **Contratar o profissional habilitado**, exigir **ART**, e comunicar por escrito a **responsabilidade solidaria** do art. 9º, §1º.
5. **Avaliar o arrolamento documental** (art. 381, §1º) de rebanho, maquinario e produto estocado; e checar o **§4º** se houver ente federal no polo.
6. **Entregar:** peticao de producao antecipada + objeto da pericia + quesitos + **dossie de frustracao** (laudo, serie historica de produtividade, notas de insumo e venda, dados climaticos, imagens) formatado para ser reaproveitado pelas tres skills que o consomem.

## Postura honesta
- 🔴 **A producao antecipada documenta, nao declara.** O juiz **nao decide** que houve frustracao (art. 382, §2º) — quem decide e o processo seguinte, ou o agente financeiro. Cliente que espera "sentenca da perda" foi mal informado.
- **Sem recurso do indeferimento parcial** (§4º): objeto mal desenhado nao se conserta depois.
- **O laudo tem dono e tem risco.** A responsabilidade **solidaria** do art. 9º, §1º da MP 1.376 alcanca o **profissional legalmente habilitado** que **emitir, assinar, homologar ou validar** laudo falso — o texto **nao estende** a quem apenas monta o dossie sem praticar esses atos.
- 🟡 **"A confirmar", rotear ao `validador-agrario`:** **numeracao dos artigos** dos Provimentos CNJ 216/2026 e 214/2026 · **status da MP 1.376/2026**, que segue em Comissao Mista com emendas e **pode mudar** — a janela de contratacao de 120 dias corre para **~11/11/2026 (data de seguranca)**, e o *dies a quo* nao e explicito.
- **A prova antecipada nao suspende prazo nem trava execucao.** Se o cliente precisa de efeito imediato sobre a divida, o pedido e outro (tutela na skill correspondente).

## Cross-link soft + fechamento
Enquadramento e requerimento ao agente financeiro -> `renegociacao-mp-1376`. Alongamento com Sumula 298 -> `prorrogacao-de-divida-rural`. Dossie territorial -> `rj-produtor-rural-inicial` e `rj-produtor-defesa-do-credor`. Laudo de produtividade contra o INCRA -> `defesa-na-vistoria-e-laudo-de-produtividade`. Rito e competencia -> `base-processual-agraria`. Prazos -> `calendario-safra-e-prazos-criticos`. Cruzamento -> `protocolo-p4-agrario`. Calculo do prejuizo -> `calculosjudiciais-adv-os` (soft).

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
