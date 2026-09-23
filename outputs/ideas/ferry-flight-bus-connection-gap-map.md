# Ferry–Flight–Bus Connection Gap Map

**Pitch.** Put domestic air, RTL ferries and buses on one map to reveal where a traveler must wait overnight or cannot make a feasible transfer.

**Type:** Adapted

**Research status:** 24 September 2026; concept document. The three modes have public-facing information, but an openly licensed machine-readable feed for all three is **not verified**.

## Problem, users and decision

Travel from many islands combines a local ferry, a domestic flight and a Greater Malé bus/airport leg. A map of route lines alone does not show whether the schedules connect. Atoll transport planners, airlines, MTCC and health planners need transfer-gap evidence.

**Decision supported:** Which one ferry, flight or bus time shift would let the most islands reach an airport, higher-level hospital or Malé on the same day?

## Precedent and Maldivian equivalent

**Foreign precedent:** Finland's [Digitransit](https://portal-api.digitransit.fi/) combines open transit data in a journey-planning platform; [Transport for NSW](https://opendata.transport.nsw.gov.au/developers/documentation) publishes standard bus and ferry feeds. The Maldivian adaptation adds domestic flights and emphasizes a planning-gap dashboard rather than another consumer trip planner.

**Maldives evidence and confidence:** [RTL](https://www.rtl.mv/) already shows ferry and bus routes, schedules and tracking. [Maldivian's annual report](https://maldivian.aero/assets/files/Annual%20Report%202024.pdf) maps domestic airports, and [Velana's flight board](https://velana.macl.aero/) displays flights. A combined public planning tool is **not verified**. Confidence: high that mode information is displayed; low that reusable feeds or a comparable tool exist. [MACL's terms](https://macl.aero/terms-of-service) claim rights over flight schedule feeds and restrict automated scraping, so a visible flight board must not be treated as an open dataset.

## Prototype interaction

Map one origin island to Velana and a Greater Malé destination; show ferry, flight, walking and bus legs on a time line, with check-in and transfer margins. Toggle a five- or ten-minute timetable shift and highlight newly feasible same-day journeys. Each layer carries a provenance and licensing badge.

## Data plan

**Available now / collectable by the team:** [Census 2022](https://statisticsmaldives.gov.mv/census-2022-results-summary/) island population; [OpenStreetMap](https://www.openstreetmap.org/) island, airport and street geometry; public [RTL](https://www.rtl.mv/) route/stop information subject to reuse check; [Maldivian's published network](https://maldivian.aero/assets/files/Annual%20Report%202024.pdf) for route existence. For the demo, use only facts with permitted reuse, and mark unlicensed flight times, seat availability and transfer behavior **synthetic**. Pilot: Velana, one nearby bus link and one atoll-to-airport path. Census/network snapshot fixed; verify route status before presentation.

**Future data to collect and method:** Airlines, airport operators and MTCC would publish licensed feed fields mode, operator, route_id, trip/flight_id, stop/airport_id, service day, scheduled/actual arrival/departure, cancellation and transfer minimum. Operators generate versioned schedules daily and actual updates per trip; MBS or a designated steward checks identifiers, permissions and data quality. Publish only aggregate connection metrics if operational feeds cannot be open.

## Demo and rollout

**Datathon demo:** Show a real mode/airport geography layer and a highly visible **synthetic timetable exercise** for one ferry–flight–bus chain. The audience sees how a small timing change alters reachable population, but hears no claim that the shown flight is a real bookable service.

**Longer-term rollout:** Seek explicit data-sharing/open-feed permission, build common stop/airport identifiers, validate transfer rules and expand to atolls and alternate domestic airlines.

## Value and safeguards

**Expected benefit:** Reveals coordination opportunities and gaps hidden by separate mode sites.

**Limits:** An attractive map is not a planning result unless connection feasibility and population exposure are calculated; flight schedules and seats change.

**Privacy:** Use public schedules and aggregate census data, not bookings or passenger itineraries.

**Dependencies:** Rights-cleared timetable feeds, airline/MTCC partnership and verified minimum connection times.

## Datathon fit and ratings

The [FAQ](https://www.datathon.stats.gov.mv/faq) seeks better transport-data integration, GIS and resource-allocation decisions; this directly answers that brief. Its seven-minute story is one missed connection and one timed fix.

**Feasibility: Medium — route geography is public, but live or reusable flight timetables are not verified as permitted.**

**Distinctiveness: High — a national ferry–flight–bus transfer analysis complements existing separate service displays.**
