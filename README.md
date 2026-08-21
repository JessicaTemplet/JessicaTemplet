### Jessica Templet

I come at engineering from discrete mathematics rather than a CS degree.
Structure first, implementation second. Most of what I build lives in
backend reliability, distributed systems, and data integrity, the kind of
problems that don't have an off-the-shelf answer.

I am a researcher first. I believe you cannot effectively solve a problem if
you don't understand every facet of said problem.

I started coding as a hobby after I got out of the army. I started with
Python, then decided to learn Rust and reinforced my understanding porting
Python projects to Rust. From there I moved through Go, TypeScript, React
and JavaScript, and now Ruby on Rails, with Rust remaining my preferred
language and where my personal projects live, followed closely by Go. Along
the way I picked up SQL, PostgreSQL, GraphQL, Docker, Axum, Tauri, Vite,
Git, MapLibre GL, Playwright, tokio, and DAX.

My path wasn't the typical linear path, I learned what I needed as I needed
to learn it. Which I feel like resulted in a stronger understanding because
each new thing served a specific purpose and was necessary. That has served
me well and at the same time has left some gaps. Luckily I am a very fast
learner with a level of curiosity typically reserved for suicidal felines.

I have five published research papers in a belief manifold series about AI
memory architecture. I also build GNN PDEs for CFD applications. I make
it a point not to hide my mistakes. I own them and I own my correction
of them. The only mistake you should be ashamed of is the one you try to
hide.

Most of what's here is portfolio and personal challenges because I like
jumping in head first, clueless, and seeing if I can figure it out. My
commercial work, including VeritasMemoria, is private for obvious reasons,
so what's public is a slice, not the whole picture.

#### Rust

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
- [Waterfall-Enrichment](https://github.com/JessicaTemplet/Waterfall-Enrichment):
  a lead enrichment pipeline that scores how much is still unknown about a
  lead and only pays for a data source when it needs to
- [Owner_Finance_App](https://github.com/JessicaTemplet/Owner_Finance_App):
  owner finance property finder
- [anagraphe](https://github.com/JessicaTemplet/anagraphe): scans GitHub
  and local repos and catalogs each project's tech stack, secrets
  inventory, cloud dependencies, and subscriptions into a dashboard (Rust
  core, TypeScript/Tauri frontend)

Five of the above (rust_internals, resp_kv_store, zero_copy_json,
turbogrep, binsg) also exist as faithful Python ports, see
[rust-scripts-python-ports](https://github.com/JessicaTemplet/rust-scripts-python-ports)
under Python below.

#### Go

- [limes](https://github.com/JessicaTemplet/limes): multi-cloud network
  egress guard and diagnostics, CIDR overlap detection, policy checks
  (AWS SCP / Azure Policy / GCP Org Policy), and remediation suggestions
- [flagforge](https://github.com/JessicaTemplet/flagforge): a standalone
  real-time feature flag and configuration engine
- [kvstore](https://github.com/JessicaTemplet/kvstore): a lightweight,
  network-accessible, in-memory key-value store speaking a
  Redis-compatible subset of RESP over TCP, standard library only
- [linkcheck](https://github.com/JessicaTemplet/linkcheck): a concurrent
  CLI link checker and asset crawler, worker pool, context-based
  cancellation, token-bucket rate limiting, robots.txt support, standard
  library only

#### Python

- [rust-scripts-python-ports](https://github.com/JessicaTemplet/rust-scripts-python-ports):
  Python 3.13 ports of all five of the Rust projects above, with notes on
  where the port is faithful versus where it's necessarily conceptual
  (memory layout and zero-copy slicing don't have a literal Python
  equivalent)
- [waterfall-enrichment-python](https://github.com/JessicaTemplet/waterfall-enrichment-python):
  Python implementation of the doubt-score-gated enrichment pipeline,
  Redis job queue, SQLAlchemy storage
- [gnn-pde-cfd](https://github.com/JessicaTemplet/gnn-pde-cfd): training
  GNNs to imitate classical PDE solvers, one class at a time, elliptic,
  parabolic, hyperbolic, each validated against a finite-difference
  reference
- [Atomic-Rate-Limiter](https://github.com/JessicaTemplet/Atomic-Rate-Limiter):
  a sliding-window-log rate limiter using Lua scripting for atomicity
- [Idempotent-API-Layer](https://github.com/JessicaTemplet/Idempotent-API-Layer):
  Redis-backed idempotency for distributed systems
- [Background-Job-Processor](https://github.com/JessicaTemplet/Background-Job-Processor):
  an async task queue built on Python and Redis
- [Immutable-Audit-Log](https://github.com/JessicaTemplet/Immutable-Audit-Log):
  a high-integrity activity tracking service for compliance and observability
- [AgentJournalClaw](https://github.com/JessicaTemplet/AgentJournalClaw):
  an agent that writes journal entries reliably

#### TypeScript

- [github-mcp](https://github.com/JessicaTemplet/github-mcp): an MCP
  server giving Claude direct access to GitHub (repos, files, issues,
  PRs, Actions) via a personal access token, built to fill the gap where
  Claude chat has no first party GitHub connector
- [zoho-mail-mcp](https://github.com/JessicaTemplet/zoho-mail-mcp): an
  MCP server giving Claude read access to Zoho Mail, list/search inbox,
  read emails, save draft replies for approval, never sends

#### Ruby

- [SaaSTenant](https://github.com/JessicaTemplet/SaaSTenant): a Rails 8
  multi-tenant SaaS starter with subdomain-per-tenant routing,
  defense-in-depth tenant isolation, a from-scratch Fugue CRDT for
  real-time collaborative editing over ActionCable, and LemonSqueezy
  webhook handling

#### Languages and tools

Rust, Python, JavaScript, TypeScript, React, SQL, PostgreSQL, GraphQL,
Docker, Axum, Tauri, Vite, MapLibre GL, Playwright, tokio, Git, DAX.

SQL, PostgreSQL, GraphQL, and DAX work obviously lives in client databases,
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

How to reach me: through [Templet Solutions](mailto:jessica@templetsolutions.com).
