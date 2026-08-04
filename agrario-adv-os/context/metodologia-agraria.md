# Metodologia do plugin agrario-adv-os

> Anexo mestre do plugin **agrario-adv-os**. O "como pensar" antes do "o que escrever": pilares, mapa das 10 camadas, árvore de triagem, as 12 verdades duras, a regra de distinção e o contrato de anti-alucinação.
> É o arquivo que o `agrario-master`, o `anti-alucinacao-agraria`, o `validador-agrario` e a `suprema-corte-agraria` consultam para não escorregar.
> **Captura das fontes:** Planalto, STJ, STF, CNJ, INCRA e Receita Federal, em **02/08/2026**.

---

## 1. ⛔ A REGRA DE LEITURA DOS ANEXOS (vale para TODAS as skills)

**Faça `grep` do dispositivo e leia a FAIXA. Nunca despeje um anexo inteiro no contexto.**

Formato do ponteiro dentro de cada skill:

```
`context/<arquivo>.md` (arts. X e Y — grep o artigo e leia a faixa)
```

**Por quê:** os anexos são densos de propósito. Carregar um arquivo inteiro para citar um artigo desperdiça contexto, dilui a atenção e aumenta a chance de a skill puxar um dispositivo revogado que estava na tabela histórica ao lado do vigente.

**Toda skill referencia pelo menos um anexo.** Nunca cite dispositivo "de cabeça": **o anexo é a prova**.

---

## 2. OS PILARES (herança da família Adv-OS)

1. **Porta única** — todo caso entra pelo `agrario-master`, que triara e roteia. Toda peça fecha pela **`suprema-corte-agraria` (R1-R4)** + **`validador-agrario`**.
2. **Standalone-first** — CPC filtrado internamente (`base-processual-agraria`) e recursos modelados no cível **sem dependência dura**. O plugin funciona sozinho; zero dependência de API em runtime.
3. **Anti-alucinação por design** — nenhum dispositivo, súmula, tema, provimento, resolução ou prazo entra em peça sem âncora no `context/`. Itens 🟡 entram **sempre** como "a confirmar", nunca como fato.
4. **Lei VIGENTE 2026** — a captura de fonte oficial **supera o treino do modelo**. Este domínio tem seis normas pós-corte que mudam o resultado do caso.
5. **Postura honesta** — rachas e pendências **declarados**, nunca escondidos. Promessa fácil é **defeito**, não venda.
6. **Despersonalizado** — autoria **IA Combativa**; o escritório do cliente é configurado em runtime via `/start-agrario`.

---

## 3. O MAPA DAS 10 CAMADAS

