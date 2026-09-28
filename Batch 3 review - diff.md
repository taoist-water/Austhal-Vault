# Batch 3 — Aqueduct follow-through + link repair (review diff)

**Nothing has been written to the vault.** Parts A, B and C can each be approved separately.

**Judgement calls to check**
- **Whispering Coast hierarchy:** `Austhal.md` now lists the Five Duchies *inside* the Whispering Coast, not as a sibling region. Both the tracker and Three Layers recommended this.
- **Links deliberately left unresolved:** these point to notes you haven't written yet, and Obsidian treats them as "wanted" notes: The Twelgorn Kingdom (9 references), The Tidespoken Clergy (6), the De Vonce children, Oakhaven Cove, Shield Atolls, Broken Spires, Captain Vesper Locke, Low-Tide Market, Slipway Seven, Brine-Glow Depot and the Rusty Anchor Foundry. They go into the tracker's gap list in Batch 4.
- **Tidespoken Clergy path:** five notes link to `100 Society/The Tidespoken Clergy`. If you create that note, put it at that path, or at the same name in `101 Factions & Guilds` (Obsidian will still resolve it).

**For you in Obsidian (optional):** rename `The Kald Mountain  Territory.md` to remove the double space. Obsidian will update its two links.

**Also noticed:** the two review files `Batch 1 review - diff.md` and `Batch 2 review - diff.md` are now inside your vault folder. They contain the old names, and their links will show up in Obsidian's graph and search. I'd move them outside `Adventures_Port_Nevarellon`.

---

## Part A — Spine Aqueduct follow-through (4 files)

The one piece of new prose is Tythius's paragraph, built from the three-part reasoning already in Three Layers.

### `000 Atlas/001 Regions & Continents/The Five Duchies of the Whispering Coast.md`

```diff
@@ -21,3 +21,3 @@
 - **Terrain & Seat:** Rolling hills, heavily fortified stone keeps, and dense oak forests leading up to the foothills of the Spine. The ducal seat is **[[Castle Iron-Spire|Castle Iron-Spire]]**, built directly into those foothills.
-- **Logistics & Economy:** The martial heart of the coast. They control the primary iron mines and timber mills that supply the shipyards of Port Nevarellon. 
+- **Logistics & Economy:** The martial heart of the coast. They control the primary iron mines and timber mills that supply the shipyards of Port Nevarellon. They also hold the headwater of the **Spine Aqueduct** — the city's only piped fresh water — in the western foothills: a leverage no Duke has ever used, and every Council has noticed. 
 - **Realism Anchor:** They maintain the largest standing feudal levy. They are culturally rigid, hyper-militaristic, and deeply bitter that they must rely on the foreign mercenaries of **The Golden Company** to protect the central port rather than their own knights.
```

### `000 Atlas/002 Cities & Settlements/Port Nevarellon.md`

```diff
@@ -14,3 +14,3 @@
 To maintain a realistic setting, Port Nevarellon’s design is governed by its environment:
-- **Fresh Water:** The city does *not* have a freshwater river. The River Aer reaches the harbour through a broad tidal estuary, and every flood tide pushes salt miles upstream; the water at the city's edge is brackish and undrinkable. The grain barges from Millhaven ride the ebb in. The city relies entirely on massive stone cisterns located beneath the High Quarter that collect rainwater, and a single aqueduct pipe running from the foothills of [[The Jagged Spine]]. Water is a heavily taxed commodity.
+- **Fresh Water:** The city does *not* have a freshwater river. The River Aer reaches the harbour through a broad tidal estuary, and every flood tide pushes salt miles upstream; the water at the city's edge is brackish and undrinkable. The grain barges from Millhaven ride the ebb in. The city relies entirely on massive stone cisterns located beneath the High Quarter that collect rainwater, and a single aqueduct — the **Spine Aqueduct**, known in the Docks as *the Duke's Straw* — running from a spring-fed catchment in the western foothills of [[The Jagged Spine]], inside the Duchy of De Vonce. Water is a heavily taxed commodity.
 - **Sanitation:** The Lower Districts have no sewage system; waste drains directly into the harbor via open stone gutters, leading to severe stagnation during low tides. The High Quarter uses a subterranean flush-vault system that vents out past the eastern cliffs.
```

### `200 Cast/201 Nobility & Elites/Tythius De Vonce.md`

```diff
@@ -28,2 +28,4 @@
 
+**The Duke's Straw.** The [[Framework - The Three Layers#💧 CANON ADDITION: The Spine Aqueduct|Spine Aqueduct]] that waters Port Nevarellon rises in De Vonce's western foothills and runs south through his farmland to the cisterns beneath the High Quarter. It was built when the coast was one kingdom and the pipe crossed no border, and the Accord never addressed it. Tythius has never touched it, and his reasons are over-determined: the Accord is the only thing standing between his house and a second civil war he personally fought; thirty-five thousand dead of thirst is a line he will not cross; and the Council's maritime taxes fund his border keeps, so choking the city would empty his own garrison purse within a season. Nobody can say which of the three reasons is load-bearing — including Tythius.
+
 ## 🔗 Connected Notes
```

