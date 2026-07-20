Software engineer working across Flutter, Dart, and Go, mostly where client
apps, native code, local data, and infrastructure meet and have to stay correct
under load. I publish open-source packages, contribute upstream, and write about
the work.

#### Native, over FFI

Bindings that compile real C and C++ libraries from source through Dart's build
hooks, so there is nothing to install and the same code runs on Linux, macOS,
and Windows.

- [simdjson_dart](https://pub.dev/packages/simdjson_dart): SIMD JSON, lazy field access over simdjson
- [blake3_ffi](https://pub.dev/packages/blake3_ffi): BLAKE3 hashing at native throughput
- [re2](https://pub.dev/packages/re2): linear-time regex, immune to catastrophic backtracking
- [image_ffi](https://pub.dev/packages/image_ffi): decode, resize, and encode images via stb
- [audio_decode](https://pub.dev/packages/audio_decode): Ogg Vorbis and MP3 to PCM
- [xlsxwriter](https://pub.dev/packages/xlsxwriter): write .xlsx with a constant-memory mode

#### LLM tooling

- [instructor_dart](https://pub.dev/packages/instructor_dart): typed, validated structured outputs
- [rag_kit](https://pub.dev/packages/rag_kit): chunking, embeddings, retrieval, context building
- [llm_eval](https://pub.dev/packages/llm_eval): assertions and LLM-as-judge scoring for CI
- [mcp_probe](https://pub.dev/packages/mcp_probe): a conformance harness for MCP servers
- [hf_tokenizers](https://pub.dev/packages/hf_tokenizers): byte-exact HuggingFace tokenization over FFI
- [stream_struct](https://pub.dev/packages/stream_struct): a token stream parsed into the typed object as it fills in

#### Flutter

- [photo_zoom](https://pub.dev/packages/photo_zoom): pan, zoom, and gallery, zooming at the touch point
- [expandable_plus](https://pub.dev/packages/expandable_plus): accordion panels, one open at a time
- [skeleton_shimmer](https://pub.dev/packages/skeleton_shimmer): shimmer loading placeholders
- [text_autosize](https://pub.dev/packages/text_autosize): text that fits its space
- [find_in_page](https://pub.dev/packages/find_in_page): Ctrl+F for Flutter
- [constellation_particles](https://pub.dev/packages/constellation_particles): an animated particle field

#### Infrastructure

- [resilience](https://pub.dev/packages/resilience): retries, circuit breaker, rate limiter, bulkhead
- [vector_kit](https://pub.dev/packages/vector_kit): vector math and top-k search over packed matrices
- [redis_task_queue](https://pub.dev/packages/redis_task_queue): a server-side queue with retries and dead letters
- [flutter_prerender](https://pub.dev/packages/flutter_prerender): prerender Flutter web for search engines
- [queue-inspector-mcp](https://github.com/Yusufihsangorgel/queue-inspector-mcp): queue operations for Asynq and BullMQ
- [go-multitenant-gateway](https://github.com/Yusufihsangorgel/go-multitenant-gateway): tenant routing, auth, and rate limiting in Go

#### Upstream

Merged fixes and features into [dart-lang/ai](https://github.com/dart-lang/ai/pull/524)
([twice](https://github.com/dart-lang/ai/pull/528)),
[FlutterFire](https://github.com/firebase/flutterfire/pull/18443),
[Drift](https://github.com/simolus3/drift/pull/3835),
[Flutter Form Builder](https://github.com/flutter-form-builder-ecosystem/flutter_form_builder/pull/1512),
and [Bun](https://github.com/uptrace/bun/pull/1390) on the Go side.
In review: an [engine fix](https://github.com/flutter/flutter/pull/189500) for Flutter web's
first frame, and [decoded-message channels](https://github.com/dart-lang/ai/pull/531)
for package:dart_mcp.

[Portfolio](https://developeryusuf.com) · [Writing](https://yusufihsangorgel.github.io) · [dev.to](https://dev.to/yusufihsangorgel) · [Medium](https://medium.com/@developeryusufihsan) · [LinkedIn](https://www.linkedin.com/in/yusuf-ihsan-g%C3%B6rgel/)