| Camada | Escopo | Skills |
|---|---|---|
| **C0 — Orquestração / QA (8)** | porta única, triagem, memória, estilo e as duas travas de qualidade | `agrario-master` · `suprema-corte-agraria` · `agrario-onboarding` · `triagem-agraria` · `memoria-de-caso-agraria` · `estilo-agrario` · `validador-agrario` · `anti-alucinacao-agraria` |
| **C1 — Fundação (5)** | a base que todas as demais citam | `base-estatuto-da-terra` · `base-funcao-social-e-reforma-agraria` · `base-credito-rural-e-lei-do-agro` · `base-processual-agraria` · `jurisprudencia-agraria` |
| **C2 — Contratos agrários (8)** ⭐ *o fosso* | arrendamento, parceria, integração, barter, safra, tributação | `contrato-arrendamento-rural` · `preco-prazo-e-renovacao-do-arrendamento` · `contrato-parceria-rural` · `descaracterizacao-e-figuras-atipicas` · `contrato-integracao-vertical` · `contrato-barter` · `compra-venda-de-safra-e-armazenagem` · `tributacao-dos-contratos-agrarios` |
| **C3 — Crédito, dívida e insolvência (12)** ⭐⭐ *o núcleo comercial* | CPR, cédulas, garantias, execução, revisional, prorrogação, MP 1.376 e RJ | `cpr-emissao-e-formalizacao` · `cedulas-de-credito-rural` · `garantias-do-credito-rural` · `patrimonio-rural-em-afetacao-e-cir` · `execucao-de-cpr-e-cedula-rural` · `embargos-a-execucao-de-cpr` · `revisional-de-credito-rural` · `prorrogacao-de-divida-rural` · `renegociacao-mp-1376` 🔴 · `rj-produtor-rural-inicial` · `rj-produtor-defesa-do-credor` · `rj-sujeicao-de-creditos-agro` |
| **C4 — Terras, registral e tributário rural (7)** | *due diligence*, georreferenciamento, usucapião, regularização, estrangeiros, ITR | `due-diligence-de-terras-rurais` · `georreferenciamento-e-certificacao` 🔴 · `usucapiao-rural-judicial-e-extrajudicial` · `regularizacao-fundiaria-rural` · `terras-devolutas-e-discriminatoria` · `aquisicao-de-terra-por-estrangeiro` · `itr-e-tributacao-da-terra` |
| **C5 — Desapropriação e reforma agrária (5)** | defesa na vistoria, rito, indenização, nulidades, indireta | `defesa-na-vistoria-e-laudo-de-produtividade` · `rito-lc-76-93-e-contestacao` · `indenizacao-tda-juros-e-honorarios` · `nulidades-do-processo-expropriatorio` · `desapropriacao-indireta` |
| **C6 — Ambiental do agro (6)** | CAR/PRA, APP/RL, auto de infração, embargo, licenciamento, TAC | `car-pra-e-termo-de-compromisso` 🔴 · `app-reserva-legal-e-areas-consolidadas` · `defesa-em-auto-de-infracao-ambiental` · `embargo-e-desembargo` · `licenciamento-e-dispensa-agropecuaria` 🔴 · `tac-e-responsabilidade-ambiental-rural` |
| **C7 — Contencioso possessório e do contrato (6)** | despejo, preferência (dois lados), revisão, possessórias, prova de perda | `despejo-agrario` · `preferencia-do-arrendatario` · `defesa-na-preferencia-adquirente` · `revisao-e-consignacao-do-arrendamento` · `possessorias-rurais-e-conflito-coletivo` · `prova-de-frustracao-de-safra-e-vistoria` |
| **C8 — Recursos standalone (4)** | modelados no cível, **sem dependência dura** | `apelacao-e-agravo-agrario` · `embargos-de-declaracao-agrario` · `recursos-excepcionais-agro` · `contrarrazoes-e-agravos-excepcionais` |
| **Transversal (3)** | parecer honesto, cruzamento e o relógio do agro | `parecer-agrario` · `protocolo-p4-agrario` · `calendario-safra-e-prazos-criticos` |

**C0 e C1 vêm primeiro** porque **todas as demais camadas fecham por elas**.

---

## 4. A ÁRVORE DE TRIAGEM — dívida primeiro

```
CASO
  │
  ▼
[PERGUNTA CRÍTICA]  (triagem-agraria)
  │  "HÁ DÍVIDA VENCIDA OU EXECUÇÃO EM CURSO?"
  │      └── SIM → entra pela C3 (núcleo comercial). NÃO PASSE ADIANTE.
  ▼
[SEIS TRILHAS]
  1. dívida / insolvência ......... C3
  2. contrato ..................... C2  (+ C7 se já há litígio)
  3. terra / registral ............ C4
  4. ambiental .................... C6
  5. desapropriação ............... C5
  6. possessória .................. C7
  ▼
[LADO]  (agrario-onboarding, por AskUserQuestion)
  produtor × credor/trading × adquirente/investidor
  + UF · tipo de exploração · porte em módulos fiscais
  ▼
[PEÇA]  (skill da trilha)
  ▼
[FECHAMENTO]  suprema-corte-agraria (R1-R4) + validador-agrario
  • R1 fatos / qualificação do imóvel (módulos fiscais, área, bioma, UF) e do sujeito (PF × PJ, produtor × empresário)
  • R2 fundamentação VIGENTE (quotas 2007 não 1966; 8.929 pós-14.421/2022; PRA pós-14.595/2023)
  • R3 prazos e dies a quo (30 dias preferência · 6 meses transcrição · 6 meses renovação · 20 dias defesa ambiental · 120 dias MP 1.376)
  • R4 forma / via / competência (adm × judicial; JF × JE; entrega de coisa × quantia certa)
```

