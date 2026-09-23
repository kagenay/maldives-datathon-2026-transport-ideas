# Ferry Reliability and Lifeline Scorecard

**Pitch.** Compare route reliability and the population affected when an essential sailing fails.

**Type:** Adapted  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

A cancellation on a low-frequency island route can matter more than one on a frequent corridor. Operators, regulators and councils need a fair service metric.

**Decision supported:** Where should a spare vessel or protected sailing be allocated?

## Precedent and Maldivian equivalent

**Foreign precedent:** Scotland’s [CalMac monthly route performance reports](https://corporate.calmac.co.uk/en-gb/about-us/chfs3/annual-plan/) publish reliability and punctuality; [route packs](https://assets.calmac.co.uk/media/gzrmybsz/mull.pdf) list scheduled, operated, cancelled and diverted sailings.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) shows schedules and live tracking; [MTCC](https://mtcc.mv/wp-content/uploads/2024/06/Annual-Report-2023-2.pdf) publishes annual ridership figures. A publicly accessible route-level cancellation dataset or lifeline-weighted scorecard is **not verified**. Confidence: high on those visible products; low on nonexistence.

## Prototype interaction

Route map with ordinary cancellation rate versus population-weighted missed-service days; filter weather, technical and berth reasons, then test spare-vessel allocation.

## Data plan

**Available now / collectable by the team:** [RTL](https://www.rtl.mv/) scheduled trips and [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) island population. No verified public historical route-level cancellation file; prototype uses **synthetic** trip outcomes for a clearly marked example.

**Future data to collect and method:** MTCC and other operators enter route_id, trip_id, vessel_id, scheduled and actual times, operated/cancelled/diverted status and standardized reason into dispatch log; release route-month counts and punctuality after QA monthly.

**Geographic coverage:** Pilot — a synthetic two-route example; later all reporting operators and atolls.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Use public routes plus conspicuously synthetic 30-day service histories; change which route receives the spare vessel and show modeled exposure.

**Longer-term rollout:** Agree common definitions and automate quality checks across operators before publishing the scorecard.

## Value and safeguards

**Expected benefit:** Makes reliability investment more equitable and measurable.

**Limits:** Synthetic outcome charts cannot describe real service performance.

**Privacy:** Publish counts, not ticket identities; protect sensitive vessel movement if needed.

**Dependencies:** Operator reporting standard and denominator definition.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Clear policy metric and strong story but real outcome data is a future dependency.

**Feasibility: Medium — interface is easy; real reliability claims require new data.**  
**Distinctiveness: High — lifeline weighting reflects island dependence.**
