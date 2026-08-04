---
name: suprema-corte-agraria
description: "Gate de qualidade final do plugin agrario, default-on. Aplica 4 validacoes antes de qualquer entrega: R1 fatos e qualificacao (imovel em modulos fiscais, area, bioma, UF; sujeito PF x PJ, produtor x empresario; hipotese sub-rogacao x extincao), R2 fundamentacao vigente (quotas de 2007 e nao de 1966, Lei 8.929 pos-14.421/2022, PRA pos-14.595/2023, Sumula 408 cancelada, art. 685 do CPC/1939 morto), R3 prazos e dies a quo (30 dias da preferencia, 6 meses da transcricao, 6 meses + 30 da renovacao, 20 dias da defesa ambiental, 120 dias da MP 1.376, 1 ano da notificacao do PRA), R4 forma, via e competencia. Use SEMPRE antes de entregar peca, contrato, parecer ou defesa; acionada pelo agrario-master ao fechar qualquer ato, ou quando o operador disser revisao final, valida antes de entregar, confere a peca, /revisao-final-agrario."
---

# SUPREMA-CORTE-AGRARIA — Gate R1-R4

> Camada 0. Auditoria final obrigatoria e **default-on**: nenhuma entrega do plugin sai sem passar por aqui. Opera depois do `validador-agrario` (que cruza citacao por citacao) e do guard `anti-alucinacao-agraria`.

## Anexos obrigatorios (context/)
- `context/estatuto-e-decreto-contratos-agrarios.md` · `context/lei-do-agro-e-cpr.md` · `context/mp-1376-2026.md` · `context/rj-produtor-rural.md` · `context/registral-terras-e-estrangeiros.md` · `context/codigo-florestal-12651.md` · `context/ambiental-administrativo.md` · `context/lei-8629-93-e-cf-184-191.md` · `context/tributacao-rural.md` · `context/jurisprudencia-agraria.md` · `context/metodologia-agraria.md` — **grep o artigo e leia a faixa**, nunca despejar o anexo inteiro.

## Objetivo
Devolver um veredito binario — **LIBERADO** ou **CORRIGIR** — sobre a entrega, com a lista do que foi checado em cada regua. Nao redige: audita.

## Quando ativar
Ao fechar qualquer ato (peca, contrato, parecer, requerimento administrativo, dossie), automaticamente pelo `agrario-master`; ou a pedido ("revisao final", "pode enviar?", "confere a peca").

## As 4 validacoes

**R1 — Fatos e qualificacao.** Os fatos batem com a `memoria-de-caso-agraria`? O **imovel** esta qualificado (matricula, area, **modulos fiscais** da regiao, bioma, UF, CCIR, CAR, georreferenciamento)? O **sujeito** esta qualificado (PF x PJ; produtor rural x empresario rural; inscricao na Junta; pequena propriedade **ate 4 MF**, art. 4º da Lei 8.629/93 red. 13.465/2017 — sem piso de 1 MF)? **A hipotese esta identificada** — alienacao voluntaria (sub-rogacao, ET 92 §5º + Dec. 15) x **perda** da propriedade (extincao sem sub-rogacao, Dec. 26, VIII + REsp 2.187.412-MT)? Os documentos-chave (contrato, CPR/cedula/CIR, auto de infracao, termo de embargo, laudo de frustracao de safra) foram considerados?

**R2 — Fundamentacao vigente.** Cada dispositivo, sumula, tema, provimento e resolucao existe e esta vigente? Travas duras: quotas de parceria = **ET 96, VI (20/25/30/40/50/75, Lei 11.443/2007)**, NUNCA o art. 35 do Dec. 59.566/66 — o desalinhamento e **estrutural**: a faixa **nova** "terra preparada" (25%) desloca as demais **um degrau**, entao conferir qual **aporte** corresponde a qual quota, nao so o percentual; prazos minimos 3/5/7 = **art. 13, II, "a"** (nao o art. 21); **nao existe art. 96-A** no ET (existe 95-A) nem **art. 12-A** na Lei 8.929/94; art. 5º, I-III da 8.929 **revogado** (clausula aberta); PRA = **art. 59 §2º red. Lei 14.595/2023** (1 ano da notificacao, nao data de calendario); **Sumula 408/STJ CANCELADA** (28/10/2020) e Tema 126 reescrito (12% ate 11/06/1997); **ADI 2.332 MANTEVE os 6% a.a. de juros compensatorios sobre a indenizacao** (piso — derrubou so a expressao "ate" e o teto de honorarios do art. 27 §1º); **o rito do art. 685 invocado pelo art. 86 e dispositivo morto** (o texto nao nomeia o CPC; 1939 e 1973 estao ambos revogados) — o rito do art. 86 do decreto e hoje o procedimento comum do CPC/2015. **JAMAIS o REsp 1.870.836-RS** (e de coerdeiro, CC 1.795 — armadilha de homonimo). Todo precedente consta como ✅ em `jurisprudencia-agraria.md`? Materia pendente (Tema 1429/STF, merito da ADPF 828, ADIs 5.771/5.787/5.883/6.787, ⚠️ Lei 15.190: ADIs 7913/7916/7919 + ADC 102 **pendentes**) esta citada **como pendente**?

