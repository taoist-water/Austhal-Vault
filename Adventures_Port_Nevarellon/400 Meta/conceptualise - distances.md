### Step 1: Anchor a small set of speed benchmarks

Pick real-world-grounded rates once, and reuse them every time you need a new distance. These are standard pre-industrial figures:

|Mode|Sustained pace|Notes|
|---|---|---|
|Foot (traveler/army, decent road)|~15–20 mi/day|Half that or less in mud, snow, or hostile terrain|
|Horseback (multi-day, one rider)|~25–35 mi/day|A single hard day can hit 50–60, but not repeatable|
|Wagon/cart caravan (trade goods)|~12–15 mi/day|Your grain barges from Aerthos would beat this if river-borne|
|Coastal galley, hugging shore|~50–80 mi/day|Anchors at night, avoids open-water risk|
|Open-water sailing, full canvas|~100–150 mi/day|Matches the "2–3 days south-southwest" language in The Inner Sea.md|
|Poled/rowed skiff through marsh|~5–10 mi/day of _straight-line_ progress|Channels wind 2–3x the straight-line distance, which is why Divtown feels close on a map but takes a week to reach|

That last line is the important one for your setting specifically — the Silted Marshes' slowness isn't really about distance, it's about path inefficiency and hazard. That's a good grimdark logistics detail already baked into Silted Marshes.md; keep leaning on "the terrain lies to you" rather than "it's just far away."

### Step 2: Give each hierarchy tier a real-world size anchor

Your five-tier hierarchy (Continent → Region → Political Subdivision → Settlement → District → Building) needs a gut-check scale at each level:

|Tier|Real-world comparison|Crossing time|
|---|---|---|
|Austhal (continent)|Subcontinent-scale, most of it unmapped beyond your corner|Not meaningfully crossable in-fiction yet|
|Region (Whispering Coast, Silted Marshes, Inner Sea)|Small country, e.g. Wales-to-Portugal|Multiple days, minimum|
|Political Subdivision (a Duchy)|Large county or small nation, e.g. Wales/Belgium|2–4 days on foot/horse|
|Settlement (Port Nevarellon, Divtown)|Mid-size port city (pop. 35,000 checks out fine here)|30–60 min end to end on foot|
|District (Muddy Docks, Trade Plazas)|Neighborhood|10–15 min walk|
|Building|—|Immediate|

### Step 3: Draw isochrones, not miles

The most useful visualization tool here isn't a ruler-measured map — it's rings of _equal travel time_ from your hub (Port Nevarellon), where the ring's physical radius changes depending on which mode/terrain you're following out from the city. Here's that applied to what's already canon:

This gives you a repeatable framework, but the fastest way to build the intuition is to see it. Here's the technique applied directly to what's already canon in your vault — Port Nevarellon as hub, with the actual travel times from The Inner Sea.md and Silted Marshes.md plotted as time-distance, not mile-distance:

V

visualize

![218](https://www.google.com/s2/favicons?domain=claudemcpcontent.com&sz=32)

visualize show_widget

The core insight is right there in the shape: the marsh spoke's furthest marked point represents _more_ elapsed time (4–7 days) than the sea spoke's furthest point (2–3 days), but it sits physically closer to the hub. That's not a bug — it's the method working. Terrain speed, not raw mileage, is what should determine where you place things on your map.

**Reverse-engineering rough miles from what's already written**, using the benchmarks above:

- Oakhaven Cove: "2–3 days sailing... under full canvas" (The Inner Sea.md) at open-water pace (~100–150 mi/day) → roughly **200–450 miles** from Port Nevarellon. Wide range, but it tells you Oakhaven belongs on the far edge of your regional map, not just offshore.
- Divtown: "4–7 days by skiff" (Silted Marshes.md) at marsh-channel pace (~5–10 mi/day straight-line, more like 15–25 mi of actual winding path per day) → straight-line distance is probably only **20–70 miles**, even though the path length and time say otherwise. This is worth protecting as a design choice — it means a mounted courier _could_ theoretically reach the edge of the marsh quickly, but nothing can move fast once inside it. That tension is good grimdark material (a threat can be close and still take a week to respond to).