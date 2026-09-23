# Weather-Resilient Sailing Windows

**Pitch.** Show which scheduled connections are exposed to official marine alerts and how alternate sailing windows could preserve access.

**Type:** Adapted  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Sea conditions can interrupt travel and cascading transfers. Schedulers, councils and travelers need a planning view of vulnerable service windows.

**Decision supported:** Which departure window or backup route should be prioritized for resilience planning?

## Precedent and Maldivian equivalent

**Foreign precedent:** [BC Ferries current conditions](https://www.bcferries.com/current-conditions) combines route sailing status and notices; its [service-notice update](https://www.bcferries.com/service-notice-changes) documents vessel tracking and condition views.

**Maldives evidence and confidence:** The [Maldives Meteorological Service](https://www.meteorology.gov.mv/forecast) publishes marine forecasts and [alerts](https://meteorology.gov.mv/awareness); [RTL](https://www.rtl.mv/) provides live tracking and schedules. A combined planning view linking alerts to alternative island connectivity is **not verified**. Confidence: high on the inputs; low on gap.

## Prototype interaction

Map a selected alert polygon or atoll range against public routes; a timeline marks departures in the alert period and compares hypothetical retiming options.

## Data plan

**Available now / collectable by the team:** Official [MMS marine forecast](https://www.meteorology.gov.mv/forecast) and [alert definitions](https://meteorology.gov.mv/awareness), [RTL](https://www.rtl.mv/) published schedule sample, island population from [MBS](https://statisticsmaldives.gov.mv/census-2022-results-summary/). Treat alert area as approximate; refresh forecast live and schedules before demo.

**Future data to collect and method:** MMS should publish machine-readable alert_id, geometry, severity, start/end and update time; operators should log trip_id, weather decision, actual status, reason, diversion and alternative capacity via dispatch. Refresh on each alert/sailing.

**Geographic coverage:** Pilot — one alert region and two affected routes; later all public ferry corridors.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Use a historical published alert only if archived and verifiable; otherwise replay a **synthetic alert scenario** over a real timetable, visibly labelled scenario, with no go/no-go advice.

**Longer-term rollout:** Calibrate disruption probabilities against actual cancellations and move to an operator-facing planning dashboard.

## Value and safeguards

**Expected benefit:** Exposes network fragility and improves contingency planning.

**Limits:** Weather alerts are not route-specific sailing safety judgments.

**Privacy:** No personal data needed.

**Dependencies:** Official alert feed, operator status data and safety sign-off.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Combines marine GIS, official data and a highly visual before/after scenario.

**Feasibility: Medium-high — scenario demo works now; predictive claims wait for actuals.**  
**Distinctiveness: High — marine-weather network resilience is central to Maldives.**
