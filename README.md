# Nakama (nakama)

Nakama by Heroic Labs is an open-source (Apache-2.0) game and app backend server providing user accounts and authentication, social features (friends, groups, chat), collaborative storage, realtime multiplayer and authoritative matches, matchmaking, leaderboards and tournaments, notifications, and a server runtime with custom RPCs in Go, TypeScript/JavaScript, and Lua. Nakama exposes a gRPC-gateway-generated REST API plus a realtime WebSocket socket API, and is available self-hosted or as the managed Heroic Cloud.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nakama/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nakama/refs/heads/main/apis.yml)

## Tags

- Gaming
- Game Backend
- Backend
- Realtime
- Multiplayer
- Matchmaking
- Leaderboards
- Social
- Open Source

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Nakama Authentication API

Authenticates players and issues session tokens. Supports device ID, email/password, username, custom ID, Apple, Google, Facebook, Facebook Instant Games, Game Center, Steam, and refresh-token flows. Server key HTTP Basic auth guards authentication endpoints; a JWT session token authorizes all other calls.

- **Human URL:** [https://heroiclabs.com/docs/nakama/concepts/authentication/](https://heroiclabs.com/docs/nakama/concepts/authentication/)
- **Base URL:** `http://127.0.0.1:7350/v2`

#### Tags

- Authentication
- Accounts
- Sessions
- OAuth

#### Properties

- [Documentation](https://heroiclabs.com/docs/nakama/concepts/authentication/)
- [API Reference](https://heroiclabs.com/docs/nakama/api/)
- [OpenAPI](openapi/nakama-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nakama.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nakama.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nakama Account API

Reads and updates the authenticated user's account, fetches other user profiles, deletes the account, and links or unlinks external identity providers (device, email, Apple, Google, Facebook, Game Center, Steam, custom) to a single account.

- **Human URL:** [https://heroiclabs.com/docs/nakama/concepts/user-accounts/](https://heroiclabs.com/docs/nakama/concepts/user-accounts/)
- **Base URL:** `http://127.0.0.1:7350/v2`

#### Tags

- Accounts
- Users
- Profile
- Linking

#### Properties

- [Documentation](https://heroiclabs.com/docs/nakama/concepts/user-accounts/)
- [OpenAPI](openapi/nakama-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nakama.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nakama.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nakama Friends and Groups API

Manages the social graph - add, list, delete, and block friends; import friends from Facebook and Steam; create, update, list, join, and leave groups (clans); manage group membership, promotions, demotions, and bans.

- **Human URL:** [https://heroiclabs.com/docs/nakama/concepts/friends/](https://heroiclabs.com/docs/nakama/concepts/friends/)
- **Base URL:** `http://127.0.0.1:7350/v2`

#### Tags

- Social
- Friends
- Groups
- Clans

#### Properties

- [Documentation](https://heroiclabs.com/docs/nakama/concepts/friends/)
- [Documentation](https://heroiclabs.com/docs/nakama/concepts/groups-clans/)
- [OpenAPI](openapi/nakama-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nakama.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nakama.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nakama Storage API

Reads, writes, lists, and deletes JSON storage objects organized into collections and keyed per user, with per-object owner and public read/write permissions and optimistic-concurrency version checks. Backs save games, inventories, and shared app state.

- **Human URL:** [https://heroiclabs.com/docs/nakama/concepts/collections/](https://heroiclabs.com/docs/nakama/concepts/collections/)
- **Base URL:** `http://127.0.0.1:7350/v2`

#### Tags

- Storage
- Objects
- Save Games
- Persistence

#### Properties

- [Documentation](https://heroiclabs.com/docs/nakama/concepts/collections/)
- [OpenAPI](openapi/nakama-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nakama.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nakama.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nakama Leaderboards and Tournaments API

Writes and lists leaderboard records (including records around an owner or filtered to friends), and lists, joins, and submits scores to recurring or one-off tournaments with configurable reset schedules, categories, and reward handling.

- **Human URL:** [https://heroiclabs.com/docs/nakama/concepts/leaderboards/](https://heroiclabs.com/docs/nakama/concepts/leaderboards/)
- **Base URL:** `http://127.0.0.1:7350/v2`

#### Tags

- Leaderboards
- Tournaments
- Scores
- Ranking

#### Properties

- [Documentation](https://heroiclabs.com/docs/nakama/concepts/leaderboards/)
- [Documentation](https://heroiclabs.com/docs/nakama/concepts/tournaments/)
- [OpenAPI](openapi/nakama-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nakama.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nakama.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nakama Notifications API

Lists and deletes a user's in-app notifications with cursor-based pagination. Notifications are delivered in realtime over the socket when the user is connected, and persisted for retrieval when they reconnect.

- **Human URL:** [https://heroiclabs.com/docs/nakama/concepts/in-app-notifications/](https://heroiclabs.com/docs/nakama/concepts/in-app-notifications/)
- **Base URL:** `http://127.0.0.1:7350/v2`

#### Tags

- Notifications
- Messaging
- Push

#### Properties

- [Documentation](https://heroiclabs.com/docs/nakama/concepts/in-app-notifications/)
- [OpenAPI](openapi/nakama-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nakama.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nakama.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nakama RPC and Runtime API

Invokes custom server-side functions (RPCs) registered in the Nakama runtime over HTTP GET or POST, callable with a session token or, for server-to-server calls, an HTTP key query parameter. Runtime functions are authored in Go, TypeScript/JavaScript, or Lua.

- **Human URL:** [https://heroiclabs.com/docs/nakama/server-framework/basics/](https://heroiclabs.com/docs/nakama/server-framework/basics/)
- **Base URL:** `http://127.0.0.1:7350/v2`

#### Tags

- RPC
- Runtime
- Custom Logic
- Serverless

#### Properties

- [Documentation](https://heroiclabs.com/docs/nakama/server-framework/basics/)
- [Documentation](https://heroiclabs.com/docs/nakama/server-framework/introduction/)
- [OpenAPI](openapi/nakama-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nakama.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nakama.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Nakama Realtime Socket API

Persistent WebSocket connection carrying realtime features - status presence, realtime chat channels, relayed and authoritative multiplayer matches, matchmaking, parties, and realtime notification delivery - as envelope messages authenticated with a session token supplied as a query parameter on connect.

- **Human URL:** [https://heroiclabs.com/docs/nakama/concepts/client-relayed-multiplayer/](https://heroiclabs.com/docs/nakama/concepts/client-relayed-multiplayer/)
- **Base URL:** `ws://127.0.0.1:7350/ws`

#### Tags

- Realtime
- WebSocket
- Multiplayer
- Matchmaking
- Chat

#### Properties

- [Documentation](https://heroiclabs.com/docs/nakama/concepts/client-relayed-multiplayer/)
- [Documentation](https://heroiclabs.com/docs/nakama/concepts/matches/)
- [AsyncAPI](asyncapi/nakama-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Nakama Console API

Administrative API behind the Nakama Developer Console for managing users, storage, leaderboards, matches, runtime configuration, and server status. It is an internal operations surface (not published as a stable public client contract) authenticated with console credentials, and is documented here for completeness rather than for third-party client integration.

- **Human URL:** [https://heroiclabs.com/docs/nakama/getting-started/console-overview/](https://heroiclabs.com/docs/nakama/getting-started/console-overview/)
- **Base URL:** `http://127.0.0.1:7350/v2/console`

#### Tags

- Console
- Administration
- Operations

#### Properties

- [Documentation](https://heroiclabs.com/docs/nakama/getting-started/console-overview/)

## Common Properties

- [GitHub Organization](https://github.com/heroiclabs)
- [LinkedIn](https://www.linkedin.com/company/heroic-labs)
- [Website](https://heroiclabs.com/)
- [Documentation](https://heroiclabs.com/docs/)
- [Plans](plans/nakama-plans-pricing.yml)
- [Rate Limits](rate-limits/nakama-rate-limits.yml)
- [Fin Ops](finops/nakama-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
