# Dexterity (dexterity)

Dexterity is a Redwood City, California Physical AI company founded in 2017 by Samir Menon and a group of Stanford roboticists. It builds a full-stack industrial robotics platform that combines the Mech — a roving, dual-arm superhumanoid robot — with Foresight, an in-house world model trained on more than 100 million autonomous actions in production. Foresight orchestrates 68+ skill agents (packing, motion, actualization, trajectory, force-control) across the IRIS hardware abstraction layer to drive Kawasaki arms, HiWin motion components, and Dexterity's own mobile bases at sub-400ms decision latency with zero reported safety incidents. Customers include FedEx, UPS, Sagawa Express, Maersk, and VFC, and the company has raised more than 291M USD from Kleiner Perkins, Lightspeed Venture Partners, Obvious Ventures, Sumitomo Corporation, and B37 Ventures. Dexterity's commercial offering is enterprise Physical AI deployment (no self-service developer API), but it does run a public, research-grade REST API — the Foresight Packing Challenge — that exposes the bin-packing facet of Foresight as a programmable sequential placement game, with a 50,000 USD grand prize and participation restricted to .edu email holders.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dexterity/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dexterity/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Physical AI
- Industrial Robotics
- Robotics
- Warehouse Automation
- Logistics
- Manufacturing
- World Model
- Foresight
- Mech
- Dual-Arm
- Truck Loading
- Palletizing
- Depalletizing
- Singulation
- Research API
- Packing Challenge

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Dexterity Foresight Packing Challenge API

Public REST API exposing the Foresight Packing Challenge as a sequential 3D bin-packing problem. Autonomous agents start a game, place boxes sequentially inside a 2.0m x 2.6m x 2.75m truck, and submit final packing density scores to a public leaderboard. Two modes are supported: dev (unlimited, physics-free testing) and compete (full physics simulation with a 50 games/day per-API-key cap). API keys are issued by reaching at least 50% density in the public Truck Loading Game; full leaderboard participation and the 50,000 USD grand prize are restricted to .edu (or equivalent university) email holders. Interactive Swagger docs live at /challenge/api/docs.

- **Human URL:** [https://dexterity.ai/challenge](https://dexterity.ai/challenge)
- **Base URL:** `https://dexterity.ai/challenge/api`

#### Tags

- Physical AI
- Foresight
- Packing Challenge
- REST API
- Research API
- Bin Packing
- Leaderboard

#### Properties

- [Documentation](https://dexterity.ai/challenge)
- [API Reference](https://dexterity.ai/challenge/api/docs)
- [Getting Started](https://dexterity.ai/play)
- [Authentication](https://dexterity.ai/challenge)
- [OpenAPI](openapi/dexterity-foresight-packing-challenge-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dexterity-foresight-packing-challenge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dexterity-foresight-packing-challenge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/dexterity-foresight-game-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dexterity-foresight-box-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dexterity-foresight-placed-box-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dexterity-foresight-truck-config-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/dexterity-foresight-leaderboard-entry-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/dexterity-foresight-game-structure.json)
- [Example](examples/dexterity-foresight-start-game-example.json)
- [Example](examples/dexterity-foresight-place-box-example.json)
- [Example](examples/dexterity-foresight-stop-game-example.json)
- [Example](examples/dexterity-foresight-get-status-example.json)
- [Example](examples/dexterity-foresight-my-games-example.json)
- [Example](examples/dexterity-foresight-display-name-example.json)
- [Example](examples/dexterity-foresight-leaderboard-example.json)
- [Example](examples/dexterity-foresight-health-example.json)

## Common Properties

- [Website](https://www.dexterity.ai)
- [Platform](https://www.dexterity.ai/platform)
- [Foresight](https://www.dexterity.ai/blog/foresight)
- [Mech](https://www.dexterity.ai/platform)
- [Challenge](https://dexterity.ai/challenge)
- [Truck Loading Game](https://dexterity.ai/play)
- [About](https://www.dexterity.ai/about)
- [Blog](https://www.dexterity.ai/blog)
- [Contact](https://www.dexterity.ai/contact)
- [Terms of Service](https://dexterity.ai/terms-conditions)
- [LinkedIn](https://www.linkedin.com/company/dexterityinc)
- [Spectral Rules](rules/dexterity-rules.yml)
- [Vocabulary](vocabulary/dexterity-vocabulary.yml)
- [J S O N- L D](json-ld/dexterity-context.jsonld)
- [Plans](plans/dexterity-plans-pricing.yml)
- [Rate Limits](rate-limits/dexterity-rate-limits.yml)
- [Fin Ops](finops/dexterity-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
