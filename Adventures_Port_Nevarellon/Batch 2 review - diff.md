# Batch 2 — Factual fixes + Morgran revision (review diff)

**Nothing has been written to the vault.** Part A and Part B can be approved separately.

**Judgement calls to check**
- **Moonlight:** the newer Coastal Reckoning wins. If the sun stops existing at night, the moons can't be reflecting it, so the Celestial Graveyard now gives them their own faint glow.
- **Unwritten Day:** three attempts have failed, all Marrenhal's and all in the last eleven years; her fourth is live. This matches her file and Kress's.
- **Palla:** elected at the Council's first sitting and has held the seat for all 58 years.
- **Dray:** arrived at 40, 78 years ago, and has been Keeper for the last 31 of them.
- **Sallow:** sixty tons a month (1,200 people × about 1.6 kg a day).
- **Longlight / Highsun:** kept, with one line on why the names don't contradict the sun mechanics. This is the only new explanation in Part A.
- **Iron-Anchor epigraph:** reassigned from "Councilman Henderson" to Ottavian Kress, who is the Docks' man and fits the line.
- **Rusty Tankard / Kaleb:** policing in the Basin is now the Golden Company's, per the Basin doc.

**Not in this batch:** the canon tracker (Batch 4); Blue-Cloak Watch, Aer estuary and Tuwal Ghorun (Batch 2b); link fixes (Batch 3).

**Apply sequence:** same as Batch 1 — check against a fresh copy → write with the change-detection guard → read back.
**After the write (you, in Obsidian):** I'd move Morgran's file from `203 Historical & Mythic Figures` to `202 The Underworld`, since he's alive and working.

---

## Part A — Batch 2a factual fixes (20 files)

Corrections only. Where two documents disagreed, the newer one wins. `-` lines are the current text; `+` lines are the proposed text.

### `000 Atlas/003 Sub-Locations & Architecture/Greywater Lagoon.md`

```diff
@@ -23,3 +23,3 @@
 - **Regular Patrons:** Rogue merchantmen, mutinous naval crews, smugglers running contraband into [[The Inner Sea|The Inner Sea]], and buyers from the [[The Iron-Anchor Syndicate|Iron-Anchor Syndicate]] looking to bypass Port Nevarellon's tariffs.
-- **Primary Income:** The lagoon is the ultimate fencing floor. Pirates offload stolen silks, spices, and Imperial gold. In return, they buy the only thing they can't steal on the open ocean: fresh water, safe harbor, and repairs using Divtown's rot-resistant timber.
+- **Primary Income:** The lagoon is the ultimate fencing floor. Pirates offload stolen silks, spices, and Twelgorn gold. In return, they buy the only thing they can't steal on the open ocean: fresh water, safe harbor, and repairs using Divtown's rot-resistant timber.
 - **The Washing of the Coin:** Goods are offloaded here, logged by [[200 Cast/Tahra Beyr|Tahra Beyr]], stamped with Lord Thorne's noble seal as "legally salvaged marsh-wreckage," and then rowed north into the city as legitimate merchandise.
```

### `000 Atlas/003 Sub-Locations & Architecture/The Rusty Tankard.md`

```diff
@@ -25,3 +25,3 @@
 ## 💰 Atmosphere & Economy
-- **The Prices:** A pint of sour, watered-down harbor ale costs **2 cp**. A plate of salted herring and gray bread costs **1 cp**. Because the tavern sits within the Basin district, Un-Landed laborers frequently spend their entire daily earnings here just to stay indoors and avoid being picked up by the Golden Company for vagrancy after dark.
+- **The Prices:** A pint of sour, watered-down harbor ale costs **2 cp**. A plate of salted herring and gray bread costs **1 cp**. Because the tavern sits within the Basin district, Un-Landed laborers frequently spend their entire daily earnings here in the last hours before the curfew bell sends them back out through the Toll Gates.
 - **The Custom:** Open weapons are strictly forbidden inside the premises, conforming to the city's weapon laws. However, almost every patron has a palm-length rigging knife slipped into their boot or an iron-weighted sap hidden in their sleeve.
@@ -33,4 +33,4 @@
 
-- **[[200 Cast/Kaleb the Barkeep|Kaleb]]:** The manager and gatekeeper. She operates the dead-drops and assigns odd jobs to trusted syndicate freelancers.
-- **[[200 Cast/Maccorrack|Maccorrack]]:** A massive half-orc stevedore who practically lives here. Beyond drinking and working as occasional hired muscle for Kaleb's smuggling runs, Maccorrack fights in the Tankard's regular, brutal bare-knuckle bar brawls for extra coin. Kaleb actually encourages these brawls—the noise and spilled blood convince the local watch that the Tankard is just a standard low-class dive, drawing attention away from the quiet, high-stakes smuggling in the cellar.
+- **[[200 Cast/Kaleb the Barkeep|Kaleb]]:** The manager and gatekeeper. He operates the dead-drops and assigns odd jobs to trusted syndicate freelancers.
+- **[[200 Cast/Maccorrack|Maccorrack]]:** A massive half-orc stevedore who practically lives here. Beyond drinking and working as occasional hired muscle for Kaleb's smuggling runs, Maccorrack fights in the Tankard's regular, brutal bare-knuckle bar brawls for extra coin. Kaleb actually encourages these brawls—the noise and spilled blood convince the Company patrols that the Tankard is just a standard low-class dive, drawing attention away from the quiet, high-stakes smuggling in the cellar.
 - **[[200 Cast/Lidda Shoon|Lidda Shoon]]:** The halfling jeweler frequently uses the shadowy corner booths to discreetly fence her melted-down gold and stolen gems. She treats the Tankard as her primary dispatch point for picking up new, illicit contracts from the Syndicate.
```

