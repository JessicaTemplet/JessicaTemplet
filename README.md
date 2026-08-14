### Jessica Templet

I specialize in solving problems that don't have easy solutions. Self-taught
engineer, focused on backend reliability, distributed systems, and data
integrity.

I build the same system twice on purpose: once in Rust to understand what's
actually happening at the memory and concurrency level, and once in Python
to see what a language with different guarantees does instead. A few of
these pairs live side by side below.

**Currently building:** VeritasMemoria, a local-first AI memory and
knowledge governance system for regulated industries, built on hyperbolic
geometry, cryptographic audit trails, and formal privacy proofs. Solo
architect, from research through implementation.

#### Systems programming (Rust, ported to Python for comparison)

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

Python, Rust, TypeScript, JavaScript, SQL, DAX.

How to reach me: through [Templet Solutions](https://github.com/JessicaTemplet/Templet-Solutions).
