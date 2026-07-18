# Awesome Agent Memory [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of memory systems, frameworks, benchmarks, and research for AI agents.

Agents forget between sessions and between tools. "Agent memory" is the growing category of systems that decide what to keep, connect related facts, and improve recall over time. This list tracks the tools and research in that space.

Contributions welcome. Please keep entries factual and free of marketing language. One tool per pull request, alphabetical within each section.

## Contents

- [Managed memory APIs and services](#managed-memory-apis-and-services)
- [Open-source frameworks and engines](#open-source-frameworks-and-engines)
- [MCP memory servers](#mcp-memory-servers)
- [Benchmarks and evaluation](#benchmarks-and-evaluation)
- [Papers](#papers)
- [Contributing](#contributing)

## Managed memory APIs and services

- [Mem0](https://github.com/mem0ai/mem0) - Open-source memory layer plus a managed cloud, with many framework integrations.
- [Mnemoverse](https://github.com/mnemoverse/mcp-memory-server) - Persistent memory API for AI agents over MCP. Scores importance on write, strengthens associations between concepts (Hebbian), and re-ranks recall from outcome feedback. MIT client, managed engine.
- [Supermemory](https://github.com/supermemoryai/supermemory) - Memory API and "second brain" for AI apps and agents.
- [Zep](https://github.com/getzep/zep) - Memory platform built on a temporal knowledge graph (Graphiti), with a managed cloud.

## Open-source frameworks and engines

- [Cognee](https://github.com/topoteretes/cognee) - Memory platform that turns your data into a knowledge graph via an extract-cognify-load pipeline.
- [Graphiti](https://github.com/getzep/graphiti) - Temporal knowledge-graph engine for agent memory (powers Zep).
- [LangMem](https://github.com/langchain-ai/langmem) - Long-term memory utilities for LangGraph agents.
- [Letta](https://github.com/letta-ai/letta) - Agent framework with self-editing memory, from the team behind MemGPT.
- [Memori](https://github.com/MemoriLabs/Memori) - Memory engine for AI agents and applications.

## MCP memory servers

Memory servers that connect to any Model Context Protocol client (Claude, Cursor, VS Code, ChatGPT, and others).

- [Mnemoverse](https://github.com/mnemoverse/mcp-memory-server) - Hosted persistent memory over MCP; one key or OAuth across MCP clients.
- [OpenMemory](https://github.com/mem0ai/mem0) - Local-first, private MCP memory server (part of the Mem0 project).

## Benchmarks and evaluation

Common suites used to evaluate agent memory (canonical links welcome via PR):

- LoCoMo - long-conversation memory.
- LongMemEval - long-term interactive memory.
- BEAM - large-scale memory benchmark.

## Papers

- [SLoD: Semantic Level of Detail for Knowledge Graphs](https://arxiv.org/abs/2603.08965) - Discovering abstraction boundaries via spectral heat diffusion (Mnemoverse).
- [MemGPT: Towards LLMs as Operating Systems](https://arxiv.org/abs/2310.08560) - Virtual context management (the origin of Letta).

## Contributing

Open a pull request adding one tool, in the right section, in alphabetical order, with a short factual description (no marketing language). New sections are welcome if a genuine category is missing.

## License

[CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/). To the extent possible under law, contributors have waived all copyright and related rights to this list.
