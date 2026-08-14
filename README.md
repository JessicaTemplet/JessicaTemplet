### Jessica Templet

I come at engineering from discrete mathematics rather than a CS degree.
Structure first, implementation second. Most of what I build lives in
backend reliability, distributed systems, and data integrity, the kind of
problems that don't have an off-the-shelf answer.

I started in Python. I ported my own projects to Rust to actually learn the
language, ended up preferring to build new things in Rust for a while, then
found out the market wants Python more than Rust, so I ported the Rust-only
work back to Python for reach. Rust is still where my personal projects
live. The TypeScript projects exist to prove I can do that too. A few of
these pairs live side by side below.

**Currently building:** VeritasMemoria, a local-first AI memory and
knowledge governance system for regulated industries, built on hyperbolic
geometry, cryptographic audit trails, and formal privacy proofs. Solo
architect, from research through implementation.

#### Systems programming (Rust originals, ported to Python for reach)

- [resp_kv_store](https://github.com/JessicaTemplet/resp_kv_store): a
  Redis-compatible key-value store speaking RESP over TCP
- [zero_copy_json](https://github.com/JessicaTemplet/zero_copy_json): a
  hand-written JSON parser with zero-copy string borrowing
- [turbogrep](https://github.com/JessicaTemplet/turbogrep): a
  multi-threaded, memory-mapped grep clone
- [binsg](https://github.com/JessicaTemplet/binsg): a local semantic grep
  using binary-quantized embedding search
- [rust_internals](https://github.com/JessicaTemplet/rust_internals): a
  bump-allocation arena and a hand-built thread pool from scratch
- [rust-scripts-python-ports](https://github.com/JessicaTemplet/rust-scripts-python-ports):
  Python 3.13 ports of all five of the above, with notes on where the port
  is faithful versus where it's necessarily conceptual (memory layout and
  zero-copy slicing don't have a literal Python equivalent)

#### Backend reliability and distributed systems

- [Atomic-Rate-Limiter](https://github.com/JessicaTemplet/Atomic-Rate-Limiter):
  a sliding-window-log rate limiter using Lua scripting for atomicity
- [Idempotent-API-Layer](https://github.com/JessicaTemplet/Idempotent-API-Layer):
  Redis-backed idempotency for distributed systems
- [Background-Job-Processor](https://github.com/JessicaTemplet/Background-Job-Processor):
  an async task queue built on Python and Redis
- [Immutable-Audit-Log](https://github.com/JessicaTemplet/Immutable-Audit-Log):
  a high-integrity activity tracking service for compliance and observability
- [Waterfall-Enrichment](https://github.com/JessicaTemplet/Waterfall-Enrichment)
  / [waterfall-enrichment-python](https://github.com/JessicaTemplet/waterfall-enrichment-python):
  a lead enrichment pipeline that scores how much is still unknown about a
  lead and only pays for a data source when it needs to

#### Research

- [rhetorical-geometry-analysis](https://github.com/JessicaTemplet/rhetorical-geometry-analysis):
  political rhetoric analysis built on a geometric field theory of belief
  dynamics

#### Languages and tools

Rust, Python, JavaScript, TypeScript, React, SQL, PostgreSQL, GraphQL,
Docker, Axum, Tauri, Vite, MapLibre GL, Playwright, tokio, Git, DAX.

SQL, PostgreSQL, GraphQL, and DAX work mostly lives in client databases,
APIs, and BI reports, not the kind of thing you post to GitHub, so it won't
show up in the project list above even though it's a real chunk of the
work.

**Systems programming:** memory-mapped I/O, zero-copy parsing, protocol
implementation (RESP/TCP), memory allocators, concurrency primitives,
unsafe Rust.

**Math and theory:** hyperbolic geometry, spectral graph theory,
topological data analysis, persistent homology, differential geometry,
discrete mathematics, formal methods.

**AI and security:** AI safety, AI governance, knowledge representation,
memory architecture, cryptographic audit trails, privacy-by-architecture,
zero-knowledge proofs.

**Architecture:** system design, API design, database schema design, data
pipeline architecture, local-first software, full-stack development.

**Other:** technical writing, research.

How to reach me: through [Templet Solutions](https://github.com/JessicaTemplet/Templet-Solutions).
