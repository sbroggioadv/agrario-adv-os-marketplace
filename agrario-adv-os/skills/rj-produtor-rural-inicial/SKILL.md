---
name: rj-produtor-rural-inicial
description: "Peticao inicial de recuperacao judicial do produtor rural com o dossie probatorio territorial do Provimento CNJ 216/2026 — laudo das condicoes operacionais, declaracao das garantias sobre safras e semoventes, perspectiva de colheita e prova do registro do imovel em nome da recuperanda. Carrega o art. 48 com LCDPR, DIRPF e balanco cumulativos para pessoa fisica, ECF para pessoa juridica, o Tema 1.145 e o plano especial do art. 70-A. Use quando o operador disser recuperacao judicial do produtor, RJ rural, pedir recuperacao, o produtor vai quebrar, plano especial, biemio do art. 48, /rj-produtor."
---

> **🖱️ Escolhas = botoes:** em pergunta de **lista fechada** (pessoa fisica x juridica, plano ordinario x especial, regime de escrituracao) use **AskUserQuestion** — botoes clicaveis, max. 4 por pergunta.

# RJ-PRODUTOR-RURAL-INICIAL — a inicial e o dossie territorial de 2026

> Camada 3, nucleo comercial. ⭐ **A RJ rural de 2026 nao e pedido documental — e dossie probatorio territorial.** E o gargalo real da inicial, e o que nenhum concorrente cobre.

## Quando ativa / trilha
O quadro e de **insolvencia**, nao de divida isolada. Vem da `triagem-agraria` (pergunta 1, terceira saida). Antes de pedir RJ, esgotar `renegociacao-mp-1376` e `prorrogacao-de-divida-rural` — composicao extrajudicial que evita o pedido costuma valer mais que a RJ.

**Diferenca das vizinhas:** `rj-produtor-defesa-do-credor` e o lado oposto; `rj-sujeicao-de-creditos-agro` responde **quem entra e quem fica de fora** do concurso — analise que deve ser feita **antes** de protocolar, porque define o passivo real.

## Anexos obrigatorios (context/)
- `context/rj-produtor-rural.md` (**§1 requisitos do art. 48** · **§3 o dossie do Prov. CNJ 216/2026** · §4 Tema 1.145 · §5 lista 🟡 — **grep o artigo e leia a faixa**).
- `context/jurisprudencia-agraria.md` (**Tema Repetitivo 1.145/STJ** — grep o numero e leia a faixa).
- `context/lei-do-agro-e-cpr.md` (art. 11 da L8929 e art. 10, §4º da L13986 — o que **nao** entra) · `context/registral-terras-e-estrangeiros.md` (registro do imovel em nome da recuperanda).

## Base legal ancorada ✅

### Art. 48 — o bienio e os quatro incisos
Pode requerer RJ quem, **no momento do pedido, exerca regularmente suas atividades ha mais de 2 anos**, atendidos **cumulativamente**: **I** nao ser falido (ou ter responsabilidades extintas por sentenca transitada) · **II** nao ter obtido concessao de RJ **ha menos de 5 anos** · **III** nao ter obtido concessao com base no **plano especial ha menos de 5 anos** · **IV** nao ter condenacao por crimes da Lei 11.101/05.
⚠️ **Citar "8 anos" no inciso III e redacao revogada desde a LC 147/2014 — sao 5 anos.**

### Como se prova o bienio — e o erro que aparece em todo resumo
- **§2º — PESSOA JURIDICA:** comprovacao pela **Escrituracao Contabil Fiscal (ECF)**, ou obrigacao legal que a substitua, **entregue tempestivamente**. ⚠️ **"DIPJ" e redacao revogada** (Lei 14.112/2020).
- ⭐ **§3º — PESSOA FISICA: LCDPR + DIRPF + balanco patrimonial, CUMULATIVOS**, "**todos entregues tempestivamente**". Nao e um ou outro: sao os tres, e a **tempestividade integra o requisito**.
- **§4º — a valvula:** no periodo em que **nao for exigivel** a entrega do LCDPR, admite-se o **livro-caixa** usado para elaborar a DIRPF. E a saida do produtor que nao tinha LCDPR no inicio do bienio.
- **§5º:** escrituracao pelo padrao contabil vigente, em **regime de competencia**, com **balanco por contador habilitado**.
- 🚨 **O art. 48 NAO menciona DAP em nenhum paragrafo.** A **DAP/CAF e instrumento do Pronaf** (credito rural), **nao** requisito de RJ. Oferece-la como prova do bienio e erro de subsuncao.

### ⭐ Tema Repetitivo 1.145/STJ — o registro nao precisa ser antigo
**Tese (verbatim):** "Ao produtor rural que exerca sua atividade de forma empresarial **ha mais de dois anos** e facultado requerer a recuperacao judicial, **desde que esteja inscrito na Junta Comercial no momento em que formalizar o pedido recuperacional, independentemente do tempo de seu registro**."
**2ª Secao**, Rel. Min. **Luis Felipe Salomao**, *leading cases* **REsp 1.905.573/MT** e **REsp 1.947.011/PR**, **julgado em 22/06/2022**, tese firmada e transitada. **Ratio:** a inscricao na Junta **apenas declara** a condicao de empresario (CC art. 967), sem efeito constitutivo — **o bienio e de EXERCICIO DA ATIVIDADE, nao de REGISTRO**, e o tempo anterior ao registro **conta**.
🚨 **Armadilha invertida:** "o Tema 1.145 exige registro ha dois anos" e **o oposto** do que a tese diz.

