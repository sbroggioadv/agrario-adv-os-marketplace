---
name: estilo-agrario
description: "Define a voz, a estrutura e o enderecamento das pecas e contratos do plugin agrario, e carrega o CHECKLIST ANTI-DESATUALIZACAO que impede o folclore de balcao: quotas de parceria do ET art. 96 VI de 2007 (nunca o decreto de 1966), gatilhos da MP 1.376 sempre cumulativos, sub-rogacao x extincao por hipotese, georreferenciamento declarado sub judice, Sumula 298 com requisitos, execucao de CPR fisica x financeira por vias distintas. Usa o vocabulario do agro (modulo fiscal, safra, quota, barter, integracao, CCIR, CAR) sem jargao de balcao. Use sempre que outra skill for redigir peca, contrato, requerimento ou parecer agrario. Acionada internamente pelas skills de redacao."
---

# ESTILO-AGRARIO

> Camada 0 / transversal. Camada de estilo, consultada pelas skills de redacao **antes** de entregar. Garante que nenhuma peca saia com dispositivo revogado, prazo trocado ou promessa que a lei nao sustenta.

## Anexos obrigatorios (context/)
- `context/metodologia-agraria.md` — terminologia e regras de ouro do plugin.
- `context/estatuto-e-decreto-contratos-agrarios.md` — a **tabela de desalinhamento** entre o Estatuto e o Decreto (conferir antes de citar qualquer artigo do Dec. 59.566/66 — **grep o artigo e leia a faixa**).
- `context/jurisprudencia-agraria.md` — selo ✅ antes de citar precedente (**grep o numero e leia a faixa**).

## Objetivo
Padronizar tom, estrutura e enderecamento, e rodar o checklist anti-desatualizacao em toda producao, para que a peca chegue ao gate `suprema-corte-agraria` sem erro de vigencia.

## Quando ativar
Sempre que uma skill de redacao for produzir contrato, peticao, defesa administrativa, requerimento ao agente financeiro, dossie ou parecer.

## ✅ CHECKLIST ANTI-DESATUALIZACAO (rodar em TODA peca, antes de entregar)
1. **Quota de parceria?** Usar **ET art. 96, VI — 20/25/30/40/50/75** (red. Lei 11.443/2007). 🔴 **NUNCA** o art. 35 do Dec. 59.566/66 (10/20/30/50/75, texto de 1966 exibido pelo Planalto). O desalinhamento e **estrutural**: a faixa **nova** "terra preparada" (25%) desloca as demais **um degrau**, e nas quatro primeiras o decreto subestima a quota em um degrau inteiro — conferir qual **aporte** corresponde a qual quota, nao so trocar a lista. Quota estourada **anula a avenca** e gera consignacao com custas contra quem cobrou a mais (Dec. 35, §3º).
2. **Prazo minimo de arrendamento?** **art. 13, II, "a"** (3/5/7 anos). 🔴 Nao o art. 21, que so presume 3 anos no prazo indeterminado.
3. **Preco do arrendamento?** Teto de **15%/30% do valor CADASTRAL** (ET 95, XII + Dec. 17), correcao anual (Dec. 16 §1º). 🔴 **Vedado fixar em quantidade fixa de frutos** (Dec. 18 p.u.) — "contrato em sacas" e pratica contra texto expresso; frutos so como forma de pagamento equivalente.
4. **MP 1.376/2026?** 🟡 **PENDENTE** de conversao (Comissao Mista — pode ter sido convertida, rejeitada ou caducado; rechecar). Escrever os gatilhos com **"E"**, nunca "ou": geral = 2+ safras **E** queda >=30% da **renda bruta agropecuaria esperada**; excepcional = 3+ safras **E** queda >=40% da **renda bruta agropecuaria esperada** **por evento climatico extremo**. Declarar a janela de **120 dias** (~11/11/2026, data de seguranca) e a **responsabilidade solidaria do tecnico** que assina o laudo (art. 9º §1º).
5. **Transferencia do imovel?** Declarar a **hipotese**: alienacao voluntaria ⇒ **sub-rogacao** (ET 92 §5º + Dec. 15); **perda** da propriedade ⇒ **extincao** sem sub-rogacao (Dec. 26, VIII + REsp 2.187.412-MT). 🔴 Nunca aplicar uma pela outra.
6. **Georreferenciamento?** Nunca cravar 21/10/2029. Fazer as **4 declaracoes**: Dec. 12.689/2025 (prazo unico vigente); 🟡 **sub judice** liminar noticiada no proc. **1086967-47.2025.4.01.3700** (recorte de 101 ha, **nao confirmada em fonte primaria**); via do CNJ (Prov. 195/2025 — no registral segue exigivel); verificar na data do atendimento.
7. **Prorrogacao de divida?** **Sumula 298/STJ** sempre com os requisitos cumulativos (prova do prejuizo, capacidade futura de pagamento, **pedido formalizado antes do vencimento**). 🔴 Proibido escrever "alongamento automatico" ou "direito automatico".
8. **Preferencia do arrendatario?** **30 dias** (ET 92 §3º + Dec. 45) e teste do "homem do campo" (Dec. 38). 🔴 Nunca 180 dias (CC 504, entre condominos) e **jamais o REsp 1.870.836-RS** (coerdeiro — armadilha de homonimo). O **registro do contrato e dispensavel** (AgRg no REsp 717.860-RS).
9. **Execucao de titulo rural?** **CPR fisica ⇒ entrega de coisa incerta** (L8929 art. 15); **CPR financeira ⇒ quantia certa** (art. 4º-A §2º). A lei chama a CPR de "titulo liquido e certo"; quem e "titulo executivo extrajudicial" pela lei e a **CIR** (L13986 art. 21).
10. **Rito do art. 86 do decreto?** Remete ao **art. 685 — morto** (o texto nao nomeia o CPC; 1939 e 1973 estao ambos revogados). Hoje, procedimento comum do CPC/2015; nao existe "sem efeito suspensivo" por essa via.
11. **Ambiental?** Defesa em **20 dias**; PRA por **notificacao** (1 ano), nao por data de calendario; descontos vigentes **40 · 35 · 60 · 50** por modalidade e momento **+ 30% a vista**; 🔴 **nao cabe recurso ao CONAMA** (art. 130 revogado).
12. 🔴 **O numero do artigo colide entre diplomas? Diga de qual lei ele e — na propria linha.** Erro de **etiqueta**, nao de conteudo: a citacao parece bem formada, tem numero e nome de lei, e por isso escapa da revisao rapida. Em peca, vira municao da contraparte. Casos mapeados:
    - **Tres `art. 15-A`** — juros compensatorios na desapropriacao = **DL 3.365/41** (chega pela ADI 2.332) · embargo ambiental = **Dec. 6.514/2008** · adimplemento financeiro na regularizacao fundiaria = **Lei 11.952/2009**. ⚠️ **`grep "art. 15-A"` devolve o ambiental primeiro** — o buscador nao desambigua por voce.
    - **`art. 10` e `art. 12`: LC 76/93 x Lei 8.629/93** — na LC sao **acordo homologado** e **sentenca**; na 8.629 sao **area nao aproveitavel** e **justa indenizacao com Laudo/ART**. Sao os dois artigos mais citados do plugin, e o proprio anexo da LC abre com esse aviso. **Nas skills de desapropriacao, todo art. 10 e todo art. 12 vao com o diploma colado.**
    - **`art. 13`** colide em **pelo menos cinco** diplomas do corpus (contados por comando, lista nao exaustiva): **LC 76/93** (efeito da apelacao) · **Estatuto da Terra** (13, II, "a" — prazos minimos 3/5/7) · **Lei 8.929/94** (entrega antecipada com anuencia do credor) · **Lei 13.986/2020** (30 dias para correcao) · **DL 167/67** (amortizacoes periodicas).
    - **`art. 96`** — as **quotas do ET 96, VI** x autuacao ambiental. Aqui o erro **anula a avenca**, entao a etiqueta e a diferenca entre a peca e o prejuizo.
    ⚠️ **A lista acima nao esgota o corpus, e cada anexo novo cria colisao nova.** Na duvida, nomeie o diploma sempre — custa tres palavras.
