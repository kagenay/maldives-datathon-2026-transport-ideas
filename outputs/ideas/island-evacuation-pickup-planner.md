# Island Evacuation Pickup Planner

**Pitch.** Compare evacuation pickup sites and vessel allocation for isolated islands under a disaster scenario.

**Type:** Original  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Pickup capacity and harbour access may limit evacuation even with vessels nearby. NDMA and atoll councils need exercise planning.

**Decision supported:** Which pickup point or standby craft should be prioritized in a preparedness plan?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [NDMA’s mandate](https://ndma.gov.mv/en/mandate) covers preparedness and response, and [MMS](https://meteorology.gov.mv/awareness) has official hazard alerts. A public boat-pickup capacity simulator is **not verified**. Confidence: high on mandates; low on gap.

## Prototype interaction

Island map with candidate pickup sites, vulnerable population bands, vessel capacity and sailing-time assumptions; scenario slider shows clearance time and bottlenecks.

## Data plan

**Available now / collectable by the team:** [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) island/age aggregates, publicly mapped harbours, [NDMA](https://ndma.gov.mv/en) hazard context; **synthetic** vessel resources and evacuation demand for one atoll.

**Future data to collect and method:** NDMA and councils maintain pickup_site_id, access depth/status, safe capacity, sheltered area, estimated population needing assistance, vessel type/capacity, crew availability and drill timestamps; update quarterly and after every drill.

**Geographic coverage:** Pilot — one fictional atoll exercise; later NDMA-approved priority islands.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Use a clearly marked fictional exercise; compare two pickup-site allocations without claiming operational readiness.

**Longer-term rollout:** Run NDMA-led drills, validate clearance-time assumptions and restrict sensitive detailed plans to authorized users.

## Value and safeguards

**Expected benefit:** Reveals capacity and route bottlenecks before an emergency.

**Limits:** Evacuation is highly situation-specific; model cannot replace command decisions.

**Privacy:** Only aggregate vulnerability categories; safeguard sensitive infrastructure and household details.

**Dependencies:** NDMA governance and vessel/harbour verification.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Strong impact and scenario demo but institutional validation is substantial.

**Feasibility: Medium-low for operational use, medium for exercise demo.**  
**Distinctiveness: Very high — boat-dependent evacuation planning is geographically specific.**
