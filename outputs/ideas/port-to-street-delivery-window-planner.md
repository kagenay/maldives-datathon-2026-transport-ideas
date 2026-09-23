# Port-to-Street Delivery Window Planner

**Pitch.** Test how changing cargo unloading windows could reduce conflicts with peak walking and bus movement.

**Type:** Original  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Goods must move off boats onto narrow streets, often near passenger terminals. Port managers and city planners need timing evidence.

**Decision supported:** Which unloading window minimizes combined freight delay and pedestrian conflict?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [MTCC downloads](https://mtcc.mv/downloads/) list cargo ferry schedules and the [transport master-plan terms](https://www.transport.gov.mv/pdf_file/741dcae8-041f-4442-9ee5-79f164737804/TOR-and-Timeline.pdf) request road congestion analysis. A public port-to-street delivery window planner is **not verified**. Confidence: medium-high on schedules/planning need; low on gap.

## Prototype interaction

Linked port berth and adjacent street timeline; adjust unloading slot to see modeled cart/truck and pedestrian overlap.

## Data plan

**Available now / collectable by the team:** Public cargo ferry schedules from [MTCC downloads](https://mtcc.mv/downloads/), [OpenStreetMap](https://www.openstreetmap.org/) street geometry, a short manual count of carts/trucks/pedestrians if safe; otherwise **synthetic** flows. One Greater Malé port pilot.

**Future data to collect and method:** Port/city teams record shipment arrival window (no commercial contents), unloading start/end, vehicle class/count, exit time, street occupancy and pedestrian count by 15-minute block via gate tally and periodic observation; aggregate monthly.

**Geographic coverage:** Pilot — one Greater Malé port; later consenting cargo terminals.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Use one real published timetable and explicit synthetic overlap rates; show how a window shift changes modeled conflicts.

**Longer-term rollout:** Pilot a reversible loading-window rule and repeat counts for congestion/safety effects.

## Value and safeguards

**Expected benefit:** Could reduce peak street friction without new construction.

**Limits:** Private cargo schedules and operational constraints may restrict feasible shifts.

**Privacy:** Do not publish customer, shipment or license-plate data.

**Dependencies:** Port authority and cargo operator consent.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Clear optimization story but weakest ready-data position among options.

**Feasibility: Medium-low — requires operational access for a defensible result.**  
**Distinctiveness: High — connects marine logistics to dense island streets.**