### `100 Society/101 Factions & Guilds/Council of Five.md`

```diff
@@ -31,3 +31,3 @@
   - **The Contract expires in 41 years and there is no succession plan.** Only [[Marcian Thole]] treats this as urgent
-  - **The Unwritten Day.** The 365th day belongs to no turn, and no instrument specifying a turn can fall due on it. Four attempts to close it have failed
+  - **The Unwritten Day.** The 365th day belongs to no turn, and no instrument specifying a turn can fall due on it. Three attempts to close it have failed; a fourth is before the chamber now
   - **The Tuwal Ghorun identity void.** Southern instruments name a polity no coastal register lists. It cannot be resolved, and one councillor is actively ensuring it never is
@@ -39,3 +39,3 @@
 
-**The consequence is that any two councillors can block anything that matters, indefinitely, without ever making an argument.** This is not a flaw the Council is working around. It is the load-bearing reason the Vagrancy Tolls have never been repealed, the curtain wall at [[The Foundry Slips]] has never been surveyed, the Scar-Holders have never been recognised, and the Unwritten Day is still standing after four attempts by the most capable administrator in the city.
+**The consequence is that any two councillors can block anything that matters, indefinitely, without ever making an argument.** This is not a flaw the Council is working around. It is the load-bearing reason the Vagrancy Tolls have never been repealed, the curtain wall at [[The Foundry Slips]] has never been surveyed, the Scar-Holders have never been recognised, and the Unwritten Day is still standing after three attempts by the most capable administrator in the city.
 
@@ -53,3 +53,3 @@
 - [[Verrine Sallow]] — *The Contract Seat.* The Golden Company, the Contract Sum, defence. Human, 39. Feeds twelve hundred halberds; the only councillor who has read the Contract to the end
-- [[Palla Vantry]] — *The Long Seat.* Foreign trade, the sea-lanes, the south. Elf, 214. Elected continuously for eighty years, has claimed nothing, and cannot be confirmed or removed by any court that exists
+- [[Palla Vantry]] — *The Long Seat.* Foreign trade, the sea-lanes, the south. Elf, 214. Elected at the Council's first sitting and continuously since — fifty-eight years, has claimed nothing, and cannot be confirmed or removed by any court that exists
 
```

### `100 Society/101 Factions & Guilds/The Golden Company.md`

```diff
@@ -70,3 +70,3 @@
   - **Fiscal dependency:** the Contract Sum is drawn from the same trade economy the [[The Iron-Anchor Syndicate|Iron-Anchor Syndicate]] depends on. A serious disruption to Port Nevarellon's trade doesn't just hurt merchants — it threatens the Company's own pay.
-  - **The Chalced Question:** the Contract's founding purpose was suppressing a *domestic* return to kingship. Whether it legally obligates the Company to fight a full-scale invasion by the exiled [[100 Society/The Chalced Kingdom|Chalced]] royal line is genuinely unsettled — a gap High Captain Marco is quietly aware of and deeply unsettled by (hence his watching "the northern sky").
+  - **The Twelgorn Question:** the Contract's founding purpose was suppressing a *domestic* return to kingship. Whether it obligates the Company to fight a foreign invasion by the [[000 Atlas/The Twelgorn Kingdom|Twelgorn Kingdom]] — even one carrying the exiled royal claimant in its baggage train — is unsettled, and the invasion would be unambiguously foreign. High Captain Marco is quietly aware of the gap; [[Verrine Sallow]] is paying advocates to find out how wide it is.
   - **The Recruitment Fault Line:** as more of the rank and file are raised from the very districts they're ordered to police, quiet reluctance and small mercies are becoming more common lower in the ranks than the Officer Corps would like to admit.
```

### `100 Society/101 Factions & Guilds/The Iron-Anchor Syndicate.md`

```diff
@@ -3,3 +3,3 @@
 
-> "The City Watch keeps the peace in the plazas, but the Syndicate keeps the ships moving. Displace them, and the whole port starves in a fortnight." — Councilman Henderson
+> "The City Watch keeps the peace in the plazas, but the Syndicate keeps the ships moving. Displace them, and the whole port starves in a fortnight." — Ottavian Kress, the Water Seat
 
@@ -30,3 +30,3 @@
 - **External Rivals:** [[100 Society/The Tidespoken Clergy|The Tidespoken Clergy]] (who actively undermine Syndicate recruitment by feeding and protecting the poorest dockworkers).
-- **Public Perception:** Feared by the merchants, loathed by the nobility, but viewed by many impoverished dockworkers as a necessary shield against the tyrannical taxes of the city's crown.
+- **Public Perception:** Feared by the merchants, loathed by the nobility, but viewed by many impoverished dockworkers as a necessary shield against the tyrannical tolls of the Council.
 
```

### `100 Society/101 Factions & Guilds/The Wyvern tail Pirates.md`