**Toda escolha de lista fechada usa `AskUserQuestion`** — botões clicáveis, nunca "digite 1, 2 ou 3".

---

## 5. AS 12 VERDADES DURAS (o plugin vende a lei vigente, não o folclore de balcão)

Repita quando pertinente; **NUNCA contrarie**. O guard `anti-alucinacao-agraria` carrega estas mesmas 12.

1. **Quotas de parceria: o art. 35 do Decreto 59.566/66 está MORTO desde 2007.** Vigente: **ET art. 96, VI, red. Lei 11.443/2007 — 20/25/30/40/50/75%**. O Planalto exibe o decreto em texto de 1966 (10/20/30/50/75). ⚠️ **O desalinhamento é ESTRUTURAL, não é troca de lista:** a Lei 11.443/2007 **criou a faixa nova "terra preparada" (25%)**, que **desloca as faixas seguintes um degrau** — nas **quatro primeiras faixas** o Decreto **subestima a quota legítima em um degrau inteiro**. Não basta trocar a lista: é preciso **reconferir qual aporte corresponde a qual quota** (Dec. 35, §3º: quota errada anula a avença). **PROIBIDO citar o decreto para quotas.** Estourar a quota **anula a avença** (Dec. art. 35, §3º). → `context/estatuto-e-decreto-contratos-agrarios.md`

2. **MP 1.376/2026 — DOIS regimes, gatilhos CUMULATIVOS. Nunca "OU".** Geral (§1º+§4º): **2+ safras E ≥30%**, limites 400 mil/2 mi/4 mi, encargos **6/9/12%**, reembolso 8 anos. Excepcional (§7º): **3+ safras E ≥40%, por evento CLIMÁTICO** (queda de preço **não** entra), limites 500 mil/2,5 mi/8 mi, encargos **5/8/11%**, reembolso 10 anos. **Contratação em 120 dias** da publicação (15/07/2026): o **dia 120 = 12/11/2026**, mas o ***dies a quo* não está explícito na MP** — se a contagem incluir o dia da publicação, o termo final é 11/11/2026. **Trabalhe com 11/11/2026 como data de segurança e nunca prometa o dia 12 ao cliente.** ⚠️ **art. 9º, §1º: o profissional que assina o laudo responde SOLIDARIAMENTE.** → `context/mp-1376-2026.md`

3. **IBS/CBS alcançam o arrendamento rural** pela porta genérica de "arrendamento de bem imóvel" — a **LC 214/2025 não usa a expressão "arrendamento rural" uma única vez**. Gatilho da PF **cumulativo** (art. 251, §1º, I): **> R$ 240.000 E mais de 3 imóveis**. Alíquota reduzida em **70%**. **O redutor social de R$ 600/mês é SÓ residencial.** Os gatilhos dos arts. 164 e 251 são **independentes**. → `context/tributacao-rural.md`

4. **Súmula 298/STJ não é passe livre.** O enunciado é real e favorável, mas a base é a Lei 9.138/95 (alcance temporal contestado) e os tribunais exigem **requisitos cumulativos comprovados** — prova do prejuízo, capacidade futura de pagamento, **pedido formalizado ANTES do vencimento** conforme o MCR (**TJPR 0098700-19.2025.8.16.0000, j. 01/12/2025**). **PROIBIDO vender "alongamento automático".**

5. **Laudo de GUT/GEE com mais de 5 anos deve ser atualizado a pedido do proprietário** — Lei 8.629/93, **art. 6º, §9º, red. Lei 14.757/2023**. É a alteração **mais recente** da Lei 8.629. GUT ≥ **80%** · GEE ≥ **100%** · art. 7º (projeto técnico aprovado **6 meses antes da COMUNICAÇÃO DA VISTORIA**). → `context/lei-8629-93-e-cf-184-191.md`

