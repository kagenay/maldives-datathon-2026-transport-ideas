# Rain-Flood Walking Detour Atlas

**Pitch.** Show how localized flooding changes safe walking access to ferry terminals, clinics and bus stops.

**Type:** Original  
**Research status:** 23 September 2026; concept document. Comparable Maldivian implementation status is assessed below.

## Problem, users and decision

A flooded low point can create a long detour even where straight-line access is short. Councils need a maintenance and drainage priority map.

**Decision supported:** Which drainage or raised-crossing intervention most restores access during heavy rain?

## Precedent and Maldivian equivalent

**Foreign precedent:** Original Maldives proposal; no foreign implementation claimed.

**Maldives evidence and confidence:** [MMS](https://meteorology.gov.mv/awareness) publishes heavy-rain alerts and [NDMA](https://ndma.gov.mv/en) reports disaster impacts. A public walking-network flood-detour tool is **not verified**. Confidence: high on hazard services; low on gap.

## Prototype interaction

Street network map with reported passable/blocked segments; toggle one flooded segment to see destination catchment and walking time change.

## Data plan

**Available now / collectable by the team:** [OpenStreetMap](https://www.openstreetmap.org/) paths, [MMS alert categories](https://meteorology.gov.mv/awareness) and a small opt-in, timestamped field audit of puddle depth/passability after rain if safe. If no event occurs, all flood locations are **synthetic**.

**Future data to collect and method:** Council crews record segment_id, start/end, depth band, passability, photo without people, time and drainage asset_id via mobile form after qualifying rain; sensor or crowdsourced reports require verification. Update per event.

**Geographic coverage:** Pilot — one Greater Malé walking corridor; later flood-prone urban islands.

**Update frequency:** Census 2022 is a fixed release; where used, take a dated [OpenStreetMap](https://www.openstreetmap.org/) snapshot. Recheck any public timetable, fare or alert immediately before presentation. Team observations are one-off pilot snapshots. The future collection cadence is specified above; no live feed is assumed for the demo.

Where a future input is required, any generated values in the datathon view must be marked **synthetic scenario data**, visually separated from observed/public data. The [official FAQ](https://www.datathon.stats.gov.mv/faq) allows public or newly gathered credited data, says MBS will provide Census 2022/HIES 2019 to participants, and also prohibits private/nonpublic sources; confirm the scope and terms of event-provided files before using them.

## Demo and rollout

**Datathon demo:** Use a visibly synthetic flood overlay unless safely observed data exist; one click reveals detour and affected census population.

**Longer-term rollout:** Validate against repeated storms and link to drainage maintenance tickets.

## Value and safeguards

**Expected benefit:** Protects everyday walking access.

**Limits:** Highly local, fast-changing conditions; do not issue safety routing from unverified reports.

**Privacy:** Avoid geolocated reporter identity and private-property photos.

**Dependencies:** Field validation and safe observation.

## Datathon fit and ratings

The [2026 theme and criteria](https://www.datathon.stats.gov.mv/faq) emphasize transport data systems, GIS, decision-making, relevance, data use, innovation, technical execution, clarity, impact and teamwork. **Fit:** Climate resilience, GIS and practical maintenance priority.

**Feasibility: Medium-high with synthetic scenario; real hazard sample uncertain.**  
**Distinctiveness: High — microflooding is analyzed as lost mobility.**
