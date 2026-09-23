# Open Multimodal Island Journey Graph

**Pitch.** Represent public bus, ferry and walking legs in one transparent graph for route-change testing.

**Type:** Adapted  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Travelers and planners need to understand complete journeys across modes, including transfers. Government and civic developers need a reusable data model.

**Decision supported:** Which route or transfer change improves door-to-door access most?

## Precedent and Maldivian equivalent

**Foreign precedent:** Finland’s [Digitransit](https://portal-api.digitransit.fi/) is an open-source journey planning platform; [Transport for NSW](https://opendata.transport.nsw.gov.au/developers/documentation) publishes GTFS for buses and ferries.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) already offers route maps, schedules, tracking and tickets; this is **not** a claim that Maldives lacks a journey planner. A public, reusable cross-mode graph/feed for policy experiments is **not verified**. Confidence: high on RTL features, low on feed status.

## Prototype interaction

Interactive path finder for a small Greater Malé sample with walking, bus and ferry legs, plus a toggle to close a link or retime a service.

## Data plan

**Available now / collectable by the team:** Public [RTL](https://www.rtl.mv/) route/schedule sample, [OpenStreetMap](https://www.openstreetmap.org/) walking links and [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) context. Validate all stops manually; sample is explicitly incomplete.

**Future data to collect and method:** Operators publish GTFS fields agency, route, stop, trip, stop_time, calendar, shape, fare and accessibility; add trip updates and alerts, versioned daily, with license terms. Council maintains safe walking connections monthly.

**Geographic coverage:** Pilot — a small Greater Malé bus-ferry-walk subnetwork; later all participating operators.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Encode a small verified sample as static GTFS-like tables; show route closure and access change. Clearly mark coverage and missing operators.

**Longer-term rollout:** Govern a national feed with quality checks and open documentation, then connect journey planners and agency analysis.

## Value and safeguards

**Expected benefit:** Reusable transport data infrastructure.

**Limits:** High implementation breadth; static routes ignore actual reliability.

**Privacy:** Public schedules only.

**Dependencies:** Licensing and operator data stewardship.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Matches the challenge’s data-system emphasis, but infrastructure story is harder to pitch than one policy outcome.

**Feasibility: Medium-high — small graph works, national standard needs partners.**  
**Distinctiveness: Medium — open data foundation has high reuse, modest novelty.**
