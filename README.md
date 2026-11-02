# Awesome-Developer-API-Platform-Tools

# Awesome-Developer-API-Platform-Tools
**Top Developer API Platform Tools (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on API Clients, Backend-as-a-Service, Search Infrastructure, Low-Code Platforms & API Gateways*
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Developer API & Platform Tools**. These tools enable developers to build, test, and deploy applications faster—from API clients and backend services to search engines and internal tool builders—with a strong emphasis on open-source alternatives that give teams data sovereignty and cost control.

**Examples** include Postman, Supabase, Firebase, Algolia, Retool, AWS Amplify, GitHub, Stripe, Twilio, and HubSpot (the category leaders in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosted API tooling, backend platforms, and open infrastructure. **Critical note**: The open-source landscape is exceptionally strong in every category—**Bruno** and **Hoppscotch** rival Postman, **Supabase** and **Appwrite** challenge Firebase, **Typesense** and **Meilisearch** undercut Algolia, and **Appsmith** and **ToolJet** replace Retool. No single open-source project matches every SaaS feature, but for each category, production-proven alternatives exist.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Postman**
  **API development and testing platform** with collections, environments, and mock servers. **Pricing**: Free tier available; paid plans per user. **Free tier**: Yes, limited collection runs and mock calls. **Best for**: teams wanting a polished, collaborative API client with cloud sync—**trade-off**: data stored in vendor cloud; pricing scales with users.

- **Supabase**
  **Open-source Firebase alternative** (hosted). **Pricing**: Free tier; Pro from $25/month. **Free tier**: Yes, generous. **Best for**: developers wanting Postgres-based backend with auth, storage, and realtime—**trade-off**: hosted version has usage limits; self-hosted is available for free.

- **Firebase**
  **Google's backend-as-a-service** with Firestore, Auth, and Hosting. **Pricing**: Spark (free) and Blaze (pay-as-you-go). **Free tier**: Yes, limited reads/writes. **Best for**: mobile and web apps wanting Google ecosystem integration—**trade-off**: NoSQL-only; vendor lock-in concerns.

- **Algolia**
  **Hosted search API** with instant search and typo tolerance. **Pricing**: Build (free) and Grow plans; usage-based pricing. **Free tier**: Yes, limited records and searches. **Best for**: teams wanting turnkey search without infrastructure—**trade-off**: costs scale sharply with search volume .

- **Retool**
  **Low-code internal tool builder** with AI credits. **Pricing**: Free up to 5 users; paid from $10/builder/month. **Free tier**: Yes, 5 users. **Best for**: teams building admin panels and dashboards—**trade-off**: per-builder and per-user pricing stacks .

- **AWS Amplify**
  **Full-stack development platform** for AWS. **Pricing**: Pay-as-you-go. **Free tier**: Limited. **Best for**: AWS-centric teams wanting integrated frontend and backend.

- **GitHub**
  **Code hosting and DevOps platform** with Actions, Packages, and Projects. **Pricing**: Free for public repos; paid per user. **Free tier**: Yes, generous. **Best for**: teams wanting integrated source control and CI/CD.

- **Stripe**
  **Payment infrastructure API** with billing and subscriptions. **Pricing**: Per-transaction fees. **Free tier**: None for payments. **Best for**: developers wanting the most mature payment APIs.

- **Twilio**
  **Communication APIs** for SMS, voice, and WhatsApp. **Pricing**: Usage-based. **Free tier**: Trial credits. **Best for**: teams adding messaging and voice to applications.

- **HubSpot Developer Platform**
  **CRM development platform** with APIs and app marketplace. **Pricing**: Free developer tier; paid for production apps. **Free tier**: Yes, sandbox. **Best for**: developers building on HubSpot CRM.

## Open-Source GitHub Projects

### API Clients

- **Bruno**
  **Offline-first API client with Git-native collections** (MIT) — **the most popular open-source Postman alternative** with **47.2k GitHub stars** . **Features**: Stores every request as a plain-text `.bru` file in a folder—**collections live in your repository and change through pull requests**; offline-only with "no plans to add cloud-sync to Bruno, ever" per the repository; **REST, GraphQL, SOAP, gRPC, and WebSocket** support; **CLI** for running collections in CI . **Tech stack**: Electron, JavaScript. **Deploy**: Desktop app. **Trade-off**: `.bru` is Bruno's own format—portable as text but not as OpenAPI. Some Git workflow features sit in paid tiers (Pro $6/user/month) . **Best for**: teams wanting Git as the collaboration layer and no request data in a vendor cloud.

- **Hoppscotch**
  **Open-source API development ecosystem** (MIT) — **the most starred open-source API client** with **80.5k GitHub stars** . **Features**: Browser-based (PWA), desktop, CLI, and self-hosted; **REST, GraphQL, WebSocket, SSE, Socket.IO, and MQTT** support—broadest protocol coverage among open-source clients; local or cloud workspaces; lightweight and fast . **Tech stack**: Vue.js, TypeScript. **Deploy**: Self-hosted (Docker) or Hoppscotch Cloud. **Trade-off**: Paid tier from $6/user/month for advanced collaboration features . **Best for**: teams wanting a lightweight, multi-protocol API client that can be self-hosted for the whole team.

### Backend-as-a-Service

- **Supabase**
  **Open-source Firebase alternative** (Apache-2.0 for core) — **the most mature open-source BaaS**, built on **PostgreSQL** . **Features**: Postgres database with **Row Level Security**; authentication; file storage; realtime subscriptions; edge functions; generous free cloud tier; self-hostable via Docker . **Tech stack**: PostgreSQL, Go, TypeScript. **Deploy**: Self-hosted (Docker) or Supabase Cloud. **Trade-off**: Self-hosting requires more DevOps effort than Firebase; real-time less mature than Firebase . **Best for**: developers wanting a Postgres-native backend with Firebase-like features and no vendor lock-in.

- **Appwrite**
  **Self-hostable BaaS with simple Docker setup** (MIT) — **the easiest open-source BaaS to deploy** . **Features**: Authentication, databases, storage, functions, and messaging; **single Docker Compose command** gets you a full backend; multi-platform SDKs (Web, Flutter, iOS, Android); affordable cloud tier from $15/mo . **Tech stack**: MariaDB, PHP, TypeScript. **Deploy**: Self-hosted (Docker) or Appwrite Cloud. **Trade-off**: **MariaDB-based, not Postgres**—loses Postgres-specific features like RLS and advanced JSON operations . **Best for**: teams needing easy self-hosting without deep DevOps work.

- **PocketBase**
  **Single-binary backend in Go** (MIT) — **the simplest possible backend** . **Features**: One file—run it and get REST API, real-time subscriptions, auth, file storage, and admin dashboard; **SQLite-based**—runs on minimal hardware ($5 VPS handles surprising traffic); no Docker, no dependencies . **Tech stack**: Go, SQLite. **Deploy**: Single binary. **Trade-off**: **SQLite limits write concurrency** at scale; no managed cloud option; smaller ecosystem . **Best for**: side projects, prototypes, small internal tools, and developers wanting zero infrastructure overhead.

### Search Infrastructure

- **Typesense**
  **Open-source search engine with typo tolerance** (GPL-3.0) — **the most cost-effective Algolia alternative** . **Features**: Instant search-as-you-type; typo tolerance; **self-hosted or Typesense Cloud**; **50–98.5% cheaper than Algolia** depending on search volume ; **no per-search or per-record charges** on self-hosted . **Tech stack**: C++. **Deploy**: Self-hosted or Typesense Cloud. **Trade-off**: Requires running infrastructure; less analytics depth than Algolia . **Best for**: teams wanting Algolia-quality search without the bill—especially at high search volumes.

- **Meilisearch**
  **Lightweight search engine** (MIT for Community) — **the easiest self-hosted search** . **Features**: Fast, typo-tolerant search; simple setup; good relevance out of the box. **Tech stack**: Rust. **Deploy**: Self-hosted or Meilisearch Cloud. **Trade-off**: **Single-node only in Community Edition**—HA and sharding require Enterprise (BUSL) or Cloud . **Best for**: small to mid-size catalogs wanting simple, fast search.

- **PragmaSearch**
  **Local-first semantic search** (open source) — **the most innovative search alternative for small catalogs** . **Features**: **Hybrid search** (vector + BM25 with RRF fusion) with typo tolerance and faceting; **runs entirely locally**—no cloud, no API keys, $0 per search; **one local index file**, no database; benchmarked at **0.941 nDCG@10** on sample catalog . **Tech stack**: JavaScript (Transformers.js). **Deploy**: Self-hosted (npm). **Trade-off**: **Built for small-to-mid catalogs (≤ ~50k items)**—not for million-SKU real-time catalogs . **Best for**: shops with modest catalogs wanting semantic search without Algolia's bill.

### Low-Code Internal Tools

- **Appsmith**
  **Low-code platform for internal tools** (Apache-2.0) — **the most mature open-source Retool alternative** with **41k GitHub stars** . **Features**: Drag-and-drop UI builder; 25+ database integrations; JavaScript for custom logic; self-hosted with Docker; SSO and app embedding on free plan . **Tech stack**: Java, React. **Deploy**: Self-hosted or Appsmith Cloud. **Trade-off**: UI can feel complex for simple apps; enterprise features gated . **Best for**: teams wanting a full-featured, self-hosted Retool alternative.

- **ToolJet**
  **Open-source low-code platform** (AGPL-3.0) — **a strong Appsmith/Retool alternative** with **41.1k GitHub stars** . **Features**: Drag-and-drop builder; 50+ widgets; AI-powered app generation; multi-player editing; self-hosted . **Tech stack**: Node.js, React. **Deploy**: Self-hosted or ToolJet Cloud. **Trade-off**: Smaller community than Appsmith . **Best for**: teams wanting AI-assisted internal tool building.

- **Budibase**
  **Open-source low-code with generous free self-hosting** (GPL-3.0 for core) — **the best Retool alternative for small teams** . **Features**: **Free for up to 20 users self-hosted** (more than Retool's 5); single Docker container setup; auto-generated CRUD screens from databases; built-in database; SSO and embedding on free plan . **Tech stack**: Node.js, Svelte. **Deploy**: Self-hosted (Docker) or Budibase Cloud. **Trade-off**: Less flexible than Appsmith for highly custom UIs; smaller widget library . **Best for**: small teams wanting to build internal tools quickly on a budget.

### API Gateways

- **Apache APISIX**
  **Apache-governed API gateway** (Apache 2.0) — **the vendor-neutral open-source gateway** . **Features**: Built on NGINX + LuaJIT; etcd-backed dynamic configuration or standalone file mode; plugin ecosystem spanning auth, rate limiting, observability, and transformation; multi-language plugins (Lua, Java, Go, Python, Wasm); Kubernetes ingress controller . **Tech stack**: Lua, NGINX. **Deploy**: Self-hosted. **Trade-off**: Requires etcd for dynamic mode; steeper learning curve than single-binary gateways . **Best for**: teams wanting a community-governed, feature-rich gateway with broad plugin support.

- **Kong Gateway OSS**
  **The most widely deployed open-source API gateway** (Apache 2.0) — **the industry standard** . **Features**: NGINX + LuaJIT; PostgreSQL-backed, DB-less, or hybrid modes; **decK CLI** for declarative configuration (dump, edit YAML, sync with diff preview)—**infrastructure-as-code for gateways** ; large Plugin Hub with open-source and commercial plugins . **Tech stack**: Lua, NGINX. **Deploy**: Self-hosted. **Trade-off**: Enterprise features gated; heavier than single-binary alternatives . **Best for**: teams wanting the most mature gateway with strong IaC tooling (decK).

### Additional Strong Open-Source Options

- **Scalar** — OpenAPI-based API client and reference (MIT). 15.7k stars; REST-focused; native OpenAPI support . **Note**: Client is free; hosted platform for docs/SDKs is paid. **Best for**: teams whose API already has an OpenAPI document.
- **Hurl** — Command-line HTTP testing tool (Apache 2.0). Plain-text test files; assertions inline; CI-friendly . **Best for**: teams wanting API tests as code in CI.
- **HTTPie** — Human-friendly HTTP client (BSD-3). 38.6k stars; intuitive syntax; colored output . **Best for**: developers wanting a better curl for scripting and smoke tests.
- **KrakenD** — Stateless high-performance gateway (Apache 2.0). No database; config-file driven; single Go binary . **Best for**: teams wanting a lightweight, Git-friendly gateway without state.

**Frameworks for building custom systems**: Combine **Bruno** for Git-native API testing with **Supabase** for backend, **Typesense** for search, **Appsmith** for internal tools, and **Kong** for gateway—creating a complete open-source developer platform stack. **None of these match every SaaS feature**, but for each category, the open-source alternatives are production-proven.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Developer platforms handling application data and credentials must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls.
- **The "API client" vs. "BaaS" vs. "search" vs. "low-code" vs. "gateway" distinction is critical.** **Postman, Bruno, and Hoppscotch** are **API clients**—they send and test requests. **Supabase, Firebase, Appwrite, and PocketBase** are **backend-as-a-service**—they provide database, auth, and storage. **Algolia, Typesense, and Meilisearch** are **search engines**—they index and query documents. **Retool, Appsmith, ToolJet, and Budibase** are **low-code builders**—they create internal tools. **Kong and APISIX** are **API gateways**—they route and manage traffic. **Choose based on what layer of the stack you need.**
- **Bruno's Git-native approach is genuinely different from Postman.** Collections are files in your repo—not a cloud database—so collaboration happens through pull requests, and data sovereignty is automatic . **The trade-off**: `.bru` format is not OpenAPI-portable.
- **Hoppscotch has the broadest protocol coverage** among open-source API clients—REST, GraphQL, WebSocket, SSE, Socket.IO, and MQTT . **For teams working with non-REST protocols, it is the strongest choice.**
- **Supabase is the most mature open-source Firebase alternative** with Postgres RLS and a generous free tier . **Appwrite is easier to self-host** (single Docker Compose) but uses MariaDB . **PocketBase is the simplest** (single binary, SQLite) but limits write concurrency .
- **Typesense's cost advantage vs. Algolia is dramatic at scale**—**97.5% savings at 4.1M searches/month**, **98.5% at 141.7M** . **For search-heavy applications, self-hosting Typesense or Meilisearch is the pragmatic financial choice.**
- **PragmaSearch is for small catalogs**—it explicitly targets **≤ ~50k items** and is not for million-SKU real-time catalogs . **For semantic search on a budget, it is a compelling option.**
- **Budibase's free self-hosting for 20 users** is more generous than Retool's 5 . **For small teams wanting to start free, it is the best entry point.**
- **Kong's decK CLI is the strongest IaC tooling** for gateways—dump, edit YAML, sync with diff preview . **For teams practicing GitOps with gateways, it is the standard.**
- Self-hosted open-source solutions require proper infrastructure (PostgreSQL for Supabase, Docker for Appsmith/Budibase, etcd for APISIX), security hardening, and ongoing maintenance. **Developer platforms handle credentials and application data**—ensure your deployment meets your organization's security standards before connecting production systems.

---

**Made for developers, platform teams, and organizations building transparent developer tooling solutions.**
Let's make Developer API & Platform Tools more open, data-driven, and developer-friendly.