6. **GEORREFERENCIAMENTO — SUB JUDICE. PROIBIDO afirmar 2029 como incontroverso.** É o item mais perigoso do plugin. **As 4 declarações, sem exceção:** (a) Dec. **12.689/2025** (prazo único 21/10/2029, revogou o escalonamento); (b) **questionamento judicial noticiado** — JF/MA, proc. **1086967-47.2025.4.01.3700**, recorte de **101 ha**, **fonte secundária, NÃO confirmada em primária**; (c) via do CNJ — **Prov. 195/2025**, no registral **permanece exigível**; (d) **verificar na data do atendimento**. → `context/registral-terras-e-estrangeiros.md`

7. **A RJ rural de 2026 não é pedido documental — é DOSSIÊ PROBATÓRIO TERRITORIAL.** **Prov. CNJ 216/2026**: biênio por documentos enumerados, admitido período **anterior ao registro mercantil**; **laudo das condições operacionais**; **declaração de garantias sobre safras presentes e futuras e semoventes**; **perspectiva de colheita**; o perito esclarece se a propriedade está **registrada em nome da recuperanda**; **constatação prévia** e **monitoramento contínuo**. Some **ACT CNJ-MAPA 013/2026** (VMG: satélite, clima, georreferenciamento) e **Prov. 231/2026**. → `context/rj-produtor-rural.md`

8. **A preferência do arrendatário NÃO é automática.** Exige perfil de **"homem do campo"** — exploração direta e pessoal, **residência no imóvel**, atividade familiar (**Dec. 59.566/66, arts. 38 e 8º**). **REsp 1.447.082-TO** afastou empresa rural de grande porte; **REsp 2.140.209** (acórdão publicado 08/09/2025) excluiu quem **não residia, tinha outros bens e era empresário agrícola**. ⚠️ **O modelo treinado tende a afirmar a preferência como direito quase incondicional — esse erro perde a causa.** Em contrapartida, **o registro do contrato na matrícula é DISPENSÁVEL** (**AgRg no REsp 717.860-RS**).

9. **Quatro divergências que o plugin DECLARA, não esconde:** (a) **CPR física e barter extraconcursais** (L8929 art. 11 + REsp 2.178.558-MT, **Turma**) **× TJ/GO** reconhecendo cédula rural financeira como **concursal**, com o **ACT 013/2026 reconhecendo o racha**; (b) **menos de 1/4 dos planos de RJ são cumpridos** 🟡; (c) **MP 1.376/2026 em Comissão Mista — o texto pode mudar**; (d) **ADIs contra a Lei 13.465/2017 NÃO julgadas** — o **voto** do Min. Dino foi noticiado como **resultado**, e **é erro grave repetir isso**.

10. **Estrangeiros: FECHADO pelo STF em 23/04/2026, por unanimidade.** **ADPF 342 + ACO 2.463** validaram o art. 1º, §1º da Lei 5.709/1971, mantendo a equiparação da **PJ brasileira controlada por estrangeiros** e a competência da **União**. A tese de que a **EC 6/1995 revogou** a equiparação **está superada**. **PL 2.963/2019 parado** (última movimentação 25/04/2024).

11. **O prazo de adesão ao PRA deixou de ser data de calendário.** Lei 12.651/2012, **art. 59, §2º, red. Lei 14.595/2023**: adesão requerida **no prazo de 1 ano contado da NOTIFICAÇÃO**, que pressupõe validação prévia do cadastro e identificação de passivos. **Sem notificação válida, o prazo NÃO CORRE** — e a proteção do §4º (não autuação por infrações anteriores a **22/07/2008**) continua de pé. **Não confundir com o art. 29, §4º** (31/12/2023 e 31/12/2025 = limites de **inscrição no CAR** para ter **direito**, ambos vencidos). → `context/codigo-florestal-12651.md`