```diff
@@ -19,4 +19,4 @@
 
-- **Shallow-Draft Tacticians:** Haren’s crews utilize heavy, deep-sea warships that have been heavily modified by [[000 Atlas/Divtown|Divtown]] shipwrights. By stripping away heavy iron hull-plating and replacing it with lightweight, rot-resistant **Iron-Burl** timber, her ships sit incredibly high in the water. This allows them to lure the deep-draft, iron-clad warships of the southern empire into the shifting sandbars of [[000 Atlas/The Silted Marshes|The Silted Marshes]], where the heavier vessels run aground and become defenseless targets.
-- **The Economic Alliance:** The fleet maintains a strict, symbiotic relationship with [[200 Cast/Lord Kelf Thorne|Lord Kelf Thorne]]. They unload massive hauls of plundered Imperial silks, spices, and bullion into the lagoon. Once Thorne washes the cargo using his noble wax seals, Haren's agents receive clean **Silver Pieces** and high-grade provisions, completely bypassing the taxes of Port Nevarellon.
+- **Shallow-Draft Tacticians:** Haren’s crews utilize heavy, deep-sea warships that have been heavily modified by [[000 Atlas/Divtown|Divtown]] shipwrights. By stripping away heavy iron hull-plating and replacing it with lightweight, rot-resistant **Iron-Burl** timber, her ships sit incredibly high in the water. This allows them to lure the deep-draft, iron-clad warships of the Twelgorn navy into the shifting sandbars of [[000 Atlas/The Silted Marshes|The Silted Marshes]], where the heavier vessels run aground and become defenseless targets.
+- **The Economic Alliance:** The fleet maintains a strict, symbiotic relationship with [[200 Cast/Lord Kelf Thorne|Lord Kelf Thorne]]. They unload massive hauls of plundered Twelgorn silks, spices, and bullion into the lagoon. Once Thorne washes the cargo using his noble wax seals, Haren's agents receive clean **Silver Pieces** and high-grade provisions, completely bypassing the taxes of Port Nevarellon.
 
```

### `100 Society/102 Lore & History/History - The Broken Crown of Austhal.md`

```diff
@@ -9,3 +9,3 @@
 The known world for the mortal races in this sector of the Infinite Disk is the vast continent of **Austhal**. 
-- Centurires have passed since the breaking of the cosmic sphere. 
+- Centuries have passed since the breaking of the cosmic sphere. 
 - The truth of the deicide, the shattering of the Sphere into the Tideways, and the cosmic war has completely faded out of mortal memory. 
@@ -22,3 +22,3 @@
    - **The North:** The treacherous peaks of [[The Jagged Spine|The Jagged Spine Range]].
-   - **The East:** The dwarven realm of [[Ubaraz Kingdom|The Ubaraz Kingdom]], dug beneath the Lonely Mountain.
+   - **The East:** The dwarven realm of [[Ubaraz Kingdom|The Ubaraz Kingdom]], dug deep into its mountain halls.
    - **The South:** The toxic, waterlogged expanse of [[Silted Marshes|The Silted Marshes]].
@@ -54,7 +54,7 @@
 4. **The Ultimate Law:** The absolute, unshakeable law of the Accord dictates that **no mortal may ever hold or claim the moniker of "King"** within the boundaries of the Whispering Coast again. --- 
-## ⚓ The Realism-Fantasy Intersect for Your Vault 
+## ⚓ The Realism-Fantasy Intersect 
 ### 1. The Mercenary State Balance 
-Because the city is enforced by the Golden Company under a 99-year lease, the **Blue-Cloak Watch** we mentioned in the docks are actually subordinates or cheap local recruits overseen by this elite foreign mercenary corporation. The Golden Company doesn't care about street-level crime in the docks; they care about tax revenue, harbor defense, and making sure the contract is paid on time. 
+Because the city is enforced by the Golden Company under a 99-year lease, the **Blue-Cloak Watch** of the lower districts are subordinates or cheap local recruits overseen by this elite foreign mercenary corporation. The Golden Company doesn't care about street-level crime in the docks; they care about tax revenue, harbor defense, and making sure the contract is paid on time. 
 ### 2. The Golden Company vs. The Syndicate 
-Think about the tension this creates! **Garrick the Keelhauler** wants to turn his Syndicate into a legitimate "Logistics Guild." To do that, he has to wait out or corrupt the Golden Company's contract, because a hyper-professional mercenary army cannot be easily intimidated by common dockyard thugs. Meanwhile, **Silas Bane**'s violent chaos risks bringing the full, lethal weight of the Golden Company down on the Muddy Docks. 
+**Garrick the Keelhauler** wants to turn his Syndicate into a legitimate "Logistics Guild." To do that, he has to wait out or corrupt the Golden Company's contract, because a hyper-professional mercenary army cannot be easily intimidated by common dockyard thugs. Meanwhile, **Silas Bane**'s violent chaos risks bringing the full, lethal weight of the Golden Company down on the Muddy Docks. 
 ### 3. The Threat from the South: The Twelgorn Kingdom
```

### `100 Society/102 Lore & History/Law - The Council's Edicts.md`

```diff
@@ -3,3 +3,3 @@
 
-> "A sword in the hand of a man with no property is a rebellion. A sword in the hand of a man who owns a warehouse is an asset protection strategy." — Chief Magistrate of the Council of Five
+> "A sword in the hand of a man with no property is a rebellion. A sword in the hand of a man who owns a warehouse is an asset protection strategy." — a magistrate of the High Courts
 
```

### `100 Society/104 Cosmology/Cosmology - The Celestial Graveyard and The war of Creation.md`

