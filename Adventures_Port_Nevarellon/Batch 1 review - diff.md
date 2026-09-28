# Batch 1 — Today's decisions (review diff)

**Nothing has been written to the vault.** Each part below can be approved on its own.

**Decisions this batch applies**
- The "frequency" vocabulary is retired. *The Undertow* is the name of the layer, and *Undertow-touched* is the adjective for taint.
- Garrick Vance becomes **Garrick Rudd** and Maeve Vance becomes **Maeve Dunn**. Captain Elias "Half-Step" Vance stays, and both epigraphs now name him.
- Maccorrack works for the **Cobalt Feather**.
- Telorna Belaar becomes **Tahra Beyr**, moved from the Landed Latinate register to the Southern register.
- **Guild of Alchemists:** one cross-border body. The old "High Alchemist Guild" references now name its Port Nevarellon chapter.
- **Firearms and black powder:** a fifth Edict of Armament, plus the knock-on edits for Garrick, Maeve and Kress.
- **The Shades has two deeds.** Garrick and the Dolly Sisters each hold one, and neither will go to the Zenith.

**Deliberately left out of this batch**
- The canon tracker (Batch 4)
- Anything under `drafts/`, the loose `.txt` snapshots, and the D&D session notes
- The rules folder

**Apply sequence (after your approval)**
1. **You:** make an Obsidian Git commit as a restore point.
2. **Me:** check each file's modified time against the copy this diff was built from. If any file has changed since, I stop and rebuild that file's diff instead of writing.
3. **Me:** write the approved files, with a guard that refuses to write over any file edited in between.
4. **You, in Obsidian after the write:** rename `200 Cast/Telorna Belaar.md` → `Tahra Beyr.md`, and `100 Society/101 Factions & Guilds/The High Alchemist Guild.md` (currently empty) → `The Guild of Alchemists.md`. The links already point to the new names, so they resolve as soon as the files are renamed.
5. **Me:** re-read the written files and confirm that no "frequenc", "Telorna", "Garrick Vance", "Maeve Vance" or "High Alchemist Guild" remains outside `drafts/` and the tracker.

**Rules implications — flagged, not carried over:** firearm and powder stats, and whether Golden Company officers carry firearms.

---

## Part A — Terminology & names (26 files)

Substitutions only. No new lore except one resolution note in Three Layers and Maccorrack's habit reassigned to existing canon (Cindin). Lines beginning `-` are the current text; lines beginning `+` are the proposed text.

### `000 Atlas/001 Regions & Continents/Silted Marshes.md`

```diff
@@ -24,3 +24,3 @@
 - **Who Claims It:** The **Council of Five** nominally claims the northern estuaries, while the **Twelgorn Kingdom** claims the southern reaches. [[Lord Kelf Thorne|Lord Kelf Thorne]] claims the title of "Baron of the Silted Marshes."
-- **Who Actually Controls It:** Nature itself is the supreme authority. Locally, survival is dictated by [[200 Cast/Telorna Belaar|Telorna Belaar]] and her logging crews. Along the southern fringes, the true power lies with the heavily armed **"Retrievers"**—brutal bounty hunters sent north by the Twelgorn Kingdom to hunt down escaped slaves hiding in the muck.
+- **Who Actually Controls It:** Nature itself is the supreme authority. Locally, survival is dictated by [[200 Cast/Tahra Beyr|Tahra Beyr]] and her logging crews. Along the southern fringes, the true power lies with the heavily armed **"Retrievers"**—brutal bounty hunters sent north by the Twelgorn Kingdom to hunt down escaped slaves hiding in the muck.
 - **Notable Fauna / Predators:** 
```

### `000 Atlas/001 Regions & Continents/The Five Duchies of the Whispering Coast.md`

