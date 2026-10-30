# Nakama

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Nakama by Heroic Labs is an open-source (Apache-2.0) game and app backend server providing user accounts and authentication, social features (friends, groups, chat), collaborative storage, realtime multiplayer and authoritative matches, matchmaking, leaderboards and tournaments, notifications, and a server runtime with custom RPCs in Go, TypeScript/JavaScript, and Lua. Nakama exposes a gRPC-gateway-generated REST API plus a realtime WebSocket socket API, and is available self-hosted or as the managed Heroic Cloud.

**Areas:** Gaming · Game Backend · Backend · Real-Time · Multiplayer · Matchmaking · Leaderboards · Social · Open Source

## Nakama on APIs.io

Everything profiled for Nakama is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nakama/](https://apis.io/providers/nakama/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Nakama Realtime Socket API](https://apis.io/apis/nakama/nakama-realtime-api/) — Persistent WebSocket connection carrying realtime features - status presence, realtime chat channels, relayed and authoritative multiplayer matches,…
- [Nakama Console API](https://apis.io/apis/nakama/nakama-console-api/) — Administrative API behind the Nakama Developer Console for managing users, storage, leaderboards, matches, runtime configuration, and server status. It is…
- [Nakama Account API](https://apis.io/apis/nakama/nakama-account-api/) — Read, update, and delete the current account and link identities.
- [Nakama Authentication API](https://apis.io/apis/nakama/nakama-authentication-api/) — Authenticate users and issue or refresh session tokens.
- [Nakama Friends API](https://apis.io/apis/nakama/nakama-friends-api/) — Manage the friend graph.
- [Nakama Groups API](https://apis.io/apis/nakama/nakama-groups-api/) — Create and manage groups (clans) and their members.
- [Nakama Leaderboards API](https://apis.io/apis/nakama/nakama-leaderboards-api/) — Write and list leaderboard records.
- [Nakama Notifications API](https://apis.io/apis/nakama/nakama-notifications-api/) — List and delete in-app notifications.
- [Nakama RPC API](https://apis.io/apis/nakama/nakama-rpc-api/) — Call custom runtime functions.
- [Nakama Storage API](https://apis.io/apis/nakama/nakama-storage-api/) — Read, write, list, and delete storage objects.
- [Nakama Tournaments API](https://apis.io/apis/nakama/nakama-tournaments-api/) — List, join, and submit to tournaments.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Nakama Realtime Socket API (WebSocket)](https://apis.io/asyncapis/nakama/nakama-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/ws](https://apis.io/channels/nakama/ws/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Nakama Agentic Access](https://apis.io/agentic-access/nakama/nakama-agentic-access/)

#### Collections (10)

Postman and Open Collection request collections.

- [Nakama API](https://apis.io/collections/nakama/open-nakama/)
- [Nakama Account API](https://apis.io/collections/nakama/open-nakama-account-api/)
- [Nakama Account Authentication API](https://apis.io/collections/nakama/open-nakama-authentication-api/)
- [Nakama Account Friends API](https://apis.io/collections/nakama/open-nakama-friends-api/)
- [Nakama Account Groups API](https://apis.io/collections/nakama/open-nakama-groups-api/)
- [Nakama Account Leaderboards API](https://apis.io/collections/nakama/open-nakama-leaderboards-api/)
- [Nakama Account Notifications API](https://apis.io/collections/nakama/open-nakama-notifications-api/)
- [Nakama Account RPC API](https://apis.io/collections/nakama/open-nakama-rpc-api/)
- [Nakama Account Storage API](https://apis.io/collections/nakama/open-nakama-storage-api/)
- [Nakama Account Tournaments API](https://apis.io/collections/nakama/open-nakama-tournaments-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Nakama — asyncapi rules](https://apis.io/rules/nakama/nakama-asyncapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Nakama Authentication](https://apis.io/security/nakama/nakama-authentication/)
- [Nakama Domain Security](https://apis.io/security/nakama/nakama-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Nakama Plans Pricing](https://apis.io/plans/nakama/nakama-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Nakama Rate Limits](https://apis.io/rate-limits/nakama/nakama-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Nakama Finops](https://apis.io/finops/nakama/nakama-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://heroiclabs.com/)
- [Documentation](https://heroiclabs.com/docs/)
- [Blog](https://heroiclabs.com/blog/)
- [GitHub](https://github.com/heroiclabs)

## API Evangelist rating

**Kin Score 32.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 52.5 |
| Contract governance | 11.4 |
| Operational transparency | 10.5 |
| Developer ergonomics | 31.0 |
| Access clarity | 7.9 |

**Agent readiness 19.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nakama/](https://apis.io/providers/nakama/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Nakama: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nakama/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
