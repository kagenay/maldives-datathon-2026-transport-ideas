# Single-Link Failure Atlas

**Pitch.** Identify which existing bridge, key road or atoll ferry link would disrupt the most essential journeys if closed.

**Type:** Original  
**Research status:** 24 September 2026; concept document. The planned western bridge is a separate future scenario.

## Problem, users and decision

Small networks have critical links with few substitutes. Infrastructure planners need a transparent failure priority list.

**Decision supported:** Which link deserves preventive maintenance, backup service or contingency plan first?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) gives bus/ferry route structure, [MBS census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) gives populations, and the [transport ministry](https://www.transport.gov.mv/pdf_file/741dcae8-041f-4442-9ee5-79f164737804/TOR-and-Timeline.pdf) explicitly asks for Greater Malé network analysis. A public multimode single-link failure atlas is **not verified**. Confidence: high on inputs/need; low on product status.

## Prototype interaction

Select the existing Sinamalé Bridge or a key road to close; the Greater Malé map recalculates bus, walking and clinic access. A second, separately styled scenario adds the planned western bridge. Atoll ferry-link failures are an optional national extension.

## Data plan

**Available now / collectable by the team:** [RTL](https://www.rtl.mv/) bus timetable sample, [OpenStreetMap](https://www.openstreetmap.org/) existing roads/bridges and [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) population. Manually validate Greater Malé network links; planned bridge geometry is visibly hypothetical until official engineering data permit reuse.

**Future data to collect and method:** Asset owners publish link_id, location, closure status, planned works and restoration estimate; operators publish alternative capacity and actual service status at each event. Refresh closures immediately, asset review quarterly.

**Geographic coverage:** Pilot — existing Greater Malé road and bus network; later bridge-opening assessment and selected national ferry links.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Show a hypothetical Sinamalé closure over a verified current road graph, then a separate planned-bridge scenario; never imply either closure or future link is observed/open.

**Longer-term rollout:** Integrate formal closure feeds and a contingency playbook with councils and NDMA.

## Value and safeguards

**Expected benefit:** Prioritizes resilience spending.

**Limits:** Network topology cannot represent every informal/private option.

**Privacy:** No personal data.

**Dependencies:** Asset inventory and backup-service verification.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** A one-click failure scenario is compelling and spatially clear.

**Feasibility: Medium-high for static graph.**  
**Distinctiveness: High — compares current and planned bridge redundancy while retaining atoll extension.**
