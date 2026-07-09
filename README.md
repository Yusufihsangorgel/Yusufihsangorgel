### Hi, I'm Yusuf 👋

Software engineer from Turkey. I build **Flutter** apps and the **Go** backends behind them, and I run most of what I ship on infrastructure I operate myself.

That infrastructure is a small **self-hosted platform** — a single Go API gateway (17 product modules, ~500 routes), background workers, and self-hosted auth — serving a suite of apps from a handful of nodes. I lean toward small, readable, single-binary tools over heavy dependencies, and I write about the decisions behind them.

#### Stack

Go (Fiber · Asynq) · Flutter / Dart · TypeScript / Next.js · PostgreSQL · Redis · Docker & self-hosted (Swarm, Dokploy)

#### Selected work

**[queue-inspector-mcp](https://github.com/Yusufihsangorgel/queue-inspector-mcp)** — an MCP server that lets an AI agent inspect and operate Redis-backed job queues (Asynq and BullMQ): per-state counts, job detail, safe retries and dead-letter handling. Mutations run each library's own atomic scripts; a read-only mode strips them entirely. On [npm](https://www.npmjs.com/package/queue-inspector-mcp).

**[go-multitenant-gateway](https://github.com/Yusufihsangorgel/go-multitenant-gateway)** — a single-binary multi-tenant API gateway in Go: tenant resolution, per-tenant rate limiting, JWT auth, and a module-per-product pattern. The reference version of the gateway I run in production, with the architecture tradeoffs written up.

**[redis_task_queue](https://github.com/Yusufihsangorgel/redis_task_queue)** — a small Redis-backed task queue for server-side Dart: enqueue from the request path, process in a worker with retries, a dead-letter list, and weighted queues. The Asynq model, brought to a gap in the Dart ecosystem. On [pub.dev](https://pub.dev/packages/redis_task_queue).

**[constellation_particles](https://github.com/Yusufihsangorgel/constellation_particles)** — a mouse-reactive particle field for Flutter. A spatial hash grid keeps the connecting-lines pass close to O(n) instead of O(n²). Zero runtime dependencies. On [pub.dev](https://pub.dev/packages/constellation_particles).

**[Flutter Cinematic Portfolio](https://github.com/Yusufihsangorgel/Flutter-Web-Portfolio)** — a portfolio built in Flutter Web: scene-driven backgrounds, a dependency-free particle engine, 7 languages, 187 tests. Not a template.

#### Recent writing

- [A Redis MCP Server Shows You Keys. When a Queue Breaks, You Need Jobs.](https://yusufihsangorgel.github.io/2026/07/08/queue-inspector-mcp.html)
- [I Run 17 Products From One Go Binary. Here's the Case For and Against.](https://yusufihsangorgel.github.io/2026/07/07/one-go-binary-for-and-against.html)
- [I Built an LLM Filter That Prefers Silence Over Slop — and the Eval Harness That Keeps It Honest](https://dev.to/yusufihsangorgel/i-built-an-llm-filter-that-prefers-silence-over-slop-and-the-eval-harness-that-keeps-it-honest-3pce)
- [Server-Side Dart Doesn't Have a Task Queue. So I Ported the Idea From Go.](https://yusufihsangorgel.github.io/2026/07/08/asynq-for-dart.html)
- [In Praise of the Boring Library](https://medium.com/@developeryusufihsan/in-praise-of-the-boring-library-e2b2430ba7e2)

#### Elsewhere

- Blog — [yusufihsangorgel.github.io](https://yusufihsangorgel.github.io)
- dev.to — [@yusufihsangorgel](https://dev.to/yusufihsangorgel)
- Medium — [@developeryusufihsan](https://medium.com/@developeryusufihsan)
- LinkedIn — [yusuf-ihsan-görgel](https://www.linkedin.com/in/yusuf-ihsan-g%C3%B6rgel/)

<sub>📍 Antalya, Turkey (remote) · ✉️ developeryusuf@icloud.com</sub>
