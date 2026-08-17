# Iron & Marrow — Playtest Session: "The Ledger House Job"

*A one-session playtest built around three fixed set-pieces, each designed to stress-test a specific open mechanical question. Nothing here is committed to the core documents — this is a testing pass. If a piece plays well, fold it into the Bestiary / GM Tools afterward.*

---

## Session Overview

**Premise:** The PCs are down-and-out mercs who've heard that a wealthy family patriarch has died, and the surviving heirs are quietly moving inheritance money out of the city to dodge taxes and each other. A rumor points to a small warehouse — the Ledger House — as a staging point for some of that wealth.

**Structure:** Cold Open (infiltration + Minor Scene 1) → chase/pressure → Minor Scene 2 → Major Scene → resolution.

| Scene | Set-Piece | What It's Actually Testing |
|---|---|---|
| Cold Open | The Grave-Warden (strongroom guardian) | Broken flat-Impact math on Faith Miracles (Wrathful Light / Rime-Fang's Bite); the missing clearance rule for the Fear condition |
| Cross-scene | The Watch (chase/pressure track) | Passive Notice / Stealth escalation as a non-lethal pressure tool; whether Cunning Leader needs an explicit Fodder-Threat clause |
| Minor Scene 2 | The Sluice Vault | The Drowned condition in live play; Hazard Roll interacting with ongoing combat |
| Major Scene | The Frost-Cave Troll | Queued Elite-durability stress test — is it a Brace-specific problem or universal? |
| Ambient, all session | — | Watch for any Natural 12 that also lands Margin 12+ (the Momentum double-dip flag) |

A Playtest Log checklist is at the end — fill it in as things happen, not from memory afterward.

---

## Scene 1 (Cold Open): The Ledger House

The party stakes out and infiltrates the warehouse. Run this as standard Stealth/Thievery play — Passive Notice (7 + Wits + Notice) vs. the party's Stealth (2d6 + Reflex + Stealth) for any watchmen or hired hands on site, opposed Notice/Stealth for the guards inside.

In the back office or under a false floor, the party finds the real prize: a sealed strongroom built into the family's private crypt, guarded by a construct.

### The Grave-Warden (Grunt)

*A rusted, robed shape that was once a mourning-effigy, animated to guard both the patriarch's bones and his hidden coin from grasping relatives and thieves alike.*

- **Tier:** Grunt
- **Type:** Construct
- **Size:** Standard
- **Stats:** Reflex +2
- **Skills:** Melee +2 *(Strikes at +2; Prowess assumed zero)*
- **Derived Stats:** Wound Threshold **4** (4 base + Prowess 0) | Wound Slots: 2 | Stress Limit: 4 (4 + Will 0 + Wits 0)
- **Equipment:** Ancient bone blade (Power 2)
- **Traits (1):** **Fear Inducing** *(existing trait — anyone engaging it or activating within line of sight rolls Will + Resolve vs. TN 8 or gains the Fear condition)*
- **Vessel Limit:** 1
- **Threat Abilities (1):**
  - **Cost 1 Threat — Grinding Assault:** *Trigger:* Declared on a successful Melee Clash. *Effect:* This Strike gains the **Cleave** tag (per Hardware), catching an adjacent ally in the same roll.

**Phases**
- **Unbroken:** Advances in a straight line toward whoever is closest to the crypt door. No tactics, no hesitation — it isn't afraid and doesn't need to be clever.
- **Broken (Surrender-tier, Humanoid Elites rule doesn't apply — use Construct default):** At max Stress, it doesn't rout or surrender — it seizes up mid-swing, frozen mid-motion, and is removed from the tactical equation. *(Note: Construct break-behavior isn't explicitly defined anywhere yet — this is a reasonable default, but worth formalizing if Constructs recur.)*

### What to watch for here

**1. The Faith Impact-math test.** If any PC runs a Faith build with Wrathful Light or Rime-Fang's Bite, this is the ideal target — WT 4 is the absolute floor of the system. A flat 2 Impact (even ignoring Armor) can never cross it, on any roll, at any tier. Let it happen naturally; don't steer the player toward or away from casting it. Just note the outcome.

**2. The Fear clearance gap.** If the Grave-Warden's Fear Inducing trait lands, the table will hit the fact that Fear (unlike Terrified) has no written way to shake it off. Don't quietly rule one in ahead of time — let the table hit the wall and see what a GM improvises under pressure. Write down whatever ruling you make on the spot; that's useful data for the eventual fix.

### Trigger for the Watch

Whichever comes first — a loud Grave-Warden fight, a failed Stealth roll, or a Snake Eyes (per the existing Catastrophic Exposure consequence) — moves the Watch Escalation Track (below) to **Stage 1**.

---

## The Watch: A Pressure Track, Not a Combat Encounter

Built entirely from existing tools — no new subsystem. The Watch's job is to be evaded or outrun, not fought to the death; a stand-and-fight is possible but should carry a cost the players feel later (reputation, bounty, more Watch), not just XP.

### Stage 0 — Unaware
Standard opposed check: Passive Notice (7 + Wits + Notice) or an active Notice roll vs. the party's Stealth (2d6 + Reflex + Stealth).

### Stage 1 — Alerted
Triggered by a failed Stealth check, a loud fight, or Catastrophic Exposure. A whistle or bell sounds. No stat block appears yet. **Mechanical effect:** every further Stealth attempt this scene takes the existing **Difficult (-2) Situational Modifier** — patrols are now actively listening, not idly patrolling.

### Stage 2 — Pursuit
The Sergeant and 2 Patrolmen physically close in.
- Each round the party is fleeing, call for **Prowess + Athletics** or **Reflex + Acrobatics** (TN 8) to gain ground.
- If the Watch has crossbows loosed to suppress rather than kill, a failed check applies the existing **Suppressed** condition (Disadvantage on anything but Attack/Block/Brace/Regroup, +1 Dissonant Stress) instead of a Wound.
- If the party turns to fight, resolve normally with the stat blocks below — it should be short.

**Resolved since this doc was drafted:** Fodder now spend Threat freely regardless of whether a leader is present, up to their Vessel Limit (see Tools for the Nameless — Tiers of Attrition). The Watch Patrolman doesn't currently have a Threat Ability defined, so this doesn't change anything for this specific stat block — but the open question about Cunning Leader is settled and can be dropped from the log.

### Watch Patrolman (Fodder)
- **Type:** Humanoid | **Size:** Standard
- **Stats:** Prowess +1 *(Strikes at +1, everything else +0)*
- **Wound Threshold:** 6 (4 + 1 Prowess + 1 Light Armor) | Wound Slots: 1 | Stress Limit: 0
- **Equipment:** Baton (Power 1), Light Armor (+1)
- **Vessel Limit:** 1

### Watch Sergeant (Grunt)
- **Type:** Humanoid | **Size:** Standard
- **Stats:** Prowess +1, Wits +1 | Melee +1, Influence +1
- **Wound Threshold:** 6 (4 + 1 Prowess + 1 Light Armor) | Wound Slots: 2 | Stress Limit: 5 (4 + Wits 1)
- **Equipment:** Saber (Power 2), Light Armor (+1) — Strike: `2d6+2`
- **Traits (1):** **Cunning Leader** *(existing trait)*
- **Vessel Limit:** 1

---

## Scene 2 (Minor): The Sluice Vault

The party's escape route — the smugglers' sewer route one PC knows — runs directly into a collapsing sluice gate that floods a lower vault.

### The Trap

- **Unaware or failed-Notice targets:** standard **Hazard Roll** (2d6 + Hazard Power 3), compared directly against the target's Wound Threshold like a Strike, per the existing Trap Resolution rules. Anyone caught unaware cannot add Shield Value or Parry.
- **Anyone swept under** (whether they took a Wound from the initial surge or not) immediately gains the **Drowned** condition:
  - Disadvantage on all rolls; 1 Dissonant Stress at the start of each turn.
  - Clears via Prowess + Athletics (TN 8) — self or an adjacent ally spending an Action — or by being physically pulled out of the water.

### The Complication

**Bog-Wretch (Fodder)**
- **Type:** Undead | **Size:** Standard
- **Stats:** Prowess +1 *(Strikes and grabs at +1, everything else at +0)*
- **Wound Threshold:** 5 (4 + 1) | Wound Slots: 1 | Stress Limit: 0
- **Equipment:** Waterlogged claws (Power 1) — Strike: `2d6+1`
- **Traits (1):** **Vicious** *(existing trait — inflicted damage forces a Prowess check or Bleeding)*
- **Vessel Limit:** 1

Field 3–4 of these, surging out of the flooded muck while some PCs are still fighting off Drowned. Individually harmless — the point is testing whether Drowned's slow bleed actually feels oppressive layered under combat pressure, not as a standalone puzzle.

**If the Watch Pursuit (Stage 2) is still live when the party hits this scene**, that's a useful second data point: does splitting attention between an environmental hazard and human pursuers actually break the tension, or does it just pile on? Note which.

---

## Scene 3 (Major): The Frost-Cave

The tunnel surfaces in a natural cave system at the city's edge — the actual exit — currently denned by a Frost-Cave Troll that has no idea a smugglers' route now runs through its territory.

*This is an existing Bestiary entry, reused deliberately — it's already sitting on the stress-test queue, so running it here closes an open item instead of opening a new one.*

### The Frost-Cave Troll (Elite)

*A towering, territorial brute of dense muscle and thick frost-bitten hide. It swings a shattered pine tree with horrifying speed, its wounds knitting together almost as fast as they are opened.*

- **Wound Threshold:** 9 (4 + Prowess 3 + Scale 2) | **Wound Slots:** 3 | **Stress Limit:** 4
- **Stats:** Prowess +3 | Melee +3, Brace +1, Reflex +1 *(Assumed Zero: Dodge, Wits, Will, Arcana, Resolve — fast and hits like a siege weapon, but entirely defenseless against mind-altering magic or illusions)*
- **Traits (2):**
  - **Large (Scale +1)**
  - **Troll-Blood Regeneration:** At the start of its activation, automatically heals 1 Wound Slot and clears 1 Stress. *Weakness:* any Impact from a Fire source (Naphtha Fire-Flask, Pyromancy) fully suppresses this trait until the end of the next round.
- **Threat Abilities (2):**
  - **Cost 1 Threat — Vicious Frenzy:** *Trigger:* immediately after the Troll completes a Strike. *Effect:* an immediate secondary Strike against an adjacent target (claws, treated as Power 1, Vicious).
  - **Cost 2 Threat — Sweeping Uproot:** *Trigger:* declared before a Strike with its Tree Trunk (Power 3, Reach, Brutal). *Effect:* the Strike gains **Cleave**, forcing everyone in its frontal arc to defend against the same roll; anyone who loses is knocked Prone.
- **Vessel Limit:** 2

### Staging Notes

- **Start Threat at 3–4 (High Alert)** — enough for it to open with Sweeping Uproot or immediately chain into Vicious Frenzy.
- **Terrain:** icy, mire-touched cave floor (ties naturally to Winter & Wilds flavor without contradicting anything established).
- **The actual test:** make sure at least one Brace-oriented PC (shield/heavy armor) *and* one Dodge/Parry-oriented PC both take hits from the Tree Trunk. If only one defense style shows up, you won't get a clean answer to "is this an Elite-durability problem, or specifically a Brace problem" — which is the whole reason this fight is queued. Don't let the fiction quietly let one PC dodge the whole encounter.
- **Ambient watch:** any Natural 12 that also lands a Margin of 12+ in this fight is the Momentum double-dip (2 from Fates' Bounty + 2 from Massive Success off one roll). Dice-heavy fights like this are the most likely place to actually see it happen — note it if it does.

---

## GM Playtest Log

Fill this in during or immediately after the session — don't rely on memory afterward.

**Grave-Warden / Faith math**
- [ ] Did a PC cast Wrathful Light or Rime-Fang's Bite on it? Outcome:
- [ ] Did the Fear Inducing trait land on anyone? What ruling did you improvise for clearing Fear?

**The Watch**
- [ ] Did the party evade, fight, or get caught? At which Stage?
- [ ] Did Suppressed actually create meaningful pressure, or did it fizzle?
- [ ] Any moment where "does Cunning Leader unlock Fodder Threat-spending" actually came up?

**The Sluice Vault**
- [ ] Did Drowned feel oppressive, or did the party clear it trivially?
- [ ] Did the Bog-Wretch ambush land while PCs were still Drowned, or did the timing miss?

**The Frost-Cave Troll**
- [ ] Did a Brace user take a hit? Outcome (Wound / no Wound)?
- [ ] Did a Dodge/Parry user take a hit? Outcome?
- [ ] Conclusion: universal Elite-durability issue, or Brace-specific?
- [ ] Any Natural 12 + Margin 12+ double-dip observed? How much Momentum did it generate?

**General**
- [ ] Any other seam or contradiction that surfaced and wasn't on the original flag list?
