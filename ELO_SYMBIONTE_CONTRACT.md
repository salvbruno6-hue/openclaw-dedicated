# OpenClaw Dedicated — ELO Simbionte Contract

OpenClaw is an external capability provider connected to ELO only through explicit adapters/contracts.

### Protocol

`ELO → authorize → OpenClaw → execute → evidence/outcome → ELO validate → arbitrate → canonical learning`

OpenClaw MUST preserve the boundary between execution and cognition. It can execute and report; ELO remains responsible for cognitive authority, decisions, governance, and canonical learning.

### Forge

Forge is an internal construction and experimentation layer of ELO. OpenClaw may be used as an external execution capability by Forge, but Forge artifacts do not become Core merely because OpenClaw executed them. Promotion remains subject to ELO's governance and validation gates.

### Security

No credential, secret, or private operational state is to be committed to this repository. Runtime secrets remain outside source control.
