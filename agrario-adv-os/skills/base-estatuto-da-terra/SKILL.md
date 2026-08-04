---
name: base-estatuto-da-terra
description: "Fundacao normativa dos contratos agrarios: entrega o texto VIGENTE do Estatuto da Terra (Lei 4.504/64, arts. 92-96 e 95-A) e do Decreto 59.566/66 com o mapa do desalinhamento entre os dois — quota de parceria, prazos minimos, preco, renovacao, despejo, preferencia, benfeitorias e extincao. Fixa qual dos dois prevalece e barra o dispositivo morto antes que ele entre na peca. Nao redige contrato: sustenta quem redige. Use antes de skill de contrato agrario ou de contencioso do contrato, ou quando o operador disser qual e a quota da parceria, qual o prazo minimo, onde esta a preferencia, vale o Decreto ou o Estatuto, posso citar o art. 35, existe art. 96-A, contrato verbal vale, pode fixar em sacas."
---

# BASE-ESTATUTO-DA-TERRA — Fundacao dos contratos agrarios (ET x Dec. 59.566/66)

> Camada 1. Nao redige: entrega o texto **vigente** e diz **qual dos dois diplomas prevalece**. O Estatuto foi alterado pela **Lei 11.443/2007**; o Decreto **nunca foi formalmente alterado** e o Planalto o exibe em texto de 1966. Esse desencontro e o valor desta camada, nao um defeito dela.

## Quando ativa / trilha
Entra **antes ou junto** de toda skill de C2 (contratos) e de C7 (despejo, preferencia, revisao e consignacao), depois de `triagem-agraria`. O `agrario-master` dispara as cinco de C1 como passo de "nao esquecer nada".

**Diferenca da vizinha:** `contrato-arrendamento-rural` **redige a minuta**; esta skill diz **qual dispositivo entra nela**.

## Anexos obrigatorios (context/)
- `context/estatuto-e-decreto-contratos-agrarios.md` (§1 quotas e desalinhamento · §2-§4 ET 92-96 · §5 Decreto arts. 1º-48, 84, 88 · §6 divergencia dos 30 dias · §8 sub-rogacao x extincao · §9 armadilhas — **grep o artigo e leia a faixa**).
- `context/jurisprudencia-agraria.md` (§2 armadilha do REsp 1.870.836-RS e os quatro institutos de preferencia — **grep o numero e leia a faixa**).
- `context/metodologia-agraria.md` (§1 regra de leitura · §3 camadas).

## Base legal ancorada

**Precedencia, decida primeiro:** quota **-> ET 96, VI** (lei posterior sobre decreto anterior) · procedimento **-> Decreto** · rito do art. 86 **-> nenhum dos dois** 🔴, morto (ver `base-processual-agraria`).

### Quotas — ET art. 96, VI ✅ — teto da **quota do proprietario na participacao dos frutos** (20 / 25 / 30 / 40 / 50 / 75%)
a) 20% terra nua · b) **25% terra preparada** · c) 30% terra preparada e moradia · d) 40% conjunto basico de benfeitorias · e) 50% terra preparada + conjunto basico + maquinas, sementes e animais de tracao (ou pecuaria com cria > 50%) · f) 75% pecuaria ultra-extensiva. Quota adicional maxima **10%**: cite o **inciso IX** (texto de 2007), nao a alinea "g".

🚨 **O desalinhamento e ESTRUTURAL, nao numerico.** A Lei 11.443/2007 criou a faixa **"terra preparada" (25%)**, inexistente no Decreto, e ela **desloca todas as demais em um degrau**: "conjunto basico" era 30% no art. 35 e e **40%** hoje. Ler a tabela do Decreto **subestima a quota em um degrau inteiro**.

**Sancao — Dec. art. 35, §3º ✅:** nao valem as avencas que contrariem os percentuais; cabe **consignacao judicial da cota**, com **riscos, despesas, custas e honorarios por conta do infrator**. Use a **sancao do Decreto com o teto do Estatuto**: o §3º afere contra "este artigo" (o 35, morto), mas o parametro vigente e o art. 96, VI.

### Estatuto da Terra ✅ — as ancoras que decidem caso
**Art. 92:** §3º preferencia em **30 dias** · §4º adjudicacao **depositando o preco** em **6 meses da transcricao** · §5º alienacao **nao interrompe** (adquirente **sub-rogado**) · §7º fraude -> **taxas minimas da regiao** · §8º **a ausencia de contrato nao elide** os principios.
**Art. 95:** IV renovacao (notificacao ate 6 meses antes + os 30 dias — ver Postura honesta) · V retomada · VIII benfeitorias uteis e necessarias + **direito de retencao** · XII teto de **15% do valor cadastral**, ate **30%** em gleba intensiva. ⚠️ **95-A existe; 96-A NAO** — apos o 96 vem o 97.
**Art. 96:** I 3 anos se nao convencionado · VIII fertilizantes **a preco de custo** · IX quota adicional de ate 10%.
- **§1º teste dos 3 riscos** (nucleo anti-simulacao): partilha, **isolada ou cumulativamente**, de caso fortuito e forca maior · frutos, produtos ou lucros · **variacao de precos**. Sem partilha de risco nao ha parceria.
- **§2º** prefixacao valida **so com ajuste final conforme a producao**; **§3º** adiantamento **nao descaracteriza**; **§4º** direcao **exclusiva do proprietario** = **locacao de servico regida pela CLT** (espelho no art. 84); **§5º** **aves, suinos e agroindustrial estao FORA** do art. 96 -> **Lei 13.288/2016**.

