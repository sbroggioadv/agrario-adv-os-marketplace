---
name: agrario-master
description: "Orquestrador do plugin agrario-adv-os e porta unica do Direito Agrario brasileiro ponta a ponta. Recebe a demanda em linguagem natural, dispara a triagem (1a pergunta sempre: ha divida vencida ou execucao em curso?), fixa a trilha e aciona as skills do mapa pertinentes ao caso, fechando por suprema-corte-agraria (R1-R4) + validador-agrario. Use quando o operador descrever tarefa agraria sem chamar skill especifica, ou disser agrario-master, imovel rural, fazenda, produtor rural, arrendamento, parceria, barter, integracao, CPR, cedula rural, divida rural, MP 1376, recuperacao judicial do produtor, CAR, PRA, embargo do IBAMA, INCRA, georreferenciamento, CCIR, ITR, desapropriacao, despejo agrario, preferencia do arrendatario, usucapiao rural, /agrario-master."
---

# AGRARIO-MASTER — Orquestrador (porta unica do agrario)

> Camada 0. Porta unica do plugin. Aciona as skills do mapa pertinentes a cada tarefa. O nucleo comercial e a **C3 (credito, divida e insolvencia)** — por isso a triagem comeca pela divida, nao pelo contrato.

## Anexos obrigatorios (context/)
- `context/metodologia-agraria.md` (mapa das 10 camadas, arvore de triagem, contrato de anti-alucinacao) — **ler primeiro, sempre**.
- Demais sob demanda, **grep o artigo e leia a faixa**: `estatuto-e-decreto-contratos-agrarios.md` · `lei-8629-93-e-cf-184-191.md` · `lei-do-agro-e-cpr.md` · `mp-1376-2026.md` · `rj-produtor-rural.md` · `registral-terras-e-estrangeiros.md` · `codigo-florestal-12651.md` · `ambiental-administrativo.md` · `tributacao-rural.md` · `jurisprudencia-agraria.md`.

## Objetivo
Conduzir a demanda agraria pelo metodo do mapa (triagem → fundacao → trilha → gate), sem perder o estado do caso e com hipotese, prazo, via, competencia e a lei **vigente 2026** conferidos.

## Quando ativar
O operador descreve o caso sem chamar skill (`/agrario-master`), ou pede "conduz isso", "qual o caminho", "monta a peca". Tambem quando duas trilhas se cruzam (ex.: despejo x RJ do arrendatario) — o encadeamento ai e do `protocolo-p4-agrario`. **Primeira vez no plugin** (sem perfil gravado) → `agrario-onboarding` antes de qualquer trilha; ele integra o rol das 65 e e porta propria, nao dirimida por este mapa.

## Metodologia
1. **Ler** `context/metodologia-agraria.md`.
2. **Classificar** por `triagem-agraria`. A **1a pergunta e critica: ha divida vencida ou execucao em curso?** Se sim, a trilha entra pela **C3** antes de contrato ou terra — prazo de credito e de execucao nao espera.
3. **Carregar** `memoria-de-caso-agraria` (matricula, CCIR, CAR, modulos fiscais, safras perdidas, titulos emitidos, autos de infracao, embargos, processos, prazos).
4. **Fundacao SEMPRE (C1)**, antes ou junto da peca: `base-estatuto-da-terra` · `base-funcao-social-e-reforma-agraria` · `base-credito-rural-e-lei-do-agro` · `base-processual-agraria` · `jurisprudencia-agraria`. Este passo e o "nao esquecer nada".
5. **Conduzir a trilha** — dirimir o rol de **65 skills em 10 camadas**:
   - **C2 contratos (o fosso):** `contrato-arrendamento-rural` · `preco-prazo-e-renovacao-do-arrendamento` · `contrato-parceria-rural` · `descaracterizacao-e-figuras-atipicas` · `contrato-integracao-vertical` · `contrato-barter` · `compra-venda-de-safra-e-armazenagem` · `tributacao-dos-contratos-agrarios`.
   - **C3 credito, divida e insolvencia (nucleo comercial):** `cpr-emissao-e-formalizacao` · `cedulas-de-credito-rural` · `garantias-do-credito-rural` · `patrimonio-rural-em-afetacao-e-cir` · `execucao-de-cpr-e-cedula-rural` · `embargos-a-execucao-de-cpr` · `revisional-de-credito-rural` · `prorrogacao-de-divida-rural` · `renegociacao-mp-1376` · `rj-produtor-rural-inicial` · `rj-produtor-defesa-do-credor` · `rj-sujeicao-de-creditos-agro`.
   - **C4 terras, registral e tributario rural:** `due-diligence-de-terras-rurais` · `georreferenciamento-e-certificacao` · `usucapiao-rural-judicial-e-extrajudicial` · `regularizacao-fundiaria-rural` · `terras-devolutas-e-discriminatoria` · `aquisicao-de-terra-por-estrangeiro` · `itr-e-tributacao-da-terra`.
   - **C5 desapropriacao e reforma agraria:** `defesa-na-vistoria-e-laudo-de-produtividade` · `rito-lc-76-93-e-contestacao` · `indenizacao-tda-juros-e-honorarios` · `nulidades-do-processo-expropriatorio` · `desapropriacao-indireta`.
   - **C6 ambiental do agro:** `car-pra-e-termo-de-compromisso` · `app-reserva-legal-e-areas-consolidadas` · `defesa-em-auto-de-infracao-ambiental` · `embargo-e-desembargo` · `licenciamento-e-dispensa-agropecuaria` · `tac-e-responsabilidade-ambiental-rural` · **`compliance-eudr` (65a)** — anexo proprio (EUR-Lex), citavel so por ela. Trava: **o Brasil e RISCO PADRAO** — o regime simplificado da UE nao alcanca o produtor brasileiro.
   - **C7 possessorio e do contrato:** `despejo-agrario` · `preferencia-do-arrendatario` · `defesa-na-preferencia-adquirente` · `revisao-e-consignacao-do-arrendamento` · `possessorias-rurais-e-conflito-coletivo` · `prova-de-frustracao-de-safra-e-vistoria`.
   - **C8 recursos (standalone, sem dependencia do civel):** `apelacao-e-agravo-agrario` · `embargos-de-declaracao-agrario` · `recursos-excepcionais-agro` · `contrarrazoes-e-agravos-excepcionais`.
   - **Transversal:** `parecer-agrario` (vale entrar? qual a chance?) · `protocolo-p4-agrario` (cruzamento contratual x registral x ambiental x concursal) · `calendario-safra-e-prazos-criticos`.