### Art. 70-A — plano especial do produtor rural
"**O produtor rural de que trata o §3º do art. 48**" pode apresentar **plano especial**, **desde que o valor da causa nao exceda R$ 4.800.000,00**. Escopo: remete ao §3º ⇒ regime da **pessoa fisica**. Segue os **arts. 71 e 72**: abrange os creditos existentes na data do pedido, **exceto** repasse de recursos oficiais, fiscais e os dos §§3º e 4º do art. 49; **ate 36 parcelas** mensais com **juros SELIC**; primeira em ate **180 dias** da distribuicao.

### ⭐ O DOSSIE TERRITORIAL — Provimento CNJ 216, de 09/03/2026 🔴
A inicial **nasce instruida** com, entre outros: **bienio por documentos enumerados**, admitido **periodo anterior ao registro mercantil** (coerente com o Tema 1.145) · **laudo das condicoes operacionais** (maquinario, instalacoes, pastos, granjas, silos) · **declaracao das garantias sobre safras presentes e futuras e sobre semoventes** · **perspectiva de colheita** no ciclo vigente (fatores agronomicos, climaticos e logisticos) · elemento para o perito esclarecer se a propriedade esta **formalmente registrada em nome da recuperanda** · **constatacao previa** e **monitoramento continuo**.

Complementam o **ACT CNJ-MAPA 013/2026** (26/03/2026), que autoriza a **Infraestrutura VMG** — **imagens de satelite, dados climaticos e georreferenciamento** — nos dois momentos, e o **Provimento CNJ 231/2026** (administradores judiciais).

⚠️ **Faltando peca do dossie, a constatacao previa devolve o problema.** E a inicial "documental" do modelo antigo que morre nessa porta.

### Trava a antecipar — art. 49, §9º
**Nao se enquadra** nos creditos do caput a divida **constituida nos 3 ultimos anos anteriores ao pedido** contraida para **aquisicao de propriedades rurais**, **bem como as respectivas garantias**. Compra recente de terra financiada **fica fora** do concurso — e e o primeiro indicio de blindagem que o credor levanta. Mapear isso **antes** de protocolar.

## Passo a passo / o que produzir
1. **Qualificar (botoes):** pessoa fisica x juridica — define §3º (LCDPR + DIRPF + balanco) ou §2º (ECF).
2. **Testar o bienio pelo Tema 1.145:** tempo de **exercicio**, nao de registro; e **inscricao na Junta no momento do pedido**.
3. **Auditar a tempestividade** de cada documento do §2º/§3º — e requisito, nao formalidade. Faltando LCDPR no periodo, acionar o **§4º**.
4. **Rodar os incisos I a IV** do caput (III = **5 anos**).
5. **Mapear o passivo real** com `rj-sujeicao-de-creditos-agro` **antes** da inicial: CPR fisica e barter, alienacao fiduciaria, recursos controlados, patrimonio afetado e a trava do §9º. RJ desenhada sobre passivo que nao se sujeita nasce inutil.
6. **Montar o dossie do Prov. 216/2026** — laudo operacional, declaracao de garantias sobre safras e semoventes, perspectiva de colheita, prova do registro do imovel em nome da recuperanda.
7. **Escolher o plano (botoes):** ordinario ou **especial do art. 70-A** (teto de **R$ 4,8 milhoes** de valor da causa).
8. **Entregar:** peticao inicial + dossie do Prov. 216 + demonstrativo do passivo com a classificacao de sujeicao + parecer honesto de viabilidade.

## Postura honesta
- ⚠️ **Menos de 1/4 dos planos de recuperacao aprovados sao efetivamente cumpridos** 🟡 (dado de mercado, nao ancora juridica). Entra no diagnostico do `parecer-agrario` e na conversa com o cliente **antes** da contratacao — RJ nao e solucao, e prazo.
- 🟡 **A numeracao dos artigos do Prov. CNJ 216/2026 nao esta confirmada**. O **conteudo das exigencias e seguro**; **nao cite numero de artigo do Provimento em peca** sem confirmar no portal de atos do CNJ.
- 🟡 **O teor dos arts. 14 e 21 da Lei 4.829/65** (recursos controlados, art. 49, §7º) **nao foi lido** — nao afirme o conteudo deles.
- 🟡 **Nao ha varredura integral confirmada da Lei 11.101/05** (consultados os arts. 6º, 48, 48-A, 49, 50, 70-A, 71 e 72). **Nao afirme ausencia de alteracao fora desses artigos.**
- 🟡 **UF lider em pedidos de RJ do agro:** o trecho capturado comeca em "na sequencia aparecem Goias". 🚨 **Nao invente Mato Grosso.**
- ⚠️ **A MP 1.376/2026** 🟡 **pendente** em Comissao Mista (**pode caducar ou ser alterada**) **nao trata de recuperacao judicial.** Que seus arts. 3º, I e 5º, p.u. viabilizem composicao extrajudicial e **leitura**, nao comando legal.

## Cross-link e fechamento
Sujeicao de creditos -> `rj-sujeicao-de-creditos-agro`. Lado credor -> `rj-produtor-defesa-do-credor`. Evitar a RJ -> `renegociacao-mp-1376` · `prorrogacao-de-divida-rural`. Titulos e garantias -> `cpr-emissao-e-formalizacao` · `garantias-do-credito-rural` · `patrimonio-rural-em-afetacao-e-cir`. Laudo de perda -> `prova-de-frustracao-de-safra-e-vistoria`. Viabilidade -> `parecer-agrario`.

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
