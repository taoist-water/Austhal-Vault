# Downtime, Revised: Settlements, Budgets, and Reputation

This extends the base Downtime Endeavour procedure (the TN 8 Margin roll, Progress Momentum on a Massive Success) with three new layers per your dev notes: a time-budget system replacing literal day-counting, a Settlement Tier ladder gating what's available, and a Settlement Reputation stance mirroring the existing NPC Social Engine. None of the individual Endeavours defined previously (Hammer & Forge, Tend to the Flesh, Religious Endeavour, etc.) change their checks or outputs — what changes is how many of them a character can actually attempt, and where.

________________________________________________________________________

## 1. Endeavour Points (Replacing Literal Day-Counting)

Tracking exact calendar days across a party with different ongoing Endeavours gets unwieldy fast — especially once a Priest is spending a full day on Religious Endeavour while the Fighter is mid-week into a Commission. Instead, the GM sets a **Downtime Budget** in **Endeavour Points (EP)** based on the narrative gap between adventures, and each Endeavour costs EP rather than literal days.

**Endeavour Costs (EP):**

| Endeavour | EP Cost |
|---|---|
| Acquisition (Restock/Purchase) | 1 EP |
| Tend to the Flesh (per Wound Slot cycle) | 1 EP |
| Hammer & Forge (per item) | 1 EP |
| Religious Endeavour | 1 EP |
| Commission | 3 EP |
| Tinkerer's variant (feat-gated) | 1 EP |

**Example Budgets by Narrative Gap:**

- **A Single Night (1 EP):** The party makes camp in a waystation or sleeps at an inn before pushing on at dawn. Barely enough time for one quick Acquisition run or a single round of Tend to the Flesh.
- **A Few Days' Respite (3 EP):** The party has a short, clear break — recovering after a dungeon, waiting on a lead. Enough for a couple of Endeavours each, or one character to push hard on a single big one.
- **A Full Week in Town (5–7 EP):** The classic "return to town between dungeons" beat. Enough EP for most characters to run two or three Endeavours, or for one character to commit their whole budget to a Commission.
- **A Season of Downtime (10+ EP):** Used sparingly — between story arcs, over a winter, during travel to a new region. The GM should treat this as an explicit pacing tool, not a default, since it lets characters stack multiple Commissions or fully clear Locked Stress and gear damage across the whole party.

**The Rule:** Each character tracks their own EP budget independently — one character spending their whole budget on a Commission doesn't prevent another from running three small Endeavours in the same gap. This keeps downtime parallel rather than turn-based, matching how real "everyone goes off and does their own thing in town" play actually happens at the table.

________________________________________________________________________

## 2. Settlement Tiers (What's Even Possible Here)

Not every Endeavour is available everywhere. A fishing hamlet has no master blacksmith to Commission from; a sprawling capital has no shortage of either. This uses the same tiered-category instinct as your Fodder/Elite/Boss and Cover ladders — a small, memorable set of named tiers rather than a sliding numeric scale.

### Hamlet (Tier 0)
*A handful of families, maybe a shrine, no real market.*
- **Available Endeavours:** Tend to the Flesh, Religious Endeavour (if the local shrine matches the Priest's tradition — GM's call), basic Acquisition (food, rope, torches, common-tier items only).
- **Unavailable:** Hammer & Forge (no forge), Commission (no master artisan).
- **Acquisition Modifier:** **-2** to the Acquisition check for anything beyond Common availability — a hamlet simply doesn't stock it, full stop, regardless of how good the roll is. Treat a roll that would otherwise succeed as automatically failing if the item's Availability rating exceeds Common.

### Town (Tier 1)
*A proper market square, a working forge, a temple or chapter house.*
- **Available Endeavours:** All of the above, plus Hammer & Forge and Acquisition up to Scarce availability.
- **Unavailable:** Commission for anything above Masterwork (no legendary specialists here).
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

## 3. Settlement Reputation (The Demeanor Layer)

This directly mirrors the existing NPC Stance system, scaled up from a single person to an entire settlement's general disposition toward the party. It exists specifically so Influence-based skills and feats have somewhere to matter outside of combat and individual NPC negotiation — closing the same gap flagged in the broader non-combat review.

