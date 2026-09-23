# Island-to-Clinic Access Atlas

**Pitch.** Map the actual scheduled time and transfer burden for each island to reach a higher-level health facility.

**Type:** Adapted  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

A straight-line distance hides waits, missed connections, and infrequent departures. Atoll planners, health planners and residents need a service-access measure.

**Decision supported:** Which island or departure window should receive an extra sailing, referral slot, or overnight support first?

## Precedent and Maldivian equivalent

**Foreign precedent:** Transport for London’s [WebCAT](https://tfl.gov.uk/info-for/urban-planning-and-construction/planning-applications/planning-with-webcat?intcmp=25861) maps travel-time catchments and public-transport access for planning; this adapts that method to scheduled sea travel.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) already publishes routes and schedules; [MBS OneMap](https://statisticsmaldives.gov.mv/atoll-profiles/) already visualizes census data. A public timetable-based health access atlas is **not verified**. Confidence: high that the component services exist; low on the claimed gap.

## Prototype interaction

Select an origin island, weekday, departure time and maximum travel time; the map shades reachable islands and facilities, with a timetable path, waiting-time waterfall and a before/after extra-sailing slider.

## Data plan

**Available now / collectable by the team:** Island population (island_id, resident_population, age group where published) from [Census 2022](https://statisticsmaldives.gov.mv/census-2022-results-summary/); island positions from [OpenStreetMap](https://www.openstreetmap.org/) after manual validation; public route/stop/departure/arrival times from [RTL](https://www.rtl.mv/) sampled and attributed. Pilot: two atolls and Greater Malé; census fixed, schedules checked before demo.

**Future data to collect and method:** Agency would publish machine-readable service calendar, trip_id, stop_id, scheduled and actual arrival/departure, cancellation, transfer guarantee and facility referral capability. Operators log each trip at dispatch and arrival; health agency updates facility capability quarterly. Refresh trips daily and actuals after each sailing.

**Geographic coverage:** Pilot — two atolls and Greater Malé; later all inhabited islands.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Build a small audited schedule graph from public times; show one island gaining access when a departure shifts. Label any estimated transfer and facility capability as assumptions; do not use patient records.

**Longer-term rollout:** Extend to all atolls with operator feeds and verified health facilities; validate calculated travel times with observed trips.

## Value and safeguards

**Expected benefit:** Makes a funding question visible and supports equitable scheduling.

**Limits:** Static schedules do not prove reliability; do not route an actual emergency with it.

**Privacy:** Use aggregated census counts only; no patient origins.

**Dependencies:** Schedule extraction permission, facility list verification and manual geocoding.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Strong GIS plus official statistics; the single before/after accessibility map is clear in seven minutes.

**Feasibility: High — public census and a two-atoll timetable sample support a credible static demo.**  
**Distinctiveness: High — measures sea-connected service access instead of merely showing routes.**
