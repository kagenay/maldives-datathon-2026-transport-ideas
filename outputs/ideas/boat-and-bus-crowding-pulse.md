# Boat and Bus Crowding Pulse

**Pitch.** Show where crowding occurs by departure and whether shifting frequency or capacity would reduce it.

**Type:** Adapted  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

Annual ridership totals obscure peak crowding at terminals and bus stops. MTCC and planners need load profiles.

**Decision supported:** Which departure should receive more capacity or a retimed feeder bus?

## Precedent and Maldivian equivalent

**Foreign precedent:** Singapore [LTA DataMall bus-arrival API](https://datamall.lta.gov.sg/content/dam/datamall/datasets/LTA_DataMall_API_User_Guide.pdf?ref=public_apis) reports estimated current load with arrivals, illustrating structured crowding information.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) already has route/live tracking; [MTCC](https://mtcc.mv/wp-content/uploads/2024/06/Annual-Report-2023-2.pdf) reports aggregate commutes. Public departure-level load data are **not verified**. Confidence: high for existing service, low for data absence.

## Prototype interaction

Time-of-day heatmap of boardings versus seats for a selected route, with a capacity and departure-shift slider plus terminal queue map.

## Data plan

**Available now / collectable by the team:** [RTL](https://www.rtl.mv/) timetables and publicly stated vessel/bus capacity only where verifiable; otherwise a **synthetic** load matrix. [MTCC](https://mtcc.mv/wp-content/uploads/2024/06/Annual-Report-2023-2.pdf) annual totals may provide context but cannot validate departure loads.

**Future data to collect and method:** Operator counts from anonymous ticket scans or manual counters: trip_id, stop_id, timestamp, boardings, alightings, capacity, denied boardings and queue estimate; aggregate to trip level daily. No ticket or payment IDs in published feed.

**Geographic coverage:** Pilot — a synthetic two-route week; later all participating ferry and bus services.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Show the dashboard on a prominently synthetic two-route week and demonstrate the data form for a possible short manual-count pilot.

**Longer-term rollout:** Pilot anonymous counting, compare with ticket totals, then integrate into planning and possibly passenger information.

## Value and safeguards

**Expected benefit:** Can reduce waiting and target capacity.

**Limits:** Synthetic loads must not be represented as observed demand.

**Privacy:** Only counts, no passenger identities or journeys.

**Dependencies:** Operator participation and consistent capacity definitions.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Strong technical dashboard and direct service decision; real load evidence is future work.

**Feasibility: Medium — demo feasible, meaningful estimates require collection.**  
**Distinctiveness: Medium — crowding products exist abroad; multi-modal island application adds value.**
