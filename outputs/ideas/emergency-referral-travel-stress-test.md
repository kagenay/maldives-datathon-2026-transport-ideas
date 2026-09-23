# Emergency Referral Travel Stress Test

**Pitch.** Stress-test which islands lack a timely route to appropriate care when one sea or air link is unavailable.

**Type:** Original  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Medical referrals depend on vessel type, weather, facility capability and handoffs. Health emergency planners need a preparedness map, not patient routing advice.

**Decision supported:** Where should standby transport, equipment or a referral agreement be strengthened?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** The [Ministry of Health safe transport guideline](https://health.gov.mv/storage/uploads/8qe8PdYP/iqlvm2yb.pdf) documents sea, air and helicopter transfer modes, and [MMS](https://www.meteorology.gov.mv/forecast) issues marine forecasts. A public scenario-based referral vulnerability map is **not verified**. Confidence: high on existing response arrangements; low on gap.

## Prototype interaction

Map of islands colored by modeled time to an appropriate facility under normal, rough-sea and unavailable-vessel scenarios; click an island for assumptions and fallback chain.

## Data plan

**Available now / collectable by the team:** [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) island population, official [health transport guideline](https://health.gov.mv/storage/uploads/8qe8PdYP/iqlvm2yb.pdf), [MMS](https://www.meteorology.gov.mv/forecast) alert categories and public geography. Use **synthetic** vessel availability, transfer times and facility capability unless independently verified.

**Future data to collect and method:** Health and emergency agencies capture island_id, referral capability category, dispatch request time, mode, vessel/aircraft availability, departure/arrival timestamps, weather category and outcome category in a secure registry; publish only island/atoll aggregates after disclosure review quarterly.

**Geographic coverage:** Pilot — one illustrative atoll; later clinically validated national coverage.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Two transparent hypothetical emergencies at the same island, one with a blocked sea leg. Display uncertainty ranges and an explicit “planning exercise, not dispatch guidance” label.

**Longer-term rollout:** Secure interagency data agreement, validate simulations against de-identified historical timings, and use only with clinical/dispatch governance.

## Value and safeguards

**Expected benefit:** Identifies backup gaps before crises.

**Limits:** Highly sensitive inputs and safety-critical assumptions; unsuitable for real-time triage at datathon.

**Privacy:** Never display patient records, exact incidents or identifiable dispatch traces.

**Dependencies:** Health, MNDF and operator collaboration; clinical validation.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Excellent policy relevance, GIS and climate resilience with a crisp scenario story.

**Feasibility: Medium-high for planning demo; real model needs agency data.**  
**Distinctiveness: Very high — island emergency dependency is unusually specific.**