```diff
@@ -47,12 +47,12 @@
 - **Terrain & Seat:** Once a rich valley of black soil, dense pine, and ancient stone spires. Today, it is a blackened, ash-choked wasteland known as **The Corvus Scar**. The ancestral seat, **Corvus Spire**, was buried in the mountain collapse fifty years ago and has never been excavated or resettled. It should not be confused with [[The Inner Sea#🪓 Resource & Industry|The Broken Spires]] out in the Inner Sea — those are drowned peaks, not masonry, and what they share with Corvus is not architecture but the same heat-scarred fracturing along the same seam.
-- **Travel Time to Port Nevarellon:** Not meaningfully defined. No lawful road runs into the Ash-Blight, and there is no seated authority left to travel to. The only hard figure on record is tactical, not diplomatic: De Vonce's standing border levy along the Jagged Spine could reach the Scar's edge in roughly 1–2 days if the low frequencies stirred again.
+- **Travel Time to Port Nevarellon:** Not meaningfully defined. No lawful road runs into the Ash-Blight, and there is no seated authority left to travel to. The only hard figure on record is tactical, not diplomatic: De Vonce's standing border levy along the Jagged Spine could reach the Scar's edge in roughly 1–2 days if the Undertow stirred again.
 
 ### 💥 The Cataclysm (50 Years Ago)
-Five decades ago, a catastrophic breach in the god-frequencies occurred along the northern peaks, resulting in a violent, low-frequency **Demonic Incursion**. The sheer pressure of the entities entering the mortal plane caused a massive mountain spire in the Spine Mountains to physically collapse, burying the ancestral seat of House Corvus under millions of tons of shattered rock.
+Five decades ago, a catastrophic breach opened into the Undertow along the northern peaks, resulting in a violent **Demonic Incursion**. The sheer pressure of the entities entering the mortal plane caused a massive mountain spire in the Spine Mountains to physically collapse, burying the ancestral seat of House Corvus under millions of tons of shattered rock.
 
 ### 🥖 Modern Aftermath & Realism Logistics
-- **The Ash-Blight:** The collapse of the spire released a localized, lingering atmospheric shroud of low-frequency alchemical soot. Most of the Scar's soil is dead and the streams run black with acidic sulfur — but *dead* is a word the ducal surveyors used because measuring properly would have meant going in. There are pockets. Wind-shadowed valleys where the soot never settled thick, seeps of clean water below the blight-line, ground that will take a crop if you know which ground and are willing to find out the hard way. None of this makes the Scar habitable in any sense the four Duchies would recognise. It makes it *claimable*.
+- **The Ash-Blight:** The collapse of the spire released a localized, lingering atmospheric shroud of Undertow-touched alchemical soot. Most of the Scar's soil is dead and the streams run black with acidic sulfur — but *dead* is a word the ducal surveyors used because measuring properly would have meant going in. There are pockets. Wind-shadowed valleys where the soot never settled thick, seeps of clean water below the blight-line, ground that will take a crop if you know which ground and are willing to find out the hard way. None of this makes the Scar habitable in any sense the four Duchies would recognise. It makes it *claimable*.
 - **The Scar-Holders:** A thin, uncounted population lives inside the Ash-Blight — squatters, blight-scavengers stripping metal from the buried spire's outworks, and a handful of steadings genuinely farming the clean pockets. They hold no deed, pay no levy, and appear on no roll. Life expectancy is short and the ways it ends are ugly: blight-lung, sulfur-poisoned water, exposure, and whatever still moves in the corrupted valleys. What they have instead is the only land on the Whispering Coast that nobody can legally take from them, because nobody can legally hold it in the first place. Grit is not a virtue out there. It is the entire entry requirement.
 - **The Refugee Crisis:** Fifty years later, the displaced populations of Corvus still form the desperate, impoverished underclass living in **The Sunken Ward** and **The Muddy Docks** of Port Nevarellon. 
-- **The Shattered Power Balance:** House Corvus is functionally extinct. The remaining four duchies have spent the last fifty years in a cold war, quietly pushing their borders inward to annex the edges of the un-scarred farmlands left behind, while their border guards nervously watch the corrupted valleys for signs of the low frequencies stirring again.
-- **The Annexation Problem Nobody Planned For:** Every year the Scar-Holders make more of the Blight productive, they make the land the four Duchies are quietly annexing more valuable — and harder to annex quietly. A Duke can absorb an empty valley by moving a border stone at night. Absorbing a *worked* valley means either recognising the people on it, which grants standing to Un-Landed squatters and sets a precedent the [[Council of Five|Council]] would seize on within the year, or clearing them, which is a massacre performed on land the Duke has no legal claim to. Both roads run through the Cult of the Zenith, which cannot validate either claim. The border guards are not only watching for the low frequencies. They are watching smoke rise from chimneys that are not supposed to exist.
+- **The Shattered Power Balance:** House Corvus is functionally extinct. The remaining four duchies have spent the last fifty years in a cold war, quietly pushing their borders inward to annex the edges of the un-scarred farmlands left behind, while their border guards nervously watch the corrupted valleys for signs of the Undertow stirring again.
+- **The Annexation Problem Nobody Planned For:** Every year the Scar-Holders make more of the Blight productive, they make the land the four Duchies are quietly annexing more valuable — and harder to annex quietly. A Duke can absorb an empty valley by moving a border stone at night. Absorbing a *worked* valley means either recognising the people on it, which grants standing to Un-Landed squatters and sets a precedent the [[Council of Five|Council]] would seize on within the year, or clearing them, which is a massacre performed on land the Duke has no legal claim to. Both roads run through the Cult of the Zenith, which cannot validate either claim. The border guards are not only watching for the Undertow. They are watching smoke rise from chimneys that are not supposed to exist.
```

### `000 Atlas/001 Regions & Continents/The Inner Sea.md`

```diff
@@ -43,3 +43,3 @@
   - **Grounded Threats:** Reef-drakes and giant barnacle-mimics that latch onto wooden hulls to rot the timber.
-  - **The Leviathans:** Massive, prehistoric, low-frequency monstrous sea creatures that drift up from the abyssal trenches of the outer ocean. Some are heavily armored, requiring specialized harpoon ballistas and alchemical explosives to kill.
+  - **The Leviathans:** Massive, prehistoric, Undertow-touched monstrous sea creatures that drift up from the abyssal trenches of the outer ocean. Some are heavily armored, requiring specialized harpoon ballistas and alchemical explosives to kill.
 
```

### `000 Atlas/002 Cities & Settlements/Port Nevarellon.md`

```diff
@@ -34,3 +34,3 @@
 While magic exists, it is bounded by industrial cost:
-- **[[The Brine-Glow Lanterns| The Brine-Glow Lanterns:]]** The city's main avenues are illuminated at night not by oil, but by glass globes containing chemically preserved, bioluminescent deep-sea algae. Maintaining these lanterns is a massive municipal expense managed by [[The High Alchemist Guild|The High Alchemist Guild]].
+- **[[The Brine-Glow Lanterns| The Brine-Glow Lanterns:]]** The city's main avenues are illuminated at night not by oil, but by glass globes containing chemically preserved, bioluminescent deep-sea algae. Maintaining these lanterns is a massive municipal expense managed by the Port Nevarellon chapter of [[The Guild of Alchemists|the Guild of Alchemists]].
 - **The Tide-Wards:** Ancient, eroding basalt monoliths are embedded along the Sea-Wall. They do not stop storms, but they stabilize the bedrock beneath the city to prevent the timber stilts from sliding into the ocean shelf during tremors.
```

### `000 Atlas/003 Sub-Locations & Architecture/Greywater Lagoon.md`

```diff
@@ -24,3 +24,3 @@
 - **Primary Income:** The lagoon is the ultimate fencing floor. Pirates offload stolen silks, spices, and Imperial gold. In return, they buy the only thing they can't steal on the open ocean: fresh water, safe harbor, and repairs using Divtown's rot-resistant timber.
-- **The Washing of the Coin:** Goods are offloaded here, logged by [[200 Cast/Telorna Belaar|Telorna Belaar]], stamped with Lord Thorne's noble seal as "legally salvaged marsh-wreckage," and then rowed north into the city as legitimate merchandise.
+- **The Washing of the Coin:** Goods are offloaded here, logged by [[200 Cast/Tahra Beyr|Tahra Beyr]], stamped with Lord Thorne's noble seal as "legally salvaged marsh-wreckage," and then rowed north into the city as legitimate merchandise.
 
@@ -33,3 +33,3 @@
 - [[200 Cast/Captain Vesper Locke|Captain Vesper "Red-Wake" Locke]] — *Captain of the 'Carrion Crow'. The unofficial speaker for the pirate crews, currently negotiating repair costs.*
-- [[200 Cast/Telorna Belaar|Telorna Belaar]] — *Frequent Visitor. She stands on the pontoons with a ledger, calculating the exact exchange rate of stolen spices for raw timber.*
+- [[200 Cast/Tahra Beyr|Tahra Beyr]] — *Frequent Visitor. She stands on the pontoons with a ledger, calculating the exact exchange rate of stolen spices for raw timber.*
 - [[Morgran the Abomination|Morgran the Abomination]] — *The only pilot trusted to guide the heavy galleons through the shifting mud-veins into the lagoon.*
```

