# Greater Malé Bus Priority Tester

**Pitch.** Test where a short bus-priority measure could save more traveler time than adding another vehicle to congestion.

**Type:** Original

**Research status:** 24 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Bus reliability on dense roads matters even more as bridge links extend the urban travel market. MTCC and road authorities need a way to compare signal priority, a short reserved segment and schedule changes.

**Decision supported:** Which corridor segment or junction should receive a reversible bus-priority trial?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) operates and publishes Greater Malé bus routes. The [transport ministry's mobility terms](https://www.transport.gov.mv/pdf_file/741dcae8-041f-4442-9ee5-79f164737804/TOR-and-Timeline.pdf) request alternatives to road congestion, public-transport improvements and future-link mode options. A public Greater Malé bus-priority decision tool is **not verified**. Confidence: high on bus and planning need; low on product status.

## Prototype interaction

Select a bus route on a map; a segment-by-segment chart shows scheduled versus pilot ride times and estimated person-minutes saved from a signal or short priority lane. A slider changes assumed bus delay reduction and auto-updates the result.

## Data plan

**Available now / collectable by the team:** Public [RTL](https://www.rtl.mv/) stop order/schedule and a small team ride-time sample on one Malé–Hulhumalé or internal bus route: trip time, stop arrival/departure, segment travel time, rough occupancy count and weather. Use one or two days; label the sample and avoid recording passengers. Dated [OpenStreetMap](https://www.openstreetmap.org/) segment geometry.

**Future data to collect and method:** MTCC records anonymized trip_id, stop_id, actual timestamps, segment delay and boardings; road agency records signal phase, bus passage time and other-traffic delay at candidate junctions. Log each trip, aggregate weekly, and repeat before/after a trial.

## Demo and rollout

**Datathon demo:** Show observed short-run segment times and a clearly labelled **hypothetical** 10–20% delay-reduction scenario; display both bus passenger benefit and possible general-traffic cost rather than promise net savings.

**Longer-term rollout:** Trial one reversible treatment with operator and police sign-off; evaluate observed person-minutes and safety after several weeks.

## Value and safeguards

**Expected benefit:** Moves road-space decisions toward person throughput.

**Limits:** Small ride samples and assumed treatment effects are uncertain.

**Privacy:** No passenger images, names, tap IDs or GPS traces of individuals.

**Dependencies:** Operator cooperation, street-design approval and repeat counts.

## Datathon fit and ratings

The [2026 criteria](https://www.datathon.stats.gov.mv/faq) value data use, technical execution, impact and clarity. One route with a selectable treatment yields a focused seven-minute policy demo.

**Feasibility: High — public schedules and a small ride-time sample are practical.**

**Distinctiveness: High — compares scarce street space by people moved through a changing bridge network.**
