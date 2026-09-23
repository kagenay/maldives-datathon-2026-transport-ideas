# Heat-and-Rain Walking Comfort Map

**Pitch.** Locate exposed walks to bus stops and ferry terminals where shade or shelter would help the most people.

**Type:** Original  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Short walks can be difficult under strong sun or rain; councils need to prioritize small-scale shelter investments.

**Decision supported:** Which two street segments or stops should get shade or rain cover first?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) lists stops/routes and [MMS](https://www.meteorology.gov.mv/forecast) provides weather forecasts. A verified public shade-and-shelter access map is **not verified**. Confidence: high on components; low on gap.

## Prototype interaction

Walking network colored by observed cover and exposure; select a stop, time of day and hypothetical new shelter to see people-hours of unprotected access reduced.

## Data plan

**Available now / collectable by the team:** [OpenStreetMap](https://www.openstreetmap.org/) paths, [RTL](https://www.rtl.mv/) stops, [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) population and a field audit of cover type, segment length, time, weather and photos without people on one corridor. Solar exposure is modeled and labelled.

**Future data to collect and method:** Council crews survey segment_id, shelter width/condition, usable covered length, obstruction and maintenance status twice yearly; anonymous pedestrian counts by hour quarterly.

**Geographic coverage:** Pilot — one Greater Malé walking corridor; later bus and ferry catchments.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Show audited segments and a hypothetical shelter intervention; no claim that modeled exposure equals heat illness risk.

**Longer-term rollout:** Validate with repeated counts and user feedback, then link to capital works.

## Value and safeguards

**Expected benefit:** Improves walkability and inclusive access.

**Limits:** Population is a weak proxy for actual footfall; cloud and building shade vary.

**Privacy:** No individual paths or photos of faces.

**Dependencies:** Field audit and shade model validation.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Accessible, visual local GIS project, but outcome evidence takes longer.

**Feasibility: Medium-high — corridor pilot straightforward.**  
**Distinctiveness: Medium-high — tropical last-mile comfort linked to transit.**
