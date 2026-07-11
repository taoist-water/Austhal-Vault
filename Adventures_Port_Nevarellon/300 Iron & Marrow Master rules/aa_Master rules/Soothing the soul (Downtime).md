# Downtime: Settlements, Budgets, and Reputation

## 1.Pursuit Points (Replacing Literal Day-Counting)

Tracking exact calendar days across a party with different ongoing Endeavours gets unwieldy fast — especially once a Priest is spending a full day on Religious Pursuit  while the Fighter is mid-week into a Commission. Instead, the GM sets a **Downtime Budget** in **Pursuit  Points (PP)** based on the narrative gap between adventures, and each Pursuit  costs PP rather than literal days.

**Pursuit  Costs (PP):**

| Pursuit                                  | PP Cost |
| ---------------------------------------- | ------- |
| Acquisition (Restock/Purchase)           | 1 PP    |
| Tend to the Flesh (per Wound Slot cycle) | 1 PP    |
| Hammer & Forge (per item)                | 1 PP    |
| Religious Pursuit                        | 1 PP    |
| Commission                               | 3 PP    |
| Tinkerer's variant (feat-gated)          | 1 PP    |
| Bank Finances                            | 1 PP    |

**Example Budgets by Narrative Gap:**

- **A Single Night (1 PP):** The party makes camp in a waystation or sleeps at an inn before pushing on at dawn. Barely enough time for one quick Acquisition run or a single round of Tend to the Flesh.
- **A Few Days' Respite (3 PP):** The party has a short, clear break — recovering after a dungeon, waiting on a lead. Enough for a couple of Endeavours each, or one character to push hard on a single big one.
- **A Full Week in Town (5–7 PP):** The classic "return to town between dungeons" beat. Enough EP for most characters to run two or three Endeavours, or for one character to commit their whole budget to a Commission.
- **A Season of Downtime (10+ PP):** Used sparingly — between story arcs, over a winter, during travel to a new region. The GM should treat this as an explicit pacing tool, not a default, since it lets characters stack multiple Commissions or fully clear Locked Stress and gear damage across the whole party.

**The Rule:** Each character tracks their own PP budget independently — one character spending their whole budget on a Commission doesn't prevent another from running three small Endeavours in the same gap. This keeps downtime parallel rather than turn-based, matching how real "everyone goes off and does their own thing in town" play actually happens at the table.

________________________________________________________________________

##  2.Settlement Tiers (What's Even Possible Here)

Not every Pursuit  is available everywhere. A fishing hamlet has no master blacksmith to Commission from; a sprawling capital has no shortage of either. 

### Hamlet (Tier 0)
*A handful of families, maybe a shrine, no real market.*
- **Available Endeavours:** Tend to the Flesh, Religious Pursuit  (if the local shrine matches the Priest's tradition — GM's call), basic Acquisition (food, rope, torches, common-tier items only).
- **Unavailable:** Hammer & Forge (no forge), Commission (no master artisan).
- **Acquisition Modifier:** **-2** to the Acquisition check for Common-tier goods — a hamlet's stock is thin, and there's little room to haggle or substitute. Anything above Common isn't a modifier problem, it's a hard gate: automatically fails regardless of the roll — a hamlet simply doesn't stock Scarce, Rare, or Legendary goods, full stop.
### Town (Tier 1)
*A proper market square, a working forge, a temple or chapter house.*
- **Available Endeavours:** All of the above, plus Hammer & Forge and Acquisition up to Scarce availability, Finance bank.
- **Unavailable:** Commission, only available to 1 player(not enough artisans to service everyone at once), for anything above Masterwork (no legendary specialists here).
- **Acquisition Modifier:** None — this is the baseline, no bonus or penalty.