### `100 Society/101 Factions & Guilds/Faction - The Civic Constabulary (The Coppers).md`

```diff
@@ -3,3 +3,3 @@
 
-> "The Golden Company protects the gold. We protect the mud. And let me tell you, the mud doesn't pay its taxes on time, but it sure as hell stabs you just as deep." — Sergeant Vance, Dock-Watch
+> "The Golden Company protects the gold. We protect the mud. And let me tell you, the mud doesn't pay its taxes on time, but it sure as hell stabs you just as deep." — Captain Elias Vance, Dock-Watch
 
```

### `100 Society/101 Factions & Guilds/The Cobalt Feather Syndicate.md`

```diff
@@ -3,3 +3,3 @@
 
-> "Garrick’s men fight with iron pins and broken bottles. The Feathers fight with a whisper in a magistrate’s ear, a forged cargo manifestation, and a drop of tasteless toxin in your evening soup." — Captain Vance, Dock-Watch
+> "Garrick’s men fight with iron pins and broken bottles. The Feathers fight with a whisper in a magistrate’s ear, a forged cargo manifestation, and a drop of tasteless toxin in your evening soup." — Captain Elias Vance, Dock-Watch
 
@@ -20,3 +20,3 @@
 
-- **The High-Steel and Magic Market:** They are the primary source for illegal **High-Steel** weapons inside the city walls. They also specialize in smuggling unanchored god-shards recovered from the deep trenches of the Expanse, selling them to rogue alchemists in the High Quarter who want to bypass the city's strict ecclesiastical monopolies.
+- **The High-Steel and Magic Market:** They are the primary source for illegal **High-Steel** weapons inside the city walls. They also specialize in smuggling unanchored god-shards recovered from the deep trenches of the Expanse, selling them to rogue alchemists in the High Quarter who want to bypass the monopolies of [[The Guild of Alchemists|the Guild of Alchemists]].
 - **The Friction:** There is a silent, bloody cold war between the Cobalt Feather and the Iron-Anchor Syndicate. Garrick wants to control the Basin, but the Cobalt Feather systematically leaks information about Iron-Anchor operations to the Golden Company, letting the law wipe out their rivals while keeping their own hands clean.
```

### `100 Society/101 Factions & Guilds/The Golden Company.md`

```diff
@@ -86,3 +86,3 @@
 ## 🔗 Key Figures & Relations
-- **[[High Captain Marco|High Captain Marco]]:** *(NPC)* The senior Company officer stationed in Port Nevarellon and its de facto local commander. Foreign-born, coldly professional, and unusually strategically minded for a garrison officer — he tracks the Corvus Scar and the northern passes with real anxiety, aware the Contract was never designed for a low-frequency incursion, only for policing merchants and mobs.
+- **[[High Captain Marco|High Captain Marco]]:** *(NPC)* The senior Company officer stationed in Port Nevarellon and its de facto local commander. Foreign-born, coldly professional, and unusually strategically minded for a garrison officer — he tracks the Corvus Scar and the northern passes with real anxiety, aware the Contract was never designed for an incursion out of the Undertow, only for policing merchants and mobs.
 - **[[Provost Halvard Stross|Provost Halvard Stross]]:** *(NPC)* Marco's officer responsible for overseeing the Civic Constabulary's conduct citywide — the man Captain Elias "Half-Step" Vance dreads and quietly bribes information toward, terrified Stross will eventually notice how selectively Vance's Toll-House makes its arrests.
```

### `100 Society/101 Factions & Guilds/The Iron-Anchor Syndicate.md`

```diff
@@ -28,3 +28,3 @@
 ## ⚡ Internal Friction & Conflict
-- **Internal Factions:** A growing rift exists between the *Old Guard* (who want to stick to traditional smuggling and protection) and the *Young Bloods* led by [[Silas Bane|Silas Bane]], who wants to violently challenge [[The High Alchemist Guild|The High Alchemist Guild]] for control of the bioluminescent lighting monopoly.
+- **Internal Factions:** A growing rift exists between the *Old Guard* (who want to stick to traditional smuggling and protection) and the *Young Bloods* led by [[Silas Bane|Silas Bane]], who wants to violently challenge the Port Nevarellon chapter of [[The Guild of Alchemists|the Guild of Alchemists]] for control of the bioluminescent lighting monopoly.
 - **External Rivals:** [[100 Society/The Tidespoken Clergy|The Tidespoken Clergy]] (who actively undermine Syndicate recruitment by feeding and protecting the poorest dockworkers).
```

### `100 Society/101 Factions & Guilds/The Wyvern tail Pirates.md`

```diff
@@ -3,3 +3,3 @@
 
-> "The Twelgorn navy builds their warships like floating fortresses. Haren treats them like fat cattle. She waits until they beach themselves on the silt-banks, then she bleeds them dry." — Telorna Belaar
+> "The Twelgorn navy builds their warships like floating fortresses. Haren treats them like fat cattle. She waits until they beach themselves on the silt-banks, then she bleeds them dry." — Tahra Beyr
 
```

### `100 Society/102 Lore & History/History - The Broken Crown of Austhal.md`

```diff
@@ -10,3 +10,3 @@
 - Centurires have passed since the breaking of the cosmic sphere. 
-- The truth of the deicide, the shattered god-frequencies, and the cosmic war has completely faded out of mortal memory. 
+- The truth of the deicide, the shattering of the Sphere into the Tideways, and the cosmic war has completely faded out of mortal memory. 
 - Today, that ancient era exists only as unmapped ruins, petrified bones deep in the earth, and fragmented lore pieced together by fringe philosophers, explorers, and radical religious sects.
```

### `200 Cast/201 Nobility & Elites/High Arbiter Sevrin Kalder.md`

