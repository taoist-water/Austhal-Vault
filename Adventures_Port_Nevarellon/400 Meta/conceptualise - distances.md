### Step 1: Anchor a small set of speed benchmarks

> **Units (TheTao, 2026-11-17).** GM-facing measurements are in kilometres. In-world, the coast still says *miles*: it is the people's word, and notes in their voice keep it.

Pick real-world-grounded rates once, and reuse them every time you need a new distance. These are standard pre-industrial figures:

|Mode|Sustained pace|Notes|
|---|---|---|
|Foot (traveler/army, decent road)|~25–30 km/day|Half that or less in mud, snow, or hostile terrain|
|Horseback (multi-day, one rider)|~40–55 km/day|A single hard day can hit 80–95, but not repeatable|
|Wagon/cart caravan (trade goods)|~20–25 km/day|Your grain barges from Aerthos would beat this if river-borne|
|Coastal galley, hugging shore|~80–130 km/day|Anchors at night, avoids open-water risk|
|Open-water sailing, full canvas|~160–240 km/day|Matches the "2–3 days south-southwest" language in The Inner Sea.md|
|Poled/rowed skiff through marsh|~8–16 km/day of _straight-line_ progress|Channels wind 2–3x the straight-line distance, which is why Divtown feels close on a map but takes a week to reach|

That last line is the important one for your setting specifically — the Silted Marshes' slowness isn't really about distance, it's about path inefficiency and hazard. That's a good grimdark logistics detail already baked into Silted Marshes.md; keep leaning on "the terrain lies to you" rather than "it's just far away."

### Step 2: Give each hierarchy tier a real-world size anchor

Your five-tier hierarchy (Continent → Region → Political Subdivision → Settlement → District → Building) needs a gut-check scale at each level:

|Tier|Real-world comparison|Crossing time|
|---|---|---|
|Austhal (continent)|Australia (~7.7 million km²), most of it unmapped beyond your corner|Not meaningfully crossable in-fiction yet|
|Region (Whispering Coast, Silted Marshes, Inner Sea)|Varies. The Whispering Coast is NSW + Victoria (~1 million km²); its settled corner, the Five Duchies, is about England + Wales|Weeks to cross the Whispering Coast; its settled corner in about 8 days|
|Political Subdivision (a Duchy)|Large county or small nation, e.g. Wales/Belgium|2–4 days on foot/horse|
|Settlement (Port Nevarellon, Divtown)|Mid-size port city (pop. 35,000 checks out fine here)|30–60 min end to end on foot|
|District (Muddy Docks, Trade Plazas)|Neighborhood|10–15 min walk|
|Building|—|Immediate|

### Step 3: Draw isochrones, not kilometres

The most useful visualization tool here isn't a ruler-measured map — it's rings of _equal travel time_ from your hub (Port Nevarellon), where the ring's physical radius changes depending on which mode/terrain you're following out from the city. Applied to what's already canon, with Port Nevarellon as the hub and the travel times from The Inner Sea.md and Silted Marshes.md plotted as time, not distance *(the original diagram was not saved)*: the marsh spoke's furthest marked point represents _more_ elapsed time (4–7 days) than the sea spoke's furthest point (2–3 days), but it sits physically closer to the hub. That's not a bug — it's the method working. Terrain speed, not raw mileage, is what should determine where you place things on your map.

**Reverse-engineering rough distances from what's already written**, using the benchmarks above:

- Oakhaven Cove: "2–3 days sailing... under full canvas" (The Inner Sea.md) at open-water pace (~160–240 km/day) → roughly **320–720 km** from Port Nevarellon. Wide range, but it tells you Oakhaven belongs on the far edge of your regional map, not just offshore.
- Divtown: "4–7 days by skiff" (Silted Marshes.md) at marsh-channel pace (~8–16 km/day straight-line, more like 25–40 km of actual winding path per day) → straight-line distance is probably only **30–110 km**, even though the path length and time say otherwise. This is worth protecting as a design choice — it means a mounted courier _could_ theoretically reach the edge of the marsh quickly, but nothing can move fast once inside it. That tension is good grimdark material (a threat can be close and still take a week to respond to).