```diff
@@ -10,3 +10,3 @@
 - **The Sun:** The brilliant, burning corpse of a primary Creator entity. Its light is a fading, radiating echo of the original infinite energy that powered the Sphere.
-- **The Moons:** The frozen, pale remnants of secondary entities. Because they are dead flesh drifting in the Void, they reflect the sun's fading energy, their cycles casting shifting, borrowed hues of light onto the Disk below.
+- **The Moons:** The frozen, pale remnants of secondary entities. They are dead flesh drifting in the Void, and they still give off a faint glow of their own — which is why they remain visible when the sun has faded out of the sky. Their cycles cast shifting hues of light onto the Disk below.
 
```

### `200 Cast/201 Nobility & Elites/Marcian Thole.md`

```diff
@@ -13,3 +13,3 @@
 ## ⚖️ Realism & Physicality
-- **Age & Vitality:** Human, 58. Broad, stooped, and visibly worn out. He looks a decade older than Lucia Marrenhal despite being fourteen years her senior in a way that reads as *labour*, not age
+- **Age & Vitality:** Human, 58. Broad, stooped, and visibly worn out. He is fourteen years Lucia Marrenhal's senior and looks nearer thirty, in a way that reads as *labour*, not age
 - **Physical Flaws / Limitations:** Substantially deaf from thirty years of caulking hammers in enclosed hulls — he reads lips and turns his good ear like a man aiming it. Three fingers on his left hand set wrong after a spar crushed them. He cannot hear a whispered aside in the chamber, which means he cannot hear the deals being made across him, and everyone knows it
```

### `200 Cast/201 Nobility & Elites/Palla Vantry.md`

```diff
@@ -20,3 +20,3 @@
 - **Immediate Goal:** Nothing urgent, and this is not a failure of the character — it is the character. Her working horizon is the **Contract expiry in 41 years**, which she fully expects to attend
-- **The Core Fear:** Being named. Not exposed — *named*. The Ducal Accord's ultimate law forbids any mortal claiming the moniker of King, and Palla Vantry has held one-fifth of a sovereign city's government for eighty years by continuous free election. She has claimed nothing. She has never needed to. She is acutely aware that the [[Religion - The pagan Pantheon and the Faith Domains|Cult of the Zenith]] could void her seat for irregularity and could never validate it either, and that the day someone puts the word to what she is, the Court of Nullity becomes the only venue in the world and it has exactly one setting
+- **The Core Fear:** Being named. Not exposed — *named*. The Ducal Accord's ultimate law forbids any mortal claiming the moniker of King, and Palla Vantry has held one-fifth of a sovereign city's government for fifty-eight years by continuous free election. She has claimed nothing. She has never needed to. She is acutely aware that the [[Religion - The pagan Pantheon and the Faith Domains|Cult of the Zenith]] could void her seat for irregularity and could never validate it either, and that the day someone puts the word to what she is, the Court of Nullity becomes the only venue in the world and it has exactly one setting
 - **Moral Compromises:** The Long Seat handles external trade, and external trade includes **Tuwal Ghorun**. She has spent decades ensuring the identity void between *Tuwal Ghorun* and *Twelgorn* is never resolved, because an unresolved polity cannot be formally traded with, formally taxed, or formally condemned — and the Vantry houses have moved southern goods through that gap for her entire tenure. Every escaped slave in [[Divtown]] whose Retriever's writ is unenforceable owes that to the same void that launders her cargo. She is aware of this symmetry and has never once used it as a defence
@@ -24,3 +24,3 @@
 ## 📜 Backstory & Current Role
-She was 156 and a junior factor of a middling house when the merchants hired the Golden Company. She watched the King die, watched the Accord drafted, and watched five families decide that the greatest danger to a republic is any one person accumulating unchallenged power. They wrote the **four-of-five rule** to prevent it. She has spent eighty years demonstrating that a rule against combination is not a rule against *duration*.
+She was 156 and a junior factor of a middling house when the merchants hired the Golden Company. She watched the King die, watched the Accord drafted, and watched five families decide that the greatest danger to a republic is any one person accumulating unchallenged power. They wrote the **four-of-five rule** to prevent it. She has spent fifty-eight years demonstrating that a rule against combination is not a rule against *duration*.
 
@@ -30,3 +30,3 @@
 
-**The mote, such as it is:** she is the only member of the Council who remembers what the King was actually like. When Kress makes a populist speech about the tyranny of the merchants, she does not correct him, and she does not vote against him either. She has been quietly, invisibly moderating the Council's worst instincts for eighty years by simply declining to finish considering them — and she is the single largest obstacle to anything ever improving. Both of those are the same behaviour.
+**The mote, such as it is:** she is the only member of the Council who remembers what the King was actually like. When Kress makes a populist speech about the tyranny of the merchants, she does not correct him, and she does not vote against him either. She has been quietly, invisibly moderating the Council's worst instincts for fifty-eight years by simply declining to finish considering them — and she is the single largest obstacle to anything ever improving. Both of those are the same behaviour.
 
```

### `200 Cast/201 Nobility & Elites/Verrine Sallow.md`

```diff
@@ -24,3 +24,3 @@
 ## 📜 Backstory & Current Role
-Vess Sallow was a warehouse clerk's daughter who noticed, at nineteen, that twelve hundred soldiers require eleven tons of food a month and that nobody had organised it properly. She spent fifteen years making herself unavoidable to the Company's quartermasters and then bought a deed with the proceeds.
+Vess Sallow was a warehouse clerk's daughter who noticed, at nineteen, that twelve hundred soldiers require sixty tons of food a month and that nobody had organised it properly. She spent fifteen years making herself unavoidable to the Company's quartermasters and then bought a deed with the proceeds.
 
```

### `200 Cast/202 The Underworld/Captain Haren Twarde.md`

