# Public implementation repositories

Workers will record created `<company-slug>-public` repositories here.

## Implementation-Ready Queue

Queue artifact: [`implementation-ready.json`](implementation-ready.json).

This queue lists copyable companies ready for meta fan-out. This discovery worker must not create implementation repos unless explicitly instructed; meta creates/registers repos and launches workers to avoid duplicates.

Confirmed ready first:
- `napkin-math` -> `napkin-math-public`
- `inth` -> `inth-public`

Current queue counts:
- Confirmed ready: 2
- Additional ready: 277
- Total ready: 279

Next unambiguous copyable entries:
| Slug | Name | Issue | Proposed Repo | Source |
| --- | --- | --- | --- | --- |
| `agentphone` | AgentPhone | [#8](https://github.com/PalmerMichaels/yc-2026-public-master/issues/8) | `agentphone-public` | [YC](https://www.ycombinator.com/companies/agentphone) |
| `akkari` | Akkari | [#10](https://github.com/PalmerMichaels/yc-2026-public-master/issues/10) | `akkari-public` | [YC](https://www.ycombinator.com/companies/akkari) |
| `amboras` | Amboras | [#13](https://github.com/PalmerMichaels/yc-2026-public-master/issues/13) | `amboras-public` | [YC](https://www.ycombinator.com/companies/amboras) |
| `andco` | Andco | [#14](https://github.com/PalmerMichaels/yc-2026-public-master/issues/14) | `andco-public` | [YC](https://www.ycombinator.com/companies/andco) |
| `andustry` | Andustry | [#15](https://github.com/PalmerMichaels/yc-2026-public-master/issues/15) | `andustry-public` | [YC](https://www.ycombinator.com/companies/andustry) |
| `aquashield` | AquaShield | [#18](https://github.com/PalmerMichaels/yc-2026-public-master/issues/18) | `aquashield-public` | [YC](https://www.ycombinator.com/companies/aquashield) |
| `ara` | Ara | [#19](https://github.com/PalmerMichaels/yc-2026-public-master/issues/19) | `ara-public` | [YC](https://www.ycombinator.com/companies/ara) |
| `archer` | Archer | [#20](https://github.com/PalmerMichaels/yc-2026-public-master/issues/20) | `archer-public` | [YC](https://www.ycombinator.com/companies/archer) |
| `arctic-health` | Arctic Health | [#21](https://github.com/PalmerMichaels/yc-2026-public-master/issues/21) | `arctic-health-public` | [YC](https://www.ycombinator.com/companies/arctic-health) |
| `arden` | Arden | [#22](https://github.com/PalmerMichaels/yc-2026-public-master/issues/22) | `arden-public` | [YC](https://www.ycombinator.com/companies/arden) |
| `ardent` | Ardent | [#23](https://github.com/PalmerMichaels/yc-2026-public-master/issues/23) | `ardent-public` | [YC](https://www.ycombinator.com/companies/ardent) |
| `arga-labs` | Arga Labs | [#24](https://github.com/PalmerMichaels/yc-2026-public-master/issues/24) | `arga-labs-public` | [YC](https://www.ycombinator.com/companies/arga-labs) |
| `armature` | Armature | [#26](https://github.com/PalmerMichaels/yc-2026-public-master/issues/26) | `armature-public` | [YC](https://www.ycombinator.com/companies/armature) |
| `arzana` | Arzana | [#27](https://github.com/PalmerMichaels/yc-2026-public-master/issues/27) | `arzana-public` | [YC](https://www.ycombinator.com/companies/arzana) |
| `asendia-ai` | Asendia AI | [#28](https://github.com/PalmerMichaels/yc-2026-public-master/issues/28) | `asendia-ai-public` | [YC](https://www.ycombinator.com/companies/asendia-ai) |
| `asterlab` | Aster | [#30](https://github.com/PalmerMichaels/yc-2026-public-master/issues/30) | `asterlab-public` | [YC](https://www.ycombinator.com/companies/asterlab) |
| `atrisa` | Atrisa (formerly Refortifai) | [#32](https://github.com/PalmerMichaels/yc-2026-public-master/issues/32) | `atrisa-public` | [YC](https://www.ycombinator.com/companies/atrisa) |
| `auxos` | Auxos | [#34](https://github.com/PalmerMichaels/yc-2026-public-master/issues/34) | `auxos-public` | [YC](https://www.ycombinator.com/companies/auxos) |
| `bentolabs-ai` | BentoLabs AI | [#36](https://github.com/PalmerMichaels/yc-2026-public-master/issues/36) | `bentolabs-ai-public` | [YC](https://www.ycombinator.com/companies/bentolabs-ai) |
| `biostack-platforms` | BioStack Platforms | [#37](https://github.com/PalmerMichaels/yc-2026-public-master/issues/37) | `biostack-platforms-public` | [YC](https://www.ycombinator.com/companies/biostack-platforms) |
| `callab-ai` | Callab AI | [#38](https://github.com/PalmerMichaels/yc-2026-public-master/issues/38) | `callab-ai-public` | [YC](https://www.ycombinator.com/companies/callab-ai) |
| `centralcoms` | CentralComs | [#39](https://github.com/PalmerMichaels/yc-2026-public-master/issues/39) | `centralcoms-public` | [YC](https://www.ycombinator.com/companies/centralcoms) |
| `characterquilt` | CharacterQuilt | [#40](https://github.com/PalmerMichaels/yc-2026-public-master/issues/40) | `characterquilt-public` | [YC](https://www.ycombinator.com/companies/characterquilt) |
| `chert` | Chert | [#41](https://github.com/PalmerMichaels/yc-2026-public-master/issues/41) | `chert-public` | [YC](https://www.ycombinator.com/companies/chert) |
| `chronicle-labs` | Chronicle Labs | [#42](https://github.com/PalmerMichaels/yc-2026-public-master/issues/42) | `chronicle-labs-public` | [YC](https://www.ycombinator.com/companies/chronicle-labs) |
| `cignara` | Cignara | [#43](https://github.com/PalmerMichaels/yc-2026-public-master/issues/43) | `cignara-public` | [YC](https://www.ycombinator.com/companies/cignara) |
| `clara-2` | Clara | [#44](https://github.com/PalmerMichaels/yc-2026-public-master/issues/44) | `clara-2-public` | [YC](https://www.ycombinator.com/companies/clara-2) |
| `clawvisor` | Clawvisor | [#45](https://github.com/PalmerMichaels/yc-2026-public-master/issues/45) | `clawvisor-public` | [YC](https://www.ycombinator.com/companies/clawvisor) |
| `cohesion` | Cohesion | [#46](https://github.com/PalmerMichaels/yc-2026-public-master/issues/46) | `cohesion-public` | [YC](https://www.ycombinator.com/companies/cohesion) |
| `complir` | Complir | [#47](https://github.com/PalmerMichaels/yc-2026-public-master/issues/47) | `complir-public` | [YC](https://www.ycombinator.com/companies/complir) |
| `datost` | Datost | [#48](https://github.com/PalmerMichaels/yc-2026-public-master/issues/48) | `datost-public` | [YC](https://www.ycombinator.com/companies/datost) |
| `dayjob` | Dayjob | [#49](https://github.com/PalmerMichaels/yc-2026-public-master/issues/49) | `dayjob-public` | [YC](https://www.ycombinator.com/companies/dayjob) |
| `deep-interactions` | Deep Interactions | [#50](https://github.com/PalmerMichaels/yc-2026-public-master/issues/50) | `deep-interactions-public` | [YC](https://www.ycombinator.com/companies/deep-interactions) |
| `drafted` | Drafted | [#52](https://github.com/PalmerMichaels/yc-2026-public-master/issues/52) | `drafted-public` | [YC](https://www.ycombinator.com/companies/drafted) |
| `drippay` | Drip | [#53](https://github.com/PalmerMichaels/yc-2026-public-master/issues/53) | `drippay-public` | [YC](https://www.ycombinator.com/companies/drippay) |
| `elyra` | Elyra | [#55](https://github.com/PalmerMichaels/yc-2026-public-master/issues/55) | `elyra-public` | [YC](https://www.ycombinator.com/companies/elyra) |
| `expanse` | Expanse | [#57](https://github.com/PalmerMichaels/yc-2026-public-master/issues/57) | `expanse-public` | [YC](https://www.ycombinator.com/companies/expanse) |
| `flowscope` | flowscope | [#59](https://github.com/PalmerMichaels/yc-2026-public-master/issues/59) | `flowscope-public` | [YC](https://www.ycombinator.com/companies/flowscope) |
| `foaster` | Foaster | [#60](https://github.com/PalmerMichaels/yc-2026-public-master/issues/60) | `foaster-public` | [YC](https://www.ycombinator.com/companies/foaster) |
| `foresight` | Foresight | [#61](https://github.com/PalmerMichaels/yc-2026-public-master/issues/61) | `foresight-public` | [YC](https://www.ycombinator.com/companies/foresight) |
| `framewise-health` | Framewise Health | [#62](https://github.com/PalmerMichaels/yc-2026-public-master/issues/62) | `framewise-health-public` | [YC](https://www.ycombinator.com/companies/framewise-health) |
| `gigacatalyst` | Gigacatalyst | [#66](https://github.com/PalmerMichaels/yc-2026-public-master/issues/66) | `gigacatalyst-public` | [YC](https://www.ycombinator.com/companies/gigacatalyst) |
| `godhands` | GodHands | [#2](https://github.com/PalmerMichaels/yc-2026-public-master/issues/2) | `godhands-public` | [YC](https://www.ycombinator.com/companies/godhands) |
| `gojiberry-ai` | Gojiberry AI | [#67](https://github.com/PalmerMichaels/yc-2026-public-master/issues/67) | `gojiberry-ai-public` | [YC](https://www.ycombinator.com/companies/gojiberry-ai) |
| `govguard` | GovGuard | [#68](https://github.com/PalmerMichaels/yc-2026-public-master/issues/68) | `govguard-public` | [YC](https://www.ycombinator.com/companies/govguard) |
| `gravy` | Gravy | [#69](https://github.com/PalmerMichaels/yc-2026-public-master/issues/69) | `gravy-public` | [YC](https://www.ycombinator.com/companies/gravy) |
| `hessian` | Hessian | [#71](https://github.com/PalmerMichaels/yc-2026-public-master/issues/71) | `hessian-public` | [YC](https://www.ycombinator.com/companies/hessian) |
| `hexa` | Hexa | [#73](https://github.com/PalmerMichaels/yc-2026-public-master/issues/73) | `hexa-public` | [YC](https://www.ycombinator.com/companies/hexa) |
| `heyclicky` | HeyClicky | [#74](https://github.com/PalmerMichaels/yc-2026-public-master/issues/74) | `heyclicky-public` | [YC](https://www.ycombinator.com/companies/heyclicky) |
| `humwork` | Humwork | [#76](https://github.com/PalmerMichaels/yc-2026-public-master/issues/76) | `humwork-public` | [YC](https://www.ycombinator.com/companies/humwork) |
