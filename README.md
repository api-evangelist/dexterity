# Dexterity (dexterity)

Dexterity is a Redwood City, California Physical AI company building a full-stack industrial robotics platform — the Mech roving dual-arm superhumanoid robot driven by the Foresight world model and 68+ skill agents — for warehouse, logistics, and manufacturing operations. Customers include FedEx, UPS, Sagawa Express, Maersk, and VFC, with 100M+ autonomous actions in production and zero safety incidents. Dexterity's commercial offering is enterprise Physical AI deployment with custom pricing, but the company also runs a public research-grade REST API — the Foresight Packing Challenge — that exposes the bin-packing facet of Foresight to .edu researchers competing for a 50,000 USD grand prize.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/dexterity/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

 - Physical AI, Industrial Robotics, Robotics, Warehouse Automation, Logistics, Manufacturing, World Model, Foresight, Mech, Dual-Arm, Truck Loading, Palletizing, Depalletizing, Singulation, Research API, Packing Challenge

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Dexterity Foresight Packing Challenge API

Public REST API exposing the Foresight Packing Challenge as a sequential 3D bin-packing problem. Autonomous agents start a game, place boxes sequentially inside a 2.0m x 2.6m x 2.75m truck, and submit final packing density scores to a public leaderboard. Two modes are supported: dev (unlimited, physics-free testing) and compete (full physics simulation with a 50 games/day per-API-key cap). API keys are issued by reaching at least 50% density in the public Truck Loading Game; full leaderboard participation and the 50,000 USD grand prize are restricted to .edu (or equivalent university) email holders. Interactive Swagger docs live at /challenge/api/docs.

**Human URL:** [https://dexterity.ai/challenge](https://dexterity.ai/challenge)

**Base URL:** `https://dexterity.ai/challenge/api`

#### Tags

 - Physical AI, Foresight, Packing Challenge, REST API, Research API, Bin Packing, Leaderboard

#### Properties

- [Documentation](https://dexterity.ai/challenge)
- [API Reference (Swagger UI)](https://dexterity.ai/challenge/api/docs)
- [Getting Started — Truck Loading Game](https://dexterity.ai/play)
- [OpenAPI](openapi/dexterity-foresight-packing-challenge-openapi.yml)
- [JSON Schema — Game](json-schema/dexterity-foresight-game-schema.json)
- [JSON Schema — Box](json-schema/dexterity-foresight-box-schema.json)
- [JSON Schema — PlacedBox](json-schema/dexterity-foresight-placed-box-schema.json)
- [JSON Schema — TruckConfig](json-schema/dexterity-foresight-truck-config-schema.json)
- [JSON Schema — LeaderboardEntry](json-schema/dexterity-foresight-leaderboard-entry-schema.json)
- [JSON Structure — Game](json-structure/dexterity-foresight-game-structure.json)
- [Example — Start Game](examples/dexterity-foresight-start-game-example.json)
- [Example — Place Box](examples/dexterity-foresight-place-box-example.json)
- [Example — Stop Game](examples/dexterity-foresight-stop-game-example.json)
- [Example — Get Status](examples/dexterity-foresight-get-status-example.json)
- [Example — My Games](examples/dexterity-foresight-my-games-example.json)
- [Example — Display Name](examples/dexterity-foresight-display-name-example.json)
- [Example — Leaderboard](examples/dexterity-foresight-leaderboard-example.json)
- [Example — Health](examples/dexterity-foresight-health-example.json)
- [Naftiko Capability — Packing Game Play](capabilities/packing-game-play.yaml)
- [Naftiko Capability — Leaderboard Tracking](capabilities/leaderboard-tracking.yaml)

## Common Properties

- [Website](https://www.dexterity.ai)
- [Platform](https://www.dexterity.ai/platform)
- [Foresight](https://www.dexterity.ai/blog/foresight)
- [Challenge](https://dexterity.ai/challenge)
- [Truck Loading Game](https://dexterity.ai/play)
- [About](https://www.dexterity.ai/about)
- [Blog](https://www.dexterity.ai/blog)
- [Contact](https://www.dexterity.ai/contact)
- [Terms of Service](https://dexterity.ai/terms-conditions)
- [LinkedIn](https://www.linkedin.com/company/dexterityinc)
- [Spectral Rules](rules/dexterity-rules.yml)
- [Vocabulary](vocabulary/dexterity-vocabulary.yml)
- [JSON-LD Context](json-ld/dexterity-context.jsonld)
- [Plans](plans/dexterity-plans-pricing.yml)
- [Rate Limits](rate-limits/dexterity-rate-limits.yml)
- [FinOps](finops/dexterity-finops.yml)

## Features

- **Foresight World Model** — In-house world model trained on 100M+ autonomous actions for spatial reasoning, prediction, and dual-arm orchestration.
- **68+ Autonomous Skill Agents** — Specialized agents including Packing, Motion, Actualization, Trajectory, and Force-Control coordinated in real time.
- **IRIS Hardware Abstraction Layer** — Unified API enabling deployment of Physical AI across Kawasaki arms, HiWin motion components, and Dexterity-built mobile bases.
- **Mech Dual-Arm Robot** — Roving superhumanoid robot with two arms designed for industrial logistics tasks.
- **Sub-400ms Decision Loop** — End-to-end perception-to-action loop under 400ms in production environments.
- **Zero Safety Incidents** — 100M+ autonomous decisions in production with no reported safety incidents to date.
- **Foresight Packing Challenge API** — Public, research-grade REST API exposing the bin-packing facet of Foresight with a public leaderboard and 50,000 USD prize.

## Use Cases

- Trailer Loading and Unloading
- Palletizing and Depalletizing
- Singulation
- Aircraft Cargo Loading and Unloading
- Bin Packing Research (via the public Foresight Packing Challenge API)

## Integrations and Partners

Kawasaki Heavy Industries, HiWin, NVIDIA, FedEx, Sagawa Express, Sumitomo Corporation, UPS, Maersk, VFC.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
