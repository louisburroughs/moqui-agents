# moqui-agents
durion-moqui-frontend component that holds agent code

## Purpose

Provide a Moqui component home for agent-related code and assets (prompts, scripts, and helper logic) that support developer and operator workflows within the Durion platform.

## Scope

In scope:
- Agent prompt assets, templates, and local tooling that runs in the Moqui context
- Shared utilities for agent-driven workflows (analysis helpers, adapters) where implemented
- Documentation and examples for using agents safely with Durion

Out of scope:
- Business domain ownership (agents should consume domain rules rather than redefine them)
- Storing secrets or credentials in-repo (must use environment/secret stores)
