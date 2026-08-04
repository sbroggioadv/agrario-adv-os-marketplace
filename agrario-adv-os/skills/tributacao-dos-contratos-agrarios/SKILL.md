---
name: tributacao-dos-contratos-agrarios
description: "A camada de precificacao que nao existia em 2024: IBS e CBS sobre o contrato agrario. A LC 214/2025 nao escreve arrendamento rural uma unica vez — ele entra pela porta generica de arrendamento de bem imovel do art. 251. Fixa o gatilho CUMULATIVO da pessoa fisica (receita acima de R$ 240.000 no ano anterior E mais de 3 imoveis distintos), a reducao de aliquota de 70%, e por que o redutor social de R$ 600 NAO socorre o arrendamento rural. Mostra que os gatilhos do art. 164 e do art. 251 sao independentes e convivem. Use quando o operador disser o arrendamento paga IBS CBS, quanto custa de imposto arrendar, meu cliente e produtor rural nao contribuinte, tem os R$ 600 de desconto, reforma tributaria no arrendamento, como precifico o contrato agora."
---

# TRIBUTACAO-DOS-CONTRATOS-AGRARIOS — a camada IBS/CBS

> Camada 2. Nao e contencioso tributario: e **precificacao de contrato**. O contrato agrario de 2026 tem uma variavel que o de 2024 nao tinha, e ela e invisivel para quem procura "rural" na lei nova.

## Quando ativa / trilha
Roda **junto** com qualquer skill de redacao de C2 — arrendamento, parceria, integracao, barter, venda de safra —, na etapa de **preco**. Tambem sozinha, quando a pergunta e "quanto sai de imposto".

**Fronteiras:** **ITR** (imunidade, isencao, area tributavel, aliquotas) -> `itr-e-tributacao-da-terra`, nao aqui · contencioso tributario pesado e defesa em auto fiscal -> `tributario-societario-adv-os` (soft) · estruturacao societaria e sucessoria -> `holding-architect` (soft).

## Anexos obrigatorios (context/)
- `context/tributacao-rural.md` (**PARTE I inteira — §1 a armadilha de busca · §2 quadro dos dispositivos · §3 as tres regras que decidem · §4 o que nao afirmar**; **grep "251" e leia a faixa**).
- `context/estatuto-e-decreto-contratos-agrarios.md` (§5 Dec. arts. 16-18, o teto do preco sobre o qual a carga incide — **grep e leia a faixa**).

## Base legal ancorada

### 🚨 A armadilha de busca — por que essa camada passa despercebida
**Verificado por varredura do texto compilado: a LC 214/2025 tem ZERO ocorrencias da expressao "arrendamento rural".** O arrendamento rural entra pela **porta generica de "arrendamento de bem imovel"** (**art. 251, §1º, I**). Quem procura "rural" no capitulo de bens imoveis **nao acha e conclui, errado, que o contrato esta fora**.

### O quadro que decide a precificacao ✅
| Tema | Dispositivo | Regra |
|---|---|---|
| Regime especifico de bens imoveis | **art. 251, caput** | Operacoes com bens imoveis por contribuintes do regime regular ficam no regime especifico do Capitulo |
| **PF vira contribuinte** (locacao e **arrendamento**) | **art. 251, §1º, I** 🔴 | **CUMULATIVAMENTE**, no ano-calendario anterior: receita total **> R$ 240.000** **E** **mais de 3 bens imoveis distintos** |
| Gatilho no **proprio** ano | **art. 251, §2º, II** 🔴 | Tambem e contribuinte quem **exceder em 20%** o limite da alinea "a" ⇒ **R$ 288.000** |
| Atualizacao do limite | **art. 251, §5º** | Os R$ 240.000 sao atualizados **mensalmente pelo IPCA** desde a publicacao |
| **Reducao de aliquota** | **LC 214, art. 261, p.u.** 🔴 | Locacao, cessao onerosa e **arrendamento** de bens imoveis: aliquotas **reduzidas em 70%** *(o caput reduz 50% nas demais operacoes imobiliarias)* |
| **Redutor social** | **LC 214, art. 260** | R$ 600,00 por mes, por imovel — **SO PARA USO RESIDENCIAL** |
| **Produtor rural nao contribuinte** | **LC 214, art. 164** 🔴 | Produtor rural PF ou PJ com receita **< R$ 3.600.000** no ano e o **produtor rural integrado** nao sao contribuintes. **§2º:** excedido o limite, vira contribuinte **a partir do 2º mes subsequente** |
| Credito presumido | **art. 168** | O contribuinte do regime regular apropria **credito presumido** ao adquirir de produtor rural nao contribuinte |
| Opcao pelo regime regular | **arts. 165 e 166** | A qualquer tempo, **irretratavel para todo o ano-calendario**; renuncia com efeito no ano seguinte |
| Alteracoes de 2026 | **LC 227/2026** 🔴 | Altera a LC 214/2025 em **460 pontos**, **16 deles no capitulo de bens imoveis**, inclusive o **art. 260 da LC 214** |