### `400 Meta/Framework - The Three Layers.md`

```diff
@@ -163,5 +163,5 @@
 
-### Propagation required (not yet applied)
+### Propagation — applied 2026-09-28
 
-These four files need updating to carry the addition. Flagging rather than editing, since three are `status/solid`:
+Applied to files 1–3 below. The canon-tracker row (4) follows in the tracker rebuild.
 
```

## Part B — Link repoints and resolved notes (24 files)

Mechanical. Each broken link now points to a note that exists; links that were resolving but sent readers to Religion instead of the Zenith are corrected. Three Layers' open questions that are now settled are struck through, not deleted.

### `000 Atlas/001 Regions & Continents/Austhal.md`

```diff
@@ -5,3 +5,3 @@
 -**The Main Known Continent**
- - **regions within:** [[The Five Duchies of the Whispering Coast]] ,[[Whispering Coast]], [[Silted Marshes]], [[000 Atlas/The Twelgorn Kingdom| The Kingdom of Twelgorn]], [[Wastelands| The Wastelands]], [[The Inner Sea| Inner sea]],
+ - **regions within:** [[Whispering Coast]] (including [[The Five Duchies of the Whispering Coast|the Five Duchies]]), [[Silted Marshes]], [[000 Atlas/The Twelgorn Kingdom| The Kingdom of Twelgorn]], [[Wastelands| The Wastelands]], [[The Inner Sea| Inner sea]],
 - **Bordering Areas:** [[Link Region/City A]], [[Link Region B]]
```

### `000 Atlas/001 Regions & Continents/Silted Marshes.md`

```diff
@@ -20,3 +20,3 @@
   - [[Divtown|Divtown]] — *Smuggler's Shanty Town / Logging Outpost.* A derelict refuge built on stilts, populated by escaped slaves and the truly hopeless.
-  - [[000 Atlas/Grey Water Lagoon|Grey Water Lagoon]] — *Deep-Water Anchorage.* A hidden, unusually stable basin of deep water where pirate galleons drop anchor to fence stolen goods through Divtown.
+  - [[Greywater Lagoon|Grey Water Lagoon]] — *Deep-Water Anchorage.* A hidden, unusually stable basin of deep water where pirate galleons drop anchor to fence stolen goods through Divtown.
   - **The Sunken Causeway:** *Ruined Point of Interest.* The submerged, shattered remains of an ancient stone highway built by the old kings, now completely swallowed by the mud and serving only as a hazard that rips the hulls of unwary boats.
```

### `000 Atlas/001 Regions & Continents/The Five Duchies of the Whispering Coast.md`

```diff
@@ -38,3 +38,3 @@
 ## 4. Duchy of Stonereach (The High Shields)
-- **Terrain & Seat:** Treacherous mountain passes and sheer granite peaks along the north-eastern edge, bordering [[000 Atlas/The Ubaraz Kingdom|The Ubaraz Kingdom]]. The ducal seat is **Granite Spire**, a dwarven-engineered citadel cut directly into the passes.
+- **Terrain & Seat:** Treacherous mountain passes and sheer granite peaks along the north-eastern edge, bordering [[Ubaraz Kingdom|The Ubaraz Kingdom]]. The ducal seat is **Granite Spire**, a dwarven-engineered citadel cut directly into the passes.
 - **Logistics & Economy:** Granite quarrying, heavy masonry, and toll-keep control over the mountain trade roads.
```

### `000 Atlas/001 Regions & Continents/Whispering Coast.md`

```diff
@@ -4,3 +4,3 @@
 ## 🗺️ Geography & Scope
-- **Bordering Areas:** [[draft_Silted Marshes| Silted Marshes]], [[Ubaraz Kingdom]], [[The Kald Mountain  Territory| Kald Mountain Territory]], [[The Inner Sea]]
+- **Bordering Areas:** [[Silted Marshes| Silted Marshes]], [[Ubaraz Kingdom]], [[The Kald Mountain  Territory| Kald Mountain Territory]], [[The Inner Sea]]
 - **Terrain Type:** (e.g., Jagged cliffs, salt marshes, dense pine valleys)
@@ -17,3 +17,3 @@
   - [[Port Nevarellon]]- Free City Metropolis
-  - [[400 Meta/drafts/draft2_The Five Duchies of the Whispering Coast]]
+  - [[The Five Duchies of the Whispering Coast]]
   - 
```

### `000 Atlas/002 Cities & Settlements/Divtown.md`

