# Spec Kit

## O que é
Ferramenta oficial do GitHub para **Spec-Driven Development**. CLI chamada `specify` que gera templates de specs, workflows e integrações com coding agents.

## Instalação
```bash
python -m uv tool run --from git+https://github.com/github/spec-kit.git specify --help
```

Alias no `.bashrc`:
```bash
alias specify='python -m uv tool run --from git+https://github.com/github/spec-kit.git specify'
```

## Comandos Principais
| Comando | Uso |
|---------|-----|
| `specify init` | Inicializa projeto SDD |
| `/speckit-specify` | Escreve a spec base |
| `/speckit-clarify` | Perguntas de de-risco |
| `/speckit-plan` | Plano de implementação |
| `/speckit-tasks` | Tasks atômicas |
| `/speckit-implement` | Executa tasks |
| `/speckit-converge` | Verifica conformidade |
| `/speckit-constitution` | Princípios imutáveis |
| `/speckit-analyze` | Relatório de consistência |
| `/speckit-checklist` | Checklists de qualidade |

## Integrações
- Claude Code (`claude`)
- GitHub Copilot (`copilot`)
- Google Gemini (`gemini`)
- OpenAI Codex (`codex`)
- Generic (`generic`)

## Pitfalls Windows
- Use `python -m uv` em vez de `uv` (não está no PATH do git-bash)
- `specify init` precisa `--force --here` em pastas com arquivos
- `--integration <nome>` obrigatório no modo `--non-interactive`
