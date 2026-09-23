# Holiday Last-Seat Stress Test

**Pitch.** Estimate how peak holiday demand could strand travelers even when a timetable exists.

**Type:** Original  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Fixed seats and burst demand may expose islands to same-day return failures. Operators and councils need peak contingency planning.

**Decision supported:** Which route and date needs an extra sailing or protected resident quota?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) offers seat booking and schedules; [MTCC](https://mtcc.mv/wp-content/uploads/2024/06/Annual-Report-2023-2.pdf) reports ridership. A public peak stranded-passenger stress test is **not verified**. Confidence: high on booking service; low on gap.

## Prototype interaction

Route/date map with seat capacity, demand scenarios and stranded-night counts; slider tests extra sailing or quota.

## Data plan

**Available now / collectable by the team:** [RTL](https://www.rtl.mv/) public timetable and verified vessel capacities if published; otherwise **synthetic** seats and holiday demand. [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) population is a scale anchor, not a demand estimate.

**Future data to collect and method:** Operators log trip_id, service_date, sellable seats, booked seats, no-shows, denied/waitlisted requests, resident/visitor category only if lawful and anonymous; aggregate weekly with small-cell suppression.

**Geographic coverage:** Pilot — one route and holiday scenario; later high-demand routes.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Compare low, medium and high **synthetic** demand scenarios, with no statement about actual booking pressure.

**Longer-term rollout:** Validate with anonymized booking aggregates and publish seasonal capacity plans.

## Value and safeguards

**Expected benefit:** Supports fair contingency capacity.

**Limits:** Booking behavior and cancellations can alter actual unmet demand.

**Privacy:** Do not expose individual booking history or citizenship status.

**Dependencies:** Operator capacity and booking aggregates.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Interactive service allocation decision, though data deficit lowers immediate strength.

**Feasibility: Medium — scenario is easy, calibration needs data.**  
**Distinctiveness: High — last-seat and overnight island consequences are specific.**