### City (Tier 2)
*A genuine trade hub. Guild halls, multiple forges, a cathedral.*
- **Available Endeavours:** All Endeavours, including Commission, fully available. Rare-tier Acquisition becomes possible.
- **Acquisition Modifier:** **+2** to Acquisition checks (competition between merchants works in the buyer's favor), but prices for Common goods may be inflated 10–20% at GM discretion (city premiums).

### Capital / Metropolis (Tier 3)
*The seat of power. Anything that exists, exists here.*
- **Available Endeavours:** Everything, including bespoke or one-of-a-kind Commissions the GM may gate behind a specific NPC artisan or a waiting list (a narrative hook, not a mechanical penalty).
- **Acquisition Modifier:** **+2**, and Rare-tier items no longer require a roll to locate — only to afford.

________________________________________________________________________

## 3.Settlement Reputation (The Demeanor Layer)

This directly mirrors the existing NPC Stance system, scaled up from a single person to an entire settlement's general disposition toward the party. It exists specifically so Influence-based skills and feats have somewhere to matter outside of combat and individual NPC negotiation 

**The Four Settlement Stances:** Hostile, Unfriendly, Neutral, Friendly — identical states and identical shift rules to the NPC Stance System (Standard Success shifts one step, High Success shifts two steps, never jumping straight to the opposite pole), applied collectively to a settlement's general disposition.

- **Hostile:** The party has actively wronged this settlement — botched a job, insulted the local lord, left a debt unpaid, or committed a crime that's become common knowledge. Acquisition checks suffer **-4**, Commission requests are refused outright regardless of payment, and most other Endeavours (Religious Pursuit  at a shrine whose faction the party has angered) may be denied entirely at GM discretion. This is the settlement actively working against the party, not just distrusting them.
- **Unfriendly:** The settlement is wary or has a poor opinion of the party — minor past friction, an unresolved rumor, simple distrust of outsiders — but isn't yet acting against them. Acquisition checks suffer **-2**. Most Endeavours remain available, just at worse terms; merchants quote higher prices, artisans are slower to commit to a Commission (requiring more EP to commission).
- **Neutral:** The default starting state for any settlement the party hasn't meaningfully interacted with yet. No modifier — this is the baseline the Settlement Tier modifiers above are written against.
- **Friendly:** The party has earned genuine goodwill — cleared a local threat, donated generously, performed a public service. Acquisition checks gain **+2** (stacking with Tier modifiers — a Friendly City offers a generous **+4** total), and Massive Successes become more frequent in practice simply because the combined modifier pushes more rolls past the Margin 5 threshold.

**Changing a Settlement's Stance:** Unlike an individual NPC, a settlement's stance shouldn't flip on a single Influence roll — it represents the aggregated opinion of dozens or hundreds of people, and should move the way reputation actually moves: slowly, and mostly through action rather than conversation.

- **The Single Roll Exception:** If the party is dealing with one clearly-defined authority who speaks for the settlement (a mayor, a guild master, a garrison captain), a standard opposed Influence vs. Resolve check against that NPC can shift the *settlement's* stance exactly as if they were shifting an individual's — because, narratively, they effectively are the settlement's gatekeeper. This is the fast path, and it's identical math to the existing Social Engine, just with a wider blast radius on the outcome.
- **The Slow Path (No Single Authority, or a Fractured Settlement):** Settlement stance shifts one level after the party completes a deed the GM rules is significant enough — clearing a dungeon threatening the town, publicly exposing a corrupt official, sponsoring a town festival. This is a narrative trigger, not a roll, deliberately mirroring how individual NPC trust-building sometimes bypasses dice entirely in favor of "you did the thing, the stance moves."

___________________________________________________________________

## Summary: How a Downtime Period Actually Resolves at the Table

1. The GM narrates the time gap and sets an **EP Budget** (Section 1).
2. The GM (or the players, by simply being somewhere already established) confirms the **Settlement Tier** (Section 2), which gates what's even on the menu and sets the baseline Acquisition modifier.
3. The GM checks the party's current **Settlement Reputation** with this specific settlement (Section 3) — Hostile/Unfriendly/Neutral/Friendly — which further modifies Acquisition and may gate or unlock specific Endeavours.
4. Each player spends their own EP budget across the Endeavours now available to them, rolling each as defined in the base Downtime Endeavours document.

This keeps the actual dice-facing procedure exactly as previously defined — nothing about *how a single Pursuit  resolves* has changed — while giving the GM three new dials (time, place, and standing) to make every return to town feel mechanically distinct rather than an identical menu regardless of where or when the party arrives.

___________________________________________________________________

# Downtime Pursuits

## The Base Procedure: Progress Momentum

Downtime uses the same Margin-driven logic as everything else in the system, scaled to a slower clock. Rather than resolving in seconds, a Downtime Pursuit resolves across hours, days, or weeks — but the dice still tell you how well it went.

- **The Mechanic:** When a character undertakes a named Downtime Pursuit , they make the check listed for that Pursuit  (almost always an unopposed roll against TN 8, exactly like the Margin of Manifestation used elsewhere in the system).
    
- **Failure (<8):** The Pursuit  does not complete this cycle. Time is lost — the character must spend the full duration again before attempting it a second time (this is what makes failure costly even without inflicting Stress or harm: it's a tempo loss, not a damage source).
    
- **Standard Success (Margin 0–4):** The Pursuit  completes exactly as described in its own entry.
    
- **Massive Success (Margin 5+):** The Pursuit  completes, and the character generates **1 Progress Momentum.**
    

**Progress Momentum** is a downtime-specific currency, mechanically separate from combat Momentum (it cannot be spent on Aggressor/Reactor maneuvers, and combat Momentum cannot be spent on downtime). It exists specifically to fuel the accelerants and quality-of-life feats that already reference it — *Focused Burst*, *Field Medic*, and others — and represents banked competence: a particularly good week in town that can be cashed in to skip a roll or accelerate a later Pursuit . Unless a feat says otherwise, Progress Momentum does not expire at the end of a Downtime period, but most GMs will want to cap how much a party can stockpile between dungeon crawls (a soft cap of 3–5, mirroring the combat Momentum bank, is a reasonable default).

________________________________________________________________________

## The Named Pursuits

Each entry below formalizes an Pursuit  already referenced elsewhere in the rules. Where a feat or item already specifies a detail (a time cost, a bonus, an output), that detail is preserved exactly — this section is filling the gaps around existing text, not overwriting it.

### Carousing (placeholder, to be developed like the old school warhammer quest from 1995, a D66 roll on a table. Will have good and bad results and/or skill/attribute checks to resolve or just need a certain level in either to get the good result?)
### Finance Bank
- (dev note) Needs definition.  effectively need a system for players to store excess money as carrying it into adventures might impinge on the inventory system.  Assuming a narrative of independent or chain of banks enables the players to store and retrieve money where ever there is a bank or bank representative in a settlement.  maybe have a result on the roll determine if they have lost money due to the banks bad investment or brigands on the road managed to assault the carriages transferring real coinage between settlements? (/dev note)
### Hammer & Forge
*Repair gear that's broken beyond field fixes.*

- **Time Cost:** 1 day per item being repaired.
- **The Check:** Crafting vs. TN 8, assuming access to a proper forge or workshop (a town blacksmith, the party's own tools if sufficiently equipped).
- **Standard Success:** Strips the **Ruined** tag from one item, restoring it to its un-Damaged baseline. Note: per the Gear Condition rules, this is also the standard route back from **Damaged** — Hammer & Forge can be used on a merely-Damaged item to clear the tag outright in a single day, rather than needing it to break further first.
- **Massive Success:** As above, and the character banks 1 Progress Momentum (their work was clean enough to also get ahead on something else this week).
- **Cost:** Typically requires spending sp equal to roughly 25% of the item's base value in raw materials (coal, leather, replacement fittings), unless the character has the Tinkerer feat (see below) or equivalent.

### Commission
*Pay a master artisan to build something better than you could make yourself.*

- **Time Cost:** 1 week (this is why Masterwork items command a 300% price markup and a specialized action — you're buying someone else's time and reputation, not just materials).
- **The Check:** No roll required if a qualified artisan is hired and paid in full. The Commission resolves automatically at the end of the week. (If the party is trying to commission something from a reluctant, suspicious, or unusually talented artisan, the GM may require an Influence check to secure the commission *before* the week of work begins — this is a Social Engine interaction, not a Crafting one.)
- **Output:** One weapon or armor piece upgraded to Masterwork Quality, per the existing Hardware rules (weapons: +1 Power; armor: suppress one negative tag).

### Tend to the Flesh
*Mundane medical care, not battlefield triage.*

- **Time Cost:** Per Wound Slot — see the base healing rule below.
- **The Base Rule:** A character heals 1 Wound Slot for every 3 days of dedicated rest and care, regardless of whether a Tend to the Flesh check is made. This is the passive floor — healing happens eventually even with no one rolling dice.
- **The Check (to accelerate or improve the outcome):** Medicine vs. TN 8. A character providing care to themselves or an ally may roll once per 3-day cycle.
- **Standard Success:** No change to the timeline, but the patient does not suffer the minor Stress tick from a poorly-tended wound (GM's call whether this applies in your table's fiction — e.g., infection risk, festering).
- **Massive Success:** The 3-day healing cycle is reduced to 2 days for that Wound Slot, and the caregiver banks 1 Progress Momentum.
- **Equipment Interaction:** A Field Surgeon's Kit grants a flat +2 to this check, as already specified in Hardware. It holds 6 uses before requiring restocking (see Acquisition, a separate gap worth addressing later).

### Field Medic
*An accelerant feat-driven Pursuit , not a base action available to everyone.*

This Pursuit  does not exist independently — it is unlocked by a specific feat (already referenced, not included in this document) that allows a character to spend Progress Momentum to bypass the standard 3-day Tend to the Flesh cycle. Per the existing Flesh Weaver feat text already in *The Marrow*: spending 2 Progress Momentum instantly heals 1 Wound Slot in 10 minutes, at a cost of 2 Dissonant Stress to the patient. This document does not change that feat's text — it simply confirms Field Medic sits under the Downtime Pursuit  umbrella defined here, and that the Progress Momentum it spends is the same currency generated above.

### Religious Pursuit  (Penance, Communion, or Pilgrimage)
*How a Priest clears Locked Stress.*

- **Time Cost:** A minimum of 1 full day, dedicated entirely to the practice (fasting, prayer, ritual confession, a pilgrimage to a shrine) — no other Downtime Pursuit  may be performed simultaneously.
- **The Check:** Will + Faith vs. TN 8.
-  **Standard Success:** Clears Locked Stress equal to the character's Will score (minimum 1), and clears 1 point of Encroachment (see Embracing the Abyss).
- **Massive Success:** Clears all of the Priest's Locked Stress and all of their Encroachment, and banks 1 Progress Momentum — a moment of genuine, total absolution.
- **Failure:** No Stress is cleared, and the day is lost. Unlike a failed Hammer & Forge or Tend to the Flesh, a failed Religious Pursuit is worth narrating: the Priest reached for their faith and found only silence. This is a good spot for the GM to foreshadow consequences of past Borrowed Authority Fails — a Priest carrying Encroachment from failed Tithes brings that same silence into this roll, at GM discretion.

### Acquisition (Restocking and Purchasing)
*Replenishing limited-use kits and consumables, like the Field Surgeon's Kit's 6 uses — and the same procedure governing any new gear bought outright in town.*

| Availability | Sourced from              | Price band | Logic                                               |
| ------------ | ------------------------- | ---------- | --------------------------------------------------- |
| Common       | Hamlet+                   | 1–25 sp    | Village smith/herbalist, ordinary materials         |
| Scarce       | Town+                     | 15–50 sp   | Needs a proper forge, market, or trained specialist |
| Rare         | City+                     | 50–200+ sp | Guild-level craftsmanship, exotic materials         |
| Legendary    | Capital, Commission-gated | GM-set     | One-of-a-kind, not a market good                    |
Bands deliberately overlap — Availability tracks *how often the world stocks it*, price tracks *how good it is*. Same orthogonal relationship Quality tags (Shoddy/Balanced/Masterwork) already use.

- **Time Cost:** Half a day, assuming the party is in a settlement of at least modest size.
- **The Check:** Influence vs. TN 8 (haggling, calling in favors, knowing the right back-alley supplier) or Survival vs. TN 8 if restocking from the wild rather than a market (foraging replacement herbs, harvesting more thread from a hunted beast).
- **Standard Success:** The item or kit is restocked, or the new item is purchased, at standard listed price.
- **Massive Success:** Restocked or purchased at a 25% discount, and the character banks 1 Progress Momentum.
- **Failure:** The settlement simply doesn't have what's needed this visit — no harm done, but the party must look elsewhere or wait.

**The Slot Check (New):** A successful Acquisition only completes the purchase — it does not grant a character extra room to carry the result. The moment an item changes hands, the buyer must immediately have an open Slot to receive it (per the Inventory Slot Assignments), exactly as if they'd looted it from a dungeon. If they don't, the purchase still happens (their coin is spent, the item is theirs), but the item is left with the merchant, a hired porter, or back at the inn until the character frees up the room to carry it — buying it doesn't conjure pack space out of nowhere. This is the same logic already governing battlefield looting; town shopping shouldn't get a quieter exemption from the rule just because it's peaceful.

**Why this matters in town specifically:** Dungeon looting is naturally self-limiting — a character drowning in treasure usually also has fresh Wounds eating their Slots (per the Attrition Tax), so the system already polices itself in the field. A trip to town has no such friction: nothing stops a fully-healed character from trying to walk out with a Tower Shield, a Longbow, and six potions in a single shopping spree. The Slot Check above exists specifically to close that loophole — town shopping should still cost something other than coin.

________________________________________________________________________

(dev note) seems light on where to SPEND progress momentum(/dev note)

________________________________________________________________________

## Summary Table

| Pursuit                        | Time Cost | Check | Output on Standard Success |
|---|---|---|---|
| Hammer & Forge                 | 1 day/item | Crafting vs TN 8 | Clears Damaged or Ruined |
| Commission                     | 1 week | None (paid) | Upgrades item to Masterwork |
| Tend to the Flesh              | 3 days/Wound (base rate) | Medicine vs TN 8 to improve | Heals 1 Wound Slot |
| Field Medic                    | 10 minutes | Feat-gated, spends Progress Momentum | Heals 1 Wound Slot at a Stress cost |
| Focused Burst                  | Instant | None — converts Locked Stress | Generates Progress Momentum |
| Religious Pursuit              | 1 day | Will + Faith vs TN 8 | Clears Locked Stress |
| Acquisition (Restock/Purchase) | Half a day | Influence or Survival vs TN 8 | Restocks a kit, or completes a new purchase — subject to a Slot Check |
