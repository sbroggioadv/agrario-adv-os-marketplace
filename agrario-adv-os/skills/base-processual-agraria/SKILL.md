---
name: base-processual-agraria
description: "Fundacao processual do plugin agrario, standalone e sem depender do civel: fixa via, competencia, rito, prazos e onus de prova antes de qualquer peca — procedimento comum do CPC/2015 no lugar do rito morto do art. 86 do Decreto 59.566/66, escolha entre execucao para entrega de coisa incerta e por quantia certa, foro de cada demanda agraria, as duas vias de notificacao extrajudicial e o obice das Sumulas 5 e 7 do STJ. Use antes de ajuizar ou contestar, ou quando o operador disser onde ajuizo, qual o rito, e Justica Federal ou Estadual, qual o valor da causa, cabe tutela, o recurso tem efeito suspensivo, qual execucao uso para essa CPR."
---

# BASE-PROCESSUAL-AGRARIA — Via, competencia e rito (CPC filtrado, standalone)

> Camada 1. O plugin **nao depende do `civel-adv-os`**: o CPC entra aqui **filtrado** ao que o agrario usa. Nao redige peca — decide **onde**, **por qual rito** e **com que prazo** ela vai. O erro que esta camada existe para impedir e o mais barato de cometer e o mais caro de consertar: **peca certa na porta errada**.

## Quando ativa / trilha
Roda **depois** da base material (as tres outras de C1) e **antes** de qualquer peca de C3, C5, C7 e C8. Toda skill que ajuiza ou contesta passa por aqui.

**Diferenca da vizinha:** a **C8 redige o recurso**; esta skill fixa o **regime** que ele obedece — inclusive o efeito suspensivo, que **nao** se resolve pelo art. 86 do Decreto.

## Anexos obrigatorios (context/)
- **`context/cpc-agrario.md`** — os 77 artigos do CPC/2015 do agrario, verbatim do Planalto (§2 competencia e **art. 60** · §3 procedimento comum · §5 tutela · §6 producao antecipada · §7 **art. 178, III** · §8 possessorias e **art. 565** · §9 art. 784 · §10 entrega de coisa · §12 impenhorabilidade · §13 recursos e **art. 1.012**) — **grep e leia a faixa**.
- `context/estatuto-e-decreto-contratos-agrarios.md` (**§7 rito morto do art. 86** · art. 32 despejo e purga · art. 22 §3º notificacao · arts. 45-47 preferencia — **grep o artigo e leia a faixa**).
- `context/jurisprudencia-agraria.md` (**§13 Sumulas 5 e 7** · Sumula 354 · Tema 1.234 · §11 pendentes) · `context/lei-do-agro-e-cpr.md` (§1 a via correta) · `context/lei-8629-93-e-cf-184-191.md` (**CF 184, §3º**) · `context/registral-terras-e-estrangeiros.md` (Lei 6.383/76 **arts. 19 e 23**) · **`context/lc-76-93-desapropriacao.md`** (**§10 art. 13** efeito da apelacao · **§17 art. 22** CPC subsidiario).

## Base legal ancorada

### 🔴 O art. 86 do Decreto 59.566/66 e RITO MORTO — com a hedge correta
O art. 86 manda os litigios entre arrendadores e arrendatarios seguirem "o rito processual estabelecido pelo art. 685 do Codigo de Processo Civil".

⚠️ **Precisao que evita ser desmentido em audiencia:** **o texto NAO nomeia qual CPC**. O Decreto e de 1966 (CPC entao vigente: **1939**), mas a **remissao editorial do Planalto aponta para o CPC/1973**. **Nos dois cenarios o rito esta revogado** — a conclusao se sustenta. **Nao afirme "CPC/1939" como se estivesse escrito**: use a hedge. Hoje, **procedimento comum do CPC/2015**.

🔴 **Corolario para a C8 — o art. 1.012 diz o CONTRARIO do art. 86, p.u.** A regra vigente e **"a apelacao tera efeito suspensivo"** (caput). O **§1º** tem **ROL taxativo mas FONTE aberta** — abre com **"Alem de outras hipoteses previstas em lei"** —, e **duas das seis sao agrarias**: **I** homologacao de **divisao ou demarcacao de terras** e **III** **improcedencia dos embargos do executado** (a rota de quem perdeu embargos contra CPR ou cedula). O **§1º, V** (tutela provisoria) e frequentissimo no agro; o **§4º** deixa o relator suspender a eficacia. **Sustentar "recurso sem efeito suspensivo" pelo art. 86 e sustentar dispositivo morto.**

