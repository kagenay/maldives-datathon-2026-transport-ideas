# Missed-Connection Ferry Heatmap

**Pitch.** Find timetable transfers that are possible on paper but leave passengers with an unsafe or very long wait.

**Type:** Adapted  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Separate RTL legs can make an inter-island journey depend on a short connection. Transport schedulers and atoll councils need to see weak transfers.

**Decision supported:** Which two sailings should be retimed to reduce missed connections per timetable cycle?

## Precedent and Maldivian equivalent

**Foreign precedent:** [Transport for NSW open data](https://opendata.transport.nsw.gov.au/developers/documentation) publishes ferry timetables, trip updates and service alerts that support connection analysis.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) provides route maps, live tracking and schedules, and [MTCC reports](https://mtcc.mv/wp-content/uploads/2024/06/Annual-Report-2023-2.pdf) dynamic schedules. A public connection-risk planning heatmap is **not verified**. Confidence: high on RTL features; low on absence of equivalent.

## Prototype interaction

Time-expanded network map of transfer ports; click an arrival to see feasible onward departures and waiting-time bands. Drag a departure by 10 minutes to watch at-risk links change.

## Data plan

**Available now / collectable by the team:** Public [RTL](https://www.rtl.mv/) stop names, routes, days and scheduled times, manually transcribed for one or two atolls; static island coordinates and [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) population. Schedules checked before the event.

**Future data to collect and method:** Operators record trip_id, actual berth time, first boarding time, final departure, cancellation reason, seat availability and transfer-held flag at every port via dispatch app; share daily aggregates/GTFS-Realtime where licensed. Refresh each sailing.

**Geographic coverage:** Pilot — one or two atolls; later all published ferry and bus transfers.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Use only static connection margins from actual published schedules; an optional delay slider uses clearly labelled hypothetical delays, never alleged historical reliability.

**Longer-term rollout:** Add operator actuals and ferry-to-bus transfers; validate the threshold for feasible walking/boarding time at each terminal.

## Value and safeguards

**Expected benefit:** Low-cost timetable fixes may prevent stranded trips.

**Limits:** A scheduled connection is not a guaranteed connection or available seat.

**Privacy:** No identifiable ticket records required.

**Dependencies:** Accurate route calendar, port walking times and operator cooperation.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Directly answers a scheduling decision using GIS and official population exposure; one retiming slider tells the pitch story.

**Feasibility: High — a limited public-schedule network is tractable.**  
**Distinctiveness: Medium-high — shifts focus from route display to connection quality.**
