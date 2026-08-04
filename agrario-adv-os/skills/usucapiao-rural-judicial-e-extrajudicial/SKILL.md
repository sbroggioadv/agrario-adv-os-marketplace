---
name: usucapiao-rural-judicial-e-extrajudicial
description: "Monta a usucapiao de imovel rural nas duas vias: a inicial da especial rural do art. 191 da CF e do art. 1.239 do CC, com os seis requisitos cumulativos e o memorial georreferenciado do art. 225 §3º da LRP, e o requerimento extrajudicial do art. 216-A — que VALE PARA RURAL, e no qual o silencio do confinante conta como CONCORDANCIA desde a Lei 13.465/2017. Separa a especial rural da extraordinaria e da ordinaria, e barra de saida quem tem posse derivada. Use quando o operador disser quero usucapir essa area, o cliente esta na terra ha anos, da pra fazer no cartorio, quantos anos preciso, o confinante nao assina, arrendatario pode usucapir, a area tem mais de 50 hectares, essa terra e do Estado."
---

# USUCAPIAO-RURAL-JUDICIAL-E-EXTRAJUDICIAL — as duas vias, sem confundir a especie

> Camada 4. Nao ha uma usucapiao rural: ha **tres especies** e **duas vias**. Errar a especie derruba a inicial no merito; errar a via custa tempo. Esta skill decide as duas antes de redigir.

## Quando ativa / trilha
Entra na trilha **terra/registral** quando ha **posse sem titulo** — tipicamente depois da `due-diligence-de-terras-rurais` mostrar cadeia dominial rota ou inexistente.

**Fronteira que evita a skill errada:** usucapiao **urbana** e do `direito-imobiliario-adv-os`. **Titulo publico** com clausula resolutiva nao se usucape, se regulariza -> `regularizacao-fundiaria-rural`. Suspeita de **terra devoluta** -> `terras-devolutas-e-discriminatoria` **antes** de ajuizar.

## Anexos obrigatorios (context/)
- `context/registral-terras-e-estrangeiros.md` (**§6 usucapiao rural — grep "216-A" e leia a faixa**; §1 art. 176 §§3º-4º e art. 225 §3º; §2 CCIR).
- `context/cpc-agrario.md` (**art. 47** foro da situacao da coisa e **art. 60** — **grep "art. 60" e leia a faixa**; §3 procedimento comum).
- `context/tributacao-rural.md` (§11 **art. 21**, quitacao de ITR nos atos registrais — **grep "art. 21"**).
- `context/jurisprudencia-agraria.md` (**Sumula 340/STF** — selo ✅ antes de citar).

## Base legal ancorada

### A especial rural — CF art. 191 e CC art. 1.239 ✅ (6 requisitos CUMULATIVOS)
| # | Requisito | Nota que derruba a inicial |
|---|---|---|
| 1 | Posse por **5 anos ininterruptos** | interrupcao quebra o prazo; soma-se a anterior so pelo CC 1.243 |
| 2 | **Sem oposicao** | acao possessoria, notificacao ou embargo do titular descaracteriza |
| 3 | Area **em zona rural**, **nao superior a 50 ha** | teto **constitucional**: acima disso a especial nao serve |
| 4 | Torna-la **produtiva pelo trabalho proprio ou da familia** | sem prova de exploracao nao ha *pro labore* |
| 5 | Ter **nela sua moradia** | residencia no imovel, nao visita |
| 6 | **Nao ser proprietario de NENHUM imovel, rural ou urbano** | um apartamento no nome do cliente mata o pedido |

⭐ **A vantagem da especial:** dispensa **justo titulo e boa-fe**. O preco e a rigidez dos seis itens — todos, ao mesmo tempo.

### ⛔ As duas travas de saida
1. **Imovel publico NAO se usucape** — **CF art. 191, p.u.** e **Sumula 340/STF**. ⚠️ O p.u. **so entra depois de provada a natureza publica**: a tese do onus (quem alega devolutividade prova) e 🟡 **pendente** (AREsp 888.195/PI; EDcl REsp 617.428/SP, sem repetitivo) — ver `terras-devolutas-e-discriminatoria`.
2. 🚨 **O arrendatario NAO usucape.** Posse **derivada** do contrato nao e posse *ad usucapionem* — nem a do parceiro, nem a do comodatario. Cliente que "esta na terra ha 20 anos pagando arrendamento" pode ter **preferencia** (ET 92, §3º) **se** preencher o perfil de **homem do campo** (exploracao direta, residencia, atividade familiar — Dec. arts. 38 e 8º); a preferencia **nao e automatica**. Usucapiao, **nunca**. Confundir os dois e perder o caso e a prescricao do direito certo.

### As outras duas especies — escolha pelo prazo ✅
- **CC art. 1.238 (extraordinaria)** — **15 anos**, sem interrupcao nem oposicao, **independentemente de titulo e boa-fe**; **paragrafo unico: 10 anos** se o possuidor estabeleceu **moradia habitual** ou realizou **obras ou servicos de carater produtivo**. **Nao tem teto de area.**
- **CC art. 1.242 (ordinaria)** — **10 anos**, com **justo titulo E boa-fe**; **paragrafo unico: 5 anos** se o imovel foi adquirido onerosamente com base em **registro posteriormente cancelado** e houve moradia ou investimentos de interesse social e economico.
- **CC art. 1.243** — **acessao de posses**: soma-se a posse dos antecessores, desde que **continuas e pacificas**, e, no caso do art. 1.242, tambem com **justo titulo e boa-fe**.

> ⭐ **Area acima de 50 ha nao encerra o caso** — encerra a *especial*. A extraordinaria nao tem teto: reclassifique em vez de recusar.