🔴 **A hipotese que vem de FORA do CPC — LC 76/93, art. 13:** na desapropriacao, **"da sentenca que fixar o preco da indenizacao cabera apelacao com efeito simplesmente devolutivo, quando interposta pelo EXPROPRIADO e, em ambos os efeitos, quando interposta pelo EXPROPRIANTE"**. E uma das "outras hipoteses previstas em lei" que o proprio §1º admite — e o **art. 22** da mesma lei, que manda aplicar o CPC **"no que for compativel"**, e a clausula que faz o art. 13 prevalecer. **Contrapeso ✅ (art. 13, §1º):** condenacao superior a **50% do valor oferecido na inicial** sobe em **duplo grau de jurisdicao**, de oficio — vitoria grande em 1º grau **nao transita** sem reexame. **Cirurgico:** vale para **essa sentenca**; nos demais provimentos do rito e em todo o resto do agrario o art. 1.012 vale **integralmente** — nao vire isto em "no agrario o efeito suspensivo e incerto". Texto em `context/lc-76-93-desapropriacao.md` **§10 e §17** (**grep o artigo e leia a faixa**); redacao da peca em `apelacao-e-agravo-agrario`.

### Via de execucao — escolha antes de peticionar ✅
**CPR fisica -> ENTREGA DE COISA INCERTA** (L8929 **art. 15**; CPC 811-813). **CPR financeira -> QUANTIA CERTA** (**art. 4º-A, §2º**). A **CIR** e o titulo que a **L13986 art. 21** chama de **titulo executivo extrajudicial**. Errar a porta e vicio que a defesa explora.

### Competencia e foro
| Demanda | Onde |
|---|---|
| Desapropriacao p/ reforma agraria | **Uniao** autora (CF 184, §2º), **rito sumario da LC 76/93** (CF 184, §3º) |
| Discriminatoria de devolutas | **Justica Federal** (L6383 **art. 19**); **art. 23**: **preferencial e prejudicial** |
| Contratos, despejo, preferencia, possessorias | Justica Estadual da **situacao do imovel** |
| Integracao vertical | Foro do **local do empreendimento do integrado** (L13288) |

🔴 **Art. 60 — a fazenda que cruza divisa:** imovel em **mais de um Estado, comarca, secao ou subsecao**, a competencia do **juizo prevento alcanca a TOTALIDADE do imovel**. Alto uso, baixa lembranca: a contraparte tenta fatiar a demanda ou arguir incompetencia parcial. Vale para possessoria, divisao, demarcacao e discriminatoria.

