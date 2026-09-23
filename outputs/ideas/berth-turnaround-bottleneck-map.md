# Berth Turnaround Bottleneck Map

**Pitch.** Measure where berth occupancy and boarding time force ferries or speedboats to queue.

**Type:** Original  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

A full sailing plan can fail at a shared wharf if boarding, cargo and arrival overlap. Port operators and councils need a capacity view.

**Decision supported:** Which berth needs a revised slot, boarding rule or physical upgrade?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) shows routes and [MTCC](https://mtcc.mv/wp-content/uploads/2024/06/Annual-Report-2023-2.pdf) describes terminal upgrades. A public berth-occupancy planning dashboard is **not verified**. Confidence: high on services/upgrades; low on gap.

## Prototype interaction

Animated berth Gantt chart linked to a harbour map; drag a slot or reduce turnaround time and see modeled queue minutes.

## Data plan

**Available now / collectable by the team:** Public [RTL](https://www.rtl.mv/) scheduled arrivals/departures and [OpenStreetMap](https://www.openstreetmap.org/) wharf geometry, checked on site. Use **synthetic** berth assignment and handling times unless a small observer pilot can verify them.

**Future data to collect and method:** Port authority logs berth_id, vessel_id, actual arrival, first line ashore, boarding start/end, departure, cargo handling window and queue start/end with clock-synced mobile form or AIS plus manual validation; daily data.

**Geographic coverage:** Pilot — one terminal; later participating high-traffic harbours.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** One terminal, a real published timetable and clearly synthetic berth/turnaround parameters; show sensitivity rather than claim actual delay.

**Longer-term rollout:** Pilot at one busy terminal, validate with harbour staff, then schedule berth slots and publish aggregate metrics.

## Value and safeguards

**Expected benefit:** Could reduce vessel idle time and missed connections.

**Limits:** Operational assignments may be commercially sensitive.

**Privacy:** No passenger identity needed; aggregate operator views.

**Dependencies:** Harbour authority access and safety approval for observations.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Good marine GIS and operational decision, though current observed data are thin.

**Feasibility: Medium — model easy, measurements harder.**  
**Distinctiveness: High — island wharves as network bottlenecks.**
