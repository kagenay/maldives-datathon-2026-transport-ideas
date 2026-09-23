# Greater Malé Bus Crowding Pulse

**Pitch.** Measure where bus-stop queues and full vehicles make scheduled Greater Malé service less useful than it appears on a route map.

**Type:** Adapted

**Research status:** 24 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Road-connected Malé, Hulhulé and Hulhumalé need usable buses, and the planned western bridge could add new demand. MTCC and city planners need stop-level crowding evidence to adjust service.

**Decision supported:** Which Greater Malé bus stop and time window should receive an extra departure, larger vehicle or queue-management change?

## Precedent and Maldivian equivalent

**Foreign precedent:** Singapore's [LTA DataMall bus-arrival API](https://datamall.lta.gov.sg/content/dam/datamall/datasets/LTA_DataMall_API_User_Guide.pdf?ref=public_apis) includes estimated current vehicle load; the adaptation emphasizes planning counts and denied boarding.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) publishes bus routes, schedules and live tracking, and [MTCC's annual report](https://mtcc.mv/wp-content/uploads/2024/06/Annual-Report-2023-2.pdf) reports Greater Malé bus trips. A public stop-and-departure crowding dataset is **not verified**. Confidence: high on existing bus service; low on product status.

## Prototype interaction

Map stops by observed queue length and waiting time, linked to a time-of-day chart; move one bus departure and see a clearly modeled queue change. Show sample size beside every observation.

## Data plan

**Available now / collectable by the team:** Public [RTL](https://www.rtl.mv/) route/stop/schedule information; a team manual pilot at two publicly accessible stops recording stop_id, 15-minute window, arrivals, approximate queue, boardings and passengers left behind if safely observable. Pilot: Malé and Hulhumalé; one-day snapshot, schedules rechecked before demo.

**Future data to collect and method:** Operator counts by trip_id, stop_id, arrival time, boardings, alightings, vehicle capacity and denied boarding, using anonymous tap totals or manual counters; release stop-hour aggregates weekly. Repeat baseline counts before and after any bridge-route change.

## Demo and rollout

**Datathon demo:** Show the two real pilot stops and one hypothetical extra-bus scenario. If counting cannot be done, use a prominent **synthetic data** label for the queue chart; never equate annual ridership with stop load.

**Longer-term rollout:** Expand across Greater Malé and validate manual counts against operator totals before automating frequency recommendations.

## Value and safeguards

**Expected benefit:** Targets bus capacity where it reduces waiting most.

**Limits:** A short count cannot represent normal weekly demand or future bridge trips.

**Privacy:** Count people, not identities, images or payment records.

**Dependencies:** Safe observation locations, operator service calendar and consistent capacity definitions.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize data collection, GIS and decision support. A stop map plus one frequency change gives a concise seven-minute story.

**Feasibility: High — a small real bus-stop pilot is possible with public-side observations.**

**Distinctiveness: Medium-high — applies structured crowding evidence to Greater Malé bus operations and bridge transition.**
