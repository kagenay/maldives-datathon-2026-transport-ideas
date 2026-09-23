# Ferry-to-Bus Transfer Walk Clock

**Pitch.** Measure whether the physical walk from ferry arrival to bus boarding fits the published transfer window.

**Type:** Original  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Transfer plans often ignore terminal exit, crossing and bus-stop access time. MTCC schedulers and city planners need measured transfer margins.

**Decision supported:** Should a bus departure be shifted, a stop moved or a walking crossing improved?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) includes both ferry and bus information, and [MTCC](https://mtcc.mv/wp-content/uploads/2024/06/Annual-Report-2023-2.pdf) describes app live tracking. A publicly audited terminal-to-bus walking-margin tool is **not verified**. Confidence: high on RTL scope; low on gap.

## Prototype interaction

Map a terminal-to-stop route with timed steps, crossing waits and accessibility detours; compare transfer success under different ferry delays.

## Data plan

**Available now / collectable by the team:** [RTL](https://www.rtl.mv/) public schedules, [OpenStreetMap](https://www.openstreetmap.org/) sidewalks, and timed team walks at one Greater Malé transfer (start/end, route, crossing wait, walking condition, mobility profile selected only with consent). Repeat several runs.

**Future data to collect and method:** Operator logs actual ferry door-open and bus door-close timestamps by trip_id; city audits safe path length and closures monthly. No need to track individual passengers.

**Geographic coverage:** Pilot — one Greater Malé terminal transfer; later all transfer terminals.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Show distribution of a few clearly labelled pilot walks and compare with scheduled margins; hypothetical ferry delays are separate.

**Longer-term rollout:** Repeat for peak and off-peak periods and revise schedules/wayfinding using actual trip data.

## Value and safeguards

**Expected benefit:** Low-cost integration fix for a common daily journey.

**Limits:** A small healthy-adult walk sample cannot represent all mobility needs.

**Privacy:** No identifiable routes or tracking of people; record observer timing only.

**Dependencies:** Safe walk audit and time-synced schedules.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Specific, measurable and easy to explain in a short pitch.

**Feasibility: High — small real pilot possible.**  
**Distinctiveness: Medium-high — focuses on the physical transfer rather than only timetable graph.**