12. **Existe Lei Geral do Licenciamento Ambiental em vigor, e ela DISPENSA a agropecuária.** **Lei 15.190/2025** — sancionada 08/08/2025 com 63 vetos, **52 derrubados em 27/11/2025**, promulgação 05/12/2025, **em vigor desde fevereiro/2026**. O **art. 9º** retira do licenciamento cultivo agrícola, pecuária extensiva e semi-intensiva, pecuária intensiva de pequeno porte e pesquisa agropecuária — **condicionado a imóvel "regular ou em regularização"**, e a alínea do **CAR pendente de homologação** foi **vetada e restabelecida**. ⚠️ **ADIs 7913/7916/7919 + ADC 102, SEM liminar, mérito pautado para 12/08/2026 — RECHECAR.** → `context/ambiental-administrativo.md`

---

## 6. ⭐ A REGRA DE DISTINÇÃO — sub-rogação × extinção (hipótese, não escolha)

Parecem contraditórias e não são. **A skill identifica a hipótese ANTES de responder.**

| Hipótese | Efeito | Âncora |
|---|---|---|
| **Alienação voluntária** (venda, doação) ou imposição de ônus real | **NÃO interrompe**; o adquirente fica **SUB-ROGADO** | ET art. 92, §5º + Dec. art. 15 ✅ |
| **PERDA da propriedade** (decisão judicial, execução, evicção, expropriação) | **EXTINGUE**, **sem** sub-rogação; o arrendatário **não** permanece até o fim do prazo | Dec. art. **26, VIII** + **REsp 2.187.412-MT**, 3ª T, Nancy Andrighi, **10/02/2026**, Info 879 🔴 |

**Nunca aplique uma pela outra.** O REsp é de **fevereiro de 2026** e quase certamente **não está em nenhuma base de treino**.
⚠️ **Nuance:** extinção **não** é saída imediata — o **art. 28 do Decreto** garante permanecer **até o término dos trabalhos necessários à colheita**.

**Duas skills carregam a distinção explicitamente:** `contrato-arrendamento-rural` e `despejo-agrario`.

---

## 7. AS ARMADILHAS QUE DERRUBAM PEÇA (trava do guard)

- 🚨 **REsp 1.870.836-RS é de preferência de COERDEIRO (CC 1.795, 180 dias) — NÃO é agrário. JAMAIS citar em peça agrária.** É armadilha de homônimo: o buscador o oferece para "preferência".
- **Preferência do arrendatário = 30 dias** (ET 92, §3º; Dec. 45). Os **180 dias são do CC art. 504**, preempção **entre condôminos**.
- **Não existe art. 96-A** no Estatuto (existe **95-A**); **não existe art. 12-A** na Lei 8.929/94.
- **Prazos mínimos 3/5/7 estão no art. 13, II, "a"** do Decreto — **não** no art. 21.
- **A Lei 8.929/94 nunca chama a CPR de "título executivo extrajudicial"** — diz "**título líquido e certo**". Quem a lei chama assim é a **CIR** (L13986 art. 21).
- **Súmula 408/STJ está CANCELADA** (28/10/2020, Pet 12.344). O **Tema 126** foi reescrito (**12% até 11/06/1997**). A **ADI 2.332 MANTEVE os 6%** (derrubou só a expressão "até" ⇒ 6% virou **piso**) e derrubou o **teto de honorários**.
- **ADPF 828: só há cautelar referendada (nov/2022). O mérito NUNCA foi julgado.**
- **Súmula 354/STJ trata da INVASÃO como causa de suspensão** — não de notificação prévia da vistoria. **Nenhuma súmula sobre notificação foi localizada: não inventar número.**
- **Não cabe recurso ao CONAMA** — art. 130 revogado pelo Dec. 11.080/2022.
- **O Dec. 11.373/2023 EXTINGUIU a conciliação ambiental** (revogou 97-A e 98-A) — **não a criou**.
- **Descontos ambientais vigentes: 40% · 35% · 60% · 50% + 30% à vista.** A tabela 60/50/40 do Dec. 9.760/2019 está **revogada**.
- **O rito do art. 86 do Dec. 59.566 está MORTO.** Hoje é o **procedimento comum do CPC/2015**.
- **Garantias da CPR: o art. 5º, I, II e III está REVOGADO desde 2020** — hoje é **cláusula aberta**.
- **FGS: "4% + 4% + 2%" revogado** pela Lei 14.421/2022.
- **Sem ADA não se exclui APP/RL do ITR: FALSO desde 24/07/2024** — o **CAR basta** (Lei 14.932/2024).

