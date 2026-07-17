### Software Engineer

I build and operate products across Flutter, Dart, and Go. My work sits at the boundaries where client applications, local data, native integrations, queues, and production infrastructure have to remain understandable and correct.

#### Open source

- **Merged · [Dart MCP #524](https://github.com/dart-lang/ai/pull/524)** — separated reusable server feature registration from the legacy initialization handshake, preserving legacy compatibility while making the lifecycle usable beyond that transport path.
- [FlutterFire #18443](https://github.com/firebase/flutterfire/pull/18443) — fixed a WebKit initialization race by making Firebase script loading deterministic.
- [Drift #3835](https://github.com/simolus3/drift/pull/3835) — corrected SQLite boolean-default schema verification with regression coverage.
- [Flutter Form Builder #1512](https://github.com/flutter-form-builder-ecosystem/flutter_form_builder/pull/1512) — fixed invalid dropdown initial values on the first build.
- [Fiber Recipes #4997](https://github.com/gofiber/recipes/pull/4997) — added a tested Fiber and Asynq background-jobs recipe.
- **Under review · [Flutter #189500](https://github.com/flutter/flutter/pull/189500)** — makes the web first-frame event wait for asynchronous scene rendering and the next browser frame, preventing splash removal before SkWasm rasterization completes.

#### Packages on pub.dev

- [simdjson_dart](https://pub.dev/packages/simdjson_dart) — simdjson over FFI; lazy JSON Pointer access reads selected fields 5-15x faster than full decoding.
- [resilience](https://pub.dev/packages/resilience) — retry with backoff and jitter, circuit breaker, timeout, rate limiter, and bulkhead, zero dependencies.
- [instructor_dart](https://pub.dev/packages/instructor_dart) — typed, validated structured outputs from LLMs without code generation.
- [mcp_probe](https://pub.dev/packages/mcp_probe) — test harness and conformance checks for MCP servers, built on the official dart_mcp client.
- [llm_eval](https://pub.dev/packages/llm_eval) — assertion checks, LLM-as-judge scoring, and response caching for testing LLM output in CI.
- [rag_kit](https://pub.dev/packages/rag_kit) — chunking, embeddings, vector search, and context building with a bring-your-own-embedder contract.
- [vector_kit](https://pub.dev/packages/vector_kit) — SIMD-accelerated vector math and top-k search over packed matrices.
- [find_in_page](https://pub.dev/packages/find_in_page) — Ctrl+F for Flutter: match highlighting, navigation, and scroll-into-view.
- [skeleton_shimmer](https://pub.dev/packages/skeleton_shimmer) — shimmer loading effect, pixel-compatible with the shimmer package, with reduced-motion support.
- [text_autosize](https://pub.dev/packages/text_autosize) — auto-sizing text, TextScaler-aware and API-compatible with auto_size_text.

#### Selected systems

- [queue-inspector-mcp](https://github.com/Yusufihsangorgel/queue-inspector-mcp) — queue inspection and operations for Asynq and BullMQ.
- [go-multitenant-gateway](https://github.com/Yusufihsangorgel/go-multitenant-gateway) — tenant resolution, JWT authentication, and per-tenant rate limiting in one Go binary.
- [redis_task_queue](https://github.com/Yusufihsangorgel/redis_task_queue) — a server-side Dart queue with retries, dead letters, and weighted scheduling.
- [constellation_particles](https://github.com/Yusufihsangorgel/constellation_particles) — a dependency-free Flutter particle field with spatial-grid neighbour lookup.

[Portfolio](https://developeryusuf.com) · [Writing](https://yusufihsangorgel.github.io) · [dev.to](https://dev.to/yusufihsangorgel) · [Medium](https://medium.com/@developeryusufihsan) · [LinkedIn](https://www.linkedin.com/in/yusuf-ihsan-g%C3%B6rgel/)