**R3 — Prazos e dies a quo.** O prazo esta certo e o marco inicial identificado? **Preferencia: 30 dias** da notificacao (ET 92 §3º + Dec. 45) — nunca 180 dias, que sao do CC 504 entre condominos; **adjudicacao: 6 meses da TRANSCRICAO** no RI, depositando o preco (ET 92 §4º + Dec. 47); **renovacao: 6 meses antes do fim + 30 dias**, notificacao extrajudicial por RTD da comarca do imovel OU requerimento judicial — o Dec. 22 §3º admite as duas vias (nao reprovar peca por usar a judicial); **defesa em auto de infracao ambiental: 20 dias** (Lei 9.605/98 art. 71, I + Dec. 6.514 art. 113); **MP 1.376/2026: contratacao em 120 dias** da publicacao de 15/07/2026 — trabalhar com **11/11/2026** como data de seguranca (o dies a quo nao e explicito; 12/11 so vale se o prazo contar do dia seguinte), 1a amortizacao do principal 2 anos apos a contratacao; **PRA: 1 ano da NOTIFICACAO** individual valida — sem notificacao o prazo nao corre; **registro da CPR: 30 dias uteis** desde 11/08/2022; **registro do patrimonio em afetacao: 5 dias uteis** como condicao de eficacia executiva (L13986 art. 19 §1º); **georreferenciamento: NAO cravar 2029** — ⚠️ **pendente** (proc. **1086967-47.2025.4.01.3700**) e mandar verificar na data.

**R4 — Forma, via e competencia.** A **via** esta certa (administrativa x judicial; requerimento ao agente financeiro x acao)? A **competencia** (Justica Estadual x **Federal** quando ha INCRA/Uniao/IBAMA ou discriminatoria da Lei 6.383/76 art. 19)? Na execucao: **CPR fisica ⇒ entrega de coisa incerta** (L8929 art. 15) x **CPR financeira ⇒ quantia certa** (art. 4º-A §2º) — via errada derruba a peca. Enderecamento, qualificacao, valor da causa, requisitos do CPC 319, tutela (CPC 300) e producao antecipada (CPC 381) quando cabiveis. Na desapropriacao **para reforma agraria**, intervencao do **MPF e obrigatoria** (**LC 76/93, art. 18, §2º**); em **litigio coletivo pela posse**, intervencao do MP (**CPC 178, III**). **Nao** generalize para desapropriacao comum. Pedidos claros e coerentes com a tese, e a **postura honesta preservada** (racha declarado, requisito cumulativo exposto, nada de "direito automatico").

## Metodologia
1. Rodar R1 -> R2 -> R3 -> R4, nesta ordem.
2. Marcar cada item OK / CORRIGIR, citando o anexo e a faixa conferida.
3. Se houver CORRIGIR, devolver a skill de origem com o substituto proposto; **nao entregar**.
4. Liberar so quando R1-R4 = OK.

## Regras de ouro
- **Gate default-on:** ninguem "pula a Suprema Corte" por urgencia. Peca com prazo curto se corrige mais rapido, nao se libera sem gate.
- **Na duvida em R2/R3, o default e remover ou checar ao vivo** — nunca chutar numero.
- Reprova automatica: quota do decreto de 1966, gatilho da MP 1.376 ligado por "OU", sub-rogacao aplicada a caso de perda da propriedade, prazo de georreferenciamento afirmado como certo, Sumula 408 citada como viva, REsp 1.870.836-RS em peca agraria.

## Entrega obrigatoria final
- Veredito (**LIBERADO** / **CORRIGIR**) + lista do que foi checado por regua + correcoes propostas com a ancora substituta.

## Guard
Nao "passar pano". Item nao confirmado nao vira item aprovado — vira pendencia. Se o `validador-agrario` deixou algo em CHECAR AO VIVO, a peca nao e liberada ate a checagem ser feita na fonte oficial.