---

## 7.1 🚨 HOMÔNIMO DE CRITÉRIO — a classe de erro que NENHUM grep pega

Há **duas** classes de homônimo neste plugin. A primeira é de **numeração** (dois "art. 15-A", dois "art. 96") — essa o `audit/check-colisao-artigos.sh` detecta. **A segunda é de CRITÉRIO, e nenhuma ferramenta pega:** dois limites que convivem na mesma frase do cliente, **medidos em unidades que NÃO SE CONVERTEM**.

> ⛔ **HECTARE × MÓDULO FISCAL não são conversíveis.** O módulo fiscal **varia por município** (de poucos hectares a dezenas). Não existe fator fixo. Quem "converte" um no outro inventa número.

**O caso que originou o registro** — regularização fundiária (Lei 11.952/2009):

| Limite | Unidade | Dispositivo |
|---|---|---|
| **2.500 ha** | **ÁREA** | art. 6º, §1º — teto da **regularização** |
| **15 módulos fiscais** | **MÓDULO FISCAL** | **art. 16-A** — requisito da **extinção das cláusulas resolutivas** (via CCIR) |

**Critérios diferentes, dispositivos diferentes, unidades diferentes. Não os troque** — e não conclua que um imóvel que passa num passa no outro.

**Outros pares do corpus que sofrem do mesmo mal:**

| Contexto | Unidade A | Unidade B |
|---|---|---|
| Pequena propriedade × usucapião especial rural | **até 4 módulos fiscais** (L8629 art. 4º, II) | **≤ 50 hectares** (CF 191) |
| Imunidade do ITR | **100 / 50 / 30 hectares** por região (Lei 9.393, art. 2º, p.ú.) | — *(não é módulo fiscal)* |
| Estrangeiros | **50 MEI** — Módulo de Exploração Indefinida (Lei 5.709, art. 3º) | **≠ módulo fiscal ≠ módulo rural** — **três** unidades distintas |
| Geolocalização EUDR | **4 hectares** (limiar de polígono, art. 2º, ponto 28) | — *(nada a ver com módulo fiscal)* |
| Áreas consolidadas em APP | faixas em **metros** por **módulo fiscal** (art. 61-A) | teto em **% da área total** (art. 61-B) |

**Regra operacional:** ao ler qualquer limite, **anote a unidade junto do número**. Se a peça compara dois limites, confirme que estão **na mesma unidade** antes de concluir. Se não estiverem, **são testes independentes e cumulativos** — passar em um não dispensa o outro.

---

## 8. 🟡 CONTRATO DE ANTI-ALUCINAÇÃO — o que é PROIBIDO afirmar sem verificação

Cada item abaixo foi **buscado e NÃO confirmado** em fonte oficial. Marque "**a confirmar**" e roteie ao `validador-agrario`. **Nunca preencha número por memória** — é exatamente onde o modelo alucina com mais confiança.