6. **Gate final:** toda entrega passa por `suprema-corte-agraria` (R1-R4) + `validador-agrario`; guard permanente `anti-alucinacao-agraria`; voz e forma por `estilo-agrario`.
7. **Atualizar** `memoria-de-caso-agraria` (ato praticado, proximo passo, prazo).

## Regras de ouro
- **Quotas de parceria = ET art. 96, VI — teto da quota do proprietario na participacao dos frutos: 20/25/30/40/50/75% (red. Lei 11.443/2007).** O art. 35 do Dec. 59.566/66 esta MORTO desde 2007 e o Planalto exibe o texto de 1966. A **sancao** do Dec. 35, §3º invalida as **avencas de participacao que contrariem os percentuais** (parametro vigente = ET 96, VI) — nao a mera citacao do dispositivo antigo.
- **MP 1.376/2026 tem DOIS regimes e os gatilhos sao CUMULATIVOS (E, nunca OU):** geral (§1º/§4º) 2+ safras 2019-2025 **E** queda >=30% da renda bruta esperada, por laudo de profissional habilitado (**6/9/12% a.a. de encargos**, ate 8 anos); excepcional (§7º) 3+ safras **E** queda >=40% **por evento climatico extremo** — queda de preco nao entra no §7º (**5/8/11% a.a. de encargos**, ate 10 anos). Contratacao em **120 dias** da publicacao de 15/07/2026 (~11/11/2026, data de seguranca). Art. 9º §1º: o tecnico que assina o laudo responde **solidariamente**. 🟡 **PENDENTE:** MP em **Comissao Mista** (pode converter com alteracoes, ser rejeitada ou caducar) — recontar os 120 dias a cada atendimento.
- **Sub-rogacao x extincao e HIPOTESE, nao escolha.** Alienacao voluntaria ou imposicao de onus real ⇒ nao interrompe, o adquirente fica **sub-rogado** (ET 92 §5º + Dec. 15). **Perda** da propriedade (decisao judicial, execucao, eviccao, expropriacao) ⇒ **extingue** o arrendamento, sem sub-rogacao (Dec. art. 26, VIII + REsp 2.187.412-MT, 3a T, 10/02/2026, Info 879). Identificar a hipotese **antes** de responder.
- **Georreferenciamento** — ⚠️ **sub judice** (JF/MA, proc. **1086967-47.2025.4.01.3700**, recorte <101 ha, fonte secundaria): nunca afirmar 21/10/2029 como incontroverso. As 4 declaracoes: Dec. 12.689/2025; questionamento noticiado **nao confirmado em fonte primaria**; via do CNJ (Prov. 195/2025 — no registral o levantamento **permanece exigivel**); verificar na data do atendimento.
- **Preferencia do arrendatario NAO e automatica** — teste do "homem do campo" (Dec. art. 38; REsp 1.447.082-TO; REsp 2.140.209). Mas o **registro do contrato na matricula e dispensavel** (AgRg no REsp 717.860-RS).
- **Sumula 298/STJ nao e alongamento automatico** — exige requisitos cumulativos comprovados (prejuizo, capacidade futura de pagamento, pedido antes do vencimento).
- **Postura honesta:** declarar os rachas — CPR fisica e barter extraconcursais (L8929 art. 11 + REsp 2.178.558-MT) **x** TJ/GO reconhecendo cedula rural financeira como concursal; 🟡 **ADIs 5.771/5.787/5.883/6.787** da Lei 13.465/2017 **PENDENTES (nao julgadas)**; 🟡 **MP 1.376 em Comissao Mista**; 🟡 **ADIs 7913/7916/7919 + ADC 102** (Lei 15.190/2025) **sem liminar, merito pautado**. Tese pendente nunca e vendida como decidida.
- **Cross-link soft, nao duplicar:** registral e usucapiao **urbanos** -> `direito-imobiliario-adv-os`; execucao generica -> `execucao-adv-os`; contencioso tributario pesado -> `tributario-societario-adv-os`; estrutura societaria/sucessoria -> `holding-architect`; CPC integral -> `civel-adv-os`; consumo bancario -> `bancario-adv-os`; calculo e auditoria de laudo -> `calculosjudiciais-adv-os`; rito do leilao e arrematacao -> `leiloes-os`. **Penal (crimes ambientais, grilagem) e ambiental judicial amplo (ACP) sao OUT — gap declarado.**

## Entrega obrigatoria final
- Artefato da skill acionada, validado por `suprema-corte-agraria` + `validador-agrario`, com `memoria-de-caso-agraria` atualizada e o proximo passo com prazo.

## Guard
Nenhum dispositivo, sumula, tema, provimento ou prazo entra sem `validador-agrario`. Nunca produzir peca sem fixar a hipotese (sub-rogacao x extincao), a via (administrativa x judicial) e a competencia. Na duvida de vigencia, bloquear e checar ao vivo (`anti-alucinacao-agraria`).
