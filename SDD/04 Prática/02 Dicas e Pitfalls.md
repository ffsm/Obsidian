# Dicas e Pitfalls

## Dicas
1. **Spec antes de código** — regra de ouro
2. **Edite a spec** se precisar mudar requisito
3. **Git commit da spec** — rastreabilidade completa
4. **Constitution primeiro** — protege contra drift de requisitos
5. **Use `--max-turns`** — evita loops infinitos no Claude

## Pitfalls
1. **Windows PATH** — `uv` não está no PATH, use `python -m uv`
2. **`--force` necessário** — `specify init` em pastas não vazias
3. **`--integration` obrigatório** — no modo `--non-interactive`
4. **`.claude/` no gitignore** — evita vazamento de credenciais
5. **Session resume** — mesmo diretório é obrigatório

## Boas Práticas
- Spec deve ser auto-contida
- Tasks devem ser atômicas (uma coisa por task)
- Testes devem vir com as tasks, não depois
- Revisão manual da spec antes de `/speckit-implement`