```diff
@@ -21,3 +21,3 @@
 ## 🧠 Psychology & Drive
-- **Immediate Goal:** Intercept the upcoming seasonal Imperial payroll convoy before it reaches the naval garrisons on the southern edge of the marshes.
+- **Immediate Goal:** Intercept the upcoming seasonal Twelgorn payroll convoy before it reaches the naval garrisons on the southern edge of the marshes.
 - **The Core Fear:** Being trapped or cornered in enclosed waters where her tactical mobility is neutralized. She deeply understands that her power relies entirely on the freedom of open water and the camouflage of the swamp.
```

### `200 Cast/202 The Underworld/Garrick the Keelhauler.md`

```diff
@@ -3,3 +3,3 @@
 
-> "A pirate hangs from the gibbet because he wants to steal a ship. Garrick dines on silver plate because he chose to buy the harbor." — Archon Sterling, High Quarter Court
+> "A pirate hangs from the gibbet because he wants to steal a ship. Garrick dines on silver plate because he chose to buy the harbor." — overheard in the High Courts
 
@@ -29,3 +29,3 @@
 ## 🤫 Current Conflict: The Shaking Anchor
-Garrick’s greatest struggle is age. His body is failing, and his pragmatism is being misread as weakness by the younger generation. He spends more time analyzing trade sheets and balancing bribe ledgers than cracking skulls. He knows [[Silas Bane|Silas]] wants his seat, but Garrick is playing a longer game—he is currently negotiating with certain corrupt nobles to fully legitimize the Syndicate into an official "Maritime Logistics Guild," which would permanently shield his wealth under royal law.
+Garrick’s greatest struggle is age. His body is failing, and his pragmatism is being misread as weakness by the younger generation. He spends more time analyzing trade sheets and balancing bribe ledgers than cracking skulls. He knows [[Silas Bane|Silas]] wants his seat, but Garrick is playing a longer game—he is currently negotiating with certain corrupt nobles to fully legitimize the Syndicate into an official "Maritime Logistics Guild," which would permanently shield his wealth under the Council's own charters.
 
```

### `200 Cast/202 The Underworld/Kaleb.md`

```diff
@@ -8,3 +8,3 @@
 ## 📊 Vital Statistics
-- **Full Name / Aliases:** Kaleb / "The Lock-Smith" (Old alias from her younger days).
+- **Full Name / Aliases:** Kaleb / "The Lock-Smith" (Old alias from his younger days).
 - **Current Occupation:** Barkeep and Manager of [[000 Atlas/The Rusty Tankard|The Rusty Tankard]].
@@ -32,2 +32,2 @@
 - **Faction Network:** [[100 Society/The Cobalt Feather Syndicate|The Cobalt Feather Syndicate]]
-- **The Threat:** [[100 Society/The Civic Constabulary|The Civic Constabulary]] (He keeps a specialized jar of counterfeit copper pennies behind the bar specifically to buy off the local Watch sergeants who poke their noses too close to his cellar).
+- **The Threat:** [[The Golden Company|The Golden Company]]'s Basin patrols (He keeps a specialized jar of counterfeit copper pennies behind the bar specifically to buy off the locally-raised Company sergeants who poke their noses too close to his cellar).
```

### `200 Cast/202 The Underworld/Silas Bane.md`

```diff
@@ -20,3 +20,3 @@
 - **Immediate Goal:** Seize absolute control of the **Bioluminescent Lantern Monopolies** in the lower districts, weaponizing the resource against the upper city.
-- **The Core Fear:** Being trapped beneath a ceiling. Silas despises the idea of a slow, pragmatic transition into "legitimacy." He genuinely believes that if the Syndicate tries to become a legal guild under the crown, the nobles will strip them of their true power and executioner's edge.
+- **The Core Fear:** Being trapped beneath a ceiling. Silas despises the idea of a slow, pragmatic transition into "legitimacy." He genuinely believes that if the Syndicate tries to become a legal guild under the Council's charters, the nobles will strip them of their true power and executioner's edge.
 - **Moral Compromises:** Completely unhinged by cruelty. Where Garrick uses violence as a precise ledger correction, Silas uses it as performance art. He has ordered public flayings on the boardwalks, used experimental chemical agents on debtors, and treats his own street muscle as entirely disposable resources.
```

### `200 Cast/204 Middle Class/Keeper Merrit Dray.md`

```diff
@@ -20,3 +20,3 @@
 - **Immediate Goal:** **A successor, and there isn't one.** The Copyists are lay and unordained. The Notaries are competent and twenty-six. The one Keeper senior enough for the post is High Quarter-born and would hand the vault to whoever asked nicely and dressed well. Dray has been quietly training a Notary from the Foundry Slips for two years without telling her what for
-- **The Core Fear:** **Being asked directly.** Not exposure — he has no fear of being investigated, because he has left nothing to find. But he has spent a hundred and eighteen years on the accuracy of records, and if an Arbiter stands in front of him and asks plainly whether he delayed that verification, **he will say yes.** He will not construct a lie. Everything after that is arithmetic
+- **The Core Fear:** **Being asked directly.** Not exposure — he has no fear of being investigated, because he has left nothing to find. But he has spent seventy-eight years on the accuracy of records, and if an Arbiter stands in front of him and asks plainly whether he delayed that verification, **he will say yes.** He will not construct a lie. Everything after that is arithmetic
 - **Moral Compromises:** Precisely one, and it took eleven weeks. See below
@@ -24,3 +24,3 @@
 ## 📜 Backstory & Current Role
-A hauler's son from a Stonereach village who came down to the coast at forty with a good hand and no prospects, took a Copyist's bench because it was indoor work, and was promoted for the only quality the Zenith reliably rewards in the low-born: he was never once wrong. Thirty-one years later he holds the vault.
+A hauler's son from a Stonereach village who came down to the coast at forty with a good hand and no prospects, took a Copyist's bench because it was indoor work, and was promoted for the only quality the Zenith reliably rewards in the low-born: he was never once wrong. That was seventy-eight years ago. He has held the vault for the last thirty-one of them.
 
```

