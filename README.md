# Community Studio

Forums, groups, badges and moderation

Build forums, groups, and member directories with badges and reputation. Manage moderation queues, guidelines, and leaderboards, run ambassador programs and event feeds, send activity digests, and track community growth analytics.

## Microservices Used

**Platform baseline** (common to every app & studio): `gateway-service`, `authentication-service`, `identity-service`, `access-service`, `security-service`, `audit-service`, `observability-service`, `control-service`, `deployment-service`, `integration-service`, `storage-service`, `reporting-service`, `analytics-service`, `notification-service`

**Functional services (7):**

| Service | Status |
|---|---|
| `publishing-service` | Core |
| `customer-service` | Core |
| `review-service` | New (Tier-1) |
| `search-service` | Core |
| `media-service` | New (Tier-1) |
| `moderation-service` | Suggested — not yet built |
| `realtime-service` | Suggested — not yet built |
