# SDD — Spec-Driven Development

## O que é
Metodologia onde **documentos de especificação são escritos antes de qualquer código**. A spec é a fonte única da verdade.

## Fluxo SDD
1. `/speckit-constitution` — princípios imutáveis (uma vez)
2. `/speckit-specify` — escreve o que construir
3. `/speckit-clarify` — perguntas de de-risco (opcional)
4. `/speckit-plan` — como construir
5. `/speckit-tasks` — tasks atômicas
6. `/speckit-implement` — executar
7. `/speckit-converge` — verificar conformidade

## Princípios
- Spec é viva: muda antes do código
- Spec é rastreável: git diff da spec
- Agente é executor: lê spec, gera código
- Qualidade guiada por spec
