---
name: execucao-de-cpr-e-cedula-rural
description: "Lado credor: escolhe a via executiva correta e constringe a safra. CPR fisica cobra-se por execucao para entrega de coisa incerta (art. 15 da Lei 8.929/94); CPR financeira, por quantia certa (art. 4º-A, §2º). Cobre a individualizacao do produto na inicial, a impugnacao da escolha com pericia, a conversao em valor mais perdas e danos e a liquidacao previa obrigatoria de benfeitorias. Use quando o operador disser vou executar a CPR, o produtor nao entregou a soja, executar cedula rural, penhorar a safra, qual a via da execucao, constricao de safra."
---

> **🖱️ Escolhas = botoes:** em pergunta de **lista fechada** (especie, via, objeto da constricao) use **AskUserQuestion** — botoes clicaveis, max. 4 por pergunta.

# EXECUCAO-DE-CPR-E-CEDULA-RURAL — o lado credor, e a porta certa

> Camada 3, lado **credor** (banco, trading, cerealista). Espelho de `embargos-a-execucao-de-cpr`. A primeira decisao — **qual via** — define tudo.

## Quando ativa / trilha
Titulo rural vencido e nao cumprido, e o credor decidiu cobrar. Apoia-se na `base-credito-rural-e-lei-do-agro` (especie e via) e na `base-processual-agraria` (rito).

**Diferenca das vizinhas:** a **execucao generica** de titulo extrajudicial e do `execucao-adv-os`; aqui e a **especializada** em CPR e cedula rural, com constricao de safra e penhor agricola.

## Anexos obrigatorios (context/)
- `context/cpc-agrario.md` (**§10 entrega de coisa, arts. 806-813** · **§9 art. 784** · §11 embargos · §12 impenhorabilidade · §2.2 art. 60 — **grep o artigo e leia a faixa**).
- `context/lei-do-agro-e-cpr.md` (L8929 arts. 3º-B §3º, 4º-A §2º, 15, 16, 18 · DL 167/67 art. 10 · CIR art. 21) · `context/jurisprudencia-agraria.md` (REsp 2.178.558-MT · Tema 1.234 · REsp 2.233.886-RS).

## Base legal ancorada ✅

### ⭐ A porta — errar aqui e entregar a defesa pronta
| Especie | Via | Ancora |
|---|---|---|
| **CPR fisica** | execucao para **ENTREGA DE COISA INCERTA** | L8929 **art. 15** |
| **CPR financeira** | execucao **POR QUANTIA CERTA** | L8929 **art. 4º-A, §2º** |
| **Cedula de credito rural** | quantia certa (titulo civil liquido e certo) | DL 167/67 **art. 10** |
| **CIR** | titulo executivo extrajudicial; e ha a via **extrajudicial** do art. 28 | L13986 **arts. 21 e 28** |

🚨 Executar **por quantia certa** uma **CPR fisica** (ou o inverso) e a hipotese do **CPC 917, §2º, III** — excesso por processar-se de **modo diferente do determinado no titulo**. E o vicio que o produtor alega primeiro.

⚠️ **CPC 784: cite o ARTIGO, nunca o inciso** — **nenhum dos doze incisos nomeia a CPR ou a cedula rural**; a executividade vem de **lei especial** (8.929/94 e DL 167/67). ⭐ **§4º** (Lei 14.620/2023): em titulo constituido por meio eletronico admite-se **qualquer assinatura eletronica prevista em lei, dispensada a assinatura de testemunhas** quando a integridade for conferida por **provedor de assinatura** — resposta a objecao de "sem duas testemunhas" contra CPR digital. **Art. 784, §1º:** **qualquer acao relativa ao debito nao inibe o credor de promover a execucao** — e a resposta a revisional ajuizada para travar a cobranca.

### Entrega de coisa INCERTA — arts. 811 a 813, a via da CPR fisica
- **Art. 811:** recaindo sobre **coisa determinada pelo genero e pela quantidade**, o executado e citado para **entrega-la individualizada, se lhe couber a escolha**. ⭐ **P.u. — instrucao de redacao da inicial:** cabendo a **escolha ao exequente**, ele **deve indica-la na peticao inicial**. Confira a clausula da CPR **antes** de protocolar, sob pena de emenda.
- **Art. 812:** qualquer das partes **impugna a escolha em 15 dias**, e o juiz decide de plano ou **ouvindo perito**. E aqui — nao nos embargos — que se discute **qualidade e padrao**: umidade, impureza, avariados, classificacao.
- **Art. 813:** aplica-se, no que couber, a Secao I ⇒ arts. 806-810.

### O que vem por remissao — arts. 806 a 810
- **Art. 806:** citacao para satisfazer em **15 dias**; **§1º** o juiz **pode fixar multa diaria** ja no despacho da inicial; **§2º** do mandado consta **ordem de imissao na posse ou de busca e apreensao**, cumprida **de imediato**. **Art. 807:** entregue a coisa, prossegue-se para **frutos ou ressarcimento de prejuizos**.
- **Art. 808:** **alienada a coisa quando ja litigiosa**, expede-se mandado contra o **terceiro adquirente**, que **so sera ouvido apos deposita-la**.
- ⭐ **Art. 809 — o artigo da safra que nao veio:** deteriorada, nao entregue, nao encontrada ou nao reclamada do terceiro, o exequente recebe **o valor da coisa alem de perdas e danos**; **§1º** sem valor no titulo, apresenta **estimativa** sujeita a arbitramento; **§2º** apuracao **em liquidacao**. E onde entra o **preco da saca na data devida**.
- ⚠️ **Art. 810 — a contramedida que o credor antecipa:** havendo **benfeitorias indenizaveis**, a **liquidacao previa e OBRIGATORIA**, e, com saldo em favor do executado, **o exequente o deposita ao requerer a entrega da coisa**. Casa com a **retencao do arrendatario** (ET 95, VIII; Dec. 59.566/66, art. 25) quando a coisa e o imovel rural.

