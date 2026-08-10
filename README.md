Software engineer working across Flutter, Dart, and Go, where client apps, native code, and infrastructure have to stay correct under load.

#### Upstream

Reworking `package:dart_mcp` for the 2026 MCP specification: fourteen pull requests are merged, from the [lifecycle split](https://github.com/dart-lang/ai/pull/524) and [request-scoped dispatch](https://github.com/dart-lang/ai/pull/528) to the [streamable HTTP POST handler](https://github.com/dart-lang/ai/pull/572) that the 2026-07-28 revision defines. Four changes landed in the Dart SDK analyzer: it now [rejects Struct-constrained mixin applications](https://github.com/dart-lang/sdk/commit/94c4d27546cc90b81312735055b0fc45b3fcefca), [handles `NativeCallable` arguments independently of source order](https://github.com/dart-lang/sdk/commit/ab364ca4aa5a9cef2bfb411c5508924606506e3d), [reports an inherited getter and setter whose types disagree](https://github.com/dart-lang/sdk/commit/a3b24110dc4ac6edb4a85c171d264c0034932ec0), and [covers `fromFunction` against invalid and unresolved input](https://github.com/dart-lang/sdk/commit/623309d91db2). In `package:code_assets`, a [validator now reads a dynamic library's architecture from its file headers](https://github.com/dart-lang/native/pull/3484). Also merged fixes into [shelf](https://github.com/dart-lang/shelf/pull/536), [vector_graphics_compiler](https://github.com/flutter/packages/pull/12199), [Drift](https://github.com/simolus3/drift/pull/3835), [FlutterFire](https://github.com/firebase/flutterfire/pull/18443), [Retrofit](https://github.com/trevorwang/retrofit.dart/pull/921), and [Bun](https://github.com/uptrace/bun/pull/1390); more across dart-lang, flutter, and grpc-go on my profile.

#### Packages

Twenty-three on pub.dev. Several bind native C and C++ libraries through Dart's build hooks, with nothing to install beyond a C++ toolchain:

- [re2](https://pub.dev/packages/re2): linear-time regex, immune to catastrophic backtracking
- [simdjson_dart](https://pub.dev/packages/simdjson_dart): SIMD JSON parsing over simdjson
- [blake3_ffi](https://pub.dev/packages/blake3_ffi): BLAKE3 hashing over the official C implementation, with the NEON kernel on arm64

Others are pure Dart:

- [resilience](https://pub.dev/packages/resilience): retries, circuit breaker, rate limiter, bulkhead, and hedged calls
- [redis_task_queue](https://pub.dev/packages/redis_task_queue): a server-side queue with retries and dead letters
- [mcp_probe](https://pub.dev/packages/mcp_probe): conformance checks for an MCP server's handshake and declared capabilities

[The full list is on pub.dev](https://pub.dev/publishers/developeryusuf.com/packages).

#### Writing

[The Biggest MCP Update Ever, Explained With a Restaurant](https://medium.com/@developeryusufihsan/the-biggest-mcp-update-ever-explained-with-a-restaurant-7b1f2bcd7d06).

[Debugging a 45-second deadlock in MCP's Streamable HTTP](https://dev.to/yusufihsangorgel/one-request-two-streams-debugging-a-45-second-deadlock-in-mcps-streamable-http-30o9).

[Portfolio](https://developeryusuf.com) · [Writing](https://yusufihsangorgel.github.io) · [dev.to](https://dev.to/yusufihsangorgel) · [Medium](https://medium.com/@developeryusufihsan) · [LinkedIn](https://www.linkedin.com/in/yusuf-ihsan-g%C3%B6rgel/)
