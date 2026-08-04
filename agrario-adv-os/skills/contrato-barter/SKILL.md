---
name: contrato-barter
description: "Redige e blinda a troca de insumo por safra instrumentalizada em CPR fisica, com o risco de preco explicitado no contrato. Carrega o art. 11 da Lei 8.929/94 na redacao da Lei 14.112/2020 — nao da Lei do Agro — que poe a CPR fisica com antecipacao de preco e o barter FORA da recuperacao judicial, com direito a restituicao, tendo como UNICA excecao o caso fortuito ou forca maior comprovado. Ancora no REsp 2.178.558-MT (3a Turma, 09/09/2025, Info 867) e declara o racha com o TJ/GO. Use quando o operador disser contrato de barter, troca de insumo por soja, o produtor nao entregou os graos, a trading quer executar o barter, o produtor entrou em recuperacao judicial e tem barter, a soja caiu e o barter ficou caro, isso entra ou nao na recuperacao."
---

# CONTRATO-BARTER — insumo por safra, e a porta de saida da RJ

> Camada 2. O barter nao e tipo contratual proprio: e **permuta** instrumentalizada por **CPR com liquidacao fisica**. E essa forma que produz o efeito mais valioso do agro em 2026 — **ficar fora da recuperacao judicial** — e que se perde quando o instrumento e mal escolhido.

## Quando ativa / trilha
Pela `triagem-agraria` na trilha contrato (redacao) **ou** na trilha divida quando ja ha inadimplemento, execucao ou RJ. Roda depois de `base-credito-rural-e-lei-do-agro`.

**Fronteiras:** requisitos e registro da CPR em geral -> `cpr-emissao-e-formalizacao` · executar -> `execucao-de-cpr-e-cedula-rural` · defender o executado -> `embargos-a-execucao-de-cpr` · sujeicao de creditos no processo de RJ -> `rj-sujeicao-de-creditos-agro` · insumo dentro de **sistema de integracao** (aves, suinos) -> `contrato-integracao-vertical`.

## Anexos obrigatorios (context/)
- `context/lei-do-agro-e-cpr.md` (**§1 CPR — grep "art. 11" e leia a faixa inteira**; arts. 3º, 5º, 8º, 12, 13, 15 e 18).
- `context/jurisprudencia-agraria.md` (§4 credito e CPR — **REsp 2.178.558-MT**; **§10 RACHAS**; §12 o que nao tem numero).
- `context/cpc-agrario.md` (§9 art. 784 e seu 🟡 · §10.2 entrega de coisa **incerta** · §2.4 foro — **grep o artigo e leia a faixa**).
- `context/rj-produtor-rural.md` (restituicao e extraconcursalidade — **grep e leia a faixa**).

## Base legal ancorada

### ⭐ O nucleo — Lei 8.929/94, art. 11, red. Lei 14.112/2020 ✅🔴
**Nao se sujeitam aos efeitos da recuperacao judicial** os creditos e as garantias cedulares vinculados a **CPR com liquidacao fisica**, em caso de **antecipacao parcial ou integral do preco**, **ou** representativa de **operacao de troca por insumos (barter)**, subsistindo ao credor o **direito a restituicao** desses bens que estiverem em poder do emitente **ou de qualquer terceiro**, **salvo motivo de caso fortuito ou forca maior** que comprovadamente impeca o cumprimento parcial ou total da entrega.

🔴 **Dois pontos que quase todo material erra:**
1. **Quem reescreveu o art. 11 foi a Lei 14.112/2020** (reforma da recuperacao judicial), **nao a Lei do Agro (13.986/2020)**. Atribuir a autoria a Lei do Agro e a armadilha nº 11 da tabela do plugin.
2. **A redacao vigente INVERTEU a logica anterior.** Antes, o caso fortuito e a forca maior eram **vedados** ao emitente como escusa; hoje sao a **unica excecao** que traz o credito **de volta** para dentro da RJ. Quem redige pela redacao antiga entrega ao cliente o oposto do que a lei diz.

### O precedente — REsp 2.178.558-MT ✅🔴
**3a Turma, Rel. Min. Ricardo Villas Boas Cueva, julgado em 09/09/2025, DJEN 15/09/2025, Informativo 867.** Destaque: o credito de **CPR vinculada a operacao barter nao se submete a RJ mesmo quando ha conversao da execucao para entrega de coisa incerta em execucao por quantia certa** — e a conversao **nao e renuncia ao penhor agricola**. Fecha a porta de abuso em que bastaria ao devedor **dar outra destinacao aos graos** para arrastar o credor para dentro do concurso.

⚠️ **Duas precisoes:** **07/10/2025 e a data da NOTICIA do STJ**, nao do julgamento — nao cite as duas como se fossem dois julgados. E a **Lei 14.112/2020 alcanca CPR emitida antes dela**: o que importa e o momento da **classificacao do credito na RJ**, nao o da emissao.

### ⚔️ Racha declarado — nao escolha um lado como pacifico
A extraconcursalidade da **CPR fisica e do barter** e ✅. **Mas** ha decisao do **TJ/GO** reconhecendo natureza **concursal** da **cedula rural financeira**, e o proprio **ACT CNJ-MAPA 013/2026** registra que **persistem divergencias entre tribunais** sobre quais creditos do agro se sujeitam a RJ. **Declare a divergencia na peca** — a verdade vigente aqui inclui o racha.