- **Números de Resolução CMN** do Plano Safra 2026/2027 e a **Res. CMN 5.193/2024**.
- **Capítulo/seção do MCR** de prorrogação e renegociação; número da última Atualização MCR.
- **Prescrição da CPR e da cédula de crédito rural** — nenhum prazo afirmado por nenhuma frente.
- **Inciso do CPC art. 784** que enquadra CPR e cédula.
- **Periodicidade da capitalização** (mensal × semestral) — acórdão-paradigma não confirmado.
- **Conflito de garantias sobre a mesma safra** e **boa-fé do terceiro adquirente de safra gravada** — bloco inteiro sem número confirmado.
- **Eficácia do penhor rural sem registro** perante terceiros.
- **Termo inicial do prazo decadencial de 6 meses** da preferência e **depósito do preço** como requisito da adjudicação *(o texto legal é ✅; a jurisprudência é 🟡)*.
- **Requisitos formais mínimos da notificação** ao arrendatário; **preferência na RENOVAÇÃO** (ET art. 95).
- **Parceria simulada** — nenhum precedente do STJ confirmado.
- **CDC entre integrado e integradora** — busca dirigida no STJ voltou vazia.
- **Artigo do Provimento CNJ 149/2023** sobre usucapião extrajudicial rural (401, §3º × 416, III).
- **Decreto 74.965/1974** — não aberto; **não citar artigo**.
- **Número e sigla do Parecer CGU/AGU nº 01/2008-RVJ ("LA-01")**.
- **Acórdão e tese das ADPF 342 / ACO 2.463**; eventual modulação.
- **IN do INCRA/MAPA** com os índices de rendimento e lotação vigentes.
- **Regulamento da Lei 13.288/2016**; existência efetiva dos FONIAGRO.
- **IN RFB 2.330/2026** (3 quotas na lei × 4 na IN; se já incorporou a Lei 14.932/2024).
- **RPPN** como área não tributável do ITR.
- **Precedentes do STJ sobre embargo administrativo** — ⛔ **não citar o REsp 1.816.808/SP**. A âncora é **NORMATIVA — art. 15-A do Decreto 6.514/2008** *(⚠️ homônimo: o art. 15-A do **DL 3.365/41** é o dos juros compensatórios na desapropriação — ver `context/jurisprudencia-agraria.md` §6)*.
- **Súmula 355/STJ** — teor completo não conferido.
- **MP 1.314/2025** — confirmada apenas por remissão dentro da MP 1.376/2026.
- **Securitização de dívida rural** — **não confundir** com a composição de dívidas da MP 1.376.
- **Lei 15.300/2025 (LAE)** — texto integral não lido.
- **UF líder em pedidos de RJ do agro** — 🚨 **NÃO inventar Mato Grosso.**

---

## 9. ⏰ O RELÓGIO DO AGRO — prazos críticos

| Prazo | Marco | Selo |
|---|---|---|
| **120 dias da MP 1.376/2026** | publicação 15/07/2026 ⇒ **~12/11/2026** *(11/11 como data de segurança)* | 🔴 |
| **30 dias** — preferência do arrendatário | da notificação (ET 92, §3º; Dec. 45) | ✅ |
| **6 meses** — adjudicação por venda não notificada | da **transcrição no RI** (ET 92, §4º; Dec. 47) | ✅ |
| **6 meses** — notificação da renovação/retomada | antes do vencimento do contrato (ET 95, IV e V; Dec. 22) | ✅ |
| **20 dias** — defesa em auto de infração ambiental | da ciência da autuação | ✅ |
| **1 ano** — adesão ao PRA | **da NOTIFICAÇÃO** individual (não é data de calendário) | ✅🔴 |
| **21/10/2029** — georreferenciamento | Dec. 12.689/2025 — **SUB JUDICE**, exige as 4 declarações | 🔴 |
| **DITR 2026** | entrega de **10/08 a 30/09/2026**; vencimento da 1ª quota **30/09/2026** | ✅ |
| **12/08/2026** | **mérito das ADIs da LGLA no STF** — rechecar | 🔴 |

---

## 10. 🔴 GATE DE REVERIFICAÇÃO DE VIGÊNCIA — antes do publish e de cada atendimento

Cinco itens com prazo de validade curto. **Qualquer um que tenha mudado ⇒ atualizar a skill afetada E o anexo correspondente ANTES do publish.**

| # | Item | O que checar |
|---|---|---|
| 1 | **MP 1.376/2026** | Em Comissão Mista com emendas — conferir se foi **convertida, alterada ou caducou**; recontar os 120 dias |
| 2 | **ADIs 7913 / 7916 / 7919 + ADC 102** (Lei 15.190/2025) | **Mérito pautado para 12/08/2026** — conferir resultado |
| 3 | **Liminar da JF/MA** (proc. 1086967-47.2025.4.01.3700, Dec. 12.689/2025) | De maio/2026 — pode ter sido revista, ampliada ou cassada |
| 4 | **ADIs 5.771 / 5.787 / 5.883 / 6.787** (Lei 13.465/2017) | Retiradas de pauta em 23/06/2026 — verificar reinclusão |
| 5 | **Tema 1429/STF** | Mérito pendente; em junho/2026 ainda se admitiam *amici curiae* |

