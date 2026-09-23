# Single-Link Failure Atlas

**Pitch.** Identify the bridges, wharves and ferry legs whose closure disconnects the most people from essentials.

**Type:** Original  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Small networks have critical links with few substitutes. Infrastructure planners need a transparent failure priority list.

**Decision supported:** Which link deserves preventive maintenance, backup service or contingency plan first?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) gives route structure, [MBS census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) gives island populations, and [NDMA](https://ndma.gov.mv/en/mandate) has preparedness responsibilities. A public multimode single-link failure atlas is **not verified**. Confidence: high on inputs/mandate; low on gap.

## Prototype interaction

Select a bridge, berth or ferry leg to close; map recalculates reachable population, clinic access and extra travel time by island.

## Data plan

**Available now / collectable by the team:** [RTL](https://www.rtl.mv/) timetable sample, [OpenStreetMap](https://www.openstreetmap.org/) roads/bridges and [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) population. Manually validate connectivity for Greater Malé plus one atoll; static data.

**Future data to collect and method:** Asset owners publish link_id, location, closure status, planned works and restoration estimate; operators publish alternative capacity and actual service status at each event. Refresh closures immediately, asset review quarterly.

**Geographic coverage:** Pilot — Greater Malé and one atoll sample; later national public transport assets.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Show only hypothetical closures over a verified network sample, with explicit assumptions about alternate capacity.

**Longer-term rollout:** Integrate formal closure feeds and a contingency playbook with councils and NDMA.

## Value and safeguards

**Expected benefit:** Prioritizes resilience spending.

**Limits:** Network topology cannot represent every informal/private option.

**Privacy:** No personal data.

**Dependencies:** Asset inventory and backup-service verification.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** A one-click failure scenario is compelling and spatially clear.

**Feasibility: Medium-high for static graph.**  
**Distinctiveness: High — quantifies island and bridge dependencies together.**