### Formalizacao que sustenta o efeito ✅
O efeito do art. 11 depende de o instrumento ser **CPR fisica bem constituida**. Grep no anexo e confira:
- **Art. 3º — 10 requisitos formais** (contados no anexo). O **inciso IV** exige a promessa de entrega **com o LOCAL ONDE SERA DESENVOLVIDO O PRODUTO RURAL** — exigencia de 2020, gancho de nulidade subutilizado dos dois lados.
- **Art. 5º — clausula ABERTA.** ⛔ Citar "art. 5º, I, II e III (hipoteca, penhor, alienacao fiduciaria)" e citar dispositivo **revogado desde 2020**.
- **Art. 12 — registro em entidade autorizada pelo BCB**, sob pena de perder validade e eficacia: **30 dias uteis** para CPR emitida **a partir de 11/08/2022** (10 dias uteis ate 10/08/2022). **§2º: cartorio DISPENSADO para o titulo**; ao RI vao as **garantias reais**.
- **Art. 8º, §2º:** **beneficiamento e transformacao NAO extinguem o vinculo real** — ele segue aos produtos e subprodutos; e o que derruba a defesa de "os graos viraram farelo". **Art. 18:** bens vinculados **nao penhorados por outras dividas**. **Art. 13:** entrega antecipada **so com anuencia**. **Art. 15:** a via da CPR fisica e a **entrega de coisa incerta**.
- **Foro:** vale a regra nova do **CPC art. 63, §1º (red. Lei 14.879/2024)** — pertinencia territorial obrigatoria, e o **§5º** torna o juizo aleatorio declinavel **de oficio**. Eleja a comarca do imovel ou a do local de entrega.

### O risco que gera o litigio — preco
A raiz economica do contencioso de barter e a **assimetria de preco**: o insumo e precificado na assinatura, o produto na entrega. Saca desvalorizada na liquidacao transforma a troca em divida real muito maior. **Escreva isso no contrato**: relacao de troca, preco-base de referencia, mecanismo de ajuste ou trava, e o que acontece na quebra de safra. Silencio sobre preco nao protege o produtor — transfere a discussao para o processo.

## Passo a passo / o que produzir
1. **Definir lado e fase** (AskUserQuestion, botoes): **produtor x fornecedor/trading** · **redacao · inadimplemento · execucao · RJ**.
2. **Confirmar a especie:** CPR **fisica** (a que atrai o art. 11) ou **financeira**? Trocar as duas destroi o efeito extraconcursal e erra a via de execucao.
3. **Auditar a formalizacao:** requisitos do art. 3º (com o **local** do inciso IV), garantias pelo art. 5º aberto, **registro em entidade do BCB no prazo**, garantias reais averbadas no RI.
4. **Escrever a equacao de preco:** relacao de troca, referencia, ajuste, quebra de safra, e a **clausula de caso fortuito e forca maior** — e ela que define a unica porta de retorno a RJ.
5. **Na RJ:** do lado do credor, sustentar a extraconcursalidade pelo art. 11 + REsp 2.178.558-MT, pedir **restituicao** e **declarar o racha**; do lado do produtor, a tese viavel nao e "esta na RJ", e **caso fortuito ou forca maior comprovado** — o que exige o dossie de frustracao de safra.
6. **Entregar:** minuta (ou peca) + quadro "requisito -> cumprido? -> efeito sobre a extraconcursalidade".

## Postura honesta
- **A extraconcursalidade nao e escudo automatico do credor nem condenacao do produtor.** Depende de **CPR fisica** formalizada e registrada, e cede diante de **caso fortuito ou forca maior comprovado**. "Barter nunca entra na RJ" e meia verdade.
- **O racha e real** (TJ/GO na cedula rural financeira; ACT 013/2026 reconhecendo divergencia entre tribunais). Apresentar o tema como pacifico custa credibilidade na primeira contraminuta.
- **Do lado do produtor, o caso fortuito exige PROVA** — laudo, dados climaticos, producao verificada. Sem dossie a tese e retorica; monte-o em `prova-de-frustracao-de-safra-e-vistoria`.
- 🟡 **Sem numero confirmado — "a confirmar" e rotear ao `validador-agrario`:** **prescricao da CPR** (prazo nao ancorado no plugin) · **conflito de garantias sobre a mesma safra** (penhor x CPR x alienacao fiduciaria) e **boa-fe do terceiro adquirente de safra gravada** — bloco inteiro sem numero · **inciso do CPC art. 784**: nenhum dos incisos contem "cedula", "CPR" ou "produto rural" — **cite o artigo, nunca o inciso**; a executividade vem de lei especial.
- ⛔ A Lei 8.929/94 **nunca** chama a CPR de "titulo executivo extrajudicial" — diz **"titulo liquido e certo"**. Quem a lei chama assim e a **CIR** (Lei 13.986/2020, art. 21).

## Cross-link soft + fechamento
Emissao e registro -> `cpr-emissao-e-formalizacao`. Execucao -> `execucao-de-cpr-e-cedula-rural`. Defesa do produtor -> `embargos-a-execucao-de-cpr`. Sujeicao de creditos -> `rj-sujeicao-de-creditos-agro`. Dossie de perda -> `prova-de-frustracao-de-safra-e-vistoria`. Venda de safra sem troca de insumo -> `compra-venda-de-safra-e-armazenagem`. Tributo -> `tributacao-dos-contratos-agrarios`.

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