```diff
@@ -16,3 +16,3 @@
 - **Financial Status:** Comfortable, and thinner than the frontage suggests. The Kalder money is two generations old and was never as deep as the address implies. He takes the fixed notarial fee and nothing else, which is a point of enormous personal pride and has cost him a great deal
-- **Equipment & Upkeep:** A heavy comet pendant worn since ordination, the silver worn concave where his thumb sits. A working copy of the *Meditations on Law* annotated in his own hand across four decades, the margins now longer than the text. A throat-tincture from [[The High Alchemist Guild]] that does not work and that he continues to buy
+- **Equipment & Upkeep:** A heavy comet pendant worn since ordination, the silver worn concave where his thumb sits. A working copy of the *Meditations on Law* annotated in his own hand across four decades, the margins now longer than the text. A throat-tincture from [[The Guild of Alchemists|the Guild of Alchemists]] that does not work and that he continues to buy
 
```

### `200 Cast/201 Nobility & Elites/Lord Kelf Thorne.md`

```diff
@@ -24,3 +24,3 @@
 ## 🔗 Connected Notes
-- **Right Hand / Enforcer:** [[200 Cast/Telorna Belaar|Telorna Belaar]] 
+- **Right Hand / Enforcer:** [[200 Cast/Tahra Beyr|Tahra Beyr]] 
 - **Vital Guide:** [[Morgran the Abomination|Morgran (The Cursed Dwarf)]]
```

### `200 Cast/201 Nobility & Elites/Lucia Marrenhal.md`

```diff
@@ -16,3 +16,3 @@
 - **Financial Status:** The wealthiest of the five by a wide margin, and the only one whose wealth is genuinely liquid. She could buy Thole's yards outright and has calculated the figure more than once
-- **Equipment & Upkeep:** Lenses in a plain case, replaced every eighteen months at ruinous cost from the [[The High Alchemist Guild]]. No Golden Writ. She has never owned a weapon and regards the fact as a statement
+- **Equipment & Upkeep:** Lenses in a plain case, replaced every eighteen months at ruinous cost from [[The Guild of Alchemists|the Guild of Alchemists]]. No Golden Writ. She has never owned a weapon and regards the fact as a statement
 
```

### `200 Cast/201 Nobility & Elites/Tythius De Vonce.md`

```diff
@@ -21,3 +21,3 @@
 - **The Core Fear:** The extinction of his house through internal decay. He has watched human lines rot from within over his long life, and he deeply fears his children lack the hard iron grit required to protect the northern border when he finally passes.
-- **Moral Compromises:** To fund his massive border keeps, Tythius turns a blind eye to the brutal working conditions within his iron mines. He also quietly permits certain "controlled" low-frequency alchemical weapons to be tested by his garrison captains, violating the spirit of the old laws for the sake of tactical readiness.
+- **Moral Compromises:** To fund his massive border keeps, Tythius turns a blind eye to the brutal working conditions within his iron mines. He also quietly permits certain "controlled" Undertow-touched alchemical weapons to be tested by his garrison captains, violating the spirit of the old laws for the sake of tactical readiness.
 
```

### `200 Cast/202 The Underworld/Captain Haren Twarde.md`

```diff
@@ -32,3 +32,3 @@
 - **Fencing Partner:** [[200 Cast/Lord Kelf Thorne|Lord Kelf Thorne]] (She tolerates his noble vanity because his legal seals are flawless).
-- **Logistical Liaison:** [[200 Cast/Telorna Belaar|Telorna Belaar]] (Haren coordinates directly with Telorna to secure timber for hull repairs).
+- **Logistical Liaison:** [[200 Cast/Tahra Beyr|Tahra Beyr]] (Haren coordinates directly with Tahra to secure timber for hull repairs).
 - **The Southern Enemy:** [[000 Atlas/The Twelgorn Kingdom|The Twelgorn Kingdom Navy]] (Her primary target and bitterest rivals).
```

### `200 Cast/202 The Underworld/Garrick the Keelhauler.md`

```diff
@@ -6,3 +6,3 @@
 ## 📊 Vital Statistics
-- **Full Name / Aliases:** Garrick Vance / "The Keelhauler" (A moniker from his mutinous privateer days that he now finds unrefined but useful for intimidation).
+- **Full Name / Aliases:** Garrick Rudd / "The Keelhauler" (A moniker from his mutinous privateer days that he now finds unrefined but useful for intimidation).
 - **Current Occupation:** Grandmaster of [[The Iron-Anchor Syndicate|The Iron-Anchor Syndicate]] / Unofficial Magistrate of the Waterfront.
```

### `200 Cast/202 The Underworld/Maeve the Scribe.md`

```diff
@@ -3,6 +3,6 @@
 
-> "Garrick bought my freedom, but Silas bought the guards at my front door. I don't balance loyalty; I balance survival." — Maeve Vance (The Scribe)
+> "Garrick bought my freedom, but Silas bought the guards at my front door. I don't balance loyalty; I balance survival." — Maeve Dunn (The Scribe)
 
 ## 📊 Vital Statistics
-- **Full Name / Aliases:** Maeve Vance / "The Ledger-Witch" (A name whispered by superstitious dock hands who don't understand how she tracks thousands of barrels across fifty ships by memory).
+- **Full Name / Aliases:** Maeve Dunn / "The Ledger-Witch" (A name whispered by superstitious dock hands who don't understand how she tracks thousands of barrels across fifty ships by memory).
 - **Current Occupation:** Chief Accountant, Auditor, and Cryptographer for [[The Iron-Anchor Syndicate|The Iron-Anchor Syndicate]].
```

### `200 Cast/202 The Underworld/Silas Bane.md`

```diff
@@ -10,3 +10,3 @@
 - **Primary Residence:** A heavily guarded suite above the fighting pits at [[000 Atlas/The Rusty Anchor Foundry|The Rusty Anchor Foundry]].
-- **Affiliations:** [[The Iron-Anchor Syndicate|The Iron-Anchor Syndicate]] (Faction Leader of the Young Bloods); covert buyer from rogue members of [[The High Alchemist Guild|The High Alchemist Guild]].
+- **Affiliations:** [[The Iron-Anchor Syndicate|The Iron-Anchor Syndicate]] (Faction Leader of the Young Bloods); covert buyer from rogue members of the Port Nevarellon chapter of [[The Guild of Alchemists|the Guild of Alchemists]].
 
```

