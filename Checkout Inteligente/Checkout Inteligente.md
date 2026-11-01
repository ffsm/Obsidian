# Checkout Inteligente

> Micro-frontend de chat conversacional para agentes comerciais de banco.

## Visão
Interface conversacional (texto + áudio) para atores comerciais interagirem com um Agente de IA que cria e atualiza dados no Microsoft Dynamics 365 (Dataverse). Automatiza processos que antes eram manuais.

## Estrutura do Projeto
```
Checkout Inteligente/
├── obsidian/          ← docs e notas SDD
├── sdd/               ← Spec Kit (specs, planos, tasks)
└── src/               ← código
    ├── mfe-chat/          ← micro-frontend
    ├── agent-orchestration/ ← orquestrador IA
    └── dynamics-connector/  ← connector Dynamics 365
```

## Stack
- **MFE**: a definir
- **Comunicação**: Dynamics 365 (Dataverse) API
- **Canais**: chat texto + áudio
- **IA**: agentes LLM

## Metodologia
Spec-Driven Development + Claude Code
