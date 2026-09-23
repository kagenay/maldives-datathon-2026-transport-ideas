# Island Fare Burden Lens

**Pitch.** Compare the affordability of reaching essential services across islands and household types.

**Type:** Original  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

A low single-leg fare may become expensive after multiple transfers or overnight stays. Social and transport planners need an end-to-end burden measure.

**Decision supported:** Where would a transfer discount, targeted fare cap or timetable change matter most?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) publishes tickets and schedules; [MBS datathon FAQ](https://www.datathon.stats.gov.mv/faq) says HIES 2019 data will be supplied to participants. A public island-level end-to-end fare burden dashboard is **not verified**. Confidence: high on component services; low on gap.

## Prototype interaction

Island choropleth of modeled fare plus unavoidable lodging against income bands; choose household type and policy option.

## Data plan

**Available now / collectable by the team:** Published [RTL](https://www.rtl.mv/) fares where visible and [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) island population. Use event HIES only after organizers release it and confirm permitted fields/aggregation; until then use **synthetic** income bands and no poverty claims.

**Future data to collect and method:** MBS could publish disclosure-safe island/atoll income deciles; operators publish fare_id, eligibility, transfer rules and historic fare changes. Update fares on change and household metrics by survey release.

**Geographic coverage:** Pilot — a sampled island set; later disclosure-safe atoll or island estimates.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Show a synthetic household budget vignette over real published fare legs, marking all income assumptions as fictional.

**Longer-term rollout:** Validate with anonymized HIES and consult on fare equity policy.

## Value and safeguards

**Expected benefit:** Supports equitable subsidy design.

**Limits:** HIES 2019 may be old and too sparse for island estimates.

**Privacy:** Never publish household microdata or small island income cells.

**Dependencies:** HIES access and disclosure controls.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Official statistics and policy fit strongly; uncertain HIES detail constrains demo.

**Feasibility: Medium — public fare sample works but robust burden estimates await data.**  
**Distinctiveness: High — includes transfer and overnight cost.**
