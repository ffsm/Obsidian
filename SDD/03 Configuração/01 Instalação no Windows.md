# Instalação no Windows

## Spec Kit
```bash
python -m pip install uv
python -m uv tool run --from git+https://github.com/github/spec-kit.git specify --help
```

## Claude Code
```bash
npm install -g @anthropic-ai/claude-code
claude --version
claude auth status
```

## Pitfalls
- `uv` não está no PATH do git-bash → use `python -m uv`
- `specify init` requer `--force --here` em pastas não vazias
- `--integration` obrigatório no modo `--non-interactive`
- CLAUDE.md é carregado automaticamente pelo Claude Code
