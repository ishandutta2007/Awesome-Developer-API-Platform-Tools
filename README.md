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

### Sector Overview & Market Dynamics

The global Developer API Platform & API Management market is estimated at **$7.6B to $10.3B** and projected to exceed **$30B+ by 2032–2034**, expanding at a robust CAGR of **16%–22%**. The sector exhibits a **bifurcated market structure**: it is **moderately concentrated at the infrastructure layer**—dominated by cloud hyperscalers (Microsoft, Google Cloud, AWS) that capture high aggregate market share—while remaining **highly fragmented across specialized verticals** (developer tooling, low-code builders, payments, search, and communication APIs) where best-of-breed platforms and emerging open-source contenders challenge incumbent monopolies.

| Product | Company Size (Valuation / Revenue) | Category / Focus | Starting Pricing | Free Tier / Free Trial Limits | Best For / Key Trade-off |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **GitHub** | **~$3.88T Market Cap** (Parent: Microsoft) / **~$2B ARR** | Code Hosting & DevOps | **$4 / user / month** (Team plan) | **Free forever plan**: Unlimited public/private repositories, **2,000 CI/CD Actions minutes/month** (private repos), **500 MB** package storage. | **Best for:** Integrated source control & CI/CD.<br>**Trade-off:** Advanced governance locked behind Enterprise ($21/user/mo). |
| **Firebase** | **~$3.42T Market Cap** (Parent: Alphabet/Google) | Backend-as-a-Service | **Pay-as-you-go** ($0 base fee on Blaze plan; Firestore reads ~$0.03 / 100k) | **Free forever plan (Spark)**: **50,000 document reads/day**, **20,000 document writes/day**, **1 GB** stored data, **50,000 Auth MAUs**, **10 GB hosting storage**, 360 MB hosting transfer/day. | **Best for:** Rapid mobile & web app development.<br>**Trade-off:** NoSQL focus; proprietary API lock-in. |
| **AWS Amplify** | **~$2.60T Market Cap** (Parent: Amazon/AWS) | Full-Stack App Platform | **Pay-as-you-go** ($0.01 / build minute, $0.023 / GB storage, $0.15 / GB data served) | **Free forever plan**: **1,000 build minutes/month**, **5 GB hosting storage/month**, **15 GB data served/month**, 100 GB-hours/month SSR duration. | **Best for:** AWS-centric frontend & backend workflows.<br>**Trade-off:** Steep learning curve when configuring underlying AWS IAM & services. |
| **Stripe** | **$159B Valuation** / **~$6.8B Revenue** | Payment Infrastructure | **2.9% + $0.30** per successful card transaction | **Free forever developer sandbox**: **Free test mode (no time limit)** with full API simulation; live processing has **$0 / month base subscription** (pay only per successful transaction, min $0.50 charge). | **Best for:** Mature, production-grade payment workflows.<br>**Trade-off:** High transaction margins on international & converted currencies. |
| **Twilio** | **~$35B Market Cap** / **~$5.07B Revenue** | Communication APIs | **$0.0083 / SMS message** segment (US) + $1.15/month phone number rental | **30-day Free Trial**: **100 SMS messages**, **100 WhatsApp messages**, **75 voice minutes**, **3,000 SendGrid emails**, and up to 3 trial phone numbers (restricted to verified numbers). | **Best for:** Global multi-channel telecom & messaging.<br>**Trade-off:** Carrier pass-through surcharges and A2P compliance overhead scale costs quickly. |
| **HubSpot Developer Platform** | **~$30B Market Cap** / **~$3.13B Revenue** | CRM & App Marketplace | **$20 / seat / month** (Starter Customer Platform; $15/seat/mo billed annually) | **Free forever developer account**: **Up to 10 developer test accounts** (with 90-day renewable access to Enterprise CRM features, 25 website pages, 100,000 workflow enrollments/day, and 250,000 API requests/day ceiling). | **Best for:** B2B integration builders and SaaS ecosystems.<br>**Trade-off:** Steep tier jumps into Professional & Enterprise pricing. |
| **Supabase** | **$10.5B Valuation** / **~$170M ARR** | Backend-as-a-Service | **$25 / organization / month** (Pro plan base, includes $10 compute credit) | **Free forever plan**: **2 active projects** (pauses after 7 days inactivity), **500 MB database space**, **1 GB file storage**, **50,000 MAUs**, **500,000 edge function invocations**, **2M realtime messages**, 5 GB data egress. | **Best for:** Postgres-native backend with auth & storage.<br>**Trade-off:** Strict database storage ceilings on free tier; compute add-ons require Pro plan. |
| **Postman** | **$5.6B Valuation** / **~$313M ARR** | API Client & Platform | **$19 / user / month** (Team plan billed annually; $14/user/mo Basic) | **Free forever plan**: **1 user** solo workspace, **10,000 Postman API calls/month**, **5 integrations**, unlimited manual collection runs & mock server requests. | **Best for:** Collaborative API design, testing & docs.<br>**Trade-off:** Free plan strictly limits team sharing; requires paid upgrade for multi-seat collaboration. |
| **Retool** | **$3.2B Valuation** / **~$130M ARR** | Internal Tool Builder | **$10 / builder / month** + $5 / internal user / month (Team plan billed annually) | **Free forever plan**: **Up to 5 total users** (builders + internal users), **unlimited apps**, **500 workflow runs/month**, **5 GB Retool Database storage**, 20 hours/month Retool Agents. | **Best for:** Rapid internal dashboards and operational tools.<br>**Trade-off:** Pricing scales per-builder and per-end-user; staging environments locked to paid plans. |
| **Algolia** | **$2.3B Valuation** / **~$100M ARR** | Search & Discovery API | **Pay-as-you-go** ($0 base monthly fee on Grow plan; overages at $0.50 / 1k searches, $0.40 / 1k records) | **Free forever plan (Grow)**: **10,000 search requests/month** and **100,000 records** stored across indices. | **Best for:** Instant typo-tolerant search-as-you-type.<br>**Trade-off:** Costs scale sharply with search query traffic spikes. |

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