```diff
@@ -10,3 +10,3 @@
 - **Primary Export:** Rot-resistant marsh timber, and "legitimately salvaged" pirate cargo.
-- **Regional Location:** [[000 Atlas/The Silted Marshes|The Silted Marshes]]
+- **Regional Location:** [[Silted Marshes|The Silted Marshes]]
 
@@ -15,3 +15,3 @@
 - **Access & Navigation:** Divtown is incredibly difficult to reach by land or sea. The labyrinthine waterways are choked with constantly shifting sandbars. To reach the town, one must hire local fisher-folk from the mouth of the marsh, or seek out a specific, cursed dwarven guide working out of **Fenmouth**, the marsh-mouth village where hiring a guide is required by law.
-- **Neighboring Locations:** Directly borders the [[000 Atlas/Grey Water Lagoon|Grey Water Lagoon]], a deep-water blind spot hidden from the Golden Company where pirate galleons drop anchor.
+- **Neighboring Locations:** Directly borders the [[Greywater Lagoon|Grey Water Lagoon]], a deep-water blind spot hidden from the Golden Company where pirate galleons drop anchor.
 
```

### `000 Atlas/003 Sub-Locations & Architecture/The Muddy Docks.md`

```diff
@@ -12,3 +12,3 @@
 ## ⚖️ Law, Order & Safety
-- **Guarding Presence:** The official [[100 Society/The City Watch|Blue-Cloak Watch]] refuses to patrol here after dusk, maintaining only a single, heavily fortified guard-post at the district's landward gate. 
+- **Guarding Presence:** The official [[Faction - The Civic Constabulary (The Coppers)|Blue-Cloak Watch]] refuses to patrol here after dusk, maintaining only a single, heavily fortified guard-post at the district's landward gate. 
 - **Local Customs / Unwritten Rules:** Weapons must be kept bound or sheathed while on the main thoroughfares, but fighting with fists or rigging knives is largely ignored. To wear fine silks or flashy jewelry here is viewed as an invitation to be tossed into the mud and stripped.
```

### `000 Atlas/003 Sub-Locations & Architecture/The Rusty Tankard.md`

```diff
@@ -10,3 +10,3 @@
 - **District / Region:** [[000 Atlas/The Great Anchor Basin|The Great Anchor Basin]], Port Nevarellon.
-- **Owner / Proprietor:** Officially registered under a shell name held by a minor Landed clerk; practically operated by [[200 Cast/Kaleb the Barkeep|Kaleb]].
+- **Owner / Proprietor:** Officially registered under a shell name held by a minor Landed clerk; practically operated by [[Kaleb|Kaleb]].
 - **Affiliation:** [[100 Society/The Cobalt Feather Syndicate|The Cobalt Feather Syndicate]] (Front / Safehouse).
@@ -33,3 +33,3 @@
 
-- **[[200 Cast/Kaleb the Barkeep|Kaleb]]:** The manager and gatekeeper. She operates the dead-drops and assigns odd jobs to trusted syndicate freelancers.
+- **[[Kaleb|Kaleb]]:** The manager and gatekeeper. She operates the dead-drops and assigns odd jobs to trusted syndicate freelancers.
 - **[[200 Cast/Maccorrack|Maccorrack]]:** A massive half-orc stevedore who practically lives here. Beyond drinking and working as occasional hired muscle for Kaleb's smuggling runs, Maccorrack fights in the Tankard's regular, brutal bare-knuckle bar brawls for extra coin. Kaleb actually encourages these brawls—the noise and spilled blood convince the Company patrols that the Tankard is just a standard low-class dive, drawing attention away from the quiet, high-stakes smuggling in the cellar.
```

### `000 Atlas/003 Sub-Locations & Architecture/The Sunken Ward.md`

```diff
@@ -12,3 +12,3 @@
 - **Social Stratum:** Squalid/Slums — the city's most impoverished and least-documented population, overwhelmingly Un-Landed.
-- **Architecture & Infrastructure:** Two distinct zones stitched together by shared poverty rather than shared architecture: the waterfront sprawl of stilt-housing and boardwalks that make up [[The Muddy Docks|The Muddy Docks]], and the older, inland tenement blocks — collectively known as **Cinder Row** — thrown up in a hurry fifty years ago to absorb the flood of refugees fleeing the [[400 Meta/drafts/draft2_The Five Duchies of the Whispering Coast#5. 💀 The Scarred Land: Duchy of Corvus (The Fallen Crown)|Corvus Scar]].
+- **Architecture & Infrastructure:** Two distinct zones stitched together by shared poverty rather than shared architecture: the waterfront sprawl of stilt-housing and boardwalks that make up [[The Muddy Docks|The Muddy Docks]], and the older, inland tenement blocks — collectively known as **Cinder Row** — thrown up in a hurry fifty years ago to absorb the flood of refugees fleeing the [[The Five Duchies of the Whispering Coast#5. 💀 The Scarred Land: Duchy of Corvus (The Fallen Crown)|Corvus Scar]].
 
@@ -17,3 +17,3 @@
 ## ⚖️ Law, Order & Safety
-- **Guarding Presence:** The [[100 Society/The City Watch|Blue-Cloak Watch]] treats the Ward the way it treats the Docks — a single fortified checkpoint at the landward gate, no patrols after dark. Cinder Row fares worse: it generates no trade revenue, so unlike the Docks it doesn't even benefit from the [[The Iron-Anchor Syndicate|Iron-Anchor Syndicate]]'s self-interested version of order.
+- **Guarding Presence:** The [[Faction - The Civic Constabulary (The Coppers)|Blue-Cloak Watch]] treats the Ward the way it treats the Docks — a single fortified checkpoint at the landward gate, no patrols after dark. Cinder Row fares worse: it generates no trade revenue, so unlike the Docks it doesn't even benefit from the [[The Iron-Anchor Syndicate|Iron-Anchor Syndicate]]'s self-interested version of order.
 - **Local Customs / Unwritten Rules:** Newcomers are assumed to be either Corvus-descended or recently ruined. Nobody asks which, and nobody expects a straight answer.
```