---

## 11. FRONTEIRAS — cross-link soft, NÃO duplicar

| Plugin | O que fica lá | O que fica no agrário |
|---|---|---|
| `direito-imobiliario-adv-os` | Registral e usucapião **urbanos**, REURB urbana, locação 8.245, condomínio | **Tudo RURAL**: georreferenciamento, CCIR/CNIR, devolutas, regularização fundiária rural, usucapião especial rural |
| `execucao-adv-os` | Execução genérica, monitória, cobrança | Execução **especializada** em CPR e cédula rural |
| `tributario-societario-adv-os` | Contencioso tributário pesado | **ITR consultivo** e a **camada IBS/CBS do contrato agrário** |
| `holding-architect` | Método das 4 células, estruturação societária e sucessória | **Ponteiro** — o rural-específico (imóvel rural na integralização, módulo fiscal, ITR, CCIR) |
| `civel-adv-os` | CPC integral, tutelas, teoria geral | CPC **filtrado e standalone** em `base-processual-agraria` |
| `bancario-adv-os` | Consumo bancário, fraudes, superendividamento | Revisional de **crédito rural** (regime próprio: DL 167/67, Súmula 93, MCR) |
| `calculosjudiciais-adv-os` | Cálculo e auditoria de laudo | Cross-link em revisional, indenização e excesso de execução |
| `leiloes-os` | Rito do leilão, arrematação, anulação | **Ponteiro nos dois sentidos**: leilão de fazenda por execução extrajudicial de hipoteca (Lei 14.711/2023, art. 9º), leilão do art. 28 da Lei 13.986, 2º leilão da Lei 9.514/97 |

**OUT, gap declarado:** **penal** (crimes ambientais, grilagem) — o art. 60 do Código Florestal entra só como **efeito** do termo do PRA, **nunca como defesa penal**.
**OUT:** **ambiental judicial amplo** (ACP, dano ambiental ofensivo) — fica só a camada **defensiva/consultiva** (propter rem, Tema 1.204, defesa do alienante).

---

## 12. MAPA DOS ANEXOS `context/`

| Tema | Arquivo |
|---|---|
| Contratos agrários: ET 92-96, 95-A + Dec. 59.566 **com a tabela de desalinhamento** | `estatuto-e-decreto-contratos-agrarios.md` |
| Função social, GUT/GEE, TDA, CF 184-191 | `lei-8629-93-e-cf-184-191.md` |
| CPR, Lei do Agro (afetação e CIR), cédulas do DL 167/67 | `lei-do-agro-e-cpr.md` |
| Composição de dívidas, dois regimes, janela de 120 dias 🔴 | `mp-1376-2026.md` |
| RJ do produtor, sujeição de créditos, Prov. CNJ 216/2026 | `rj-produtor-rural.md` |
| LRP, CCIR/CNIR, georreferenciamento sub judice, 11.952, estrangeiros | `registral-terras-e-estrangeiros.md` |
| APP, RL, áreas consolidadas, CAR e PRA | `codigo-florestal-12651.md` |
| Auto de infração, embargo, prescrição, descontos, LGLA | `ambiental-administrativo.md` |
| IBS/CBS no arrendamento + ITR | `tributacao-rural.md` |
| Súmulas, temas e REsp ✅ + CANCELADOS / RACHAS / PENDENTES | `jurisprudencia-agraria.md` |
| **EUDR — Reg. (UE) 2023/1115** (exclusivo da skill `compliance-eudr`) 🔴 | `eudr-regulamento-2023-1115.md` |
| Metodologia (este arquivo) | `metodologia-agraria.md` |

**Nota sobre o anexo EUDR:** o gate do BUILD-CONTRACT §8 foi **satisfeito** — a frente G entregou captura primária do **EUR-Lex** (texto consolidado PT de 26/12/2025, CELEX `02023R1115-20251226`). O anexo existe e a skill **`compliance-eudr`** pode ser construída. Ela é a **única** skill que consome esse anexo, e **nenhuma outra skill deve citá-lo** — é norma estrangeira, fora do escopo das demais camadas.