### `200 Cast/203 Historical & Mythic Figures/Morgran the Abomination.md`

```diff
@@ -13,3 +13,3 @@
 - **Age & Vitality:** 112 years old (Dwarven). 
-- **The Curse (The Mutation):** Decades ago, Morgran was a prospector who dug too deep in the southern marshes and struck an unanchored shard of the Undertow itself, sunk deep in the ocean floor. The chaotic magic warped his dwarven biology. His lower jaw and neck are flared with pulsing, fish-like gills, and patches of thick, slimy gray scales cover his arms and torso. His eyes are entirely black, like a deep-sea predator. Fittingly, the curse didn't just change his body — it left a piece of the Undertow's pull inside him, which is likely why saltwater soothes the change and dry air makes it crack and bleed.
+- **The Curse (The Mutation):** Decades ago, Morgran was a prospector who dug too deep in the southern marshes and struck an unanchored, Undertow-touched god-shard buried deep beneath the marsh bed. The chaotic magic warped his dwarven biology. His lower jaw and neck are flared with pulsing, fish-like gills, and patches of thick, slimy gray scales cover his arms and torso. His eyes are entirely black, like a deep-sea predator. Fittingly, the curse didn't just change his body — it left a piece of the Undertow's pull inside him, which is likely why saltwater soothes the change and dry air makes it crack and bleed.
 - **Physical Flaws / Limitations:** He is a raging alcoholic. Because of his mutation, he must submerge himself in saltwater at least once a day or his skin begins to crack and bleed. He is universally shunned by his own people in [[000 Atlas/The Ubaraz Kingdom|The Ubaraz Kingdom]].
```

### `200 Cast/Maccorrack.md`

```diff
@@ -7,3 +7,3 @@
 - **Full Name / Aliases:** Maccorrack
-- **Current Occupation:** Stevedore (Dockhand) / Syndicate Muscle.
+- **Current Occupation:** Stevedore (Dockhand) / Hired muscle for [[The Cobalt Feather Syndicate|the Cobalt Feather Syndicate]].
 - **Race:** Half-Orc (Descendant of the manufactured monstrous weapons of the pre-sundering war).
@@ -14,3 +14,3 @@
 - **Physicality:** Massive, heavily scarred, and visibly carrying the genetic markers of the monstrous races (heavy jaw, dense bone structure). Due to the city's extreme prejudice and the laws of the [[100 Society/Law - The Council's Edicts|Palm-Length Edict]], he relies entirely on his fists and heavy wooden shipping crates in a fight.
-- **Physical Flaws / Limitations:** Maccorrack suffers from a severe narcotics dependency—likely a low-frequency marsh-root or brine-lotus—used to numb the psychological trauma of his past and the physical aches of heavy labor. 
+- **Physical Flaws / Limitations:** Maccorrack suffers from a severe narcotics dependency—[[Cindin]], chewed by the fistful rather than the pinch—used to numb the psychological trauma of his past and the physical aches of heavy labor. 
 - **Background:** He is an escaped slave who fled north from the brutal [[000 Atlas/The Twelgorn Kingdom|Twelgorn Kingdom]]. The trauma of his enslavement has stripped him of the typical berserker rage expected of his lineage; instead, he is uncharacteristically soft-spoken, deliberate, and fiercely loyal to those who treat him like a man rather than a beast.
@@ -20,3 +20,3 @@
 - **The Core Fear:** Being recognized by a southern Retriever and dragged back in chains to the Twelgorn Kingdom.
-- **Current Role:** He works as a legitimate stevedore by day. By night, Alfric and Kaleb use him as a bodyguard. When the Syndicate trades stolen goods in the hostile pirate towns of the Silted Marshes, Maccorrack is brought along as silent, imposing insurance.
+- **Current Role:** He works as a legitimate stevedore by day. By night, Alfric and Kaleb use him as a bodyguard. When the Cobalt Feather trades stolen goods in the hostile pirate towns of the Silted Marshes, Maccorrack is brought along as silent, imposing insurance.
 
```

### `200 Cast/Telorna Belaar.md`

```diff
@@ -1,8 +1,8 @@
-# Character: Telorna Belaar
+# Character: Tahra Beyr
 #cast/active #status/solid
 
-> "The Baron stamps the wax. I make sure the trees fall, the pirates get paid, and the sandbars don't swallow us all." — Telorna Belaar
+> "The Baron stamps the wax. I make sure the trees fall, the pirates get paid, and the sandbars don't swallow us all." — Tahra Beyr
 
 ## 📊 Vital Statistics
-- **Full Name / Aliases:** Telorna Belaar / "The Iron-Knot"
+- **Full Name / Aliases:** Tahra Beyr / "The Iron-Knot"
 - **Current Occupation:** Timber Forewoman / Syndicate Operations Manager of Divtown.
@@ -22,2 +22,2 @@
 ## 📜 Backstory & Current Role
-Telorna is the true backbone of Divtown. While Kelf drinks wine and negotiates with pirates, Telorna organizes the labor force of outcasts and refugees. She is the one who wades into the waist-deep muck to harvest the timber. The escaped slaves of the town are fiercely loyal to her, not the Baron. If Lord Kelf ever pushes her too far, she could take control of the settlement in a single hour.
+Tahra is the true backbone of Divtown. While Kelf drinks wine and negotiates with pirates, Tahra organizes the labor force of outcasts and refugees. She is the one who wades into the waist-deep muck to harvest the timber. The escaped slaves of the town are fiercely loyal to her, not the Baron. If Lord Kelf ever pushes her too far, she could take control of the settlement in a single hour.
```

### `400 Meta/Framework - The Coastal Reckoning.md`

```diff
@@ -152,3 +152,3 @@
 |---|---|---|
-| **[[The High Alchemist Guild\|The High Alchemist Guild]]** | The Low Moons tables, reckoned in **days** | They must, for the Brine-Glow and Brine-Fire stock. The tables are their property and they sell access |
+| **[[The Guild of Alchemists\|The Guild of Alchemists]]** | The Low Moons tables, reckoned in **days** | They must, for the Brine-Glow and Brine-Fire stock. The tables are their property and they sell access |
 | **The [[Council of Five\|Council of Five]]** | The civil year, reckoned in **turns** | Contracts, tolls, writs, tariff dates. The Council's clerks publish the turn-roll |
```