### `100 Society/101 Factions & Guilds/The Cobalt Feather Syndicate.md`

```diff
@@ -26,3 +26,3 @@
 - The Syndicate relies entirely on bribery, perfect forgeries, and crippling blackmail. 
-- When muscle is required (usually when dealing with pirates in the [[000 Atlas/The Silted Marshes|Silted Marshes]]), it is used strictly for intimidation or defense, never for assassination.
+- When muscle is required (usually when dealing with pirates in the [[Silted Marshes|Silted Marshes]]), it is used strictly for intimidation or defense, never for assassination.
 ---
```

### `100 Society/101 Factions & Guilds/The Golden Company.md`

```diff
@@ -78,3 +78,3 @@
 - **Contract Before Cause:** The Company's ethos is transactional, not ideological. It doesn't care about street-level crime in the docks; it cares about tax revenue, harbor defense, and making sure the Contract is paid on time. This is a professional army administering a business arrangement, not a crusading order — which is exactly why it can be *fooled* by a good forgery rather than only fought.
-- **Unwitting Tool of the Cobalt Feather:** The Company's greatest quiet vulnerability isn't force, it's paperwork. [[The Cobalt Syndicate|The Cobalt Feather Syndicate]] forges manifests convincing enough that Golden Company guards personally escort smuggled cargo out of the Basin, believing it belongs to the Council itself — dramatic irony the Company has no idea it's living inside.
+- **Unwitting Tool of the Cobalt Feather:** The Company's greatest quiet vulnerability isn't force, it's paperwork. [[The Cobalt Feather Syndicate|The Cobalt Feather Syndicate]] forges manifests convincing enough that Golden Company guards personally escort smuggled cargo out of the Basin, believing it belongs to the Council itself — dramatic irony the Company has no idea it's living inside.
 - **Contempt for the Coppers:** Officers routinely override Constabulary arrests and treat Blue-Cloak watchmen as undisciplined amateurs, a resentment the Coppers return in full (see [[Faction - The Civic Constabulary (The Coppers)]]).
```

### `100 Society/101 Factions & Guilds/The Iron-Anchor Syndicate.md`

```diff
@@ -17,3 +17,3 @@
 - **Expenses & Upkeep:**
-  - Massive monthly bribes to high-ranking captains of [[100 Society/The City Watch|The Blue-Cloak Watch]] to look the other way.
+  - Massive monthly bribes to high-ranking captains of [[Faction - The Civic Constabulary (The Coppers)|The Blue-Cloak Watch]] to look the other way.
   - Wages for roughly 300 "Enforcers" (grizzled sailors, thuggish dock hands, and crossbowmen).
```

### `100 Society/101 Factions & Guilds/The Wyvern tail Pirates.md`