### Decreto 59.566/66 ✅ — o lado operacional
- **Art. 2º, p.u.:** ordem publica — estipulacao contraria e **nula de pleno direito**, nao anulavel (reforco no art. 13, I).
- **Arts. 7º, 8º e 38 — regua do "homem do campo":** exploracao direta e de quem **assume os riscos**; cultivo direto e pessoal exige **residencia no imovel** e mutua dependencia familiar. Base do teste da preferencia.
- **Art. 9º** sem CCIR **sob pena de nulidade** · **art. 11 o contrato verbal VALE** · **art. 12** os 11 incisos.
- **Art. 13, II, "a" — PRAZOS MINIMOS: 3 anos** (lavoura temporaria, pecuaria de pequeno e medio porte **e toda parceria**) · **5 anos** (lavoura permanente, pecuaria de grande porte) · **7 anos** (exploracao florestal). ⚠️ **Nao estao no art. 21**, que so traz a presuncao de 3 anos.
- **Preco:** art. 17 §1º **15% da terra nua**, §2º **30%** no parcial; **art. 18, p.u.: VEDADO ajustar como preco quantidade fixa de frutos** — o "contrato em sacas" e pratica contra texto expresso (PL 3887/23 **nao e lei**); **art. 19** moeda corrente diante de preco abaixo do regional ou de fraude.
- **Art. 22:** notificacao ate **6 meses** antes; **§3º** notificacao, desistencia e proposta se fazem **por carta pelo RTD da comarca do imovel OU por requerimento judicial** — **duas vias, nao uma**; **§4º** insinceridade gera perdas e danos.
- **Arts. 24-25** detalham benfeitorias e retencao (ancora ja no ET 95, VIII) — **grep no anexo §5**.
- **Art. 26** 10 causas de extincao, entre elas **VIII, perda do imovel** · **art. 28 ⭐** verbatim: ele permanece **"ate o termino dos trabalhos que forem necessarios a colheita"** (mais largo que "ate o fim da colheita" — nao encurte) · **art. 32** **9 hipoteses taxativas de despejo**, purga da mora no III · **art. 39** trava anti-atipicidade.
- **Arts. 45-47 preferencia:** **30 dias** (45); com varios arrendatarios so **aquisicao total** (46); adjudicacao **depositando o preco** em **6 meses da transcricao** (47). ⚠️ O **art. 44** e outra coisa: trabalhos preparatorios entre quem sai e quem entra.

### Sub-rogacao x extincao — hipotese, nao escolha
| Hipotese | Efeito | Ancora |
|---|---|---|
| **Alienacao voluntaria** (venda, doacao) ou onus real | **NAO interrompe**; adquirente **SUB-ROGADO** | ET 92 §5º + Dec. **15** ✅ |
| **PERDA da propriedade** (decisao judicial, execucao, eviccao, expropriacao) | **EXTINGUE**, **sem** sub-rogacao | Dec. **26, VIII** + **REsp 2.187.412-MT**, 3a T, 10/02/2026, Info 879 🔴 |

⭐ **Extincao nao e saida imediata:** o **art. 28** mantem o arrendatario **"ate o termino dos trabalhos que forem necessarios a colheita"**. O REsp afasta a permanencia **ate o fim do prazo contratual** — nao esses trabalhos.

## Passo a passo / o que produzir
1. **Classificar**: arrendamento · parceria · figura atipica · aves e suinos (fora do art. 96).
2. **Rotear pela precedencia** — quota ao Estatuto, procedimento ao Decreto, rito a nenhum dos dois.
3. **Grep no anexo e ler a faixa** de cada dispositivo. Nunca citar de cabeca.
4. Havendo transferencia do imovel, **fixar a hipotese** (sub-rogacao x extincao) antes de fundamentar.
5. Rodar as armadilhas do **§9 do anexo** (as 50 vivem no `validador-agrario`, nao aqui).
6. **Entregar o quadro**: dispositivo · texto vigente · diploma que prevalece · faixa lida · selo (✅ / 🟡 / 🔴).

## Postura honesta
- **Divergencia viva do sujeito dos 30 dias na renovacao:** **ET 95, IV** diz "**o arrendador**"; **Dec. 22, §1º** diz "**o arrendatario**". A troca e **literal, verificada nos dois compilados**, e **sem jurisprudencia pacificadora confirmada**. **Nao resolva por conta propria** — declare como controverso e argumente com o texto que favorece o cliente.
- 🟡 **Sem numero confirmado** (marcar "a confirmar" e rotear ao `validador-agrario`): termo inicial dos 6 meses · **deposito do preco** na adjudicacao — **texto legal ✅** (ET 92 §4º e Dec. 47), **jurisprudencia nao** · requisitos da notificacao · preferencia na **renovacao** (ET 95) · **parceria simulada** · comodato rural (CC 579-585 nao lidos; a fronteira e a **gratuidade**).
- ⛔ **Nao existe sumula nem repetitivo do STJ sobre preferencia do arrendatario** — nao invente numero; o **REsp 1.870.836-RS** e de **coerdeiro** (CC 1.795). E o Decreto **nao foi corrigido em 2007**: o art. 35, §3º invalida as **avencas de participacao que contrariem os percentuais** (parametro vigente = ET 96, VI) — nao a mera citacao do dispositivo antigo.

## Cross-link e fechamento
Minuta -> C2; aves e suinos -> `contrato-integracao-vertical`. Ponte do art. 9º §4º -> `base-funcao-social-e-reforma-agraria`. Rito -> `base-processual-agraria`. Precedentes -> `jurisprudencia-agraria`. Registral **urbano** -> `direito-imobiliario-adv-os` (soft).

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
