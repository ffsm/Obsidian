# Exemplo Prático

## Walkthrough: Criando uma Feature com SDD

### 1. Specify
```
cd /c/path/projeto
claude -p "Use /speckit-specify para escrever a spec de login com SSO"
```
Gera: `specs/login/spec.md`

### 2. Clarify (opcional)
```
claude -p "Use /speckit-clarify para perguntas de de-risco"
```

### 3. Plan
```
claude -p "Use /speckit-plan para criar o plano"
```
Gera: `specs/login/plan.md`

### 4. Tasks
```
claude -p "Use /speckit-tasks para quebrar em tasks"
```
Gera: `specs/login/tasks.md`

### 5. Implement
```
claude -p "Use /speckit-implement para executar as tasks"
```

### 6. Converge
```
claude -p "Use /speckit-converge para verificar conformidade"
```

## Dica
Edite a spec manualmente se o Claude errar algum ponto. Sempre antes de codar.