### Constricao — o que se alcanca
- **L8929, art. 18:** bens vinculados a CPR **nao sao penhorados por outras dividas** — protege o credor **desta** cedula.
- **L8929, art. 16:** busca e apreensao **ou** leilao do bem alienado fiduciariamente **nao elidem** posterior execucao, inclusive da hipoteca e do penhor da mesma cedula, pelo **remanescente**.
- ⭐ **CPC 834:** frutos e rendimentos de bens inalienaveis sao penhoraveis **a falta de outros bens** — alcanca **a safra** e a **renda do arrendamento** ainda quando a terra e impenhoravel pelo art. 833, VIII. E o caminho quando a tese da pequena propriedade prospera.
- **L8929, art. 3º-B, §3º:** a certidao da entidade escrituradora tem **liquidez, certeza e exigibilidade** — instrui a execucao da CPR **escritural**.
- **CPC 60:** imovel em **mais de um Estado ou comarca** — o juizo **prevento julga a totalidade**. Fazenda que cruza divisa nao se fatia.

### O que esperar da defesa
**CPC 919:** os embargos **nao suspendem** a execucao (suspender exige **tutela do art. 300 E garantia integral**). **CPC 916:** deposito de **30% do valor em execucao** + 6 parcelas importa **renuncia aos embargos** (§6º). **CPC 917, §§3º-4º:** excesso sem demonstrativo e rejeitado liminarmente — mas o credor tambem chega com **memoria integra**, porque o **DL 167/67, art. 10, §1º** obriga a **descontar parcela nao levantada e pagamentos parciais**: cobrar o valor cheio quando o custeio foi liberado por etapas e o erro que entrega o excesso. Detalhe em `embargos-a-execucao-de-cpr`.

## Passo a passo / o que produzir
1. **Classificar o titulo (botoes)** e fixar a via pela tabela acima. Conferir o **registro no BCB** (art. 12): titulo sem registro no prazo **perde validade e eficacia**, e isso derruba a propria execucao.
2. **Sendo CPR fisica:** conferir de quem e a escolha; **cabendo ao exequente, individualizar o produto na inicial** (art. 811, p.u.), com genero, quantidade, qualidade e padrao.
3. **Requerer no despacho inicial** a **multa diaria** (806, §1º) e a **ordem de imissao ou busca e apreensao** (806, §2º).
4. **Montar a memoria de calculo** ja com os descontos do art. 10, §1º — antecipar o excesso e barato; responde-lo depois, caro.
5. **Planejar a constricao:** bens vinculados (art. 18) · remanescente apos busca e apreensao (art. 16) · **frutos e rendimentos** (CPC 834) quando a terra for impenhoravel.
6. **Antecipar a retencao por benfeitorias** (810 + 917, §§5º-6º) e **entregar**: inicial de execucao + memoria de calculo + rol de bens a constringir + plano de resposta aos embargos.

## Postura honesta
- ⚠️ **A conversao da execucao de entrega em quantia certa nao renuncia a garantia nem torna o credito concursal** — **REsp 2.178.558-MT** (3ª Turma, Villas Boas Cueva, **09/09/2025**, **Info 867**), sobre CPR **barter**. ⚠️ **07/10/2025 e a data da NOTICIA do STJ, nao outro caso.** E e **precedente de Turma, nao repetitivo**.
- ⚔️ **Racha declarado:** ha decisao do **TJ/GO** reconhecendo natureza **concursal** da cedula rural **financeira**, e o **ACT CNJ-MAPA 013/2026** reconhece divergencias entre tribunais. Nao venda pacificacao que nao existe.
- ⚠️ **O onus da impenhorabilidade e do executado (Tema 1.234)** — mas a garantia real **sem** divida de aquisicao encontra o **REsp 2.233.886-RS**. Dimensione o risco antes de prometer resultado ao credor.
- 🚫 **Prescricao da CPR e da cedula rural: GAP.** Nenhum prazo afirmado por nenhuma fonte confirmada — inclusive para aferir a **exigibilidade** antes de executar.
- 🟡 **Sem numero confirmado** (lista no `validador-agrario`): conflito de garantias sobre a **mesma safra** · **boa-fe do terceiro adquirente de safra gravada**, relevante justamente na constricao · penhor rural sem registro.

## Cross-link e fechamento
Defesa -> `embargos-a-execucao-de-cpr`. Titulos -> `cpr-emissao-e-formalizacao` · `cedulas-de-credito-rural`. Garantias -> `garantias-do-credito-rural` · `patrimonio-rural-em-afetacao-e-cir`. Devedor em RJ -> `rj-produtor-defesa-do-credor` · `rj-sujeicao-de-creditos-agro`. Calculo -> `calculosjudiciais-adv-os`; execucao generica -> `execucao-adv-os` (soft).

**Toda peca fecha pela `suprema-corte-agraria` (R1-R4) + `validador-agrario` antes de entregar.**