### `400 Meta/Framework - The Coastal Reckoning.md`

```diff
@@ -60,3 +60,3 @@
 
-To every faith on the coast, and to a great many people with no faith at all, this is the plain daily fact of existence: the light went out, and it was under no obligation to return, and it did. Nobody has ever been owed a morning. Fifty-eight years of Accord, a hundred generations of settlement, and an entire dead pantheon rotting in the sky — and the reprieve has arrived every single time so far.
+To every faith on the coast, and to a great many people with no faith at all, this is the plain daily fact of existence: the light went out, and it was under no obligation to return, and it did. Nobody has ever been owed a morning. Fifty-eight years of Accord, a few centuries of settlement, and an entire dead pantheon rotting in the sky — and the reprieve has arrived every single time so far.
 
@@ -106,2 +106,4 @@
 
+**Longlight** and **Highsun** look like mistakes and are not. The light lasts no longer in those turns than in any other — but with the moons riding high, the weight comes off the world, the days feel long and warm, and the farmers who named the turns named what they felt.
+
 ---
@@ -119,3 +121,3 @@
 
-The [[Council of Five|Council of Five]] has attempted to absorb the day into Hollow or Ashfall four times in fifty-eight years. Each attempt failed, twice loudly. **The Toll Amnesty** *(Table 3, #3)* is what the Council calls its annual defeat — a mercy announced from the steps, granted with great ceremony, and legally unavoidable.
+The [[Council of Five|Council of Five]] has attempted to absorb the day into Hollow or Ashfall three times in fifty-eight years — all three in the last eleven, all three [[Lucia Marrenhal|Marrenhal]]'s — and each failed, twice loudly. Her fourth is before the chamber now. **The Toll Amnesty** *(Table 3, #3)* is what the Council calls its annual defeat — a mercy announced from the steps, granted with great ceremony, and legally unavoidable.
 
```

### `400 Meta/Reference - Name Tables.md`

```diff
@@ -11,3 +11,3 @@
 
-**Nothing in these tables contradicts an existing document.** Where an entry deliberately extends canon (Concord Road waystations, Corvus Scar ruins, Spine Aqueduct settlements), it's marked *→ extension* and noted in the Flags section at the end.
+**Nothing in these tables contradicts an existing document.** Where an entry deliberately extends canon (Concord Road waystations, Corvus Scar ruins, Spine Aqueduct settlements), it's marked *→ extension* inline.
 
@@ -81,11 +81,11 @@
 | 19 | Corran Ossius | B | Third son of a minor Landed house; no inheritance, expensive tastes |
-| 20 | Lucia Marrenhal | B | Banking-house factor in the Trade Plazas |
+| 20 | Lucia Marrenhal | B | *(allocated — canon: Councillor, the Writ Seat)* |
 | 21 | Deverus Aleth | B | Magistrate; sells adjournments, not verdicts |
-| 22 | Verrine Sallow | B | Latinised *Sallow* — bought a deed nine years ago and everyone remembers |
-| 23 | Ottavian Kress | B | Guild-Master of the coopers; sponsors Un-Landed grievances for a cut |
+| 22 | Verrine Sallow | B | *(allocated — canon: Councillor, the Contract Seat)* |
+| 23 | Ottavian Kress | B | *(allocated — canon: Councillor, the Water Seat)* |
 | 24 | Serrian De Vonce | B | Cadet branch of the Iron Court, kept far from the succession |
-| 25 | Palla Vantry | B | Distant kin to Isolde; born Landed and resents the comparison |
+| 25 | Palla Vantry | B | *(allocated — canon: Councillor, the Long Seat)* |
 | 26 | Halcus Rive | B | Guild of Alchemists assessor, licences Brine-Glow lanterns |
 | 27 | Ysolde Corran | B | Deliberate near-miss on Isolde Vantry; a social climber's chosen name |
-| 28 | Marcian Thole | B | Shipwright house; owns a deep-water keel and therefore a vote |
+| 28 | Marcian Thole | B | *(allocated — canon: Councillor, the Harbour Seat)* |
 | 29 | Rashid Al Deyr | C | Twelgorn-born tally-clerk; came north legally and is trusted by nobody |
@@ -216,3 +216,3 @@
 
-**Trigger** states when it fires. The coastal year currently has no formal calendar — see Flag 7. Until it does, seasonal entries hang off the three canon markers: the **spring trade season**, the **Winter Moons**, and the **Low Moons**.
+**Trigger** states when it fires. Dates follow [[Framework - The Coastal Reckoning]]; seasonal entries hang off its three canon markers: the **spring trade season**, the **Winter Moons**, and the **Low Moons**.
 
@@ -287,3 +287,3 @@
 | 8 | Thraw | Peak | Stonereach; gives its name to the pass |
-| 9 | Broken Ward | Peak | Corvus Scar; the peak that fell → *canon: Corvus Spire* |
+| 9 | Broken Ward | Fallen peak | Corvus Scar; the folk name for the stump. The peak itself was Corvus Spire, and the seat cut into it took its name → *canon: Corvus Spire* |
 | 10 | Thraw's Pass | Mountain pass | Stonereach; the northeast trade artery |
```

