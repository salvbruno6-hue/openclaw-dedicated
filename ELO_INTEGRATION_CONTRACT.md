# OpenClaw Dedicated — ELO Integration Contract

## Authority

- ELO Cognitivo (`salvbruno6-hue/Cognitico_IA-corporative`) is the canonical cognitive authority.
- OpenClaw Dedicated is an integration/development repository, not a parallel ELO authority.
- OpenClaw MUST NOT create, mutate, or promote ELO canonical knowledge independently.
- Canonical learning occurs only through ELO governance and arbitrated results.

## Domain boundary

OpenClaw operates as an external execution/integration capability. It may provide tools, execution, observations, and technical capabilities requested by ELO, but returned results are advisory/evidentiary until accepted through ELO governance.

## Simbionte boundary

When acting as part of the ELO Simbionte architecture, OpenClaw follows the same external-provider boundary used for Hermes:

1. ELO determines intent, authority, policy, and allowed capability.
2. The external agent receives only the authorized execution request.
3. The external agent executes within its own operational boundary.
4. Results return with provenance, status, evidence, and errors.
5. ELO validates and arbitrates the result before any canonical mutation.

## Prohibited

- Parallel cognitive memory.
- Independent ELO authority.
- Direct Forge → Core promotion.
- Silent canonical mutation.
- Treating OpenClaw local state as canonical ELO memory.
- Bypassing ELO governance to execute privileged actions.

## Required integration properties

Every ELO-facing adapter SHOULD preserve:

- request/correlation identity;
- tenant/domain scope;
- capability identity;
- provenance;
- authorization context;
- execution outcome;
- evidence references;
- explicit failure/degraded status.

## Relationship to Hermes

OpenClaw is a separate external integration surface. Hermes remains the established ELO Symbionte execution bridge. OpenClaw does not replace Hermes or redefine the Hermes contract unless a future ELO governance decision explicitly promotes such a change.

## Repository role

This repository is dedicated to OpenClaw integration and development. ELO-specific adapters, contracts, and tests belong at the boundary; canonical cognitive rules remain in the ELO Cognitivo repository.