### `400 Meta/Framework - The Three Layers.md`

```diff
@@ -27,3 +27,3 @@
 
-Rank also fails to predict actual power. [[Garrick the Keelhauler|Garrick the Keelhauler]] holds no title and functionally governs [[The Muddy Docks|the Muddy Docks]] — which no Duke does. [[Telorna Belaar|Telorna Belaar]]'s logging crews are the real authority in the [[Silted Marshes|Silted Marshes]] over a man who calls himself Baron.
+Rank also fails to predict actual power. [[Garrick the Keelhauler|Garrick the Keelhauler]] holds no title and functionally governs [[The Muddy Docks|the Muddy Docks]] — which no Duke does. [[Tahra Beyr|Tahra Beyr]]'s logging crews are the real authority in the [[Silted Marshes|Silted Marshes]] over a man who calls himself Baron.
 
@@ -114,3 +114,3 @@
 - **[[Lord Kelf Thorne|Lord Kelf Thorne]]**, self-styled Baron of the Silted Marshes — a Layer 2 title in a place Layer 1 does not reach at all. Chokepoint: a noble seal that launders pirate cargo as marsh salvage, plus rot-proof Iron-Burl timber that every shipwright on the coast needs.
-- **[[Telorna Belaar|Telorna Belaar]]** — actual control of the marsh through the logging crews, with no title whatsoever. The clean demonstration of why this framework sorts by holding, not by rank.
+- **[[Tahra Beyr|Tahra Beyr]]** — actual control of the marsh through the logging crews, with no title whatsoever. The clean demonstration of why this framework sorts by holding, not by rank.
 - **The Twelgorn "Retrievers"** — armed slave-hunters projecting a foreign power's authority into the southern marsh fringes.
@@ -133,3 +133,3 @@
 
-Populated: [[The Iron-Anchor Syndicate|Iron-Anchor Syndicate]], [[The Cobalt Feather Syndicate|Cobalt Feather Syndicate]], [[100 Society/The Tidespoken Clergy|Tidespoken Clergy]], [[The High Alchemist Guild|High Alchemist Guild]], [[Faction - The Civic Constabulary (The Coppers)|Civic Constabulary]], [[The Dolly Sisters|the Dolly Sisters]], [[Silas Bane|Silas Bane]], the Cinder Row elder-councils.
+Populated: [[The Iron-Anchor Syndicate|Iron-Anchor Syndicate]], [[The Cobalt Feather Syndicate|Cobalt Feather Syndicate]], [[100 Society/The Tidespoken Clergy|Tidespoken Clergy]], [[The Guild of Alchemists|Guild of Alchemists]] (Port Nevarellon chapter only — the parent Guild is cross-border and sits outside the Layers), [[Faction - The Civic Constabulary (The Coppers)|Civic Constabulary]], [[The Dolly Sisters|the Dolly Sisters]], [[Silas Bane|Silas Bane]], the Cinder Row elder-councils.
 
@@ -176,3 +176,3 @@
 
-- **Undertow → low-frequency terminology pass (pending).** The frequency language in the revised Five Duchies doc is the current canon; `Silted_Marshes.md`, `Morgran_the_Abomination.md`, and `Cosmology - The Celestial Graveyard...md` simply haven't been folded in yet. **Scope rule for that pass: the adjective converts, the place name does not.** *Undertow* remains the name of the Tideways' lowest layer per `Cosmology - The Great Fracture.md` — a `status/solid` document where it is the load-bearing cosmological term. Only taint and property usages become "low-frequency": Morgran struck a low-frequency god-shard, but what he struck it *in* is still the Undertow. Once that lands, the `Tidal Undertow` Domain Tag in `Religion.md` should be renamed — with the word reserved for the lower plane, a purely kinetic shove effect carrying it reads as cosmological when it isn't.
+- ~~**Undertow → low-frequency terminology pass.**~~ **RESOLVED 2026-09-28 — reversed.** "Frequency" language is retired. The tidal cosmology of `Cosmology - The Great Fracture.md` is canon throughout: *the Undertow* names the Tideways' lowest layer, and *Undertow-touched* is the adjective for taint and property — Morgran struck an Undertow-touched god-shard; the Ash-Blight is Undertow-touched soot. Applied to The Five Duchies, The Inner Sea, The Golden Company, History, Tythius De Vonce, Maccorrack, Morgran and The Wondrous Markets.
 - **Broken link.** Corvus Spire is wikilinked as `[[The Inner Sea#🪓 Resource & Industry|Corvus Spire]]` — pointing the seat at a section of a different region's document, which references it rather than defining it. Recommend a bold unlinked term until Corvus Spire gets its own stub.
```

### `400 Meta/Reference - Name Tables.md`

```diff
@@ -22,4 +22,4 @@
 | **A — Coastal Common** | Blunt, 1–2 syllables, hard stops. Surnames are occupational, physical, or geographic. | Wren Cobb, Silas Bane, Kelf Thorne, Halvard Stross, Haren Twarde, Alfric Danniken, Lidda Shoon, Garrick, Maeve, Kaleb | Un-Landed, dockers, marsh-folk, rural tenants, most of the Blue-Cloaks |
-| **B — Landed Latinate** | Polysyllabic, vowel-heavy, `-us / -ius / -a / -os` endings. Surnames are house names. | Tythius De Vonce, Valerius, Aerthos, Corvus, Isolde Vantry, Telorna Belaar, Nevarellon | High Quarter, ducal houses, Council patrons, saints |
-| **C — Southern (Twelgorn)** | Guttural, `Al-` patronymic particle, long back vowels. | Qasim Al Goor | Twelgorn-born, escaped slaves, Retrievers |
+| **B — Landed Latinate** | Polysyllabic, vowel-heavy, `-us / -ius / -a / -os` endings. Surnames are house names. | Tythius De Vonce, Valerius, Aerthos, Corvus, Isolde Vantry, Nevarellon | High Quarter, ducal houses, Council patrons, saints |
+| **C — Southern (Twelgorn)** | Guttural, `Al-` patronymic particle, long back vowels. | Qasim Al Goor, Tahra Beyr | Twelgorn-born, escaped slaves, Retrievers |
 | **D — Dwarven** | Consonant-dense, no soft endings; a trade-lineage word replaces a surname. | *(none in canon — proposed)* | Oakhaven Cove, deep-mine work, the Spine |
@@ -87,3 +87,3 @@
 | 25 | Palla Vantry | B | Distant kin to Isolde; born Landed and resents the comparison |
-| 26 | Halcus Rive | B | Alchemist Guild assessor, licences Brine-Glow lanterns |
+| 26 | Halcus Rive | B | Guild of Alchemists assessor, licences Brine-Glow lanterns |
 | 27 | Ysolde Corran | B | Deliberate near-miss on Isolde Vantry; a social climber's chosen name |
@@ -247,3 +247,3 @@
 | 27 | Lantern Watch | Civic | Golden Company | Low Moons mobilisation; double patrols, closed gates |
-| 28 | The Shuttering | Trade rite | High Alchemist Guild | All Brine-Fire stock sealed and logged before the Low Moons → *canon tie* |
+| 28 | The Shuttering | Trade rite | Guild of Alchemists | All Brine-Fire stock sealed and logged before the Low Moons → *canon tie* |
 | 29 | Moonmeat Night | Folk | Rural coast | Livestock slaughtered before the Low Moons rather than risk what the light does |
@@ -269,3 +269,3 @@
 | 49 | Retriever's Fast | Folk | Silted Marshes | Days when nobody moves on open water. Everyone knows why |
-| 50 | The Iron-Burl Felling | Trade rite | Silted Marshes | First cut of the season; Telorna Belaar's crews go first by force of habit |
+| 50 | The Iron-Burl Felling | Trade rite | Silted Marshes | First cut of the season; Tahra Beyr's crews go first by force of habit |
 
```

### `400 Meta/Reference - The Wondrous Markets.md`

```diff
@@ -114,6 +114,6 @@
 
-Corvus took a breach in the god-frequencies in 8 A.A. and a spire came down and killed the duchy outright. The Fourth took its own breach and **the city stayed up** — and then had to go on living around an opening nobody could close. Same phenomenon, two outcomes, and one of them is arguably worse. That grounds every element of the notes in machinery the setting already has, and it gives the Corvus Scar a mirror the players can actually visit.
+Corvus took a breach into the Undertow in 8 A.A. and a spire came down and killed the duchy outright. The Fourth took its own breach and **the city stayed up** — and then had to go on living around an opening nobody could close. Same phenomenon, two outcomes, and one of them is arguably worse. That grounds every element of the notes in machinery the setting already has, and it gives the Corvus Scar a mirror the players can actually visit.
 
 - **The five columns of flame** are the breach, still open, standing where the grandest house was — which is to say it opened *inside* the seat of power, exactly as Corvus Spire did
-- **The winged fiends** are low-frequency entities that came through, same class as the Corvus incursion. `Cosmology` already defines the Undertow as what the pious call the Hells
+- **The winged fiends** are Undertow entities that came through, same class as the Corvus incursion. `Cosmology` already defines the Undertow as what the pious call the Hells
 - **The beasts that fear light** are the part that pays off hardest, and it is because of the sky. The sun does not rise — it *comes back*, from nowhere in particular, owing nobody anything. In the Fourth, that is not theology. It is the difference between being alive at the end of the dark and not. **Every citizen of the Struck City lives the setting's central dread as a literal nightly fact**, and has done for however long this has been going on
```

## Part B — New lore prose (6 files)

Powder Edict, the contested Shades deed, and the firearms consequences. Read these for tone as well as fact. Shown against the Part A result.

### `000 Atlas/003 Sub-Locations & Architecture/The Shades.md`

```diff
@@ -8,3 +8,3 @@
 - **District / Neighborhood:** [[The Muddy Docks|The Muddy Docks]]
-- **Owner / Proprietor:** [[The Dolly Sisters|The Dolly Sisters]] (Clara and Tessa Dolly)
+- **Owner / Proprietor:** [[The Dolly Sisters|The Dolly Sisters]] (Clara and Tessa Dolly) — **title contested.** [[Garrick the Keelhauler|Garrick]] holds a second Council-stamped deed to the same hull. Neither claimant will take it to the Zenith; see [[The Dolly Sisters]].
 - **Affiliation / Protection:** [[The Iron-Anchor Syndicate|The Iron-Anchor Syndicate]] (Pays a heavy weekly tribute to ensure safety from religious zealots and rival gangs)
```

### `100 Society/102 Lore & History/Law - The Council's Edicts.md`

```diff
@@ -24,3 +24,3 @@
 ## 🗡️ The Edicts of Armament
-Because Un-Landed citizens have no property to defend, the Council deems any martial weapon in their hands a direct threat to the city's stability. The Golden Company enforces four strict laws to maintain a monopoly on violence.
+Because Un-Landed citizens have no property to defend, the Council deems any martial weapon in their hands a direct threat to the city's stability. The Golden Company enforces five strict laws to maintain a monopoly on violence.
 
@@ -42,2 +42,6 @@
 
+### 5. The Powder Edict
+Black powder is a controlled substance in Port Nevarellon, as it is in most realms that trade with it. The secret of its making belongs to the [[The Guild of Alchemists|Guild of Alchemists]], and every legal measure of it in the city is issued, logged and inspected by the Guild's Port Nevarellon chapter.
+- **The Reality:** A firearm is a weapon for the very wealthy or the very important, and the law is written to keep it that way. A pistol is a martial weapon and requires a Golden Writ — the copper wire and red wax are threaded through the trigger-guard — but the Writ alone is not enough: its charges must be drawn under a Guild licence in the bearer's name. A Landed citizen caught with unlicensed powder is fined and quietly embarrassed. An Un-Landed citizen caught with powder — not a pistol, merely the powder — is presumed to be supplying someone, and is treated as a seditionist until he names them.
+
 ---
@@ -47,3 +51,3 @@
 
-[[Garrick the Keelhauler|Garrick the Keelhauler]] uses shell companies and bribes to hold the legal deeds to rotting warehouses and taverns like The Shades. Therefore, in the eyes of the law, **Garrick is a Landed Citizen**. He has the legal right to purchase Peace-Bonds, hire private security, and demand court hearings, using the Council's own laws as a shield against the Golden Company. 
+[[Garrick the Keelhauler|Garrick the Keelhauler]] uses shell companies and bribes to hold the legal deeds to rotting warehouses and taverns — among them a deed to The Shades, a hull the [[The Dolly Sisters|Dolly Sisters]] hold a Council-stamped deed to as well. Neither side has taken the question to the [[The Cult of the Zenith|Cult of the Zenith]], and neither will: the Court of Nullity could void both deeds and could never confirm either. Therefore, in the eyes of the law, **Garrick is a Landed Citizen**. He has the legal right to purchase Peace-Bonds, hire private security, and demand court hearings, using the Council's own laws as a shield against the Golden Company. 
 
```

### `200 Cast/201 Nobility & Elites/Ottavian Kress.md`

```diff
@@ -24,3 +24,3 @@
 ## 📜 Backstory & Current Role
-Otta Kress was born in the Muddy Docks and made barrels for twenty years before he made money. Everything in Port Nevarellon moves in a barrel — salt fish, brine-glow algae, black powder, water — and the man who controls the cooperage controls a chokepoint nobody thinks about until it fails. He turned that into a Guild-Mastership, a deed, and eventually the **Water Seat**.
+Otta Kress was born in the Muddy Docks and made barrels for twenty years before he made money. Everything in Port Nevarellon moves in a barrel — salt fish, brine-glow algae, black powder, water — and the man who controls the cooperage controls a chokepoint nobody thinks about until it fails. Powder kegs are coopered only under licence from the [[The Guild of Alchemists|Guild of Alchemists]], and that licence is the one contract the Coopers' Guild cannot afford to lose. He turned that into a Guild-Mastership, a deed, and eventually the **Water Seat**.
 
```

### `200 Cast/202 The Underworld/Garrick the Keelhauler.md`

```diff
@@ -16,3 +16,3 @@
 - **Financial Status:** Imbued with immense, hidden wealth. He hoards foreign gold specie, title deeds to mainland farmland (his ultimate exit strategy), and high-grade alchemical contracts. He could buy a noble title tomorrow, but knows he would be assassinated within a week if he left his power base.
-- **Equipment & Upkeep:** Dresses in bespoke, thick wool coats with tarnished silver buttons—practical for the damp cold of the docks, yet distinct from common deckhands. Carries a heavy, double-barreled flintlock pistol loaded with buckshot (reliable at short range where his vision fails) and his signature iron-capped cane.
+- **Equipment & Upkeep:** Dresses in bespoke, thick wool coats with tarnished silver buttons—practical for the damp cold of the docks, yet distinct from common deckhands. Carries a heavy, double-barreled flintlock pistol loaded with buckshot (reliable at short range where his vision fails; its charges are drawn under a [[The Guild of Alchemists|Guild of Alchemists]] licence held by one of his shell companies, which is the only reason a man of his standing may carry one) and his signature iron-capped cane.
 
@@ -34,3 +34,3 @@
 - **Primary Financial Advisor:** [[Maeve the Scribe|Maeve the Scribe]] (The only person allowed to see his true ledger files)
-- **Covert Partners:** [[The Dolly Sisters|The Dolly Sisters]] (He pays them for intelligence, completely unaware that they hold his secrets in their Black Ledger)
+- **Covert Partners:** [[The Dolly Sisters|The Dolly Sisters]] (He pays them for intelligence, completely unaware that they hold his secrets in their Black Ledger. He also holds a rival deed to their hull, The Shades, and has never tried to enforce it)
 - **Command Center:** [[The Black Mast Warehouse|The Black Mast Warehouse]]
```

### `200 Cast/202 The Underworld/Maeve the Scribe.md`

```diff
@@ -16,3 +16,3 @@
 - **Financial Status:** Paid exceptionally well by Garrick, though her wealth is purely abstract—she has a massive "credit ledger" with the city's banks, but rarely leaves the warehouse to spend a single copper. Her true wealth lies in her ownership of the encrypted keys to every smuggling route on the coast.
-- **Equipment & Upkeep:** Carries a custom leather writing kit containing varying grades of iron-gall ink, vellum scraping knives, and wax seals. Tucked into her bodice is a tiny, double-barreled brass derringer (loaded with lead balls)—useless at range, but meant for a last-resort desk ambush.
+- **Equipment & Upkeep:** Carries a custom leather writing kit containing varying grades of iron-gall ink, vellum scraping knives, and wax seals. Tucked into her bodice is a tiny, double-barreled brass derringer (loaded with lead balls)—useless at range, but meant for a last-resort desk ambush. It was Garrick's gift and is the most valuable thing she owns: its powder is Guild-licensed under his name, which tells anyone who knows how to read it that she belongs to him first and is a bookkeeper second.
 
```

### `200 Cast/202 The Underworld/The Dolly Sisters.md`

```diff
@@ -40,2 +40,7 @@
 The sisters do not just collect secrets for survival—they are running a massive extortion ring against the city's elite. Hidden behind a false bulkhead in their private cabin is a leather-bound journal written in Clara's precise code. It contains the names of several prominent nobles from **The High Quarter** who are secretly financing illegal smuggling operations through **The Iron-Anchor Syndicate** to avoid paying the [[Council of Five]]'s maritime tariffs. This ledger is their ultimate life insurance policy; if either sister is murdered, a designated courier has instructions to drop the journal directly on the steps of the High Court. 
+### 📜 The Second Deed
+The sisters hold a Council-stamped deed to the hull they converted. So does [[Garrick the Keelhauler|Garrick]], through one of his shell companies. How the Writ Seat came to stamp the same hull twice is a question nobody involved wants asked.
+
+Neither side will take it to the [[The Cult of the Zenith|Cult of the Zenith]]. The Court of Nullity can void a deed and can never confirm one — a hearing would most likely end with both instruments struck and a ship with no lawful owner, which in Port Nevarellon means a ship that belongs to whoever the Golden Company removes last. So the matter sits. The sisters pay their weekly tribute and call it protection; Garrick collects it and, privately, calls it rent. Each keeps their paper somewhere dry, and each knows the other's paper is exactly as good.
+
 ## 🔗 Connected Notes 
```
