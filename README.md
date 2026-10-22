### Hi there 👋

Sangin Geum — building tools for local-first AI agents and high-performance C++ systems.

Focused on:
- **Agent infrastructure** that stays deterministic, inspectable, and fully under the owner's control
- **C++20 networking libraries** with strong performance characteristics
- Local-first stacks (Ollama + Qdrant) that never require the cloud

---

### Featured Projects

| Project | Description | Stack |
|---------|-------------|-------|
| **[code-indexer](https://github.com/sangingeum/code-indexer)** | Semantic code search for agents. One-shot CLI + MCP server over Qdrant + Ollama. Agents never index themselves — they just search. | Python, tree-sitter, Qdrant, Ollama |
| **[tackboard](https://github.com/sangingeum/tackboard)** | Project-scoped task board for multi-agent coordination. CLI-first, SQLite-backed, dependency DAG, claim system, read-only human board. | Python, SQLite |
| **[vector-memory](https://github.com/sangingeum/vector-memory)** | Persistent vector memory for agents. MCP + CLI over the same core. Deduplication, superseding, filtering, lifecycle management. | Python, Qdrant, Ollama |
| **[calc-engine](https://github.com/sangingeum/calc-engine)** | Deterministic, subcommand-driven CLI math engine designed for agents. Strict stdout contract, finance, statistics, distributions, matrices. | Python |
| **[Edriel](https://github.com/sangingeum/Edriel)** | C++20 multicast pub/sub library with automatic discovery and typed protobuf messaging. Best-effort + reliable QoS paths. | C++20, Asio, gRPC, Protobuf |

---

### Other Notable Work

- **[NetworkProgramming](https://github.com/sangingeum/NetworkProgramming)** — C++ networking examples with Asio
- **[Algorithm-and-DataStructure](https://github.com/sangingeum/Algorithm-and-DataStructure)** — Classic algorithms & data structures in C++
- Various older game / visualization experiments (Gomoku, Breakout, A*, RayCasting, etc.)

---

### Tech Interests

- Local AI agent tooling (MCP, CLI-first design, deterministic contracts)
- C++20 systems programming & high-performance networking
- SQLite + vector databases for agent memory and coordination
- Clean, agent-friendly CLI surfaces (one-shot commands, stable JSON, clear exit codes)

---

*Building tools I actually want to use with my own agents.*
