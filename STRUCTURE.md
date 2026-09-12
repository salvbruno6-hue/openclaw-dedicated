# Estrutura de Arquivos - OpenClaw Dedicated

## Hierarquia Completa

```
openclaw-dedicated/
│
├── 📁 openclaw-core/
│   ├── src/
│   │   ├── agent/
│   │   ├── skills/
│   │   ├── executor/
│   │   └── governance/
│   └── README.md
│
├── 📁 clawhub/
│   ├── registry/
│   │   ├── skills/
│   │   └── plugins/
│   ├── validators/
│   └── README.md
│
├── 📁 lobster/
│   ├── src/
│   │   ├── cli/
│   │   ├── shell/
│   │   └── commands/
│   └── README.md
│
├── 📁 integrations/
│   ├── peekaboo/
│   │   ├── src/
│   │   │   ├── screenshot/
│   │   │   ├── vqa/
│   │   │   └── models/
│   │   └── README.md
│   │
│   ├── mcporter/
│   │   ├── src/
│   │   │   ├── protocol/
│   │   │   ├── wrapper/
│   │   │   └── adapters/
│   │   └── README.md
│   │
│   └── acpx/
│       ├── src/
│       │   ├── cli/
│       │   ├── client/
│       │   └── auth/
│       └── README.md
│
├── 📁 platform-clis/
│   ├── discrawl/          # Discord CLI
│   ├── slacrawl/          # Slack CLI
│   ├── wacli/             # WhatsApp CLI
│   ├── gogcli/            # Google Workspace CLI
│   └── imsg/              # Apple Messages CLI
│
├── 📁 platform-support/
│   ├── openclaw-windows-node/     # Windows
│   ├── esp-openclaw-node/         # Sistemas Embarcados
│   └── openclaw-ansible/          # Deployment
│
├── 📄 README.md
├── 📄 GOVERNANCE.md
├── 📄 STRUCTURE.md
└── 📄 package.json
```

## Categorias Principais

### 1. **Core** (Sistema Central)
- `openclaw-core/` - Agente IA principal
- `clawhub/` - Registry de skills/plugins
- `lobster/` - Shell de workflows

### 2. **Integrations** (Extensões)
- `peekaboo/` - Screenshots e VQA
- `mcporter/` - MCP wrapper
- `acpx/` - ACP sessions

### 3. **Platform CLIs** (Integrações de Plataforma)
- Discord, Slack, WhatsApp, Google Workspace, Apple Messages

### 4. **Platform Support** (Suporte a Sistemas)
- Windows, Sistemas Embarcados, Deployment

## Tecnologias
- **Linguagem Principal**: TypeScript
- **Runtime**: Node.js
- **Deployment**: Ansible
- **Plataformas**: Windows, Linux, Embedded Systems
