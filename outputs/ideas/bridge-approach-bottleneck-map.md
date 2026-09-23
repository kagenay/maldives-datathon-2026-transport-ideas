# Bridge Approach Bottleneck Map

**Pitch.** Identify which junctions and crossings around the existing and planned Greater Malé bridges could become bottlenecks.

**Type:** Original

**Research status:** 24 September 2026; concept document. Future link operation is **not verified**.

## Problem, users and decision

A bridge shifts pressure onto a few approach streets and crossings. Road authorities, councils, bus operators and pedestrians need to distinguish a bridge-capacity problem from a local junction problem.

**Decision supported:** Which approach junction should receive a turning-rule, bus-priority or pedestrian-crossing pilot first?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** The [transport ministry's Greater Malé mobility terms](https://www.transport.gov.mv/pdf_file/741dcae8-041f-4442-9ee5-79f164737804/TOR-and-Timeline.pdf) call for congestion heat maps and future-link assessment; the [President's Office](https://presidency.gov.mv/Press/Article/37257) describes bridge construction progress. A public bridge-approach queue and conflict map is **not verified**. Confidence: high on the decision need; low on product status.

## Prototype interaction

Map each approach junction with counted vehicles, motorcycles, buses and pedestrians by movement. A timeline shows queue growth; a scenario toggle reroutes a hypothetical share of traffic onto the future bridge and highlights the resulting pressure on nearby crossings.

## Data plan

**Available now / collectable by the team:** Dated [OpenStreetMap](https://www.openstreetmap.org/) street geometry, public [RTL](https://www.rtl.mv/) bus routes, and team-collected 15-minute turning/pedestrian counts at 2–3 safe public-side junctions near the existing Sinamalé Bridge or planned western approach. Fields: site_id, arm, turn, mode, time band, queue length, crossing count, weather. One-day pilot; no future-bridge counts claimed.

**Future data to collect and method:** Road authority installs or conducts periodic count stations for approach_id, direction, vehicle class, hourly flow, queue length, bus delay and crossing wait. Collect before opening and daily after opening for an initial monitoring period; publish verified aggregate series monthly.

## Demo and rollout

**Datathon demo:** Show real baseline turning movements where collected, then a visibly **synthetic bridge-opening load scenario**. Let judges pick a junction and compare two reversible treatments.

**Longer-term rollout:** Lock count locations, repeat measurements after road changes and evaluate observed delay/safety instead of relying on the forecast.

## Value and safeguards

**Expected benefit:** Finds lower-cost junction fixes before widening or major construction.

**Limits:** A tiny count sample does not forecast citywide traffic; queue models need calibration.

**Privacy:** Do not collect faces, plates or individual vehicle paths.

**Dependencies:** Safe count locations and updated bridge approach design.

## Datathon fit and ratings

The [2026 FAQ](https://www.datathon.stats.gov.mv/faq) explicitly welcomes traffic-flow, GIS and transport-planning tools. The before/future junction comparison is visual and policy focused.

**Feasibility: High — existing-junction counts are possible now; future flows stay synthetic.**

**Distinctiveness: High — focuses on the streets that absorb bridge traffic, not only the bridge itself.**