🔴 **Art. 178, III — MP obrigatorio no litigio coletivo pela posse de terra rural** (intimado em **30 dias**). **Nao e faculdade**: casa com os arts. 554, §1º e 565, §2º, e a **falta de intimacao e nulidade**. ⚠️ **Nao confundir** com o MP na desapropriacao (ancora propria: JT 46 #4) — o 178, III cobre **posse coletiva**.

### CPC/2015 filtrado ✅ — os artigos estao no anexo, por secao
**300** tutela · **319** inicial · **381** producao antecipada · **554-568** possessorias, com o **565** exigindo **audiencia de mediacao se o esbulho tiver mais de ano e dia** · **784** titulos extrajudiciais (🟡 **inciso nao confirmado — cite o artigo, nunca o inciso**) · **806-813** entrega de coisa · **832-834** impenhorabilidade (base do Tema 1.234) · **914-920** embargos · **994-1.042** recursos. Prazos em **dias uteis** no judicial, **corridos** no administrativo.

### Notificacao extrajudicial — duas vias, nao uma ✅
**Dec. 59.566/66, art. 22, §3º:** notificacao, desistencia e proposta se fazem **por carta pelo RTD da comarca do imovel OU por requerimento judicial**. **A extrajudicial nao e via unica.**

### Despejo, purga e prazos-relogio ✅
**Dec. art. 32:** **9 hipoteses taxativas**. **Purga da mora (III):** o devedor requer **no prazo da contestacao**; paga em prazo do juiz **nao excedente de 30 dias**, contados **da entrega em cartorio do mandado de citacao cumprido**.

**O relogio do agro:** **30 dias** da preferencia (ET 92 §3º; Dec. 45) · **6 meses da transcricao** para adjudicar (ET 92 §4º; Dec. 47) · **6 meses** da notificacao de renovacao ou retomada · **20 dias** da defesa ambiental · **120 dias** da MP 1.376/2026 (**~11/11/2026, data de seguranca**) 🟡 **PENDENTE (Comissao Mista)**.

### Prova e obice recursal ✅
**Tema 1.234/STJ:** **onus do EXECUTADO** provar a exploracao familiar (base legal nos arts. 832-834). **Sumula 354/STJ:** a **invasao** suspende o processo expropriatorio. **Sumulas 5 e 7 do STJ sao o obice recorrente** — travaram o **REsp 1.447.082-TO** na parte fatica: o excepcional se desenha sobre **prequestionamento e materia de direito**, nunca reexame de prova ou de clausula.

## Passo a passo / o que produzir
1. **Fixar a via**: administrativa x judicial; sendo executiva, **entrega de coisa incerta x quantia certa** pela especie.
2. **Fixar a competencia** pela tabela — Justica Federal so onde a lei a impoe.
3. **Fixar o rito**: procedimento comum do CPC/2015 no arrendamento (**nunca o art. 86**); rito sumario da LC 76/93 na desapropriacao; possessorio com o filtro do art. 565.
4. **Datar os prazos** pelo relogio acima; checar decadencia antes de tudo (30 dias e 6 meses derrubam pedido bom).
5. **Checar tutela** (300) e **producao antecipada** (381) antes de ajuizar.
6. **Entregar a folha de rosto**: via · competencia e foro · rito · valor da causa · prazo e *dies a quo* · tutela · onus de prova · selo (✅ / 🟡 / 🔴).

## Postura honesta
- ✅ `context/cpc-agrario.md` traz os 77 artigos verbatim. Vale a regra normal — **grep o artigo e leia a faixa**. Skill de peca que ainda traga a ressalva "nao citar CPC sem conferencia ao vivo" esta superada pelo anexo.
- 🟡 **Nao cite o inciso do CPC art. 784** que enquadraria CPR e cedula — nao foi confirmado por nenhuma frente.
- ✅ `context/lc-76-93-desapropriacao.md` tem o texto integral — o 🟡 "nao cite artigo por memoria" esta **superado**; cite pelo anexo. ⚠️ **arts. 14 e 15 REVOGADOS** (MP 759/2016; Lei 13.465/2017), ainda exibidos na pagina.
- ⚠️ **Sobre o art. 86:** afirmar categoricamente "CPC/1939" **e atacavel**, porque o dispositivo nao nomeia o diploma e a remissao oficial aponta para 1973. A conclusao (rito morto) e segura; a premissa exige a hedge. Este e um caso raro em que ganhar precisao custa uma frase a mais — pague a frase.
- 🟡 **PENDENTE — ADPF 828:** existe apenas a **cautelar referendada** (nov/2022); **o merito nunca foi julgado**. Em possessoria coletiva cite "a decisao cautelar referendada", **nunca "o acordao de merito"**.
- Nenhuma sumula sobre **notificacao previa da vistoria** foi localizada — a Sumula 354 e sobre **invasao**. **Nao invente numero.**

## Cross-link e fechamento
Recursos -> C8. Titulo -> `execucao-de-cpr-e-cedula-rural` · `embargos-a-execucao-de-cpr`. Despejo e preferencia -> C7. Possessoria coletiva -> `possessorias-rurais-e-conflito-coletivo`. Rito expropriatorio -> `rito-lc-76-93-e-contestacao`. Cruzamento -> `protocolo-p4-agrario`. CPC integral -> `civel-adv-os`; execucao generica -> `execucao-adv-os` (soft — o agrario e dono da **especializada em CPR e cedula rural**).

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
