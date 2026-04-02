# generos-agents

The canonical agentic layer for the [Generos](https://generos.io) ecosystem.

## What This Is

`generos-agents` is a curated collection of agent skills, protocols, and foundational documents that any agent — internal or external — can adopt to interact authentically with the Generos platform.

This is not a code SDK. It is a skill and protocol package: the philosophical and operational layer that gives agents the context to understand not just *how* to interact with Generos, but *why*.

## Who It's For

- **User agents** — personal AIs representing individual Generos users, operating their vault and generosity actions on their behalf
- **External agents** — third-party AIs from other platforms and applications that want to participate in the Generos ecosystem

## Repository Structure

```
generos-agents/
  docs/
    manifesto.md           ← the human-facing philosophical foundation
    agent-manifesto.md     ← a declaration for agents entering the ecosystem
    values.md              ← what Generos stands for operationally
    glossary.md            ← vault, gencoin, treasury defined
  skills/
    generos-core/          ← foundational context skill any agent adopts
    generos-vault/         ← how to interact with a user's vault
    generos-treasury/      ← community treasury mechanics
    generos-onboarding/    ← onboarding new users and agents
  protocols/
    agent-identity.md      ← how agents represent users in Generos
    giving-protocol.md     ← rules for recording generosity actions
    gencoin-protocol.md    ← how rewards flow
  examples/
    personal-agent.md      ← example: a user's AI adopting generos-core
    external-agent.md      ← example: a third-party agent integrating
```

## Start Here

Read the [Generos Manifesto](./docs/manifesto.md) for the human-facing foundation. Then read the [Agent Manifesto](./docs/agent-manifesto.md) — a direct declaration for agents entering this ecosystem. Any agent that adopts these skills inherits their values.

## The Vision

As AI accelerates, the agents people use to navigate the world will need to know how to show up inside economic systems — not just as task executors, but as value-aligned participants. `generos-agents` is how you give your agent the context to show up in Generos the right way.

> *You bring the why. Your agents handle the how.*

## Generos

Generos is a regenerative giving economy — a new economic system where generosity is the engine of wealth, not a sacrifice against it. Learn more at [generos.io](https://generos.io).