```diff
@@ -10,3 +10,3 @@
 - **Leadership:** [[200 Cast/Captain Haren Twarde|Captain Haren Twarde]].
-- **Base of Operations:** The Outer Reach of the [[000 Atlas/Grey Water Lagoon|Grey Water Lagoon]], anchored alongside the floating pontoons of [[000 Atlas/Divtown|Divtown]].
+- **Base of Operations:** The Outer Reach of the [[Greywater Lagoon|Grey Water Lagoon]], anchored alongside the floating pontoons of [[000 Atlas/Divtown|Divtown]].
 - **Primary Focus:** Intercepting royal treasure galleons sailing north from the [[000 Atlas/The Twelgorn Kingdom|Twelgorn Kingdom]], raiding high-value merchant convoys, and monopolizing the illicit arms trade across the Inner Sea.
@@ -19,3 +19,3 @@
 
-- **Shallow-Draft Tacticians:** Haren’s crews utilize heavy, deep-sea warships that have been heavily modified by [[000 Atlas/Divtown|Divtown]] shipwrights. By stripping away heavy iron hull-plating and replacing it with lightweight, rot-resistant **Iron-Burl** timber, her ships sit incredibly high in the water. This allows them to lure the deep-draft, iron-clad warships of the Twelgorn navy into the shifting sandbars of [[000 Atlas/The Silted Marshes|The Silted Marshes]], where the heavier vessels run aground and become defenseless targets.
+- **Shallow-Draft Tacticians:** Haren’s crews utilize heavy, deep-sea warships that have been heavily modified by [[000 Atlas/Divtown|Divtown]] shipwrights. By stripping away heavy iron hull-plating and replacing it with lightweight, rot-resistant **Iron-Burl** timber, her ships sit incredibly high in the water. This allows them to lure the deep-draft, iron-clad warships of the Twelgorn navy into the shifting sandbars of [[Silted Marshes|The Silted Marshes]], where the heavier vessels run aground and become defenseless targets.
 - **The Economic Alliance:** The fleet maintains a strict, symbiotic relationship with [[200 Cast/Lord Kelf Thorne|Lord Kelf Thorne]]. They unload massive hauls of plundered Twelgorn silks, spices, and bullion into the lagoon. Once Thorne washes the cargo using his noble wax seals, Haren's agents receive clean **Silver Pieces** and high-grade provisions, completely bypassing the taxes of Port Nevarellon.
```

### `100 Society/104 Cosmology/Cosmology - The Celestial Graveyard and The war of Creation.md`

```diff
@@ -48,2 +48,2 @@
 ### 3. The Ruins of the War
-Because the disk is so vast and the war was fought everywhere before the shattering, if one digs deep enough into the rock beneath Port Nevarellon or explores the wilderness of [[The Whispering Coast]], they won't find traditional dinosaur fossils. They will find the titanic, petrified bones of the manufactured war-beings and fallen gods from the Pre-Sundering War, often still bleeding raw, unanchored magical energy into the stone — mute evidence of a war whose actual causes nobody alive remembers, only the story mortals chose to tell about it afterward.
+Because the disk is so vast and the war was fought everywhere before the shattering, if one digs deep enough into the rock beneath Port Nevarellon or explores the wilderness of [[Whispering Coast|the Whispering Coast]], they won't find traditional dinosaur fossils. They will find the titanic, petrified bones of the manufactured war-beings and fallen gods from the Pre-Sundering War, often still bleeding raw, unanchored magical energy into the stone — mute evidence of a war whose actual causes nobody alive remembers, only the story mortals chose to tell about it afterward.
```

### `200 Cast/201 Nobility & Elites/Alfric Danniken.md`

```diff
@@ -22,2 +22,2 @@
 ## 🔗 Connected Notes
-- **Key Underworld Asset:** [[200 Cast/Kaleb the Barkeep|Kaleb]] (Maintains the urban dead-drops).
+- **Key Underworld Asset:** [[Kaleb|Kaleb]] (Maintains the urban dead-drops).
```

### `200 Cast/201 Nobility & Elites/Lucia Marrenhal.md`

```diff
@@ -33,2 +33,2 @@
 - **Rivals / Creditors:** [[Ottavian Kress]] (blocks her on the Unwritten Day every time, on principle and for profit), [[Marcian Thole]] (she holds his mortgage and has never called it; she has not decided whether that is leverage or something she would rather not examine)
-- **Key Notes:** [[Council of Five]], [[Law - The Council's Edicts]], [[Framework - The Coastal Reckoning]], [[Religion - The pagan Pantheon and the Faith Domains]] (the Court of Nullity)
+- **Key Notes:** [[Council of Five]], [[Law - The Council's Edicts]], [[Framework - The Coastal Reckoning]], [[The Cult of the Zenith]] (the Court of Nullity)
```

### `200 Cast/201 Nobility & Elites/Palla Vantry.md`