### `400 Meta/Reference - The Wondrous Markets.md`

```diff
@@ -66,3 +66,3 @@
 
-⚠️ **Hook, not asserted.** [[Palla Vantry]] is 214 and has held the Long Seat for eighty years. If the Fourth was struck inside her tenure, she was in a position to be the connection. That is not written anywhere and should probably stay that way until someone goes looking.
+⚠️ **Hook, not asserted.** [[Palla Vantry]] is 214 and has held the Long Seat for all fifty-eight years of the Accord. If the Fourth was struck inside her tenure, she was in a position to be the connection. That is not written anywhere and should probably stay that way until someone goes looking.
 
```

## Part B — Morgran revision and the Slack-Born (5 files)

New lore from your Morgran decisions. Read this part for tone. Shown against the Part A result.

### `000 Atlas/001 Regions & Continents/Silted Marshes.md`

```diff
@@ -18,2 +18,3 @@
 - **Settlements/Points of Interest:**
+  - **Fenmouth** — *Guide Village & Council Toll Post.* At the mouth of the marsh, where hiring a marsh-guide is required by law. Base of [[Morgran the Abomination|Morgran]].
   - [[Divtown|Divtown]] — *Smuggler's Shanty Town / Logging Outpost.* A derelict refuge built on stilts, populated by escaped slaves and the truly hopeless.
```

### `000 Atlas/002 Cities & Settlements/Divtown.md`

```diff
@@ -14,3 +14,3 @@
 - **Architecture:** A chaotic, derelict sprawl of shanties, stilt-houses, and rope bridges suspended above the brackish, sucking mud of the marshes. It is constantly sinking and being rebuilt.
-- **Access & Navigation:** Divtown is incredibly difficult to reach by land or sea. The labyrinthine waterways are choked with constantly shifting sandbars. To reach the town, one must hire local fisher-folk from the mouth of the marsh, or seek out a specific, cursed dwarven guide residing in [[000 Atlas/Oakhaven Cove|Oakhaven]].
+- **Access & Navigation:** Divtown is incredibly difficult to reach by land or sea. The labyrinthine waterways are choked with constantly shifting sandbars. To reach the town, one must hire local fisher-folk from the mouth of the marsh, or seek out a specific, cursed dwarven guide working out of **Fenmouth**, the marsh-mouth village where hiring a guide is required by law.
 - **Neighboring Locations:** Directly borders the [[000 Atlas/Grey Water Lagoon|Grey Water Lagoon]], a deep-water blind spot hidden from the Golden Company where pirate galleons drop anchor.
```

### `100 Society/104 Cosmology/Cosmology - The Great Fracture.md`

```diff
@@ -52 +52,10 @@
 **A note on the labels:** "Good" and "Evil" are mortal words laid over the High Reach and the Undertow after the fact, the same way mortal Ego and Identity were laid over the nameless entities during the Naming. The Reach and the Undertow are not inherently virtuous or wicked — they are simply where mortal collective feeling pulled the wreckage. A saint of the Reach can be a butcher who happened to die convinced he was righteous. A thing that crawled up out of the Undertow can be the only creature that ever told a slave the truth. Nothing in the Tideways is required to be good just because it floats, or evil just because it sinks.
+
+---
+
+## 🌿 The Slack-Born: Fey and Hags
+Not all the god-essence that settled in the Slack Water sank into stone and silt as shards. Where it pooled in still places — marsh, tarn, sheltered reef, the drowned edges of old forests — some of it quickened. **The fey** are what quickened: beings formed from essence that neither rose to the High Reach nor sank to the Undertow, and so belong wholly to the still water of the world. They are not a mortal race. The Creators never designed them, and they had no part in the War of Creation. Most mortals never meet one; those who do find them beautiful, unhurried, and unconcerned with mortal purposes.
+
+**Hags** are humanoid fey — long-lived, rooted to a single place, and unlike the rest of their kind, willing to trade with mortals. Their stock in trade is change. A hag can work an Undertow-touched shard into living flesh, and will, for a price that is always paid in full.
+
+> *`needs crunch` — fey and hag stat blocks belong to the Iron & Marrow ruleset.*
```

### `200 Cast/203 Historical & Mythic Figures/Morgran the Abomination.md`

