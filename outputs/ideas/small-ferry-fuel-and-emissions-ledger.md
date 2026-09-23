# Small-Ferry Fuel and Emissions Ledger

**Pitch.** Compare route-level fuel intensity and schedule changes for a lower-emission public ferry fleet.

**Type:** Adapted  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Marine fuel use is a major operational cost and emissions source, yet planning needs route-specific measurements.

**Decision supported:** Which route should be piloted for speed optimization, vessel reassignment or propulsion study?

## Precedent and Maldivian equivalent

**Foreign precedent:** The EU’s [EMSA THETIS-MRV](https://emsa.europa.eu/thetis-mrv.html) reports fuel, CO₂, distance and sea time for large vessels; its scale and legal rules do **not** transfer directly to Maldivian speedboats.

**Maldives evidence and confidence:** [MTCC annual reporting](https://mtcc.mv/wp-content/uploads/2024/06/Annual-Report-2023-2.pdf) describes ferry operations and ridership, but public route-level fuel and emissions intensity is **not verified**. Confidence: medium for published operations; low on absence of ledger.

## Prototype interaction

Route map with litres per passenger-km scenarios, uncertainty bands and a speed/capacity slider; highlight routes needing measurement before any ranking.

## Data plan

**Available now / collectable by the team:** [RTL](https://www.rtl.mv/) routes and schedules, [Census](https://statisticsmaldives.gov.mv/census-2022-results-summary/) population; **synthetic** fuel and load inputs, with explicit assumed emission factor and no measured CO₂ claim.

**Future data to collect and method:** Operators log vessel_id, engine type, fuel_type, fuel litres per bunkering or voyage, trip_id, GPS-derived distance, passengers and speed profile; meter or reconciled fuel receipts and verify monthly. Publish aggregated route-month intensities quarterly.

**Geographic coverage:** Pilot — a synthetic two-vessel example; later measured routes for participating operators.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Show a clearly synthetic vessel comparison and sensitivity analysis; include a field sheet for a feasible fuel-and-passenger pilot.

**Longer-term rollout:** Collect a representative seasonal sample before procurement or speed-rule decisions.

## Value and safeguards

**Expected benefit:** Can target fuel savings and climate investments.

**Limits:** Load and sea conditions strongly affect intensity; wrong factors mislead.

**Privacy:** Aggregate operations; no ticket-level detail.

**Dependencies:** Fuel measurement, operators and robust emission factors.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Sustainability and official statistics fit well, but real measurements are not currently verified public.

**Feasibility: Medium-low — analysis hinges on new measurements.**  
**Distinctiveness: High — small-island ferry unit economics and emissions together.**
