# Essential Medicines Parcel Reach

**Pitch.** Test how ferry schedules affect the time to move essential medicine parcels to island clinics.

**Type:** Original  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

A passenger route may not accept temperature-sensitive parcels or may miss clinic hours. Health logisticians need a transport reach metric.

**Decision supported:** Where should a scheduled courier handoff, storage point or route change be piloted?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) publishes passenger routes and [Ministry of Health transport guidance](https://health.gov.mv/storage/uploads/8qe8PdYP/iqlvm2yb.pdf) documents medical transport, but a public medicine-parcel timetable tool is **not verified**. Confidence: medium on context; low on gap.

## Prototype interaction

Origin depot-to-clinic timeline and island map showing scheduled handoffs, cold-chain waiting time and alternative dispatch days.

## Data plan

**Available now / collectable by the team:** Public [RTL](https://www.rtl.mv/) schedule, [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) geography, publicly verified clinic locations; **synthetic** parcel volumes, cold-chain limits and depot stock for demo.

**Future data to collect and method:** Health supply chain and operators record parcel batch_id pseudonym, category, temperature requirement, origin, destination, dispatch/arrival times, accepted carrier, cold-storage readings and failed handoffs in a secure system; publish aggregated route-month service metrics.

**Geographic coverage:** Pilot — one hypothetical depot-to-clinic path; later consenting atoll health networks.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Show a hypothetical insulin replenishment case clearly labelled scenario; use no real stock or patient information.

**Longer-term rollout:** Partner with one atoll health network for a controlled logistics pilot and validate handling rules.

## Value and safeguards

**Expected benefit:** Could reduce avoidable stockout risk.

**Limits:** Transport time alone does not establish inventory need; cold-chain compliance is safety-critical.

**Privacy:** Keep clinic stock levels and batch details protected.

**Dependencies:** Health supply data and operator handling agreement.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Unusual but practical linkage of transport data to public service allocation.

**Feasibility: Medium-low — supply inputs are not public.**  
**Distinctiveness: High — treats ferry schedules as health logistics infrastructure.**
