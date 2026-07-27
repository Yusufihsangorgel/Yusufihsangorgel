Software engineer working across Flutter, Dart, and Go, where client apps, native code, and infrastructure have to stay correct under load.

#### Upstream

Reworking `package:dart_mcp`'s transport for the 2026 MCP specification: the [lifecycle split](https://github.com/dart-lang/ai/pull/524), [request-scoped dispatch](https://github.com/dart-lang/ai/pull/528), and [decoded-message channels](https://github.com/dart-lang/ai/pull/531) are merged. Two changes landed in the Dart SDK analyzer: it now [rejects Struct-constrained mixin applications](https://github.com/dart-lang/sdk/commit/94c4d27546cc90b81312735055b0fc45b3fcefca) and [handles `NativeCallable` arguments independently of source order](https://github.com/dart-lang/sdk/commit/ab364ca4aa5a9cef2bfb411c5508924606506e3d). In `package:code_assets`, a [validator now reads a dynamic library's architecture from its file headers](https://github.com/dart-lang/native/pull/3484). Also merged fixes into [shelf](https://github.com/dart-lang/shelf/pull/536), [Drift](https://github.com/simolus3/drift/pull/3835), [FlutterFire](https://github.com/firebase/flutterfire/pull/18443), [Retrofit](https://github.com/trevorwang/retrofit.dart/pull/921), and [Bun](https://github.com/uptrace/bun/pull/1390); more across dart-lang, flutter, and grpc-go on my profile.

#### Packages

20+ on pub.dev. Several bind native C and C++ libraries through Dart's build hooks, so there is nothing to install:

- [re2](https://pub.dev/packages/re2): linear-time regex, immune to catastrophic backtracking
- [simdjson_dart](https://pub.dev/packages/simdjson_dart): SIMD JSON parsing over simdjson
- [blake3_ffi](https://pub.dev/packages/blake3_ffi): BLAKE3 hashing at native throughput

Others are pure Dart:

- [resilience](https://pub.dev/packages/resilience): retries, circuit breaker, rate limiter, bulkhead
- [redis_task_queue](https://pub.dev/packages/redis_task_queue): a server-side queue with retries and dead letters
- [mcp_probe](https://pub.dev/packages/mcp_probe): a conformance harness for MCP servers

[The full list is on pub.dev](https://pub.dev/publishers/developeryusuf.com/packages).

#### Writing

[Debugging a 45-second deadlock in MCP's Streamable HTTP](https://dev.to/yusufihsangorgel/one-request-two-streams-debugging-a-45-second-deadlock-in-mcps-streamable-http-30o9).

[Portfolio](https://developeryusuf.com) · [Writing](https://yusufihsangorgel.github.io) · [dev.to](https://dev.to/yusufihsangorgel) · [Medium](https://medium.com/@developeryusufihsan) · [LinkedIn](https://www.linkedin.com/in/yusuf-ihsan-g%C3%B6rgel/)
