# Greater Malé Traffic Count Map

**Pitch.** Create repeatable junction-level vehicle counts to target congestion measures instead of relying on anecdote.

**Type:** Adapted  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Road space is scarce and planners need mode-specific counts by time, especially motorcycles and buses.

**Decision supported:** Which junction and time period should receive a signal or loading-rule study?

## Precedent and Maldivian equivalent

**Foreign precedent:** The UK Department for Transport publishes [mapped count-point data](https://www.data.gov.uk/dataset/208c0e7b-353f-4e2d-8b7a-1a7118467acc/gb-road-traffic-counts), including raw trained-enumerator counts and vehicle types.

**Maldives evidence and confidence:** The [Maldives transport master-plan terms](https://www.transport.gov.mv/pdf_file/741dcae8-041f-4442-9ee5-79f164737804/TOR-and-Timeline.pdf) explicitly request a Greater Malé congestion heat map. A public, reproducible junction count map is **not verified**. Confidence: high on planning demand; low on product absence.

## Prototype interaction

Street map with normalized vehicles per hour by mode and observed turning movements; compare school start and midday periods, with sample-size badges.

## Data plan

**Available now / collectable by the team:** [OpenStreetMap](https://www.openstreetmap.org/) junctions plus a team-collected manual count at 4 sites using a published protocol: site_id, arm, 15-minute interval, vehicle class, turn and weather. [MBS census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) contextual population only. One-day pilot, no citywide inference.

**Future data to collect and method:** City/transport agency establishes fixed count stations or quarterly video-to-aggregate surveys with site_id, time, direction, vehicle class and QA flags; erase raw video after aggregation. Quarterly counts.

**Geographic coverage:** Pilot — four Greater Malé sites; later repeatable network count points.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Show four audited 15-minute count windows with a filter and an explicit coverage mask; explain what additional sampling is needed.

**Longer-term rollout:** Standardize count locations and repeated seasons, then test interventions before/after.

## Value and safeguards

**Expected benefit:** Provides low-cost baseline for road allocation.

**Limits:** A few windows cannot establish annual congestion.

**Privacy:** Count vehicle classes, never plates or faces.

**Dependencies:** Safe observer positions and repeatable protocol.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Strong new statistical data method, GIS and direct planning use.

**Feasibility: High — manual counts are practical.**  
**Distinctiveness: Medium — standard method, locally valuable data gap.**
