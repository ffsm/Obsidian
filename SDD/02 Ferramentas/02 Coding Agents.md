# Coding Agents

## Claude Code
- **Instalação**: `npm install -g @anthropic-ai/claude-code`
- **Versão**: v2.1.296 (Pro account)
- **Auth**: `claude auth status`
- **Modo preferido**: print mode (`-p`) para tarefas únicas
- **Modo interativo**: tmux para sessões multi-turno

## GitHub Copilot
- Integrado via VS Code
- `--integration copilot` no Spec Kit

## OpenAI Codex
- CLI disponível para tarefas autônomas

## Google Gemini
- `--integration gemini` no Spec Kit

## Dicas de Uso
- Use `--max-turns` em print mode para evitar loops infinitos
- Use `--allowedTools` para restringir permissões
- Session resume: `claude -c` ou `--resume <id>`
