---
description: Inicia o wizard de configuracao do plugin direito-agrario — cria a pasta agrario/ com identidade do escritorio, UF e comarcas, perfil de atuacao (produtor, credor, trading, cooperativa), culturas e calendario de safra, e o modo de fluxo.
allowed-tools: Read, Write, Edit, Bash, Glob, Grep
argument-hint: [--update para reconfigurar]
---

Voce foi acionado pelo comando `/start-agrario` do plugin agrario-adv-os (Direito Agrario brasileiro ponta a ponta).

Argumento recebido: `$ARGUMENTS`

**Objetivo:** configurar o plugin ao perfil do escritorio antes de qualquer trilha.

## PROTOCOLO
1. **Acionar a skill `agrario-onboarding`** (wizard com botoes via AskUserQuestion nas escolhas de lista fechada).
2. Cria `<cwd>/agrario/perfil.md`: identidade do escritorio, UF e comarcas, perfil de atuacao (produtor devedor, credor/trading, cooperativa, adquirente de terra), culturas e janela de safra, orgaos-alvo (INCRA, IBAMA e orgao ambiental estadual, cartorio de registro de imoveis, JUCESP/junta).
3. Se ja existir, oferecer continuar / atualizar / recriar.
4. Fechar apontando a porta unica (`/agrario-master`) e o alerta de janela: a contratacao da **MP 1.376/2026** vence em **~11/11/2026** (120 dias da publicacao de 15/07/2026, data de seguranca).

**Skill a acionar:** `agrario-onboarding`.
