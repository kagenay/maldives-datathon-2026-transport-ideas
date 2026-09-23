# After-Dark Island Access Gap

**Pitch.** Reveal which islands lose practical access to essential destinations after the last scheduled sailing.

**Type:** Original  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

The final departure can turn a short physical separation into an overnight access gap. Atoll councils and route schedulers need to see that temporal inequality.

**Decision supported:** Which one late sailing or overnight support location would close the largest gap?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) publishes schedules, while [MBS island indicators](https://statisticsmaldives.gov.mv/census-2022-island-and-atoll-level-indicator-sheets/) provide island context. A public after-dark access gap analysis is **not verified**. Confidence: high on inputs; low on gap.

## Prototype interaction

Island map turns from reachable to isolated as a clock advances; choose a clinic, work center or airport and compare the last departure with a proposed extension.

## Data plan

**Available now / collectable by the team:** [RTL](https://www.rtl.mv/) published service days and times for one atoll, [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) resident population, public destination locations validated on map. Static schedule checked before demo.

**Future data to collect and method:** Operators publish trip_id, service_date, final-departure time, actual departure/cancellation, capacity and booking cut-off through daily feed; councils maintain essential destination hours quarterly.

**Geographic coverage:** Pilot — one atoll; later all inhabited islands with published services.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Run the clock over a verified subset of scheduled services and show affected resident population as exposure, not observed passenger demand.

**Longer-term rollout:** Audit all atolls and use an opt-in travel survey to distinguish actual late-night need from theoretical access.

## Value and safeguards

**Expected benefit:** Simple, legible equity metric.

**Limits:** Population exposure does not equal nighttime travel demand.

**Privacy:** Aggregated island counts; suppress small survey cells.

**Dependencies:** Destination operating hours and service-day exceptions.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Very visual GIS/statistics demonstration with a single schedule decision.

**Feasibility: High — static schedules suffice for pilot.**  
**Distinctiveness: High — the day-to-night island connectivity framing is locally specific.**