### ⭐ As tres regras que decidem o caso
**(a) O gatilho da pessoa fisica e CUMULATIVO — nunca "ou".** Receita **> R$ 240.000** no ano anterior **E** **mais de 3 imoveis distintos**. Faltando **um** dos dois, nao e contribuinte por essa via. Escrever "ou" infla a carga estimada e derruba a precificacao do contrato.

**(b) O redutor social NAO socorre o arrendamento rural.** Os R$ 600/mes do **art. 260** valem **somente para uso RESIDENCIAL**. Aplica-lo a arrendamento rural subestima a carga — erro que o cliente so descobre depois de assinar.

**(c) 🎯 Os dois regimes CONVIVEM — os gatilhos sao INDEPENDENTES.** O mesmo sujeito pode ser, ao mesmo tempo, **produtor rural nao contribuinte pelo art. 164** (receita < R$ 3,6 milhoes) **e contribuinte pelo art. 251, §1º, I** se arrendar **mais de 3 imoveis** com receita superior a R$ 240 mil. Concluir "e nao contribuinte pelo 164, logo o arrendamento esta fora" e **o erro central desta camada**.

### Onde a carga incide
A base e a **contraprestacao do contrato** — a renda do arrendamento, que ja tem **teto legal** de 15% ou 30% do **valor cadastral** (ET 95, XII + Dec. 17). O calculo util para o cliente e sempre o **liquido do arrendador** e o **custo total do arrendatario** apos a reducao de 70% do art. 261, p.u., e nao a aliquota nominal isolada.

## Passo a passo / o que produzir
1. **Levantar o perfil** (AskUserQuestion, botoes): **PF x PJ** · **receita do ano anterior** faixa (**ate R$ 240 mil · de R$ 240 mil a R$ 3,6 mi · acima de R$ 3,6 mi**) · **quantos imoveis distintos** (**ate 3 · mais de 3**).
2. **Testar os dois gatilhos separadamente** — art. 164 (produtor rural) **e** art. 251, §1º, I (locador/arrendador). Nunca deduzir um do outro.
3. **Checar o gatilho do proprio ano** (art. 251, §2º, II — os 20%, R$ 288.000) e **apurar o limite atualizado pelo IPCA na data** (art. 251, §5º).
4. **Aplicar a reducao de 70%** (art. 261, p.u.) e **descartar o redutor de R$ 600** se o uso nao for residencial.
5. **Avaliar a opcao pelo regime regular** (arts. 165-166), lembrando que e **irretratavel no ano** — decisao que nao se desfaz em dezembro.
6. **Entregar:** memoria de calculo com premissas declaradas + clausula contratual que **defina quem suporta o tributo** e o que ocorre em mudanca de regime + sinalizacao dos itens 🟡 a confirmar.

## Postura honesta
- **Esta skill precifica; nao substitui o contador nem o tributarista.** A memoria de calculo sai com **premissas declaradas** — receita, numero de imoveis, uso do bem, regime — e a conferencia final e do profissional habilitado.
- 🟡 **As 16 alteracoes da LC 227/2026 no capitulo de bens imoveis nao foram lidas integralmente.** Foram **contadas as notas** no compilado e **lida apenas a alteracao do art. 260**. **As outras 15 permanecem nao lidas**, assim como o texto integral da LC 227/2026 — **confirme antes de citar qualquer uma delas**.
- 🟡 **A definicao regulamentar de "bens imoveis distintos" (art. 251, §6º) foi remetida a regulamento nao verificado.** E o **valor atualizado** do limite de R$ 240.000 **nao pode ser calculado por memoria** (art. 251, §5º manda atualizar mensalmente pelo IPCA) — apure na data do atendimento.
- 🟡 **PL 2827/25 — projeto pendente, nao e lei.** Incluiria a receita de arrendamento rural no conceito de atividade rural para fins de IR (aprovado em comissao em dez/2025). **Nao precifique com ele.**
- ⛔ **A reforma tributaria NAO mudou o ITR.** A EC 132/2023 e a LC 214/2025 reformaram o **consumo**. Quem levar IBS/CBS para a discussao de ITR erra de tributo — o ITR e de `itr-e-tributacao-da-terra`.

## Cross-link soft + fechamento
Teto do preco sobre o qual a carga incide -> `preco-prazo-e-renovacao-do-arrendamento`. Minuta -> `contrato-arrendamento-rural`. Parceria, integracao, barter e venda de safra -> as respectivas skills de C2, todas na etapa de preco. **ITR** -> `itr-e-tributacao-da-terra`. Contencioso tributario pesado -> `tributario-societario-adv-os` (soft). Estrutura societaria -> `holding-architect` (soft).

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