```diff
@@ -20,3 +20,3 @@
 - **Immediate Goal:** Nothing urgent, and this is not a failure of the character — it is the character. Her working horizon is the **Contract expiry in 41 years**, which she fully expects to attend
-- **The Core Fear:** Being named. Not exposed — *named*. The Ducal Accord's ultimate law forbids any mortal claiming the moniker of King, and Palla Vantry has held one-fifth of a sovereign city's government for fifty-eight years by continuous free election. She has claimed nothing. She has never needed to. She is acutely aware that the [[Religion - The pagan Pantheon and the Faith Domains|Cult of the Zenith]] could void her seat for irregularity and could never validate it either, and that the day someone puts the word to what she is, the Court of Nullity becomes the only venue in the world and it has exactly one setting
+- **The Core Fear:** Being named. Not exposed — *named*. The Ducal Accord's ultimate law forbids any mortal claiming the moniker of King, and Palla Vantry has held one-fifth of a sovereign city's government for fifty-eight years by continuous free election. She has claimed nothing. She has never needed to. She is acutely aware that the [[The Cult of the Zenith|Cult of the Zenith]] could void her seat for irregularity and could never validate it either, and that the day someone puts the word to what she is, the Court of Nullity becomes the only venue in the world and it has exactly one setting
 - **Moral Compromises:** The Long Seat handles external trade, and external trade includes **Tuwal Ghorun**. She has spent decades ensuring the identity void between *Tuwal Ghorun* and *Twelgorn* is never resolved, because an unresolved polity cannot be formally traded with, formally taxed, or formally condemned — and the Vantry houses have moved southern goods through that gap for her entire tenure. Every escaped slave in [[Divtown]] whose Retriever's writ is unenforceable owes that to the same void that launders her cargo. She is aware of this symmetry and has never once used it as a defence
@@ -35,2 +35,2 @@
 - **Rivals / Creditors:** [[Verrine Sallow]] (whom she blocked and quietly rates highest of the four), [[Lucia Marrenhal]] (the only councillor who has openly asked, in chamber, how long is too long), [[Ottavian Kress]] (vulgar, effective, unignorable)
-- **Key Notes:** [[Council of Five]], [[History - The Broken Crown of Austhal]] (the Accord, Tuwal Ghorun), [[Religion - The pagan Pantheon and the Faith Domains]] (the Court of Nullity), [[The Inner Sea]]
+- **Key Notes:** [[Council of Five]], [[History - The Broken Crown of Austhal]] (the Accord, Tuwal Ghorun), [[The Cult of the Zenith]] (the Court of Nullity), [[The Inner Sea]]
```

### `200 Cast/202 The Underworld/Captain Haren Twarde.md`

```diff
@@ -11,3 +11,3 @@
 - **Social Class / Standing:** Outlaw / Sovereignty of the Lagoons.
-- **Primary Residence:** The Captain's Cabin aboard the *Dread-Wing*, currently moored in the [[000 Atlas/Grey Water Lagoon|Grey Water Lagoon]].
+- **Primary Residence:** The Captain's Cabin aboard the *Dread-Wing*, currently moored in the [[Greywater Lagoon|Grey Water Lagoon]].
 - **Affiliations:** The Wyvern Tail Pirates (Commander); [[000 Atlas/Divtown|Divtown]] Syndicate (Primary Commercial Partner).
```

### `200 Cast/202 The Underworld/Morgran the Abomination.md`

```diff
@@ -17,3 +17,3 @@
   The change left a piece of the Undertow's pull inside him, which is likely why saltwater soothes it and dry air makes his skin crack and bleed. It did not come with a way back.
-- **Physical Flaws / Limitations:** He is a raging alcoholic. Because of the change, he must submerge himself in saltwater at least once a day or his skin begins to crack and bleed. He is shunned by his own people in [[000 Atlas/The Ubaraz Kingdom|The Ubaraz Kingdom]] — first for leaving the mountains for a marsh boat, and finally for what he let a hag make of him.
+- **Physical Flaws / Limitations:** He is a raging alcoholic. Because of the change, he must submerge himself in saltwater at least once a day or his skin begins to crack and bleed. He is shunned by his own people in [[Ubaraz Kingdom|The Ubaraz Kingdom]] — first for leaving the mountains for a marsh boat, and finally for what he let a hag make of him.
 - **Equipment & Upkeep:** Carries a specialized, heavy dwarven sounding-lead on a chain to test the depth of the shifting sandbars, and a perpetually empty iron flask.
```

### `200 Cast/204 Middle Class/High Captain Marco.md`

```diff
@@ -34,2 +34,2 @@
 - **Wary respect / friction:** [[Tythius De Vonce|Duke Tythius De Vonce]]
-- **Unresolved institutional concern:** [[The Jagged Spine|The Jagged Spine]] and [[draft2_The Five Duchies of the Whispering Coast#5. 💀 The Scarred Land: Duchy of Corvus (The Fallen Crown)|the Corvus Scar]]
+- **Unresolved institutional concern:** [[The Jagged Spine|The Jagged Spine]] and [[The Five Duchies of the Whispering Coast#5. 💀 The Scarred Land: Duchy of Corvus (The Fallen Crown)|the Corvus Scar]]
```

### `200 Cast/204 Middle Class/Jeerdan Darcy.md`

```diff
@@ -40,3 +40,3 @@
 - **Demands his paperwork:** [[Tythius De Vonce|Duke Tythius De Vonce]]
-- **Whose cargo he has declined to inspect:** [[The Cobalt Syndicate|The Cobalt Feather Syndicate]]
+- **Whose cargo he has declined to inspect:** [[The Cobalt Feather Syndicate|The Cobalt Feather Syndicate]]
 - **Structural parallel — status that evaporates without a document:** [[First Envoy Isolde Vantry|First Envoy Isolde Vantry]]
```

### `200 Cast/Lidda Shoon.md`