```diff
@@ -3,3 +3,3 @@
 
-> "Don't look at the scales. Just pour him another tankard of ale, pay him his silver, and follow his boat exactly where he tells you, or the Silt will eat your bones." — Advice given at Oakhaven Cove
+> "Don't look at the scales. Just pour him another tankard of ale, pay him his silver, and follow his boat exactly where he tells you, or the Silt will eat your bones." — Advice given at Fenmouth
 
@@ -7,10 +7,13 @@
 - **Full Name / Aliases:** Morgran Deep-Draught / "Fin" / The Abomination
-- **Current Occupation:** Navigator of the Silted Marshes / Town Drunk in [[000 Atlas/Oakhaven Cove|Oakhaven Cove]].
+- **Current Occupation:** Marsh-guide out of **Fenmouth** / the village drunk.
 - **Social Class / Standing:** Outcast / Feared Oddity.
-- **Primary Residence:** Sleeps under the drydock slips in Oakhaven Cove, but technically "lives" on his small, flat-bottomed skiff.
+- **Primary Residence:** His small, flat-bottomed skiff, moored at the far end of the Fenmouth guide-stage, where nobody else will tie up.
 
 ## ⚖️ Realism & Physicality
-- **Age & Vitality:** 112 years old (Dwarven). 
-- **The Curse (The Mutation):** Decades ago, Morgran was a prospector who dug too deep in the southern marshes and struck an unanchored, Undertow-touched god-shard buried deep beneath the marsh bed. The chaotic magic warped his dwarven biology. His lower jaw and neck are flared with pulsing, fish-like gills, and patches of thick, slimy gray scales cover his arms and torso. His eyes are entirely black, like a deep-sea predator. Fittingly, the curse didn't just change his body — it left a piece of the Undertow's pull inside him, which is likely why saltwater soothes the change and dry air makes it crack and bleed.
-- **Physical Flaws / Limitations:** He is a raging alcoholic. Because of his mutation, he must submerge himself in saltwater at least once a day or his skin begins to crack and bleed. He is universally shunned by his own people in [[000 Atlas/The Ubaraz Kingdom|The Ubaraz Kingdom]].
+- **Age & Vitality:** 112 years old (Dwarven).
+- **The Change (The Mutation):** Before he was the Abomination, Morgran ran a shallow-bottomed trading boat up and down the Grey Veins, carrying salt, needles, news and small debts between stilt-villages that have no other way of reaching each other. Somewhere in those channels he fell in love with one of the marsh fey — a creature of the Slack Water, and by every account he has ever given, the only thing in the Silt that was ever kind to him.
+  He was a dwarf and she belonged to the water, and he understood what that meant. So he went looking for an Undertow-touched god-shard, knowing exactly what such a shard can do to living flesh. When he found one, he carried it to a marsh hag and asked her to use it: to make him into something that could spend the rest of its life with the one he loved. The hag agreed. Hags always agree.
+  It worked. His lower jaw and neck flared into pulsing gills, thick grey scales spread across his arms and torso, and his eyes went entirely black. He could breathe the water she lived in. When she saw what he had become, she was disgusted. She rebuked him, and she was never seen again.
+  The change left a piece of the Undertow's pull inside him, which is likely why saltwater soothes it and dry air makes his skin crack and bleed. It did not come with a way back.
+- **Physical Flaws / Limitations:** He is a raging alcoholic. Because of the change, he must submerge himself in saltwater at least once a day or his skin begins to crack and bleed. He is shunned by his own people in [[000 Atlas/The Ubaraz Kingdom|The Ubaraz Kingdom]] — first for leaving the mountains for a marsh boat, and finally for what he let a hag make of him.
 - **Equipment & Upkeep:** Carries a specialized, heavy dwarven sounding-lead on a chain to test the depth of the shifting sandbars, and a perpetually empty iron flask.
@@ -19,3 +22,4 @@
 - **Immediate Goal:** Earn enough silver guiding smugglers into the Grey Water Lagoon to afford another week of heavy dwarven spirits.
-- **The Core Fear:** Being captured by the priests of [[100 Society/The Tidespoken Clergy|The Tidespoken Clergy]], who view him as a piece of the Undertow given flesh and want to burn him.
+- **The Core Fear:** Being captured by the priests of [[100 Society/The Tidespoken Clergy|The Tidespoken Clergy]]. They know a hag made him, they hold that anything shaped from an Undertow-shard belongs to the Undertow, and they want to burn him.
 - **The Utility:** Despite his tragic existence, Morgran is a savant of the Silt. He can taste the brackish water and tell you exactly where the sandbars have shifted overnight. Without him, heavy ships attempting to reach Divtown will inevitably run aground.
+- **The Mote:** Once a season he still makes the old trading run to the stilt-villages, at cost. They are the only people on the coast who call him Fin.
```

### `400 Meta/Reference - Name Tables.md`

```diff
@@ -24,5 +24,5 @@
 | **C — Southern (Twelgorn)** | Guttural, `Al-` patronymic particle, long back vowels. | Qasim Al Goor, Tahra Beyr | Twelgorn-born, escaped slaves, Retrievers |
-| **D — Dwarven** | Consonant-dense, no soft endings; a trade-lineage word replaces a surname. | *(none in canon — proposed)* | Oakhaven Cove, deep-mine work, the Spine |
+| **D — Dwarven** | Consonant-dense, no soft endings; a trade-lineage word replaces a surname. | Morgran Deep-Draught | Oakhaven Cove, deep-mine work, the Spine |
 | **E — Atoll (Elf / Halfling / mixed)** | Soft, liquid consonants, tidal imagery. **Weathered, not ethereal.** | *(none in canon — proposed)* | Shield Atolls stilt-villages, reef fisher communities |
-| **F — Half-Orc / Monstrous descent** | Mac-/Mor- prefixes, hard clusters. Often a single name — chattel status denied them lineage. | Maccorrack, Morgran | Escaped slaves, dock muscle, marsh outcasts |
+| **F — Half-Orc / Monstrous descent** | Mac-/Mor- prefixes, hard clusters. Often a single name — chattel status denied them lineage. | Maccorrack | Escaped slaves, dock muscle, marsh outcasts |
 | **B-e — Elf-descended Landed** | Register B house name, but the *given* name is liquid and multi-vowelled. Marks elven blood the bearer may be trying to downplay. | Sheandri De Vonce, Imaihil De Vonce | Half-elven nobility, chiefly House De Vonce |
```