**The Four Settlement Stances:** Hostile, Unfriendly, Neutral, Friendly — identical states and identical shift rules to the revised NPC Stance System (Standard Success shifts one step, High Success shifts two steps, never jumping straight to the opposite pole), applied collectively to a settlement's general disposition.

- **Hostile:** The party has actively wronged this settlement — botched a job, insulted the local lord, left a debt unpaid, or committed a crime that's become common knowledge. Acquisition checks suffer **-4**, Commission requests are refused outright regardless of payment, and most other Endeavours (Religious Endeavour at a shrine whose faction the party has angered) may be denied entirely at GM discretion. This is the settlement actively working against the party, not just distrusting them.
- **Unfriendly:** The settlement is wary or has a poor opinion of the party — minor past friction, an unresolved rumor, simple distrust of outsiders — but isn't yet acting against them. Acquisition checks suffer **-2**. Most Endeavours remain available, just at worse terms; merchants quote higher prices, artisans are slower to commit to a Commission.
- **Neutral:** The default starting state for any settlement the party hasn't meaningfully interacted with yet. No modifier — this is the baseline the Settlement Tier modifiers above are written against.
- **Friendly:** The party has earned genuine goodwill — cleared a local threat, donated generously, performed a public service. Acquisition checks gain **+2** (stacking with Tier modifiers — a Friendly City offers a generous **+4** total), and Massive Successes become more frequent in practice simply because the combined modifier pushes more rolls past the Margin 5 threshold.

**Changing a Settlement's Stance:** Unlike an individual NPC, a settlement's stance shouldn't flip on a single Influence roll — it represents the aggregated opinion of dozens or hundreds of people, and should move the way reputation actually moves: slowly, and mostly through action rather than conversation.

- **The Single Roll Exception:** If the party is dealing with one clearly-defined authority who speaks for the settlement (a mayor, a guild master, a garrison captain), a standard opposed Influence vs. Resolve check against that NPC can shift the *settlement's* stance exactly as if they were shifting an individual's — because, narratively, they effectively are the settlement's gatekeeper. This is the fast path, and it's identical math to the existing Social Engine, just with a wider blast radius on the outcome.
- **The Slow Path (No Single Authority, or a Fractured Settlement):** Settlement stance shifts one level after the party completes a deed the GM rules is significant enough — clearing a dungeon threatening the town, publicly exposing a corrupt official, sponsoring a town festival. This is a narrative trigger, not a roll, deliberately mirroring how individual NPC trust-building sometimes bypasses dice entirely in favor of "you did the thing, the stance moves."

**Touchpoint — Reputation and the Captain Voss Encounter (Worked Example):** If a party successfully bribes or intimidates a corrupt watch-captain into a Friendly stance (using the Social Engine work from earlier in this project), that shift is properly scoped to *Voss personally*, not the whole settlement — unless Voss specifically *is* the settlement's gatekeeper (a watch-captain plausibly is, for matters of law and access). This is worth flagging as the kind of judgment call a GM will make constantly: is this NPC speaking for themselves, or for the town?

________________________________________________________________________

## Summary: How a Downtime Period Actually Resolves at the Table

1. The GM narrates the time gap and sets an **EP Budget** (Section 1).
2. The GM (or the players, by simply being somewhere already established) confirms the **Settlement Tier** (Section 2), which gates what's even on the menu and sets the baseline Acquisition modifier.
3. The GM checks the party's current **Settlement Reputation** with this specific settlement (Section 3) — Hostile/Unfriendly/Neutral/Friendly — which further modifies Acquisition and may gate or unlock specific Endeavours.
4. Each player spends their own EP budget across the Endeavours now available to them, rolling each as defined in the base Downtime Endeavours document.

This keeps the actual dice-facing procedure exactly as previously defined — nothing about *how a single Endeavour resolves* has changed — while giving the GM three new dials (time, place, and standing) to make every return to town feel mechanically distinct rather than an identical menu regardless of where or when the party arrives.