13. **Toda citacao passou pelo `validador-agrario`?** Sem selo, sai da peca ou entra como "a confirmar".

## Enderecamento correto (nao confundir a via)
- **Requerimento de enquadramento na MP 1.376 / prorrogacao** -> ao **agente financeiro**, com dossie de perda anexo (via extrajudicial, antes do judicial).
- **Defesa e recurso ambiental** -> a autoridade que lavrou o auto e depois a instancia superior do orgao; **duas instancias administrativas e ponto**.
- **Peticao inicial judicial (CPC 319)** -> juizo competente: **Justica Federal** quando ha INCRA, Uniao ou IBAMA e na discriminatoria (Lei 6.383/76 art. 19); **Justica Estadual** nas demais.
- **Recuperacao judicial** -> juizo do principal estabelecimento; instruir com o dossie do **Prov. CNJ 216/2026**.
- **Recursos** -> tribunal competente; REsp/RE ao presidente ou vice da origem.

## Estrutura padrao por tipo
- **Contrato agrario:** qualificacao das partes e do imovel (matricula, area, modulos fiscais, CCIR, CAR) + objeto + prazo + preco/quota **dentro do teto legal** + clausulas obrigatorias do Dec. 12 + clausulas irrenunciaveis do art. 13 + benfeitorias e retencao + preferencia + foro. Lembrar: **clausula contraria e nula de pleno direito** (Dec. 2º p.u.) e o **contrato verbal vale**.
- **Peca judicial:** enderecamento + partes + qualificacao do imovel + fatos + fundamentos (dispositivo vigente + precedente ✅) + tutela quando cabivel + pedidos + valor da causa + provas.
- **Defesa administrativa ambiental:** orgao + identificacao do auto + tempestividade (20 dias) + nulidades (descricao clara e objetiva, art. 97; coordenadas do embargo, art. 16 §1º) + merito + pedido + protesto por provas.
- **Parecer:** pergunta + premissas de fato + analise + **riscos e o que a tese nao garante** + recomendacao com prazo.

## Tom e vocabulario
Tecnico, objetivo, assertivo, de engenheiro-advogado. Vocabulario do agro correto: **modulo fiscal** (nao "modulo rural", nao MEI — que aqui e Modulo de Exploracao Indefinida, L5709 art. 3º, nunca Microempreendedor Individual), **quota** da parceria, **safra**, **barter**, **integracao** (CADEC e DIPC, nunca "CODEC"), **CCIR**, **CAR**, **GUT/GEE**. **Sem promessa de resultado** (Codigo de Etica da OAB). Racha declarado no corpo da peca, nao escondido.

## Guard
Toda citacao passa por `validador-agrario`; a peca fecha por `suprema-corte-agraria` (R1-R4). Peca que falha em qualquer item do checklist volta para correcao — nao se entrega com ressalva verbal.