```diff
@@ -18,2 +18,2 @@
 ## 🔗 Connected Notes
-- **Business Contact:** [[200 Cast/Kaleb the Barkeep|Kaleb]] (She drops fenced coin at the Tankard for the Syndicate to collect).
+- **Business Contact:** [[Kaleb|Kaleb]] (She drops fenced coin at the Tankard for the Syndicate to collect).
```

### `400 Meta/Framework - The Coastal Reckoning.md`

```diff
@@ -119,3 +119,3 @@
 - **Debts cannot be called**, and the debt-prisons take no new admissions
-- **A Nullity Sitting cannot be convened** — the [[Religion - The pagan Pantheon and the Faith Domains|Cult of the Zenith]] holds that a day outside the reckoning cannot host a judgment. This is doctrinally awkward for them and they do not enjoy discussing it
+- **A Nullity Sitting cannot be convened** — the [[The Cult of the Zenith|Cult of the Zenith]] holds that a day outside the reckoning cannot host a judgment. This is doctrinally awkward for them and they do not enjoy discussing it
 
```

### `400 Meta/Framework - The Three Layers.md`

```diff
@@ -91,3 +91,3 @@
 - **Cost & Mote:** Documented at length in [[Economy - the Price of Survival|the Price of Survival]] — a deliberate poverty trap where a labourer's daily survival costs exactly their daily wage. The mote is thin and should stay thin: the [[100 Society/The Tidespoken Clergy|Tidespoken]] soup kitchens, and Company enlistment as the one legal ladder out.
-- **⚠️ Gap:** no named members. The body that governs 35,000 people has zero faces. This is the single highest-value gap at Layer 1.
+- ~~**⚠️ Gap:** no named members.~~ **Filled:** [[Marcian Thole]], [[Lucia Marrenhal]], [[Ottavian Kress]], [[Verrine Sallow]], [[Palla Vantry]].
 
@@ -177,8 +177,8 @@
 - ~~**Undertow → low-frequency terminology pass.**~~ **RESOLVED 2026-09-28 — reversed.** "Frequency" language is retired. The tidal cosmology of `Cosmology - The Great Fracture.md` is canon throughout: *the Undertow* names the Tideways' lowest layer, and *Undertow-touched* is the adjective for taint and property — Morgran struck an Undertow-touched god-shard; the Ash-Blight is Undertow-touched soot. Applied to The Five Duchies, The Inner Sea, The Golden Company, History, Tythius De Vonce, Maccorrack, Morgran and The Wondrous Markets.
-- **Broken link.** Corvus Spire is wikilinked as `[[The Inner Sea#🪓 Resource & Industry|Corvus Spire]]` — pointing the seat at a section of a different region's document, which references it rather than defining it. Recommend a bold unlinked term until Corvus Spire gets its own stub.
+- ~~**Broken link.**~~ **Resolved — the link no longer exists.** Corvus Spire was wikilinked as `[[The Inner Sea#🪓 Resource & Industry|Corvus Spire]]` — pointing the seat at a section of a different region's document, which references it rather than defining it. Recommend a bold unlinked term until Corvus Spire gets its own stub.
 - **"Functionally extinct" is a hedge.** With the seats now named, the epigraph's "one rules an ossuary" reads as poetry rather than a claimant. Confirm that's intended — if there *is* a surviving Corvus line somewhere, that changes the annexation problem from a legal impossibility into a live succession crisis.
 - **Tier vocabulary collision.** `The Sunken Ward` and `The Muddy Docks` are both tagged `#location/district`, but the Docks sit *inside* the Ward. If the Layers are formalising scale, the location tags should too — recommend `#location/district` for Ward-scale and a new `#location/neighborhood` for Docks-scale.
-- **Blue-Cloak contradiction, still open.** `Port_Nevarellon.md` describes the Watch as professional in the wealthy districts; the Constabulary faction file describes uniform systemic corruption. Both cannot be true. This is a Layer 3 enforcement question and should be resolved before Layer 3 gets built out further.
-- **Whispering Coast hierarchy, still open.** `Austhal.md` and `Whispering_Coast.md` disagree on whether the Five Duchies are a sibling region or a subdivision. The Layer model assumes subdivision.
-- **Does the Council of Five have named members?** Until it does, Layer 1 is a third empty.
+- ~~**Blue-Cloak contradiction.**~~ **RESOLVED 2026-09-28:** `Port Nevarellon.md` now names the Golden Company as the military and the Blue-Cloaks as the Constabulary beneath it. Original note: `Port_Nevarellon.md` describes the Watch as professional in the wealthy districts; the Constabulary faction file describes uniform systemic corruption. Both cannot be true. This is a Layer 3 enforcement question and should be resolved before Layer 3 gets built out further.
+- ~~**Whispering Coast hierarchy.**~~ **RESOLVED 2026-09-28:** the Five Duchies are a subdivision of the Whispering Coast; `Austhal.md` updated. Original note: `Austhal.md` and `Whispering_Coast.md` disagree on whether the Five Duchies are a sibling region or a subdivision. The Layer model assumes subdivision.
+- ~~**Does the Council of Five have named members?**~~ **Yes** — see [[Council of Five]].
 
```

### `400 Meta/Reference - The Wondrous Markets.md`

```diff
@@ -24,3 +24,3 @@
 
-The setting already has the perfect machinery for this. Under the **Court of Nullity** doctrine, the [[Religion - The pagan Pantheon and the Faith Domains|Cult of the Zenith]] may void a claim and may never validate one. If the Fourth's claim to the title was *voided* on grounds of calamity, then:
+The setting already has the perfect machinery for this. Under the **Court of Nullity** doctrine, the [[The Cult of the Zenith|Cult of the Zenith]] may void a claim and may never validate one. If the Fourth's claim to the title was *voided* on grounds of calamity, then:
 
@@ -36,3 +36,3 @@
 
-This is not a new institution. The [[Religion - The pagan Pantheon and the Faith Domains|Cult of the Zenith]] already maintains **the Register**, and already enforces by *refusal to verify* rather than by force. The Wondrous Markets are an entry in it. Nobody founded the Register of Markets; somebody with a grievance against a rival city brought a claim, the Zenith heard it because the Zenith hears things, the ruling stuck because no one could produce a better forum, and fifty years later it is simply where the number lives.
+This is not a new institution. The [[The Cult of the Zenith|Cult of the Zenith]] already maintains **the Register**, and already enforces by *refusal to verify* rather than by force. The Wondrous Markets are an entry in it. Nobody founded the Register of Markets; somebody with a grievance against a rival city brought a claim, the Zenith heard it because the Zenith hears things, the ruling stuck because no one could produce a better forum, and fifty years later it is simply where the number lives.
 
```

## Part C — Rebuilt `_Home.md` hub (1 file)

Optional. The old hub linked to nine notes that don't exist (Brine-Weaving, Midnight Fogs, Salt-Coin Accord, five Duchy files, a timeline). This version links only to live notes.

### `_Home.md`

```diff
@@ -3,23 +3,22 @@
 ## 📍 World & Geography
-- [[Austhal| The continent of Austhal]] (Nation overview)
-- [[Port Nevarellon]] (The central hub city)
-- [[Whispering Coast]] (Regional geography)
-- [[000 Atlas/De Vonce Duchy]]
-- [[000 Atlas/Duchy of Corvus]]
-- [[000 Atlas/Duchy of Aerthos]]
-- [[Duchy of Valerius]]
-- [[000 Atlas/Duchy of Stonereach]]
-- [[The Drowned Rat Tavern]]
+- [[Austhal|The continent of Austhal]]
+- [[Whispering Coast]] — the region
+  - [[The Five Duchies of the Whispering Coast]] — De Vonce, Aerthos, Valerius, Stonereach, and the Corvus Scar
+  - [[Port Nevarellon]] — the Free City
+- [[Silted Marshes]] · [[The Inner Sea]] · [[Ubaraz Kingdom]] · [[The Jagged Spine]]
 
 ## 🏛️ Power & Culture
-- **Factions:** [[The Iron-Anchor Syndicate]], [[The Cobalt Syndicate|The Cobalt Syndicate]]
-- **Religions:** [[The Tidespoken Clergy]]
-- **Economics:** [[The Salt-Coin Trade Accord]]
+- **Governance:** [[Council of Five]] · [[The Golden Company]] · [[The Cult of the Zenith]] · [[Law - The Council's Edicts]]
+- **Underworld:** [[The Iron-Anchor Syndicate]] · [[The Cobalt Feather Syndicate]] · [[The Wyvern tail Pirates]]
+- **Guilds & Watch:** [[The Guild of Alchemists]] · [[Faction - The Civic Constabulary (The Coppers)|The Civic Constabulary]]
+- **Faith:** [[Religion - The Pagan Pantheon and the Faith Domains]]
+- **Economy:** [[Economy - the Price of Survival]] · [[Reference - The Wondrous Markets]]
 
 ## 🔮 The Rules of the World
-- **Magic:** [[The Brine-Weaving System]]
-- **Phenomena:** [[The Midnight Fogs]]
+- **Cosmology:** [[Cosmology - The Great Fracture]] · [[Cosmology - The Celestial Graveyard and The war of Creation]]
+- **Calendar & Sky:** [[Framework - The Coastal Reckoning]]
+- **History:** [[History - The Broken Crown of Austhal]]
 
 ## 📝 Creator Tools
-- [[Worldbuilding Timeline]]
-- [[Active Character Directory]]
+- [[iron and marrow canon tracker|Canon Tracker]]
+- [[Framework - The Three Layers]] · [[Reference - Name Tables]]
```
