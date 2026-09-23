# Street Safety Intervention Map

**Pitch.** Prioritize Greater Malé junctions by exposure, observed conflicts and feasible street changes.

**Type:** Adapted  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Police aggregates show crashes but do not identify the junction treatment to fund. Councils, police and street designers need local evidence.

**Decision supported:** Which three crossings deserve a pilot curb extension, slower turn or protected pedestrian phase?

## Precedent and Maldivian equivalent

**Foreign precedent:** [NYC Vision Zero View](https://www.nyc.gov/content/visionzero/pages/vz-view) overlays injury crashes with safety interventions; [its open-data page](https://www.nyc.gov/content/visionzero/pages/open-data) documents the underlying collision and treatment data.

**Maldives evidence and confidence:** [Maldives Police](https://www.police.gov.mv/crime-statistics) publishes traffic-accident category counts, and the [transport master-plan terms](https://www.transport.gov.mv/pdf_file/741dcae8-041f-4442-9ee5-79f164737804/TOR-and-Timeline.pdf) call for traffic safety analysis. A public junction-level crash-and-treatment map is **not verified**. Confidence: high for aggregates/planning need; low for map absence.

## Prototype interaction

Map pilot crossings with pedestrian counts, turning-vehicle counts, conflict observations and intervention cards; compare a prioritization score under different weights.

## Data plan

**Available now / collectable by the team:** [Police](https://www.police.gov.mv/crime-statistics) aggregate context only, [OpenStreetMap](https://www.openstreetmap.org/) junctions, [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) nearby population and team-observed 15-minute counts at 3–5 Greater Malé junctions. Pilot observations refreshed once.

**Future data to collect and method:** Police and hospitals jointly publish de-identified crash_id, date/hour band, geocoded junction, modes, severity and injury; councils log treatment_id, location and installation date. Update monthly after QA.

**Geographic coverage:** Pilot — three to five Greater Malé junctions; later citywide and other urban islands.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Use actual pilot count sheets and clearly label them as short observations; do not imply they estimate annual crash risk. Show how priorities change with safety versus exposure weights.

**Longer-term rollout:** Add verified crash locations and evaluate before/after treatment trends with exposure normalization.

## Value and safeguards

**Expected benefit:** Turns safety data into testable street actions.

**Limits:** Short pilot counts and reporting bias limit inference.

**Privacy:** Do not publish faces, plates or exact victim records.

**Dependencies:** Safe counting protocol and agency crash-location access.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** GIS, new data collection and an obvious resource-allocation decision.

**Feasibility: High for pilot, medium for injury analytics.**  
**Distinctiveness: Medium-high — evidence-to-intervention workflow goes beyond accident totals.**