### A via extrajudicial — LRP art. 216-A ✅ (vale para rural)
**O texto nao distingue urbano de rural**: fala em "o imovel usucapiendo", perante o registro da comarca de situacao, a requerimento do interessado **representado por advogado**. A unica mencao a especie de imovel esta no §11 (unidade autonoma de condominio edilicio) — **regra especial, nao limitacao**.

**Instruido com 4 documentos (incisos I a IV):** **I** **ata notarial** com o tempo de posse do requerente e dos antecessores · **II** **planta e memorial descritivo** por profissional habilitado com **ART**, assinados tambem pelos titulares de direitos na matricula do usucapiendo e dos confinantes · **III** **certidoes negativas** dos distribuidores da comarca do imovel e do domicilio do requerente · **IV** **justo titulo ou documentos** de origem, continuidade, natureza e tempo da posse.

**Os paragrafos que decidem o rito:**
- **§2º (red. Lei 13.465/2017) ⭐** — faltando assinatura de titular na matricula ou de confinante, ele e notificado para se manifestar em **15 dias**, **"interpretado o silencio como concordancia"**. 🔴 **Ate 2015 o silencio era DISCORDANCIA** — a inversao e de 2017 e e erro classico de base de treino.
- **§3º** — ciencia a **Uniao, Estado, DF e Municipio**, em **15 dias**.
- **§4º** — **edital** em jornal de grande circulacao, **15 dias**.
- **§10 (red. Lei 14.382/2022)** — havendo **impugnacao justificada**, o oficial remete ao juizo competente e o requerente emenda a inicial para o procedimento comum; **impugnacao injustificada nao e admitida** pelo registrador, cabendo ao interessado **suscitar duvida** (art. 198).

### O que a via rural exige a mais ✅
Mesmo no extrajudicial: **descricao georreferenciada** quando exigivel (LRP art. 176, §§3º e 4º; **art. 225, §3º** para autos judiciais), **CCIR** (Lei 4.947/66, art. 22, §1º), **quitacao de ITR** (Lei 9.393/96, art. 21) e **CAR**. **Competencia judicial:** foro da **situacao da coisa** (**CPC art. 47**); imovel em mais de uma comarca ou Estado, o **juizo prevento julga a totalidade** (**CPC art. 60**).

## Passo a passo / o que produzir
1. **Qualificar** (AskUserQuestion, botoes): natureza da posse — **propria x derivada de contrato** · especie — **especial rural · extraordinaria · ordinaria** · via — **judicial x extrajudicial** · titularidade aparente — **particular · publica · desconhecida**.
2. **Rodar a trava de saida:** posse derivada ou imovel comprovadamente publico => **nao ajuize**; roteie.
3. **Marcar os 6 requisitos** um a um, com o **documento que prova cada um** (nao a alegacao). Falhando um, **reclassifique** para 1.238 ou 1.242 antes de desistir.
4. **Montar a prova:** ata notarial ou prova testemunhal e documental do tempo de posse · planta e memorial com ART · certidoes · CCIR, ITR e CAR.
5. **Escolher a via:** consenso dos confinantes e titulares => extrajudicial; titular resistente => judicial. **Impugnacao justificada joga o caso ao juizo de qualquer forma** (§10).
6. **Entregar:** inicial de usucapiao (enderecamento, qualificacao do imovel, os 6 requisitos um a um, pedido de registro) **ou** requerimento extrajudicial instruido; mais o **quadro requisito -> prova -> selo** e a lista de pendencias registrais.

## Postura honesta
- **DECLARE NA PECA qual via esta aplicando** — judicial (CPC) ou extrajudicial (art. 216-A da LRP). Escolher a via no botao resolve o roteamento; **declarar por escrito protege quem le a peca depois**, porque os requisitos de instrucao e o onus da prova **nao sao os mesmos** nas duas.
- **A usucapiao nao conserta posse derivada** — arrendatario, parceiro e comodatario nao usucapem, por mais longo que seja o tempo. Dizer o contrario e vender acao perdida.
- **O teto de 50 ha e constitucional** e nao comporta leitura elastica; area maior migra para a extraordinaria, **com prazo maior** — o cliente precisa saber disso antes de contratar.
- 🟡 **A confirmar, rotear ao `validador-agrario`:** o **artigo do Provimento CNJ 149/2023** sobre usucapiao extrajudicial rural — as fontes divergem entre art. 401, §3º e art. 416, III. **NAO cite numero de artigo**; o **conteudo** (CAR, CCIR e certificacao do INCRA quando ha georreferenciamento) e seguro.
- 🔴 **Georreferenciamento:** nao crave 2029 na peca — materia ⚠️ **pendente** (proc. **1086967-47.2025.4.01.3700**, JF/MA, fonte secundaria); as **4 declaracoes** sao obrigatorias (`georreferenciamento-e-certificacao`).
- ⛔ **Sem prova de produtividade e de moradia nao ha especial rural.** Improcedencia por prova fraca custa mais que adiar para instruir melhor.

## Cross-link soft + fechamento
Diagnostico do imovel -> `due-diligence-de-terras-rurais`. Memorial -> `georreferenciamento-e-certificacao`. Terra publica ou devoluta -> `terras-devolutas-e-discriminatoria`. Titulo publico -> `regularizacao-fundiaria-rural`. Posse contratual e preferencia -> `contrato-arrendamento-rural` e `preferencia-do-arrendatario`. Esbulho coletivo -> `possessorias-rurais-e-conflito-coletivo`. Rito -> `base-processual-agraria`. Usucapiao **urbana** -> `direito-imobiliario-adv-os` (soft).

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
