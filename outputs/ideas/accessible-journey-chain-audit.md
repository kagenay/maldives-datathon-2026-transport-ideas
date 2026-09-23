# Accessible Journey Chain Audit

**Pitch.** Identify where a nominally accessible Greater Malé bus journey fails between home, crossing, stop, vehicle and clinic.

**Type:** Adapted  
**Research status:** 24 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

A low-floor bus is insufficient if a curb, crossing or stop blocks the trip. Disability groups, councils and operators need end-to-end evidence, especially as the Greater Malé road network expands.

**Decision supported:** Which low-cost barrier should be fixed first to unlock the most complete journeys?

## Precedent and Maldivian equivalent

**Foreign precedent:** [Transport for NSW GTFS guidance](https://opendata.transport.nsw.gov.au/sites/default/files/2025-03/TfNSW%20GTFS%20%20GTFS%20R%20Implementation%20Specification%20v1.0.3.pdf) specifies wheelchair boarding at stops; [NYC DOT](https://www.nyc.gov/html/dot/html/infrastructure/accessiblepedsignals.shtml) publishes accessible crossing locations.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) has bus route information and [MTCC](https://mtcc.mv/wp-content/uploads/2024/06/Annual-Report-2023-2.pdf) reports access improvements, but an end-to-end audited barrier map is **not verified**. Confidence: medium on documented features; low on product status. Do not infer a trip is accessible from bus type alone.

## Prototype interaction

Walk-and-bus map with audit points, barrier type, photo evidence and route segments; toggle one curb-ramp or crossing repair to show newly connected destinations.

## Data plan

**Available now / collectable by the team:** [OpenStreetMap](https://www.openstreetmap.org/) paths and public [RTL](https://www.rtl.mv/) bus stops; team-collected opt-in, ground-checked audit of a small Greater Malé corridor (curb height, ramp slope, clear width, surface, crossing wait, bus boarding gap, timestamp), collected during fieldwork. Refresh pilot once.

**Future data to collect and method:** Councils/operators use a standardized mobile survey with stop_id, barrier_id, coordinates, dimensions, pass/fail, photo consent, inspection date and repair status; reassess quarterly and after works.

**Geographic coverage:** Pilot — one Malé or Hulhumalé bus-to-clinic corridor; later bus catchments and transfer points nationwide.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Audit one real corridor with permission and show precisely which links were verified; inaccessible or unvisited links stay unknown, not assumed open.

**Longer-term rollout:** Co-design scoring with disabled residents; maintain inspection and repair workflow nationwide.

## Value and safeguards

**Expected benefit:** Targets repairs that complete journeys.

**Limits:** A small pilot cannot characterize all Malé or all disability needs.

**Privacy:** Avoid faces and precise traveler traces; consent for photos.

**Dependencies:** Disability community review, field access and operator facility details.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Strong participatory GIS and inclusive policy action; a single repaired link makes a vivid 7-minute demo.

**Feasibility: High — a short, ethical field audit is achievable.**  
**Distinctiveness: High — audits the whole chain rather than one transport mode.**
