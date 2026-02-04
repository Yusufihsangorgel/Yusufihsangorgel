<div align="center">

# Yusuf İhsan Görgel  
**Mobile Software Engineer** · Flutter · Swift · Kotlin  

I engineer **production-grade mobile apps** with a focus on **architecture**, **performance**, and **reliability**.  
Most of my senior work is **private (NDA)** — I optimize systems, ship releases, and keep apps stable at scale.

<p>
  <a href="mailto:developeryusuf@icloud.com"><img alt="Email" src="https://img.shields.io/badge/Email-developeryusuf@icloud.com-111111?style=flat-square"></a>
  <a href="https://linkedin.com/in/yusuf-ihsan-gorgel"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-yusuf--ihsan--gorgel-111111?style=flat-square"></a>
  <img alt="Location" src="https://img.shields.io/badge/Antalya-T%C3%BCrkiye-111111?style=flat-square">
</p>

<p>
  <img alt="Flutter" src="https://img.shields.io/badge/Flutter-111111?style=flat-square&logo=flutter">
  <img alt="Dart" src="https://img.shields.io/badge/Dart-111111?style=flat-square&logo=dart">
  <img alt="Swift" src="https://img.shields.io/badge/Swift-111111?style=flat-square&logo=swift">
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-111111?style=flat-square&logo=kotlin">
  <img alt="iOS" src="https://img.shields.io/badge/iOS-111111?style=flat-square&logo=apple">
  <img alt="Android" src="https://img.shields.io/badge/Android-111111?style=flat-square&logo=android">
</p>

<p align="center">
  <img src="https://img.shields.io/github/followers/Yusufihsangorgel?style=flat-square&label=Followers" />
  <img src="https://img.shields.io/github/stars/Yusufihsangorgel?style=flat-square&label=Stars" />
  <img src="https://img.shields.io/github/commit-activity/y/Yusufihsangorgel/Yusufihsangorgel?style=flat-square&label=Commits%20this%20year" />
</p>


</div>

---

## What I focus on

**Architecture**
- Feature-first modularization (clear boundaries: UI ↔ domain ↔ data)
- Dependency inversion, testable business logic, replaceable infrastructure
- Predictable state modeling (tradeoff-driven, not framework-driven)

**Performance**
- Frame budget mindset (60/120fps), DevTools profiling, render discipline
- Jank avoidance: rebuild minimization, list perf, async scheduling, caching

**Native (iOS/Android)**
- Flutter ↔ native boundaries (platform channels / plugin-style isolation)
- Swift/Kotlin for device capabilities, performance-critical edges, and stability

**Reliability & delivery**
- Offline-first (caching + sync), resilient networking, retries/backoff
- CI, testing, versioning, reproducible builds, release discipline

---

## How I structure real apps (feature-first + product core)

This is the structure I use when I want **scale + clarity** without over-complicating things:

- `feature/<name>/` → screen/flow-specific code  
  - `view/` → **UI only** (no service calls inside widgets)  
  - `view/mixin/` → lifecycle / page ops (initial fetch, listeners, navigation glue)  
  - `view_model/` → state + orchestration  
- `product/` → shared building blocks used across features  
  - `init/` → bootstrap, DI, env, app-wide setup  
  - `service/` → networking + cache clients  
  - `model/` → shared DTOs / app models  
  - `utility/` → widgets, constants, extensions, helpers  

```mermaid
flowchart TB
  APPROOT["main.dart<br/>AppRoot"] --> INIT

  subgraph FEATURE["feature/<feature_name>"]
    direction TB
    subgraph VIEW["view"]
      UI["home_view.dart<br/>UI only"]
      MIXIN["home_view_mixin.dart<br/>page lifecycle ops"]
    end
    VM["home_view_model.dart<br/>state + orchestration"]
    UI -->|binds| VM
    MIXIN -->|triggers| VM
  end

  subgraph PRODUCT["product (shared)"]
    direction TB
    INIT["init<br/>bootstrap + DI"]
    SVC["service<br/>network + cache clients"]
    MODEL["model<br/>DTOs / shared models"]
    UTIL["utility<br/>widgets / constants / extensions"]
  end

  INIT -->|provides| VM
  VM -->|uses| SVC
  VM -->|uses| MODEL
  VM -->|uses| UTIL

  subgraph INFRA["infrastructure"]
    direction TB
    API["remote<br/>REST / WebSocket"]
    LOCAL["local<br/>SQLite / secure storage"]
    NATIVE["native<br/>Swift / Kotlin modules"]
  end

  SVC --> API
  SVC --> LOCAL
  SVC --> NATIVE
```


---

## Private work (NDA) — what I can say publicly

- Shipping and maintaining **multi-module mobile apps**
- Building **stable release pipelines** and reducing regression risk
- Performance work: **profiling**, **memory/CPU hotspots**, smooth UI
- Integrations: **auth / realtime / offline sync / payments** (context-dependent)

> If needed, I can publish anonymized “case-study” style writeups (no IP, no client data) as Markdown articles in this repo.

---

## Engineering proof (process > hype)

- **Code review discipline:** small PRs, clear diffs, rollback-friendly changes
- **Testing strategy:** unit-first for domain, targeted widget/integration tests
- **Observability mindset:** logs, crash signals, performance baselines
- **Documentation:** decisions recorded (ADR-style), onboarding-friendly structure

---

## Tech stack

**Mobile**
- Flutter (Dart), Swift (SwiftUI), Kotlin (Android)

**Backend (when needed)**
- Java (Spring Boot), Node.js (TypeScript), Go

**Data**
- SQLite / local persistence, PostgreSQL, MongoDB

**Engineering**
- REST, WebSocket, testing, CI/CD

---

## Contact

- Email: **developeryusuf@icloud.com**
- LinkedIn: https://linkedin.com/in/yusuf-ihsan-gorgel

---

> If it ships reliably, it’s engineered.
