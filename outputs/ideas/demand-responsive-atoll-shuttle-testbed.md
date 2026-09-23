# Demand-Responsive Atoll Shuttle Testbed

**Pitch.** Test whether a small pre-booked speedboat service could fill gaps without replacing viable fixed routes.

**Type:** Adapted  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Sparse off-peak demand may not justify a fixed sailing but some islands still need access. Atoll councils and operators need a transparent trial design.

**Decision supported:** Which island pair, day and booking window merit a controlled pilot?

## Precedent and Maldivian equivalent

**Foreign precedent:** Ireland’s [TFI Local Link](https://www.transportforireland.ie/tfi-local-link/) offers pre-booked flexible rural transport; [TFI Anseo](https://www.transportforireland.ie/news/minister-calleary-and-nta-launch-irelands-first-smart-demand-responsive-transport-pilot-in-achill/) documents an app-based demand-responsive pilot.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) provides scheduled ferry and booking; [MTCC Southern Transport Link](https://stl.mtcc.mv/) also books ferries. A publicly documented demand-responsive atoll boat service is **not verified**. Confidence: high on fixed/booking services; low on absence.

## Prototype interaction

Atoll map with fixed routes plus hypothetical request dots; compare fixed, on-demand and hybrid coverage, wait, vessel-hours and cost under user-selected demand.

## Data plan

**Available now / collectable by the team:** [RTL](https://www.rtl.mv/) timetables and [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) island population; **synthetic** anonymous trip requests, costs and vessel capacity in the demo. No private booking records.

**Future data to collect and method:** With consent, pilot operator records request_id pseudonym, requested origin/destination, earliest/latest window, party size, accessibility need category, accepted/rejected, actual pickup, fuel and vessel-hours; delete detailed requests on a schedule and publish only aggregates weekly.

**Geographic coverage:** Pilot — one illustrative atoll; later selected low-frequency atolls.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Run several clearly synthetic demand scenarios over real island geography and published fixed schedules; show break-even boundaries, not a predicted business case.

**Longer-term rollout:** Run a six-week voluntary booking pilot with phone access, then compare denied demand and cost per completed trip.

## Value and safeguards

**Expected benefit:** May serve low-demand trips efficiently.

**Limits:** Sea state, safety regulation and very low demand can defeat pooling.

**Privacy:** Minimize requests, pseudonymize and suppress tiny island cells.

**Dependencies:** Operator, maritime safety approval, vessel costs.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Decision simulator with clear policy tradeoffs and local geography.

**Feasibility: Medium — simulation works, behavioral demand is unknown.**  
**Distinctiveness: High — applies DRT to atoll sea travel.**
