# Iron & Marrow — Rules of Play

*Compiled 2 October 2026 from the Master rules folder. This note is generated — edit the source files, then rebuild.*

## Contents

**Part I — Playing the Game**

- [[#Chapter 1 — Iron Core|Chapter 1 — Iron Core]] · *Core Rules*
- [[#Chapter 2 — The Marrow|Chapter 2 — The Marrow]] · *Character Creation & Advancement*
- [[#Chapter 3 — Metal meet Flesh|Chapter 3 — Metal meet Flesh]] · *Combat*
- [[#Chapter 4 — Iron World|Chapter 4 — Iron World]] · *The Environment & the Social Engine*
- [[#Chapter 5 — Hardware|Chapter 5 — Hardware]] · *Equipment*
- [[#Chapter 6 — Embracing the Abyss|Chapter 6 — Embracing the Abyss]] · *Magic*
- [[#Chapter 7 — Manipulating the Void|Chapter 7 — Manipulating the Void]] · *Spells & Prayers*
- [[#Chapter 8 — Soothing the Soul|Chapter 8 — Soothing the Soul]] · *Downtime*

**Part II — Running the Game**

- [[#Chapter 9 — Tools for the Nameless|Chapter 9 — Tools for the Nameless]] · *GM Tools*
- [[#Chapter 10 — Beasts, Monsters & Mutants|Chapter 10 — Beasts, Monsters & Mutants]] · *Bestiary*

**Appendices**

- [[#Appendix A — Building Enemies|Appendix A — Building Enemies]] · *The Enemy Template*
- [[#Appendix B — Sample Characters|Appendix B — Sample Characters]] · *Pregenerated Player Characters*

---

# Part I — Playing the Game

# Chapter 1 — Iron Core

*Core Rules*

## Design concept
- A gritty, High fantasy realism role playing game.
- a brutal, psychologically driven fantasy RPG built around opposed rolls, Momentum, and the interaction between physical trauma and mental collapse
- Rolls are either opposed or against a static target number, with contextually applied modifiers.
- Unopposed rolls always resolve with a margin of success or scaler.
- rule system that is simple, yet detailed. When dealing with combat.
- trying to reduce cognitive load on the GM and Players.

##  The Golden Rules:
- Bonuses to Wound Threshold from magical sources (Spells, Auras, Enchanted Equipment) do not stack. A character only benefits from the highest single bonus. This does not apply to Shield Value.
- Bane effects (a flat reduction to a target's Wound Threshold against one specific Creature Type — see the Bestiary's Creature Types list) do not stack with each other against the same target; only the single highest Bane reduction applies. Bane reduces Wound Threshold before Impact is compared against it — this is a separate step from the Massive trait's Impact-halving, and the two apply independently rather than cancelling out.
- **Attunement Locked Stress is absolute.** Locked Stress committed to an item's Attunement (see Hardware: Enchantments) **cannot be cleared, unlocked, converted, transferred, reduced or otherwise removed by any means whatsoever while the item remains attuned** — not by the Reprieve, a Long Rest, a Breather, Religious Pursuit, any Downtime Pursuit or any number of nights, any alchemical preparation, any Feat, any spell or Prayer, and not by any future effect that clears Locked Stress. **Breaking passes it over** rather than converting it to Dissonant. There is exactly one release: the item is **deliberately unattuned**. An attuned item costs a permanent slice of the character's Stress track, and that permanence is the entire price of the item.
- Locked Stress paid for a Prayer that is currently **Flowing** cannot be targeted by the Reprieve or Religious Pursuit, and releases when the Prayer ends. Unlike Attunement it *is* reachable by alchemical override (Hardware, Alchemical Wares) — a Priest can force it open at a price, which is what those preparations are for. Locked Stress from a Prayer that has already resolved is clearable by the normal routes. Arcane **Sustain** commits no Locked Stress at all and is never subject to this rule.
- Situational Modifiers are applied at GM’s discretion, +2, -2, -4.
- Advantage and Disadvantage do not stack. If you have multiple sources of Disadvantage, you still only roll 1 extra die and drop the highest. If you have both Advantage and Disadvantage, they cancel each other out entirely.
- Wounds Threshold Bypassing effects cannot target creatures of Scale +3 or higher without a weapon carrying Devastating or Siege.

## Dice Mechanics

- The Check: 2d6 + Skill vs. TN 8 (or Opposed).
	- Attributes are not added to the roll. They set the ceiling a Skill
	  can reach, and they drive your derived stats.
	- When opposed in Combat, using a weapon is resolved as follows;
		- The Currently Active character chooses an Attack action,
		  like strike or shoot.
		- roll 2d6 + Melee/Ranged
		- The target chooses a Defensive action, like parry, and
		  rolls 2d6 + Skill.
		- the Higher roll wins.
		- the difference between the winner and the loser is the
		  Impact (when attacking).
		- Impact is compared to the losers Wound Threshold.

- **Fates Bounty (double 6s):** When a natural double 6 is rolled, the player (or Elite/boss NPC)  rolls an additional die and adds it to the total. This is only done once.
- **Snake Eyes (natural 2):** Automatic failure. The character immediately suffers 1 Stress, and additional contextual penalties.
- **Desperate Edge is not a universal Core Rule.** A lone natural 6 on a 2d6 check is just a 6 — no exploding die — unless the roller has the **Desperate Edge** Feat (Tier 1, see The Marrow, Feats). A character without that Feat gets nothing extra here, no matter how desperate their situation is.

### The Margin-Focused Resolution (Unopposed Checks)

Instead of artificially inflating the Target Number to combat high modifiers, we accept that highly skilled characters will succeed at standard tasks. The dice roll dictates the collateral damage, the speed, or the Momentum generated.

The Universal TN 8 Baseline Whenever a player makes an unopposed roll (like picking a lock, tending to a wound, or deciphering a grimoire), the Target Number is always 8.

The Resolution Ladder You calculate the Margin (Total Result - 8) and apply the outcome:

- Failure (Total 7 or less): The task fails outright. Time is wasted, and a consequence triggers (e.g., the lock picks snap, or you take 1 Dissonant Stress from frustration).

- Messy Success (Margin 0–2): You accomplish the task, but it costs you. You pick the lock, but it takes 10 minutes and your torch burns out. You forge the armour, but you must spend an extra 5 Silver Pieces on wasted materials.

- Clean Success (Margin 3–4): Flawless execution. You achieve the exact desired result with no complications.

- Massive Success (Margin 5+): You absolutely dominate the challenge. You achieve the result and generate 1 Momentum, or you gain a Prep Tag for an upcoming encounter.

---

**Passive Notice**
Not every threat announces itself with a die roll. When a character isn't actively searching — walking down a corridor, mid-conversation, sprinting through a firefight — the world still needs a number to test their awareness against, without pausing the game for a check nobody declared.

**The Formula: Passive Notice = 7 + Notice**, modified by any applicable Situational Modifier (+2/-2/-4, per Tools for the Nameless).

The baseline of 7 (rather than a flat TN8) anchors Passive Notice to the statistical average of 2d6, keeping it consistent with the actual odds of an active roll. An unmodified character's Passive Notice sits just below TN8 — matching the fact that they'd fail an active TN8 check more often than not. Passive Notice should never make an untrained bystander more perceptive than a trained character actively rolling to look.

***Advantage/Disadvantage Conversion:*** Because Passive Notice doesn't roll dice, sources of Advantage or Disadvantage on Notice checks (e.g. the Dwarf's Subterranean Senses, or the Whispers in the Dark feat) apply as a flat +2 or -2 to the Passive Notice score instead — consistent with the existing Situational Modifier scale (Advantageous = +2, Difficult = -2).

***The Winded Penalty:*** Passive Notice stands in for a roll, not an exemption from one. It takes the Winded `-1` or Breaking `-2` penalty whenever the character has one, exactly as an active roll would.

**Resolution Modes:**

*Opposed (detecting a person):* Compare Passive Notice directly against the sneaking creature's Stealth roll (2d6 + Stealth), or against a fixed Concealment Rating. This mirrors the existing Illusion/Disguise pattern of comparing a static value against a banked roll or Margin.
*Unopposed (detecting a hazard or feature):* Passive Notice + Situational Modifier vs. TN8 flat.
This mechanic resolves the Aware/Unaware fork in Iron World's Hazard Roll, the Bestiary's Ambusher trait, and the Cultist Assassin's Vanish ability — see those entries for specific application.

---

### The "Snake Eyes" Rule (Natural 2)

When a player rolls a Natural 2 (two 1s) on a 2d6 check, the result is an Automatic Catastrophic Failure, regardless of their Attributes, Skills, or Gear modifiers. The total margin is irrelevant; the world intervenes in the worst possible way.

When this happens on an unopposed check, the GM immediately applies one of the following consequences based on the context of the action:

- Gear Degradation: The tool being used is pushed beyond its physical limit. If picking a lock, the picks snap off inside the mechanism, permanently jamming it. If using an Alchemist's Kit, the vials shatter. The item immediately gains the Damaged tag (or is Ruined if already Damaged).

- The Panic Reflex: The character realizes they have made a catastrophic error. They instantly suffer 1 point of Dissonant Stress, immediately ticking them closer to the Death Spiral.

- The Momentum Drain: The sheer embarrassment or shock of the failure kills the party's forward drive. The party instantly loses 1 banked Momentum. If they have no Momentum to lose, the active character takes 1 Dissonant Stress instead.

- Catastrophic Exposure: If the roll was related to Stealth or Scouting, the failure is loud and undeniable. The character is completely exposed, and all enemies in the upcoming encounter gain Advantage on their opening Activation order rolls.

**In an opposed Clash**, a Snake Eyes is an automatic loss of the Clash regardless of the actual total rolled, and the roller also suffers the Panic Reflex consequence (1 Dissonant Stress) on top of losing. This overrides any reroll effect that would normally apply to the roll (such as Finesse's natural-1 reroll) — a Snake Eyes can never be rerolled, by any means.

---

## The Momentum Economy

### The Momentum Bank

Momentum represents tactical flow, adrenaline, and sudden strokes of genius.
Each player maintains a personal bank capped at **4 + Reflex**.

- **Generation:** Players earn 1 Momentum by winning a Clash — an Attack Action, a Defense, evading a trap, or executing an ambush — **by a Margin of 5+**. A win alone isn't enough; it has to be decisive. See *Gaining Momentum* below for the full ladder, which this line summarises.

- **Spending (The Rule-Breakers):** Momentum is never spent to add a "+1" to a die. It is spent to break the rules. Players can spend Momentum to instantly clear debilitating conditions (like _Anchored_), construct improvised alchemical explosives mid-dungeon, rapidly patch _Damaged_ armour with spit and twine, or bend the narrative via flashbacks.

### Gaining Momentum

#### 1. The Skill Pillar (The Margin of Success)

 If we want to keep the engine unified, Momentum generation should be directly tied to the Margin math we have built. It shouldn't be arbitrary; it should be the mechanical reward for overwhelming success.

-  Combat: Winning a Clash by a Margin of 5+ (Massive Success, 1 Momentum)

- Magic: hitting that Margin of 5+ on an unopposed Arcana check generates Momentum because the caster executed the spell flawlessly.

- Exploration: Exceeding an unopposed Target Number (like TN 8 for picking a lock or scaling a wall) by a Margin of 5+ (1 Momentum).

#### 2. The Engine Pillar (The Exploding Dice)

Because the 2d6 engine only explodes on a Natural 12, that moment is already mechanically rare and highly celebrated at the table.

-  The Trigger: Anytime a player rolls a Natural 12 (Double 6s) on any check—whether it is a Strike, a Parry, or a lore check—they instantly generate 2 Momentum, regardless of the final Margin. It mathematically reinforces that "perfect luck" fuels their adrenaline. This CAN compound with a Massive Success margin (5+) for 3 momentum off 1 roll.

#### 3. The Sacrificial Pillar (The Desperate Push)

 In a gritty system like Iron & Marrow, players should have a way to generate Momentum when the dice are failing them, but it must come at a terrible physiological cost.

- The Trigger: A player can voluntarily take 1 or 2 Dissonant Stress to instantly generate 1 Momentum. This perfectly feeds into the Death Spiral. They are burning their own mental threshold to force a tactical advantage, pushing themselves closer to breaking just to survive the current round.

---

Momentum must become a currency of Rule-Breaking and Action Economy. Players spend Momentum to temporarily alter the laws of the game.

### Spending Momentum
#### Cost 1 Momentum: Tactical Shifts

 These are cheap, immediate physiological or tactical reactions.

- Shake It Off (Condition Clearance): As a Free Reaction at the start of their turn, the player spends 1 Momentum to immediately clear a physical condition like Ablaze, Anchored, or Rigor without having to waste their entire turn taking the Regroup action.

-  The Blood Price (Triage/Stress Mitigation): When an enemy's Impact exceeds the player's Wound Threshold and is about to cause a physical Wound, the player can spend 1 Momentum to convert the physical trauma into mental trauma. They take 0 Wounds, but instantly take 2 Dissonant Stress instead.

#### Cost 2 Momentum: Breaking the Engine

 These manipulate the action economy and the Bestiary tags directly.

- The Surge (Action Economy): After successfully winning an Attack Action, the player spends 2 Momentum to immediately take a second, completely free Attack action before the enemy can respond or the turn passes.

- Adrenaline Flush (Death Spiral Reversal): As a Free Reaction, the player spends 2 Momentum to instantly clear 1 Dissonant Stress. This is the only way to heal the mind mid-combat without casting a spell , finding a safe room for a Breather, or use alchemical resources.

#### Cost 3 Momentum: The Ultimates

 These are massive, encounter-shifting expenditures that drain more than half of their maximum bank.

-  The Decisive Blow (Forcing the Threshold): The player wins an Attack Action, but the math reveals the Impact is lower than the Boss's massive Wound Threshold, meaning it would normally only cause 1 Stress. The player spends 3 Momentum to drive the blade through anyway. The attack automatically inflicts exactly 1 Wound Slot, bypassing the Threshold check entirely. *without equipment and preparation this could be the only way to wound Boss tier entities. Use it!*

-  Interrupt / Seize the Initiative: When the GM declares an enemy is about to activate, the player can spend 3 Momentum to literally pause time. The player instantly interrupts the enemy, and moves into the activation order before the enemy taking a full  turn before the enemy's activation.

---

## Stress vs. Wounds
### Stress
In _Iron & Marrow_, Stress is the primary mechanical representation of a character's mental fortitude, stamina, and panic. It serves as the crucial buffer before taking physical, lethal trauma (Wounds) and acts as the central pacing mechanic for combat, magic, and survival.

#### The Stress Limit

A character's capacity to handle pressure before breaking is defined by their Stress Limit, which is calculated as **4 + Will + Wits + Feat Bonus + Species bonus.**

#### The Two Categories of Stress

Stress is strictly divided into two types, which affect the character's capabilities in drastically different ways:

- **Dissonant Stress:** This represents immediate panic, physical pain, fumbles, or sudden exhaustion. It simulates a character losing their edge as they are battered and terrified. It can be cleared relatively quickly by spending Momentum, taking a The Breather, or using consumable items.

- **Locked Stress:** This represents sustained mental and physiological burdens: the cost a Priest pays to borrow authority, the weight of an Attuned item, an Arcanist's deliberate Overcharge, suffering through specific negative conditions, or enduring harsh environmental hazards. Crucially, Locked Stress ***does not*** apply the negative -1 penalty to your dice rolls. However, it fills up your Stress Limit and is much harder to clear, requiring a specific action like the Reprieve, a Long Rest, or specific Downtime Endeavours — **except the Locked Stress of an Attuned item, which none of those reach at all while the item is worn** (see the Golden Rules).

	*Note the division of currencies: an Arcanist's ordinary casting bleeds **Dissonant** Stress — botched manifestations, Messy margins, failed Sustain checks. Locked Stress is the Priest's bill, and reaches an Arcanist only through Overcharge, Attunement, conditions, and the environment.*

#### The Death Spiral (The Stress Track)

_Iron & Marrow_ is a game of psychological and physical attrition. Stress is the primary currency of exhaustion.

- #### The "Squeeze" Mechanic

Think of the character's Stress Limit as a track. Dissonant Stress fills the track from the left, and Locked Stress fills it from the right.

- **Dissonant Stress (The Panic Trigger):** The only type of Stress that counts toward Winded.

    - _The 50% Tier (Winded):_ While a character's **Dissonant Stress** is at or above half of their Stress Limit (rounded up), they suffer a flat `-1 penalty` to all rolls. Locked Stress of any kind, Attunement included, never counts toward this threshold.

- **Locked Stress (The Capacity Drain):** This represents sustained exhaustion, a debt owed, or a burden carried — most often a Priest's Tithe, but also Attunement, Overcharge, conditions, and exposure. It does not trigger the `-1 penalty`, but it "blacks out" available slots on the track, drastically reducing the character's buffer before they hit the absolute limit.

- **Total Capacity (The Breaking Point):** Every box counts toward filling the track: Dissonant, Locked and Attunement alike.

    - _The 100% Tier (Breaking):_ The moment a character's **Total Stress (Dissonant + Locked, including Attunement)** reaches their Stress Limit, the track is full and their mental focus shatters: all current Locked Stress immediately becomes Dissonant — **except Attunement Locked Stress, which does not convert and stays locked** (see the Golden Rules). Because Attunement boxes count toward a full track, an attuned character Breaks exactly as anyone else does.
    - **While the track is full**, the character suffers a flat `-2 penalty` to all rolls. This replaces the Winded `-1`; the two never stack.
    - **Leaving Breaking:** the moment any Stress clears and the track is no longer full, the `-2` ends. The character is Winded instead if their Dissonant Stress is still at or above half their Limit (rounded up).

- When the Stress Track is full and a Character would gain additional Stress, it immediately converts to Wounds — or to Unconscious, if the source is `non-Lethal` (see The Death Spiral (Stress Conversion)).

## Wounds

In _Iron & Marrow_, **Wounds** are the brutal, mechanical representation of physical trauma and bodily failure. While Stress represents panic and exhaustion, Wounds are the broken bones, deep lacerations, and punctured organs that eventually pull a character into the grave.

Here is a breakdown of how Wounds function within the system:

### The Wound Slots

Unlike traditional hit point systems that feature inflated health pools, _Iron & Marrow_ uses a strict, low-capacity slot system to maintain high lethality.

- A standard character has exactly 3 Wound slots.

- Taking a 4th Wound means you are instantly Incapacitated.

- Unlike Dissonant Stress, Wounds do not apply direct stat or dice penalties. Instead, they act as a terrifying countdown to absolute bodily collapse.

#### Calculating Wounds (Impact vs. Threshold)

To take a Wound, an enemy's attack must overcome your physical durability, represented by your **Wound Threshold (WT)** (calculated as 4 + Brawn + Armour Value + Species Bonuses + Scale bonus + Misc.mods). When a character loses a Clash, the resulting Impact dictates the severity of the Wound:

- **Minor Wound:** If the Impact equals or exceeds your Threshold, you take 1 Minor Wound (filling 1 slot).

- **Major Wound:** If the Impact equals or exceeds _twice_ your Threshold, you suffer massive trauma, taking 1 Major Wound (filling 2 slots) + 1 Dissonant Stress.

- **Overwhelming Trauma (Instant Incapacitation):** If the Impact equals or exceeds _three times_ your Threshold, the attack bypasses your Wound Slots entirely — it does not fill one, no matter how many you have available (including bonus slots from spells, feats, or magic items; nothing makes a character immune to a single catastrophic blow). Instead, you immediately gain the **Incapacitated** condition exactly as if you'd taken a Wound with no slot to fill it: fall Prone, drop what you're holding, and begin Bleed-Out checks per *At Death's Door*. Also inflicts 2 Dissonant Stress.

#### Incidental Damage — choosing the right currency

Not every effect that hurts someone is a Strike. A zone's thorns, an item's spikes, a spell's backlash and a Boss's signature blow all need a way to say *this hurts*, and they must not all reach for the same one. **Impact is only the right answer when a number is going to be compared against a Wound Threshold.** Below that comparison it does nothing at all: **the lowest Wound Threshold in the game is 3**, so an effect dealing a flat 1 or 2 Impact can never fill a Wound Slot on anything, and resolves as 1 Dissonant Stress every single time it fires. Writing *"1 Impact"* is a long way of writing *"1 Dissonant Stress"* — and *"ignoring Armour"* attached to such a value is decorative, because Armour is not what stops it. The base 4 is.

**Four rungs. Pick one; do not invent a fifth.**

| Rung | Use it for | Write |
|---|---|---|
| **1. Incidental** | always-on gear, zone ticks, backlash the caster pays, the price a target pays to escape | **1 Dissonant Stress** |
| **2. Condition** | anything that sets an existing condition | **the condition's name and nothing else** — *"the target is Ablaze"* |
| **3. Gated payload** | a once-per-Scene item, or a Margin 5+ rider that has bought the right to matter | **a real Impact value — 4** |
| **4. Signature** | named Boss abilities, Master-tier magic, Snake Eyes tolls, Relic-tier items, environmental extremes | **1 Direct Wound** (GM Tools, *The Lethal Bypass*) |

**Rung 2 never restates the number.** A condition carries its own cost in its own entry — *Ablaze* is 2 Dissonant Stress a turn, see *The Conditions System* below — and an effect that names a number alongside the condition is a contradiction waiting to happen.

**Rung 3 is 4 because 4 is the base Wound Threshold**, so the rule states itself: **a flat Impact 4 Wounds anything with no Brawn and no armour, and Stresses everything else.** Across the Bestiary that is 8 creatures in 29 — the Fodder tier and the unarmoured Elite specialists, the shamans and assassins and marksmen — while everything carrying muscle or metal takes 1 Stress and walks on. It also gives *"ignoring Armour"* a real job: measured against `4 + Brawn`, a flat 4 that ignores Armour Wounds any Brawn 0 creature however heavily plated it is.

**Rung 4 is expensive and must stay that way.** *The Decisive Blow* (see *Spending Momentum*, above) prices a threshold bypass at **3 Momentum**. Nothing purchasable below Legendary should hand one out for free.

**`+N Impact` as a rider on a real attack is not on this ladder, and is always fine** — it modifies an Impact that is already being calculated, and it works.

#### The Death Spiral (Stress Conversion)

Weapons are not the only things that cause Wounds. Wounds are inextricably linked to a character's mental state.

- If a character's Stress Limit is maxed out, any further Stress they take instantly converts into physical Wounds. This means a character can suffer lethal trauma simply from the systemic shock of freezing temperatures, absolute exhaustion, or the mystical blowback of channelling too much raw Arcane energy.
- **The one exception — `non-Lethal` sources.** Stress from a **`non-Lethal`** weapon or effect never converts. Against a full Stress track it is not applied at all: no Wound, no further Stress. The target gains the **Unconscious** condition instead. This is the whole point of a sap, a cudgel-butt or a chokehold — it is how you take someone alive, and it is the only way a full Stress track resolves without blood.

#### Structural Damage and Destruction

Doors, walls, ropes, ships and the sword in an enemy's hand all break under the same maths as a body. **An object has a Wound Threshold and Wound Slots, and Impact is compared to them exactly as it is for a creature.** There is no separate subsystem to learn.

**Objects are Wounds only.** They have no Stress track, no Momentum Bank, and no Activation. Nothing about panic applies to a crate.

**Resolving the attack.**

- **An unattended object does not defend.** Roll the relevant Skill — Melee for a swing, Ranged for a shot, Athletics for a shoulder against a door — as an **unopposed check vs TN 8**, and read Impact off the standard unopposed formula: **Margin over the TN, plus Weapon Power**.
- **A held or worn object defends with its owner.** Striking the blade out of someone's hand, or splitting the shield they are hiding behind, is an **opposed Clash against the wielder**, resolved normally. You are fighting the person, not the object.

**Structural Damage Reduction (SDR).** Fortification-grade material — worked stone, iron plate, packed earthwork — carries a flat **SDR**, subtracted from incoming Impact before it is compared to the Wound Threshold. It is the object equivalent of the **Plated** trait's flat reduction. Ordinary objects have none.

**Reading the result.** The Wound bands work exactly as they do on a creature, and an object's “Wound Slots” are the **Damaged → Ruined** condition track Hardware already defines:

- **Impact ≥ Threshold:** mark 1 slot.
- **Impact ≥ 2× Threshold:** mark 2 slots — the same massive-trauma doubling a body takes.
- **Impact ≥ 3× Threshold:** the object is **Ruined outright**, regardless of how many slots it had left. This is Overwhelming Trauma's counterpart: a cannonball through a door does not *damage* the door.
- **First slot filled: Damaged.** *(Hardware — a flat −1 to whatever value the item contributes.)* **Last slot filled: Ruined.**

**Wound Threshold and Slots by material.**

| Object | WT | Slots | SDR |
|---|---|---|---|
| Rope, cloth, parchment, glass | 2 | 1 | — |
| Crate, chair, shutter, ladder | 4 | 1 | — |
| Plank door, cart, small boat | 6 | 2 | — |
| Ironbound door, portcullis, wagon | 8 | 2 | 1 |
| Stone wall, pillar, statue | 10 | 3 | 2 |
| **Fortification** — curtain wall, gate, ship's hull | 14 | 4 | 3 |

**Fortifications need `Siege`, or something built to breach.** Per the tag itself (Hardware), a **Siege** weapon can damage a fortification or structure and **halves that Wound Threshold** when comparing Impact. **Devastating does not** — its own text says so. The other route is an effect that explicitly states it damages structures: the **Petard** (Hardware) is the worked example, and it already halves a structure's Wound Threshold *“as Siege does”* despite carrying no Siege tag. A determined party with hand weapons does not breach a curtain wall; they find a gate, a sewer, a cannon, or a charge.

**Tag interactions.**

- **`Siege`:** the gate on fortifications, and halves their Wound Threshold.
- **`Sunder`:** **ignores SDR entirely.** It is the anti-material tag, and this is the same idea as its existing armour-shredding rider applied to an object directly.
- **The Estoc:** on a natural 3 and 4 it ignores Armour *and* SDR, per its own entry.
- **`Devastating`:** works on creatures of any Scale but **grants no benefit against fortifications.**

**What this should feel like at the table.** A Green fighter with Melee 3 and a Power 2 axe breaks glass or rope on most swings (83%), works through a crate in a round or two (58% a swing), **has to really want it to chop a plank door down (28% a swing)**, and cannot scratch worked stone at all. **Breaking in is loud, slow and often impossible — picking the lock remains the faster and quieter route**, and Thievery keeps its job. A Ship's Gun, by contrast, breaches a curtain wall on well over half its shots, which is what a siege is supposed to look like.

---

## At Deaths Door

When a character takes a Wound and cannot fill a wound slot, they immediately fall Prone, drop their weapons, and gain the **Incapacitated** condition.

**1. The Activation Order (Bottom of the Barrel)** An Incapacitated character's Activation Order is ignored — it is a static value (6 + Reflex, per Metal meet Flesh), not a roll, and nothing about being Incapacitated changes it. They automatically act at the absolute bottom of the turn order. If multiple characters are Incapacitated, they act simultaneously at the end of the round.

**2. The Bleed-Out Check** When the character's activation comes up, they can take no Actions or Free Actions. Instead, they must make a desperate roll to cling to life.

- **The Check:** Roll 2d6 + Brawn (or Will, relying on sheer stubbornness) against TN 8.

- **Success (Margin 0-4):** You secure a **Stabilization Mark**.

- **Massive Success (Margin 5+):** Your body forcefully halts the trauma. You instantly gain 3 Stabilization Marks and are Stabilized.

- **Failure:** You secure a **Death Mark**. You are bleeding out or slipping into shock.

- **Fumble (Two natural 1s):** The trauma is too severe. You instantly die.

> [!note] Designer's Note
> This is the one roll in the game that adds an Attribute rather than a Skill. Attributes are derived-only everywhere else, and that rule stands; the Bleed-Out Check is carved out on purpose. Clinging to life isn't a trained competency — there is no skill for refusing to die — so it runs off raw constitution or raw stubbornness. The Attribute cap of 3 also keeps the death save on a tighter band than a Skill's +6 would, which is the intent: nobody becomes reliably hard to kill.

**3. The Outcomes**

- **3 Stabilization Marks:** You are **Stabilized**. You remain Unconscious and Incapacitated, but you no longer have to make Bleed-Out checks. You will survive the combat unless struck again.

- **3 Death Marks:** Your character dies.

### External Interventions & Threats

Because the player is stuck at the bottom of the turn order, the rest of the party has a desperate window to save them.

- **Triage (The Save):** An ally can use an Action to perform a _Medicine_ check (TN 8), use an Alchemical Poultice, or cast  _Stabilize_. If successful, the Incapacitated character instantly becomes Stabilized, stopping the Death Marks.

- **The Coup de Grâce (The Threat):** If an Incapacitated character is hit by a melee attack action they do not calculate Impact. They immediately suffer 1 automatic Death Mark. If the attacker uses the uses their whole activation, the character is instantly killed.

---

#### The Breather (Universal Action)

 The party barricades a room, binds their bleeding, and tries to calm their racing hearts. It is a desperate pause, not a comfortable rest.

- Time Requirement: 30 uninterrupted in-game minutes.

-  The Cost: Every participating player immediately empties their Momentum Bank to 0. The adrenaline fades.

- The Effect: All accumulated Dissonant Stress is completely wiped away. The Death Spiral is reset, and players lose their negative dice modifiers.

- The Limitation: A Breather cannot heal physical Wounds, and it cannot clear Locked Stress.
- At The conclusion of a Breather the party rolls their Community Supply Die (if they have one), if a 1 or 2 is rolled, the die reduces one category. on a 3+ all is ok.

## Long Rest

A period of secure, undisturbed rest — a night at an inn, a fortified wilderness campsite, anywhere the GM narrates as safe — lasting at least 8 hours, during which a character does nothing more strenuous than eating, drinking, and uninterrupted sleeping. A Long Rest is separate from a Downtime period (see *Soothing the Soul*, Section 1): it needs no PP Budget or Settlement Tier, and can happen mid-adventure between combats, not just in town.

- **Effect:** Clears all accumulated Dissonant Stress, and 1 point of Locked Stress. No check is required.
- **Limitation:** A Long Rest cannot touch **Attunement** Locked Stress — nothing can, while the item is worn (see the Golden Rules). Among the routes that reach *clearable* Locked Stress this is the only one that is free, automatic and available to everyone regardless of Faith; the alchemical preparations in Hardware also reach it, at a cost. It's deliberately modest (Religious Pursuit's own guaranteed floor is Will score, minimum 1, and scales upward), so a Long Rest never outperforms a successful Tithe of Will, only guarantees a small amount to everyone regardless of Faith.
- **Supplies:** At the conclusion of a Long Rest, the party rolls their Community Supply Die exactly once (per Hardware) — the same single roll as a Breather, covering the whole night's consumption rather than scaling with its extra length. If the Die is Depleted, this Long Rest's Stress-clearing effect doesn't happen at all: no clean bandages, no hot food, no real rest either.

---

## The Conditions System
### Negative Conditions:

- *Incapacitated:* Prone and Helpless, dying requiring Bleeding out checks.

- *Unconscious:* You are **Prone** and **Helpless**. You take no Actions, Free Actions or Reactor actions, and you cannot Clash. Your Activation is skipped entirely. You are **not** dying and make no Bleed-Out checks — this is the Stress track's equivalent of Incapacitated, not a milder version of it.
    - **Gained:** when your Stress Limit is full and you take further Stress from a **`non-Lethal`** source (see The Death Spiral — Stress Conversion), or from any effect that says so.
    - **Cleared:** the instant your Stress track is no longer full — by Adrenaline Flush, an alchemical preparation, a Breather, or an ally clearing your Stress. An ally may also spend an Action on a **Medicine check vs TN 8** to rouse you, exactly as Triage works on an Incapacitated character. Otherwise it ends when the scene does.
    - **The Coup de Grâce still applies.** An attacker in melee may leave you where you lie, or finish the job: the attack automatically wins its Clash, and a Wound taken with no defense and no slot to fill makes you **Incapacitated** and dying. A `non-Lethal` weapon cannot do this at all. Killing an unconscious body is a second, deliberate decision — never an accident of the dice.

- *Helpless:* You cannot defend. Any attack against you automatically wins its Clash, with no roll and no Reactor action. Impact is calculated as an unopposed hit.

-  *Prone:* You are on the ground. You suffer Disadvantage on all Clashes. It costs a Move Action or 1 Momentum to scramble to your feet.

- *Blinded:* (Dirt in the eyes, magical darkness). You cannot take attack actions against targets beyond 5 feet. All Reactor Clashes are made with Disadvantage.

- *Poisoned:* At the start of your turn, make an Athletics check. On a failure, you instantly take 1 Dissonant Stress. (If you max out your Stress while Poisoned, the toxin causes a Wound).

-  *Bleeding:* At the beginning of each of your activations can spend a Momentum to “stem the wound”, or make an Athletics check. Succeed Lose the Bleeding condition. Fail, lose a wound.

- *Fatigued:* Gain 1 Locked Stress. If a circumstance causes an additional instance of this condition, gain another locked Stress. If at the stress limit, no more locked stress can be assigned. This condition can only be cleared by a Long Rest or magical Restoration.

- *Terrified:* Your mind is clouded by panic. 1 stress is locked. You cannot spend Momentum for any reason. You must spend your turn running away from the object/being causing the Terror, fleeing until you can hide, or break the complete line of sight. When out of sight or hidden from the object/entity you can take a Resolve check to shake the condition.

- *Fear:* 1 stress is locked, until fear condition is lost. Has disadvantage against the object/being causing the Fear condition. must Pass a Resolve check to make Attack actions or interact with the object/being causing the fear. Cleared by taking the regroup action when out of sight or has cover from the object/enemy causing fear, or immediately and automatically if the source of the Fear is destroyed or removed from the scene.

- *Distracted:* suffer a - 1 to rolls until next activation, then lose the condition.

- *Confused:* Your thoughts will not hold still. At the start of each of your Activations, make an **Insight or Resolve check vs TN 8** — your choice, wits or willpower. **On a pass you act normally and the condition ends.** On a failure you lose the Activation entirely, standing dumbfounded: no Action, no Move, no Free Action. You may still take Reactor actions — you are bewildered, not helpless.

- *Cursed:* (Magical). Healing magic (like Mend Flesh or Surge of Relief) has no effect on you, and Alchemical draughts taste like ash, providing no benefit.

- *Hexed:* (Magical). A minor curse rides on you, waiting for the moment you need steadiness most. **The next roll you make — an Aggressor Strike or a Reactor defense, whichever comes first — suffers Disadvantage.** The condition is spent the instant that roll is made, whichever kind it turned out to be.

- *In-Fighting:* All 1H weapons without Close-Quarters suffer Disadvantage. 2H weapons cannot be used.

- *Surprised:* Rolls suffer Disadvantage.

- *Grappled:*  can only take limited actions. Strike: does not break or control the grapple, unless the target becomes incapacitated, then participants loose the grappled condition. Grab: to take control of the Grapple, meaning to maintain grappling, or move the participants 5ft in a chosen direction. Shove: To break free of the Grapple. Cannot Block, Parry, Dodge.

- *Anchored*: (The Movement Lock)
	- **The Mechanic:** The character’s movement speed is reduced to 0.

	- **The Engine Interaction:** Because their feet are pinned, an Anchored character completely loses the ability to use the **Dodge** action in a Clash. They must rely on **Block** (shield), **Parry** (weapon), or **Brace** (taking the hit).

	- **Clearance:** Cleared when the effect ends, or by using the _Regroup_ action to physically tear free.

- *Rigor:* (The Articulation Lock) A severe stiffening of the joints, caused by nervous system shock, extreme cold, or necromancy.
	- **The Mechanic:** The character's movement is halved.

	- **The Engine Interaction:** Because they cannot fluidly articulate their wrists or shift their weight, a character suffering from Rigor completely loses the ability to use the **Parry** or **Dodge** actions. If attacked, they must use **Block** or **Brace**. Furthermore, any Attack action they attempt suffers **Disadvantage**.

	- **Clearance:** Fades automatically at the end of their next turn as the blood flow normalizes.

- *Ablaze:* (The Attrition Tax) Active, ongoing environmental destruction to the character's physical body or gear.
	- **The Mechanic:** At the absolute start of the character’s turn, before they can move or act, At the start of your turn, the agonizing heat causes you to suffer 2 Dissonant Stress before you can act.

	- **The Engine Interaction:** It creates a brutal, ticking clock. A player cannot ignore it, or it will mathematically chew through their Stress Limit and push them into the Death Spiral without an enemy ever swinging a sword.

	- **Clearance:** The character _must_ spend their turn taking the _Regroup_ action (stopping, dropping, and rolling) to extinguish the flames.

- *Drowned:* (The Rising Tide) The lungs burn, the light above the surface gets smaller, and the pressure keeps mounting.
	- **The Mechanic:** The character suffers Disadvantage on all rolls. At the start of their turn, before they can move or act, they suffer 1 Dissonant Stress as their body burns through the last of its air.

	- **The Engine Interaction:** Slower and quieter than Ablaze's clock, but just as inescapable if ignored — it doesn't force a specific reset action, it just keeps draining until the character gets clear of the water or breaks whatever's holding them under.

	- **Clearance:** The character (or an adjacent ally spending an Action) may attempt an **Athletics check (TN 8)** to reach the surface and clear the condition. Automatically cleared if the character is physically removed from the water.

- *Suppressed:* (The Discipline Tax) _The relentless, disciplined pressure of coordinated fire makes anything but hunkering down feel like an invitation to disaster. _
	- **The Mechanic:** While Suppressed, if the character takes any action other than Attack, Block, Brace, or Regroup, that action is made with Disadvantage, and the character immediately suffers 1 Dissonant Stress from breaking cover under pressure.

	- **The Engine Interaction:** Suppressed doesn't stop a character from doing something risky — it makes doing anything except holding their ground and fighting back cost real Stress. It pushes the target toward committing to the exchange rather than repositioning or using utility actions.

	- **Clearance:** Fades automatically at the start of the Suppressed character's next turn if they're no longer in line of sight of the source. Otherwise cleared via the Regroup action.

### Positive Conditions:

- *Blessed:* (Granted by Faith magic or holy sites). You feel the weight of the divine. You ignore the first point of Stress you would take in a scene.

- *Inspired:* gain advantage on non-combat checks for a scene.

# Chapter 2 — The Marrow

*Character Creation & Advancement*

## Character Creation: The Novice Hero
Creating a character in this system is about deciding how you survive. You have a pool of points to define your raw talent (Attributes) and your specific training (Skills).

The Golden Rule of 3: The maximum score an Attribute or Skill can have at character creation is 3.

- Step 1: Select Race.
- Step 2: Determine Attributes (Raw Potential).
	- 4 DP to spend
- Step 3: Distribute skill points (Practical Training).
	- 8 DP to spend (9 for a Human, or a Half-Elf who took Adaptable)
- Step 4: Select 2 Feats.
	- Tier 1 only.
- Step 5: Outfit the character.
	- **80 sp to spend.** See *The Starting Purse* below.
    - The Party Community Supply Die starts at a **d8** (a d10 is the restocked ceiling, not the starting state — see *Hardware*).

### The Starting Purse

You begin with **80 silver pieces** and buy your own kit from Hardware. There is no free armour pick — a breastplate is a breastplate whether you are wearing it in Chapter 1 or Chapter 9, and it costs what it costs.

**Availability: Scarce or lower.** You kitted out in a settlement with a market and a working forge — a Town, in the language of Soothing the Soul — not a guild-hall trade hub. Rare-tier goods are sourced from a City or better and are not available to a starting character at any price. They are something you acquire in play, through Acquisition, Commission, or the point of a sword.

**Enchanted and Relic items are unavailable at creation**, regardless of their availability tier or price. Attunement is a bond formed in play, not a purchase. A Green character has not yet made one.

**Free with the kit — these do not come out of the 80 sp:**

- A standard **Backpack and Belt**, and the mundane clothes you stand up in.
- **A caster's focus, if a Tier 1 feat granted you one.** *Arcane Awakening* and *Arcane Dabbler* grant a Grimoire; *Divine Conduit* and *Ritualist* grant a Holy Symbol. These are the instruments of the feat, not equipment purchases, and neither tradition pays for what the other gets free.

**Everything else comes out of the purse** — armour, weapons, shields, ammunition, tools, consumables, and whatever coin you choose to keep in your pocket rather than spend. Unspent silver stays yours.

**Grip still constrains the loadout.** The purse governs what you can *afford*; the Grip rules in Hardware govern what you can *hold*. Two 1-Handed items, or one 2-Handed item — a Greatsword leaves no hand for a shield, and a Grimoire must be wielded in one hand with the other free to cast without penalty.

> **A note on the trade.** 80 sp buys a Chain Shirt and very little else, or it buys a Gambeson and a workshop's worth of rope, lockpicks, oil, and caltrops. Armour is roughly two-thirds of any heavily-armoured kit, and every point of Wound Threshold you buy is bought with something you now do not own. That is the intended shape of the choice. A character who walks out of Step 5 with nothing left over has made a real decision, not a mistake.

---

## Species

 **Human (The Resilient Adapters)**

_Humans in gritty fantasy aren't the strongest or the fastest, but they have sheer grit and adaptability. They outlast others through willpower and versatility._

- **Size:** Standard.
- **Move Value:** 30 ft/6 squares
- **Adaptable:** Humans gain **1 extra Skill DP** at character creation to represent their varied backgrounds and quick learning. *(DP, not a free rank — a Human's creation Skill budget is 9 rather than 8. This does **not** unlock Rank 6 at creation; see the Skill Costs ladder.)*
- **Indomitable Spirit:** Humans have a slightly higher breaking point. Their base Stress Limit is increased by +1.
- **Steady, Not Sharp (Drawback):** Humans burn slow and steady rather than bright. Their Momentum Bank cap suffers a **-1**  — they rarely hit the adrenaline peaks a specialist can chase down.
- **Playstyle:** The perfect blank slate. They can flex into any role, and that extra point of Stress gives them just a little more breathing room before they panic or break — but they'll be the last one at the table to cash in a 3-Momentum Ultimate.

**Half-Elf (The Bridge Builders)**

_Possessing the ambition of humans and the grace of elves, Half-Elves are charismatic wanderers who fit in everywhere but belong nowhere._

- **Size:** Standard
- **Move Value:** 30 ft/6 squares
- **Silver-Tongued:** Half-Elves have a supernatural knack for reading a room. They gain Advantage on Influence checks when trying to persuade, de-escalate a fight, negotiate, or gather information.
- **Split Heritage:** They may choose either the Human's Adaptable trait (1 extra Skill DP) or the Elf's Fey Reflexes trait (Advantage to dodge hazards) — and inherit that race's paired drawback along with it. Choosing Adaptable also imposes **Steady, Not Sharp** (Momentum Bank cap - 1); choosing Fey Reflexes also imposes **Hollow-Boned** (-1 Wound Threshold). You cannot take the trait without its cost — that cost is what the source race actually paid for it.
- **Between Worlds (Drawback):** Half-Elves suffer Disadvantage on Influence checks when dealing with an insular or homogeneous community that has had little contact with outsiders — an isolated Elven enclave, a xenophobic frontier hamlet, a closed guild.
- **Playstyle:** The ultimate face characters and versatile support pieces — everywhere except the one room that's never trusted an outsider.

**Half-Orc (The Relentless Brutes)**

 Born of two worlds and often shunned by both, Half-Orcs survive through raw intimidation and a terrifying physiological ability to push through lethal pain.

-  Size: Standard.

- Move Value: 30 ft/6 squares

- Blood Frenzy: When a Half-Orc suffers a Wound, the adrenaline spikes. They immediately clear 1 Dissonant Stress. (This creates a terrifying dynamic where injuring them clears their panic and focuses their rage).

-  Menacing: Half-Orcs gain Advantage on Influence checks, when attempting to intimidate anyone smaller or weaker than them.

- Outcast (Drawback): They face deep-seated prejudice. They suffer Disadvantage on Social/Persuasion checks when dealing with civilized strangers who don't know them.

-  Playstyle: Berserkers and shock troopers who actually become more mentally stable (mechanically) when the blood starts flowing.

**Halfling (The Unseen & Unbothered)**

 In a world of towering monsters and lethal blows, Halflings survive by not being noticed and having an uncanny knack for slipping out of danger at the last possible second.

- Size: Small.

- Move Value : 30 ft/6 squares

-  Underfoot: Because of their size, Halflings gain Advantage on Stealth checks as long as they have cover, obscured, or are moving through the space of larger creatures.

-  Halfling Luck: Once per session, a Halfling may completely ignore the mechanical effects of a Fumble (Snake Eyes). They still fail the action, but they do not take the Stress penalty.

-  Small Stature (Drawback): They physically cannot wield weapons carrying the Cumbersome tag. Unlike other Small-Scale creatures, this does not extend to the standard Scale −1 penalty to Stress Limit (Metal meet Flesh) — a Halfling's nerve holds up regardless of size.

-  Playstyle: Stealthy opportunists who excel at avoiding the brutal consequences of the system's lethal dice spikes.

**Elf (The Ancient & Graceful)**

_Elves are attuned to magic and the natural world. They are blindingly fast and perceptive, but lack the physical density of the heavier races._

- **Size:** Standard.
- **Move Value:** 30 ft/6 squares
- **Fey Reflexes:** Elves gain Advantage (roll 3d6, keep the highest two) on Acrobatics checks to avoid environmental hazards, traps, or area-of-effect abilities.
- **Trance:** Elves do not sleep deeply. They only require 4 hours of meditation to gain the benefits of a full night's rest (clearing Stress and Stabilizing wounds), making them excellent watchmen.
- **Hollow-Boned (Drawback):** Their lithe frames are susceptible to trauma. Their base Wound Threshold is reduced by 1. _(This drawback travels with Fey Reflexes if a Half-Elf takes it via Split Heritage — see Half-Elf.)_
- **Playstyle:** Agile skirmishers or perceptive scouts. They avoid getting hit because if they do get hit, they go down faster.

**Dwarf (The Ironclad Survivors)**

 Dwarves are built like brick outhouses. They are dense, stubborn, and completely at home in the dark, punishing environments of the deep earth.

- Size: Standard.

- Move Value: 30 ft/6 squares

- Stone-Bones: Dwarves are incredibly dense. Their base Wound Threshold is increased by +1. (This is huge in this system, effectively granting them the hardiness of a higher Brawn score without breaking the Attribute cap).

- Subterranean Senses: Dwarves gain Advantage on Notice checks while underground, or when examining stonework/engineering.

- Stumpy (Drawback): Their short legs make open-ground sprints difficult. They suffer Disadvantage on Athletics checks during chases or when trying to sprint across open battlefields.

- Playstyle: The ultimate frontline anchors. They can take a beating and hold a choke point better than anyone.

---

## Attributes and Derived Stats

Attributes are not added to your Checks. They do two things: they set the
ceiling each Skill can be trained to, and they determine your derived stats.

- *Brawn:* Strength and physical power. Feeds Wound Threshold.
- *Reflex:* Speed and coordination. Feeds Momentum Bank and Activation Order.
- *Wits:* Logic and mental processing. Feeds Stress Limit.
- *Will:* Resolve and spiritual weight. Feeds Stress Limit.

- *Wound Threshold:* **4 + Brawn + Armour Value + Species Bonuses +
  Scale bonus + Misc. mods**
- *Stress Limit:* **4 + Will + Wits + Feat Bonus + Species bonus.**
	- When your total Stress (Locked + Dissonant) reaches this limit — the
	  track is full — your mental focus shatters: all current Locked Stress
	  immediately becomes Dissonant (except Attunement Locked Stress),
	  applying its full penalties. Any further Stress converts into Wounds,
	  or into Unconscious if from a non-Lethal source.
- *Momentum Bank:* **4 + Reflex**
- *Activation Order:* **6 + Reflex**

**Attributes (capped at +3 Max)**
**Skills (capped at Associated Attribute + 3, absolute maximum +6)**

### Determine Attributes

You have 4 Development Points to distribute among your four Attributes.
All Attributes start at 0, and no Attribute may exceed 3.

At four points there are only four possible shapes. Pick one, then assign
its values to whichever Attributes you like.

| Array | Spread  | Skill Ceilings | What it buys you                                                                       |
| ----- | ------- | -------------- | -------------------------------------------------------------------------------------- |
| Spike | 3/1/0/0 | 6 / 4 / 3 / 3  | One skill that can eventually reach the mortal ceiling. Everything else stays capable. |
| Twin  | 2/2/0/0 | 5/5/3/3        | Two strong pillars, neither of them absolute.                                          |
| Broad | 2/1/1/0 | 5/4/4/3        | One strength, wide competence beneath it.                                              |
| Flat  | 1/1/1/1 | 4/4/4/4        | No weaknesses, no peak. Derived stats spread evenly across every track.                |

Every array is worth exactly four points of derived stat, however you
assign it. There is no efficient choice — only different shapes.

- Brawn: Physical power, strength, and brute force.
- Reflex: Speed, precision, and fine motor control.
- Wits: Intellect, observation, and applied knowledge.
- Will: Presence, grit, and mental fortitude.

Your array is a starting shape, not a permanent identity. The first
Attribute you raise through Advancement takes you to five points and off
every array for good.

Calculate your survival metrics based on your Attributes and gear choices.

- Wound Threshold: 4 + Brawn + Armour + Species Bonuses + Scale + Misc.
  (Impact required in a single hit to cause a physical Minor Wound.)
- Stress Limit: 4 + Wits + Will + species bonus + Feat bonus.
  (Your mental fatigue pool. Once filled, taking more Stress causes Wounds.)
- Momentum Bank: 4 + Reflex.
- Activation Order: 6 + Reflex.
- Wound Slots: All characters have exactly 3 Wound Slots. Taking a 4th
  wound leaves you Incapacitated.

---

## Determine Skills

You have 8 DP to distribute among the Broad Skills — **9 if you are a Human, or a
Half-Elf who took Adaptable**. All Skills start at Level 0.

The Ceiling Rule: a Skill can never be trained higher than its Associated
Attribute + 3, to an absolute maximum of +6.

| Associated Attribute | 0 | 1 | 2 | 3 |
|----------------------|---|---|---|---|
| Skill Ceiling        | 3 | 4 | 5 | 6 |

An Attribute of 0 does not lock you out of a Skill — it caps how far that
training can take you. Anyone can learn to fight. Not everyone has the frame
to become a master of it.

Skill Costs:

| Rank | Cost | Cumulative |
|------|------|------------|
| 1–4  | 1 DP each | 4 DP  |
| 5    | 2 DP      | 6 DP  |
| 6    | 3 DP      | 9 DP  |

Rank 6 cannot be reached at character creation, **regardless of budget**. This is
a flat rule, not an arithmetic consequence — a Human, or a Half-Elf who took
Adaptable, has 9 Skill DP at creation, which is exactly what Rank 6 costs, and
still cannot take it. The mortal ceiling is something you climb to across a
campaign, not something you start at. A creation character who spends 6 of their
8 points reaching Rank 5 is a genuine prodigy with almost nothing else to their
name.

The nine Skills under Brawn and Reflex are collectively the Physical Skills.
Rules that reference "Physical Skills" as a category mean these.
##### Brawn Skills

- Melee: Close-quarters combat, from greatswords to brawling.

- Athletics: Raw physical exertion and mobility (climbing, swimming, sprinting, jumping).

- Block: Using the haft of your spear, effective with a shield

- Prowess: Raw physical control over yourself or an opponent — grappling, shoving, and bracing to absorb a hit. Governs the Grab, Shove, and Brace actions.

##### Reflex Skills

- Ranged: Accuracy with projectile weapons (bows, crossbows, throwing axes).

- Stealth: The art of going unnoticed in shadows or crowds.

- Thievery: Fine manipulation under pressure (locks, traps, sleight of hand).

- Acrobatics: agility, balance, coordination, and finesse in manoeuvring their body.

- Ride: a celestial beast, a griffin, battle ram or a donkey.

##### Wits Skills

- Notice: Active and passive perception and investigation, deals with the physical world and sensory input.

- Insight: focuses on social interpretation, reading motives, and identifying lies.

- Medicine: Medical triage, applying trauma kits, and stabilising wounds.

- Crafting: Alchemy, forging, and repairing gear,Invent, build, create, distill.

- Lore: A character's formal or practical education. Covers history, geography, heraldry, and identifying monsters.

- Arcana: The mastery and Understanding of arcane channelling and cosmic energy.

##### Will Skills

- Influence: The universal social skill. Covers persuasion, intimidation, deception, and leadership.

- Faith: understanding and manifesting Divine miracles, healing, and holy wrath

- Survival: Tracking, foraging, and enduring harsh environments.

- Resolve: Resolve is your mental fortitude, your ability to resist fear, pain, and manipulation.

---

## Feats
### Tier 1 Blood and Rust

**Arcane Awakening**

* Prerequisites: Arcana 1, Wits 1.

>You have forced your mind to perceive the volatile geometries of the world.

* Mechanic: **Choose one Paradigm.** You gain a Grimoire containing 4 Novice Arcana spells, drawn from the Common list, your chosen Paradigm's list, and/or any other Paradigm's Novice list. You may manifest these spells using the Arcane Margin mechanics whenever you meet The Casting Requirements — Grimoire wielded in one hand, other hand free (see Embracing the Abyss). Casting without them is Blind Casting. Spells from your chosen Paradigm benefit from **Paradigm Mastery**: a Messy Success (Margin 0–2) resolves as a Clean Success instead. Common spells and spells from other Paradigms never benefit from Mastery. Since every Paradigm's Novice tier holds exactly 3 spells, every Arcane Awakening character takes at least 1 spell from outside their chosen Paradigm — Common or another Paradigm's Novice list — among their starting 4, regardless of which Paradigm they picked. This loosening is Arcane-only: Faith casters remain locked to the Common Prayer list and their chosen Domain, unless they walk the Heretic's Path. _(Additional spells — in- or off-Paradigm — are learned later through Advancement; off-Paradigm spells cost a +1 DP surcharge and never gain Mastery, but they're never feat-gated or forbidden.)_

**Arcane Dabbler**

* Prerequisites: Arcana 1.

>You never opened the deeper books. You learned the two or three things that work and stopped there.

* Mechanic: You gain a Grimoire containing a number of **Novice** Arcane spells equal to your Arcana rank, drawn from the Common list and/or any Paradigm's Novice list. This total is recalculated whenever your Arcana rank changes — raising the skill is how a Dabbler learns. You manifest them using the Arcane Margin mechanics whenever you meet The Casting Requirements (see Embracing the Abyss); casting without them is Blind Casting. **You choose no Paradigm**, and therefore never benefit from Paradigm Mastery — every Messy Success (Margin 0–2) costs you the Dissonant Stress, always. You may purchase further Arcane spells through Advancement at the off-Paradigm +1 DP surcharge, but **never above Novice tier**. Breadth without depth is the whole bargain.

**Divine Conduit**

* Prerequisites: Faith 1, Will 1.

>You have tethered your physical form to a higher authority — or convinced yourself you have.

* Mechanic: Choose one path when you take this feat:

    - **The Covenant:** Bind yourself to one Domain. You gain a Holy Symbol, that Domain's Domain Tag, and 4 Novice Prayers drawn from the Common Prayer list and/or your chosen Domain's list. This binding is permanent — your Holy Symbol can never hold Prayers blessed by a different entity. No exceptions; no later switching.
    - **The Heretic's Path:** Bind yourself to no single power. You gain a Holy Symbol and 4 Novice Prayers drawn from the Common Prayer list and/or **any combination** of the seven Domains' lists. You never gain a Domain Tag — no entity has claimed you long enough to bless you — and you roll every Tithe of Will check with **Disadvantage** (3d6, keep the lowest two) for as long as you walk this path. Nothing you channel is trusting you by default; you're convincing it fresh, every time.

As long as you speak the litany and bear your symbol, manifest these Prayers by rolling the Tithe of Will and paying their Locked Stress cost.

> [!note] Designer's Note
> Any future feat or item that grants "additional Prayers from your Domain" should be read as "from any Domain's list" for a character on the Heretic's Path.

**Ritualist**

* Prerequisites: Faith 1.

>You know the forms. You say the words correctly. Nothing has ever answered you by name.

* Mechanic: You gain a Holy Symbol and a number of **Novice** Prayers equal to your Faith rank, drawn from the Common Prayer list and/or any Domain's Novice list. This total is recalculated whenever your Faith rank changes — raising the skill is your only route to new Prayers, since you have no Chosen Domain to learn from through Advancement. You manifest them by rolling the Tithe of Will and paying their Locked Stress cost, exactly as any Priest does. **You bind yourself to no Domain**: you gain no Domain Tag, and you can never learn an Adept or Master Prayer by any route. _(This is what separates a Ritualist from the Heretic's Path: the Heretic keeps full access to every tier and pays permanent Disadvantage on the Tithe for it. You pay no penalty, and the ceiling is the price.)_

**Battlefield Orator**

* Prerequisites: Influence 2

>You don't need a blade to break a formation — just the right word, aimed well.

* Mechanic: Spend an Action in combat to shout orders, hurl insults, or rally the line. Choose one: An ally immediately clears 1d6 Dissonant Stress, OR an engaged enemy suffers a -2 penalty to their next Defense roll due to distraction/fear.

**Callous Pragmatism**

* Prerequisites: Will 1, Wits 1

>Pity gets you killed. Focus gets you out.

* Mechanic: If you witness an ally take a Wound or fall Incapacitated, your survival instincts override panic. You may immediately use a Free Action to bank 1 Momentum.

**Calloused Lungs**

* Prerequisites: Survival 1

>You've breathed in worse.

* Mechanic: When you fail an environmental Hazard check (such as navigating a toxic swamp or freezing blizzard), you take 1 less Locked Stress from the resulting penalty (to a minimum of 1 Locked Stress).

**Cold Reader**

* Prerequisites: Insight 1, Notice 1

>You know who breaks first.

* Mechanic: When you first enter a tense social situation, you may use a Free Action to roll Insight against a baseline TN 8. On a success, the GM reveals which NPC in the room has the lowest Resolve score, and you gain Advantage (roll 3d6, keep the highest two) on your first Influence check against them.

**Covering Fire**

* Prerequisites: Ranged 2

>You are not trying to hit him. You are trying to make him stay exactly where he is.

* Mechanic: Instead of a Shoot that resolves Impact, you may loose to suppress. Choose one target within your weapon's range that you can see: they must pass a Resolve check (TN 8) or gain the **Suppressed** condition (Iron Core) — Disadvantage on any action other than Attack, Block, Brace or Regroup, and 1 Dissonant Stress for breaking cover under pressure. This replaces your attack entirely and deals no damage on any result.

**Desperate Edge**

* Prerequisites: Resolve 1

>You fight hardest with your back against the wall.

* Mechanic: When exactly one of the two dice in a 2d6 check shows a 6, and you are in a qualifying desperate state — at half or more of your Stress Limit in Dissonant Stress, or at your final Wound Slot — you may treat that die as exploding: roll one additional d6 and add it to the total. Outside a qualifying desperate state, or without this feat, a lone natural 6 is just a 6.

**Dung-Healer's Salve**

* Prerequisites: Medicine 1 or Crafting 1

>It smells awful, it burns terribly, but it stops the bleeding.

* Mechanic: A Breather cannot normally heal Wounds — this feat is the exception. During a Breather, you can forage mundane mud, moss, and strong alcohol and perform a Medicine check to heal a Wound Slot. Healing a Wound this way inflicts 1 Locked Stress on the patient due to the sheer agony, but restores the Wound Slot.

**Gallows Humour**

* Prerequisites: Influence 1 or Resolve 1

>You find the punchline at the end of the world.

* Mechanic: When taking a Breather, if you recount a recent harrowing experience or near-death encounter, you and all allies participating in the rest may each clear 1 point of **clearable** Locked Stress. **Attunement Locked Stress is never eligible** (see Iron Core's Golden Rules).

**Haggler’s Scorn**

* Prerequisites: Influence 1

>You are unfazed by threats when coin is on the table.

* Mechanic: You ignore the standard social penalties of dealing with hostile environments. When attempting to buy, sell, or trade information, you treat NPCs/settlements with a Hostile stance as if they were Neutral for the purposes of setting prices and negotiating terms.

**Hipshot**

* Prerequisites: Ranged 1, Reflex 1

>The bow is already up. Whether there is room for it is his problem, not yours.

* Mechanic: You ignore the Disadvantage the **Point-Blank** range band imposes on ranged attacks (Metal meet Flesh — Ranges), whether or not your weapon carries the **Sidearm** tag. Being inside someone's Threat Zone no longer costs you your shot.

**Iron Grip**

* Prerequisites: Melee 1 or Prowess 1

>You don't let go when the steel catches.

* Mechanic: During the Engagement Flow, if you tie on a Clash and the weapons bind (ending the engagement), you automatically bank 1 Momentum as you secure a superior physical footing for the next exchange.

**Ledger of the Deep**

* Prerequisites: Insight 1 or Lore 1

>Every entity has a name, a nature, and a price. Once you know all three, it stops being able to surprise you.

* Mechanic: On a Massive Success (Margin 5+) on an Insight or Lore check made to identify a creature, curse, or occult phenomenon, you immediately bank 1 Momentum — what you've read about the abyss becomes leverage, not just trivia.

**Lethal Strikes**

* Prerequisites: Melee 1

>Your knuckles are as dense and dangerous as rusted iron.

* Mechanic: Your Unarmed strikes can deal Lethal impact and can cause physical Wounds.

**Long Eye**

* Prerequisites: Ranged 1, Notice 1

>Everyone can see that far. Not everyone can shoot that far.

* Mechanic: You ignore the Disadvantage the **Long** range band imposes on ranged attacks (Metal meet Flesh — Ranges). **Extreme** range is unaffected — it still imposes Disadvantage, and the target must still be completely in the open.

**Practised Hands**

* Prerequisites: Ranged 1

>Once a fight, the crank turns like it is greased.

* Mechanic: Once per Scene, you may reload a weapon carrying the **Reload** or **Heavy Reload** tag as a Free Action instead of spending an Action on it.

**Quick**

* Prerequisites: Reflex 1

>The world moves like sludge when the adrenaline hits.

* Mechanic: +3 to your Activation Order, and break ties against others without Quick.

**Scavenger’s Eye**

* Prerequisites: Wits 1, Stealth 1 or Survival 1

>Paranoia is just a high-functioning survival instinct.

* Mechanic: When you achieve a Massive Success (winning by 5+) on an exploration or scouting check. You gain 2 points of Momentum instead of the standard 1.

**Scholarly Resonance**

* Prerequisites: Arcana 2

>Locked Stress isn't just the price of a working — it's a live current running under your skin, wherever it comes from.

* Mechanic: While you have at least 1 point of Locked Stress (from an Overcharge, an Attuned item, an environmental hazard, or a hostile effect), you gain +1 SV (Shield Value) against magical effects as the excess energy forms a protective harmonic shell.

**Shadow-Weaver**

* Prerequisites: Stealth 1

>You move without displacing the air around you.

* Mechanic: You ignore the standard penalty for moving quickly while trying to remain hidden.

**Stoic Resolve**

* Prerequisites: Will 2, Resolve 1

>The mind must be a fortress against the meat-grinder.

* Mechanic: You increase your maximum Stress Limit by +2. Additionally, when you take the Reprieve action, or spend Momentum on Adrenaline Flush, you clear 1 extra point of the relevant Stress type.

**Tactical Mind**

* Prerequisites: Wits 2, Notice 2

>You count the exits and weigh the weapons before anyone even speaks.

* Mechanic: You are always reading the room before weapons are even drawn. You automatically start every combat encounter with 1 Momentum in your bank.

**The Downward Spiral**

* Prerequisites: Wits 1

>When everything falls apart, you find clarity at the bottom.

* Mechanic: If your Stress Limit is maxed out and you are forced into the Death Spiral (Stress converting instantly into Wounds), the shock to your nervous system instantly generates 1 Momentum.

**Trench Fighter**

* Prerequisites: Brawn 1 or Reflex 1

>You are at home in the muck.

* Mechanic: You completely ignore the Disadvantage penalty on checks caused by Difficult Terrain. Furthermore, drawing a weapon whilst engaged doesn't gain disadvantage.

**Whispers in the Dark**

* Prerequisites: Stealth 1, Notice 1

>The best secrets are the ones people think they are keeping.

* Mechanic: You excel at gathering intel from the shadows. As long as you remain successfully hidden, you gain Advantage on Notice checks to eavesdrop, read lips, or observe minor details without breaking your cover.

### Tier 2 Tactical Momentum

> **Every feat in this Tier additionally requires any one Tier 1 feat** you already hold, on top of the Skill and Attribute prerequisites listed on each entry. It is restated on every line so it can't be missed mid-list. See Advancement §4.

**Architect of Ruin**

* Prerequisites: Wits 2, Thievery 2 — plus **any one Tier 1 feat**.

>You see the fatal flaw in every design.

* Mechanic: When examining a lock, mechanical trap, or structural weak point, you can spend 1 Momentum. If you do, you instantly deduce its precise mechanism, allowing you to automatically pass the Thievery check to bypass or disable it without rolling—completely eliminating the risk of a Fumble.

**Combat Scholar**

* Prerequisites: Reflex 1, Arcana 2 — plus **any one Tier 1 feat**.

>You are used to the chaos of the battlefield.

* Mechanic: When you are forced into Blind Casting (casting with your Grimoire stowed, your hands full, or both — see The Casting Requirements, Embracing the Abyss), you still cast with Disadvantage and still pay the Dissonant Stress. However, you may reroll any natural 1s that appear in your dice pool. You must keep the second result.

**Fevered Channelling**

* Prerequisites: Desperate Edge (feat — a Tier 1 feat, so it satisfies the Tier 1 requirement on its own), Will 2, Arcana 2 or Faith 2

>The magic wants out. Let it burn through you.

* Mechanic: If you roll a Desperate Edge on a spell manifestation, you generate 1 Momentum. Arcane: if you Fail a Sustain check, you take the 1 Dissonant Stress but the spell does not drop — you keep hold of it for one more Activation. Faith: if you Fail a Flowing check, you do not gain the point of Encroachment it would otherwise cost you. Neither clause applies on Snake Eyes.

**Giant Feller**

* Prerequisites: Brawn 2, Acrobatics 2 or Prowess 2 — plus **any one Tier 1 feat**.

>Physics and leverage apply to monsters, too.

* Mechanic: You may attempt to Grab or Shove creatures up to two sizes larger than you (e.g., Standard Scale vs. Huge Scale). Furthermore, you ignore the automatic 1 Stress penalty when attempting to defend an Attack from an enemy who is larger than you.

**Iron Conviction**

* Prerequisites: Will 2, Resolve 2 — plus **any one Tier 1 feat**.

>Your sheer grit is terrifying.

* Mechanic: When you use **The Blood Price** (Iron Core, *Spending Momentum* — the 1-Momentum conversion of a Wound into 2 Dissonant Stress), you do not spend the Momentum.

**Juggernaut**

* Prerequisites: Brawn 2 — plus **any one Tier 1 feat**.

>Meat and bone, hardened against kinetic shock.

* Mechanic: Your sheer mass makes it incredibly difficult to deal kinetic damage to you. you may spend 1 Momentum to add 2 to your wounds threshold for that attack. stacks with brace.

**Lateral Assessment**

* Prerequisites: Wits 2 — plus **any one Tier 1 feat**.

>Spiral out and over-analyze the chaos of the battlefield.

* Mechanic: When you perform the Tactical Assessment action (2d6 + Skill), a successful check allows you to bank 2 Momentum instead of 1. However, the mental friction of processing that much combat data instantly inflicts 1 Dissonant Stress.

**Midnight Oil**

* Prerequisites: Wits 2, Crafting 2 or Arcana 2 — plus **any one Tier 1 feat**.

>Sleep is a luxury you cannot afford right now.

* Mechanic: During downtime, you can intentionally inflict up to 3 points of Locked Stress upon yourself. For each point of Locked Stress taken, you generate 1 point of Progress Momentum. This allows you to artificially fuel the Field Medic, hammer & forge, etc downtime actions without needing to roll a Massive Success.

**Path of Least Resistance**

* Prerequisites: Desperate Edge (feat — a Tier 1 feat, so it satisfies the Tier 1 requirement on its own), Wits 2, Survival 2

>You see the safe steps where others only see the hazard.

* Mechanic: When you roll a Desperate Edge on an environmental Hazard Check, you generate 1 Momentum. You may immediately spend this Momentum to allow an adjacent ally who failed their check to retroactively pass, saving them from the Locked Stress penalty.

**Psychological Fracture**

* Prerequisites: Will 2, Influence 2 — plus **any one Tier 1 feat**.

>You don't just win an argument; you dismantle their confidence.

* Mechanic: You may spend 1 Momentum to do one of the following:
	- Isolate a Flaw: Exert psychological weight, forcing the NPC to take 2 Stress or immediately shift their social stance to one extreme (e.g., to Hostile out of sheer panic, or Friendly out of awe).
	- Control the Room: Give an ally Advantage (3d6, keep the highest 2) on a subsequent follow-up check (e.g., the face of the party terrifies the merchant, which the thief immediately gets Advantage on picking the merchant's strongbox while he's distracted).

**Relentless Momentum**

* Prerequisites: Brawn 2 — plus **any one Tier 1 feat**.

>Forward progression is the only way out of the meat-grinder.

* Mechanic: You thrive on forward progression. Whenever you successfully inflict a Minor or Major Wound on an enemy, you instantly gain 1 Momentum.

**Riposte**

* Prerequisites: Melee 2 — plus **any one Tier 1 feat**.

>You are a master of punishing overextension.

* Mechanic: If you win a Parry action in a melee Clash, you violently deflect the blow and instantly inflict Impact on the Attacker — calculated exactly as if you had won a Strike (your Margin of victory + your weapon's Power). This turns your defense directly into a weapon.

**Silver-Tongued Viper**

* Prerequisites: Wits 2, Influence 2 — plus **any one Tier 1 feat**.

>You can talk a zealot out of their faith.

* Mechanic: If you achieve a Massive Success (winning by a Margin of 5+) on an opposed Influence vs. Resolve check, you bypass the standard limitation of only shifting an NPC's stance up one level. You can instantly flip an NPC 3 steps in either direction, bending them entirely to your agenda for the scene.

**Smuggler’s Pockets**

* Prerequisites: Reflex 2, Thievery 2 — plus **any one Tier 1 feat**.

>They only find what you want them to find.

* Mechanic: Any NPC attempting an opposed Notice check to search your person for concealed weapons, lockpicks, or contraband automatically suffers Disadvantage. Furthermore, drawing these hidden items is a Free Action that does not provoke an engagement penalty. grants an additonal belt slot.

**Surgical Cruelty**

* Prerequisites: Wits 2, Medicine 1 — plus **any one Tier 1 feat**.

>You know exactly where the nerves cluster.

* Mechanic: When calculating Impact after a successful Clash, if your Impact exactly equals the target's Wound Threshold (hitting the < Threshold or =< Threshold bracket with no overage), you inflict 2 Dissonant Stress to the target in addition to any physical Wounds.

**Sweep**

* Prerequisites: Brawn 1, Reflex 1, Melee 1 — plus **any one Tier 1 feat**.

>One wide, brutal arc of butchery.

* Mechanic: When you win a Strike action with a Melee weapon, you can spend 1 Momentum to apply your full Impact to every enemy adjacent to your primary target, in addition to the target itself.

**The Chain**

* Prerequisites: Reflex 2, Melee 2 or Ranged 2 — plus **any one Tier 1 feat**.

>Violence, properly applied, is perpetual motion.

* Mechanic: When you win a Clash with a Massive Success (a margin of 5+), you can immediately spend 1 Momentum to initiate a secondary, free Strike or Shoot Clash against a different valid target within range.

**The Grudge**

* Prerequisites: Will 2 — plus **any one Tier 1 feat**.

>Wear your scars as a weapon.

* Mechanic: When you suffer a Wound from an Attack, you automatically bank 1 Momentum  and gain Advantage on your next Clash against that specific target.

**The Scoundrel**

* Prerequisites: Reflex 1, Wits 1 — plus **any one Tier 1 feat**.

>You don't fight fair; you throw sand, strike groins, and exploit blind spots.

* Mechanic: When you win a Clash with a concealable or Unarmed strike, you may spend 1 Momentum to forego calculating Impact. Instead, the target takes 1 dissonant Stress and is permanently at Disadvantage on their next roll as they stumble or wipe blood from their eyes.

**The Vanguard / Shield Brother**

* Prerequisites: Brawn 2, Melee 2, Block 1 — plus **any one Tier 1 feat**.

>You anchor the line so others can breathe.

* Mechanic: You know how to anchor a line and protect the vulnerable. If an adjacent ally is targeted by an attack action, you may spend 1 Momentum to physically shove them aside and become the Target in their place.

**Void Weaver**

* Prerequisites: Reflex 1, Arcana 2 — plus **any one Tier 1 feat**.

>You can reach out and unravel the magic of others.

* Mechanic: When an enemy within 30 feet attempts to cast an Arcana or Faith spell (even if you are not the target), you may spend 1 Momentum to unweave it. You roll an opposed Arcana check against their casting roll, and if you win, the spell is entirely shattered before it takes effect. If you win by a Margin of 5 or more, you also absorb the ambient magic, instantly restoring 1 dissonant Stress to yourself.

**Zeal**

* Prerequisites: Brawn 1, Faith 2 — plus **any one Tier 1 feat**.

>The holy spirit renders your flesh numb.

* Mechanic: When the holy spirit fills you, you feel no pain. While you are successfully keeping a Novice Prayer Flowing, you may spend 1 Momentum. For as long as that spell remains active, you completely ignore the negative dice penalties caused by your current Dissonant Stress when making Melee attacks.

### Tier 3 The Void

> **Every feat in this Tier additionally requires either its Archetype's Tier 2 feat, or any two Tier 2 feats** — on top of the Skill and Attribute prerequisites listed on each entry. Feats belonging to an Archetype name their own Tier 2 feat as the cheaper route; feats outside any Archetype simply need two. See Advancement §4.

**Apex Survivor**

* Prerequisites: Brawn 3 or Wits 3, Survival 3 — plus **any two Tier 2 feats**.

>The wild cannot kill you.

* Mechanic: You are immune to the Death Spiral when it is caused by the environment. If a Hazard check (freezing blizzard, starvation, toxic gas) fills your Stress Limit, the excess Stress is simply lost into the void. Environmental hazards can never convert to Wounds on your character sheet.

**Weapon Master**

* Prerequisites: Melee 3 — plus **any two Tier 2 feats**.

>Perfect edge alignment and flawless footwork.

* Mechanic: You have spent thousands of hours perfecting edge alignment and footwork. Choose a weapon class e.g. Blades, Bludgeons, axes, etc. You gain permanent Advantage on Clash rolls when wielding weapons of this class.

**Break Morale**

* Prerequisites: Influence 3 — plus **any two Tier 2 feats**.

>A brutal execution is the purest form of rhetoric.

* Mechanic: When you inflict an Incapacitating Wound on a Grunt-tier or higher enemy, every Fodder or Grunt-tier enemy who witnesses the kill must pass a Resolve check (TN 8) or instantly break formation and flee. Every Elite-tier witness instead gains the Fear condition (per Iron Core). You end fights not by killing everyone, but by demonstrating the absolute futility of opposing you.

**Defiance**

* Prerequisites: Resolve 3 — plus **any two Tier 2 feats**.

>You refuse to die quietly on their terms.

* Mechanic: You do not go down quietly. If you take a Wound that would cause you to become incapacitated, you may immediately spend 1 Momentum to make a final Resolve check. On a success, you remain conscious and standing for exactly one more turn, allowing you to make a final, heroic action before you collapse.

**Embrace the Void**

* Prerequisites: Desperate Edge (feat), Will 3, Brawn 2 or Reflex 2 — plus **any two Tier 2 feats**.

>Birth, suffering, and a rusty blade.

* Mechanic: When your Wounds slots are full, but before you take anymore wounds, you enter a state of lethal, detached focus. Your Desperate Edge triggers on natural 5s as well as 6s for all Clash rolls. However, rolling a Fumble in this state results in immediate incapacitation rather than 1 Stress.

**Flesh Weaver**

* Prerequisites: Wits 3, Medicine 3

>You treat biology as clay.

* Mechanic: When performing downtime triage, you completely ignore the rule requiring 3 days of rest to heal a Wound. You can spend 2 Progress Momentum to instantly and gruesomely stitch up a Wound Slot in 10 minutes. The patient suffers 2 Dissonant Stress from the agony, but the Wound Slot is fully restored.

**Ghost in the Machine**

* Prerequisites: Reflex 3, Thievery 3 — plus **any two Tier 2 feats**.

>Mechanisms simply cease to acknowledge your presence.

* Mechanic: You never trigger mechanical traps by walking over them or interacting with them (they only trigger if you intentionally choose to set them off). Additionally, you can open any non-magical lock instantly as a Free Action, without needing tools or making a Thievery check.

**Ingrained Arcana**

* Prerequisites: Wits 3, Arcana 3 — plus **any two Tier 2 feats**.

>You have burned the formula into your very marrow.

* Mechanic: Choose one Novice or Adept Arcana spell from your Grimoire. You can cast this spell purely from memory — it needs no Grimoire and no free hand, ignoring the Blind Casting Disadvantage and its Dissonant Stress penalty entirely. You can still cast it when the book itself is lost, stolen, or destroyed. Furthermore, this spell never resolves as Messy: treat a Margin 0–2 result as Clean, even if it is a Common or off-Paradigm spell.

**Macabre Genius**

* Prerequisites: Wits 3, Crafting 3 — plus **any two Tier 2 feats**.

>You can build a masterpiece out of absolute garbage.

* Mechanic: You do not require a proper forge, toolkit, or high-grade materials to repair or craft items. With 1 hour of downtime and the salvaged remains of Fodder/Grunt weapons and armour, you can permanently upgrade any standard weapon or piece of armour to Masterwork, granting it a permanent +1 modifier to damage or defense.

**Marrow-Forged**

* Prerequisites: Will 3, Brawn 3 — plus **any two Tier 2 feats**.
* *Deliberate: two Attributes at 3 costs 6 Attribute DP against a creation allowance of 4, so this can never be a creation-adjacent pick regardless of the Tier gate.*

>You are a patchwork of scar tissue and stubborn grit.

* Mechanic: You gain a 4th Wound slot, meaning you are only Incapacitated upon taking your 5th Wound. However, your body is so heavily damaged that any healing (whether magical or through mundane downtime activities) takes twice as long and requires double the normal resources.

**Overchannel**

* Prerequisites: Arcana 3 — plus **any two Tier 2 feats**.

>You rip the fabric of the world apart, taking yourself with it.

* Mechanic: Spend 2 Momentum instead of making your casting roll to automatically resolve an Arcana spell at a Margin of Success of 5 (Massive Impact), devastating the battlefield. You still instantly take 1 physical Wound from the magical blowback.

**Perfect Nullification**

* Prerequisites: Reflex 3, Acrobatics 3

>Be exactly where the blade isn't.

* Mechanic: When acting as the Reactor and using the Dodge action, if you roll a natural 12, you don't just dodge the attack. You instantly steal the initiative, becoming the Aggressor, and may resolve a free Shoot or Strike action against your attacker before the Engagement ends.

**Reaper’s Engine**

* Prerequisites: Brawn 3, Melee 3 — plus **any two Tier 2 feats**.

>Death begets life. Blood washes the slate clean.

* Mechanic: When you inflict an Incapacitating Wound on a living, non- fodder enemy, the surge of adrenaline violently clears your system. You instantly recover 1 Wound Slot and reset your Stress to 0.

**Sabotage**

* Prerequisites: Thievery 3 — plus **any two Tier 2 feats**.

>You dismantle their hope right along with their steel.

* Mechanic: As a Combat Action, spend 3 Momentum instead of making an attack roll to slice a shield strap, cut a bowstring, or unbuckle armour. The target loses the use of that item or loses their Armour rating for the rest of the fight. This completely bypasses the Wound system to permanently cripple Elite or Boss-level enemies.

**Shatter the Ego**

* Prerequisites: Will 3, Influence 3 — plus **any two Tier 2 feats**.

>You strip away their identity until only obedience remains.

* Mechanic: If you win an opposed Influence vs. Resolve check against a standard NPC (Fodder or Grunt level) by a Margin of 3+, their mind fractures. Instead of gaining Momentum, you permanently break them. They will act as an indentured servant, informant, or terrified zealot for your cause until they die, requiring no further Influence checks to command.

**The Oracle’s Burden**

* Prerequisites: Wits 3, Insight 3

>You see the absolute truth of the world, but it hurts to look.

* Mechanic: Once per session, you can ask the GM one specific, unvarnished truth about a person's motives, a hidden location, or a complex plot. The GM must answer completely honestly. However, absorbing this cosmic absolute instantly fills every empty box but one on your Stress track with Locked Stress, bringing you to the absolute brink of the Death Spiral.

**Transgressive Asymmetry**

* Prerequisites: Desperate Edge (feat), Wits 3 or Reflex 3 — plus **any two Tier 2 feats**.

>Cynicism applied to giant monsters.

* Mechanic: When fighting creatures of a larger Scale, your precision bypasses their natural resilience. If your Clash roll includes a natural 6 (triggering a Desperate Edge) against a larger creature, their Wound Threshold scale bonus (+2 for Large, +4 for Huge, etc.) is completely ignored during the Impact calculation of that specific attack.

**Vital Strike**

* Prerequisites: Melee 3 — plus **any two Tier 2 feats**.

>You see the map of their arteries; nothing matters when the blood stops flowing.

* Mechanic: As an Attack action, you take a -2 penalty to your Attack Roll. Ignore armour value in threshold; if you inflict a Wound, you may disable a targeted limb, forcing the target to drop their weapon or halving their movement. On a Massive Success (Margin 5+) against a target of Elite tier or below, you strike a major artery or the neck — the target is instantly Incapacitated, regardless of how many Wound Slots they have left. This cannot target Boss-tier enemies under any circumstance.
### Archetypes

**The Arcanist (Wizard Archetype)**

*Suggested path: **Arcane Awakening** or **Scholarly Resonance** (Tier 1) → **Euclidean Nightmare** (Tier 2) → **The Engine of Ruin** (Tier 3). A signpost, not a requirement — any two Tier 2 feats also open The Engine of Ruin. See Advancement §4.*

>Focused on esoteric geometries, pushing the mind to the breaking point, and treating magic as a volatile engine.

**Euclidean Nightmare (Tier 2)**

* Prerequisites: Wits 2, Arcana 2 — plus **any one Tier 1 feat**.

>The geometry of your mind bleeds into reality.

* Mechanic: When you successfully cast an Arcana spell, you may spend 1 Momentum to leave a residual, jagged magical glyph in the air in an adjacent square. Any enemy that enters or starts their turn in that square takes 1 Dissonant Stress as the impossible angles burn their retinas.

**The Engine of Ruin (Tier 3)**

* Prerequisites: Wits 3, Arcana 3 — plus **Euclidean Nightmare** (this Archetype's Tier 2 feat), *or* any two Tier 2 feats.

>Destruction is just energy seeking its natural resting state.

* Mechanic: When you suffer the Snake Eyes Backfire on an Arcana roll, resolve its Wound and Dissonant Stress as normal — then discharge everything: your full current Dissonant Stress total becomes the "lethal hazard" the Backfire produces, converting to an outward blast that deals Impact equal to the amount discharged (ignoring Armour) to everyone within Short Range, allies included. Your Dissonant Stress clears to 0.

**The Berserker (Barbarian Archetype)**

*Suggested path: **Desperate Edge** (Tier 1) → **The Red Mist** (Tier 2) → **Apex Butcher** (Tier 3). A signpost, not a requirement — any two Tier 2 feats also open Apex Butcher. See Advancement §4.*

>Focused on leveraging sheer trauma, terrifying resilience, and turning bodily punishment directly into kinetic output.

**The Red Mist (Tier 2)**

* Prerequisites: Brawn 2, Resolve 2 — plus **any one Tier 1 feat**.

>Pain is just a targeting mechanism.

* Mechanic: If you suffer a Minor or Major Wound from a melee attack, your nervous system rejects the shock. You may immediately spend 1 Momentum to perform a brutal, retaliatory Strike action against them. This occurs instantly before the Engagement ends and before you suffer any associated Stress penalties.

**Apex Butcher (Tier 3)**

* Prerequisites: Brawn 3, Athletics 3 — plus **The Red Mist** (this Archetype's Tier 2 feat), *or* any two Tier 2 feats.

>You are a walking abattoir; your survival demands their collapse.

* Mechanic: When you inflict an Incapacitating Wound on a non-fodder organic target, the sheer brutality of the execution breaks the morale of those watching. All enemies within 15 feet immediately suffer 2 Dissonant Stress. Furthermore, you may use a Free Action to revel in the carnage, instantly converting up to 3 of your own accumulated Dissonant Stress points directly back into your Momentum bank.

**The Biomancer (Druid Archetype)**

*Suggested path: **Scavenger's Eye** or **Calloused Lungs** (Tier 1) → **Parasitic Symbiosis** (Tier 2) → **Apex Chimera** (Tier 3). A signpost, not a requirement — any two Tier 2 feats also open Apex Chimera. See Advancement §4.*

>Focused on survival horror, weaponized flora, and treating biology as a malleable, expendable resource.

**Parasitic Symbiosis (Tier 2)**

* Prerequisites: Wits 2, Survival 2 — plus **any one Tier 1 feat**.

>Nature reclaims everything, starting with their bloodstream.

* Mechanic: When you successfully inflict a Minor or Major Wound on a living creature, you may spend 1 Momentum to plant a parasitic, alchemically-altered spore deep in the tissue. At the start of each of their subsequent turns, they must pass an Athletics check or take 1 Dissonant Stress. If they fail, the blooming spore also grants you a flat +1 bonus on your next Clash roll against them.

**Apex Chimera (Tier 3)**

* Prerequisites: Brawn 2, Survival 3 — plus **Parasitic Symbiosis** (this Archetype's Tier 2 feat), *or* any two Tier 2 feats.

>You forcefully rewrite your own anatomy to survive.

* Mechanic: During combat, you may inflict 1 Dissonant Stress upon yourself as a Free Action to violently warp your bones and musculature. You gain one Monster Entity Tag (such as Regeneration, Corrosive Form, or shifting your Scale up by +1) until the end of the scene. However, if you roll a Fumble while in this state, the transformation destabilizes, resulting in a permanent, gruesome physiological penalty (GM's discretion).

**The Bravo (Duelist Archetype)**

*Suggested path: **Iron Grip** (Tier 1) → **The Insulting Deflection** (Tier 2) → **Death of a Thousand Cuts** (Tier 3). A signpost, not a requirement — any two Tier 2 feats also open Death of a Thousand Cuts. See Advancement §4.*

>Focused on surgical precision, arrogant mobility, and completely dismantling an enemy's Momentum economy.

**The Insulting Deflection (Tier 2)**

* Prerequisites: Reflex 2, Melee 2 — plus **any one Tier 1 feat**.

>Their greatest strike is just an opening for your blade.

* Mechanic: When you act as the Reactor and successfully Parry an attack by a Margin of 5+. You may immediately spend 1 Momentum to inflict the Surprised condition on the Aggressor.

**Death of a Thousand Cuts (Tier 3)**

* Prerequisites: Reflex 3, Melee 3 — plus **The Insulting Deflection** (this Archetype's Tier 2 feat), *or* any two Tier 2 feats.

>You move faster than their pain receptors can register.

* Mechanic: When wielding two one-handed weapons (a primary weapon and a weapon with the Sidearm tag), your sheer speed bypasses the standard Momentum economy. Whenever you win an attack action in a clash, your off-hand weapon automatically deals its Power + 1 Stress to the target. You no longer need to spend 1 Momentum to perform the Twin Strike maneuver.

**The Cutthroat (Thief/Rogue Archetype)**

*Suggested path: **Shadow-Weaver** (Tier 1) → **Parasitic Momentum** (Tier 2) → **Anatomical Nihilism** (Tier 3). A signpost, not a requirement — any two Tier 2 feats also open Anatomical Nihilism. See Advancement §4.*

>Focused on opportunistic strikes, siphoning momentum from the failures of others, and anatomical nihilism.

**Parasitic Momentum (Tier 2)**

* Prerequisites: Reflex 2, Stealth 2 or Thievery 2 — plus **any one Tier 1 feat**.

>You thrive on the systemic collapse of others.

* Mechanic: When an enemy within 30 feet rolls a Fumble (two natural 1s), you steal their panicked energy, instantly banking 1 Momentum for yourself as you capitalize on their mistake.

**Anatomical Nihilism (Tier 3)**

* Prerequisites: Reflex 3, Melee 3 or Ranged 3 — plus **Parasitic Momentum** (this Archetype's Tier 2 feat), *or* any two Tier 2 feats.

>Nothing matters when the arteries are severed.

* Mechanic: If you win an Attack action with a finesse Weapon or Sidearm by a Massive Success (Margin of 5+), you do not calculate standard Impact against the target's Wound Threshold. Instead, you permanently disable one of the target's limbs or sensory organs (GM's discretion), instantly inflicting 1 Minor Wound (1 slot) and applying the Bleeding condition.

**The Demagogue (Bard Archetype)**

*Suggested path: **Battlefield Orator** (Tier 1) → **Vitriolic Cadence** (Tier 2) → **Architect of Panic** (Tier 3). A signpost, not a requirement — any two Tier 2 feats also open Architect of Panic. See Advancement §4.*

>Focused on psychological warfare, weaponizing the Momentum of a crowd, and manipulating the Social Engine right in the middle of a slaughter.

**Vitriolic Cadence (Tier 2)**

* Prerequisites: Will 2, Influence 2 — plus **any one Tier 1 feat**.

>You orchestrate the rhythm of the meat-grinder.

* Mechanic: You know exactly how to twist the knife when an enemy is faltering. Whenever an ally within earshot successfully gains Momentum from winning a Clash, you may hurl a devastating insult or terrifying tactical observation. This instantly inflicts 1 Dissonant Stress on the enemy your ally just struck.

**Architect of Panic (Tier 3)**

* Prerequisites: Will 3, Influence 3 — plus **Vitriolic Cadence** (this Archetype's Tier 2 feat), *or* any two Tier 2 feats.

>You narrate their inevitable doom until their mind simply accepts it.

* Mechanic: You may spend 2 Momentum to target one enemy within 30 feet who can hear and understand you. Instead of an Aggressor action, you roll an opposed Influence check against their Resolve. On a Massive Success (a Margin of 5+), you completely shatter their psychological fortitude to absorb kinetic trauma. Their Wound Threshold is permanently reduced by 2 for the remainder of the scene.

**The Inquisitor (Paladin Archetype)**

*Suggested path: **Divine Conduit** (Tier 1) → **The Weight of Guilt** (Tier 2) → **Penance Engine** (Tier 3). A signpost, not a requirement — any two Tier 2 feats also open Penance Engine. See Advancement §4.*

>Focused on weaponized dogma, absolute punishment, and crushing the enemy under the sheer weight of divine authority.

**The Weight of Guilt (Tier 2)**

* Prerequisites: Will 2, Faith 2, Melee 1 — plus **any one Tier 1 feat**.

>Your judgment is a physical anchor dragging them down.

* Mechanic: When you win a Clash against an enemy who has inflicted a Wound on an ally during the current scene, you may immediately spend 1 Momentum. The target must pass an opposed Resolve check against your Faith. If they fail, their nervous system locks up in terror, instantly inflicting the Anchored condition until they can break free on their next activation.

**Penance Engine (Tier 3)**

* Prerequisites: Will 3, Faith 3, Brawn 2 — plus **The Weight of Guilt** (this Archetype's Tier 2 feat), *or* any two Tier 2 feats.
* *Deliberate: Will 3 + Brawn 2 costs 5 Attribute DP against a creation allowance of 4 — an intentional second barrier on top of the Tier gate.*

>To strike you is to invite the wrath of god.

* Mechanic: When an Attack roll has a natural 6 on a Clash against you, you may spend 2 Momentum to instantly shatter their weapon or their arm via divine backlash. The incoming attack is completely nullified (0 Impact), and the Aggressor instantly suffers 1 Major Wound (2 slots) as the kinetic energy violently rebounds into their own body.

**The Ironclad (Fighter/Warrior Archetype)**

*Suggested path: **Iron Grip** (Tier 1) → **Attrition Engine** (Tier 2) → **The Downward Swing** (Tier 3). A signpost, not a requirement — any two Tier 2 feats also open The Downward Swing. See Advancement §4.*

>Focused on brutal mechanical efficiency, surviving physical trauma, and turning defense into inevitable offense.

**Attrition Engine (Tier 2)**

* Prerequisites: Brawn 2, Block 2 or Melee 2 — plus **any one Tier 1 feat**.

>You grind them down to the marrow.

* Mechanic: Whenever you successfully Block or Parry an attack, you automatically bank 1 Momentum. Your defense directly fuels your offensive economy.

**The Downward Swing (Tier 3)**

* Prerequisites: Brawn 3, Melee 3 — plus **Attrition Engine** (this Archetype's Tier 2 feat), *or* any two Tier 2 feats.

>The heavier the physical burden, the harder the kinetic release.

* Mechanic: For every active Wound slot currently filled on your character sheet, you gain a flat +1 bonus to the total of your Strike actions. As your body breaks down, your lethality spikes.

**The Stalker (Ranger/Hunter Archetype)**

*Suggested path: **Long Eye** or **Calloused Lungs** (Tier 1) → **Predator's Rhythm** (Tier 2) → **No Quarter in the Mud** (Tier 3). A signpost, not a requirement — any two Tier 2 feats also open No Quarter in the Mud. See Advancement §4.*

>Focused on isolation, predatory tracking, and ruling the fringes of the battlefield.

**Predator's Rhythm (Tier 2)**

* Prerequisites: Wits 2, Survival 2 — plus **any one Tier 1 feat**.

>You have synchronized your breathing with the slaughter.

* Mechanic: When you successfully kill or Incapacitate a Fodder or Grunt level enemy, you may immediately clear 1 Dissonant Stress or bank 1 Momentum (your choice).

**No Quarter in the Mud (Tier 3)**

* Prerequisites: Brawn 3 or Reflex 3, Survival 3 — plus **Predator's Rhythm** (this Archetype's Tier 2 feat), *or* any two Tier 2 feats.

>You are the apex organism of the wasteland.

* Mechanic: When an enemy attempts to leave your Threat Zone and provokes a Free Attack action from you, your strike is devastatingly precise. You roll the Clash with Advantage, and if you hit, the attack ignores 2 points of the target’s Wound Threshold.

**The Zealot (Priest/Cleric Archetype)**

*Suggested path: **Divine Conduit** or **Ritualist** (Tier 1) → **Litany of Nails** (Tier 2) → **Martyr's Furnace** (Tier 3). A signpost, not a requirement — any two Tier 2 feats also open Martyr's Furnace. See Advancement §4.*

>Focused on weaponized suffering, cynical devotion, and using the self as a conduit for divine violence.

**Litany of Nails (Tier 2)**

* Prerequisites: Will 2, Faith 2 — plus **any one Tier 1 feat**.

>Your scripture is a weapon of blunt force.

* Mechanic: When you keep a Prayer Flowing by passing your Tithe of Will (2d6 + Faith) at the start of your turn, you may instantly inflict 1 Dissonant Stress on any one engaged enemy who can hear you speak the profane words.

**Martyr’s Furnace (Tier 3)**

* Prerequisites: Will 3, Faith 3 — plus **Litany of Nails** (this Archetype's Tier 2 feat), *or* any two Tier 2 feats.

>You take on the world's rot so others might live.

* Mechanic: When an ally within 30 feet suffers a Wound, you may spend 2 Momentum to instantly transfer that Wound to yourself instead. If this Wound pushes you to Incapacitation, your collapse triggers a shockwave of absolute divine radiation, instantly clearing all Locked and Dissonant Stress from all allies within line of sight.

**The Scrounger (Survivalist Archetype)**

*Suggested path: **Spit and Twine** (Tier 1) → **Volatile Concoction** (Tier 2) → **Tactical Engineering** (Tier 3). **This one is a real chain, not a signpost** — all three extend the same cumulative list of Momentum spends, so each genuinely requires the one below it and the any-two-Tier-2 route does not apply. It is the only Archetype that works this way.*

>Some adventurers carry a forge's worth of steel into the dungeon. The Scrounger carries a knife, a length of wire, and the absolute certainty that everything around them is a weapon, a tool, or a meal if you're desperate enough.

---

**Spit and Twine (Tier 1)**

* Prerequisites: Crafting 1 or Survival 1

>You've never owned anything that wasn't already broken once.

* Mechanic: You gain access to the following Momentum spends:

  - **The Patch Job:** Your armour or weapon just gained the Damaged tag, rendering it mechanically weak. Spend 1 Momentum to hurriedly bind it with leather straps, sap, or wire. You completely ignore the Damaged tag for the duration of the next scene. Once the scene ends, the gear breaks again.

  - **Shivs and Shrapnel:** Spend 1 Momentum to instantly fashion a crude, single-use Power 1 weapon (a glass shiv, a heavy bone club) or a rudimentary tool (a makeshift lockpick, a wedge for a door) from the immediate environment, without needing to roll for success.

**Volatile Concoction (Tier 2)**

* Prerequisites: Spit and Twine (a Tier 1 feat, so it satisfies the Tier 1 requirement on its own — and here it is a genuine requirement, not a suggestion), Crafting 2 or Survival 2

>Given a corpse, a puddle, and ten minutes, you could probably brew up something that kills.

* Mechanic: You gain access to the following Momentum spends:

  - **Dungeon Chemistry:** You don't have a lab, but you have monster viscera, dungeon flora, and desperation. Spend 2 Momentum to quickly mash together a single-use tactical item — like a blinding powder, a highly localized acid vial to melt an iron lock, or a crude smoke bomb. When used, it perfectly mimics the effect of a Tier 1 environmental spell (like *Choking Vapor* or *Choking Brambles*), allowing non-magic users to temporarily alter the battlefield.

  - **Savage Reinforcement:** Spend 2 Momentum to drive spikes, nails, or shattered glass into your shield or gauntlets. The next time you successfully Parry or Block an enemy's Strike, the enemy automatically suffers 1 dissonant stress from striking the jagged metal. The reinforcement then breaks off.

  - **Scavenge and Cannibalize:** Spend 2 Momentum after clearing a room to harvest meat from a beast, boil stagnant water, or pull unbroken arrows from corpses (using the Spit and Twine or Dungeon Chemistry logic above). This immediately steps the Community Supply Die back up by one tier (e.g., from a d4 back to a d6). Spend this before any subsequent Breather empties your Momentum Bank.

**Tactical Engineering (Tier 3)**

* Prerequisites: Volatile Concoction, Crafting 3 or Survival 3

>Give them ten minutes and a pile of rubble, and they'll build you a grave.

* Mechanic: You gain access to the following Momentum spends:

  - **The Kill-Box Barricade:** You only have minutes before the swarm arrives. Spend 3 Momentum to cannibalize the environment (pews, iron gates, rubble) to create a  booby-trapped choke point. The first enemy that attempts to cross the threshold automatically suffers a massive kinetic hit (e.g., 7 Impact) and gains the Anchored condition, without you ever having to roll a Strike.

  - **Cannibalize Gear:** Instead of a temporary patch, you permanently repair a critical piece of gear. Spend 3 Momentum and destroy one piece of equipment (an enemy's dropped sword, a heavy iron pot) to permanently strip the Damaged tag from your primary weapon or armour mid-dungeon.

---

## Advancement

Every 2 to 3 sessions, the GM awards the party a Milestone Reward of 3 Development Points (DP). When spending these points to grow, the relationship between a character's physical/mental limits (Attributes) and their techniques (Skills) dictates the cost.

#### The Training & Growth Menu

1. Learning a New Skill (Rank 1 / Novice)
	- Costs 2 DP to unlock Rank 1 in a Skill currently at 0. Finding a
	  teacher mid-campaign costs more than choosing a background did.

2. Upgrading an Existing Skill
	- Ranks 2, 3 and 4: 1 DP each.
	- Rank 5: 2 DP.
	- Rank 6: 3 DP.
	- No Skill may exceed its Associated Attribute + 3, or +6, whichever
	  is lower.

3. Advancing an Attribute
	- Physical/Mental Conditioning: Costs 5 DP to increase any Attribute
	  by +1, to a maximum of 3. This raises your derived stats (Brawn
	  raises Wound Threshold; Wits and Will raise Stress Limit; Reflex
	  raises your Momentum Bank and Activation Order) and raises the
	  ceiling on every Skill tethered to it.

4. Purchase a Feat
	- Horizontal development: costs 3 DP  to gain a new feat, as long as the prerequisites are met.
	- **The Tier ladder.** A feat's Tier is a gate, not just a label. Without this, a creation-legal character with one Skill at rank 3 can spend their very first Milestone on a Tier 3 feat, which contradicts everything the Standing table says about when those arrive.
		- A **Tier 2** feat additionally requires **any one Tier 1 feat** you already hold.
		- A **Tier 3** feat additionally requires **its Archetype's Tier 2 feat**, *or* **any two Tier 2 feats**.
	- **Archetypes are a signpost, not a cage.** Each Archetype in the feat list names a suggested path — a Tier 1, a Tier 2 and a Tier 3 feat that build on one another. Following it is *cheaper*: that Archetype's own Tier 2 feat unlocks its Tier 3 by itself, where a character built outside any Archetype needs two Tier 2 feats to reach the same rung. Nothing obliges you to pick an Archetype, declare one, or stay in one. A character holding Tier 2 feats from three different Archetypes is entirely legal, and reaches Tier 3 for 3 DP more than the specialist does. The suggested paths exist so a player who *wants* a clear mechanical identity can see one at a glance — not to fence off the players who don't.
	- **What this costs in practice.** A specialist following a suggested path reaches their first Tier 3 feat at **Milestone 2** (6 DP of feats). A character building freely reaches it at **Milestone 3** (9 DP) — and both figures assume every Milestone goes to feats and none to Skills or Attributes, so a normally-developed character arrives later still. That puts Tier 3 around Veteran at the very earliest and Storied in ordinary play, which is what the Standing table describes.
	- *Creation is unaffected — Step 4 remains **Tier 1 only**, regardless of what a character's Skill ranks would otherwise permit.*

5. Learn New Faith Spells
	- Cannot learn Prayers from outside your Chosen Cult/Domain. *(Deliberate: the ability to enact miracles comes from rigorous devotion to a single ideology. The Common Prayer list lets any Priest mix in some breadth without breaking that theme; a character who wants full cross-Domain access takes the Heretic's Path over the Covenant at Divine Conduit instead — every Domain's list, paid for with permanent Disadvantage on the Tithe of Will.)*
	- Novice Prayer = 2 DP
	- Adept = 3 DP (requires Faith 2+)
	- Master = 4–5 DP (requires Faith 3+)

6. Learn New Arcane Spells
	-  Novice = 2 DP
	- Adept = 3 DP (requires Arcana 2+)
	- Master = 4–5 DP (requires Arcana 3+)
	- Spells from outside your chosen Paradigm cost a +1 DP surcharge.

---

## Milestone Standing — Tracking Advancement

Two characters can both be "advanced" and be nowhere near equivalent — one might have sunk every Milestone into a single Attribute, another into six different Feats. Rather than pretend that maps onto a single power number, track two things per character.

**Milestone count** is the objective, countable fact: how many Milestone Rewards (3 DP each) a character has received since creation, regardless of whether that DP has actually been spent yet or is still sitting banked. A character who has received 6 Milestone Rewards has earned 18 DP through Advancement — full stop — whether all 18 have been spent (like the example below) or half of it is still saved up for a big purchase. Record it on the sheet as a header line:

`Milestone [N] — [X] DP earned, [Y] DP currently banked`

**Standing** is a named band over Milestone count, for table talk and GM planning shorthand only. It is descriptive, not a mechanical gate — nothing in the rules checks a character's Standing directly; Feat and Attribute prerequisites still check actual Attribute/Skill values exactly as they always have. Standing exists so a GM building an encounter, or a table comparing characters, has a one-word answer to "how far along is this character" without doing arithmetic first.

| Standing     | Milestone count | DP earned via Advancement | Typical Skill points* | Rough shape of the character                                                                                                                                              |
| ------------ | --------------- | ------------------------- | --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Green**    | Milestone 0     | 0 DP                      | 8 (9 for a Human)     | Fresh off character creation. Everything on the sheet came from the Novice Hero build. Best roll is +4 or +5.                                                             |
| **Blooded**  | Milestone 1–2   | 3–6 DP                    | 9                     | Survived the early sessions. Usually one Skill bump or a second Tier 1 Feat — not yet an Attribute increase.                                                              |
| **Veteran**  | Milestone 3–5   | 9–15 DP                   | 10–11                 | First Attribute increase has usually landed by now, opening ceilings that were previously out of reach. Tier 2 Feats start becoming affordable as prerequisites catch up. |
| **Hardened** | Milestone 6–9   | 18–27 DP                  | 12–14                 | Multiple Attribute increases banked. Wound Threshold, Stress Limit and Momentum Bank have visibly grown past the creation baseline. A first Skill has likely reached +6.  |
| **Storied**  | Milestone 10+   | 30+ DP                    | 15+ (open-ended)      | Late-campaign. Pushing into Tier 3 Feats, core Attributes at the +3 mortal cap and their tethered Skills at or near the +6 ceiling.                                       |

*\*"Skill points" is the sum of every Skill rank on the sheet. Attributes are excluded on purpose. They do not contribute to a roll, and at 5 DP each against a Skill rank's 1–3 they are not the same currency — summing the two would add unlike things and flatter a character who bought breadth of ceiling over actual competence. This is the same number the Bestiary's enemy budgets are measured in (see "Enemy Budget by Party Standing" in Beasts, Monsters, Mutants), so a GM can compare the two sides directly.*

*Green's figure is near-fixed: the creation budget is 8 Skill DP — **9 for a Human, or a Half-Elf who took Adaptable** — and ranks 1–4 cost 1 DP each, so a character who buys no rank past +4 lands on exactly that many ranks. The only way to land lower is to buy the expensive top of the ladder — a specialist reaching +5 spends 6 DP for 5 ranks and ends on 7.*

# Chapter 3 — Metal meet Flesh

*Combat*

## When it comes to Combat
### The Engagement Flow

1. Activation Order: **6 + Reflex**, a static value. This determines turn
   order and does not change between rounds.
	- Activations are executed in descending order.
	- Ties are broken by higher Acrobatics; if still tied, the player
	  acts before the NPC.
	- Once all Activations are complete, the round is over. Order
	  carries over unchanged into the next round.

2. Move and Action: Active Characters (aggressors) can spend their activation moving and taking an action and a free action if they are not also engaged. They may move up to their Move value and at any time resolve their action/free action during that movement. If the Active Character enters an enemies Threat zone both the Active character and the enemy become Engaged.

3. When choosing to use their action to attack a target.
	1. Declarations: Aggressor declares an attack first (e.g., Strike, shove)
	2. Reactor declares a defense (e.g., Dodge, Block)

4. Fight (The Clash): Both Aggressor and reactor roll their chosen actions, Highest total wins.
	1. Compare the roll results, the difference is the Impact(where applicable)
    - In a Tie: the weapons bind/arrows miss or are deflected, the clash ends.

### Combat on the Grid
- Scale: 1 Square = 5ft. Medium creatures occupy 1 square and move 30 ft (6 squares) per action.

- Threat zone: Threaten all adjacent 8 squares (5ft radius).

- Provoking: Leaving a Threat Zone normally grants the enemy a Aggressor action - strike with Advantage.

- The Flanking Bonus (outnumbered):  If you outnumber an opponent in melee, you have Advantage on the Clash.

### Damage Calculation
Impact: (Winner Roll - Loser Roll) + Weapon Power.

- Impact < Threshold: 1 Dissonant Stress. "A Glancing Hit"

- Impact => Threshold: 1 Minor Wound (1 slot).

- Impact => 2x Threshold: 1 Major Wound (2 slots) + 1 Dissonant Stress.

- Impact => 3x Threshold: **Overwhelming Trauma** — bypasses Wound Slots entirely (never fills one, regardless of how many are available) and immediately triggers Incapacitated / At Death's Door (Bleed-Out checks). Potential long-term injury + 2 Dissonant Stress.

## Action Types

During a Characters activation it may move up to its base movement value [MV] and take an Action. A Character can take an Action at any time during their movement. If a Character wishes to move up to double  their movement value, they will sacrifice their Action for that activation.  

**Free Actions:**
- at any time during their activation a Character may take a Free Action in addition to their Action. Free actions are drinking a potion, pulling a lever, passing an item to a nearby ally, etc. actions that are quick and require little to no effort.
- When taken whilst engaged in an enemy threat zone, gain disadvantage on combat actions until next activation.
- **Retrieve a Dropped Weapon or Shield:** A Free Action — but it halves the character's movement for that activation. Stooping to grab it costs mobility, not the whole turn.

**Attack Actions:**

- Strike: 2d6 + Melee. The standard attack.
- Power Strike: 2d6 + Melee + weapon power. Apply the weapon power to the strike roll, instead of the impact calculation. however, it reduces your Wounds threshold by 2 until the beginning of your next activation.

- Grab: 2d6 + Prowess. Attempt to Hold the Target in a grapple or hold onto an enemy. Win, you and the opponent gain the In-Fighting and Grappled conditions.

- Shove: 2d6 + Prowess. The physical Push, you bash the target to create space or break a grapple. If you win, the target takes 1 Stress and is pushed back 5 feet out of your threat Zone.

- Shoot: 2d6 + Ranged. The standard Ranged attack. If you win, work out Impact.

- Cast Spell: See spell description.

**Defense Actions:**

*When targeted by a ranged attack outside of movement distance and without a ranged weapon, the target of an activation is automatically the Reactor.*

- Block: 2d6 + Block. If you lose the Clash, subtract your Shield's Value from the Impact before comparing it to your Wound Threshold (minimum 0).

- Dodge: 2d6 + Acrobatics. Avoid damage and instantly shift 5ft.

- Brace: 2d6 + Prowess. If you win, you take no impact. If you lose, you gain a +2 bonus to your Wound Threshold [T] when calculating Impact.

- Parry: 2d6 + Melee.

- Shoot: **ranged option**, fire ranged weapon as target closes in. Win calculate Impact.

- Cast Spell: See spell description.

**Activation Actions:**

- Disengage: If all you do is move for your activation you can leave an enemy threat zone without provoking a free strike.
	- otherwise: a Dodge roll V opponent Strike Action.
- Tactical Assessment: Skill test based on context, gains momentum.

- Ready: Hold your action to stand ready to choose when to act next in the activation order. if the held action hasn't been used this round the player goes last in the activation order for this round.

- Charge: ** only if within move distance. Gain +2  to the The Clash roll and breaks ties(the equivalent of winning by 1).  suffer a -2 to reactor actions until next activation.

- Skill based Actions: based on skill

- The Regroup Action:
	_Sometimes, survival means giving up the offensive just to fix a deteriorating situation._

	Taking the **Regroup** action consumes a player's entire turn. They cannot declare an Aggressor Strike or make a tactical movement. Instead, they drop their guard to focus entirely on one of the following critical tasks:

	- **Rummage the Pack:** Digging past armour and straps to retrieve a stowed item (such as a potion, a specialized tool, or a backup weapon) from **The Pack** inventory slots. Items in The Pack cannot be accessed mid-combat without taking this action.

	- **Clear a Severe Condition:** Spending the precious seconds required to pat out the flames of the **Ablaze** condition, untangle themselves from a dropped net, or blindly wash acid from their visor.

	- **Catch Breath:** Flatly clear 2 Dissonant Stress. No check, no attribute tied to the amount — the whole turn already paid for it.

- **The Reprieve (Faith Caster Action):** A Priest lays a burden down for a moment, mid-battle, and asks whatever's listening to ease up. This is the only in-combat route to clearing Locked Stress, and it consumes the Priest's Activation. It cannot touch Locked Stress paid for a Prayer that is currently **Flowing**, or committed to an Attuned item (per the Golden Rules, Iron Core).

	Roll **2d6 + Faith vs. TN 8**.

	- **Success:** Unlock [Will] Locked Stress (minimum 1).
	- **Massive Success (5+):** Clear all **clearable** Locked Stress — Flowing and Attuned Locked Stress are untouched, per the exclusion above.
	- **Fumble (Snake Eyes):** The weight doesn't lift — it curdles. All **clearable** Locked Stress becomes Dissonant (Attunement Locked Stress does not convert, per the Golden Rules), **and the Priest gains 1 Encroachment** (the thing you've been borrowing from notices you reaching for relief without paying first).

#### The Twin-Blade Stance (Two weapon fighting)

When wielding two one-handed weapons (a primary weapon and a weapon with the Sidearm tag), the character gains the following benefits:

**Clash Advantage:** You may choose which weapon's tags to apply to the Engagement Clash. For example, having a Reach weapon (like a spear) in one hand and a Sidearm (like a dagger) in the other allows you to use the Reach while maintaining the ability to fight effectively in close quarters.

**Off-Hand Parry:** While wielding a Sidearm-tagged weapon in your off-hand, you may use that weapon's Power as a separate Front-End Reducer when you choose Parry as your Reactor action — stacking with (not replacing) your primary weapon's Parry bonus, up to the off-hand weapon's own Power value (minimum of 1, power 0 weapons effectively add one). This uses the weapon's **melee** Power only — a firearm counts as Power 0 here (see the Black Powder tag, Hardware). Fictionally: you're using the dagger to deflect the killing edge of the blow rather than catching the whole weapon.

**The "Twin Strike" Maneuver (Momentum Spend)**

- Effect: When you win a Clash as an Aggressor, you may spend 1 Momentum to immediately perform a second strike with your off-hand weapon.

- Impact: This second strike does not require a new roll; instead, it deals the off-hand weapon's melee Power (a firearm counts as 0) + 1 Stress to the target. This represents a quick follow-up flick or "stinger" that keeps the pressure on the opponent.

---

#### The Scale Categories

"Scale Level" relative to a standard human/dwarf (Scale 0).

- Tiny (Scale -2): Rats, pixies, small birds.

- Small (Scale -1): Goblins, halflings, wolves.

- Standard (Scale 0): Humans, Dwarves, Orcs.

- Large (Scale +1): Trolls, Ogres, Dire Wolves, Horses.

- Huge (Scale +2): Giants, Hydras, young Dragons.

- Gargantuan (Scale +3 or higher): Ancient Dragons, Krakens, Titans.

---

### Size and Scale
#### The Mechanics of Scale

Instead of over complicating stats, use the Scale Difference to determine modifiers in a Clash.

##### Accuracy and Evasion (The Clash)

It is harder to hit a rat, but very easy to hit the broad side of a dragon.

- Attacking a Larger Target: The attacker gains a +1 bonus to their Clash check for every step of difference. (e.g., A Human attacking a Huge Giant gets a +2 to hit).

- Attacking a Smaller Target: The attacker suffers a -1 penalty to their Clash check for every step of difference. (e.g., A Human attacking a Tiny rat suffers a -2 to hit).

##### Damage and Resilience (Wounds & Stress)

Mass dictates how easily a creature absorbs trauma. We adjust the Wound Threshold (WT) and Wound Slots.

- Scale -1 or -2 (Small/Tiny): Base WT is reduced by 1. They suffer a -1 to their base Stress Limit.

- Scale +1 (Large): +2 to Wound Threshold.

- Scale +2 (Huge): +4 to Wound Threshold, and they gain 1 additional Wound Slot (meaning it takes 5 Wounds to incapacitate them instead of 4).

- Scale +3 (Gargantuan): +6 to Wound Threshold, and they gain 2 additional Wound Slots. Furthermore, weapons without the Devastating or Siege tag cannot inflict Wounds on them at all, only Stress.

##### Momentum and Impact

Larger creatures hit with overwhelming force, severely taxing the defender's ability to block.

- Overwhelming Force: When a target attempts to defend an Attack action from a Larger opponent, the target suffers 1 automatic Stress, even if they successfully defend. If the attacker is two or more sizes larger (e.g., Human vs. Giant), the defense action suffers Disadvantage.

- Grappling/Shoving: A character automatically has Advantage on Prowess checks to grapple, shove, or knock down a creature smaller than them. You cannot grapple a creature more than one size larger than you without special feats or equipment (like ropes and harpoons).

---

### Ranges

| Range Band  | Distance (Squares)        | Rules / Modifiers                                                                            |
| ----------- | ------------------------- | -------------------------------------------------------------------------------------------- |
| Point-Blank | 5 ft (1 Square)           | InThreat range. Disadvantage on ranged attacks **and on casting** (unless the weapon or Arcane Focus carries the Sidearm tag). |
| Short       | 10 ft – 30 ft (2-6 Sq)    | Standard operating range. No penalties. (A typical move action distance).                    |
| Medium      | 35 ft – 60 ft (7-12 Sq)   | Standard operating range. No penalties. (A typical move action distance).                    |
| Long        | 65 ft – 120 ft (13-24 Sq) | Disadvantage to the Clash roll.                                                              |
| Extreme     | 125 ft+                   | Disadvantage. Target must be completely in the open.                                         |

**Spells and the range bands.** A spell's listed band (Short, Medium) is a **hard cap, read as "up to"** — it may be cast at any distance within that band, **including Point-Blank**, and not one foot beyond it. Spells therefore never suffer the **Long** or **Extreme** Disadvantage: they simply cannot reach. That is the deliberate counterpart to weapons, which carry no cap and pay an escalating penalty instead. **Point-Blank is the one band both pay.** Casting with an enemy inside your Threat Zone takes Disadvantage exactly as a shot does, and has the same two answers: a **Sidearm**-tagged Arcane Focus, or keeping them out with **Reach**. *(This is Disadvantage from position, where Blind Casting is Disadvantage from loadout — see the Casting Requirements, Embracing the Abyss. Blind Casting's Dissonant Stress cost still applies on its own account, but the Disadvantage from the two sources does not stack; Disadvantage never does, per Iron Core.)*

# Chapter 4 — Iron World

*The Environment & the Social Engine*

## Movement in the world:

- Scale: 1 Square = 5ft. Medium creatures occupy 1 square and move 30 ft (6 squares) per action.

- Threat zone: Threaten all adjacent 8 squares (5ft radius).

- Provoking: Leaving a Threat Zone normally grants the enemy a Aggressor action - strike with Advantage.

- The flanking Bonus (outnumbered): If you outnumber an opponent in melee, you have Advantage on the Clash.

- Rushed Stealth: Moving faster than half your Movement value whilst using Stealth imposes a disadvantage to your Stealth rolls.

- Difficult Terrain: Moving through difficult terrain (deep mire, heavy snow, shifting rubble) halves your Movement value and imposes disadvantage on all checks requiring mobility (such as Athletics or Acrobatics checks) made within it.

- Drawing a weapon is an free action.

- Move is a per-creature stat, not a formula off Scale — a Small creature can outrun a Large one and vice versa (see Hardware's Mounts table: a Guard Dog outruns a Donkey despite matching Scale). 30 ft (6 squares) is the default for an unremarkable Standard-Scale creature; adjust it up or down when the fiction calls for it.

- Flying: A creature with the Flying Trait has a Fly Move value, used in place of its land Move while airborne. While flying, it ignores ground-level Difficult Terrain and obstacles entirely. A creature with both a land Move and a Fly Move picks one mode at the start of its movement each activation and can't mix the two in a single move. Leaving an enemy's Threat Zone by flying away still triggers the normal Provoking rule (a free Aggressor strike) unless another Trait, such as Skittering, says otherwise.

---

## The Environment:

### Illumination (Light & Sight)

Every square is in one of three light bands. They don't add a new modifier of their own — Dimly Lit and Pitch Black plug directly into Cover's existing Obscured tiers below, so "dim lighting" and "pitch black" in the Cover rules specifically mean these bands.

- **Well Lit:** Full, unobstructed light. No modifier.
- **Dimly Lit:** Equivalent to **Obscured** (see Cover, below) — Attacker has Disadvantage on the Attack. Also grants Advantage on Stealth checks made within it.
- **Pitch Black:** Equivalent to **Heavily Obscured** (see Cover, below) — Attacker has Disadvantage, target gains +2 to Defense. Also grants Advantage on Stealth checks made within it, and counts as an Obscured/Heavily Obscured position for anything that keys off one (e.g. the Cultist Assassin's Vanish).
- **No light source, no ambient light: Pitch Black.**

**Light source radii:**

| Source | Well Lit radius | Dimly Lit radius (beyond Well Lit) |
|---|---|---|
| Torch, Candle, Tindertwig (Community Supply Die abstraction), Lamp (common), Everburning Torch | 20 ft | 10 ft |
| Sunrod | 30 ft | 15 ft |
| Hooded Bullseye Lantern | 30 ft, forward cone only | None — hooded and directional, no ambient spill |

- **The halving rule:** Unless a source says otherwise, its Dimly Lit ring extends half again as far as its own Well Lit radius (the baseline torch: 20 ft Well Lit, then 10 ft more of Dimly Lit — 30 ft total before Pitch Black).
- **Overlapping light:** Where two sources' radii overlap, use whichever band is brighter for that square. Light doesn't stack past Well Lit.

### Cover (The Environmental Shield)

Being Obscured acts as a direct negative modifier to the attacker's roll.

-  **Obscured (Thick underbrush, dim lighting [see Illumination, above], smoke):** You can track the target, but you are guessing their movements.

    - **The Mechanic:** Attacker has **Disadvantage** on the Attack.

- **Heavily Obscured (Pitch black [see Illumination, above], dense fog, swirling magical static):** You are effectively fighting blind. You might know they are in the zone, but you cannot pinpoint them.

    - **The Mechanic:** Attacker suffers **Disadvantage** on the Attack, and the target gains a **+2 bonus to their Defense roll**, representing the attacker’s inability to find a viable opening.

Physical barriers reduce the power of an incoming attack. They are rated by how much Impact they absorb.

-  **Partial Cover (Crates, low walls, a thin pillar):** The target is protected by a solid object, but not fully enveloped.

    - **The Mechanic:** When the target is hit, they may spend their **Block** or **Brace** action value to reduce the incoming Impact by 2.

- **Full Cover (Stone walls, reinforced iron doors, heavy portcullis):** The target is entirely hidden behind a physical object that can stop projectiles and heavy strikes.

    - **The Mechanic:** You cannot Strike a target in Full Cover unless you first spend an Action to destroy or bypass the cover. If an area-of-effect ability is used, the cover absorbs the full Impact value of the attack before the target is affected.

#### Firing Into Combat (The Risk of Friendly Fire)

When a character shoots at an enemy that is actively engaged in melee with an ally, two things happen:

- *The Chaos Penalty:* The attacker suffers disadvantage to their attack roll. (The shifting bodies essentially act as obscured).

- *The Friendly Fire Trigger:* If the attack roll fails, and either of the 2d6 dice shows a natural "1", the projectile strikes an engaged ally instead.

- *The Resolution:* You immediately compare that same failed attack total against your Ally's Wound Threshold and resolve impact as normal.

---

#### ENVIRONMENTAL HAZARDS (Survival & Athletics)

High Fantasy heroes journey across brutal landscapes. In this system, the environment attacks your Stress track before it attacks your Wounds.

- *The Mechanic:* When facing severe conditions (a blizzard, a scorching desert, freezing water), the GM calls for a Hazard Check—usually 2d6 + Survival to navigate it safely, or 2d6 + Athletics to physically endure it, against TN 8.

- *The Cost of Failure:* Failing a Hazard check inflicts 1d3 Locked Stress (or more, depending on severity).

- *The Death Spiral:* if a character's Stress limit is maxed out by a Hazard, any further Stress instantly converts into Wounds. This means a character can literally freeze to death or die of exhaustion without ever taking a sword swing.

---

## The Hazard Roll (Trap Resolution)

Traps and environmental hazards do not deal flat damage. When triggered, the GM makes a Hazard Roll (2d6 + the trap's Hazard Power) to generate a Strike Total, representing the speed, weight, or lethality of the mechanism.

How the trap resolves depends entirely on the player's awareness.

##### 1. The Unaware Target (The Ambush)

The player fails to spot the tripwire, or opens the chest without checking for a poison needle.

- The Resolution: The player is caught flat-footed, but not helpless — they may still act as the Reactor in a Clash against the trap's Hazard Roll, at Disadvantage, using Dodge only. A body that never saw the threat coming can still flinch away from it; it can't raise a shield or intercept a blade it never registered, so Block and Parry stay off the table regardless of what a given trap allows an Aware target.
- The Math: As with an Aware target, the Margin between the trap's Hazard Roll and the player's (Disadvantaged) Dodge determines the final Impact. Any win avoids the hazard entirely; a **Margin 5+** win also generates 1 Momentum, exactly as it would for an Aware target — a lucky flinch is still a lucky flinch.
- The Armour Check: On a loss, compare the resulting Impact against the player's Wound Threshold as normal — meeting or exceeding it inflicts a Wound, falling short inflicts 1 Dissonant Stress.

##### 2. The Aware Target (The Desperate Reaction)

The player spots the pressure plate but is forced to leap across it, or they deliberately trigger the swinging axe to study its timing.

- The Resolution: The player knows the threat is coming and acts as the Reactor in a standard Clash against the trap's Hazard Roll.

- Choosing the Defense: Unless the specific trap dictates a required reaction (e.g., a room-filling poison gas might strictly require a Dodge to reach the door), the player can choose their defense:

- Dodge: Attempting to completely physically avoid the mechanism.

- Block: Raising a heavy shield to absorb a dart volley or falling rocks (subtracting their Shield Value from the Impact, per the standard Block Reactor action, if they lose the Clash).

- Parry: Using a weapon to jam the gears or bat away a swinging blade.

- The Math: Just like in combat, the mathematical Margin between the trap's roll and the player's defense roll determines the final Impact. If the player wins the Clash, they avoid the hazard entirely; winning by a **Margin of 5+** also generates 1 Momentum for their flawless reflexes, per the standard Momentum ladder (Iron Core).

#### Example Hazards in the Engine

- Corpse-Rust Dart Trap (Hazard Power +3):

- Specifics: A hidden wall-shooter.

- Aware Requirement: If aware, the player can Block or Dodge, but cannot Parry the tiny projectiles.

- Crushing Iron Portcullis (Hazard Power +6):

- Specifics: A massive gate dropping from the ceiling.

- Aware Requirement: Must Dodge to roll under it. Attempting to Block or Parry such massive weight automatically fails, resulting in the player becoming Anchored beneath the iron.

#### Falling (Height as a Hazard)

A fall is resolved as a Hazard Roll like any other trap — the ground doesn't care whether the drop came from a trap, a shove, or a bad jump.

| Fall Height | Hazard Power |
|---|---|
| Short (10–20 ft) | +2 |
| Medium (20–40 ft) | +4 |
| Long (40 ft+) | +6 |

- **Aware (a controlled fall):** A character who chooses to fall, or sees it coming with enough time to react, resolves it as an Aware target: Dodge only — you can't Block or Parry a landing. Winning the Clash means a hard but controlled landing; the Margin sets the final Impact per the standard Aware rules.
- **Unaware (a genuine surprise):** Shoved from behind, a trapdoor sprung with no warning, or falling unconscious — resolved as Unaware per the normal rules: the Hazard Roll total becomes Impact directly against Wound Threshold, no Defense allowed.
- **Landing on something worse than ground:** If the fall ends on spikes, rubble, or another hazard, add that hazard's own Hazard Power to the fall's rather than rolling twice.

---

## THE SOCIAL ENGINE (Influence & Resolve)

In High Fantasy Realism, a silver tongue is just as dangerous as a drawn sword, but it isn't mind control. Social encounters use Influence (to push your agenda) opposed by the target's Resolve. A target with no Resolve skill simply rolls 2d6+0 — Attributes are never added to a roll, so an untrained defender rolls flat rather than falling back on Will.

#### The Stance System

NPCs have four basic social stances, forming a single ladder: **Hostile → Unfriendly → Neutral → Friendly.**

- **Hostile:** Actively opposed. Will act against the party — refuse service, raise an alarm, draw a weapon, sabotage where possible.
- **Unfriendly:** Wary, distrustful, uncooperative — but not yet acting against the party. The default state for someone who has reason to dislike or distrust the party but hasn't been pushed to outright opposition.
- **Neutral:** No strong opinion either way. The default starting state for anyone the party hasn't meaningfully interacted with.
- **Friendly:** Genuinely won over. Will help, vouch, take modest risks on the party's behalf.

**The Mechanic:** To change an NPC's stance or convince them to do something risky, roll an opposed check: **2d6 + Influence vs. 2d6 + Resolve.**

- **Standard Success (Margin 0–4):** Shift the NPC's stance **one step** toward the direction you were pushing (e.g., Hostile → Unfriendly, or Neutral → Friendly). Alternatively, if not attempting a stance shift, they agree to a request that doesn't put them in immediate danger.

- **Massive Success (Margin 5+):** Shift the NPC's stance **two steps** toward the direction you were pushing. This is a deliberate, flat rule — a Massive Success always moves exactly two rungs, never jumping straight to the opposite pole regardless of where the NPC started. Going from Hostile all the way to Friendly in a single roll still requires either two separate successful checks, or one Massive Success from an Unfriendly starting position.

- **Leverage (Modifiers):** The GM applies a +2 or -2 modifier based on the fiction. Bribing a greedy guard is +2. Threatening a fanatical cultist is -2.

# Chapter 5 — Hardware

*Equipment*

## The Inventory
#### 1. The Visual Slot System

Instead of tracking weight, a character’s carrying capacity is defined by a hard limit of physical "Slots" drawn on their character sheet as literal boxes.

- Total Capacity: Every character has a base of 8 Slots, plus their Brawn (Max 11 total slots).    
- Item Sizing:    

- 1 Slot: A one-handed weapon, a shield, a coiled rope, a Grimoire, a lantern, a cluster of 3 potions.    
- 2 Slots: A heavy two-handed weapon, a bulky Bestiary trophy (a Gorgon's head), a small treasure chest.    
- 0 Slots (Micro-Items): Things you can hide in a pocket don't take slots unless stacked in bulk. (e.g., 100 coins = 1 Slot).    

- Worn Armour Exemption: The armour a character is actively wearing does not take up Slots, but heavy armour inherently limits movement or stealth. If they take it off to carry it, it consumes 3 Slots.

**Containers Don't Multiply Slots:**
A container's listed Slot cost is for **the object itself**, full stop. Owning one never grants extra carrying capacity — it isn't a nested storage space, it's an item like any other. One 2-Slot chest consumes 2 - slots of Inventory and has a volume of 2-Slots. If the box is stolen or lost, any contents is stolen or lost with it.

**What decides whether an _empty_ container costs a Slot at all:**
- **Rigid/bulky-shaped** containers (Basket, Chest, Barrel) hold their shape and bulk whether full or empty, so they cost their listed Slots regardless of contents.
- **Soft/collapsible** containers (Sack, Belt Pouch, the Backpack itself) fold to nothing when unstuffed, so they're 0 Slots — until something with its own Slot cost goes inside, at which point you're tracking _that item's_ cost, not an extra charge for the sack around it.

**The Backpack** is still 0 Slots and worn-exempt, but to be explicit: it doesn't add capacity either. It's the fictional wrapper for the Pack designation, not a bag of holding — the Pack's actual size is fixed entirely by the character's Brawn-derived Slot total, independent of what container physically holds it.

#### 2. The Belt vs. The Pack (Action Economy)

To stop players from instantly accessing a dozen different items during a sword fight, the Slots are divided into two physical locations with strict action costs.

- The Belt (Readied Gear): 3 Slots maximum. These are items hung on the belt, bandoliers, or sheaths. A character can draw an item from The Belt as a Free action during combat.

- The Pack (Stowed Gear): The remaining Slots. These are items strapped to the back or buried in a rucksack. Retrieving an item from The Pack mid-combat is practically impossible while dodging blows—it requires the player to forfeit their entire turn and take the Regroup action just to rummage through their bag.

Tactical Result: If the Pyromancer has a healing potion in their Pack, they cannot simply drink it while being attacked. They have to retreat, take the Regroup action to dig it out, and hope the Fighter holds the line.

#### 3. The Attrition Tax (Wounds Limit Gear)

This is where the encumbrance system ties directly into your Death Spiral. As a character gets physically destroyed, their ability to bear weight collapses.

- The Mechanic: Every time a character suffers a Wound, they must immediately permanently cross out 1 Inventory Slot on their sheet.

- The Choice: If that Slot currently holds an item, the player must immediately drop an item in the dirt, or suffer 1 Dissonant Stress every single turn they continue to drag the excruciating weight.

- Narrative Impact: This forces agonizing decisions. Do you drop the heavy bag of gold you just found to carry your bleeding ally, or do you leave the ally behind to keep the treasure?

---

## The Community Supply Die
**The Community Supply Die**
_Hardware_ abstracts the party's shared consumables into the Community Supply Die so nobody tracks individual arrows, torches, or waterskins. Concretely, that's:

- **Ammunition** — arrows, bolts, sling stones, thrown weapons you don't bother retrieving. **Not black powder:** firearm loads are bought and tracked individually (see the Black Powder tag).
- **Light & Fuel** — torch stubs, lantern oil, flint-and-steel strikes, tindertwigs.
- **Field Rations & Water** — trail rations, waterskin refills.
- **Field Medicine** — the bandages and clean linen that make a Breather or a Long Rest actually work (see Iron Core). This is why a Depleted die specifically blocks a Breather or a Long Rest from clearing Stress — there's nothing left to bind the wounds with.

**The dividing line:** if it's _used up in the doing_ — an arrow loosed, oil burnt, a ration eaten, a bandage wound around a cut — it's the Die's problem. If it _still exists and still works_ after you use it — a bow, a lantern, a crowbar, a coil of rope — it's a normal Slotted item, tracked individually.

**Does the Die itself take a Slot?** No. It isn't a discrete object on any one character's sheet — it's already distributed as flavor across everyone's belts and packs collectively. Don't write "1× Supply Die" under anyone's inventory.

Instead of tracking every torch, bandage, and arrow, the entire party relies on a single shared abstraction of their collective resources.

- The Die Track: A party begins play with a **d8** Supply Die (see *The Marrow*). A **d10** is the fully stocked ceiling — reached by restocking in Downtime (20 sp, see *Soothing the Soul*) or mid-dungeon via *Scavenge and Cannibalize* or *Preserve*, never the default. The degradation track is: d10 → d8 → d6 → d4 → Depleted.

- The Roll: When required, any player rolls the current Supply Die. On a result of 1 or 2, the supplies dwindle, and the die steps down to the next lowest tier.

- The Depleted State: If a d4 steps down, the party is completely out of usable incidentals. Until restocked, no one can fire a bow, Breathers do not heal Dissonant Stress (no clean bandages or rations to offer comfort), and the dungeon is pitch black unless powered by magic.

**Replenishing it**, via the existing Acquisition Downtime Pursuit (_Soothing the Soul_):

| Step                             | Cost            |
| -------------------------------- | --------------- |
| Depleted → d4                    | 5 sp            |
| d4 → d6                          | 10 sp           |
| d6 → d8                          | 15 sp           |
| d8 → d10                         | 20 sp           |
| **Full restock, Depleted → d10** | **50 sp total** |

#### When to Roll the Die

1. The Breather: the party must roll the Supply Die at the exact end of a 30-minute Breather. This represents the bandages used, the rations eaten, and the torch fuel burned while resting.

2. The Catastrophic Failure: If a player rolls a Natural 2 (Double 1s) while firing a ranged weapon or navigating a physical hazard, the GM can force a Supply Die roll as arrows shatter, bowstrings snap, or a pack falls into the mud.

3. The Long Rest: the party rolls the Supply Die once at the conclusion of a Long Rest (see Iron Core) — the same single roll as a Breather, not scaled up for the extra length.

---

## Quality
**MERCANTILE CRAFTSMANSHIP STATUS**

Items found in local markets carry tags denoting the skill of the artisan who hammered them together.

*Shoddy Quality*
- Cost Modifier: -50% to base price.

- 2d6 Rule: Rusted iron, green wood, or poor craftsmanship. If a character rolls a fumble (Snake Eyes) or even just a standard failure while using a Shoddy item, the item is immediately Damaged. If it is already Damaged, it shatters completely and is Ruined.

*Balanced Quality*
- Cost Modifier: +100% to base price.

- 2d6 Rule: Perfectly weighted pommels or expertly aligned shafts. Once per scene, when rolling a Clash or Skill check using this item, the player can reroll a single die that landed on a '1' or a '2', mitigating low-end variance. (Broader than the Finesse tag's reroll, which only catches natural 1s — so Balanced remains worth paying for on a Finesse weapon, and the two stack: Finesse first, then Balanced on the remaining die.)

*Masterwork Quality*
- Cost Modifier: +300% to base price (Requires a specialized Commission downtime action).

- 2d6 Rule: Folded steel or bespoke custom-molded plating. Weapons gain a permanent +1 to their Power profile. Armour pieces grant their mechanical defensive bonuses but completely suppress one negative tag associated with them (e.g., a Masterwork Chainmail shirt loses its Bulky penalty).

---

## Gear Condition

**DAMAGED AND RUINED (THE CONDITION TRACK)**

Quality (above) describes how good a piece of gear was *when new*. Condition describes what's happened to it since — a Shoddy roll, ordinary wear, or **being attacked directly** (see Structural Damage and Destruction, Iron Core, which uses this same two-step track as an object's Wound Slots). Every weapon, armour piece, shield, or tool — regardless of its Quality tier — can degrade along the same two-step track: **Damaged**, then **Ruined**.

*Damaged (Tag)*

- **The Effect:** The item suffers a flat **-1 penalty** to whatever numeric value it normally contributes to a roll or calculation. A Damaged weapon applies -1 to its Power. Damaged armour applies -1 to its Armour Value. A Damaged shield applies -1 to its Shield Value (SV). A Damaged tool kit applies -1 to the relevant skill check it would normally assist.

- **The Fiction:** The item still works — a cracked breastplate still stops most of a blow, a notched blade still cuts — but it's compromised. This is what separates Damaged from Ruined: Damaged gear is degraded but still usable in a fight without needing repair first.

- **Stacking:** Damaged does not stack with itself. An already-Damaged item that would be Damaged again is immediately **Ruined** instead (see below) — the second failure is what finally breaks it past the point of limping along.

*Ruined (Tag)*

- **The Effect:** The item is **non-functional**. A Ruined weapon deals no Power (Unarmed-equivalent only), Ruined armour grants no Armour Value, a Ruined shield grants no SV, and a Ruined tool cannot be used to assist any check at all.

- **The Fiction:** Shattered, snapped, or warped beyond field use. This isn't a -1 anymore — it's gone until someone puts real work into it.

- **Repair:** A Ruined item cannot be restored mid-dungeon by any of the temporary battlefield fixes below — it requires a **Hammer & Forge** downtime action back in civilization (or an equivalent feat/Momentum spend that explicitly says it can strip the tag, such as Cannibalize Gear) to become functional again.

**Getting From Damaged Back to Working**

- **Temporary Field Fixes** (e.g., The Patch Job) let a character ignore the -1 Damaged penalty for the duration of the current encounter only. The penalty returns the moment the fight ends — wire and sap aren't a permanent solution.
- **Permanent Field Repair** (e.g., Cannibalize Gear) strips the Damaged tag entirely, mid-dungeon, at the cost of cannibalizing a separate piece of equipment. This is the only way to permanently clear Damaged without returning to town.
- **Downtime Repair** (Hammer & Forge) is the standard route back from either Damaged or Ruined once in civilization: **1 day, 1 PP, and roughly 25% of the item's base value in materials** (*Soothing the Soul*). The materials requirement — and only that requirement — is waived by **Macabre Genius** (The Marrow, Tier 3), which repairs out of salvage instead.

    *Repair costs coin deliberately. Without it, **Shoddy** gear would be strictly better value than Balanced — cheaper to buy, and breaking would cost only a day — and every effect in the game that damages gear (a Shoddy fumble, `Sunder`, Caustic Deluge, Vitriol Solvent, the Rust Monster) would be a tempo tax rather than a cost.*

**Condition is not the same as baseline.** Damaged and Ruined are **Conditions** — states laid over an item — and Hammer & Forge clears them. A **permanent** reduction is a different thing: it lowers what the item *is*. **Hammer & Forge restores an item to its current baseline, not the one it left the smith with**, so a permanent loss stays lost however many times the item is repaired. Only three effects in the game reach the baseline, and each says so outright: **`Sunder`**'s Armour reduction (below), **Caustic Deluge**'s shield and armour damage, and **The Long Rust**'s weapon and shield degradation (both in *Manipulating The Void*). Everything else that hurts gear produces a Condition, which a smith can undo. The counterweight already exists and runs the other way: **Macabre Genius** (Tier 3) permanently *raises* an item's baseline, upgrading it to **Masterwork**.

---

## Enchantments

### The Third Axis

Quality (above) describes how good an item was when it was forged. Condition describes what's happened to it since. **Enchantment is a third, fully independent axis** — a Balanced-Quality, Damaged-Condition, Enchanted longsword is a perfectly coherent item, and all three lines are answered separately. Magic in Iron & Marrow does not stack flat bonuses on top of the existing Power/Wound Threshold math — that headroom is already spent (see the Weapon Power tiers, and the Golden Rule that Wound Threshold bonuses from magical sources don't stack). Instead, enchanted items grant **tags, Momentum-gated abilities, or Bane effects** — the same vocabulary spells and Domain Tags already use elsewhere in the system.

### Attunement

Wearing or carrying an Enchanted or Relic item permanently isn't free — a sliver of the magic occupies a corner of the wielder's mind.

- **Trinkets and Charmed items never require Attunement.** Wear or carry as many as you like.
- **Enchanted and Relic items cost 1 Locked Stress each to Attune.** This Stress is locked for as long as the item is bonded to its wielder and **cannot be cleared, unlocked, converted or removed by any means while it remains attuned** — no Reprieve, Long Rest, Breather, Downtime Pursuit or number of nights, no alchemical preparation, no Feat, spell or Prayer reaches it, and Breaking passes it over rather than converting it. The only release is deliberately unattuning (see Iron Core's Golden Rules). Note this is **stricter** than a Flowing Prayer's Locked Stress, which alchemy can force open at a price.
- **Unattuning takes 10 minutes of uninterrupted handling** — safe to do during a Breather or downtime, impossible mid-combat.
- **Attunement Slots = Will score (minimum 1).** A character cannot be Attuned to more Enchanted/Relic items at once than this.
- Losing an Attuned item mid-combat (disarmed, stolen, Sundered) does not instantly refund the Stress — it releases at the start of the wielder's next Activation, the same beat as any other Sustain dropping.

### The Four Tiers

| Tier          | Availability                   | Attunement                                    | Power Level                                                                                          |
| ------------- | ------------------------------ | --------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| **Trinket**   | Common/Scarce                  | None                                          | Flavor only, or a single trivial non-combat nudge — the "Cantrip" of magic items.                    |
| **Charmed**   | Scarce/Rare                    | None                                          | One tag grant, or a narrow situational bonus — roughly Novice-spell strength.                        |
| **Enchanted** | Rare/Legendary                 | 1 Locked Stress                               | A real ability, or a Momentum-gated active — Adept-spell strength.                                   |
| **Relic**     | Legendary, unique, GM-authored | 1 Locked Stress + a bespoke built-in drawback | Master Prayer/Tier 3 Feat strength. Not purchasable — a campaign fixture with a name and a history. |

**On Relics specifically:** the Locked Stress cost alone isn't enough of a toll for Master-tier power. Per the same logic already used for Resurrection's Soul Scar and Half-Elf's inherited drawbacks, a Relic's cost should be written into the item itself, not just paid for in Stress. Don't hand out a Relic without also handing out its hook.

---

#### Trinkets (No Attunement)

**Ever-Warm Hearthstone** — 8 sp | Common
A fist-sized river stone that radiates gentle warmth and never needs fuel. No mechanical effect — a comfort item only. Cold-weather Survival Hazard Checks (per Iron World) are still made normally; this just makes camp pleasant.

**Chorus Locket** — 15 sp | Scarce
A hinged locket that records up to 10 seconds of whispered sound and replays it once when opened. No combat application — a message-passing or narrative tool only.

**Prattling Bauble** — 6 sp | Common
Jewellery that shifts through a slow spectrum of colours when tapped, or a stone that releases a wisp of perfume when rubbed. Common "adventurer curiosity" loot, worth exactly what a buyer will pay for a conversation piece.

#### Charmed (No Attunement)

##### General Utility (Scarce)

**Sure-Foot Charm** — 20 sp | Scarce | 0 Slots (Micro-Item, worn)
A knotted cord anklet, warm against the skin even in cold mud.
- **Effect:** Advantage on Athletics checks made to resist Difficult Terrain's movement penalty (Iron World). Does not remove the Disadvantage on mobility checks made within it — the wearer still fights the mud, just doesn't get stuck in it.

**Farsight Lens** — 20 sp | Scarce | 0 Slots (Micro-Item, carried)
A single brass-ringed lens, ground thinner at the center than any glazier would call sound practice.
- **Effect:** Advantage on Notice checks made to spot something at Long Range or beyond.

**Ember Locket** — 15 sp | Scarce | 0 Slots (Micro-Item, worn)
A small hinged locket that never quite goes cold, holding a coal that was never lit and never goes out.
- **Effect:** Once per Scene, clear 1 point of Locked Stress gained specifically from a failed cold-weather Hazard Check (Iron World, Environmental Hazards).

**Merchant's Thumb-ring** — 20 sp | Scarce | 0 Slots (Micro-Item, worn)
A plain band, worn smooth on the inside from a lifetime of counting coin.
- **Effect:** +2 to a single Acquisition check made when selling (Soothing the Soul) — stacks with existing Settlement Tier and Reputation modifiers. Once per settlement visit.

**Grappler's Ring** — 18 sp | Scarce | 0 Slots (Micro-Item, worn)
A rope-textured iron ring, cold and slightly abrasive to the touch.
- **Effect:** Advantage on Athletics checks made to escape the Anchored condition.

**Quiet Step Buckles** — 15 sp | Scarce | 0 Slots (worn, per Clothing/Worn Armour Exemption)
A pair of boot buckles that make no sound striking stone, no matter how hard the boot comes down.
- **Effect:** Once per Scene, ignore Rushed Stealth's Disadvantage (Iron World) for a single Move.

_Bane items below deliberately don't cover every Creature Type. Humanoid and Beast have no entry — not an oversight. Bane exists to answer "how do I reliably hurt something ordinary steel struggles against"; regular people and animals don't have that problem, a plain arming sword already does the job._

**Silvered Edge** (weapon add-on) — 40 sp | Rare
Requires a bladed or bludgeoning weapon. The striking surface is chased in pure silver, ground into the metal by hunters who learned the trade the hard way.
- **Effect:** Bane (Lycanthrope) — see Bestiary: Creature Types. The wielder treats a Lycanthrope target's Wound Threshold as 1 point lower.
- *The classic trope, mechanized: cold, pure silver reliably bites through a curse-born hide in a way ordinary steel doesn't.*

**Blessed Edge** (weapon add-on) — 40 sp | Rare
Requires a bladed or bludgeoning weapon, sanctified by a Priest of any Domain (fictionally, a Religious Pursuit spent in dedication to the weapon rather than the self).
- **Effect:** Bane (Undead) — see Bestiary: Creature Types. The wielder treats an Undead target's Wound Threshold as 1 point lower.
- *Deliberately the same number Smite Corruption already grants a Domain of Law Priest for free — this item is how anyone else buys a sliver of that same ward against corruption made physical. Note this is a flavor name, not a new mechanical tag — it does not grant the Blessed Condition (Iron Core); the two are deliberately kept separate so the word "Blessed" doesn't mean two different things depending on whether it's on a character sheet or an item card.*

**Cold Iron Weapon** (weapon add-on) — 25 sp | Scarce
Requires a weapon. Forged from iron worked pure of the impurities that make ordinary steel — heavier, softer, and murder on anything that isn't wholly of this world.
- **Effect:** Bane (Fey). The wielder treats a Fey target's Wound Threshold as 1 point lower.
- *Cold iron answers what is not wholly of this world by birth rather than by corruption — the Fey and their kin alone. Against **The Hag** and **The Hag Matriarch** (Bestiary) it does three jobs: the Bane above, stripping a **Glamour** on any hit, and refusing **Sister's Blood** — a Matriarch cannot pass a Cold Iron Wound to her coven.*

**Sun Iron** (weapon add-on) — 40 sp | Rare
Requires a weapon. Iron quenched at first light for nine consecutive dawns, then worked while the metal still holds the warmth.
- **Effect:** Bane (Vampire) — see Bestiary: Creature Types. The wielder treats a Vampire target's Wound Threshold as 1 point lower.

**Wyrmtooth** (weapon add-on) — 220 sp | Legendary, Commission-gated
Requires a harvested Dragon tooth, claw, or scale shard, and a weapon to set it into.
- **Effect:** Bane (Dragon) — see Bestiary: Creature Types. The wielder treats a Dragon target's Wound Threshold as 1 point lower.
- *Priced and gated well above the other Charmed Bane items for a purely narrative reason, not a mechanical one — the effect is identical in strength to Silvered Edge or Blessed Edge, but the raw material is the entire cost. A party is far more likely to loot one of these off a dead wyrm than find one for sale.*

**Grounding Chain** (weapon add-on) — 40 sp | Rare
Requires a weapon. A fine copper-and-iron chain wound through the grip or haft, humming faintly when the air itself starts to feel wrong.
- **Effect:** Bane (Elemental) — see Bestiary: Creature Types. The wielder treats an Elemental target's Wound Threshold as 1 point lower.
- *Named for the same underlying idea as the Mage Staff's Grounding Rod tag — venting raw, ungoverned energy safely to earth, just applied outward through a strike instead of inward through a caster's own working.*

**Rust-Bitten Edge** (weapon add-on) — 35 sp | Rare
Requires a weapon. Treated in a slow-acting alchemical bath related to the same formula behind Vitriol Solvent — a controlled, permanent version of the same corrosion, bonded into the metal rather than splashed on fresh each fight.
- **Effect:** Bane (Construct) — see Bestiary: Creature Types. The wielder treats a Construct target's Wound Threshold as 1 point lower.

**Cinder-Wrought Edge** (weapon add-on) — 35 sp | Rare
Requires a weapon. Tempered in a bed of true embers rather than water or oil — the blade never fully loses its warmth.
- **Effect:** Bane (Ooze) — see Bestiary: Creature Types. The wielder treats an Ooze target's Wound Threshold as 1 point lower.
- *Fire is the standard answer to "how do you stop something that just re-forms" across enough fiction to earn its slot here — and it's already the system's own answer, since Wildfire Proliferation and the rest of the Pyromancy list are built on exactly that same idea of persistent, decisive damage.*

**Leadglass Ward** (weapon add-on) — 40 sp | Rare
Requires a weapon. A sliver of lead-heavy glass, ground to a precise, unnatural facet and set into the blade or haft — it doesn't reflect light so much as refuse it.
- **Effect:** Bane (Void-Touched) — see Bestiary: Creature Types. The wielder treats a Void-Touched target's Wound Threshold as 1 point lower.
- *Worth being honest about this one's ceiling: several written Void-Touched abilities (Flay the Veil, most notably) already bypass Wound Threshold and Armour entirely by design. Leadglass Ward still matters in any fight that comes down to ordinary Impact-vs-Threshold math, but it isn't the reliable answer Silvered Edge is against a Lycanthrope — useful, not a silver bullet.*

**Quicksilver-Traced Edge** (weapon add-on) — 35 sp | Rare
Requires a weapon. A hair-thin vein of quicksilver run along the fuller or edge — an old alchemist's belief that the thing which unmakes flesh can also unmake what remade it.
- **Effect:** Bane (Mutant) — see Bestiary: Creature Types. The wielder treats a Mutant target's Wound Threshold as 1 point lower.

##### General Utility (Rare, Non-Bane)

**Cloak of Still Water** (armour add-on) — 35 sp | Rare | No additional Slot — occupies the base armour's existing Slot allowance.
A grey, unremarkable cloak that seems to drink ambient noise.
- **Effect:** The wearer gains Advantage on Stealth checks while moving at half their Move value or slower — turning the existing Rushed Stealth penalty (Iron World) into a non-issue for anyone patient enough to earn it, rather than granting a new kind of bonus outright.

**Warding Buckler** (shield add-on) — 40 sp | Rare | No additional Slot — requires a one-handed shield already carried; occupies that shield's existing 1 Slot.
A small round shield boss etched with concentric rings, fitted to an existing shield rather than sold whole.
- **Effect:** Once per Scene, when the wearer wins a Block Clash with a Margin of 3+ (Clean or better), they generate 1 additional Momentum beyond the standard win — a masterful parry-block earns extra tempo, on top of avoiding the hit.

**Wind-Step Greaves** (armour add-on) — 40 sp | Rare | No additional Slot — occupies the base armour's existing Slot allowance.
Light shin-guards that never seem to catch on anything underfoot.
- **Effect:** Once per Scene, when the wearer wins a Dodge Clash with a Margin of 3+ (Clean or better), they may immediately shift 1 square as a Free Action, without triggering a free strike, as part of the same reaction.

**Riposte Guard** (weapon add-on) — 40 sp | Rare | No additional Slot — requires a weapon already carried.
A steel hand-guard fitted below the crossbar, angled for a return strike rather than a hold.
- **Effect:** Once per Scene, when the wearer wins a Parry Clash with a Margin of 3+ (Clean or better), the attacker suffers **Impact 4**, ignoring Armour, from the wearer's controlled riposte (Iron Core, *Incidental Damage*).

**Watcher's Pendant** — 45 sp | Rare | 0 Slots (Micro-Item, worn)
A dark pendant, cool to the touch, that seems to twitch a moment before anything else in the room does.
- **Effect:** Once per Scene, when the wearer would otherwise resolve a trap or ambush as an Unaware Target (Iron World), they instead resolve it as an Aware Target — full Dodge/Block/Parry choice, no Disadvantage.

**Steadying Charm** — 35 sp | Rare | 0 Slots (Micro-Item, worn)
A worn river stone, unremarkable except for how naturally it sits in a closed fist.
- **Effect:** Once per Scene, reroll a failed Resolve check made specifically against the Fear condition. Keep the second result.

**Glowless Lantern-Ring** — 45 sp | Rare | 0 Slots (Micro-Item, worn)
A dull iron ring that seems to gather what little light is already there rather than making more of its own.
- **Effect:** The wearer treats Dimly Lit conditions (Iron World's Illumination rules) as Well Lit for the purposes of their own attack rolls only — a personal edge against gloom, not a light source others can share. Has no effect in Pitch Black.
- *Interaction with **Halgrim's Grave-Crown**: the Crown reads all light one band darker for its wearer and this ring reads Dimly Lit as Well Lit for attack rolls, so in a genuinely Well Lit room the ring does cancel the Crown's cost for attacking. It does **not** rescue a Dimly Lit one — the Crown makes that Pitch Black, where the ring has no effect at all. The Crown's drawback still bites everywhere a dungeon actually happens.*

#### Enchanted (1 Locked Stress Attunement)

Attunement is capped separately from Inventory — a character cannot be Attuned to more Enchanted/Relic items at once than their Will score (minimum 1). This tier spans two price bands: a Rare tier for a first real magic item, and a Legendary tier for late-campaign power.

##### Rare Tier

*Items in this tier take one of two shapes. Most are a **Momentum-gated active**, per the Enchantment tier table above — the Attunement's permanent Locked Stress buys a tool you can reach for as often as your Bank allows, not one free trigger a Scene. The rest are **permanently on**: a passive trait strong enough to earn a permanent Locked Stress box, such as Boots of the Long Road's +10 ft Move. An effect that fires only once per Scene belongs at **Charmed** in either shape, where it costs no Attunement at all (compare Quiet Step Buckles against the Boots of the Silent Step below).*

**Band of the Steady Hand** (ring) — 90 sp | Rare | 0 Slots (Micro-Item, worn)
A plain iron ring, warm to the touch regardless of the weather.
- **Effect:** **Spend 1 Momentum** to reroll a single failed Ranged attack roll. Keep the second result. Repeatable as often as your Bank can pay for it.

**Ring of the Anchor** — 85 sp | Rare | 0 Slots (Micro-Item, worn)
A heavy-looking ring that is, in fact, quite light.
- **Effect:** **Spend 1 Momentum** when the wearer would be shoved out of position or knocked Prone to negate that effect entirely, as if the check that caused it had been passed. Repeatable as often as your Bank can pay for it.

**Amulet of Even Breath** — 90 sp | Rare | 0 Slots (Micro-Item, worn)
A small clay bead on a plain cord, said to hold one held breath, kept for later.
- **Effect:** **Spend 1 Momentum** to immediately clear 1 Dissonant Stress upon taking a Wound. Repeatable as often as your Bank can pay for it. *(The item version of the Half-Orc's Blood Frenzy trait — a proven pressure-release valve against Stress-to-Wound conversion, made purchasable rather than species-born.)*

**Boots of the Long Road** — 80 sp | Rare | 0 Slots (worn, per Clothing/Worn Armour Exemption)
Well-worn leather boots that never seem to blister the feet inside them.
- **Effect:** The wearer's Move increases by 10 ft. Difficult Terrain (Iron World) halves this improved total rather than the wearer's base Move.

**Boots of the Silent Step** — 85 sp | Rare | 0 Slots (worn, per Clothing/Worn Armour Exemption)
Soft-soled boots that drink footfalls the way Cloak of Still Water drinks ambient noise.
- **Effect:** **Spend 1 Momentum** to ignore Rushed Stealth's Disadvantage (Iron World) for the rest of the current Scene — the Enchanted-tier step up from Quiet Step Buckles, which buys a single Move once per Scene and costs no Momentum or Attunement at all.

**Signet of Sound Mind** — 95 sp | Rare | 0 Slots (Micro-Item, worn)
A plain signet ring, its seal worn smooth and unreadable.
- **Effect:** **Spend 1 Momentum** when a point of Stress would fill the last empty box on your Stress track: that point is lost instead, and you do not Break. Repeatable as often as your Bank can pay for it. It has no effect once the track is already full — it holds the mind back from the edge, it cannot pull it back from over it.

##### Legendary Tier

**Sigil-Etched Blade** — ~150 sp | Legendary, Commission-gated
A longsword (or similar) inlaid with warding sigils that glow faintly hot to the touch of anything unnatural.
- **Effect:** Bane (Undead, Daemon). **Spend 1 Momentum** on a successful hit against a Bane-eligible target to also inflict the Fear condition (per the Bestiary Trait of the same name). Repeatable as often as your Bank can pay for it.

**Blade of the Undertow** — ~150 sp | Legendary, Commission-gated
A weapon that always smells faintly of brine, regardless of how far from the sea it travels.
- **Effect:** **Spend 1 Momentum** on a successful hit to force the target into an unopposed Prowess check vs. TN 8; on a failure, the target is shoved 10 ft (2 squares) and knocked Prone. Repeatable as often as your Bank can pay for it. (Reuses Havoc's and the Domain of Sea & Storms' existing push/shove language rather than inventing new physics.)

**Sigil-Bound Wand (Single-Charge)** — 40 sp for a stored Novice spell, scaling to Legendary for Master-tier | Rare–Legendary
A single-use wand pre-loaded with one specific spell by an Arcanist during downtime (treat the loading process as a Commission). This is the formal version of the "activate an alchemical wand looted off a dead Boss" scenario GM Tools already gestures at — any character can trigger it, not just casters.
- **Activation:** The activator makes that spell's normal Resolution roll (Arcana, opposed or unopposed per the spell's own entry), whether or not they possess the Arcane Awakening feat.
- **If the activator has Arcane Awakening:** only a Snake Eyes destroys the wand (it gains the Ruined condition). A standard Failure just fizzles — the charge remains for a later attempt.
- **If the activator does not have Arcane Awakening** (using invested Arcana skill points per the Non-Caster Usage of Faith and Arcana rules in GM Tools): any Failure, not just Snake Eyes, destroys the wand. An untrained hand can't channel it precisely enough to survive a botch.
- *This item costs the activator no personal Stress win or lose — that's the whole point, it's what makes it safely usable by non-casters. The destruction risk on a failed roll is what stops it from being strictly better than casting the spell yourself.*

**Reliquary Symbol** (Holy Symbol upgrade) — ~150 sp | Legendary, Commission-gated | 1 Locked Stress Attunement
A Holy Symbol whose Domain-blessing has visibly deepened — filigree that was plain now catches light that isn't there.
- **Effect:** +1 to all Tithe of Will rolls. *(The Faith-side equivalent of the Vitrified Wand's `Focus` tag, translated into Faith's own currency: pushing more rolls over the TN 8 line means fewer Fails, which means less Encroachment, rather than a flat combat bonus Faith's math doesn't otherwise have a slot for.)*
- **The trade, stated plainly:** this is the sharpest attunement cost in the book, because of who wears it. A Priest's whole economy is paid in Locked Stress, so they sit closer to their Stress ceiling than any other class — and per Iron Core's Golden Rules that attuned box is **permanent and unreachable by any means while the Symbol is worn**. The +1 that makes your Tithes succeed more often also permanently shrinks the track those Tithes fill. A Priest at Stress Limit 9 runs at 8 for as long as they wear it.

**Vitrified Wand** (Wand upgrade) — ~150 sp | Legendary, Commission-gated | 1 Locked Stress Attunement
A plain wand whose grain has gone glassy and still, as though it has stopped flinching.
- **Effect:** Grants the **Focus** tag — +1 to Arcana Clash rolls; on a fumbled casting check the backlash destroys the item (Ruined), and the caster fails but takes no Stress for the fumble. *(The Arcane-side counterpart to the Reliquary Symbol, priced and gated identically because it is the same effect in Arcana's currency. +1 is worth roughly 11 points of Clash win rate and 10 points of Clean rate, so on a caster whose own spells tax them on a non-Clean result it buys durability as much as accuracy.)*

**Whisper-Kissed Leathers** — ~150 sp | Legendary, Commission-gated | 1 Locked Stress Attunement  
Requires a Light armour base (Padded or Leather).

- **Effect:** When declared the target of an Aggressor action, **spend 1 Momentum** to become **Obscured** (per Iron World's Cover rules) for that single Clash — the attacker suffers Disadvantage, as if striking through smoke, even in the open. Repeatable as often as your Bank can pay for it.
- _Reuses the existing Obscured mechanic rather than inventing a new defensive stat — same logic as Cloak of Still Water reusing Rushed Stealth._

#### Relic (1 Locked Stress Attunement + Built-In Drawback)

**The Widow's Needle** (unique dagger) — Not for sale. GM-authored, campaign-specific.
A slim, black dagger that is always slightly warmer than the air around it.
- **Effect:** Functions as a permanent, always-on Vital Strike (ignores Armour value in the Wound Threshold calculation) with no -4 penalty required to use it.
- **The Cost:** Every kill made with the Needle locks 1 additional point of Stress on the wielder that **cannot** be cleared by the Reprieve, Momentum spend, or a Breather — only a full Religious Pursuit or a Long Rest will do. The blade is hungry, and it remembers who fed it.

**The Brand of Gehenna's Grip** (unique manacle) — Not for sale. Found only as loot from Arch-Devil Malaphar.
A blackened iron cuff, still faintly warm no matter how long it's been off the wrist.
- **Effect:** Once per Scene, the wielder may spend 1 Momentum to force a target within Reach into an unopposed Resolve check vs. TN 8; failure inflicts 2 Dissonant Stress as infernal heat sears inward.
- **The Cost:** Each activation locks 1 Stress on the wielder that **cannot** be cleared by Momentum spend or a Breather — only a full Religious Pursuit or a Long Rest will do. The Brand remembers whose hand last closed a shackle, and it isn't particular about whose.

**Halgrim's Grave-Crown** (unique circlet) — Not for sale. **GM-placed Relic**, per the tier above: it enters play where the GM puts it and is never bought. Its namesake has a stat block in the Bestiary (Halgrim the Unburied, Dread/Boss), which is the obvious place to hang it, but the Crown does not depend on that encounter being run.
A dull iron circlet, cold to the touch even beside a fire.
- **Effect:** Once per Scene, the wearer may treat a single failed Resolve check of their own as passed instead — the crown remembers command, even from a skull that no longer needs a body to give orders.
- **The Cost:** While worn, the wearer personally treats all light one Illumination band darker than it actually is (Iron World) — Well Lit reads as Dimly Lit, Dimly Lit reads as Pitch Black, for that wearer alone. A dead king's court is always dim, and so is anyone who wears his crown.

---

## Currency Standard:
The primary day-to-day trade currency is the Silver Piece (sp). Copper Pennies (cp) are used by peasants (10 cp = 1 sp). Gold Sovereigns (gs) are held only by nobility and wealthy cartels (1 gs = 20 sp).

---

## Weapons

### Unarmed

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Unarmed (fists/feet/knees and elbows)|0|1H/2H|5 ft Threat|Non-lethal, Sidearm|—|Always available|
|Gauntlet|0|1H|5 ft Threat|Sidearm|2 sp|Common|
|Spiked Gauntlet|0|1H|5 ft Threat|Sidearm, Precise|5 sp|Common|

### Blades

| Weapon Name     | Power       | Grip  | Range / Threat             | Tags & Attributes                                     | Cost  | Availability |
| --------------- | ----------- | ----- | -------------------------- | ----------------------------------------------------- | ----- | ------------ |
| Dagger / Knife  | 0           | 1H    | 5 ft Threat / 30 ft Thrown | Concealable, Close-Quarters, Finesse, Thrown, Sidearm | 5 sp  | Common       |
| Punching Dagger | 0           | 1H    | 5 ft Threat                | Concealable, Close-Quarters, Inertia                  | 6 sp  | Common       |
| Kukri           | 0           | 1H    | 5 ft Threat                | Precise, Concealable                                  | 10 sp | Common       |
| Sai             | 0           | 1H    | 5 ft Threat                | Disarm, Concealable                                   | 5 sp  | Scarce       |
| Shortsword      | 2           | 1H    | 5 ft Threat                | Sidearm, Finesse                                      | 10 sp | Common       |
| Rapier          | 2           | 1H    | 5 ft Threat                | Precise, Finesse                                      | 20 sp | Scarce       |
| Longsword       | 3 (4 if 2H) | 1H/2H | 5 ft Threat                | Versatile                                             | 25 sp | Scarce       |
| Bastard Sword   | 3 (4 if 2H) | 1H/2H | 5 ft Threat                | Versatile, Precise                                    | 35 sp | Scarce       |
| Greatsword      | 5           | 2H    | 5 ft Threat                | Inertia, Cumbersome                                   | 45 sp | Scarce       |

### Axes

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Sickle|0|1H|5 ft Threat|Trip|6 sp|Common|
|Hand Axe|2|1H|5 ft Threat / 30 ft Thrown|Brutal, Thrown, Sidearm|8 sp|Common|
|Battleaxe|2|1H|5 ft Threat|Brutal, Inertia|12 sp|Common|
|Light Pick|2|1H|5 ft Threat|Inertia, Precise|13 sp|Common|
|Heavy Pick|3|1H|5 ft Threat|Inertia, Precise|26 sp|Scarce|
|Greataxe|5|2H|5 ft Threat|Heavy Hitter, Cumbersome|40 sp|Scarce|

### Bludgeons

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Club|0|1H|5 ft Threat|Bash|— (improvised, always available)|Common|
|Sap|2|1H|5 ft Threat|non-Lethal, Concealable|3 sp|Common|
|Mace / Bludgeon|2|1H|5 ft Threat|Bash|8 sp|Common|
|Morningstar|2|1H|5 ft Threat|Bash, Precise|12 sp|Common|
|Quarterstaff|2/2|2H|5 ft Threat|Double, Close-Quarters|3 sp|Common|
|Warhammer|3|2H|5 ft Threat|Bash, Sunder|30 sp|Scarce|

### Polearms

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Javelin|2|1H|5 ft Threat / 30 ft Thrown|Thrown|5 sp|Common|
|Spear|2|1H/2H|10 ft Threat / 60 ft Thrown|Reach, Thrown|10 sp|Common|
|Longspear|2|2H|10 ft Threat|Reach, Set, Cumbersome|12 sp|Common|
|Trident|2|1H|10 ft Threat / 10 ft Thrown|Reach, Thrown|15 sp|Scarce|
|Glaive|3|2H|10 ft Threat|Reach, Inertia|20 sp|Scarce|
|Lance|3|2H|10 ft Threat|Reach, Set, Inertia|20 sp|Scarce|
|Scythe|3|2H|5 ft Threat|Trip, Inertia|18 sp|Scarce|
|Halberd / Poleaxe|5|2H|10 ft Threat|Reach, Cumbersome|45 sp|Scarce|

### Flails

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Whip|0|1H|10 ft Threat|Reach, Disarm, Trip, non-Lethal|5 sp|Scarce|
|Nunchaku|0|1H|5 ft Threat|Disarm, Concealable, Bash|6 sp|Scarce|
|Flail|2|1H|5 ft Threat|Disarm, Trip|16 sp|Scarce|
|Spiked Chain|2|2H|10 ft Threat|Reach, Disarm, Trip, finesse|25 sp|Scarce|
|Heavy Flail|3|2H|5 ft Threat|Disarm, Trip, Precise|35 sp|Scarce|

### Thrown

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Dart|0|1H|5 ft Threat / 20 ft Thrown|Thrown, Concealable|1 sp (cluster of 3 = 1 Slot)|Common|
|Sling|0|1H|Ranged (Max: Medium / 50 ft)|Sidearm|2 sp|Common|
|Shuriken|0|1H|5 ft Threat / 10 ft Thrown|Thrown, Concealable, Sidearm|8 sp (cluster of 3 = 1 Slot)|Scarce|
|Bolas|0|1H|5 ft Threat / 10 ft Thrown|Thrown, Trip|5 sp|Scarce|
|Net|—|1H|5 ft Threat / 10 ft Thrown|Entangling|20 sp|Scarce|

### Bows

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Blowgun|0|2H|Ranged (Max: Short / 20 ft)|Concealable|5 sp|Common|
|Shortbow|2|2H|Ranged (Max: Long / 120 ft)|Volley|15 sp|Common|
|Longbow|3|2H|Ranged (Max: Extreme / 125+ ft)|Volley|35 sp|Scarce|

### Crossbows

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Hand Crossbow|0|1H|Ranged (Max: Short / 30 ft)|Concealable, Sidearm, Reload|40 sp|Rare|
|Light Crossbow|3|2H|Ranged (Max: Long / 120 ft)|Armour Piercing, Reload|30 sp|Scarce|
|Repeating Heavy Crossbow|3|2H|Ranged (Max: Long / 120 ft)|Volley, Armour-Piercing, Repeating|90 sp|Rare|

### Arcane Focus

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Grimoire|—|1H|—|Repository: holds every spell you know. Must be wielded in one hand, with your other hand free, to cast without penalty — see The Casting Requirements (Embracing the Abyss).|15 sp|Scarce|
|Mage Staff|—|2H|—|Reach, Bound, Conduit, Grounding Rod.|45 sp|Rare|
|Wand|—|1H|—|Conduit, Sidearm.|10 sp|Common|

*The Arcane focus ladder runs Grimoire → Wand → Mage Staff → **Vitrified Wand** (Enchanted, above), mirroring the Faith side's Holy Symbol → Holy Symbol, Silver → Reliquary Symbol. The **Grimoire is not optional** — it is the Repository, and no other focus holds your spells (see The Casting Requirements, Embracing the Abyss). Everything above it buys freedom from *holding* it, or Reach, or a bonus. A flat bonus to Arcana Clash rolls exists only at the Enchanted tier, at parity with the Reliquary Symbol's +1 to the Tithe of Will.*

> [!note] Designer's Note
> **Pricing a new weapon.** These are the bands the melee list settles around. **Base cost, two-handed, one tag:** Power 0 ≈ 4 sp · Power 2 ≈ 8 sp · Power 3 ≈ 18 sp · Power 5 ≈ 40 sp. **Add roughly 4 sp per tag beyond the first.** **Add roughly 50% for one-handed at Power 2 or above** — a free hand is a shield, and Shield Value subtracts from Impact *before* it reaches the Wound Threshold, so one-handedness is worth real coin. Power 0 is exempt: those are tools and sidearms, and the `Sidearm` and Twin-Blade rules already govern them. Deviations are fine where a tag runs unusually strong or weak for its tier, but they should be deliberate rather than accidental.

### Weapon Tags

- **Bound:** enables an Arcane caster to cast spells without needing their Grimoire in hand. but it must be on their person. Cast as if the Grimoire is held in one hand.
- **Bash:** If your attack results in a Glancing Hit (Impact < Threshold), it deals +1 additional Dissonant Stress due to blunt force trauma.
- **Black Powder:** A muzzle-loaded firearm or powder charge. Carries every clause below. *(Thrown or placed charges — Powder Grenade, Petard — use only the Powder Die, Snake Eyes, Report, and Soaking clauses.)*
	- *Loads:* Each shot spends 1 load (2 for a Scatter weapon) from a Powder Flask carried on the Belt. Loads are tracked individually and are **not** covered by the Community Supply Die.
	- *The Powder Die:* Roll one of your 2d6 in a distinct colour. If it shows a natural 1, the weapon **Misfires**: the Clash resolves as a Tie and the load is spent. While **Damp** (rain, sea spray, drifting fog) it Misfires on a 1 or 2. Rerolls that can change that die (e.g. Balanced Quality) resolve before the Misfire is checked.
	- *Snake Eyes:* The barrel bursts — the weapon gains the **Damaged** tag, on top of the normal Snake Eyes consequences.
	- *Report:* The first Black Powder discharge in a scene, by anyone, reveals a shooter hidden by Stealth. Any later encounter at the same site starts one band higher on **Starting Momentum** (Tools for the Nameless) — the whole place heard it. *(The shot itself grants no Momentum to anyone: it is an alarm, not an economy.)*
	- *Reloading:* **Heavy Reload**, and cannot be done while Engaged. A firearm may be carried loaded, and enters a fight ready to fire.
	- *In melee:* Counts as a Club (Power 0, Bash). A firearm's listed Power applies only to Shoot — never to Parry, Off-Hand Parry, or Twin Strike.
	- *Soaking:* If the carrier gains **Drowned** or is submerged, every load they carry and any loaded firearm is spoiled, unless held in an Oilskin Powder Flask.
- **Brutal:** Each natural 4 showing on the wielder's 2d6 in a Clash adds +1 to the Impact this weapon generates (so double 4s add +2). This applies to any Impact the weapon produces — a Strike, a Shoot, or a Riposte — and therefore only on a Clash it wins, since a loss generates no Impact to add to. *(Brutal also remains one of the three tags that bypass the Massive trait's Impact-halving — see the Bestiary.)*
- **Close-Quarters:** suffers no penalties when In-Fighting.
- **Concealable:** Grants Advantage (3d6 keep 2) on rolls made to hide the weapon on your person.
- **Conduit:** can be used to perform Somatic components. The caster weaves the geometry of the spell using the item itself, meaning their hand does not need to be empty.
- **Cumbersome:** The weapon is heavy and slow to ready. Imposes a -1 penalty to your Activation Order.
- **Devastating:** A mark of exceptional make — masterwork craft, ancient forging, or magic worked directly into the item — assigned to a specific weapon rather than a weapon category (sole exception: the **Petard**, whose charge carries it inherently — see Alchemical Wares). Enables the weapon to inflict Wounds directly on Scale +3 (Gargantuan) creatures (without it, Strikes against Gargantuan creatures only ever inflict Stress, per the Scale rules in Metal meet Flesh). When targeting a Scale +3 or higher creature, this weapon also ignores that creature's Scale-based Wound Threshold bonus when calculating whether a Strike inflicts a Wound — otherwise a weapon capping out at Power 5 could almost never generate enough Impact to matter against a Gargantuan-scale Wound Threshold. Carries no inherent size, Power, or hands requirement, and grants no bonus against fortifications — a Devastating dagger and a Devastating greatmaul are equally valid. The tag describes what the weapon *is*, not how big it is.
- **Finesse:** When making or defending a Clash with this weapon, you may reroll one die that landed on a natural 1. The new result stands, even if it is another 1. If *both* dice landed on 1, that is Snake Eyes and cannot be rerolled — no amount of technique saves a catastrophe. A rerolled 6 triggers Desperate Edge normally.
- **Focus:** Grants +1 to Arcana Clash rolls. If the caster rolls a fumble on a casting check the magic backlash destroys the item, it gains the ruined condition. The caster fails but does not suffer the 1 stress for a fumble.
- **Grounding Rod:** grants Advantage on Arcane **Sustain** checks. The staff carries the working's excess charge so the caster's mind doesn't have to.
- **Heavy Hitter:** When wielding these weapons, the character does not benefit from "fates bounty". Instead, any natural 6 is treated as a 7. **This substitution replaces every benefit a natural 6 would otherwise grant, including Desperate Edge's exploding die** — a 6 read as a 7 is no longer a 6, so it cannot also explode. The trade is a small certain bonus on roughly one roll in three (30.6% of 2d6 show at least one 6) in place of a rare large one.
- **Heavy Reload:** After firing, reloading consumes the wielder's entire Activation — no movement, no Action, no Free Action. (The Heavy Arbalest's windlass; a muzzle-loader's ramrod.)
- **Inertia:** If you win the Clash roll by a Margin of 5+, add +2 Power to the Final Impact.
- **non-Lethal:** strikes with this weapon can only cause Stress regardless of the Impact result, and will never spill over into Wounds. Against a target whose Stress Limit is already full, the blow inflicts no Stress either — it renders them **Unconscious** instead (Iron Core). A `non-Lethal` weapon cannot inflict a Wound, land a Coup de Grâce, or kill, at any Impact.
- **Precise:** Ignores 1 Point of armour
- **Reach:** Threatens a 10-foot radius (2 grid squares). Forces an opponent with shorter 5-foot weapons to succeed on an opposed Dodge roll to move into their reach. failure stops them at the 10-foot radius.
- **Reload:** After firing, requires an Action to load the next shot.
- **Scatter:** Strikes every creature in the weapon's area — a 15 ft cone from the wielder unless the item says otherwise — ally or enemy alike. Make one attack roll; each creature in the area makes its own Reactor roll against it, and Impact is resolved per creature. No Disadvantage at Point-Blank, and the Firing Into Combat rule (Iron World) doesn't apply — allies in the area are simply targets. Counts as an area attack for Swarm and Amorphous. Inertia never applies to a Scatter attack.
- **Sidearm:** A weapon short and light enough to be brought to bear in a heartbeat, or in a doorway. One property with three consequences: **(1)** it can be **drawn as a Free Action** without penalty; **(2)** it ignores the Disadvantage the **Point-Blank** band imposes (Metal meet Flesh — Ranges); **(3)** it is the qualifying off-hand weapon for the **Twin-Blade Stance**, granting Clash Advantage and Off-Hand Parry (Metal meet Flesh). An **Arcane Focus** carrying this tag gains (1) and (2) — a caster can channel through it nose-to-nose — but never (3): a Focus has no Power to lend an Off-Hand Parry.
- **Siege:** Emplaced, crew-served, or vehicle-mounted armament — a ballista, wall gun, cannon, or siege engine — rather than a personal weapon; it isn't carried in Inventory Slots. Like Devastating, it enables inflicting Wounds directly on Scale +3 (Gargantuan) creatures and ignores that creature's Scale-based Wound Threshold bonus when calculating whether a Strike inflicts a Wound; unlike Devastating, it can also damage fortifications and structures. Reducing the Wounds Threshold of fortifications by half when comparing Impact.
- **Sunder:** If you inflict a Minor or Major Wound with this weapon, permanently reduce the target's Armour value by 1. **This is a baseline reduction, not the Damaged Condition** — no amount of Hammer & Forge brings that point back (see *Condition is not the same as baseline*, above). Against an object, Sunder **ignores Structural Damage Reduction entirely** (see Structural Damage and Destruction, Iron Core) — it is the anti-material tag, and shredding worn armour is the same property pointed at something being worn.
- **Thrown:** Can be hurled using the short range attack band. If used in melee, it retains its 5 ft Threat.
- **Versatile:** can be wielded 1H or 2H. If wielded 2H add 1 to the weapon power.
- **Volley:** Requires two hands and prevents the user from holding a Shield or Grimoire.
- **Armour-Piercing:** Ignores 2 points of the target's Armour Value when calculating Impact — twice Precise's ignore-1.
- **Trip:** As an Aggressor Strike with this weapon, you may forgo Impact on a win to instead knock the target Prone.
- **Disarm:** As an Aggressor Strike with this weapon, you may forgo Impact on a win to force the target to pass a Prowess check vs TN 8 or drop what they're holding into an adjacent square.
- **Set:** If this weapon is readied and an enemy voluntarily moves into your Threat Zone, your Strike against them gains a Charge's +2 Clash bonus and tie-break — without the -2 Reactor penalty a real Charge imposes on you.
- **Double:** This two-handed weapon has two striking ends, each with its own Power (listed X/Y). It functions as a built-in Twin-Blade Stance: spend 1 Momentum on a won Clash to immediately follow up with the second Power value as Impact + 1 Stress, without needing a separate Sidearm weapon in your off hand.
- **Repeating:** Holds multiple shots internally; does not require the Reload action between individual shots. Once the magazine is empty, reloading it fully requires a full Action.
- **Entangling:** As an Aggressor action, forgo Impact on a win to instead apply the Anchored condition to the target (identical to the Entangle spell's effect).
(Note on Ranged Weapons: firing a Ranged or Thrown weapon while an enemy is inside your 5-foot Threat Zone imposes Disadvantage on the attack roll. Exception: a **Sidearm** or **Scatter** weapon fired *at* an enemy inside that Threat Zone — Point-Blank, per the Ranges table in Metal meet Flesh — takes no Disadvantage.)

###  ADVANCED SPECIALIZED WEAPONRY

These variations add specific situational tactical tools to the baseline weapon tables.

##### The Estoc (Tuck)

- Cost: 45 sp | Availability: Scarce
- Stats: Power 2 | 1H | 5 ft Threat
- Tags: Precise, Armour-Piercing
- 2d6 Special Rule: Designed specifically to pass between armour plates. When a natural 3 and 4 are rolled on the Attack roll, this weapon completely ignores all physical Armour values and structural damage reduction, applying its full Impact raw to the Wound Threshold.

##### The Barbed Spear

- Cost: 25 sp | Availability: Common
- Stats: Power 2 | 1H/2H | 10 ft Threat
- Tags: Reach.
- 2d6 Special Rule: When you win a Clash with this weapon as an attack action, you can forego doing standard Impact damage to execute a Hook. The target is pinned at the tip of your spear; they cannot execute Shift actions until they win an opposed Prowess check against you on their activation.

##### The Heavy Arbalest

- Cost: 80 sp | Availability: Rare
- Stats: Power 5 | 2H | Ranged (Max: Long / 120 ft)
- Tags: Armour-Piercing, Cumbersome, Heavy Reload
- 2d6 Special Rule: Requiring a literal windlass to crank. It takes two entire Move Actions to reload this weapon. However, its steel-headed bolts ignore the infantry projectile protections of shields (Cover tags are nullified) and deal +2 Impact against targets with Scale +1 or higher.

### Black Powder

Firearms are new, exotic, and ruinously expensive. Nobody sells one off a shelf — each is made to order by a master gunsmith (Commission, Soothing the Soul, Capital tier only), and priced in the nobility's coin. Their job is not to out-damage a crossbow over a fight; it is the single devastating opening shot, after which you draw steel. See the **Black Powder** tag for how they fire, misfire, reload, and announce themselves.

| Weapon Name | Power | Grip | Range / Threat | Tags & Attributes | Cost | Availability |
|---|---|---|---|---|---|---|
| Pistol | 4 | 1H | Ranged (Max: Short / 30 ft) | Black Powder, Sidearm, Armour-Piercing, Inertia | 300 sp (15 gs) | Legendary, Commission-gated |
| Blunderbuss | 3 | 2H | Ranged (Max: Short / 30 ft) | Black Powder, Scatter, Cumbersome | 400 sp (20 gs) | Legendary, Commission-gated |

| Item | Slots | Cost | Availability | Notes |
|---|---|---|---|---|
| Powder Flask & Shot | 1 | 60 sp (full) | Rare | Holds 6 loads. Refilled at 10 sp per load (Acquisition). Must be on the Belt to reload in combat. |
| Oilskin Powder Flask | 1 | 75 sp (full) | Rare | As above, but its loads survive Soaking. |

- **A brace of pistols:** Sidearm lets each be drawn as a Free Action, but three pistols fill all three Belt slots — leaving no room for the flask. Three shots, then steel.
- **Firearms in enemy hands** default to **Shoddy** Quality: half price, prone to breaking on any failure, and worth half as much when looted and sold.
- **Fire sources:** a firearm's ball is not a Fire source for effects such as Troll-Blood Regeneration. A Powder Grenade or Petard is.

#### Siege Ordnance (Cannon)

Emplaced on fortifications or mounted on ships. Carries **Siege**, never occupies Inventory Slots, and is never bought through Acquisition. A cannon's powder comes from the ship's or fortress's stores, not a PC's flask.

| Ordnance | Power | Crew | Range | Tags & Attributes |
|---|---|---|---|---|
| Ship's Gun | 8 | 3 | Extreme | Siege, Armour-Piercing, Black Powder. May fire **Grapeshot** instead: Power 5, Scatter (30 ft cone). |
| Fortress Gun | 10 | 4 | Extreme | Siege, Armour-Piercing, Black Powder |

- **Firing:** the gunner makes the Shoot roll (2d6 + Ranged).
- **Reloading:** takes 3 crew-Activations in total; any crew member may spend their whole Activation to contribute one.
- **Guns firing on the party:** when the gun crew is off-scene, resolve each shot as a Hazard Roll (2d6 + the gun's Power, Iron World). Aware targets defend normally.

---

## Armour

|Armour / Shield Name|Value|Type|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|
|Padded / Gambeson|+0 Armour|Light|Cushioned|5 sp|Common|
|Leather|+1 Armour|Light|—|12 sp|Common|
|Chain Shirt|+2 Armour|Light|—|50 sp|Scarce|
|Chainmail / Scale|+2 Armour|Medium|Bulky|45 sp|Scarce|
|Breastplate|+3 Armour|Medium|Bulky|120 sp|Rare|
|Plate Armour|+4 Armour|Heavy|Restricted|200 sp (10 gs)|Rare|
|Buckler|2 SV|Shield|Nimble|8 sp|Common|
|Kite / Round Shield|4 SV|Shield|Cover|18 sp|Common|
|Tower Shield|5 SV|Shield|Bulwark, Obstructive|40 sp|Scarce|

> **Chain Shirt or Chainmail?** Both grant +2 Armour, and the Shirt is 5 sp dearer for avoiding `Bulky`. But Chainmail is **Medium**, and the reinforced pauldrons below require a Medium or Heavy base for their flat **+1 Wound Threshold** — which the Light Chain Shirt can never take. The Shirt is the quieter, more agile suit; Chainmail is the cheaper route to +3 effective armour, paid for with −1 Athletics, Stealth and Arcana and −1 Activation Order. **Neither dominates the other.**

> **Availability at character creation.** A starting character outfits from a Town — Scarce tier or lower (see *The Starting Purse*, The Marrow, and Settlement Tiers, Soothing the Soul). Breastplate and Plate Armour are Rare, sourced from a City or better, and are not available at Green at any price. They are acquired in play.

### Armour and Shield Tags

- *Bulky:* The weight and noise of the armour make it hard to move gracefully. Imposes a -1 penalty on Athletics and Stealth and Arcana rolls.
- *Bulwark:* The shield's mass lets you root yourself in place. While readied, you cannot be Shoved, knocked Prone, or forced out of your Threat Zone as a result of losing a Clash. Once per Scene, when you lose a Block Clash, you may spend 1 Momentum to reduce that Impact to 0 instead of applying your Shield Value.
- *Cover:* Provides excellent physical obstruction from missiles. Grants Advantage (3d6 Keep 2) to your defense rolls against ranged attacks.
- *Cushioned:* Thick layers of cloth absorb minor impacts. Negates the first point of Dissonant Stress you would take from a Glancing Hit each combat round.
- *Nimble:* Light enough to be actively punched out or used to deflect. When performing a Block action with this shield equipped, roll 2d6 + Melee instead of 2d6 + Block.
- *Obstructive:* The sheer size of this shield gets in the way of evasive footwork. Imposes a -2 penalty to all Dodge actions.
- *Restricted:* The heavy plates and limited visibility slow your reaction time. Your Activation Order is reduced by 3, and you can never act first in a round regardless of your total. Impossible to recreate the intricate movements required in Arcane spell casting, cannot cast Arcane spells whilst wearing. Reduces movement speed by 10ft.

 **CRITICAL UTILITY ARMOR MODIFICATIONS**

Instead of just buying entirely new suits of plate, characters in a low-fantasy setting weld, rivet, and bolt additions to their existing kit.

_Reinforced Riveted Pauldrons (Armour Add-on)_

- Cost: 20 sp | Availability: Common
- Rules: Requires a suit of Medium or Heavy armour to attach. Adds a flat +1 to your Wound Threshold (WT). However, the added shoulder bulk restricts head movement; you suffer a permanent -1 penalty to your activation order rolls.

_Visored Great-Helm (Headpiece Modification)_

- Cost: 35 sp | Availability: Scarce
- Rules: When an enemy achieves an Ace (exploding 6) or a Critical success against you, you can choose to have the helm take the structural brunt. The attack does standard damage instead of critical/bonus damage, but the helm's visor is bent shut. For the remainder of the combat, your actions suffer Disadvantage due to near-total blindness until an action is spent tearing the helm off.

_Oil-Cured Gambeson (Under-layer Layering)_

- Cost: 15 sp | Availability: Common
- Rules: Can be worn under Chainmail or Scale armour. Grants the Cushioned tag (Negates the first point of Dissonant Stress you would take from a Glancing Hit each combat round).

_Armour Spikes (Armour Add-on)_

- Cost: 15 sp | Availability: Scarce
- Rules: When an enemy loses a Grab or Shove Clash against you, they suffer **1 Dissonant Stress** from the spikes.

_Locked Gauntlet (Armour Add-on)_

- Cost: 5 sp | Availability: Common
- Rules: Grants Advantage on Prowess checks made to resist being disarmed.

_Shield Spikes (Shield Add-on)_

- Cost: 8 sp | Availability: Common
- Rules: When you win a Shove action using this shield, deal +1 Impact on top of the standard result.

---

## Expedition Gear

| Item                                                | Slots    | Cost          | Availability | Notes                                                                                                                                                                                                      |
| --------------------------------------------------- | -------- | ------------- | ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Backpack                                            | 0 (worn) | 3 sp          | Common       | Exempted from Slots like worn armour — it's the frame the Pack lives in, not an item inside it, and grants no bonus capacity.                                                                               |
| Barrel (empty)                                      | 2        | 8 sp          | Common       | Bulky; rigid — costs its Slots even empty (see Section 0b).                                                                                                                                                |
| Basket (empty)                                      | 1        | 1 sp          | Common       | Rigid — costs its Slot even empty.                                                                                                                                                                         |
| Bedroll                                             | 1        | 2 sp          | Common       | —                                                                                                                                                                                                          |
| Bell                                                | 0        | 3 sp          | Common       | —                                                                                                                                                                                                          |
| Blanket, winter                                     | 1        | 3 sp          | Common       | —                                                                                                                                                                                                          |
| Block and tackle                                    | 1        | 12 sp         | Scarce       | Advantage on Athletics checks to lift/hoist loads beyond your own strength.                                                                                                                                |
| Bottle, glass                                       | 0        | 2 sp          | Common       | —                                                                                                                                                                                                          |
| Bucket (empty)                                      | 1        | 2 sp          | Common       | —                                                                                                                                                                                                          |
| Caltrops (bag)                                      | 0        | 4 sp          | Common       | Move Action to scatter across one square. First creature to enter it without noticing (failed Notice vs. your Margin) rolls Acrobatics vs TN 8 or takes 1 Stress and half Movement for the round. |
| Candle / Chalk / Firewood / Torch / Tindertwig      | 0        | ~1 cp each    | Common       | Flavor only — light and fuel are tracked by the Community Supply Die during a dungeon crawl. Price these individually only for town/travel bookkeeping. See Iron World's Illumination rules for light radius (20 ft Well Lit / 10 ft Dimly Lit).                                                    |
| Canvas (sq. yd.)                                    | 0        | 1 sp          | Common       | —                                                                                                                                                                                                          |
| Case, map or scroll                                 | 0        | 2 sp          | Common       | —                                                                                                                                                                                                          |
| Chain (10 ft.)                                      | 1        | 15 sp         | Scarce       | —                                                                                                                                                                                                          |
| Chest (empty)                                       | 2        | 5 sp          | Common       | Rigid — costs 2 Slots whether empty or full, and grants no bonus capacity of its own. Note: _Hardware_'s "small treasure chest" example is a found-loot abstraction, a different use case from this.       |
| Crowbar                                             | 1        | 3 sp          | Common       | Advantage on Athletics/Thievery checks to force a door, crate, or portcullis latch.                                                                                                                        |
| Fishhook / Fishing net                              | 0 / 1    | 1 sp / 4 sp   | Common       | —                                                                                                                                                                                                          |
| Flask (empty) / Vial                                | 0        | 3 cp / 1 sp   | Common       | Stacks per the existing "cluster of 3 potions = 1 Slot" rule.                                                                                                                                              |
| Flint and steel                                     | 0        | 2 sp          | Common       | —                                                                                                                                                                                                          |
| Grappling hook                                      | 1        | 3 sp          | Common       | Pairs with Rope, below.                                                                                                                                                                                    |
| Hammer                                              | 1        | 2 sp          | Common       | —                                                                                                                                                                                                          |
| Hourglass                                           | 1        | 20 sp         | Scarce       | —                                                                                                                                                                                                          |
| Ink, inkpen, paper, parchment, sealing wax          | 0        | 1–2 sp bundle | Common       | —                                                                                                                                                                                                          |
| Ladder, 10-foot                                     | 2        | 3 sp          | Common       | Bulky, awkward — doesn't fold into a pocket regardless of price.                                                                                                                                           |
| Lamp, common                                        | 0        | 2 sp          | Common       | Same radius as a torch (Iron World's Illumination rules: 20 ft Well Lit / 10 ft Dimly Lit). See Hooded Bullseye Lantern in _Hardware_ (12 sp, Scarce) for the tactical version.                                                                                                                        |
| Manacles                                            | 1        | 15 sp         | Scarce       | Escaping requires a Thievery or Athletics check at **Difficult (-2)** instead of Standard.                                                                                                                 |
| Manacles, masterwork                                | 1        | 45 sp         | Rare         | As above, at **Extreme (-4)**.                                                                                                                                                                             |
| Mirror, small steel                                 | 0        | 5 sp          | Common       | —                                                                                                                                                                                                          |
| Mug/Tankard, Pitcher, Pot                           | 0        | 2 cp – 3 sp   | Common       | —                                                                                                                                                                                                          |
| Oil (1-pint flask)                                  | 0        | 1 sp          | Common       | Fictional fuel for Naphtha Fire-Flasks and lanterns alike.                                                                                                                                                 |
| Pick, miner's / Shovel / Sledge                     | 1        | 2–3 sp        | Common       | —                                                                                                                                                                                                          |
| Pole, 10-foot                                       | 1        | 2 sp          | Common       | —                                                                                                                                                                                                          |
| Pouch, belt (empty)                                 | 0        | 1 sp          | Common       | —                                                                                                                                                                                                          |
| Ram, portable                                       | 2        | 10 sp         | Scarce       | Advantage on Athletics checks to break down a door.                                                                                                                                                        |
| Rations, trail                                      | 0        | 2 sp/day      | Common       | Tracked by the Community Supply Die inside a dungeon — don't double-track. Priced here only for overland travel montages and Downtime.                                                                     |
| Rope, hemp (50 ft.)                                 | 1        | 2 sp          | Common       | Direct match for the "coiled rope" example already in _Hardware_.                                                                                                                                          |
| Rope, silk (50 ft.)                                 | 1        | 15 sp         | Scarce       | As above; Advantage on Thievery checks using it (silent bindings, garrotes).                                                                                                                               |
| Sack (empty)                                        | 0        | 1 sp          | Common       | Soft/collapsible — 0 Slots until it's holding something with its own Slot cost.                                                                                                                            |
| Sewing needle / Signal whistle / Signet ring / Soap | 0        | 1–5 sp        | Common       | —                                                                                                                                                                                                          |
| Spyglass                                            | 1        | 30 sp         | Scarce       | Advantage on Notice checks made at Long or Extreme Range — requires both hands and a Full Action spent observing. **It also resolves detail the naked eye cannot get at any distance**: counting a patrol, reading a banner, recognising a face. No lens does that. |
| Tent                                                | 2        | 8 sp          | Common       | —                                                                                                                                                                                                          |
| Water clock                                         | —        | —             | Legendary    | A city fixture, not a carried item. Not normally purchasable by PCs.                                                                                                                                       |
| Waterskin                                           | 0        | 1 sp          | Common       | —                                                                                                                                                                                                          |
| Whetstone                                           | 0        | 1 sp          | Common       | Mundane, feat-free version of the Spit and Twine feat's Patch Job: as a Regroup action, roll Crafting vs TN 8 to ignore the Damaged tag on one weapon for the rest of the encounter.                       |

**TACTICAL EXPEDITION GEAR**

Practical kits that anchor survival and optimize downtime actions.

_Iron Pitons & Sledge (Set of 6)_

- Cost: 5 sp | Availability: Common
- Tactical Rule: During a movement or preparation phase, a player can spend an action to spike a heavy iron door or narrow passageway shut. Enemies attempting to bypass this square or break the door must spend a Full Action and pass a Prowess check vs TN 8 to smash the piton out, buying the party vital tactical rounds.

_Field Surgeon Kit_

- Cost: 50 sp | Availability: Rare
- Downtime Rule: Possessing this kit grants a flat +2 bonus to all "Tend to the Flesh" downtime checks. It contains fine bone saws, clean linen sheets, and non-rancid cauterizing irons. Contains enough specialized thread for 6 uses before requiring an acquisition roll to restock.

_Hooded Bullseye Lantern_

- Cost: 12 sp | Availability: Scarce
- Tactical Rule: Illuminates a Well Lit 30-foot cone directly ahead (per Iron World's Illumination rules) and nothing beyond it — hooded and directional, it throws no Dimly Lit spill of its own. Everywhere outside the cone stays whatever it would be without the lantern. If a hidden creature is caught directly in the beam during a Draw (Initiative phase), it loses the benefit of its Obscured/Heavily Obscured position for that Draw — the focused beam finds it before it can react.

_Holy Symbol_

- **Cost:** 5 sp | **Availability:** Common
- **Rules:** Required to manifest Prayers — per _The Marrow_'s Divine Conduit feat, a Priest must "speak the litany and bear your symbol" to cast. A Symbol bound to a Domain via the Covenant path can never hold a different entity's Prayers (no later switching, per Divine Conduit). 0 Slots — worn/carried, per the Inventory micro-item exemption.

_Holy Symbol, Silver_

- **Cost:** 15 sp | **Availability:** Scarce
- **Rules:** A cosmetic/prestige upgrade over the standard Holy Symbol above — **no mechanical bonus.**

---

### ALCHEMICAL WARES & FIELD CONSUMABLES

Alchemical supplies are highly volatile, unstable, and often act as a mechanical double-edged sword.

> **None of the preparations below can touch Attunement Locked Stress.** Where an entry says it clears, unlocks or converts Locked Stress, read that as *clearable* Locked Stress only — a Priest's resolved or Flowing Tithe, an Arcanist's Overcharge, a condition, or environmental exposure. A box locked to an attuned item is not available to any of them (Iron Core, Golden Rules).

| Item Name            | Cost  | Avail.  | Slots | Mechanical 2d6 & Resource Output                                                                                                                                                                                                                                                                        |
| -------------------- | ----- | ------- | ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Grave-Dust Poultice  | 8 sp  | Common  | 1/3   | Field Medicine: Used as a Full Action. Instantly clears 1 filled Wound slot. However, due to the filth of the compounds, the target must roll an Athletics check vs TN 8. On a failure, they take 1 point of Dissonant Stress from spreading infection.                                                 |
| Black-Root Draught   | 15 sp | Scarce  | 1/3   | Exhaustion: Used as a Move Action. Instantly unlocks 2 Dissonant Stress slots for an Arcane caster. However, it drains physical stamina; at the absolute end of the current scene, the character automatically fills 1 physical Wound slot from systemic toxicity.                                      |
| Witch-Spur Salve     | 12 sp | Scarce  | 1/3   | Nerve Numbing: Rubbed into the temples as a Move Action. Grants absolute immunity to the Terrifying trait and psychological panic checks for the next scene. The Catch: It instantly fills and locks 1 Dissonant Stress slot for the duration of the scene, reducing the user's maximum stress ceiling. |
| Vitriol Solvent      | 25 sp | Rare    | 1/3   | Armour Melt: Applied to a bladed or Armour-piercing weapon as a Full Action. For the next 3 combat rounds, the weapon gains the Sunder tag. If a strike hits a target with the Plated trait, that trait is suppressed for the rest of the encounter.                                                     |
| Naphtha Fire-Flask   | 30 sp | Rare    | 1/3   | Zone Control: Can be thrown (Ranged, Max 30ft). Shatters upon a square/zone. Anyone occupying or entering the zone during the next 3 rounds must pass a Dodge check vs TN 8 or take 2 Dissonant Stress from the chemical burns.                                                  |
| Arcane Salts         | 8sp   | common  | 1/3   | A violently harsh alchemical stimulant. Using it as a Move Action instantly unlocks 1 Locked Stress slot, but immediately inflicts 1 normal Dissonant Stress on the user from the chemical shock..                                                                                                      |
| Philter of Focus     | 20sp  | scarce  | 1/3   | The next Arcane **Sustain** check the drinker makes this scene automatically passes as a Clean result, no roll required.                                                                                                                                                                                |
| Corpse-Weed Resin    | 6 sp  | Common  | 1/3   | Lethargy: For the first combat encounter after the Breather, the user cannot generate Momentum, as their nervous system is too dulled. Clears 1 Locked Stress. Can be smoked during a 30-minute Breather.                                                                                               |
| Marrow-Glass Ampoule | 40 sp | Rare    | 1/3   | The Crash: At the end of the combat encounter, the user immediately suffers 1 Minor physical Wound from the violent chemical shock to their heart. Instant Override: Can be injected mid-combat as a Free Reaction. Converts all currently **clearable** Locked Stress back into standard Dissonant Stress. **Attunement Locked Stress is untouched.**           |
| Surgical Spirits     | 10 sp | Common  | 1/3   | Tremors: The user suffers Disadvantage on any Thievery or Arcana rolls requiring fine motor skills until they return to a town (long rest/pursuit) to fully detox — lasting, but not permanent in the sense Hardware's Condition rules use the word. Taken during a Breather. Numbness allows the user to clear 2 Locked Stress.                                               |
| Antitoxin (vial)     | 20 sp | Scarce  | 0     | Drunk as a Free Action before a Poison check. Grants Advantage on the next Athletics check made to resist the Poisoned condition this scene.                                                                                                                                                            |
| Everburning Torch    | 40 sp | Rare    | 0     | Permanent arcane light source and a Micro-Item — it never burns down and never occupies a Slot. Never consumes a Supply Die step. Well Lit 30 ft / Dimly Lit 15 ft beyond (Iron World's Illumination rules). |
| Sunrod               | 5 sp  | Scarce  | 1/3   | Arcane light source, never consumes a Supply Die step, but burns out at scene's end. Well Lit 30 ft / Dimly Lit 15 ft beyond (Iron World's Illumination rules) — the same light an Everburning Torch gives, bought one scene at a time. |
| Holy Water (flask)   | 15 sp | Scarce  | 0     | Thrown as a Ranged (Short) attack; only affects targets with the Undead or Void-Touched tag. On a hit, inflicts **1 Direct Wound** (GM Tools, *The Lethal Bypass*) — no Wound Threshold comparison at all. The Creature Type restriction is its gate.                                                                                                                                                                   |
| Smokestick           | 15 sp | Scarce  | 0     | Snapped as a Move Action. Creates a 5 ft. radius of Heavily Obscured terrain for 1 round (per the Environmental cover rules in _Iron World_).                                                                                                                                                           |
| Tanglefoot Bag       | 20 sp | Scarce  | 0     | Thrown (Short Range). On a hit, the target is Anchored until they spend a full Aggressor action tearing free — mechanically identical to the Entangle spell's Margin 1–2 result.                                                                                                                        |
| Thunderstone         | 20 sp | Scarce  | 0     | Thrown; explodes in a 10 ft. radius. Everyone caught rolls Resolve vs TN 8 or gains the Distracted condition (-1 to rolls until their next Activation).                                                                                                                                                 |
| Powder Grenade       | 40 sp | Rare    | 1/3   | Black Powder, Scatter (10 ft radius), Power 2. Lit and thrown (Short, 30 ft) as one Aggressor action: roll 2d6 + Ranged, and each creature in the radius defends. Powder Die 1: a dud fuse. Snake Eyes: it detonates on the thrower's own square instead. Counts as a Fire source.                   |
| Petard               | 80 sp | Rare    | 1     | Black Powder, Devastating, Armour-Piercing. A breaching charge — see *Petard*, below.                                                                                                                                                                                                                    |

_Petard_

- **Cost:** 80 sp | **Availability:** Rare | **Slots:** 1
- **Tags:** Black Powder, Devastating, Armour-Piercing. Counts as a Fire source.
- **Planting it on a structure** (door, gate, wall section): a Full Action and Crafting vs TN 8. On a failure the charge isn't seated; try again next Activation.
- **Planting it on a creature:** an Aggressor action — 2d6 + Athletics vs the creature's Reactor roll — while adjacent to it or clinging to it. On a win, the charge is fixed. On Snake Eyes, the fuse catches early and it detonates immediately. *(Getting onto a larger creature's back is a separate, GM-adjudicated Athletics feat.)*
- **The fuse:** it detonates at the start of the planter's next Activation. Whatever Movement you have left this Activation is how far you get. Leaping from a height is a Fall (Iron World).
- **Detonation:** the GM makes one Hazard Roll, 2d6 + 8.
	- The thing the charge is fixed to takes that total directly as Impact — no Reactor roll. Against a structure, halve its Wound Threshold, as Siege does. Against a creature, Devastating applies: on a Scale +3 target, ignore its Scale-based Wound Threshold bonus.
	- Every other creature within 10 ft — the planter included — defends against the same Hazard Roll as an Aware target, Dodge only.
	- If the Powder Die shows a 1, the fuse gutters and nothing happens. The charge stays fixed; relighting it takes an Action from an adjacent square.

### Tools & Skill Kits

| Item                           | Slots                                | Cost   | Availability     | Effect                                                                                                                                                                                                                                                                           |
| ------------------------------ | ------------------------------------ | ------ | ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Alchemist's Lab                | — (stationary facility, not carried) | 150 sp | Rare, City-tier+ | Required for the **Distil & Compound** Pursuit (Soothing the Soul) — making Alchemical Wares and Powder & Shot outside of desperate battlefield chemistry (the Scrounger's Volatile Concoction feat already covers the field-expedient version).                                                                        |
| Artisan's tools (per trade)    | 1                                    | 5 sp   | Common           | Required to attempt a Crafting check in that trade without Disadvantage.                                                                                                                                                                                                         |
| Artisan's tools, masterwork    | 1                                    | 20 sp  | Scarce           | +1 flat bonus to that trade's Crafting check (same logic as Masterwork Quality weapons/armour).                                                                                                                                                                                   |
| Climber's Kit                  | 1                                    | 25 sp  | Scarce           | Advantage on Athletics checks made specifically to climb.                                                                                                                                                                                                                        |
| Disguise Kit                   | 1                                    | 15 sp  | Scarce           | Grants Advantage on the unopposed Arcana-equivalent roll for a mundane disguise (resolved exactly like the Disguise spell's Illusion check — Notice vs. your Margin to see through it).                                                                                   |
| Healer's Kit                   | 1                                    | 15 sp  | Common           | Cheaper cousin of the Field Surgeon's Kit: +1 (not +2) to Tend to the Flesh checks, and holds only 2 uses before restocking.                                                                                                                                                     |
| Magnifying Glass               | 0                                    | 30 sp  | Scarce           | Advantage on Notice checks made on small or fine details (forgeries, tiny inscriptions).                                                                                                                                                                                         |
| Musical Instrument, common     | 1                                    | 5 sp   | Common           | Flavor.                                                                                                                                                                                                                                                                          |
| Musical Instrument, masterwork | 1                                    | 40 sp  | Scarce           | +1 flat bonus to an Influence check made while performing with it.                                                                                                                                                                                                               |
| Scale, merchant's              | 0                                    | 3 sp   | Common           | Advantage on Insight/Notice checks to catch a rigged deal or counterfeit coin.                                                                                                                                                                                                   |
| Spell Component Pouch          | —                                    | —      | —                | **Not needed.** Grimoire/Wand/Staff already fill the Arcane Focus role; a separate component pouch would be a redundant subsystem.                                                                                                                                               |
| Spellbook, wizard's (blank)    | —                                    | —      | —                | This is just an unfilled Grimoire (15 sp, Scarce, already in _Hardware_) — no separate item.                                                                                                                                                                                     |
| Thieves' Tools                 | 1                                    | 20 sp  | Scarce           | Required to attempt a Thievery check against locks/mechanisms without Disadvantage.                                                                                                                                                                                              |
| Thieves' Tools, masterwork     | 1                                    | 60 sp  | Rare             | As above, +1 flat bonus to the check.                                                                                                                                                                                                                                            |
| Holy Symbol, silver            | 0                                    | 15 sp  | Scarce           | Cosmetic/prestige upgrade over the standard Holy Symbol (5 sp) only — **no mechanical bonus.** Faith runs on the Tithe of Will, not item bonuses. |

### Clothing
All Clothing is worn (0 Slots). Prices are flavor-tier, but a few outfits earn a Situational Modifier hook consistent with how _Tools for the Nameless_ already handles court dress and cold-weather Hazard checks.

| Item                                      | Cost             | Availability | Notes                                                                                                                                                            |
| ----------------------------------------- | ---------------- | ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Peasant's outfit                          | 1 sp             | Common       | —                                                                                                                                                                |
| Traveler's / Artisan's outfit             | 3 sp             | Common       | —                                                                                                                                                                |
| Entertainer's / Monk's / Scholar's outfit | 5–8 sp           | Common       | —                                                                                                                                                                |
| Priest's vestments                        | 8 sp             | Common       | —                                                                                                                                                                |
| Cold-weather outfit                       | 10 sp            | Common       | Negates the Hazard Check penalty specifically for cold-based environmental hazards (per _Iron World_'s Hazard Roll rules).                                       |
| Explorer's outfit                         | 12 sp            | Common       | —                                                                                                                                                                |
| Courtier's outfit                         | 40 sp            | Scarce       | GM may apply a +2 Advantageous modifier on Influence checks in high-society settings where dress matters — and, symmetrically, a -2 for showing up underdressed. |
| Noble's outfit                            | 90 sp            | Rare         | As above.                                                                                                                                                        |
| Royal outfit                              | 250 sp (12.5 gs) | Legendary    | As above; also a strong narrative flag on its own.                                                                                                               |

### Food, Drink & Lodging
these prices are for **town scenes and Downtime bookkeeping** — buying a round, paying for a room, throwing a banquet. They are **not** for tracking dungeon rations; that's what the Community Supply Die already abstracts.

| Item                           | Cost                | Availability |
| ------------------------------ | ------------------- | ------------ |
| Ale, mug                       | 4 cp                | Common       |
| Ale, gallon                    | 4 sp                | Common       |
| Bread, loaf                    | 2 cp                | Common       |
| Cheese, hunk                   | 1 sp                | Common       |
| Meat, chunk                    | 2 sp                | Common       |
| Meal, poor / common / good     | 1 sp / 2 sp / 4 sp  | Common       |
| Inn stay, poor / common / good | 2 sp / 5 sp / 15 sp | Common       |
| Wine, common pitcher           | 2 sp                | Common       |
| Wine, fine bottle              | 35 sp               | Scarce       |
| Banquet (per person)           | 30 sp               | Scarce       |

### Mounts, Tack & Barding
_Combat-trained mounts don't panic from ordinary Fear-Inducing effects (they're bred/drilled for it) but are not immune to Terrifying-tier effects._

| Mount                       | Scale      | Move         | Wound Threshold  | Stress Limit | Cost           | Availability |
| --------------------------- | ---------- | ------------ | ---------------- | ------------ | -------------- | ------------ |
| Donkey / Mule               | Small (-1) | 20 ft (4 sq) | 3                | 3            | 12 sp          | Common       |
| Pony                        | Small (-1) | 25 ft (5 sq) | 3                | 3            | 20 sp          | Common       |
| Guard Dog                   | Small (-1) | 40 ft (8 sq) | 3                | 3            | 15 sp          | Common       |
| Riding Horse                | Large (+1) | 40 ft (8 sq) | 7                | 4            | 60 sp          | Scarce       |
| Heavy Horse (warhorse)      | Large (+1) | 35 ft (7 sq) | 9                | 4            | 150 sp         | Rare         |

**Combat training** — **+50% of the mount's base cost, and always Rare** (a horse-breaker is a city profession, whatever the animal). The mount gains **Battle-Broke** and loses **Skittish** (Bestiary): it no longer bolts, it can be fought from, it gains Melee +1 if it had none, and it shrugs off the first Fear each Scene. It gains **no Brawn, no Wound Threshold, no Stress Limit and no Move** — *a trained horse is a braver horse, not a bigger one.* A **Riding Horse, combat trained** is **90 sp, Rare**; a **Heavy Horse, combat trained** is **225 sp, Rare**.

*Both horses have full stat blocks in the Bestiary — Riding Horse (Fodder) and Heavy Horse (Grunt) — where the Wound Thresholds above derive from Brawn and Scale like any other creature's. The Small mounts are Brawn 0: 4 + 0 − 1 Scale = 3.*

**Tack:**
**Barding:** priced as **2× the base armour's sp cost**, reflecting the extra material a Large-scale mount requires. A barded mount carries the same tag penalties as a rider would (Bulky armour still imposes its usual -1 penalties). Example: Chainmail barding = 90 sp; Plate barding = 400 sp (20 gs), Rare/exotic, warhorse-only.

| Item               | Cost  | Availability | Notes                                                                                                                                                          |
| ------------------ | ----- | ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Bit and bridle     | 3 sp  | Common       | —                                                                                                                                                              |
| Riding saddle      | 8 sp  | Common       | —                                                                                                                                                              |
| Pack saddle        | 5 sp  | Common       | —                                                                                                                                                              |
| Military saddle    | 15 sp | Scarce       | Advantage on the Ride skill check to stay mounted when your mount is Shoved, spooked, or knocked.                                                              |
| Saddlebags         | 6 sp  | Common       | Grants 2 additional Pack-equivalent Slots that live on the mount rather than the rider — still requires a Regroup-equivalent action to dig through mid-combat. |
| Feed (per day)     | 3 cp  | Common       | —                                                                                                                                                              |
| Stabling (per day) | 1 sp  | Common       | —                                                                                                                                                              |

### Transport
Campaign-scale assets, not inventory items — no Slots apply. Anything ship-sized should be treated as Commission-gated per _Soothing the Soul_ (Capital/Metropolis settlement tier, GM narrative gatekeeping), not a walk-in purchase.

| Item             | Cost                        | Availability                |
| ---------------- | --------------------------- | --------------------------- |
| Rowboat          | 25 sp                       | Common                      |
| Cart             | 20 sp                       | Common                      |
| Sled             | 25 sp                       | Common                      |
| Wagon            | 45 sp                       | Scarce                      |
| Carriage         | 90 sp                       | Rare                        |
| Keelboat         | 300 sp (15 gs)              | Rare                        |
| Longship         | 1,500 sp (75 gs)            | Legendary, Commission-gated |
| Sailing Ship     | 2,000 sp (100 gs)           | Legendary, Commission-gated |
| Galley / Warship | 5,000–6,000 sp (250–300 gs) | Legendary, Commission-gated |

### Spellcasting, Prayers & Hired Services

| Service             | Cost      | Notes |
| ------------------- | --------- | ----- |
| Coach cab           | 3 cp/mile | —     |
| Messenger           | 2 cp/mile | —     |
| Road or gate toll   | 1 cp      | —     |
| Ship's passage      | 1 sp/mile | —     |
| Hireling, untrained | 5 cp/day  | —     |
| Hireling, trained   | 3 sp/day  | —     |

| Spell/Prayer Level | Price      |
| ------------------- | ---------- |
| Cantrip             | 15 sp      |
| Novice              | 30 sp      |
| Adept               | 60 sp      |
| Master              | 120–150 sp |

_Resurrection is explicitly excluded from this table — at 8 Locked Stress cost to the caster and a Master Prayer to begin with, it should never be a walk-up shop purchase. Treat it as Commission-gated, if available at all._

# Chapter 6 — Embracing the Abyss

*Magic*

To keep the two systems distinct, we should root them in entirely opposite philosophies: Arcana is about Volatility and Margins, while Faith is about Certainty and Sacrifice.

## "Spell" is the generic term

**Spell** covers both forms of magic. An Arcane working and a Faith **Prayer** are both spells, and any rule that says *spell* applies to both — unless the surrounding rule is explicitly scoped to one, as the Arcane **Sustain** rules and the Faith **Flowing** rules below are. Where a rule must name one side alone it says **Arcane spell** or **Prayer**.

**What this settles in play:** anything that wards against, resists, counters or detects *spells* works against hostile Prayers as readily as hostile Arcana. *Arcane Protection* is the worked example — an Arcane ward whose protection extends to divine magic.

## Casting Difficulty by Spell Level (Tiered TN)

Unopposed casting checks — the Margin of Manifestation roll, a Sustain check, and a Priest's Tithe of Will — do not target a flat TN 8. The Target Number is set by the spell or Prayer's own Level:

| Level | TN |
|---|---|
| Cantrip | 6 |
| Novice | 8 |
| Adept | 10 |
| Master | 12 |

This does not apply to Arcane Clash spells or any other opposed roll — both sides already scale together, so there's no static-TN problem to fix. It also does not apply to general skill checks outside of spellcasting; those remain governed by the GM Tools Situational Modifier system. A Sustain check always targets the TN of the specific spell being sustained.

## Arcana (The Volatile Margin)

Arcana is the act of forcefully rewriting reality. It is highly complex, mathematically devastating, and inherently unstable. It relies entirely on Margin mechanics.

**The Casting Requirements (The Book and the Hand)**

An Arcanist does not carry their spells in their head. They carry them in a book, and the working itself is a physical act. Casting an Arcane spell requires two things:

1. **The Grimoire wielded**, occupying one hand exactly as a 1H weapon does.
2. **The other hand free**, to trace the somatic geometry of the working.

Casting with either requirement unmet is **Blind Casting**: the check is made at **Disadvantage**, and the caster takes **1 Dissonant Stress per unmet requirement** — so 1 if the book is stowed *or* the hand is full, 2 if both. (Disadvantage does not stack per Iron Core, so the Stress is what makes losing both worse than losing one.)

If the Grimoire is not on the Arcanist's person at all — lost, stolen, Sundered, or left behind — they cannot cast at all, with the sole exception of spells committed permanently to memory (see the *Ingrained Arcana* feat).

Both requirements have hardware answers, and an Arcanist's loadout is a real build decision (see Hardware: Arcane Focuses):

| Loadout | Grimoire req. | Free hand | Result |
|---|---|---|---|
| Grimoire + empty hand | Met | Met | Clean. No weapon, no shield. |
| Grimoire + Wand (**Conduit**) | Met | Met | Clean. The Wand legally occupies the second hand where a weapon or shield would not. No shield. |
| Grimoire + Vitrified Wand (**Conduit**, **Focus**) | Met | Met | Clean, **+1** to the Clash. Enchanted — 1 Locked Stress. No shield. |
| Mage Staff (**Bound**, **Conduit**), book stowed | Met | Met | Clean, plus Reach and Sustain support. Both hands committed. |
| Book stowed, weapon and shield in hand | Unmet | Unmet | Disadvantage, 2 Dissonant Stress per cast. |

**Casting at Point-Blank.** An enemy inside your Threat Zone imposes **Disadvantage** on the cast, exactly as it does on a shot (Metal meet Flesh — Ranges), unless your Arcane Focus carries the **Sidearm** tag. A spell's listed range band is a cap rather than a minimum, so Point-Blank is always a legal distance to cast at — it is simply a bad one. This is Disadvantage from **position**; Blind Casting above is Disadvantage from **loadout**. Blind Casting's Dissonant Stress is still owed on its own account, but the Disadvantage from the two does not stack — Disadvantage never does (Iron Core).

**The Arcane Clash (Combat Spells)**

When an Arcanist casts an offensive spell that deals Impact, calculate it the same way a weapon does:
>
> **Impact = (Margin of the Clash, or Margin over the spell's own TN for an unopposed spell) + Spell Power**
>
> Each spell's entry lists a flat **Spell Power** rating, exactly like a weapon's Power. The Margin Scaler doesn't define the Impact number directly — it defines the *special effect* that comes with each tier (a condition, a debuff, a status).
>
> **Spell Power by Level.** Spell Power is set by the spell's tier and sits on the same rungs as weapon Power (0 / 2 / 3 / 5), so a spell and a blade are always priced against each other:
>
> | Level | Spell Power |
> |---|---|
> | Cantrip | 0 |
> | Novice | 2 |
> | Adept | 3 |
> | Master | 5 |
>
> **Reduce Spell Power by 1** if the spell applies its Impact to a zone, to multiple targets, or persists across rounds — breadth and duration are paid for out of the same budget as raw force. A spell that deals no Impact at all lists no Spell Power. Deviations from this table are permitted but should be justified in the spell's own entry, not left silent.

**Clash Margin Costs (every Clash spell, Overcharged or not):** A Margin 1–2 result costs the caster 1 Dissonant Stress — this is the Clash-spell equivalent of the Margin of Manifestation's Messy Success, and it's the tier Paradigm Mastery upgrades to Margin 3+ (Clean) for in-Paradigm casters, paying no cost. Margin 3+ (Clean) costs nothing. Losing the Clash outright (the target's roll is higher) costs nothing beyond the lost action — same as whiffing a mundane Strike, you only pay to land a rough hit, not to miss. The Snake Eyes Backfire (natural double-1s: 1 Wound + 1 Dissonant Stress + a battlefield hazard) applies to any Arcana casting roll, Clash or unopposed, exactly as it already does for the Margin of Manifestation.

**Overcharge:** Once per casting, before resolving the Clash, an Arcanist may Lock 1 Stress to add +2 to that spell's Spell Power for this casting only.

**Defense :** When a spell's resolution reads "vs. Target's Defense," the target rolls **2d6 + the most relevant Reactor action available to them** — typically Block, Dodge, or Brace, exactly as if they were defending against a weapon Strike. "Defense" is shorthand for "the target picks their best applicable Reactor roll," not a separate derived stat the target has sitting on their sheet.

**The Margin of Manifestation (Utility Spells)**

When casting an unopposed spell (like Levitate or Shatter Lock), the Arcanist rolls against that spell's Target Number, set by its Level per the Tiered TN table above. The spell's effectiveness is entirely dictated by the Margin.

- Failure (below the spell's TN): The spell fails. The Arcanist takes 1 Dissonant Stress.

- Messy Success (Margin 0–2): The spell works, but with dangerous collateral. The lock shatters, but the noise alerts the dungeon. The fire lights, but it catches the caster's sleeve. The caster takes 1 dissonant stress.

- Clean Success (Margin 3–4): The spell works exactly as intended.

- Massive (Margin 5+): The spell overcharges, generating 1 Momentum.

**The "Snake Eyes" Backfire (Natural 2)**

They immediately take 1 physical Wound (as their flesh chemically burns) AND 1 Dissonant Stress, and the spell produces a lethal hazard on the battlefield.

#### 2. The Arcanist's Gamble (Pushing the Math)

To give Arcanists a tactical choice similar to the Priest's sacrifice, we can introduce Blood Channelling.

- Before rolling an Arcane check, the Arcanist can voluntarily take 1 Dissonant Stress (cutting their palm, inhaling toxic fumes) to gain Advantage on their roll.

- This allows them to push the math to guarantee hitting TN 8 or to ensure a massive margin in a Clash, but it pushes them incredibly close to the Death Spiral.

---

#### Reactor Spells (Defensive Magic)

To make "Cast Spell" a valid Reactor Action, you need a specific category of spells designed to be cast in a split second.

- **Arcane Reactions (The Opposed Clash):** _Deflection_ is the worked example. It triggers the moment the caster becomes the target of an attack — it is cast **as a Reactor action with nothing raised in advance** — and resolves as an Opposed Clash using `2d6 + Arcana` against the attack's own roll. Winning negates the attack outright; the Margin then sets what the ward leaves behind, per the spell's own entry. **Not every defensive spell works this way:** _Arcane Protection_ must be **raised ahead of time as an Activation** and can never be thrown up in reaction — its Reactor action is for *using* a ward already standing, not for casting one.

- **Faith Reactions (The Stress Soak):** Because Faith magic bypasses the dice, a Priest's Reactor spell (like _Martyr's Shield_) wouldn't require a Clash roll. Instead, when an enemy rolls an attack, the Priest declares the Prayer, instantly accepts 1 or 2 Locked Stress, and immediately grants themselves or an ally a massive Front-End Reducer (e.g., +4 Shield Value) against that specific attack.

- **Fixed-Duration Buffs:** For spells like _Calcify Armour_ that grant an ongoing +1 SV, the player does not need to use the "Cast Spell" Reactor Action. The magic is already active. When attacked, they simply choose the "Block" or "Brace" action and mathematically benefit from the buffed stats.

**The Channelling Rule** Certain powerful, ongoing spells and Prayers (like _Wildfire Proliferation_ or _Sanctuary_) carry an ongoing duration. Arcane spells call this **Sustain**; Faith Prayers call it **Flowing**. A caster can only maintain one such effect at a time, regardless of which system it comes from.

**Neither Sustain nor Flowing costs Locked Stress.** An Arcanist pays for concentration in Dissonant Stress, rolled for turn by turn; a Priest has already paid their Locked Stress at the moment of casting and owes nothing further. Locked Stress is not the currency of holding a spell open in either system.

- **The Arcane Cost (Volatility) — Sustain:** To keep an Arcane spell active, the Arcanist must dedicate their concentration. They roll `2d6 + Arcana vs. the spell's own TN` at two moments: **at the start of their Activation**, before they move or act, and **immediately upon taking a Wound**. The check resolves on the standard Margin of Manifestation ladder:

	- **Fail (below the spell's TN):** The spell drops, and the Arcanist takes 1 Dissonant Stress from the magical backfire.
	- **Messy (Margin 0–2):** The spell holds, but the strain shows — the Arcanist takes 1 Dissonant Stress.
	- **Clean or Massive (Margin 3+):** The spell holds at no cost.

	Because this is a Margin of Manifestation roll, **Paradigm Mastery applies**: an in-Paradigm spell treats a Messy sustain as Clean, and the specialist channels almost indefinitely for free. An off-Paradigm or Common spell bleeds the caster a little every round. (This also makes _Fevered Channelling_ highly valuable.)

	Being knocked Prone does **not** force a Sustain check. Arcane channelling is an act of mental concentration — pain interrupts it, posture does not.

- **The Faith Cost (Sacrifice) — Flowing:** The divine connection requires absolute physical devotion. If the Priest takes a Wound or is knocked Prone, the Flowing Prayer instantly drops, no roll permitted. The Priest also rolls the Tithe of Will each Activation to maintain their grip — see **Flowing (Maintaining a Prayer)**, below.

---

## Faith (The Somatic Sacrifice)

Faith is not about channelling chaotic energy; it is about borrowing divine or eldritch authority. It is highly reliable but physically destroys the caster from the inside out.

**The Tithe of Will**

Faith magic is not a gamble against failure — it is a negotiation with the price. When a Priest declares a Prayer, the Prayer *always happens.* What the dice determine is not whether the Priest succeeds, but **whose hand is actually on the wheel**: theirs, or the entity they're borrowing power from.

- **The Mechanic:** When declaring a Prayer, the Priest rolls **2d6 + Faith vs. the Prayer's own TN**, set by its Level per the Tiered TN table above. This is not a Margin-Scaler roll — there is no Messy/Clean/Massive ladder, and there is no Failure state that prevents the Prayer from occurring. The roll only ever determines the cost.

- **Pass (meets or exceeds the Prayer's TN) — Clean Channel:** The Priest's own faith and discipline carry the weight. The Prayer occurs exactly as written, and the Priest pays the Locked Stress cost listed for that Prayer. Nothing else happens. This is the expected, unremarkable outcome for a Priest who knows their scripture.
- **Fail (below the Prayer's TN) — Borrowed Authority:** The Prayer still occurs — full effect, no exceptions — but the power moves through the Priest rather than from them. The Priest pays the standard Locked Stress cost, exactly as on a Pass, **and** gains 1 point of **Encroachment** (see below). This is not a punishment for bad luck; it is the fictional truth of the system finally showing its teeth — the Priest doesn't actually control what they're invoking, they just have working enough faith to ask nicely.
- **Snake Eyes (Natural 2) — The Toll in Flesh:** The Prayer still occurs. But whatever the Priest is channeling decides the mind has paid enough for today, and takes the rest out of the body instead. **Convert the Prayer's entire Locked Stress cost into an equal number of points of direct Wound damage** (bypassing Wound Threshold entirely, per the Direct Wounds rule), rather than Locked Stress. A Priest who Snake-Eyes a 2-Stress Prayer takes the full toll across 2 Wound slots' worth of damage instead — this is the stigmata, the shattered bone, the bleeding from the eyes the system has always promised, given an actual trigger condition instead of being purely narrative flavor. The entity considers this payment made in full: **reset the Priest's Encroachment to 0**, regardless of its current value.
	- **The Cap:** A single Toll in Flesh conversion cannot inflict more than **3 direct Wounds**, regardless of the Prayer's Locked Stress cost — this is the existing Wound Slot ceiling (Iron Core), not a new number. This keeps a bad roll on a Master Prayer brutal (it empties every Wound Slot a character has) without being an unconditional Incapacitation from full health. A Prayer's own entry can explicitly override this cap when its fictional weight demands it (see *Resurrection*, Manipulating the Void) — the cap is the default, not an absolute.
- **Fates' Bounty (Natural 12):** As with any other check, the Priest rolls an additional die. This cannot change whether the Prayer happens (it already was going to), but a Priest who rolls a 12 may treat the result as an automatic Pass even if the additional die would have otherwise pushed them past a threshold that matters for a specific Prayer (GM's discretion for Prayers with scaling effects).

**Encroachment (The Running Tab)**

Stress isn't the only thing a Fail costs a Priest — it also costs them a little more of the entity's attention. Track it on **3 Encroachment slots**, separate from any Stress track, filled the way Wound Slots are. Wherever the rules say a Priest "gains 1 Encroachment", fill 1 slot; "clears 1 Encroachment" empties 1 slot; "resets Encroachment to 0" empties them all.

- Whenever a Priest Fails a Tithe of Will — on a fresh cast or a Flowing check — they fill 1 Encroachment slot, in addition to paying the normal Locked Stress cost.
- Encroachment never modifies a dice roll. Filled slots sit on the sheet as a silent tally, exactly the way Locked Stress does — they cost nothing until the Priest runs out of room.
- **The Tab Comes Due:** when a Priest must fill an Encroachment slot and has none left empty, the entity collects all at once. The Priest suffers **1 direct Wound** (bypassing Wound Threshold, per the Direct Wounds rule), and all 3 slots clear.
- Encroachment does not clear on its own, and a Breather cannot touch it, per the Breather's existing limitation that it cannot clear Locked Stress — Encroachment is treated the same way. It only clears when the Tab Comes Due, on a Snake Eyes result (see Toll in Flesh), or by a successful Religious Pursuit (see Downtime).

>**Why roll at all, if the Prayer never fails?**

>Because reliability was never the same thing as safety. The Arcanist risks _failure_ — a botched spell, a wasted turn, a Snake-Eyes explosion that hurts everyone nearby. The Priest never risks failure, and the Stress cost is the same whether they Pass or Fail — but every single Prayer is still a coin flip between "I paid the toll myself, cleanly" and "I paid it, but the thing on the other end remembers." A Fail doesn't hurt any worse in the moment than a Pass does; it's a mark against the Priest personally, one that has nothing to do with the party's fortunes and everything to do with how many times this specific channel has slipped. A party with a Priest who keeps rolling badly isn't watching the dungeon get hungrier — they're watching their healer quietly run up a debt that whatever they've been borrowing from will, eventually, collect on in blood.

>A Priest at Faith 6 — the mortal ceiling, reachable only through Advancement and only with Will at 3 — stands at the practical ceiling of Novice-tier Faith — Encroachment from a Fail becomes mathematically impossible outside a Snake Eyes roll. This is intended: Certainty is what Faith is buying at that investment level, and the math re-introduces risk on its own at Adept (TN 10) and Master (TN 12) without needing a separate rule to force it. Locked Stress cost is unaffected either way — a Priest cannot cast for free regardless of tier.

**The Attrition**

A Priest can perfectly heal the party and strip the armour off bosses, but every time they do, they step closer to their own breaking point — on two separate clocks. Stress is the fast one: when a Priest maxes out their Stress track, they cannot cast anymore without suffering physical Wounds, per the Death Spiral rule. Encroachment is the slow one: even a Priest who manages their Stress carefully and never Breaks can still be run down by an accumulation of Fails alone, four bad rolls from an empty tab — always with a Wound waiting at the end, never with a Locked Stress figure to negotiate against.

---

#### Flowing (Maintaining a Prayer)

A Prayer with an ongoing duration is said to be **Flowing** — the authority is still running through the Priest, and has not yet been set down. Holding it open turn after turn is its own ongoing negotiation.

- **The Faith Cost:** Because the Priest already paid the Locked Stress upfront at the moment of casting, keeping a Prayer Flowing requires no *additional* Stress payment of any kind. However, at the start of each of their Activations while it Flows, the Priest must roll **2d6 + Faith vs. the Prayer's own TN** to maintain their grip on the borrowed authority.

- **Pass:** The Prayer keeps Flowing. No further cost.
- **Fail:** The Prayer keeps Flowing anyway (Faith does not simply drop the way a failed Arcane Sustain check does) — but the Priest gains 1 point of Encroachment, exactly as with a fresh cast. The longer a Priest white-knuckles a Flowing Prayer through failed rolls, the closer they creep toward paying for it in flesh.
- **Snake Eyes:** The Prayer keeps Flowing, but the Priest takes 1 direct Wound as their body pays a toll for staying tethered to something that doesn't want to let go, and their Encroachment resets to 0 as that toll is paid in full.

- **The Physical Anchor:** Regardless of the roll, if the Priest takes a Wound or is knocked Prone, the Flowing Prayer still instantly drops. Divine connection still requires absolute physical devotion — the dice govern the cost of staying tethered, not whether the tether can be physically severed.

> **Sustain and Flowing, side by side.** Both cost no Locked Stress and both are limited to one at a time. An Arcanist rolls to find out *whether they keep the spell*; a Priest rolls to find out *what holding on costs them*. A failed Arcane Sustain ends the spell. A failed Flowing check never does — but it writes another line on the tab. Conversely, a Wound only *tests* an Arcanist's concentration, while a Wound or a fall severs a Priest's connection outright, no roll offered.

# Chapter 7 — Manipulating the Void

*Spells & Prayers*

## Common Arcane Magic
**Universal Spell list**
*Available to any Arcanist regardless of chosen Paradigm. Standard DP cost. Never benefits from Paradigm Mastery.*

### Cantrip

**Elemental Manipulation** (Common)
Minor feats of elemental control — lighting a candle, cooling a drink, kicking up dust.

- **Level:** Cantrip
- **Resolution:** Unopposed Arcana vs. TN 6
- **Target/Range:** 10ft radius, Short Range
- **Action Type:** Activation

**The Margin Scaler:**
- Margin 0–4: A single harmless elemental effect occurs, granting Advantage on one relevant skill check this scene.
- Margin 5+ (Massive): The effect sustains itself for the rest of the scene without further concentration.

### Novice

**Arcane Protection** (Common)
The air around the target thickens into a dull, shimmering haze, dampening the resonance of hostile sorcery.

- **Level:** Novice
- **Resolution:** Unopposed Arcana vs. TN 8
- **Target/Range:** Self only.
- **Action Type:** Activation to raise. **It can never be cast as a Reactor action.** Reactor to use the standing ward's defense.
- **Duration:** Sustain (see The Channelling Rule — no Locked Stress cost; roll to maintain each Activation and on taking a Wound)

**The Margin Scaler:**
- Margin 0–2 (Messy): The ward holds, but the caster takes 1 Dissonant Stress from the backlash.
- Margin 3–4 (Clean): The ward holds. Hostile spells targeting the caster suffer Disadvantage on their casting roll.
- Margin 5+ (Massive): As Clean, and the ward gains SV 2 against the next hostile spell's Impact.

**Special Interactions:** **The ward must be raised in advance.** Arcane Protection is an Activation and can never be cast as a Reactor — a caster cannot answer an unforeseen spell by throwing it up on the spot. Once raised, and for as long as it remains Sustained, the caster may use **Arcana as their defense** against an incoming hostile spell, in place of their normal Reactor stat. **This is available at every band, Messy included**, and applies on top of whatever the Margin Scaler granted when the ward went up — which is deliberately what makes a Messy ward worth keeping. Note that *spell* is the generic term (see *Embracing the Abyss*): this ward answers hostile **Prayers** as readily as hostile Arcana.

---

**Bolt** (Common)
A concentrated bolt of raw energy streaks from the caster's hand toward a single foe. This is the floor every Arcanist stands on — Pyromancy and Shamanism both build sharper, paradigm-exclusive versions of this same idea.

- **Level:** Novice
- **Resolution:** Arcane Clash, Arcana vs. Target's Defense
- **Spell Power: 2**
- **Target/Range:** One character, Medium Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Impact = Margin + 2 (Spell Power). The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ (Clean): As above, no complication.

---

**Blind** (Common)
A flash of light, a cloud of soot, or a veil of shadow robs the target of sight.

- **Level:** Novice
- **Resolution:** Arcane Clash, Arcana vs. Target's Dodge (Acrobatics)
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Target is Blinded for 1 round. The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ (Clean): Target is Blinded for 3 rounds.

---

**Burst** (Common)
A cone of raw elemental energy erupts from the caster's hands.

- **Level:** Novice
- **Resolution:** Arcane Clash, Arcana vs. each target's Defense
- **Spell Power: 1** _(Novice 2, −1 for multiple targets — see *Embracing the Abyss*, Spell Power by Level.)_
- **Target/Range:** 10ft cone
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Impact = Margin + 2 (Spell Power) to every target who loses. The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ (Clean): As above, no complication.

---

**Darksight** (Common)
The caster's eyes take on a predatory sheen, piercing the deepest gloom.

- **Level:** Novice
- **Resolution:** Unopposed Arcana vs. TN 8
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): Recipient ignores penalties for Dim or Dark illumination, but suffers 1 Dissonant Stress as their eyes adjust violently.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Massive): The recipient can also detect invisible entities and active spell effects within 30 feet.

---

**Entangle** (Common)
The ground erupts with grasping vines, shadow-tendrils, or chains.

- **Level:** Novice
- **Resolution:** Arcane Clash, Arcana vs. Target's Dodge
- **Target/Range:** One character or 10ft area, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Target is Anchored. They lose the Dodge action until they break free (a full Aggressor action, or 1 Momentum). The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ (Clean): As above, and the bindings are thorned — the target suffers 1 Dissonant Stress at the start of each turn they remain Anchored.

---

**Environmental Shield** (Common)
A thin membrane of energy stabilizes the air and temperature around the recipient.

- **Level:** Novice
- **Resolution:** Unopposed Arcana vs. TN 8
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): The recipient ignores Stress and penalties from extreme environmental hazards (per the Iron World Hazard Check rules) for the scene, but the caster takes 1 Dissonant Stress raising it.
- Margin 3–4 (Clean): As above, no cost. The recipient's Wound Threshold is also treated as +2 higher specifically against environmental Direct Wounds (lava, freezing water, acid).
- Margin 5+ (Massive): The Wound Threshold bonus increases to +4.

---

**Havoc** (Common)
A concussive wave of force throws enemies into disarray.

- **Level:** Novice
- **Resolution:** Arcane Clash, Arcana vs. each target's Athletics or Acrobatics
- **Target/Range:** 10ft radius, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Target is pushed 5 feet and suffers 1 Dissonant Stress. The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ (Clean): Target is pushed 10 feet, knocked Prone, and suffers 1 Dissonant Stress.

---

**Illusion** (Common)
Light and sound are woven into a convincing facade.

- **Level:** Novice
- **Resolution:** Unopposed Arcana vs. TN 8. Anyone inspecting it rolls Notice vs. the caster's original Margin to see through it.
- **Target/Range:** 10ft area, Short Range
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): The illusion forms, but the caster takes 1 Dissonant Stress from holding the image steady.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Massive): The illusion is "True" — it includes scent and resists touch — and cannot be seen through except by physically disrupting it.

---

**Mind Link** (Common)
A telepathic bridge forms — offered, or forced.

- **Level:** Novice
- **Action Type:** Activation
- **Duration:** **Sustain** (Communion) / Instant (Intrusion) — see *The Channelling Rule*, Embracing the Abyss. A caster holds only one Sustain or Flowing effect at a time.

**Communion — willing minds.**
- **Resolution:** Unopposed Arcana vs. TN 8
- **Target/Range:** Self and up to [Wits] **willing** allies, each within **Short Range** at the moment of casting. **Once established the link persists at any distance** for as long as it is Sustained — the strain of holding it is the limit, not the geometry.
- Margin 0–4: The linked characters communicate telepathically, silently and without line of sight, for as long as the spell is Sustained. The caster takes 1 Dissonant Stress from the strain.
- Margin 5+ (Massive): As above, and linked allies may share their Momentum banks with one another while the link holds. No Stress cost.

**Intrusion — an unwilling mind.**
- **Resolution:** Arcane Clash, Arcana vs. Target's **Resolve**
- **Target/Range:** One unwilling character, Short Range. Instant — nothing is Sustained.
- Margin 1–2 (Messy): You read the target's **surface thoughts** — what they are thinking in this moment, and nothing more. Not memories, not secrets they are not presently holding in mind, not answers to questions they have not been asked. The GM narrates a sentence or two of what is actually passing through their head. **The target feels the intrusion** and knows the direction it came from. The caster takes 1 Dissonant Stress.
- Margin 3+ (Clean): As above, and **the target notices nothing.** No Stress cost.

---

**Smite** (Common)
The caster imbues a weapon with crackling energy or holy light.

- **Level:** Novice
- **Resolution:** Unopposed Arcana vs. TN 8
- **Target/Range:** One weapon, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): Weapon's Power increases by +1; the wielder takes 1 Dissonant Stress from the rough working.
- Margin 3–4 (Clean): Weapon's Power increases by +2.
- Margin 5+ (Massive): As Clean, and the weapon gains the Precise tag for the scene (per Hardware: ignores 1 point of Armour).

---

**Light/Darkness** (Common)
The caster either ignites a beacon of radiance or conjures a void that swallows sight.

- **Level:** Novice
- **Resolution:** Unopposed Arcana vs. TN 8
- **Target/Range:** 10ft radius or one object, Short Range
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): The chosen effect (Light or Darkness) manifests at half radius.
- Margin 3–4 (Clean): Full 10ft radius. If Darkness, creatures inside suffer Disadvantage on Notice and Attack rolls unless they have Darksight.
- Margin 5+ (Massive): Radius doubles to 20ft.

### Adept

**Blast** (Common)
The caster hurls a ball of energy that explodes on impact, catching multiple foes in its radius.

- **Level:** Adept
- **Resolution:** Arcane Clash, Arcana vs. each target's Defense (caster rolls once; every target in the radius defends)
- **Spell Power: 2** _(Adept 3, −1 for a zone or multiple targets — see *Embracing the Abyss*, Spell Power by Level.)_
- **Target/Range:** A point within Medium Range, 10ft radius
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Impact = Margin + 3 (Spell Power) to every target who loses. The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ (Clean): As above, and the blast ignores the first point of Armour on anyone caught at the radius's center.

---

**Barrier** (Common)
The caster conjures a physical or energetic wall to block passage and protect allies.

- **Level:** Adept
- **Resolution:** Unopposed Arcana vs. TN 10
- **Target/Range:** A 10ft line within Short Range
- **Action Type:** Activation
- **Duration:** Until destroyed

**The Margin Scaler:**
- Margin 0–2 (Messy): The barrier forms (Full Cover, Wound Threshold 8, 3 Wound Slots before it collapses), but the caster takes 1 Dissonant Stress from the strain.
- Margin 3–4 (Clean): The barrier forms exactly as described.
- Margin 5+ (Massive): The barrier's Wound Threshold increases to 10.

---

**Damage Field** (Common)
Energy lashes out from the caster's skin, punishing any who approach or strike them.

- **Level:** Adept
- **Resolution:** Unopposed Arcana vs. TN 10
- **Target/Range:** Self, 5ft radius
- **Action Type:** Activation
- **Duration:** Sustain (see The Channelling Rule — no Locked Stress cost; roll to maintain each Activation and on taking a Wound)

**The Margin Scaler:**
- Margin 0–2 (Messy): The field holds; any character ending their turn adjacent to the caster, or hitting them in melee, suffers 1 Dissonant Stress. The caster takes 1 Dissonant Stress of their own from the initial surge.
- Margin 3–4 (Clean): As above, no self-cost.
- Margin 5+ (Massive): Impact increases to 2.

---

**Dispel** (Common)
With a sharp gesture and a word of negation, the caster severs the threads of a nearby enchantment.

- **Level:** Adept
- **Resolution:** Opposed Arcana vs. the original caster's recorded casting roll
- **Target/Range:** One active spell effect, Short Range
- **Action Type:** Activation or Reactor

**The Margin Scaler:**
- Margin 1–2: The targeted spell is suppressed for 1 round. The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ (Clean): The targeted spell ends immediately.

---

**Farsight** (Common)
The caster's vision stretches across the horizon with impossible clarity.

- **Level:** Adept
- **Resolution:** Unopposed Arcana vs. TN 10
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): Recipient ignores Range penalties on ranged attacks and gains Advantage on sight-based Notice checks, but takes 1 Dissonant Stress from the strain of the working.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Massive): The recipient can also see through up to 5 feet of solid, non-magical material.

---

**Warrior's Gift** (Common)
Echoes of ancient battles flow into the recipient, granting mastery they have not earned.

- **Level:** Adept
- **Resolution:** Unopposed Arcana vs. TN 10
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): Recipient gains one Martial weapon tag they don't already have (e.g., Cleave, Sunder, Brutal); they take 1 Dissonant Stress as the borrowed memory settles violently.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Massive): Recipient gains two tags instead of one.

### Master

**Divination** (Common)
The caster enters a trance, seeking answers from the echoes of the world.

- **Level:** Master
- **Resolution:** Unopposed Arcana vs. TN 12 (requires 1 minute of concentration)
- **Target/Range:** Self
- **Action Type:** Activation
- **Duration:** Instantaneous

**The Margin Scaler:**
- Margin 0–2 (Messy): The GM provides a cryptic but useful vision; the caster takes 1 Dissonant Stress from the mental strain.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Massive): The vision is lucid. The caster gains Advantage on the next Notice or Investigation check related to it, for the rest of the scene.

**___________________________________________________________________**
## Arcane Magic Paradigms
In-Paradigm casters get the standard DP cost and Paradigm Mastery (a Messy Success resolves as Clean). Off-Paradigm casters can still learn these at a +1 DP surcharge, with neither benefit.
### Necromancy

#### Novice

**Marrow Siphon** (Attrition)
The Necromancer stoops over a body still warm enough to answer, inhaling its fading vitality to forcefully reset their own nervous system.

- **Level:** Novice
- **Target/Range:** One freshly dead corpse, Short Range — a body that died during the current Scene (see *GM Tools*). Never a living creature, however badly wounded.
- **Action Type:** Activation
- **Duration:** Instantaneous
- **Resolution:** Unopposed Arcana vs. TN 8.

- The Effect: The caster clears their own Dissonant Stress by consuming residual life force. **A successful cast spends the corpse** — there is nothing left in it to take a second time.

- The Margin Scaler:

- Failure (<8): The dead mind pollutes the caster's. The caster takes 1 Dissonant Stress, and the corpse is left untouched.

- Margin 0–2 (Messy): The caster clears 2 Dissonant Stress, but the transfer is violent and feeds 1 Dissonant Stress straight back — a net gain of one Stress slot.

- Margin 3–4 (Clean): The caster cleanly clears 2 Dissonant Stress at no cost. The corpse is reduced to ash.

- Margin 5+ (Massive): As Clean — 2 Dissonant Stress cleared, no cost, the corpse reduced to ash — and the surge is strong enough that the caster also generates 1 Momentum.

**Rigor Mortis** (Combat Control)
The caster forces the blood in a living target's extremities to instantly coagulate and their joints to temporarily calcify.

- **Level:** Novice
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** 1 round (Margin 1–2) or until the target breaks free (Margin 3+)
- **Resolution:** Arcane Clash (Arcana vs. Target's Resolve).

- The Effect: This is not designed to deal Impact (damage), but to cripple the action economy. If the Necromancer wins the Clash, the target is afflicted with Rigor.

- The Margin Scaler (Based on Clash Margin):

- Margin 1–2: The target's movement speed is halved, and they cannot use the Dodge action on their next turn. The caster also takes 1 Dissonant Stress from the strain.

- Margin 3+ (Clean): The target is completely Anchored (cannot move) and suffers a -2 penalty to their next Aggressor Strike roll because they cannot articulate their joints.

**Calcify Armour** (Utility / Buff)
The caster forces their own bones, or the bones of an ally, to painfully extrude through the skin, creating a temporary, jagged exoskeleton.

- **Level:** Novice
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Until the end of the encounter
- **Resolution:** Unopposed Arcana vs. TN 8.

- The Effect: The target gains an ablative armour layer of bone. They gain +1 Shield Value (SV) for the duration of the encounter, which stacks with physical shields.

- The Margin Scaler:

- Margin 0–2 (Messy): The bones pierce the muscle awkwardly. The target gains the SV bonus, but immediately takes 1 Dissonant Stress from the agonizing process.

- Margin 3–4 (Clean): The bone armour forms flawlessly.

- Margin 5+ (Massive): The bone spikes are violently sharp. Any enemy who attacks the target and fails the Clash via a Block or Parry immediately suffers **Impact 4** from striking the jagged bone.

#### Adept

**Corpse Bloom** (Environmental / Damage)
The Necromancer uses a dead body on the battlefield as a bomb, rapidly accelerating its decay until the buildup of necrotic gases violently ruptures the flesh.

- **Level:** Adept
- **Target/Range:** One corpse, Short Range, 10ft radius
- **Action Type:** Activation
- **Duration:** Instantaneous
- **Resolution:** Unopposed Arcana vs. TN 10. (Requires a corpse within sight).
- **Spell Power: 3**
- The Effect: The targeted corpse explodes, spraying razor-sharp bone shrapnel and toxic bile in a 10-foot radius. Every creature (friend or foe) in the radius suffers Impact equal to the casting Margin + Spell Power.
- The Margin Scaler:
  - Margin 0–2 (Messy): The explosion is delayed or unpredictable. The GM shifts the center of the blast 5 feet in a random direction before calculating who is hit.
  - Margin 3–4 (Clean): The corpse detonates perfectly as planned.
  - Margin 5+ (Massive): The blast area becomes difficult terrain for the remainder of the Scene.

> [!note] Designer's Note
> **A justified deviation.** Spell Power stays at the full Adept **3** rather than the **2** the zone/multi-target reduction would give it (*Embracing the Abyss*). Corpse Bloom pays three costs no other area spell pays: it resolves **unopposed vs. TN 10**, not TN 8; it **requires a corpse already on the battlefield**, so a fight cannot be opened with it; and it hits **friend or foe** without discrimination.

**Puppet Strings** (Combat / Partial Puppetry)
Not the whole marionette yet — just one string, pulled hard enough to matter.

- **Level:** Adept
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Target's Resolve).
- The Effect: The caster seizes control of one limb or reflex — not the target's whole turn, just a single involuntary twitch of the strings.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: The target's weapon hand spasms — they immediately drop whatever they're holding (weapon or shield). Caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, and the caster may instead force the target to make one immediate, involuntary Aggressor Strike against the nearest character (ally or enemy) using the target's own stats — a single reflexive attack, not control of their turn.

#### Master

**Drain Stress**
The caster reaches into a mind, unraveling focus and siphoning spiritual reserve — Marrow Siphon's thesis turned outward onto an enemy.

- **Level:** Master
- **Resolution:** Arcane Clash, Arcana vs. Target's Resolve
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Target gains 2 Dissonant Stress. The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ (Clean): Target gains 3 Dissonant Stress, and the caster clears 1 of their own Dissonant Stress as the siphoned focus settles.

**Zombie**
Dark energy reanimates the dead, forcing cold flesh to serve the living.

- **Level:** Master
- **Resolution:** Unopposed Arcana vs. TN 12 (requires a corpse within reach)
- **Target/Range:** One corpse, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): The corpse rises as an NPC Undead under the caster's control for the scene (Wound Threshold 6, no Stress Limit); the working costs the caster 1 Dissonant Stress.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Massive): The caster may Lock 5 Stress instead of letting the spell end — doing so makes the servant permanent until destroyed or released.
*Last Rites - Denies the effect of this spell.*

**Puppet**
The caster seizes control of the target's motor functions, turning a foe into a marionette.

- **Level:** Master
- **Resolution:** Arcane Clash, Arcana vs. Target's Resolve
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Caster controls the target's next Activation. The target cannot be forced to directly kill themselves, but can be forced to attack allies or drop their guard. The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ (Clean): As above, and control extends for 1 additional round.

---

### Shadow Sorcery

#### Novice

**Deflection**
Invisible currents of air or shifting shadows cause incoming attacks to veer off course.

- **Level:** Novice
- **Resolution:** Arcane Clash — `2d6 + Arcana`, opposed against the incoming attack's own roll.
- **Target/Range:** Self only.
- **Action Type:** Reactor only.
- **Duration:** Scene — once it holds, it stands until the next Breather or until a defensive Clash is lost. **This is not a Sustain effect:** it takes no maintenance roll and does not occupy the Channelling Rule's one-effect-at-a-time slot.

**The Margin Scaler:**
- Margin 0–2 (Messy): The attack is deflected — no Impact — but the strain shows, and the caster takes 1 Dissonant Stress. **A tie counts as Margin 0 and resolves here.**
- Margin 3–4 (Clean): The attack is deflected at no cost, and attacks against the caster suffer **−2 to their Clash** for as long as the ward stands.
- Margin 5+ (Massive): As Clean, but the standing penalty is **Disadvantage** rather than −2.

**Special Interactions:** **Deflection is never raised in advance.** It is the Arcane Reaction the magic rules describe (*Embracing the Abyss*, Reactor Spells): cast it the moment an attack is declared against the caster, as a Reactor action, resolved as an opposed Arcane Clash. That first cast both answers the attack and leaves the ward standing; from then on the caster uses **Arcana as their defense** against incoming attacks, and **the Margin Scaler applies afresh on every defense** — so a run of Clean results keeps the penalty up, while a Messy one still stops the blow and bleeds a point of Dissonant Stress. **Losing the Clash means the attack lands for full Impact with no mitigation** — no Shield Value, no armour reduction — and the ward falls. The standing penalty never stacks with itself.

**Stitch the Silhouette** (Targeted Control)
The sorcerer drives an iron nail or a blade into the target’s cast shadow on the floor, magically pinning their physical body in place.

- **Level:** Novice
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Until the target breaks free
- **Resolution:** Arcane Clash (Arcana vs. Athletics).

- The Effect: If the caster wins, the target’s shadow is nailed to the environment. The target becomes Anchored (Movement is reduced to 0).

- The Margin Scaler (Based on Clash Margin):

- Margin 1–2: The target is Anchored until they spend their entire next Aggressor action physically tearing their shadow free, which causes them to suffer 1 Dissonant Stress from the metaphysical tearing. The caster also takes 1 Dissonant Stress from the strain.

- Margin 3+ (Clean): The target is Anchored, and because their silhouette is pulled taut, they completely lose the ability to use the Dodge action until they break free. They must rely on Block or Parry.

**Flicker-Step** (Utility / Repositioning)
The caster dissolves into a nearby shadow, losing physical cohesion, and instantly reforms in another patch of darkness across the battlefield.

- **Level:** Novice
- **Target/Range:** Self, 30ft
- **Action Type:** Activation
- **Duration:** Instantaneous
- **Resolution:** Unopposed Arcana vs. TN 8.

- The Effect: The caster instantly teleports to any other shadow within 30 feet. This movement completely ignores the Threat Zones of enemies and does not trigger any attacks of opportunity. It is the ultimate escape button for a trapped Arcanist.

- The Margin Scaler:

- Margin 0–2 (Messy): The void violently rejects the caster. They teleport successfully, but arrive gasping for air, immediately suffering 1 Dissonant Stress.

- Margin 3–4 (Clean): The teleport is flawless and silent.

- Margin 5+ (Massive): The caster steps out of the shadow in perfect ambush position. They instantly generate 1 Momentum, or they gain Advantage on their next Strike roll against an adjacent enemy.

#### Adept

**Disguise**
Magical energy warps the caster's features and voice to match another.

- **Level:** Adept
- **Resolution:** Unopposed Arcana vs. TN 10. Anyone suspicious rolls Notice vs. the caster's Margin to see through it.
- **Target/Range:** Self
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): The disguise holds; caster takes 1 Dissonant Stress from maintaining the false face under scrutiny.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Massive): The veil extends to up to three allies within Short Range.

**Invisibility**
The target fades from view, replaced by the colors and textures of whatever lies behind them.

- **Level:** Adept
- **Resolution:** Unopposed Arcana vs. TN 10
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene, or until broken

**The Margin Scaler:**
- Margin 0–2 (Messy): Target is invisible; attackers suffer Disadvantage targeting them, and they gain Advantage on Stealth. The spell drops the instant they attack or cast a spell. Caster takes 1 Dissonant Stress from the unraveling effort.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Massive): The target remains invisible even after attacking — attacking only reveals their general position, removing Disadvantage from attackers for 1 round rather than dropping the spell outright.

**Creeping Dusk** (Environmental Control)
The sorcerer exhales a cloud of unnatural, pitch-black soot that instantly smothers ambient light and chokes the room in magical darkness.

- **Level:** Adept
- **Target/Range:** 15ft radius, Short Range
- **Action Type:** Activation
- **Duration:** Scene
- **Resolution:** Unopposed Arcana vs. TN 10.

- The Effect: Creates a 15-foot radius of magical darkness. Line of sight is completely broken; ranged attacks cannot enter or pass through the zone. Anyone attacking an enemy inside the zone who they cannot see suffers a -2 penalty to their Clash.

- The Margin Scaler:

- Margin 0–2 (Messy): The darkness manifests, but the shadow hungers. It instantly snuffs out all non-magical light sources (torches, lanterns) currently carried by the party, plunging the rest of the room into standard darkness as well.

- Margin 3–4 (Clean): The localized zone forms perfectly as intended.

- Margin 5+ (Massive): The shadows become actively hostile. Any enemy that starts its turn inside the zone must pass a TN 8 Resolve check or immediately suffer 1 Dissonant Stress from hallucinatory whispers.

**Blade of Paranoia** (Combat / Psychological)
The caster pulls a blade of condensed absence-of-light from the shadows. It passes completely through physical armour to strike the enemy’s psyche.

- **Level:** Adept
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Target's Resolve).

- The Effect: This spell is explicitly designed to bypass high Shield Values and thick armour tags (like the Construct or Ablative Armour tags). It deals absolutely zero physical Impact. Instead, it attacks the enemy's binary Stress track.

- The Margin Scaler (Based on Clash Margin):

- Margin 1–2: The target's mind fractures; they suffer 1 Dissonant Stress. The caster also takes 1 Dissonant Stress from the strain.

- Margin 3+ (Clean): The target suffers 2 Dissonant Stress, rapidly pushing Elites and Bosses toward their Break Point. Furthermore, the sheer terror of the blow saps their momentum—that creature must immediately discard 1 Momentum from its own Bank (if it has any).

#### Master

**Umbral Execution** (Combat / Psychological Finisher)
The direct capstone of Blade of Paranoia, honed to a killing edge — but only for a target who cannot see it coming.

- **Level:** Master
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Target's Resolve). Requires the target to currently be unable to see the caster — invisible, in darkness (magical or mundane), attacking from total concealment, or successfully Stealthed.
- The Effect: Like Blade of Paranoia, this attacks the mind directly rather than the body, dealing zero physical Impact and bypassing Shield Value or armour entirely.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: The target suffers 3 Dissonant Stress. The caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): The target suffers 4 Dissonant Stress. If this brings them to or past Breaking (100% of their Stress Limit), the shock is total — they are immediately Incapacitated instead of suffering the normal Breaking effects.

---

### Shamanism

#### Novice

**Beast Friend**
The caster's spirit resonates with the natural world, commanding the loyalty of beasts.

- **Level:** Novice
- **Resolution:** Arcane Clash, Arcana vs. the beast's Resolve
- **Target/Range:** One animal, Short Range
- **Action Type:** Aggressor
- **Duration:** Scene

**The Margin Scaler:**
- Margin 1–2: The beast becomes an ally for the scene. The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ (Clean): As above, and the caster can communicate telepathically with it and see through its eyes for the scene.

**Wind-Shear** (Crowd Control / Geometry)
The caster sweeps their arms outward, creating a localized, concussive blast of cyclonic air meant to violently physically separate combatants.

- **Level:** Novice
- **Target/Range:** 10ft cone
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Targets' Prowess or Acrobatics). Note: This targets all enemies within a 10-foot cone.

- The Effect: This spell does not deal Impact. Instead, it alters the battlefield geometry to save swarmed allies. The Shaman rolls once, and every enemy in the cone rolls to defend.

- The Margin Scaler (Based on Clash Margin):

- Margin 1–2: The enemy is violently shoved 10 feet backward, breaking any engagements and removing them from the party's Threat Zones. The caster also takes 1 Dissonant Stress from the strain.

- Margin 3+ (Clean): The enemy is shoved 10 feet backward, slammed to the ground (gaining the Prone condition), and suffers 1 Dissonant Stress from the concussive force.

**Bone Claws** (Combat / Natural Weapon)
The caster's own finger bones tear free of the flesh, reforming into three curved, ivory-white claws on each hand — the oldest weapon a body can grow back.

- **Level:** Novice
- **Target/Range:** Self, touch
- **Action Type:** Activation
- **Duration:** Until the end of the encounter
- **Resolution:** Unopposed Arcana vs. TN 8.
- The Effect: Three retractable bone claws erupt from the knuckles of each hand. The caster may extend or retract them as a Free Action — sheathed, they're indistinguishable from ordinary hands. While extended, the claws function as a Power 2 melee weapon for the caster's Aggressor Strikes and Parry actions, and their grip is sharp enough to bite into stone or bark.
- The Margin Scaler:
  - Margin 0–2 (Messy): The bones tear through fast and jagged. The claws form, but the caster takes 1 Dissonant Stress from the shock of it.
  - Margin 3–4 (Clean): The claws emerge clean and painless.
  - Margin 5+ (Massive): The grip is perfect. For the rest of the encounter, the caster has Advantage on any Climb or Grapple check made with the claws extended.

#### Adept

**Fulminating Strike** (Combat / Anti-Armour)
The Shaman draws ambient static from the air, concentrating it into a deafening, blinding arc of jagged lightning that seeks out grounded metal.

- **Level:** Adept
- **Target/Range:** One character, Medium Range
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Target's Dodge or Brace).
- **Spell Power: 3**
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 3 (Spell Power). The sheer voltage causes the target to drop their weapon or shield; they must spend a Free Action on their next turn picking it up. The caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, and the electrical surge cooks the target inside their armour — they instantly suffer 1 Dissonant Stress in addition to the physical Wound damage.

**Blood-Wood Totem** (Environmental / Aura)
The caster drives a carved, bone-and-wood fetish into the earth, bleeding onto it to awaken a localized, territorial nature spirit.

- **Level:** Adept
- **Target/Range:** 15ft radius, Short Range
- **Action Type:** Activation
- **Duration:** Until destroyed
- **Resolution:** Unopposed Arcana vs. TN 10.

- The Effect: Creates a 15-foot radius aura centered on the totem. The environment physically warps within this zone—roots tear through cobblestones, and the air grows heavy. Any ally standing inside the aura gains the Pack Tactics tag (ignoring an enemy's Shield Value if an ally is also engaged with that enemy).

- The Margin Scaler:

- Margin 0–2 (Messy): The spirit is unruly. The totem is established, but it demands an immediate toll. The caster suffers 1 Dissonant Stress.

- Margin 3–4 (Clean): The totem takes root perfectly. It remains active until destroyed (it has 1 Wound Slot).

- Margin 5+ (Massive): The spirit is completely subjugated. Enemies entering the radius must treat it as difficult terrain, while allies move through it freely.

**Ancestral Mantle** (Utility / Buff)
The Shaman inhales the ashes or bone dust of a long-dead warrior, allowing a feral, blood-starved spirit to temporarily possess an ally's nervous system.

- **Level:** Adept
- **Target/Range:** Self or one ally, Short Range
- **Action Type:** Activation
- **Duration:** Until the end of the encounter
- **Resolution:** Unopposed Arcana vs. TN 10. (Targeting self or one ally in sight).

- The Effect: The target is physically swollen with spiritual mass. For the rest of the encounter, the target's primary weapon gains +1 Power, and they are immune to being knocked Prone or Repositioned.

- The Margin Scaler:

- Margin 0–2 (Messy): The possession is agonizing. The buff is applied, but the target immediately takes 1 Dissonant Stress as the ancient spirit tries to override their consciousness.

- Margin 3–4 (Clean): The mantle settles perfectly onto the target.

- Margin 5+ (Massive): The spirit is bloodthirsty. The target immediately generates 1 Momentum the moment the spell is cast.

#### Master

**Apex Form** (Combat / Predator Transformation)
The escalation of Bone Claws: instead of just claws, the caster's whole body commits to the change — fangs lengthen, pupils blow wide to drink in the dark, muscle and sinew reshape around a predator's instincts.

- **Level:** Master
- **Target/Range:** Self
- **Action Type:** Activation
- **Duration:** Scene
- **Resolution:** Unopposed Arcana vs. TN 12.
- The Effect: The caster gains a natural claw-and-fang weapon (Power 3) usable for Aggressor Strikes and Parry, plus heightened predator senses — Advantage on any Notice or Perception check for the duration. If the caster already has claws extended from Bone Claws, Apex Form layers over them rather than requiring the claws to reform.
- The Margin Scaler:
  - Margin 0–2 (Messy): The change takes hold, but instinct overrides higher reasoning — the caster suffers Disadvantage on any Faith or social-based check for the scene, and takes 1 Dissonant Stress from the transformation's violence.
  - Margin 3–4 (Clean): The transformation settles fully under the caster's control. No cost, no penalty.
  - Margin 5+ (Massive): Weapon Power increases to 4, and the caster is immune to Fear or Intimidation effects for the scene — an apex predator doesn't flinch.

---

### Transmutation

#### Novice

**Boost/Lower Trait**
The caster reaches into a body's fundamental rhythm, quickening it or grinding it to a crawl.

- **Level:** Novice
- **Resolution:** Arcane Clash, Arcana vs. Target's Resolve (if unwilling) — unopposed vs. TN 8 if willing
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor (unwilling) or Activation (willing)
- **Duration:** Sustain (see The Channelling Rule — no Locked Stress cost; roll to maintain each Activation and on taking a Wound)

**The Margin Scaler:**
- Margin 1–2 / 0–2 (Messy): Target gains a +1 (Boost) or -1 (Lower) modifier to one chosen Skill. The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ / 3–4 (Clean): As above, with no complication.
- Margin 5+ (Massive, unopposed only): Magnitude increases to +/-2.

**Special Interactions:** A character can only have one Boost or Lower effect active at a time; a second casting replaces the first.

**Burrow**
The caster or a chosen ally melts into the earth, moving through soil and stone like water.

- **Level:** Novice
- **Resolution:** Unopposed Arcana vs. TN 8
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): Target gains Earth Glide (move through earth at normal Move) and Total Cover from surface attacks while burrowed, but cannot see the surface; the working leaves them disoriented for 1 Dissonant Stress.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Massive): Emerging to attack grants Advantage on the first Strike roll of that turn.

**Reactive Bulwark** (Utility / Environmental Transmutation)
The caster doesn't conjure a wall from nothing — they reach into the nearest slab of earth or stone and wrench a piece of it upward, sideways, or loose, just fast enough to catch a blow.

- **Level:** Novice
- **Target/Range:** Self or one ally, Short Range (requires a nearby surface of raw material — earth, stone, wood, or similar — within touch range of the target to draw from)
- **Action Type:** Reactor
- **Duration:** The defensive Clash is instantaneous; the resulting terrain persists until destroyed or the end of the scene
- **Resolution:** Arcane Clash — Arcana vs. the attacker's Strike roll, substituting entirely for the target's normal Reactor action (Dodge, Parry, or Block) against this one Strike. If the caster loses the Clash, the material shatters before it fully forms and the target takes full Impact with no mitigation.
- The Effect: A spar of raised earth, a shard peeled from a nearby pillar, or a jutting slab of floor interposes itself between the target and the attack. Unlike a personal ward, this is a real physical object — if it survives forming, it remains standing on the battlefield afterward, and any character (not just the caster) can use it as Partial Cover until it's destroyed or the scene ends.
- The Margin Scaler (Based on Clash Margin, if the caster wins):
  - Margin 1–2: The cover holds, but only just. The target takes no Impact, and the caster suffers 1 Dissonant Stress from transmuting on pure reflex. The slab itself is cracked and unstable — it counts as difficult terrain rather than usable cover.
  - Margin 3+ (Clean): The cover holds cleanly, no cost, and the slab remains standing and stable — usable as Partial Cover by anyone for the rest of the scene.

#### Adept

**Growth/Shrink**
The target's physical dimensions warp, swelling to monstrous proportions or collapsing into a diminutive one.

- **Level:** Adept
- **Resolution:** Arcane Clash, Arcana vs. Target's Resolve (if unwilling) — unopposed vs. TN 10 if willing
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor or Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 1–2 / 0–2 (Messy): Target's Scale shifts by 1 step (per the existing Scale rules — Growth: +2 WT, Advantage on Prowess shoving/grappling, Disadvantage on Stealth; Shrink: -1 WT, Advantage on Stealth, Disadvantage on Prowess). The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ / 3–4 (Clean): As above, no complication.
- Margin 5+ (Massive, unopposed only): The shift is extreme — Scale +/-2 instead of 1.

**Caustic Deluge** (Combat / Gear Degradation)
The caster’s hands violently sweat a highly reactive, boiling solvent, which they hurl in a concentrated arc that eagerly eats through manufactured materials.

- **Level:** Adept
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Target's Defense action).
- **Spell Power: 2**
- The Effect: This spell ignores the target's Shield Value (SV) entirely during the Clash, as the acid simply splashes over and eats through the barrier.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 2 (Spell Power). If the target used a shield to Block, the shield **permanently loses 1 Shield Value** — a **baseline** reduction, not the Damaged Condition, so **no repair restores it** (see *Condition is not the same as baseline*, Hardware). The caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, and the target's armour immediately gains the **Damaged** tag — which Hammer & Forge can clear like any Condition — **and its special tags are destroyed outright**: Ablative Carapace, Construct plating and their like are a **baseline** loss and never come back, repaired or not. The acid eats the cleverness out of a harness first and the metal second.

> [!note] Designer's Note
> **A justified deviation, downward.** Spell Power is **2** where the Adept default is **3** (*Embracing the Abyss*), and the missing point was spent on permanence rather than lost. The spell ignores Shield Value outright, strips **1 SV from a shield's baseline** on any landed hit, and on Clean both Damages the target's armour *and* **destroys its special tags outright** — Ablative Carapace, Construct plating and their like are gone for good, where the Damaged tag itself is merely a Condition a smith can clear. It is single-target, so the area reduction never applied — the trade is raw force for irreversible gear destruction.

**Mutagenic Surge** (Utility / Flesh-Warping Buff)
The caster forces a localized, agonizing biological reaction—either in themselves or an ally—causing muscles to instantly hypertrophy and adrenaline to flood the nervous system.

- **Level:** Adept
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Until the end of the encounter
- **Resolution:** Unopposed Arcana vs. TN 10.

- The Effect: The target undergoes a grotesque physical enhancement. For the remainder of the encounter, the target gains a +2 modifier to Prowess, ignoring the normal Attribute + 3 Skill Ceiling, up to the absolute mortal maximum of +6, and their unarmed strikes deal Impact equal to a Power 2 weapon.

- The Margin Scaler:

- Margin 0–2 (Messy): The mutation is unstable. The buff takes hold, but the biological shock is so violent the target immediately suffers 1 Minor physical Wound (or 2 Dissonant Stress, target's choice).

- Margin 3–4 (Clean): The flesh warps and stabilizes flawlessly.

- Margin 5+ (Massive): The target's metabolism goes into overdrive. They immediately heal 1 Wound Slot (Triage effect) as their cells rapidly multiply, in addition to receiving the buff.

**Solder Joints** (Crowd Control / Transmutation)
The caster snaps their fingers, drastically superheating the ambient air around a specific metallic object, causing an enemy's gear to instantly melt and fuse together.

- **Level:** Adept
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Until the target breaks free, or (Margin 3+) until the end of the fight
- **Resolution:** Unopposed Arcana vs. TN equal to the target's Wound Threshold.

- The Effect: You target an enemy wearing metal armour or wielding a mechanical/metal weapon. If you succeed, you don't deal Impact; instead, you fuse their gear.

- The Margin Scaler (Based on Clash Margin):

- Margin 1–2: You weld the target's boots to the floor or their greaves at the knees. The target is Anchored (0 movement) until they spend their next full Aggressor action physically tearing the metal apart. The caster also takes 1 Dissonant Stress from the strain.

- Margin 3+ (Clean): You fuse the target's weapon to their gauntlet or weld their visor shut. The target is Anchored and suffers Disadvantage on all Strike rolls until the end of the fight.

**Vitrify** (Environmental / Breach)
The caster places their palm against a solid surface—stone, wood, or bone—and transmutates the molecular structure into brittle, highly pressurized glass.

- **Level:** Adept
- **Target/Range:** A **10 × 10 × 2 ft volume** of wall, floor or door — a 10 ft square face, 2 ft deep — touch
- **Action Type:** Activation
- **Duration:** Until shattered
- **Resolution:** Unopposed Arcana vs. TN 10.

- The Effect: This spell alters the physical geometry of the dungeon. The affected volume becomes **Glass** — **Wound Threshold 2, 1 Wound Slot**, per *Structural Damage and Destruction* (Iron Core). Because the glass is held under violent pressure, **any hit that lands at all shatters it outright, regardless of Impact** — even a kick. That override is what the spell is buying; the WT 2 / 1 Slot figure is there for anything that needs an actual number.

- **Depth matters.** Only the outer **2 ft** transmutates. A plank door, an interior stone wall or a portcullis grate is thinner than that and gives way entirely. **A fortification is not** — a curtain wall, a gate or a ship's hull is thicker than 2 ft by definition, so one casting glasses a 2 ft shell and leaves stone behind it. Breaching a fortification this way takes repeated castings, which is the point: Vitrify is a dungeon key, not a siege engine.

- The Margin Scaler:

- Margin 0–2 (Messy): The transmutation works, but the glass is highly unstable and explodes outward immediately. The caster takes 1 Dissonant Stress from the shrapnel.

- Margin 3–4 (Clean): The surface turns to glass, waiting to be shattered safely.

- Margin 5+ (Massive): The caster controls the tension of the glass. When it shatters, it leaves behind a floor of razor-sharp caltrops, turning that 10x10 zone into a hazard that deals 1 Dissonant Stress to any enemy that moves through it.

#### Master

**Apotheosis of Flesh** (Utility / Peak Biological Transmutation)
The caster does not merely enhance the body, but reshapes it to whatever configuration performs best, in every direction at once.

- **Level:** Master
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene
- **Resolution:** Unopposed Arcana vs. TN 12.
- The Effect: The target's body is remade for pure physical optimization: +2 to one Skill of the caster's choice (this replaces, rather than stacks with, any active Boost/Lower Trait effect), Scale increases by one step per the Growth/Shrink rules, and unarmed strikes deal Impact equal to a Power 3 weapon for the duration.
- The Margin Scaler:
  - Margin 0–2 (Messy): The transformation holds, but the body wasn't built to sustain this configuration — the target takes 1 Dissonant Stress now, and again when the spell ends as their body violently reverts.
  - Margin 3–4 (Clean): Stable for the duration; the reversion at scene's end is merely uncomfortable, no further cost.
  - Margin 5+ (Massive): The new configuration is so well-optimized that reverting is instant and painless — no Dissonant Stress at all, even on ending.

**The Long Rust** (Combat / Total Gear Failure)
Where Caustic Deluge hits one piece of gear and Solder Joints fuses one weapon, this hits everything the target is wearing or wielding at once.

- **Level:** Master
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Instantaneous (effects are permanent)
- **Resolution:** Arcane Clash (Arcana vs. Target's Resolve).
- The Effect: Every piece of equipped gear the target carries — weapon, shield, armour — decays at once: metal rusts to flaking ruin, leather cracks to dust, wood crumbles. Like Solder Joints, this deals zero Impact; it destroys equipment instead. Only affects a target actually wearing or wielding separate physical gear — a Beast or bare-handed Construct has nothing for this to grip onto.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Every equipped weapon and shield **permanently loses 2 SV or Power** — a **baseline** reduction, not the Damaged Condition, so **no repair restores it** (see *Condition is not the same as baseline*, Hardware); armour gains the **Damaged** tag, which a smith *can* clear. Caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, and one piece of the target's gear (their choice, or GM's call) is destroyed outright — gone for the rest of the campaign.

---

### Demonology and Void Magic

#### Novice

**Fear**
The caster whispers a truth from the outer dark, projecting pure existential dread.

- **Level:** Novice
- **Resolution:** Arcane Clash, Arcana vs. Target's Resolve
- **Target/Range:** One character or 10ft area, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Target suffers 2 Dissonant Stress and must spend their next Activation moving away from the caster at maximum speed. The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ (Clean): As above, and if it's a Fodder-tier enemy, they immediately Rout (per the NPC Stress rules) rather than just fleeing.

**Void Rend** (Combat / Reality Thinning)
A sliver of the void, no wider than a blade, opens against the target — reality doesn't quite reconnect where it touches.

- **Level:** Novice
- **Target/Range:** One character, Medium Range
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Target's Defense action).
- **Spell Power: 2**
- The Margin Scaler:
  - Margin 1–2: Impact = Margin + 2 (Spell Power). This Impact ignores 1 point of the target's Shield Value or Armour — the wound doesn't close right. Caster takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, no complication.

**Flicker Out** (Utility / Defensive Void)
For a fraction of a second, the target isn't fully present in reality — the attack passes through where they used to be.

- **Level:** Novice
- **Target/Range:** Self or one ally, Short Range
- **Action Type:** Reactor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash — Arcana vs. the attacker's Strike roll, substituting entirely for the target's normal Reactor action (Dodge, Parry, or Block) against this one Strike. If the caster loses the Clash, the target snaps back too late and takes full Impact with no mitigation.
- The Margin Scaler (if the caster wins):
  - Margin 1–2: The target avoids the attack entirely. Caster takes 1 Dissonant Stress from tearing the gap.
  - Margin 3+ (Clean): As above, no cost, and the target may shift up to 10 feet to an unoccupied space they can see as they reappear.

#### Adept

**The Devouring Silence** (Crowd Control / Rule Suspension)
The void doesn't erase the target's nature, just silences it for a moment — unlike Euclidean Fracture, this works on any target, not just Elites and Bosses.

- **Level:** Adept
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Until the end of the target's next turn
- **Resolution:** Arcane Clash (Arcana vs. Target's Resolve).
- The Margin Scaler:
  - Margin 1–2: One of the target's passive Bestiary tags or special rules (GM's call if they have several) simply doesn't function until the end of their next turn. Caster takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, and the target also loses access to any Momentum-fuelled special action for that same duration.

**Euclidean Fracture** (Crowd Control / Geometry)
The caster violently twists the spatial dimensions around an enemy, causing distances to become infinitely long or impossibly short.

- **Level:** Adept
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Until the paradox resolves (see Margin Scaler)
- **Resolution:** Arcane Clash (Arcana vs. Target's Resolve).
- **Spell Power: 3**
- The Effect: You target one character. If you win the Clash, you lock them in a spatial paradox.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: The target is Anchored (0 movement). Any melee attack they attempt against an adjacent player automatically suffers a -2 penalty, as their weapon swings through warped space. The caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): The target is trapped. If they attempt to move or use an Aggressor action, they instantly suffer Impact equal to the original casting Margin + 3 (Spell Power) as the twisted geometry physically tears their muscles, and must spend their entire turn taking the Regroup action just to let the space stabilize.

#### Master

**Flay the Veil** (Combat / Unmitigated Annihilation)
The caster rips a jagged, temporary tear in the air itself, exposing the target to the crushing pressure and absolute zero of the void outside reality.

- **Level:** Master
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Target's Dodge action).
- **Spell Power: 5**
- The Effect: This spell completely ignores all physical armour, Shield Values, and Bestiary tags. It is pure, unmitigated erasure. However, if the caster loses the Clash via a target's Dodge, the tear violently snaps shut, and the **defending creature banks 1 Momentum**.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 5 (Spell Power). The target is chilled to the bone, suffering Disadvantage on their next physical Strike roll. The caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, and the target loses a piece of their physical form to the void. If it is an Elite or Boss, they permanently lose one of their Rule-Breaking Tags (e.g., Pack Tactics or Ablative Armour) as it is sucked into the tear.

**Zone of Apathy** (Environmental / Meta-Disruption)
The caster whispers a truth from the outer dark, creating a localized field where ambition, adrenaline, and survival instincts simply cease to exist.

- **Level:** Master
- **Target/Range:** 15ft radius, Short Range
- **Action Type:** Activation
- **Duration:** Until the end of the encounter, or until the caster moves
- **Resolution:** Unopposed Arcana vs. TN 12.

- The Effect: Creates a 15-foot radius of soul-crushing despair. While inside this zone, the game’s meta-economy is completely paused. **Nobody inside can generate or spend Momentum — players and enemies alike.**

- The Margin Scaler:

- Margin 0–2 (Messy): The apathy infects the caster. The zone is created, but the caster immediately loses all their banked Momentum and takes 1 Dissonant Stress.

- Margin 3–4 (Clean): The zone forms and holds until the end of the encounter or until the caster moves.

- Margin 5+ (Massive): The despair is weaponized. Any enemy possessing the Fodder tier that begins its turn in the zone instantly surrenders or collapses, their Stress track functionally broken.

**The Marrow Bargain** (Utility / Sacrificial Engine)
The caster offers their own physical substance to the entities in the void in exchange for a sudden, violent distortion of probability.

- **Level:** Master
- **Target/Range:** Self or one ally, Short Range
- **Action Type:** Activation or Free Reaction
- **Duration:** Instantaneous
- **Resolution:** Unopposed Arcana vs. TN 12. (Can be cast as a Free Reaction).

- The Effect: This is the ultimate panic button. The caster intentionally suffers 1 Minor physical Wound (marking a Wound Slot). In exchange, they grant themselves or an ally an immediate, game-breaking advantage.

- The Margin Scaler:

- Margin 0–2 (Messy): The void takes more than offered. The caster suffers the Wound AND 1 Dissonant Stress, but the target ally instantly gains 2 Momentum.

- Margin 3–4 (Clean): The caster suffers the Wound, and the target ally's next Strike roll automatically counts as rolling a Natural 12 (triggering the exploding dice mechanic and a massive Margin), without having to roll.

- Margin 5+ (Massive): The void is satiated by the blood. The caster suffers the Wound, but the entire party immediately clears all Dissonant Stress.

---

### Witch Magic and Hedge Craft

#### Novice

**Confusion**
Whispers of madness scramble the target's thoughts.

- **Level:** Novice
- **Resolution:** Arcane Clash, Arcana vs. Target's Resolve
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2 (Messy): The target gains the **Confused** condition (Iron Core). The caster also takes 1 Dissonant Stress from the strain.
- Margin 3+ (Clean): The target gains **Confused** and **automatically loses their next Activation with no check at all**, testing normally from the Activation after that. No Stress cost to the caster.

**The Evil Eye** (Combat / Debuff)
The Witch locks eyes with the target and whispers a localized, highly specific curse, snapping a small chicken bone or twig to seal the hex.

- **Level:** Novice
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Until the **Hexed** roll resolves.
- **Resolution:** Arcane Clash (Arcana vs. Target's Resolve).

- The Effect: This spell does not deal immediate physical Impact. It infects the target’s luck and muscle memory.

- The Margin Scaler (Based on Clash Margin):

- Margin 1–2: The target gains the **Hexed** condition (Iron Core). The caster also takes 1 Dissonant Stress from the strain.

- Margin 3+ (Clean): The curse roots deep. The target gains **Hexed**, and if the Hexed roll fails, the supernatural backlash instantly inflicts 1 Dissonant Stress on them. This forces enemies to either stop attacking or rapidly accelerate toward their breaking point.

**Warding Knot** (Utility / Protective Curse)
The Witch ties a knot of twine, hair, and a sliver of bone into a bracelet or amulet, binding a small ill fate to anyone who dares strike its wearer.

- **Level:** Novice
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Until triggered, or the end of the scene
- **Resolution:** Unopposed Arcana vs. TN 8.
- The Effect: The target is warded. The next time an enemy successfully lands a Strike against them, the curse bites back — the attacker suffers Disadvantage on their next roll as ill luck catches up with them. The knot then unravels, its magic spent.
- The Margin Scaler:
  - Margin 0–2 (Messy): The ward binds, but loosely — it still triggers correctly, but the caster suffers 1 Dissonant Stress tying the curse.
  - Margin 3–4 (Clean): The knot ties cleanly, no cost.
  - Margin 5+ (Massive): The knot is bound deep enough to survive one triggering — it can curse an attacker this way twice before finally unraveling.

#### Adept

**Sympathetic Effigy** (Utility / Damage Mitigation)
The Witch rapidly binds a handful of straw, twine, and a drop of an ally's blood into a crude poppet, creating a metaphysical lightning rod for physical trauma.

- **Level:** Adept
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Until triggered, or the end of the scene
- **Resolution:** Unopposed Arcana vs. TN 10.

- The Effect: The Witch links the poppet to themselves or one ally. The poppet acts as a sacrificial Ward. The next time the linked character would suffer a physical Wound, the poppet violently snaps in half, completely negating the Wound.

- The Margin Scaler:

- Margin 0–2 (Messy): The sympathetic link is slightly misaligned. The poppet shatters and absorbs the Wound, but the metaphysical shock causes the Witch to immediately suffer 1 Dissonant Stress.

- Margin 3–4 (Clean): The poppet perfectly absorbs the Wound and turns to ash.

- Margin 5+ (Massive): The curse reflects the harm. The poppet absorbs the Wound, and the enemy who delivered the blow instantly suffers **Impact 4** as their own flesh mysteriously tears open.

**Choking Bramble** (Environmental / Retaliation)
The caster scatters a handful of dead seeds that instantly erupt into a writhing, ankle-high patch of thorny, iron-hard briars that bleed a numbing sap.

- **Level:** Adept
- **Target/Range:** 15ft radius, Short Range
- **Action Type:** Activation
- **Duration:** Scene
- **Resolution:** Unopposed Arcana vs. TN 10.

- The Effect: Creates a 15-foot radius of cursed ground. This is not just difficult terrain; it is actively hostile. Any enemy that declares an Aggressor action while standing in the briars is punished for shifting their weight.

- The Margin Scaler:

- Margin 0–2 (Messy): The briars sprout wildly. They deal 1 Dissonant Stress to any enemy that attacks from within them, but the Witch's allies also treat the zone as difficult terrain.

- Margin 3–4 (Clean): The briars recognize the caster’s allies. Allies move freely, but enemies who declare a Strike from within the zone automatically suffer 1 Dissonant Stress before their attack resolves.

- Margin 5+ (Massive): The thorns are venomous. In addition to the 1 Dissonant Stress, any Fodder-tier enemy taking damage from the briars instantly loses their flanking Bonus for the remainder of the round as the pain breaks their coordination.

**The Creeping Ague** (Crowd Control / Biological)
The Witch blows a handful of pale, grave-dust spores into the face of a target, instantly inducing a supernatural, bone-rattling fever.

- **Level:** Adept
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Scene
- **Resolution:** Arcane Clash (Arcana vs. Resolve or Brace action).

- The Effect: The target's immune system violently rebels, destroying their stamina and action economy.

- The Margin Scaler (Based on Clash Margin):

- Margin 1–2: The fever spikes. The target's movement is reduced to 0 (Anchored), and they completely lose the ability to use the Parry or Dodge actions on their next turn, as their muscles spasm uncontrollably. The caster also takes 1 Dissonant Stress from the strain.

- Margin 3+ (Clean): The sickness is overwhelming. The target must forfeit their entire next turn, violently retching and coughing black bile. They automatically take the Regroup action, doing nothing else. If it is an Elite or Boss, that creature cannot spend Momentum until it recovers.

#### Master

**Malefic Reflection** (Combat / Curse)
The ultimate expression of the paradigm's whole logic: where Sympathetic Effigy reflects one blow back onto whoever delivered it, this curse binds the target's own violence to themselves for good — every hit they land, they land on themselves too.

- **Level:** Master
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Scene, or until the target is Incapacitated
- **Resolution:** Arcane Clash (Arcana vs. Target's Resolve).
- The Effect: The Witch binds the cursed target's fate to their own capacity for harm. For the duration, any time the target deals Impact to another character, the curse turns that same violence back on them.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Whenever the target deals Impact to anyone, they simultaneously suffer Impact equal to half that amount (round down, minimum 1). The caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, but the rebounded Impact equals the full amount dealt — every blow they land, they take in equal measure.

### Astromancy

#### Novice

**Gravity Dart** (Combat / Kinetic Strike)
The Astromancer compresses a knot of localized space to bullet density and flings it downrange — the closest thing the discipline has to a simple bolt.

- **Level:** Novice
- **Target/Range:** One character, Medium Range
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Target's Defense action).
- **Spell Power: 2**
- The Effect: A marble-sized mass, dense enough to punch through armour, strikes the target at speed.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 2 (Spell Power). The caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, and the compression shockwave scrambles the target's inner ear — they suffer Disadvantage on their next Reactor roll (Dodge, Parry, or Block).

**Gravity Well** (Utility / Short-Range Retrieval)
The caster inverts the pull between themselves and a target for an instant, hauling it bodily through the air.

- **Level:** Novice
- **Target/Range:** One willing ally or unattended object, Medium Range
- **Action Type:** Activation
- **Duration:** Instantaneous
- **Resolution:** Unopposed Arcana vs. TN 8. (Cannot target unwilling creatures, or anything beyond what one person could carry — dragging a Construct or an enemy takes a heavier working.)
- The Effect: The target is yanked through the air to an empty space adjacent to the caster.
- The Margin Scaler:
  - Margin 0–2 (Messy): The pull works, but the transit is rough. The caster takes 1 Dissonant Stress from the recoil.
  - Margin 3–4 (Clean): The pull is smooth and controlled, no cost.
  - Margin 5+ (Massive): The target arrives with enough momentum to immediately make a free Aggressor Strike if they land adjacent to an enemy.

**Leaden Grasp** (Crowd Control / Weight Manipulation)
The caster doubles the local gravity around a single target, turning their own weight into a trap.

- **Level:** Novice
- **Target/Range:** One character, Medium Range
- **Action Type:** Aggressor
- **Duration:** Until the end of the target's next turn
- **Resolution:** Arcane Clash (Arcana vs. Target's Resolve).
- The Effect: This is not designed to deal Impact (damage), but to cripple mobility. If the Astromancer wins the Clash, the target is afflicted with crushing weight.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: The target's Move is halved for their next turn. The caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): The target's Move is reduced to 0 (Anchored) for their next turn, and they suffer a -2 penalty on any Aggressor Strike they attempt while anchored, unable to get their weight behind the swing.

#### Adept

**Crushing Singularity** (Environmental / Gravity Control)
The caster compresses a sphere of localized space into a marble-sized singularity, generating a crushing gravitational pull that distorts the battlefield.

- **Level:** Adept
- **Target/Range:** 15ft radius, Short Range
- **Action Type:** Activation
- **Duration:** Scene
- **Resolution:** Unopposed Arcana vs. TN 10.

- The Effect: Creates a 15-foot radius zone of hyper-gravity. Any creature starting its turn inside the zone, or attempting to move through it, treats the area as difficult terrain. Furthermore, moving away from the center of the singularity requires the creature to forfeit its Aggressor action for the turn as it fights the gravitational drag.

- The Margin Scaler:

- Margin 0–2 (Messy): The singularity is misaligned. The zone forms, but the caster is immediately dragged 5 feet toward the center and suffers 1 Dissonant Stress from the G-force.

- Margin 3–4 (Clean): The gravity well stabilizes perfectly.

- Margin 5+ (Massive): The pressure is absolute. Any Elite or Construct caught in the exact center of the zone instantly has their armour violently warped, immediately gaining the Damaged tag to their gear.

**Astral Piercer** (Combat / Vertical Bypassing)
The Astromancer calls down a pinpoint, blinding shaft of condensed starlight that strikes from the atmosphere directly onto the target’s skull.

- **Level:** Adept
- **Target/Range:** One character, Medium Range
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Target's Defense action).
- **Spell Power: 3**
- The Effect: Because the attack comes from directly above at orbital velocity, traditional horizontal defenses are useless. The target completely loses the ability to use the Parry action against this Strike. They must rely on a heavy shield (Block) or attempt to Dodge.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 3 (Spell Power). The flash is blinding, stripping the target of their peripheral vision and denying them the flanking Bonus or Pack Tactics on their next turn. The caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, and the sheer kinetic force instantly knocks the target Prone.

**Tidal Lock** (Crowd Control / Relational Geometry)
The caster mathematically binds an enemy’s gravitational pull to an ally, forcing them into a locked, inescapable orbit.

- **Level:** Adept
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor
- **Duration:** Until the end of the encounter
- **Resolution:** Arcane Clash (Arcana vs. Target's Arcana or Resolve).

- The Effect: You target an enemy and tether them to a specific ally.

- The Margin Scaler (Based on Clash Margin):

- Margin 1–2: The target is caught in a minor orbit. If the target willingly moves closer to or further away from the tethered ally, the spatial shearing instantly inflicts 1 Dissonant Stress on the target. They must maintain the exact distance to stay safe. The caster also takes 1 Dissonant Stress from the strain.

- Margin 3+ (Clean): The target is perfectly locked. If the tethered ally moves on their turn, the enemy is violently dragged across the battlefield with them, maintaining the exact geometric distance, completely ignoring the enemy's weight or Construct tags.

**Weightless Step** (Utility / Physics Alteration)
The Astromancer temporarily severs an ally’s connection to gravity, completely removing their physical mass.

- **Level:** Adept
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Until the end of the encounter
- **Resolution:** Unopposed Arcana vs. TN 10.

- The Effect: The target ally becomes completely weightless. For the remainder of the encounter, they ignore all difficult terrain (Mire, Choking Brambles, etc.) and automatically gain Advantage on all Dodge checks. However, because they lack physical mass and leverage, they cannot use the Block or Brace actions while under this effect.

- The Margin Scaler:

- Margin 0–2 (Messy): The sudden loss of gravity induces severe vertigo. The spell works, but the target immediately suffers 1 Dissonant Stress.

- Margin 3–4 (Clean): The target easily adapts to the microgravity.

- Margin 5+ (Massive): The target perfectly manipulates their orbital momentum. The first time the target drops from a height or leaps to perform a melee Strike, their weapon's Power is increased by +1 for that single swing due to terminal velocity.

#### Master

**Fly**
Gravity loses its grip as the target begins to drift, then soar. The escalation of Weightless Step's gravity-defiance.

- **Level:** Master
- **Resolution:** Unopposed Arcana vs. TN 12
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): Target gains a Flying Move equal to their land Move and can hover; the working leaves them nauseated for 1 Dissonant Stress.
- Margin 3–4 (Clean): As above, no cost. While airborne, they also gain Advantage on Acrobatics checks to dodge ground-based or non-flying melee attacks.
- Margin 5+ (Massive): Flying Move doubles for the scene.

### Pyromancy

#### Novice

**Thermal Detonation** (Crowd Control / Proximity Defense)
The caster hyper-pressurizes the air directly around their own body, before releasing it in a deafening, spherical concussive blast.

- **Level:** Novice
- **Target/Range:** 5ft radius, self
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Targets' Defense action). Note: This targets every enemy currently engaged in the caster's Threat Zone.
- **Spell Power: 1** _(Novice 2, −1 for multiple targets — see *Embracing the Abyss*, Spell Power by Level.)_
- The Effect: This is the Pyromancer's panic button when swarmed. The caster rolls once, and every enemy within 5 feet must roll to defend.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 1 (Spell Power). The concussive wave violently throws the enemy 5 feet backward, removing them from the caster's Threat Zone and breaking the Swarm Bonus. The caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, and the enemy is thrown 10 feet backward, knocked Prone, and suffers 1 Dissonant Stress from the ruptured eardrums.

**Ember Lance** (Combat / Direct Strike)
Furnace Lance's disciplined little cousin — controlled instead of overwhelming.

- **Level:** Novice
- **Target/Range:** One character, Medium Range
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Target's Defense action).
- **Spell Power: 2**
- The Margin Scaler:
  - Margin 1–2: Impact = Margin + 2 (Spell Power). Caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, and the burn stings enough that the target suffers Disadvantage on their next Aggressor Strike roll as they favor the wound.

**Wreath of Embers** (Combat / Weapon Ignition)
The caster wraps their weapon — or their own knuckles — in a controlled, clinging flame that answers only to them.

- **Level:** Novice
- **Target/Range:** Self or one weapon, touch
- **Action Type:** Activation
- **Duration:** Scene
- **Resolution:** Unopposed Arcana vs. TN 8.
- The Effect: The wielder's Strikes carry the flame — unlike Wildfire Proliferation's raging blaze, this fire is disciplined and only burns what the wielder intends.
- The Margin Scaler:
  - Margin 0–2 (Messy): The weapon ignites and deals +1 Impact as fire for the scene, but the heat licks back — the wielder takes 1 Dissonant Stress.
  - Margin 3–4 (Clean): As above, no cost.
  - Margin 5+ (Massive): The flame burns hot enough to catch — the first enemy struck each round must also resist being set **Ablaze** (Iron Core) — the condition carries its own per-turn cost and its own clearance.

#### Adept

**Wildfire Proliferation** (Environmental / Escalation)
The caster hurls a fistful of white-hot embers that aggressively seek out oxygen and combustible material, turning the environment into a hazard.

- **Level:** Adept
- **Target/Range:** 10x10ft zone, Short Range
- **Action Type:** Activation
- **Duration:** Sustain (see The Channelling Rule — no Locked Stress cost; roll vs. TN 10 to maintain each Activation and on taking a Wound). **When the Sustain ends the zone stops being a spell:** it deals no further Impact and does not spread. Whatever is genuinely alight keeps burning as ordinary fire — light, smoke and difficult terrain at the GM's discretion — but with no Spell Power behind it.
- **Resolution:** Unopposed Arcana vs. TN 10.
- **Spell Power: 2**
- The Effect: Creates a 10x10 foot zone of raging fire. The casting Margin is fixed at the moment of casting. Any creature (friend or foe) starting their turn in the fire or moving through it automatically suffers Impact equal to that fixed Margin + Spell Power, for as long as the zone persists. The zone destroys any wooden cover or mundane foliage.
- The Margin Scaler:
  - Margin 0–2 (Messy): The fire is dangerously hungry. The zone forms, but the backdraft instantly singes the caster, dealing 1 Dissonant Stress to them and destroying one mundane, non-magical item in their inventory (like a rope or torch).
  - Margin 3–4 (Clean): The fire zone is perfectly contained to the 10x10 area.
  - Margin 5+ (Massive): At the start of the next combat round, the GM must expand the fire zone by 5 feet in every direction.

**Cauterize** (Utility / Brutal Triage)
The Pyromancer presses a glowing, superheated hand directly against an ally’s bleeding, open Wound to violently flash-fry the tissue closed.

- **Level:** Adept
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Instantaneous
- **Resolution:** Unopposed Arcana vs. TN 10. (Requires engaging the target in close range).

- The Effect: This is the Arcane alternative to a Priest's Triage. It clears exactly 1 Wound Slot from the target, allowing them to survive another hit, but it permanently reduces their Stress Limit by 1 (following standard Triage rules).

- The Margin Scaler:

- Margin 0–2 (Messy): The heat is poorly regulated. The Wound Slot is cleared, but the agony is unbearable. The target instantly suffers 2 Dissonant Stress, and the caster suffers 1 Dissonant Stress from the trauma of performing it.

- Margin 3–4 (Clean): The Wound is cleanly sealed. The target suffers 1 Dissonant Stress from the pain, but the bleeding stops.

- Margin 5+ (Massive): The sudden rush of adrenaline overrides the pain completely. The Wound is sealed, neither party takes Dissonant Stress, and the target immediately generates 1 Momentum from the sheer shock to their system.

#### Master

**The Furnace Lance** (Combat / Anti-Parry)
The caster exhales a concentrated, blinding beam of white-hot plasma that superheats the air and violently expands upon impact.

- **Level:** Master
- **Target/Range:** One character, Medium Range
- **Action Type:** Aggressor
- **Duration:** Instantaneous
- **Resolution:** Arcane Clash (Arcana vs. Target's Defense action).
- **Spell Power: 5**
- The Effect: You cannot cross blades with a blowtorch. The target completely loses the ability to use the Parry action against this Strike. They must rely on a thick shield (Block) or attempt to Dodge.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 5 (Spell Power). The raw heat causes the target to panic, forcing them to drop any wooden weapon or shield they are holding. The caster also takes 1 Dissonant Stress from the strain.
  - Margin 3+ (Clean): As above, and the target is **Ablaze** (Iron Core) — the condition carries its own per-turn cost, and the Regroup action is what puts them out.

## The Word on Domains;
Faith domains represent direct divine intervention powered by rigid devotion. Their domains give them an aura and a specific prayer manifestation.

## Faith Spells

### Common Prayers

**Healing / Stabilize** (Common Prayer)
A litany murmured over torn flesh, asking permission to undo what was done. Available to every Priest regardless of Domain — this is the spell several Domain Tags already assumed existed.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 2 Locked Stress
- **Target/Range:** Touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: Clears 1 Wound Slot. If the target is Incapacitated, also Stabilizes them and prevents further death checks.
- Fail: As Pass — the Prayer still occurs — and the Priest gains 1 Encroachment.
- Snake Eyes: The Wound clears, but convert this Prayer's Locked Stress cost into an equal number of direct Wounds on the Priest, per the Toll in Flesh rule, and reset the Priest's Encroachment to 0.

**Special Interactions:** A character cannot benefit from a second Healing-type Prayer in the same Scene. (This should be added to Iron Core's Golden Rules directly, rather than re-stated on every healing effect that comes along later.)

**Bless**
A short, pragmatic prayer settles over an ally, steadying their hand.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** One ally, touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: The target gains +1 to their next Clash roll, made within the next minute.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The bonus applies, but convert the Locked Stress cost into an equal point of direct Wound on the Priest, and reset the Priest's Encroachment to 0.

**Sanctuary**
The Priest plants their symbol and speaks a ward; for a moment, harm forgets the way in.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation / Reactor
- **Duration:** Flowing — no additional Locked Stress cost; the Priest rolls Tithe of Will vs. TN 10 at the start of each of their Activations to maintain it (per the Flowing rule in Embracing the Abyss). The ward instantly drops if the Priest takes a Wound or is knocked Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: The warded character gains SV 3 against the next hostile Strike or spell that targets them.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The ward still grants its SV, but convert the cost into a direct Wound on the Priest, and reset the Priest's Encroachment to 0.

**Commune**
The Priest closes their eyes and asks a single question of whatever is listening.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** Self
- **Action Type:** Activation (requires 1 minute)

**The Tithe Ladder:**
- Pass: The GM truthfully answers one yes/no question to the best of the Priest's patron's knowledge.
- Fail: As Pass, but the answer is deliberately vague or riddling, and the Priest gains 1 Encroachment.
- Snake Eyes: The question is answered, but convert the Locked Stress cost into a direct Wound — something noticed the asking — and reset the Priest's Encroachment to 0.

**Beacon**
A point of warm, steady light kindles at the Priest's word — never flickers, never gutters.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Self or one object, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: A 20ft radius of steady light. Cannot be extinguished by wind, water, or non-magical means for the duration.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The light manifests, but convert the cost into a direct Wound on the Priest, and reset the Priest's Encroachment to 0.

**Purify**
The Priest lays a hand on corrupted flesh and speaks a single word of refusal.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** One character, touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: Cures one disease, poison, or curse-based condition currently affecting the target.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The affliction clears, but convert the cost into a direct Wound on the Priest, and reset the Priest's Encroachment to 0.

**Steady Breath**
The Priest turns the prayer inward. Not every burden needs another set of hands.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Self
- **Action Type:** Free Action

**The Tithe Ladder:**
- Pass: Clears 1 point of Dissonant Stress.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The Stress still clears, but convert the Locked Stress cost into a direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Special Interactions:** Deliberately self-only and half of Elara's Comfort's yield — Mercy & Healing's Domain Tag is built entirely around extending relief to *others* at cost to yourself; this is the version any Priest can manage without that specialization.

**Ease the Mind**
No maxim, no cold philosophy — just a hand on the shoulder and a reminder that they're still standing.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** One ally, touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: Immediately clears the Fear or Terrified condition on the target. Does not grant immunity to reacquiring it.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The condition still clears, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Special Interactions:** The clear-only baseline version of Strategy's Iron Discipline and Death's Peaceful Repose, both of which add scene-long immunity on top of the clear — that immunity stays a Domain-committed benefit, not a Common one.

**The Unclouded Eye**
The Priest doesn't need a vision or a verdict. A lie just sounds different once you've spent a life listening for the truth.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** One character, Short Range
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: For the duration, the Priest instantly knows whenever the target states something they themselves believe to be false. This reveals a lie was told, not the truth behind it.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The insight still holds, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Special Interactions:** New ground, not a smaller version of anything — no Domain currently detects deception (Trickery's Counterfeit Soul *creates* a false front, it doesn't see through one).

**The Faithful's Shield**
Every god's devotee has one moment like this in them — the prayer that isn't for themselves.

- **Level:** Master
- **Resolution:** Tithe of Will — Faith vs. TN 12
- **Cost:** 3 Locked Stress
- **Target/Range:** Self and all allies within 15ft
- **Action Type:** Activation
- **Duration:** Until triggered, or end of Scene

**The Tithe Ladder:**
- Pass: Every ally in range (including the Priest) gains SV 3 against the next hit they individually take this scene — a one-time burst, not a sustained ward, and it doesn't stack or refresh.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The shield still forms for everyone, but convert the Locked Stress cost into direct Wounds, capped at 3 per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Special Interactions:** Shaped as a one-shot burst specifically so it doesn't compete with Sanctuary (single-target, sustained, Flowing) or the three Domain zone-Prayers (sustained AoE conditions) — this is the only Master Prayer in the game that's party-wide and single-use rather than either single-target or ongoing.

**The First Ward**
Before Sanctuary, there is this: the first prayer any acolyte learns to keep a blade from landing clean.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Target/Range:** Self
- **Action Type:** Activation / Reactor
- **Duration:** Flowing — no additional Locked Stress cost; the Priest rolls Tithe of Will vs. TN 8 at the start of each of their Activations to maintain it (per the Flowing rule in Embracing the Abyss). The ward instantly drops if the Priest takes a Wound or is knocked Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: The Priest gains SV 1 against the next hostile Strike or spell that targets them.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The ward still grants its SV, but convert the cost into a direct Wound on the Priest, and reset the Priest's Encroachment to 0.

**Special Interactions:** Right now Flowing only exists at Adept and Master — this is the Novice rung of the same ladder. Self-only and a third of Sanctuary's SV, so Sanctuary stays the clear upgrade once a Priest can afford it, not a sidegrade.

**The Unbroken Vow**
Purify answers the rot after it takes hold. This is the older, quieter prayer — the one that keeps it from ever finding purchase.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; the Priest rolls Tithe of Will vs. TN 10 at the start of each of their Activations to maintain it (per the Flowing rule in Embracing the Abyss). The ward instantly drops if the Priest takes a Wound or is knocked Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: For as long as maintained, the warded character cannot acquire a new disease, poison, or curse-based condition.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The ward still holds, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Special Interactions:** Same relationship to Purify that Shepherd the Dying has to Stabilize — same problem, opposite timing (prevent vs. cure), not a strictly-better version of either.

### 1. The Domain of Strategy (The Cult of the Iron Horizon)
- **The Paragon:** *Saint Senecus the Unyielding*
- **The Lore:** Senecus was an ancient military philosopher who held a doomed mountain pass against a horde of aberrant monstrous races. He taught that true victory isn't survival, but the stoic adherence to tactical duty regardless of the odds.
- **Flavor:** Polished iron shields, clean-cut discipline. Prayers are recited as short, pragmatic tactical maxims.
- **Domain Tag (Tactical Horizon):** Pass Faith check vs. TN 8 -> Grant 1 point of Momentum instead of personal benefit.
#### Novice Prayers

**Senecus's Stand**
A maxim recited under pressure — the line holds because the line was told to hold.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: For the rest of the scene, the target ignores the Overwhelming Force penalty (the automatic Stress from Blocking a Larger attacker) and the Swarm Bonus a group of enemies gains against them is capped at +1 instead of +2.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The effect applies, but convert the cost into a direct Wound.

**Iron Discipline**
There is no room for fear in the formation. Senecus didn't have room for it either.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation / Free Action

**The Tithe Ladder:**
- Pass: Immediately clears any Fear or Terrified condition on the target, and grants immunity to acquiring it again for the rest of the scene.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The condition clears, but convert the cost into a direct Wound.

**Pinning Volley**
Senecus never told his soldiers to charge into the open. He told them where to make the enemy afraid to.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** One enemy, Medium Range
- **Action Type:** Aggressor

**The Tithe Ladder:**
- Pass: The target immediately gains the Suppressed condition (per Iron Core). This bypasses saving throws entirely.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0. The suppression still applies.

> [!note] Designer's Note
> Suppressed — see Iron Core. Doesn't lock movement like Anchored or halve it like Rigor; instead it taxes anything that isn't holding the line and fighting back, which is Strategy's whole identity turned outward on the enemy.

**The Marching Order**
Senecus never fought a battle his army hadn't already survived getting to.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Self and the party, Short Range
- **Action Type:** Activation
- **Duration:** The remainder of the day's travel

**The Tithe Ladder:**
- Pass: The party organizes under tactical march discipline — ignore Stress and penalties from forced-march fatigue or difficult travel terrain for the remainder of the day's travel (per the Iron World Hazard Check rules).
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The discipline still holds, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**The Council Fire**
Senecus won more battles around the map table than he ever did in the field.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Self and the gathered party
- **Action Type:** Activation (requires a few minutes of dedicated planning, outside combat)

**The Tithe Ladder:**
- Pass: The party settles on a specific plan for an upcoming scene. The first check any one ally makes that directly executes that plan is made with Advantage.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The Advantage still applies, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Special Interactions:** Rewards the table for actually planning out loud rather than winging it — the Advantage is locked to whatever plan gets stated, so it can't be claimed retroactively.

#### Adept Prayers

**Tactical Reading**
The Priest reads the battlefield the way Senecus read the pass — not what the enemy is doing, but what they intend to.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** One Elite or Boss, Short Range
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: The GM must truthfully reveal the Momentum cost of that enemy's next ability before it's declared.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The reading lands, but convert the cost into a direct Wound.

**Marked for the Line**
Senecus didn't win battles with heroes. He won them by making sure everyone hit the same spot at the same time.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** One enemy, Medium Range
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: The target is marked. The first ally (other than the Priest) to land a hit on the marked target each round generates 1 Momentum.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, and reset the Priest's Encroachment to 0. The mark still applies.

> [!note] Designer's Note
> Ties directly into the Domain Tag (Tactical Horizon), which already deals in Momentum — this gives Strategy a second, distinct hook into that resource instead of a one-off.

**The Unbroken Watch**
Senecus never slept on watch. He didn't trust the enemy to be honest about when they'd attack.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Target/Range:** Self and the camp, Short Range
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; outside combat, the Priest rolls Tithe of Will vs. TN 10 once per hour of rest to maintain it, rather than per Activation (the Flowing rule as written assumes a combat cadence — see Embracing the Abyss; every non-combat Flowing Prayer below uses this same hourly/per-scene-beat substitution). The ward instantly drops if the Priest takes a Wound or is knocked Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: The camp cannot be Surprised while the ward holds — anyone or anything approaching triggers a silent, instant alert to the Priest regardless of its Stealth.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The watch still holds, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Senecus's Vantage**
Senecus read a battlefield the way other men read a room — before he ever set foot in it.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Target/Range:** Self
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; re-rolled once per scene-beat outside combat rather than per Activation (see The Unbroken Watch, above). Drops on a Wound or Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: For as long as maintained, the Priest reads any location they enter like a battlefield map — Advantage on checks made to identify chokepoints, ambush sites, or the best defensible position.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The reading still holds, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Special Interactions:** The exploration-and-dungeon-crawling counterpart to Tactical Reading's in-combat version — same eye, aimed at a room instead of a Boss.

#### Master Prayers

**The Unbreakable Line**
The formation does not break. It was never going to break. Senecus is very clear on this point.

- **Level:** Master
- **Cost:** 3 Locked Stress
- **Target/Range:** Self and all allies within 15ft
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: For the duration, allies in range cannot be knocked Prone or forcibly Pushed by an enemy Strike or spell.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The line holds, but convert the cost into direct Wounds on the Priest.

**Senecus's Wall**
There was no clever maneuver. Senecus just told them to stand, and the wall of shields did the rest.

- **Level:** Master
- **Resolution:** Tithe of Will — Faith vs. TN 12
- **Cost:** 3 Locked Stress
- **Target/Range:** 20ft radius, Short Range
- **Action Type:** Activation
- **Duration:** Scene, or until the Priest is Incapacitated or leaves the zone

**The Tithe Ladder:**
- Pass: Every enemy in the radius immediately gains the Suppressed condition (per Iron Core). This bypasses saving throws entirely.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 3 Locked Stress into 3 direct Wounds, and reset the Priest's Encroachment to 0. The suppression still applies.

> [!note] Designer's Note
> Costed and scoped like Long Winter and Sovereign Tide — same "guaranteed AoE condition, no save" power level as the other Master zone Prayers. It is consistent with existing precedent rather than a new power ceiling.

### 2. The Domain of Trickery (The Cult of the Crooked Coin)
- **The Paragon:** *Corvo's Folly (The Grinning Prophet)*
- **The Lore:** Corvo wasn't a holy man; he was a legendary cynic and smuggler who realized the ancient bureaucratic laws of the old empire were a joke, and successfully counterfeited the royal treasury into bankruptcy. The Syndicate reveres him as the patron of outsmarting rigged systems.
- **Flavor:** Loaded dice amulets, mismatched clothes. Prayers are murmured riddles, jokes about authority, and localized distortions of luck.
- **Domain Tag (Fickle Fate):** Ally rolls Fumble -> Spend 1 Stress as Reaction to turn it into a standard failure.
#### Novice Prayers

**Beginner's Luck**
The house always wins — except for the one hand Corvo decides it doesn't.

- **Level:** Novice
- **Cost:** 1 Locked Stress
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation / Free Action

**The Tithe Ladder:**
- Pass: The target gains Advantage on their next Clash roll, made within the next minute.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The Advantage applies, but convert the cost into a direct Wound.

**The Crooked Coin**

- **Level:** Novice
- **Cost:** 1 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Target/Range:** Self or one ally, Short Range
- **Action Type:** Free Reaction (declared when an enemy targets the Priest or an ally within Short Range with an attack)

**The Tithe Ladder:**
- Pass: The Priest bends the probability of the moment. The attacking enemy automatically suffers Disadvantage on their Clash roll.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, reset the Priest's Encroachment to 0.

**Fool's Errand**

- **Level:** Novice
- **Cost:** 1 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Target/Range:** Medium Range
- **Action Type:** Activation
- **Duration:** Scene, or until physically disrupted

**The Tithe Ladder:**
- Pass: The Priest manifests a localized sensory illusion (sight and sound). Out of combat, this mimics a shouting guard, a false wall, or approaching reinforcements. In combat, it instead creates a 3x3 square zone of Heavily Obscured terrain — enemies striking through or into it suffer Disadvantage, and targets inside gain +2 to Defense (per the Environmental rules).
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, reset the Priest's Encroachment to 0.

**A Word in Passing**
Corvo's oldest trick: never lie. Just let people finish the story themselves.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** One NPC, Short Range
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: Plants one false but entirely plausible impression or rumor in the target's mind — they genuinely believe they arrived at it themselves.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The impression still takes, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

#### Adept Prayers

**The Long Con**
A favor planted now, called in later, when it does the most damage.

- **Level:** Adept
- **Cost:** 2 Locked Stress
- **Target/Range:** One enemy, Short Range
- **Action Type:** Activation
- **Duration:** Until triggered, or end of Scene

**The Tithe Ladder:**
- Pass: Mark one enemy. The next time that enemy fails a Clash this scene, they suffer 2 additional Impact as the planted ill luck calls itself in.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The mark is set, but convert the cost into a direct Wound on the Priest immediately.

**Corvo's Step**

- **Level:** Adept
- **Cost:** 2 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Target/Range:** Self and one willing ally or unattended object of similar size, Medium Range
- **Action Type:** Move Action

**The Tithe Ladder:**
- Pass: The Priest steps briefly outside conventional reality, instantly swapping positions with the target. Because this is a fold in space rather than physical movement, it does not provoke Engagement attacks. If the Priest swaps with an ally actively being targeted by an attack, the Priest becomes the new target of that Clash.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, reset the Priest's Encroachment to 0. The swap still occurs.

**Counterfeit Soul**
Corvo didn't fight the empire's laws — he forged better ones. The Priest forges a face.

- **Level:** Adept
- **Cost:** 2 Locked Stress
- **Target/Range:** Self
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: The Priest's face, voice, and bearing convincingly become someone else's. Anyone suspicious rolls Notice against the Priest's original casting roll to see through it.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The disguise holds, but convert the cost into a direct Wound.

**The Long Game**
The house always wins because the house never stops playing, even between hands.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Target/Range:** Self
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; re-rolled once per scene-beat outside combat rather than per Activation (see The Unbroken Watch, Domain of Strategy). Drops instantly if the Priest is caught in a directly-contradicted lie, takes a Wound, or is knocked Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: Advantage on Influence checks made to deceive, for as long as maintained.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The advantage still applies, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

#### Master Prayers

**The House Always Wins**

- **Level:** Master
- **Cost:** 4 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 12
- **Target/Range:** One enemy, line of sight
- **Action Type:** Free Reaction (triggered immediately after an enemy resolves an action)

**The Tithe Ladder:**
- Pass: The GM must completely undo the enemy's just-resolved action. All Wounds inflicted are healed, all Conditions applied are removed, and the enemy's turn immediately ends. Any Momentum the enemy spent to trigger the ability is not refunded.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the Locked Stress cost into direct Wounds, capped at 3 per Toll in Flesh, reset the Priest's Encroachment to 0. The undo still occurs.

**Loaded Dice**
The house always wins. Sometimes it just likes to remind the table why.

- **Level:** Master
- **Resolution:** Tithe of Will — Faith vs. TN 12
- **Cost:** 4 Locked Stress
- **Target/Range:** One enemy's triggering roll
- **Action Type:** Free Reaction (triggered immediately after an enemy rolls 2d6 for any check, but before the GM declares the outcome)

**The Tithe Ladder:**
- Pass: The roll is retroactively treated as a Natural 2 (double 1s) — an automatic Catastrophic Failure per the Snake Eyes Rule, regardless of the enemy's Attributes, Skills, or Gear modifiers. The GM applies the standard Snake Eyes consequence for that context.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the Locked Stress cost into direct Wounds, capped at 3 per Toll in Flesh, and reset the Priest's Encroachment to 0. The curse still lands.

*Scales of Aurelius overrides this Spell.
### 3. The Domain of Law (The Cult of the Zenith)
- **The Paragon:** *Aurelius the Architect*
- **The Lore:** Aurelius was an ancient, brutal warlord who united the early human tribes by writing the first Meditations on Law—a rigid, uncompromising text that dictated society must be ordered, and chaos must be purged by fire. He is the ultimate idol of the High Quarter.
- **Flavor:** Heavy comet pendants, unyielding loud booming scripture. Prayers are backed by thunderclaps and searing white light.
- **Domain Tag (Smite Corruption):** Targeting Undead, Daemons, or Mutants treats the target's Wound Threshold [T] as 1 point lower.

#### Novice Prayers

**The Architect's Decree**

- **Level:** Novice
- **Cost:** 1 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Target/Range:** One enemy, Short Range
- **Action Type:** Free Reaction (declared when an enemy attempts to Move, or attempts to leave a Threat Zone)

**The Tithe Ladder:**
- Pass: The target immediately suffers the Anchored condition. Their movement speed instantly drops to 0 for the remainder of the round, completely halting their current Move Action in its tracks.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, per the Toll in Flesh rule, and reset the Priest's Encroachment to 0.

> [!note] Designer's Note
> This is elite battlefield control. It bypasses saving throws entirely — the target stops moving regardless of the roll. What the roll determines is whether that certainty came cheap (Pass) or whether the Priest is quietly running up a tab with something that isn't them (Fail/Snake Eyes).

**Sanctuary of the Zenith**

- **Level:** Novice
- **Cost:** 1 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Target/Range:** A 3x3 square zone, centered on self or within Short Range
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: The zone of Absolute Order forms. For the rest of the Scene, no character (ally or enemy) can gain Advantage or Disadvantage on any roll while inside it. All circumstantial modifiers (Flanking, Obscured terrain, Prone penalties, etc.) are completely suppressed within the zone.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, reset the Priest's Encroachment to 0.

> [!note] Designer's Note
> This forces the core 2d6 + Attribute + Skill math to be played completely flat. If a Boss relies on stacked passive Advantages, or a pack of wolves relies on Flanking, the Priest shuts down their mechanical engine — the Tithe roll never touches whether that shutdown happens, only what it costs the Priest personally.

**Writ of Protection**
Aurelius wrote the law before the sword was drawn. The sword simply hasn't caught up yet.

- **Level:** Novice
- **Cost:** 1 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Target/Range:** One ally, Short Range
- **Action Type:** Free Reaction (declared the instant an enemy declares an Aggressor action targeting that ally)

**The Tithe Ladder:**
- Pass: The declared attack is immediately forbidden from targeting the warded ally. The attacker must redirect to a different legal target in range, or the action is wasted if none exists. This bypasses saving throws entirely — it isn't a dodge, the attack simply cannot land on this target.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, and reset the Priest's Encroachment to 0.

> [!note] Designer's Note
> Fills a gap Law otherwise leaves open — a single-target protection Prayer. Not making an ally harder to hit, but making them briefly illegal to target at all.

**The Binding Oath**
Aurelius wrote that a promise is a contract whether or not it's written down. He simply made sure the universe agreed with him.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** One willing character, touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: The target's spoken promise is bound. If they knowingly break its letter, they immediately suffer 2 Dissonant Stress.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The oath still binds, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Aurelius's Ledger**
Aurelius trusted ink over memory, and memory over any man's word — including his own.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Self
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: For the duration, the Priest perfectly recalls, word-for-word, every promise, contract, or sworn statement made in their presence — recitable later as if read from a written record.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The recall still holds, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Special Interactions:** Pure record-keeping, not lie-detection — pairs with Writ of Testimony (which tells you if a statement is true) rather than duplicating it; this just makes sure nobody can later dispute what was actually said.

#### Adept Prayers

**Chains of Mandate**

- **Level:** Adept
- **Cost:** 2 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Target/Range:** One enemy, Medium Range
- **Action Type:** Move Action
- **Duration:** 3 rounds

**The Tithe Ladder:**
- Pass: The Priest declares one specific mechanical Trait from the target's Bestiary stat block (e.g., Plated, Resilient, Cleave). That Trait is completely disabled for the next 3 combat rounds.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, reset the Priest's Encroachment to 0.

> [!note] Designer's Note
> This directly hooks into the Dynamic Trait Manifest — Bosses and Elites derive their threat from these Traits. Paying 2 Locked Stress to turn off "Resilient" right before the Fighter lands a Greatsword blow is a deeply satisfying tactical loop, backed by the same cost-not-outcome uncertainty every other Prayer carries.

**Aurelius's Judgment**
The verdict is entered. The body may keep fighting; the law has already decided it will not be saved.

- **Level:** Adept
- **Cost:** 2 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Target/Range:** One enemy, Short Range
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: The target immediately gains the Cursed condition (per Iron Core) for the duration — healing magic has no effect on them, and alchemical draughts provide no benefit. This bypasses saving throws entirely.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, and reset the Priest's Encroachment to 0.

> [!note] Designer's Note
> Reuses the existing Cursed condition rather than inventing a new debuff — turns Law into the Domain that shuts down an enemy healer's whole job on a priority target.

**Writ of Testimony**
Aurelius never needed to threaten anyone. The truth simply stopped having anywhere else to hide.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Target/Range:** One character under active questioning, Short Range
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; re-rolled once per scene-beat outside combat rather than per Activation (see The Unbroken Watch, Domain of Strategy). Drops on a Wound or Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: The Priest knows with certainty whether each sworn statement the target makes is true, for as long as maintained.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The certainty still holds, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Special Interactions:** Pairs naturally with The Binding Oath — a target already bound by it has a real incentive not to test this.

**The Zenith's Peace**
Aurelius never needed a sword drawn to win an argument. He simply made sure no one else's could be either.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Target/Range:** A defined space (a room, hall, or campsite), Short Range
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; re-rolled once per scene-beat outside combat rather than per Activation (see The Unbroken Watch, Domain of Strategy). Drops on a Wound or Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: For as long as maintained, no character inside the warded space can draw a weapon or declare an Aggressor action without first passing a Resolve check — the weight of absolute order makes violence feel like a genuine transgression.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The ward still holds, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Special Interactions:** A negotiation and sanctuary tool, not a combat-ender — a determined attacker can still push through the Resolve check, this just makes the first move cost something.

#### Master Prayers

**The Scales of Aurelius**

- **Level:** Master
- **Cost:** 4 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 12
- **Target/Range:** The triggering roll, Cannot target the Tithe of Will roll of the Prayer being cast to trigger it.
- **Action Type:** Free Reaction (triggered immediately after ANY character or enemy rolls 2d6, but before the GM declares the Impact or outcome)

**The Tithe Ladder:**
- Pass: The rolled dice are completely ignored. The roll is treated as if exactly a 7 was rolled (7 + Attribute + Skill). This explicitly overrides and prevents both Fates' Bounty (double 6s) and Snake Eyes (double 1s) on the triggering roll.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the Locked Stress cost into direct Wounds, capped at 3 per the Toll in Flesh rule, and reset the Priest's Encroachment to 0. The override still occurs regardless.

> [!note] Designer's Note
> This is the absolute peak of the Faith philosophy — Certainty vs. Volatility. For 4 Locked Stress, the Priest can look at a Boss rolling double 6s for a team-wipe and say "No, you rolled a 7." The Priest's own Tithe roll never risks the override failing — Faith doesn't work that way — it only risks what the entity extracts in payment.

**Banish** (Domain of Law — exclusive)
Unchanged — already conformant. Included here for completeness since it's Law's other Master Prayer:

- **Level:** Master
- **Cost:** 3 Locked Stress
- **Resolution:** Tithe of Will, opposed by the target's Resolve
- **Target/Range:** One supernatural entity, Short Range
- **Action Type:** Aggressor

**The Tithe Ladder:**
- Pass: If the Priest also wins the opposed roll, the target suffers 3 Stress and is banished if this exceeds their Stress Limit. If the Priest loses the opposed roll, the Prayer still occurs but produces no effect beyond a flash of light.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the Locked Stress cost into direct Wounds, reset Encroachment to 0.

### 4. The Domain of Death (The Cult of the Ashen Veil)
- **The Paragon:** *Vael the Mute*
- **The Lore:** Vael was a grave-keeper who survived the horrific aftermath of the pre-sundering wars. He taught a philosophy of absolute pessimism—that life is merely a loud, painful interruption of the peaceful void, and death is the ultimate mercy to be respected, not feared.
- **Flavor:** Black hooded raiment, stark quiet expressions. Prayers manifest as chilling quietude and falling feathers.
- **Domain Tag (Rest in Peace):** Cast *Stabilize* -> Target becomes completely immune to further Stress gains from mental shock or supernatural dread for the scene.

#### Novice Prayers

**Peaceful Repose**
Vael doesn't guard you from dying. He guards you from being afraid of it.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: The target's mind settles into the quiet Vael taught. For the duration, they're immune to the Fear and Terrified conditions.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Special Interactions:** Distinct from the Rest in Peace Domain Tag — Rest in Peace only fires off a Stabilize cast; this can be cast proactively on anyone, anytime.

**The Quiet Truth**
The Priest doesn't summon a vision. They just let the target see, for one second, exactly how small and mortal they are.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Tithe Ladder:**
- Pass: The target must pass a Resolve check (TN 8) or gain the Fear condition, fixed on the Priest.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0. The target still makes their Resolve check.

**The Last Bell**
Somewhere close, a bell only Vael's faithful can hear has begun to toll.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Self, 60ft radius
- **Action Type:** Activation
- **Duration:** Instantaneous

**The Tithe Ladder:**
- Pass: The Priest instantly knows the number, rough direction, and severity (Incapacitated / Bleeding Out / dead within the hour) of every dying or recently-dead creature in range — friend, foe, or stranger.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0. The knowledge is still granted.

**Special Interactions:** Pairs directly with Shepherd the Dying and Vael's Mercy — it's the spell that tells the Priest where to point the other two.

**Vael's Confession**
Vael's answer to a Necromancer isn't always a duel. Sometimes it's just a better question, asked first.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** One corpse dead within the last hour, touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: The Priest may ask the remains one final yes/no or short-answer question, answered honestly.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The dead still answer, but convert the Locked Stress cost into a direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Special Interactions:** The information-gathering half of Last Rites, unbundled and made accessible at Novice tier — Last Rites' permanent anti-reanimation protection stays its own Adept-exclusive niche.

**The Mourner's Rite**
Vael never taught his faithful to stop grieving. He taught them to finish it.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Self and all gathered mourners, Short Range
- **Action Type:** Activation (requires a proper funeral or vigil for the dead)

**The Tithe Ladder:**
- Pass: Every mourner in attendance clears 1 point of Dissonant Stress tied specifically to grief or loss for the dead being honored.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The Stress still clears for everyone, but convert the Locked Stress cost into a direct Wound on the Priest, and reset the Priest's Encroachment to 0.

**Special Interactions:** The only party-wide Stress relief anywhere in the game that isn't self-only or single-target — gated behind an actual funeral taking place, not castable on demand.

#### Adept Prayers

**Last Rites**
Vael's answer to a Necromancer isn't a duel. It's getting there first.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** One corpse, touch
- **Action Type:** Activation (requires a few uninterrupted minutes — cannot be cast mid-Clash)
- **Duration:** Permanent

**The Tithe Ladder:**
- Pass: The rite settles permanently over the body. This corpse can never be reanimated by Zombie, Puppet, or any spell that requires "a corpse within reach" — the protection cannot be dispelled by the Necromancer. If the character died within the last hour, the Priest may also ask the remains one final yes/no question, answered honestly.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, per Toll in Flesh, and reset the Priest's Encroachment to 0. The rite still takes.

**Special Interactions:** Death's dedicated counter to the Necromancy Spellbook — a Priest who sweeps a graveyard or battlefield ahead of time denies an enemy Necromancer their raw material entirely.

**Shepherd the Dying**
Vael doesn't fight death. He negotiates with it, on your behalf, before you can.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** One ally, Short Range
- **Action Type:** Reactor (declared the instant the target becomes Incapacitated, before any Bleed-Out check is rolled)

**The Tithe Ladder:**
- Pass: The target is instantly Stabilized (per Iron Core's Bleed-Out rules) — no roll needed.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, per Toll in Flesh, and reset the Priest's Encroachment to 0. The target is still Stabilized.

**Special Interactions:** Doesn't replace Triage or the Common Prayer Stabilize — differentiated by timing (Reactor, free of the action economy) rather than by being strictly stronger.

**The Patient Dead**
Vael's whole philosophy in one ward: the dead have earned their rest, and the Priest intends to see they get it.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Target/Range:** A grave site or the recently fallen, Short Range
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; re-rolled once per hour outside combat rather than per Activation (see The Unbroken Watch, Domain of Strategy). Drops on a Wound or Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: The dead within the zone go undisturbed — minor undead, vermin, and grave-robbers alike are turned away from the site while the ward holds.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The ward still holds, but convert the Locked Stress cost into a direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Vael's Crossing**
The dead don't always know they're finished. Vael's faithful are the ones who tell them, gently, that they are.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** One lingering spirit or restless dead, Short Range
- **Action Type:** Activation (requires a few uninterrupted minutes of communion)

**The Tithe Ladder:**
- Pass: The spirit may speak freely with the Priest, as Vael's Confession allows with the freshly dead — and if willing, the Priest can guide it to a peaceful crossing, ending its unnatural lingering for good.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The crossing still occurs, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Special Interactions:** Vael's Confession's counterpart for spirits rather than corpses — this is about the incorporeal dead who never left, not the freshly fallen.

#### Master Prayers

**Vael's Mercy**
There's no violence in it. A hand on the brow, a held breath, and it's over. Turned toward a target who still has the strength to resist, the same mercy becomes a verdict.

- **Level:** Master
- **Resolution:** Tithe of Will — Faith vs. TN 12
- **Cost:** 3 Locked Stress
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor (against a living target) or Activation/Reactor (against an already-Incapacitated target)

**The Tithe Ladder:**
- Pass, against an Incapacitated target: the target dies instantly and without pain. Bypasses the mundane Coup de Grâce entirely — no attack roll, no Impact, no Death Mark. Usable on a willing, Incapacitated ally to spare them a Bleed-Out fight the party can't win, or on an Incapacitated enemy to end them outright.
- Pass, against a living, conscious target of Elite tier or below: the target must pass a Resolve check (TN 12) or immediately become Incapacitated (per Iron Core's Incapacitated condition), regardless of remaining Wound Slots. **This cannot target Boss-tier enemies under any circumstance.**
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 3 Locked Stress into 3 direct Wounds, per Toll in Flesh, and reset the Priest's Encroachment to 0. The effect still occurs.

**Special Interactions:** A living target Incapacitated this way still enters the normal Bleed-Out track and can be saved by Triage or Stabilize — this is a removal-from-the-fight tool against a resisting target, not a second unconditional execution. Explicitly Boss-exempt.

**The Long Silence**
Every sound dies at the edge of the zone. Everyone inside feels, all at once, exactly how alone they are.

- **Level:** Master
- **Resolution:** Tithe of Will — Faith vs. TN 12
- **Cost:** 3 Locked Stress
- **Target/Range:** 20ft radius, centered on self
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; the Priest rolls Tithe of Will vs. TN 12 at the start of each of their Activations to maintain it (per the Flowing rule in Embracing the Abyss). The zone instantly drops if the Priest takes a Wound or is knocked Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: Every enemy that starts its turn in the zone must pass a Resolve check (TN 12) or gain Fear, fixed on the Priest. Allies inside the zone gain Peaceful Repose's Fear and Terrified immunity for as long as they remain there.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 3 Locked Stress into 3 direct Wounds, per Toll in Flesh, and reset the Priest's Encroachment to 0. The zone still forms.

### 5. The Domain of Winter & Wilds (The Cult of the Rime-Fang)
- **The Paragon:** *Kaelen the Survivor*
- **The Lore:** A tribal matriarch from the deepest winters of the north who supposedly hunted a primordial winter-drake with nothing but an iron spear and her bare teeth. She embodies the raw, animalistic grit required to survive when civilization fails.
- **Flavor:** Heavy white wolf pelts, frosted breath. Prayers manifest as freezing howling wind and ice.
- **Domain Tag (Chilling Frost):** Cast offensive prayer -> Target is numbed. They cannot Move next turn unless they take 1 Dissonant Stress to snap their frozen muscles free.
#### Novice Prayers

**Rime-Fang's Bite**

- **Level:** Novice
- **Cost:** 2 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Target/Range:** One target, Short Range
- **Action Type:** Aggressor

**The Tithe Ladder:**
- **Pass:** Target must pass an **Athletics check (TN 8)** or suffer 2 Dissonant Stress as the cold bites deep, and gains Rigor as it seizes their joints.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, per Toll in Flesh, and reset Encroachment to 0.

**Wolf's Ward**

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Touch
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: Target ignores Stress and penalties from extreme environmental hazards (per the Iron World Hazard Check rules) for the scene.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, reset Encroachment to 0.

**Howl of the Rime-Fang**

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 2 Locked Stress
- **Target/Range:** 15ft radius, Short Range
- **Action Type:** Aggressor

**The Tithe Ladder:**
- Pass: Every enemy in the radius must pass a Resolve check (TN 8) or gain the Fear condition as the wolf-spirit's cry breaks their nerve.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, reset Encroachment to 0.

**Frostbitten Ground**

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** 10x10ft area, Short Range
- **Action Type:** Activation
- **Duration:** Until the encounter ends or the ice is magically cleared

**The Tithe Ladder:**
- Pass: The ground glazes with black ice. The area becomes difficult terrain (per the Iron World Environmental rules).
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, reset Encroachment to 0.

**Kaelen's Eye**

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Self
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: The Priest reads the wild the way Kaelen did — broken branches, frost patterns, the direction of a fleeing breath. Gain Advantage on Survival or Notice checks to track a specific creature or navigate harsh terrain.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, reset Encroachment to 0.

**Kaelen's Larder**
Kaelen never wasted a kill. The winter punished anyone who did.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Touch, requires foraged or hunted material on hand
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: Preserves the material against spoilage indefinitely — immediately steps the Community Supply Die up one tier, the same benefit as Scavenge and Cannibalize.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The preservation still takes, but convert the Locked Stress cost into a direct Wound, reset Encroachment to 0.

#### Adept Prayers

**Winter's Endurance**

- **Level:** Adept
- **Cost:** 2 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Target/Range:** Touch
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: The target's body remembers the endurance of the old hunters. If their Stress Limit is maxed out by an environmental Hazard specifically, the excess is simply lost rather than converting to Wounds, for the rest of the scene.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, reset Encroachment to 0.

**Rime-Fang's Vigil**

- **Level:** Adept
- **Cost:** 2 Locked Stress
- **Resolution:** No roll — paid directly in Locked Stress (Faith Reaction)
- **Target/Range:** Self or one ally, Short Range
- **Action Type:** Reactor (declared the instant the target is targeted by an Aggressor Strike)
- **Effect:** The old wolf-spirit's hide answers as a ward of packed ice and matted fur. The target gains +4 Shield Value (SV) as a Front-End Reducer against that single incoming attack.

**Call of the Rime-Fang**

- **Level:** Adept
- **Cost:** 2 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Target/Range:** Self, 10ft
- **Action Type:** Activation
- **Duration:** Scene, or until the spirit-wolf is slain

**The Tithe Ladder:**
- Pass: A translucent, frost-limned wolf spirit erupts from the Priest's shadow and fights at their side. Treat it as an NPC ally (Wound Threshold 5, 1 Wound Slot, Prowess +1 | Melee +1, no Stress Limit — as a spirit, it cannot Break or flee) acting on the Priest's Activation.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, reset Encroachment to 0. If summoned, the spirit-wolf instantly dissipates.

**The Unbroken Trail**
Kaelen never got lost. She said the land only looks confusing to someone who hasn't decided to listen to it yet.

- **Level:** Adept
- **Cost:** 2 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Target/Range:** Self
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; re-rolled once per hour of travel outside combat rather than per Activation (see The Unbroken Watch, Domain of Strategy). Drops on a Wound or Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: The party cannot lose the trail the Priest is following — Advantage on Survival or Navigation checks to stay the course, even through difficult conditions.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The trail still holds, but convert the Locked Stress cost into a direct Wound, reset Encroachment to 0.

#### Master Prayers

**The Hunter's Reckoning**

- **Level:** Master
- **Cost:** 4 Locked Stress
- **Resolution:** Tithe of Will — Faith vs. TN 12
- **Target/Range:** Self
- **Action Type:** Free Reaction (declared immediately after the Priest wins an Aggressor Clash against a creature of Scale +1 or higher, or an Elite/Boss-tier enemy of any Scale)

**The Tithe Ladder:**
- Pass: Kaelen's grit answers the call. The just-resolved Clash automatically inflicts a Minor Wound on the target, even if the calculated Impact fell short of their Wound Threshold.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the Locked Stress cost into direct Wounds, capped at 3 per Toll in Flesh, and reset Encroachment to 0. The Wound is still inflicted regardless.

**The Long Winter**

- **Level:** Master
- **Resolution:** Tithe of Will — Faith vs. TN 12
- **Cost:** 3 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Target/Range:** 30ft radius, centered on self
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; the Priest rolls Tithe of Will vs. TN 12 at the start of each of their Activations to maintain it (per the Flowing rule in Embracing the Abyss). The zone instantly drops if the Priest takes a Wound or is knocked Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: Kaelen's endless winter descends. The zone becomes Heavily Obscured (per the Environmental rules), and every enemy that ends its turn inside suffers 1 Dissonant Stress from the bone-deep cold. Allies are unaffected by the cold.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 3 Locked Stress into 3 direct Wounds, reset Encroachment to 0. The blizzard still forms.

### 6. The Domain of Mercy & Healing (The Cult of the Weeping Martyr)
- **The Paragon:** *Mother Elara of the Mud*
- **The Lore:** During a massive plague in the early days of Port Nevarellon, Elara was a destitute woman who walked into the quarantine zones. It is said she systematically absorbed the rot from the dying into her own body, enduring unimaginable agony so others could live.
- **Flavor:** Plain white habits, dove pendants. Prayers manifest as golden tears and warm glowing auras.
- **Domain Tag (Pure Martyrdom):** Cast *Healing/Stabilize* -> Take 1 Locked Stress yourself to clear an additional Wound Slot on the target.
#### Novice Prayers

**Bolster the Faithful**

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: Target gains the Blessed condition.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Wrathful Light**

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 2 Locked Stress
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Tithe Ladder:**
- Pass: Target must pass a **Resolve check (TN 8)** or suffer 2 Dissonant Stress as holy light burns through them; if the target is Undead/Daemon/Mutant, they also gain Fear.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Elara's Comfort**
A hand on the shoulder, and for one moment, the weight isn't yours alone.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** One ally, touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: Target clears 2 points of Dissonant Stress.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0. The Stress still clears.

**Elara's Vigil**
Elara never rushed a healing. She said the body forgives slowly, and it deserves the time.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Touch, requires uninterrupted downtime (a Short or Long Rest)
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: Tending the target this way halves the time their next natural Wound-Slot recovery takes, or auto-succeeds a downtime Medicine check made on their behalf.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The care still takes, but convert the Locked Stress cost into a direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Tend the Many**
Elara didn't heal one plague victim at a time. She didn't have that luxury, and neither do her faithful.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** A group of the sick or wounded, Short Range
- **Action Type:** Activation (requires an hour of tending)

**The Tithe Ladder:**
- Pass: The Priest moves among the many. A mundane (non-magical) disease or plague stops spreading through the group for the day, and none in their care will die of it before the Priest can return.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The care still holds, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Special Interactions:** The communal counterpart to Purify — Purify cures one afflicted individual outright, this holds a whole group's line against a spreading sickness without curing anyone completely.

#### Adept Prayers

**Elara's Burden**
Mother Elara didn't cure the plague. She simply asked it to move house.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** One ally, touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: Transfer 1 Wound from the target to the Priest — the target's Wound Slot clears, and the Priest immediately suffers 1 Wound in its place.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The transfer still occurs, but convert the 2 Locked Stress into 2 additional direct Wounds on the Priest, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**The Weeping Communion**
She walked into the quarantine zones so no one else would have to walk in alone.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** Self and all allies within 15ft
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: Every ally in range gains the Blessed condition for the scene.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, per Toll in Flesh, and reset the Priest's Encroachment to 0. The Blessing still applies.

**The Martyr's Watch**
Elara walked into the quarantine zones and didn't leave until the last patient did. This is the same promise, made smaller.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Target/Range:** One dying or gravely ill character outside combat, touch
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; re-rolled once per hour of vigil outside combat rather than per Activation (see The Unbroken Watch, Domain of Strategy). Drops if the Priest takes a Wound or is knocked Prone — someone has to protect the vigil for it to hold.

**The Tithe Ladder:**
- Pass: The patient's condition cannot worsen while the Priest keeps watch over them.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The vigil still holds, but convert the Locked Stress cost into a direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Elara's Yoke**
A hand on the shoulder isn't always enough. Sometimes Elara just took the weight outright.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** One ally, touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: Transfer up to 3 points of Dissonant Stress from the target to the Priest — the target clears that Stress, and the Priest takes it on directly.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The transfer still occurs, but convert the 2 Locked Stress into 2 additional direct Wounds on the Priest, and reset the Priest's Encroachment to 0.

**Special Interactions:** Elara's Burden's mirror for Stress instead of Wounds — same self-sacrifice shape, aimed at trauma rather than injury.

#### Master Prayers

**Resurrection**

- **Level:** Master
- **Resolution:** Tithe of Will — Faith vs. TN 12 (requires a full hour of ritual; target must have died within 24 hours)
- **Cost:** 8 Locked Stress
- **Target/Range:** Touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: The target returns to life with 3 Wounds and maximum Stress. The Priest pays the Locked Stress cost — this will almost certainly exceed their Stress Limit, converting the excess into Wounds per the Death Spiral rule. This Prayer is built to cost the caster something severe, not "likely" to — say so plainly to the table before they commit.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the entire Locked Stress cost into direct Wounds, per the Toll in Flesh rule — at 8 points, this is unsurvivable for a Priest who isn't already braced for it — and reset the Priest's Encroachment to 0.

**Special Interactions:** Soul Scar — the resurrected character permanently loses 1 point of Will as the price of their return.

**Miraculous Intervention**
The gods reach down and aggressively deny reality.

- **Level:** Master
- **Resolution:** Tithe of Will — Faith vs. TN 12
- **Cost:** 4 Locked Stress
- **Target/Range:** One ally, line of sight
- **Action Type:** Reactor (declared the instant that ally would suffer a Wound that would kill or Incapacitate them)

**The Tithe Ladder:**
- Pass: The blow never happened. The triggering Wound is completely negated — the ally takes no Wound from it.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the Locked Stress cost into direct Wounds, capped at 3 per Toll in Flesh, and reset the Priest's Encroachment to 0. The negation still occurs regardless.

### 7. The Domain of the Sea & Storms (The Tidespoken Clergy)
- **The Paragon:** *Thalass's Omen*
- **The Lore:** Thalass was not a person, but an apocalyptic rogue wave that destroyed an entire fleet of the old king's armada. The Tidespoken revere this natural disaster as the ultimate proof that the ocean is the true sovereign of the world, and they seek to align themselves with its crushing power.
- **Flavor:** Sea-shell tokens, salt-crusted oilskins. Prayers manifest as the crash of distant rogue waves and heavy brine smells.
- **Domain Tag (Tidal Undertow):** Affect enemy with prayer -> Target is physically shoved 10 ft (2 squares) in a direction of your choosing.

#### Novice Prayers

**Riptide**
The ground itself decides it would rather be underwater.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Tithe Ladder:**
- Pass: Target must pass Athletics (TN 8) or be swept 2 Zones in a direction of the Priest's choosing and knocked Prone.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0. The target still makes their Athletics check.

**Storm's Breath**

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** Touch
- **Action Type:** Activation
- **Duration:** Scene

**The Tithe Ladder:**
- Pass: Target ignores Stress and penalties from weather- or water-related environmental hazards (per the Iron World Hazard Check rules) for the scene.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 1 Locked Stress into 1 direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Crushing Surf**

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 2 Locked Stress
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Tithe Ladder:**
- Pass: Target must pass Athletics (TN 8) or suffer 2 Dissonant Stress and be knocked Prone.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, per Toll in Flesh, and reset the Priest's Encroachment to 0. The target still makes their Athletics check.

**Thalass's Favor**
The sea doesn't grant favors. It simply, occasionally, declines to drown you.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** One vessel, touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: Calms local waters and draws a favorable wind, granting the vessel a full day of safe, expedited passage.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The passage still holds, but convert the Locked Stress cost into a direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Thalass's Due**
The sea doesn't lose things. It just decides, eventually, what to give back.

- **Level:** Novice
- **Resolution:** Tithe of Will — Faith vs. TN 8
- **Cost:** 1 Locked Stress
- **Target/Range:** A body of water, Short Range
- **Action Type:** Activation (requires a few minutes)

**The Tithe Ladder:**
- Pass: The Priest asks the water what it's taken. If a specific object or body lost within this water in the last year is within reasonable range of it (a bay, harbor, or river — not the open ocean at large), the tide reveals its exact location.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The location is still revealed, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Special Interactions:** New ground — salvage and recovery, a niche no other Prayer currently touches.

#### Adept Prayers

**The Undertow's Grip**

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** 15ft radius, Short Range
- **Action Type:** Aggressor

**The Tithe Ladder:**
- Pass: Every enemy in the radius must pass Athletics (TN 10) or become Anchored until they break free (repeat the check as a Free Action on their turn).
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Rogue Wave**

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** 15ft radius, Short Range
- **Action Type:** Aggressor

**The Tithe Ladder:**
- Pass: Every character in the radius — friend or foe — must pass Athletics (TN 10) or suffer 3 Dissonant Stress and be swept 1 Zone and knocked Prone.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 2 Locked Stress into 2 direct Wounds, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Special Interactions:** Deliberately indiscriminate, mirroring Corpse Bloom — the sea doesn't negotiate.

**Read the Deep**
Thalass doesn't warn you before it drowns you. This is the Priest borrowing that warning early, on someone else's behalf.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress, paid once at cast — keeping it Flowing costs no additional Locked Stress
- **Target/Range:** Self, aboard a vessel or navigating open water
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; re-rolled once per hour underway outside combat rather than per Activation (see The Unbroken Watch, Domain of Strategy). Drops on a Wound or Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: The Priest senses an approaching storm, reef, or dangerous current before it's a threat — Advantage on checks made to avoid maritime hazards.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The warning still comes, but convert the Locked Stress cost into a direct Wound, per Toll in Flesh, and reset the Priest's Encroachment to 0.

**Thalass's Whisper**
The tide runs everywhere, eventually. Thalass just has to be asked nicely to carry something along with it.

- **Level:** Adept
- **Resolution:** Tithe of Will — Faith vs. TN 10
- **Cost:** 2 Locked Stress
- **Target/Range:** Touch, any body of water connected to the sea
- **Action Type:** Activation (requires a few uninterrupted minutes)

**The Tithe Ladder:**
- Pass: The Priest speaks a short message into the water. If it reaches the open sea, the tide carries it to a specific person or place the Priest has a genuine prior connection to — the recipient hears or dreams the message within a day.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: The message still arrives, but convert the Locked Stress cost into a direct Wound, and reset the Priest's Encroachment to 0.

**Special Interactions:** The only long-distance communication tool anywhere in the game — deliberately one-way and delayed, not a substitute for Commune's direct divine Q&A.

#### Master Prayers

**The Drowning Depths**
Thalass doesn't drown you all at once. She simply doesn't let you back up for air.

- **Level:** Master
- **Resolution:** Tithe of Will — Faith vs. TN 12
- **Cost:** 3 Locked Stress
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Tithe Ladder:**
- Pass: Target must pass Athletics (TN 12) or gain the Drowned condition (see Iron Core).
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 3 Locked Stress into 3 direct Wounds, per Toll in Flesh, and reset the Priest's Encroachment to 0. The target still makes their Athletics check.

**The Sovereign Tide**
The storm doesn't rage because Thalass is angry. It rages because the ocean has never once needed permission.

- **Level:** Master
- **Resolution:** Tithe of Will — Faith vs. TN 12
- **Cost:** 3 Locked Stress
- **Target/Range:** 25ft radius, centered on self
- **Action Type:** Activation
- **Duration:** Flowing — no additional Locked Stress cost; the Priest rolls Tithe of Will vs. TN 12 at the start of each of their Activations to maintain it (per the Flowing rule in Embracing the Abyss). The zone instantly drops if the Priest takes a Wound or is knocked Prone (per the Physical Anchor rule).

**The Tithe Ladder:**
- Pass: The zone becomes Heavily Obscured and difficult terrain for enemies only (per the Environmental rules); every enemy that ends its turn inside suffers 1 Dissonant Stress. Allies are unaffected.
- Fail: As Pass, and the Priest gains 1 Encroachment.
- Snake Eyes: Convert the 3 Locked Stress into 3 direct Wounds, per Toll in Flesh, and reset the Priest's Encroachment to 0. The zone still forms.

# Chapter 8 — Soothing the Soul

*Downtime*

## Downtime: Settlements, Budgets, and Reputation

### 1.Pursuit Points (Replacing Literal Day-Counting)

Tracking exact calendar days across a party with different ongoing Pursuits gets unwieldy fast — especially once a Priest is spending a full day on Religious Pursuit while the Fighter is mid-week into a Commission. Instead, the GM sets a **Downtime Budget** in **Pursuit Points (PP)** based on the narrative gap between adventures, and each Pursuit costs PP rather than literal days.

**Pursuit Costs (PP):**

| Pursuit                                 | PP Cost |
| ---------------------------------------- | ------- |
| Acquisition (Restock/Purchase/Sell, per transaction) | 1 PP    |
| Tend to the Flesh (per Wound Slot cycle) | 1 PP    |
| Hammer & Forge (per item)                | 1 PP    |
| Distil & Compound (per batch)            | 1 PP    |
| Religious Pursuit                       | 1 PP    |
| Commission                               | 3 PP    |
| Finance Bank                             | 1 PP    |
| Carousing                                 | 1 PP    |

**Example Budgets by Narrative Gap:**

- **A Single Night (1 PP):** The party makes camp in a waystation or sleeps at an inn before pushing on at dawn. Barely enough time for one quick Acquisition run or a single round of Tend to the Flesh.
- **A Few Days' Respite (3 PP):** The party has a short, clear break — recovering after a dungeon, waiting on a lead. Enough for a couple of Pursuits each, or one character to push hard on a single big one.
- **A Full Week in Town (5–7 PP):** The classic "return to town between dungeons" beat. Enough PP for most characters to run two or three Pursuits, or for one character to commit their whole budget to a Commission.
- **A Season of Downtime (10+ PP):** Used sparingly — between story arcs, over a winter, during travel to a new region. The GM should treat this as an explicit pacing tool, not a default, since it lets characters stack multiple Commissions or fully clear **clearable** Locked Stress and gear damage across the whole party. (Attunement Locked Stress is never part of that — see Iron Core's Golden Rules.)

**The Rule:** Each character tracks their own PP budget independently — one character spending their whole budget on a Commission doesn't prevent another from running three small Pursuits in the same gap. This keeps downtime parallel rather than turn-based, matching how real "everyone goes off and does their own thing in town" play actually happens at the table.

**Nightly Long Rests:** A Downtime period is, definitionally, a stretch of nights spent somewhere safe — so every night it covers includes a Long Rest (Iron Core), resolved automatically alongside whatever Pursuits that night's characters are running, with one exception: a night spent on Carousing doesn't include that night's Long Rest, since you can't sleep off Stress the same night you're spending it back up at the tavern — the Carousing table's own Stress results are its trade-off for skipping guaranteed recovery. Unlike a Long Rest taken mid-adventure, a Downtime night doesn't roll the Community Supply Die — that abstraction exists for dungeon and wilderness attrition, and Downtime's own Acquisition rules already cover ordinary town living. Over the length of a full visit this is what actually delivers the Locked-Stress clearing the Season-of-Downtime entry above already promises: a Single Night is one Long Rest (1 Locked Stress), a Full Week is up to seven, and a Season is enough nights to fully clear anyone's **clearable** pool without needing a single Religious Pursuit roll — **Attunement Locked Stress is not part of that pool and no length of Downtime reaches it** (Iron Core, Golden Rules) — Religious Pursuit still wins on speed (Will score in one day instead of one point a night) and is the only thing that touches Encroachment at all, so it keeps its purpose even once nightly Long Rests are accounted for.

**PP tracks attention, not the clock.** PP and the Time Cost listed under each Named Pursuit answer two different questions, and they are never reconciled against each other. **PP** measures how many discrete undertakings a character can commit real attention and dice to during a given Downtime period — an action-economy currency, exactly like Momentum is for combat. **Time Cost** is narrative flavor: it tells the table how a Pursuit is described unfolding in the fiction (a day hunched over a forge, three days of convalescence, a week waiting on a hired artisan), and it matters for *exclusivity* — some Pursuits explicitly lock out other activity while they run, the way Religious Pursuit already states no other Pursuit may be performed alongside it — not for calculating whether a Pursuit numerically "fits" inside a PP budget measured in days.

This is why Commission costs a flat 3 PP despite a full week of Time Cost: the character isn't personally laboring for seven days, they're paying an artisan and checking in periodically, so it draws down the same attention-budget as three smaller undertakings, not seven. Tend to the Flesh works the same way from the other direction — its 3-day healing cycle runs passively in the background of a single 1 PP commitment, because the PP cost reflects one check-in on an ongoing process, not three days of hands-on effort. Hammer & Forge and Acquisition, by contrast, are personal and effort-heavy, so their PP cost happens to track close to their Time Cost — that's a coincidence of those two Pursuits, not a rule.

**The GM never needs to add up Time Costs against a PP Budget.** If a character has the PP to spend, they can spend it. The Example Budgets below describe the narrative texture of a gap — what a "Full Week in Town" feels like at the table — not a day-by-day schedule every character's chosen Pursuits have to mathematically fit inside.

---

###  2.Settlement Tiers (What's Even Possible Here)

Not every Pursuit is available everywhere. A fishing hamlet has no master blacksmith to Commission from; a sprawling capital has no shortage of either.

#### Hamlet (Tier 0)
*A handful of families, maybe a shrine, no real market.*
- **Available Pursuits:** Tend to the Flesh, Religious Pursuit (if the local shrine matches the Priest's tradition — GM's call), basic Acquisition (food, rope, torches, common-tier items only), Carousing (a hamlet doesn't need a market to have a common room and a fire).
- **Unavailable:** Hammer & Forge (no forge), Commission (no master artisan), Finance Bank (no bank or broker to speak of).
- **Acquisition Modifier:** **-2** to the Acquisition check for Common-tier goods — a hamlet's stock is thin, and there's little room to haggle or substitute. Anything above Common isn't a modifier problem, it's a hard gate: automatically fails regardless of the roll — a hamlet simply doesn't stock Scarce, Rare, or Legendary goods, full stop.
#### Town (Tier 1)
*A proper market square, a working forge, a temple or chapter house.*
- **Available Pursuits:** All of the above, plus Hammer & Forge and Acquisition up to Scarce availability, Finance Bank.
- **Unavailable:** Commission, only available to 1 player(not enough artisans to service everyone at once), for anything above Masterwork (no legendary specialists here).
- **Acquisition Modifier:** None — this is the baseline, no bonus or penalty.

#### City (Tier 2)
*A genuine trade hub. Guild halls, multiple forges, a cathedral.*
- **Available Pursuits:** All Pursuits, including Commission, fully available. Rare-tier Acquisition becomes possible.
- **Acquisition Modifier:** **+2** to Acquisition checks (competition between merchants works in the buyer's favor), but prices for Common goods may be inflated 10–20% at GM discretion (city premiums).

#### Capital / Metropolis (Tier 3)
*The seat of power. Anything that exists, exists here.*
- **Available Pursuits:** Everything, including bespoke or one-of-a-kind Commissions the GM may gate behind a specific NPC artisan or a waiting list (a narrative hook, not a mechanical penalty).
- **Acquisition Modifier:** **+2**, and Rare-tier items no longer require a roll to locate — only to afford.

---

### 3.Settlement Reputation (The Demeanor Layer)
This directly mirrors the existing NPC Stance system, scaled up from a single person to an entire settlement's general disposition toward the party. It exists specifically so Influence-based skills and feats have somewhere to matter outside of combat and individual NPC negotiation.

Most Pursuits carry a rolled check, so Settlement Stance modifies them the same way it modifies Acquisition (see below). Carousing is the exception — it has no check to modify — so Stance instead shifts which d66 band its result falls in; see the Carousing entry for the exact mechanic.

**The Four Settlement Stances:** Hostile, Unfriendly, Neutral, Friendly — identical states and identical shift rules to the NPC Stance System (Standard Success shifts one step, Massive Success shifts two steps, never jumping straight to the opposite pole), applied collectively to a settlement's general disposition.

- **Hostile:** The party has actively wronged this settlement — botched a job, insulted the local lord, left a debt unpaid, or committed a crime that's become common knowledge. Acquisition checks suffer **-4**, Commission requests are refused outright regardless of payment, and most other Pursuits (Religious Pursuit at a shrine whose faction the party has angered) may be denied entirely at GM discretion. This is the settlement actively working against the party, not just distrusting them. Carousing isn't denied outright — even a Hostile settlement usually still has a tavern — but its d66 result shifts two bands worse.
- **Unfriendly:** The settlement is wary or has a poor opinion of the party — minor past friction, an unresolved rumor, simple distrust of outsiders — but isn't yet acting against them. Acquisition checks suffer **-2**. Most Pursuits remain available, just at worse terms; merchants quote higher prices, artisans are slower to commit to a Commission (+1 PP to commission — 4 PP total instead of 3). Carousing's d66 result shifts one band worse.
- **Neutral:** The default starting state for any settlement the party hasn't meaningfully interacted with yet. No modifier — this is the baseline the Settlement Tier modifiers above are written against.
- **Friendly:** The party has earned genuine goodwill — cleared a local threat, donated generously, performed a public service. Acquisition checks gain **+2** (stacking with Tier modifiers — a Friendly City offers a generous **+4** total), and Massive Successes become more frequent in practice simply because the combined modifier pushes more rolls past the Margin 5 threshold. Carousing's d66 result shifts one band better for the same reason.

**Changing a Settlement's Stance:** Unlike an individual NPC, a settlement's stance shouldn't flip on a single Influence roll — it represents the aggregated opinion of dozens or hundreds of people, and should move the way reputation actually moves: slowly, and mostly through action rather than conversation.

- **The Single Roll Exception:** If the party is dealing with one clearly-defined authority who speaks for the settlement (a mayor, a guild master, a garrison captain), a standard opposed Influence vs. Resolve check against that NPC can shift the *settlement's* stance exactly as if they were shifting an individual's — because, narratively, they effectively are the settlement's gatekeeper. This is the fast path, and it's identical math to the existing Social Engine, just with a wider blast radius on the outcome.
- **The Slow Path (No Single Authority, or a Fractured Settlement):** Settlement stance shifts one level after the party completes a deed the GM rules is significant enough — clearing a dungeon threatening the town, publicly exposing a corrupt official, sponsoring a town festival. This is a narrative trigger, not a roll, deliberately mirroring how individual NPC trust-building sometimes bypasses dice entirely in favor of "you did the thing, the stance moves."

---

### Summary: How a Downtime Period Actually Resolves at the Table

1. The GM narrates the time gap and sets a **PP Budget** (Section 1).
2. The GM (or the players, by simply being somewhere already established) confirms the **Settlement Tier** (Section 2), which gates what's even on the menu and sets the baseline Acquisition modifier.
3. The GM checks the party's current **Settlement Reputation** with this specific settlement (Section 3) — Hostile/Unfriendly/Neutral/Friendly — which further modifies Acquisition and may gate or unlock specific Pursuits.
4. Each player spends their own PP budget across the Pursuits now available to them, rolling each as defined earlier in this document.

This gives the GM three dials (time, place, and standing) to make every return to town feel mechanically distinct rather than an identical menu regardless of where or when the party arrives.

---

## Downtime Pursuits

### The Base Procedure: Progress Momentum

Downtime uses the same Margin-driven logic as everything else in the system, scaled to a slower clock. Rather than resolving in seconds, a Downtime Pursuit resolves across hours, days, or weeks — but the dice still tell you how well it went.

- **The Mechanic:** When a character undertakes a named Downtime Pursuit , they make the check listed for that Pursuit (almost always an unopposed roll against TN 8, using the same 2d6-vs-TN math as the Margin of Manifestation used elsewhere in the system — collapsed here to two outcome bands instead of combat's four, since a Pursuit measured in days doesn't need Messy Success's mid-margin complication texture).

- **Failure (<8):** The Pursuit does not complete this cycle. Time is lost — the character must spend the full duration again before attempting it a second time (this is what makes failure costly even without inflicting Stress or harm: it's a tempo loss, not a damage source).

- **Standard Success (Margin 0–4):** The Pursuit completes exactly as described in its own entry.

- **Massive Success (Margin 5+):** The Pursuit completes, and the character generates **1 Progress Momentum** — **at most one per character per settlement visit**, however many Massive Successes they roll. Everything else a Massive Success grants — a 25% discount, a 65% sale, a full batch, total absolution — still applies every single time; only the Momentum is capped.

> [!note] Designer's Note
> **Why the cap:** without it the modifiers generate the currency rather than the rolls. A Friendly City stacks **+4** onto Acquisition, and Acquisition is the cheapest Pursuit at 1 PP — so a character with Influence +4 mints Momentum on **83%** of attempts and banks four to six in a single Full Week, enough to fire every Ultimatum on the ladder below. The same character in a Neutral Town banks about one. One per visit keeps Progress Momentum worth roughly *a visit of competent work*, wherever the party happens to be standing.

**Progress Momentum** is a downtime-specific currency, mechanically separate from combat Momentum (it cannot be spent on Aggressor/Reactor maneuvers, and combat Momentum cannot be spent on downtime). It exists specifically to fuel Field Medic and the general spend options below, and represents a hot streak within this visit: a run of good luck or skill that can be cashed in immediately to skip a roll or accelerate another Pursuit before the party moves on. Unless a feat says otherwise, unspent Progress Momentum is lost at the end of the Downtime period — it does not carry over to the next visit or the next adventure.

**Spending Progress Momentum:** Like its combat counterpart, Progress Momentum is never spent to add a flat bonus to a roll — it's spent to break one of the three rules this document just spent Section 1 establishing: PP cost, Time Cost, and the Failure tempo-loss penalty above. Same three-tier shape as the combat Momentum spend list, translated to downtime's own rules instead of combat's.

*Cost 1 — Quick Fixes*
- **No Wasted Motion:** Immediately after a Pursuit fails, spend 1 Progress Momentum to retry it this same visit without paying its Time Cost a second time. The PP already spent on the failed attempt isn't refunded — this only removes the tempo tax described above.
- **Second Round:** Spend 1 Progress Momentum to reroll a just-rolled Carousing result, taking the new roll instead. Once triggered, the second result stands even if it's worse — a gamble, not a guaranteed upgrade.
- **Guaranteed Transfer:** Immediately after failing a different-branch Finance Bank withdrawal, spend 1 Progress Momentum to upgrade the result to a Standard Success — the courier route or partner bank still took a hit somewhere, but the character's own standing with this specific broker absorbs it instead of their coin, and the full amount arrives after all.

*Cost 2 — Breaking the Ledger*
- **Field Medic** (see below) already spends Progress Momentum at this tier — it's the existing example this tier is built around.
- **Called In a Favor:** Spend 2 Progress Momentum to bypass a Settlement Reputation penalty for one Pursuit attempt this visit — a Hostile settlement's outright refusal, or an Unfriendly settlement's -2, doesn't apply to this one check. The settlement's actual stance (Section 3) doesn't move; some existing contact or leverage just made this one specific ask land anyway.
- **Word Gets Around:** Spend 2 Progress Momentum to let one Acquisition check this visit ignore the settlement's Tier-based Availability ceiling (Section 2) — a Hamlet's hard gate on Scarce+, or a Town's cap below Rare, doesn't apply to this one purchase. Someone here knows someone who has what you need, regardless of what the settlement normally stocks. This doesn't touch Selling's Liquidity Cap — a small settlement still can't physically pay out more than its own ceiling for something you're selling, no matter who's asking.

*Cost 3 — The Ultimatums*
- **Rush Job:** Spend 3 Progress Momentum so that one Commission **ignores the settlement's own Commission restrictions** for that attempt — it may be placed in a **Town** even if another character has already engaged the only artisan, and it may exceed a Town's **Masterwork** ceiling. The coin buys an outsider's time: a guild factor passing through, a master who owes somebody a favour.

---

**Stress gained during Downtime** (a Rough Night on the Carousing table, an ambient hazard, a failed Religious Pursuit's silence) sits on the same track as everything else — it's not a separate ledger. Nightly Long Rests (above) clear it the same way they clear anything carried in from the last adventure: Dissonant fully, Locked by 1 per night. Whatever's left when the party's PP runs out, or when the visit ends, simply travels into the next adventure at whatever value it's at — Downtime was never a guaranteed full wipe, just a much better rate of recovery than the field offers.
### The Named Pursuits

*A reminder while reading the entries below: each Pursuit's Time Cost is fictional framing, not a second currency to reconcile against the PP Budget (see Section 1) — only the PP Cost table gates what a character can actually attempt.*

#### Carousing
*Spend a night making the acquaintance of whoever else is still awake in this settlement, and see what comes of it.*

- **Time Cost:** 1 night.
- **The Check:** None. Carousing doesn't ask you to be good at anything — pay the 1 PP and roll d66 (roll two distinct d6s; the first is the tens digit, the second is the ones digit) directly against the table below.
- **Output:** Whatever the table says. No Standard/Massive/Failure split — the d66 result *is* the resolution, all 36 outcomes equally likely.
- **Settlement Stance:** Applies to which band the result falls in, not to the roll itself. Shift the tens digit by the settlement's Stance (Section 3) — Hostile: −2 bands, Unfriendly: −1, Friendly: +1 — then keep the ones digit as rolled; clamp at 1x (worst) or 6x (best), never wrapping. Example: a 23 rolled in a Hostile settlement resolves as 13; a 34 rolled in a Friendly settlement resolves as 44.

> **Every “Clear N Locked Stress” result below means *clearable* Locked Stress only.** A box locked to an Attuned item is not eligible and no Carousing result reaches it (Iron Core, Golden Rules).

> [!note] Designer's Note
> **Result 66 outperforms a successful Tithe of Will, deliberately.** Iron Core states that a Long Rest should never outperform a successful Tithe. Carousing 66 clears **3** Locked Stress for 1 PP with **no check at all**, which beats a Priest who rolled well. It is left that way on purpose: 66 is 1 result in 36 before Stance shifts it, the night costs the character that night's guaranteed Long Rest, and the whole point of the Pursuit is that it is a gamble nobody is good at.

**The Carousing Table (d66):**

*1x — Rough Night*
- **11:** Robbed blind in your sleep. Lose 1d6 sp from your purse, on top of anything you spent tonight.
- **12:** A fight finds you whether you started it or not. Gain 1 Locked Stress, and word travels — Acquisition checks in this settlement suffer **-2** for the remainder of this visit.
- **13:** You wake with a gap in your memory and a mark you don't recognize. Gain 1 Locked Stress. GM's call whether it becomes a hook later.
- **14:** You publicly insulted someone who mattered. If this settlement has a clear single authority figure, the GM may rule this a *failed* Single Roll Exception (Section 3), shifting the settlement's stance one step worse.
- **15:** Wake up several sp lighter with no memory of why. Lose 2d6 sp.
- **16:** Arrested for disturbing the peace. Spend 1 additional PP to buy your way out before dawn, or lose your next Pursuit this visit to a night in the cells — GM's call which fits the story better.

*2x — Minor Trouble*
- **21:** Lose a bet you don't remember making. Lose 1d6 sp.
- **22:** Something you said is already being repeated around town. No mechanical effect — a pure GM hook, for better or worse.
- **23:** Overserved, plain and simple. Gain 1 Locked Stress.
- **24:** Picked a fight with the wrong local, and lost. Gain 1 Locked Stress; the taproom remembers your face.
- **25:** Bought rounds for the whole room and meant it. Lose 1d4 sp, but you're a known face here now (flavor only — not a mechanical Reputation shift).
- **26:** A scuffle broke something. Pay 1d4 sp to cover it, or skip the bill and let the GM apply the Unfriendly settlement's **-2** Acquisition modifier for this visit.

*3x — Uneventful*
- **31:** Nothing to report. Reroll, ignoring this result.
- **32:** A quiet night and decent food. No effect either way.
- **33:** You hear the same three rumors everyone else already knows. Flavor only.
- **34:** An early night, all things considered. No effect.
- **35:** Good company, lost hours, nothing to show for it mechanically. GM's call whether an NPC remembers you fondly.
- **36:** Split the night between two taverns without much to show for either. No effect.

*4x — Solid Night*
- **41:** Clear 1 Locked Stress.
- **42:** Won back more than you spent. Gain 1d4 sp.
- **43:** Made a useful new acquaintance — a narrative hook for a future Contact, GM's call.
- **44:** Clear 1 Locked Stress, and pick up a piece of gossip worth following up on.
- **45:** A friendly local vouches for you in front of the room. If a clear single authority figure witnessed it, the GM may rule this a Single Roll Exception (Section 3) in the party's favor.
- **46:** Clear 1 Locked Stress, and gain 1d4 sp back from a friendly wager.

*5x — Great Night*
- **51:** Clear 2 Locked Stress.
- **52:** A grateful local presses 1d6 sp into your hand on the way out.
- **53:** You made a real friend in this settlement — GM's call whether this becomes a usable Contact later.
- **54:** Clear 1 Locked Stress, and hear a lead on Rare-tier goods this settlement wouldn't normally stock (Section 2) — a narrative bypass on availability, not on price.
- **55:** Clear 2 Locked Stress, and the room genuinely likes you. If a clear single authority figure was present, the GM may rule this a Single Roll Exception (Section 3), shifting the settlement's stance one step better.
- **56:** An old friend, rival, or contact recognizes you across the room — a strong narrative hook, GM's call on the shape it takes.

*6x — Legendary Night*
- **61:** Clear 2 Locked Stress, and walk off with 1d6 sp from an unclaimed pot at the gaming table.
- **62:** You're the toast of the tavern tonight. Clear 2 Locked Stress and bank 1 Progress Momentum.
- **63:** A very good story is now attached to your name here. If witnessed by this settlement's authority figure, the GM may rule this a Single Roll Exception (Section 3) in the party's favor.
- **64:** Clear 2 Locked Stress, and gain 1d6 sp from a game you probably shouldn't have won.
- **65:** Someone with real influence in this settlement owes you a favor after tonight — a genuine narrative asset, GM's call how it pays off.
- **66:** The best night the party's had in ages. Clear 3 Locked Stress, bank 1 Progress Momentum, and gain 1d6 sp from an admirer who wants the story to keep going.
#### Finance Bank
*Store coin between adventures instead of hauling it, and draw on it again in any other settlement with a branch.*

**What it solves:** Per Hardware's Slot rules, loose coin becomes a real carrying cost once it stacks up (100 coins = 1 Slot). Finance Bank exists so a party doesn't have to choose between a pack full of silver and converting every last coin into gear the moment they earn it.

**Scope:** Finance Bank holds currency (cp/sp/gs) only — it is not a general storage locker for physical loot. An item has to be sold for coin before it can be deposited, via the Selling procedure under Acquisition below.

**Deposit, or Withdrawal at the same branch it was deposited to:**
- **Time Cost:** Half a day.
- **The Check:** None — this resolves automatically, exactly like Commission resolves automatically once an artisan is hired and paid. Handing coin to a teller you already have an account with isn't a contested action, and nothing has physically moved between settlements yet.
- **Output:** Deposited coin stops counting against the character's Slots. Withdrawing it back at that same branch returns it in full, no roll.

**Withdrawal at a different settlement's branch:**
*This is the one place risk belongs — the branch has to actually move physical specie to cover you.*
- **Time Cost:** Half a day.
- **The Check:** Influence vs. TN 8 — the branch has to verify the account and vouch for the transfer, and a good relationship with the local broker smooths that over.
- **Standard Success:** The full amount arrives, no loss.
- **Massive Success:** The full amount arrives, and the character banks 1 Progress Momentum — the broker's fondness for a reliable client pays off in some other, unrelated favor.
- **Failure:** The network took a hit getting the coin here — a bad investment, a waylaid courier, a partner bank skimming its cut — and the withdrawal arrives **20% short**. The money isn't gone from the world, just gone from this transaction; a good GM hook, not a pure tax (the party now knows which courier route or which partner bank is dirty).
- **Settlement Tier and Reputation:** Apply the exact same modifiers already defined for Acquisition (Section 2's Tier modifiers, Section 3's Reputation modifiers) at the settlement being withdrawn *from* — a City or Friendly settlement's more established, trusted branch network is the same logic already making those numbers skew safer for Acquisition.
- **Hostile Settlements:** As with Commission, a Hostile settlement's bank refuses service outright. The party's money is still there; they simply can't draw on it here until relations improve.

**PP Cost:** All three cases above — deposit, same-branch withdrawal, different-branch withdrawal — draw on the same 1 PP already listed in the Pursuit Costs table. The PP cost reflects the attention spent on the errand, not the risk profile of the specific case.

#### Hammer & Forge
*Repair gear that's broken beyond field fixes.*

- **Time Cost:** 1 day per item being repaired.
- **The Check:** Crafting vs. TN 8, assuming access to a proper forge or workshop (a town blacksmith, the party's own tools if sufficiently equipped).
- **Standard Success:** Strips the **Ruined** tag from one item, restoring it to its un-Damaged baseline. Note: per the Gear Condition rules, this is also the standard route back from **Damaged** — Hammer & Forge can be used on a merely-Damaged item to clear the tag outright in a single day, rather than needing it to break further first.
- **Massive Success:** As above, and the character banks 1 Progress Momentum (their work was clean enough to also get ahead on something else this week).
- **Cost:** Typically requires spending sp equal to roughly 25% of the item's base value in raw materials (coal, leather, replacement fittings), unless a feat or equivalent effect waives it.

#### Distil & Compound
*Make alchemical wares instead of buying them.*

- **Time Cost:** 1 day per batch.
- **Requirement:** Access to an Alchemist's Lab (Hardware — Rare, City-tier+), owned or rented at a GM-set cost. Unavailable in a Hamlet or Town.
- **Scope:** One kind of Alchemical Ware of Rare availability or lower, or Powder & Shot. Firearms and Legendary items cannot be made this way.
- **Materials:** Paid up front — 50% of the ware's listed price for each of the 3 items in a full batch (for Powder & Shot, a full batch is 6 loads at 5 sp each).
- **The Check:** Crafting vs. TN 8.
- **Clean Success (Margin 3–4):** A full batch — 3 items, or 6 loads.
- **Messy Success (Margin 0–2):** 2 items, or 4 loads. The remaining materials are wasted.
- **Massive Success (Margin 5+):** A full batch, and the character banks 1 Progress Momentum.
- **Failure:** No output, and the materials are lost.
- **Snake Eyes:** A fire in the lab. No output, the materials are lost, the alchemist takes 2 Dissonant Stress, and the Lab gains the **Damaged** tag (-1 to future Distil & Compound checks until cleared with Hammer & Forge).

#### Commission
*Pay a master artisan to build something better than you could make yourself.*

- **Time Cost:** 1 week (this is why Masterwork items command a 300% price markup and a specialized action — you're buying someone else's time and reputation, not just materials).
- **The Check:** No roll required if a qualified artisan is hired and paid in full. The Commission resolves automatically at the end of the week. (If the party is trying to commission something from a reluctant, suspicious, or unusually talented artisan, the GM may require an Influence check to secure the commission *before* the week of work begins — this is a Social Engine interaction, not a Crafting one.)
- **Output:** One weapon or armour piece upgraded to Masterwork Quality, per the existing Hardware rules (weapons: +1 Power; armour: suppress one negative tag).
- **Or — Made to Order:** One item that Hardware lists as **Commission-gated** (a firearm, a ship), built new and paid for at its listed price. A Commission-gated item can only be made at a **Capital (Tier 3)** — no lesser settlement has the specialists.

#### Tend to the Flesh
*Mundane medical care, not battlefield triage.*

- **Time Cost:** Per Wound Slot — see the base healing rule below.
- **The Base Rule:** A character heals 1 Wound Slot for every 3 days of dedicated rest and care, regardless of whether a Tend to the Flesh check is made. This is the passive floor — healing happens eventually even with no one rolling dice.
- **The Check (to accelerate or improve the outcome):** Medicine vs. TN 8. A character providing care to themselves or an ally may roll once per 3-day cycle.
- **Standard Success:** No change to the timeline, but the patient does not suffer the minor Stress tick from a poorly-tended wound (GM's call whether this applies in your table's fiction — e.g., infection risk, festering).
- **Massive Success:** The character (or caregiver, if treating an ally) may immediately make one additional Tend to the Flesh check against a different Wound Slot this visit, at no further PP cost — the same steady hand that handled the first injury cleanly moves straight to the next. This bonus check cannot itself trigger a further bonus check.
- **Equipment Interaction:** A Field Surgeon's Kit grants a flat +2 to this check, as already specified in Hardware. It holds 6 uses before requiring restocking (see Acquisition).

#### Field Medic
*An accelerant feat-driven Pursuit , not a base action available to everyone.*

This Pursuit does not exist independently — it is unlocked by the **Flesh Weaver** feat (*The Marrow*), which allows a character to spend Progress Momentum to bypass the standard 3-day Tend to the Flesh cycle: spending 2 Progress Momentum instantly heals 1 Wound Slot in 10 minutes, at a cost of 2 Dissonant Stress to the patient. Field Medic sits at the Cost 2 tier of Spending Progress Momentum above, and spends the same currency generated above.

#### Religious Pursuit (Penance, Communion, or Pilgrimage)
*How a Priest clears Locked Stress.*

- **Time Cost:** A minimum of 1 full day, dedicated entirely to the practice (fasting, prayer, ritual confession, a pilgrimage to a shrine) — no other Downtime Pursuit may be performed simultaneously.
- **The Check:** The Tithe of Will (2d6 + Faith) vs. TN 8.
-  **Standard Success:** Clears Locked Stress equal to the character's Will score (minimum 1), and clears 1 point of Encroachment (see Embracing the Abyss).
- **Massive Success:** Clears all of the Priest's Locked Stress and all of their Encroachment, and banks 1 Progress Momentum — a moment of genuine, total absolution.
- **Failure:** No Stress is cleared, and the day is lost. Unlike a failed Hammer & Forge or Tend to the Flesh, a failed Religious Pursuit is worth narrating: the Priest reached for their faith and found only silence. This is a good spot for the GM to foreshadow consequences of past Borrowed Authority Fails — a Priest carrying Encroachment from failed Tithes brings that same silence into this roll, at GM discretion.

#### Acquisition (Restocking, Purchasing, and Selling)
*Replenishing limited-use kits and consumables, like the Field Surgeon's Kit's 6 uses — the same procedure governing any new gear bought outright in town — and its mirror: turning loot into coin.*

| Availability | Sourced from              | Price band | Logic                                               |
| ------------ | ------------------------- | ---------- | --------------------------------------------------- |
| Common       | Hamlet+                   | 1–25 sp    | Village smith/herbalist, ordinary materials         |
| Scarce       | Town+                     | 15–50 sp   | Needs a proper forge, market, or trained specialist |
| Rare         | City+                     | 35–200+ sp | Guild-level craftsmanship, exotic materials         |
| Legendary    | Capital, Commission-gated | GM-set     | One-of-a-kind, not a market good                    |

Bands deliberately overlap — Availability tracks *how often the world stocks it*, price tracks *how good it is*. Same orthogonal relationship Quality tags (Shoddy/Balanced/Masterwork) already use.

- **Scope:** One check resolves one transaction with a single merchant for a single kind of item — restocking one kit, buying any quantity of one item (a dozen torches, three doses of a poultice), or selling any quantity of one item you're carrying (all three of those Balanced daggers go in one check, one payout). A different item — a second kit, a different weapon, a separate sale — needs its own 1 PP check. This still matches Hammer & Forge and Tend to the Flesh's per-unit pricing where it actually applies (a broken sword and a cracked shield are still two separate repairs), it just doesn't punish a single restocking trip or a single sale of duplicate loot the way strict per-item pricing would.
- **Time Cost:** Half a day, assuming the party is in a settlement of at least modest size.
- **The Check:** Influence vs. TN 8 (haggling, calling in favors, knowing the right back-alley supplier) or Survival vs. TN 8 if restocking from the wild rather than a market (foraging replacement herbs, harvesting more thread from a hunted beast).
- **Standard Success:** The item or kit is restocked, or the new item is purchased, at standard listed price.
- **Massive Success:** Restocked or purchased at a 25% discount, and the character banks 1 Progress Momentum.
- **Failure:** The settlement simply doesn't have what's needed this visit — no harm done, but the party must look elsewhere or wait.

**Selling**
*Turning loot into coin — the other half of this procedure.*

- **The Check:** Influence vs. TN 8, using the same Settlement Tier and Reputation modifiers as buying (Section 2 and Section 3) — a deep market gives leverage shopping a sale around, same as it gives leverage shopping a purchase around.
- **Base Payout:** 50% of the item's full price, calculated after any Quality tag (Shoddy/Balanced/Masterwork) and Enchantment cost modifiers — the item sells for what it actually is, not its base-tier price.
- **Standard Success:** The item sells at the 50% base rate.
- **Massive Success:** The item sells at 65% instead of 50%, and the character banks 1 Progress Momentum.
- **Failure:** No buyer at an acceptable price this visit — the same tempo loss as any other failed Acquisition, not a Stress or harm source.
- **The Liquidity Cap:** A settlement cannot pay out more per sale than the top of its own Tier's price band in the Availability table above (Hamlet: 25 sp, Town: 50 sp, City: 200 sp, Capital: GM-set), regardless of the roll. A village blacksmith doesn't have 200 sp sitting in a drawer for a Rare blade no matter how the haggling goes — sell for the local ceiling, or carry it to a bigger settlement.
- **The Draft (a Massive Success against the Cap):** Where a Massive Success's 65% payout would exceed the settlement's Liquidity Cap, the buyer pays **the cap in coin** and **writes the remainder as a draft on a counting-house** — the excess is deposited straight into the seller's **Finance Bank** account, to be drawn out later under the different-branch withdrawal rules above (Influence vs. TN 8, and a failure still arrives **20% short**). **Town or better only** — a Hamlet has no bank and no broker, so a hamlet's ceiling is absolute.

> [!note] Designer's Note
> **Why the Draft exists:** a capped sale otherwise made the best result on the ladder pay **nothing at all**. Above **50 sp** in a Hamlet, **100 sp** in a Town and **400 sp** in a City, the 65% and 50% rates both flatten onto the cap and are identical — so a Massive Success bought no extra coin, and once Progress Momentum is capped at one a visit it may buy nothing whatsoever. The cap's job is to make heavy loot a **logistics** problem, and it still is: the money is real, it is simply somewhere else, and fetching it can cost a fifth of it.

**Replenishing the Community Supply Die:**

| Step                             | Cost            |
| -------------------------------- | --------------- |
| Depleted → d4                    | 5 sp            |
| d4 → d6                          | 10 sp           |
| d6 → d8                          | 15 sp           |
| d8 → d10                         | 20 sp           |
| **Full restock, Depleted → d10** | **50 sp total** |

Resolved as a single Half-day Acquisition action (Influence or Survival vs. TN 8, Common-tier goods) — Settlement Tier and Reputation modifiers apply normally (a Hostile settlement can refuse outright; a Hamlet's -2 still bites). This is the "civilized" counterpart to the Scrounger's _Scavenge and Cannibalize_ Momentum spend, which does the same +1 step mid-dungeon for 2 Momentum instead of coin.

**The Slot Check:** A successful Acquisition only completes the purchase — it does not grant a character extra room to carry the result. The moment an item changes hands, the buyer must immediately have an open Slot to receive it (per Hardware's Visual Slot System), exactly as if they'd looted it from a dungeon. If they don't, the purchase still happens (their coin is spent, the item is theirs), but the item is left with the merchant, a hired porter, or back at the inn until the character frees up the room to carry it — buying it doesn't conjure pack space out of nowhere. This is the same logic already governing battlefield looting; town shopping shouldn't get a quieter exemption from the rule just because it's peaceful.

**Why this matters in town specifically:** Dungeon looting is naturally self-limiting — a character drowning in treasure usually also has fresh Wounds eating their Slots (per the Attrition Tax), so the system already polices itself in the field. A trip to town has no such friction: nothing stops a fully-healed character from trying to walk out with a Tower Shield, a Longbow, and six potions in a single shopping spree. The Slot Check above exists specifically to close that loophole — town shopping should still cost something other than coin.

---

### Summary Table

| Pursuit                       | Time Cost | Check | Output on Standard Success |
|---|---|---|---|
| Hammer & Forge                 | 1 day/item | Crafting vs TN 8 | Clears Damaged or Ruined |
| Distil & Compound              | 1 day/batch | Crafting vs TN 8 (requires Lab) | Batch of 3 wares or 6 loads |
| Commission                     | 1 week | None (paid) | Upgrades item to Masterwork, or builds a Commission-gated item (Capital) |
| Tend to the Flesh              | 3 days/Wound (base rate) | Medicine vs TN 8 to improve | Heals 1 Wound Slot |
| Field Medic                    | 10 minutes | Feat-gated, spends Progress Momentum | Heals 1 Wound Slot at a Stress cost |
| Religious Pursuit             | 1 day | Tithe of Will (2d6 + Faith) vs TN 8 | Clears Locked Stress |
| Acquisition (Restock/Purchase/Sell, per transaction) | Half a day | Influence or Survival vs TN 8 (Influence only when selling) | Restocks/purchases at listed price, or sells at 50% (65% Massive Success) — Slot Check when buying, Liquidity Cap when selling |
| Finance Bank (different-branch withdrawal) | Half a day | Influence vs TN 8 (auto if same-branch or depositing) | Full withdrawal; 20% short on Failure |
| Carousing                       | 1 night | None — roll d66 directly | Varies (see Carousing Table) |

---

# Part II — Running the Game

# Chapter 9 — Tools for the Nameless

*GM Tools*

## The way the Game Plays
**Adventures**
An Adventure is a string of Scenes, created by the GM and strung together to form a story.

**Scene**
Scenes are a method of pacing and is the action between Breathers. So, when there is a reference to "scene" to describe a duration or limit, it is describing the time period between breathers.

**Within a Scene**
Players take turns Activating their character and taking actions.
Outside of combat, such as exploring the world or socially engaging actions are either played out as a discussion amongst the players and the GM. The GM facilitating the exchanges and narrating the scenes, like a traditional RPG. Dice are rolled only when the narrative/GM requires it. Activation order and the rolls to determine them generally aren't needed during these moments.
Activation order is mainly used to provide order to the chaos of combat.  This ensures the resolution can be handled in an organised fashion.
When  there is an action that requires some dice rolling it is usually against a TN, the result determines the outcome of the action.  Sometimes these actions will be Opposed by an opponent, meaning dice are rolled, appropriate modifiers are added and compared to the roll of the opponent.  Whoever rolls highest wins.  Depending on the action taken could also determine how well or how poorly a character has performed in this opposed roll.

---

**Setting Difficulty: The Static TN and Situational Modifiers** In _Iron and Marrow_, the Target Number for unopposed checks is generally **8** for a basic task. **TN 10, 12** can be used for more complex tasks as necessary. The Target Number reflects a complex/difficult task.

when the context or environment of a task is challenging or difficult, the GM can apply a **Situational Modifier** to the player's total roll. This preserves the Margin Scaler math while reflecting the harsh reality of the world:

- **Standard (+0):** The default state of the world. Picking a standard lock, leaping a small gap, translating common runes.

- **Advantageous (+2):** The player has superior tools, abundant time, or significant environmental help.

- **Difficult (-2):** The task is inherently complex, rushed, or opposed by the environment. Picking a Masterwork lock, climbing a sheer wall in the rain.

- **Extreme (-4):** The task borders on the impossible. Performing surgery mid-combat, deciphering a Dread entity's true name from a shattered tablet.

For example, tracking a giant boar through a muddy trail is somewhat easy so a TN 8 with a situational modifier of +2.  Where as, that same boar over dry ground during a dust storm could be TN 10 with a situational modifier of -4.

---

## Economic Baselines

- Currency Standard: The primary day-to-day trade currency is the Silver Piece (sp). Copper Pennies (cp) are used by peasants (10 cp = 1 sp). Gold Sovereigns (gs) are held only by nobility and wealthy cartels (1 gs = 20 sp).

- Item Degradation: Items can be Damaged (reduces effectiveness or adds a flaw) or Ruined (useless until repaired via a Hammer & Forge downtime action).

### Loot & Treasure by Party Standing

Currency scales with the party's current Standing, the same way Enemy Budget does — find the row, use it for whatever Tier just went down. Fodder barely moves, for the same reason its Skill budget barely moves: it's disposable chaff, not an economic lever.

| Party Standing | Fodder (per kill) | Grunt (per kill) | Elite (per kill/find) | Dread/Boss (per kill/find) |
|---|---|---|---|---|
| Green | 1–2 sp | 5–10 sp | 15–25 sp | 40–70 sp |
| Blooded | 1–2 sp | 8–15 sp | 20–35 sp | 60–100 sp |
| Veteran | 2–3 sp | 10–20 sp | 30–50 sp | 100–160 sp (5–8 gs) |
| Hardened | 2–3 sp | 15–25 sp | 45–75 sp | 160–260 sp (8–13 gs) |
| Storied | 3–4 sp | 20–35 sp | 70–120 sp | 260–450 sp (13–22 gs) |

**Item Find (Rare+ gear):** money alone can't buy Rare or Legendary goods — Soothing the Soul is explicit that those are "acquired in play... or the point of a sword." This is where they enter play instead:
- **Fodder:** None. Their own gear isn't worth looting individually.
- **Grunt:** Roughly 1-in-6 carries a single Scarce-tier item worth taking.
- **Elite:** Usually (roughly 1-in-2) carries or guards one Scarce–Rare item — consistent with Hardware's own Bane-item note that a party is "far more likely to loot one... off a dead wyrm than find one for sale."
- **Dread/Boss:** At least one Rare item guaranteed; a real chance (GM discretion, roughly 1-in-3) of a Legendary item or the scenario's actual macguffin.

**Set-piece treasure:** a named one-off (a hoard, a macguffin like the Temple of the Lost God's golden statue) isn't a kill-loot roll — price it using the Dread/Boss row for the party's current Standing as its raw sale value, then let the fiction decide whether the party ever actually melts it down.

---

## Targeting the Resources

Because the Community Supply Die is a tangible mechanic, an enemy can attack the party's supplies instead of their health, creating terrifying new enemy archetypes. **What that costs depends on the archetype** — an Elite spends Momentum and keeps its damage; a Fodder thief spends its whole action and deals none.

- The Rust Monster / Acid Spit: If an enemy with a corrosive or fire-based attack wins a Clash by a Margin of 5+, it may spend 1 Momentum from its own Bank to force an immediate Supply Die roll as the party's gear melts or catches fire.

- The Scavenger: Small, Fodder-tier enemies — goblins, feral ghouls — that trade their attack for the party's pack rather than their blood. **Instead of a regular attack action**, the creature slices open a satchel and flees: the target must pass an **Acrobatics check vs TN 8** or the Community Supply Die **steps down one tier**. There is no Clash and no Supply Die roll — the failed check *is* the step-down, which makes it harsher per attempt than the Rust Monster's forced roll, and it is paid for with the creature's entire action, since a Scavenger deals no Impact at all on the turn it tries. **The Goblin Scrapper's `Sabotage` (Bestiary) is this ability.**

---

#### Non-Caster usage of Faith and Arcana

- **The Cult Hunter:** A gritty, non-magical Cutthroat can invest 1 DP into _Faith_ to recognize cult insignias, understand demonic weaknesses, or desperately read a holy scroll of banishment to save the party.

- **The Dungeon Scavenger:** A Wits-based Bravo might put 1 point into _Arcana_ so they can safely disarm magical traps or activate an alchemical wand they looted off a dead Boss.

It turns those skills from "Caster-Only Taxes" into universally valuable adventuring tools for the whole party.

---

**Non-weapon damage falls into one of three distinct, terrifying categories:**

#### 1. Direct Stress (The Attrition Engine)

For minor environmental hazards, toxic environments, or persistent conditions like fire. It does not instantly sever a limb or crush bone, but the pain and exhaustion rapidly accelerate the Death Spiral.

- The Mechanic: Bypasses the Wound Threshold completely and deals Direct Dissonant Stress.

- Example (Ablaze): "At the start of your turn, the agonizing heat causes you to suffer 2 Dissonant Stress before you can act."

#### 2. Direct Wounds (The Lethal Bypass)

For catastrophic hazards, unmitigated magic, or Boss abilities that are narratively designed to rend flesh and ignore armour.

- The Mechanic: Bypasses the Wound Threshold completely and automatically crosses out 1 Wound Slot.

- Example (Gehenna's Grip): "Failure means they are violently dragged 10 feet toward Malaphar. The searing chains melt through their armour, inflicting 1 Direct Wound."

#### 3. Hazard Rolls (The Trap Mechanic)

When a falling boulder, explosive trap, or massive environmental collapse occurs, it shouldn't just be a flat number. It should strike the player like an enemy would, testing their armour and resolve.

- The Mechanic: The GM rolls a 2d6 + Hazard Power to generate a massive Impact total, which is then compared against the player's Wound Threshold just like a sword swing.

- Example: A collapsing ceiling trap rolls 2d6 + 4. It totals a 14. Because 14 is higher than the Fighter's Wound Threshold of 10, the Fighter takes a Wound. If it rolled an 8, the armour holds, and the Fighter only takes 1 Stress.

---

In Iron & Marrow, monsters do not challenge the players by having bigger numbers. They challenge the players by breaking the rules of the game.

This is managed through the Momentum Economy below and a tiered Bestiary Tag system. Here is the framework for designing brutal, terrifying encounters.

## The Momentum Economy

There is one currency in Iron & Marrow, and both sides of the table use it. **Momentum.** The GM does not have a separate resource, a separate pool, or a separate cap.

#### Every creature has a Momentum Bank

**Momentum Bank = 4 + Reflex.** Every creature, core-species and monster alike, at every tier.

- The Bank belongs to that creature. It is not shared with other enemies, it does not survive the creature's death, and nothing draws from anyone else's.
- **A Bank is already a spend cap.** Where an ability needs a tighter per-use limit than the Bank provides, that limit is written into the ability's own text — not into a second global rule.

#### How NPCs earn it — asymmetric on purpose

A PC earns 1 Momentum by winning a Clash by a Margin of 5+ (Iron Core). **NPCs do not all get that trigger**, because enemies outnumber the party and headcount would otherwise decide the economy:

| Tier | Earns Momentum from |
|---|---|
| **Fodder** | Its own Traits and Feats only. Never from a Clash. |
| **Grunt** | Its own Traits and Feats only. Never from a Clash. |
| **Elite** | Traits and Feats, **plus** 1 on winning a Clash by Margin 5+. |
| **Dread / Boss** | Traits and Feats, Margin 5+, **plus 1 at the start of every round.** |

Point nine enemies at four PCs and the PC trigger would hand the GM nine earning chances a round against the party's four. Under the table above that same fight gives the GM **one** passive earner. Adding a mook to an encounter adds a body, not an economy — which is what keeps Fodder disposable.

The round-start point is Dread/Boss only. A Boss with low Reflex will rarely win a Clash by Margin 5+, so without it a Boss could never afford its own signature abilities. It does not scale with headcount, so it cannot be farmed by fielding more bodies.

#### Behavioural Recharge — how Fodder and Grunts earn

Since the lower two tiers earn nothing from Clashes, a Trait or Feat is their *only* route to Momentum. Tie it to a binary, narrative trigger that needs no arithmetic:

- **The Blood-Crazed Orc:** banks 1 Momentum whenever it suffers a Wound.
- **The Sadistic Mercenary:** banks 1 whenever a PC in its Threat Zone suffers a Wound.
- **The Clockwork Sentinel:** banks 1 at the start of every even-numbered round.
- **Cunning Leader:** banks 1 whenever an ally within its line of sight dies.

This needs no tier gate. A Grunt's Bank is 3 or 4 — the cap does the limiting, so an ability that generates Momentum never has to ask what tier is holding it.

#### What NPCs spend it on

Their own Traits, Feats and Special Actions that carry a Momentum cost, and Iron Core's generic spends — Shake It Off, The Blood Price, Adrenaline Flush, The Surge — exactly as a PC does.

---

### The Tiers of Monsters

Because modifiers are bounded, monsters are categorized by how they interact with the game's action economy and the Momentum economy.

#### The Tiers of Attrition

**Fodder:** They exist to drain player Momentum and force tactical positioning.
	- 1 - 2 Traits. 1 Special Action (self-gated — no Momentum cost; see the Bestiary's Gate Test). Usually 1 Wound Slot. Stress as the core rules define. Earns Momentum only from its own Traits and Feats, never from a Clash.
	- _Example (Zombie, Undead):_ Brawn 1; Melee +1. _(Strikes and grabs at 2d6+1 — the Attribute sets its Wound Threshold and is never added to the roll.)_

- **Grunt:** These are the core adversaries. Armoured mercenaries, mutated alchemical horrors, and seasoned killers. They force the players to spend Momentum .
	- 1 - 2 Traits. 1 Special Action, same self-gating rule as Fodder. 2 Wound Slots. Stress as the core rules define. Earns Momentum only from its own Traits and Feats, never from a Clash.

    - _Example (Orc Line-Breaker):_ Brawn 2; Melee +2, Prowess +2. _(Strikes at 2d6+2. Reflex 0, so Activation Order 6 and Momentum Bank 4. Nothing to resist mental magic with.)_

- **Elite:** Almost equivalent to the characters capabilities, very challenging. Built to be a few advances ahead of the characters at all times.
	-  2 - 3 Traits. 1 - 2 Special Actions — reach for a Margin 3+ threshold before reaching for a Momentum cost when the ability is a bonus on top of an already-resolved action. 3 - 4 Wound Slots. Stress as the core rules define, +1. **First tier that earns Momentum from a Clash won by Margin 5+.**

    - _Example (Cultist Assassin):_ Melee +2, Acrobatics +4, Stealth +4, Notice +1. _(Strikes at 2d6+2, Dodges at 2d6+4 — Dodge is Acrobatics, there is no Dodge skill — Stealths at 2d6+4. Braces at 2d6+0.)_

- **Dread Entities / Bosses (The Behemoths):** These are terrifying, almost mechanical monstrosities or apex predators. Built to rival a highly optimized player. Attributes can exceed +3.
	- 2 - 4 Traits. 3+ Special Actions — this is the tier where a genuinely free-standing, **Momentum-costed** ability (a Free Action stacked on a full turn, or a Lair Action outside the turn order) actually belongs. 4+ Wound Slots. Stress as the core rules define, +2. Earns from Margin 5+ **and** banks 1 at the start of every round.

    - _Example (Arch-Devil Malaphar):_ Melee +7, Arcana +4, Resolve +4. _(Strikes at 2d6+7, casts at 2d6+4, resists mental magic at 2d6+4. Reflex 0, so Activation Order 6 and Momentum Bank 4 — he acts last and pays for his Mandate and his Lair Action out of that Bank.)_

**Point budgets for all four tiers, and the full Gate Test for Special Actions, live in the Bestiary's "Core Integration Rules" section.**

---

#### NPC Stress
is a binary "health bar," there are only two states: Fully Functional (0) and Broken (1). Nothing in between matters mechanically.

Here is exactly how it works at the table.

#### 1. The Tally (No Math Penalties)

When an NPC suffers Dissonant Stress (from a terrifying spell, a brutal critical hit, or a player's Intimidation action), the GM simply checks a box on their Stress Limit track.

- The Crucial Difference: The NPC suffers absolutely no penalties to their dice rolls. An Orc with 2 out of 3 Stress boxes checked still swings its axe with its full +8 modifier. It remains a 100% lethal threat right up until the breaking point.

#### 2. The Break Point (The Switch Flips)

The moment that final Stress box is checked, the binary switch flips from "Functional" to "Broken." The NPC does not get weaker; they are immediately removed from the tactical equation or their behavior radically alters.

"Breaking" means different things:

- The Rout : they drop their weapons and flee. The players have successfully defeated them without having to chew through their physical Wound slots. It rewards players for using fear and magic as crowd control.

- The Surrender: They throw down their shield, drop to their knees, and yield. Now the players have a narrative choice: take a prisoner, interrogate them, or execute them.

- The Frenzy: Instead of fleeing, the NPC breaks mentally into a pure, blind rage. It drops its defense completely (losing its Block/Dodge/brace abilities/modifiers) but gains Advantage on all Strike rolls until it dies.

- The Phase Change (Bosses): A Boss maxes out its Stress track. It doesn't die, but its behavior violently shifts. A heavily armoured warlord realizes they are losing, so they scream, tear off their heavy, restrictive armour (losing their Armour tags), and pull out two jagged daggers to fight recklessly in a new "Phase 2."

---

## Starting Momentum

Starting Momentum seeds the enemies' **Banks**, not a pool, so it scales with the roster on the table instead of a flat number:

- **The Ambush:** every Bank starts empty. The enemies are unaware, asleep, or drunk — the players dictate the entire opening, and the monsters have to survive a round just to trigger their Behavioural Recharges and get themselves on the board.
- **Standard Engagement:** the single highest-tier enemy starts with **2**; everyone else starts empty. A standard patrol, or mercenaries actively standing guard — enough for one moderate ability, keeping the players cautious.
- **High Alert:** every **Elite and above** starts with **half its Bank, rounded down**; Grunts start with **1**. The place knows the players are coming: traps set, weapons drawn, and an Elite able to afford its most devastating opener immediately.
- **The Kill-Zone:** **every** enemy starts with a **full Bank**. A Boss's lair, or a perfectly executed ambush. The atmosphere is immediately suffocating.

# Chapter 10 — Beasts, Monsters & Mutants

*Bestiary*

## The Dynamic Trait Manifest
Design Philosophy: Keep stat blocks simplified. Let traits dictate tactical behaviour, stress interaction, and Momentum usage.

Enemies use the similar character generation rules as players, the difference is the skills are bought a a 1:1 ratio regardless of the parent attribute value. Once an enemy is generated populate their stat block using the same derived stats as players, only list the stats that are most important, such as WT and Stress limit. The stats that have no modifier to not get listed and are assumed to be zero.

## Creature Types

Every stat block declares one or more Creature Types alongside its Tier. Type carries no inherent stat effect on its own — its entire job is to be a hook for other things to reference: Bane effects (Hardware: Enchantments), Domain Tags like Smite Corruption, and any future resistance/vulnerability trait. A creature can carry more than one Type where the fiction demands it (a reanimated golem is both Undead and Construct; a hag-blooded cultist could be both Humanoid and Fey) — treat it the same way multiple Traits stack on one stat block.

- **Humanoid:** Baseline mortal peoples and their monstrous cousins. Humans, orcs, goblins, cultists, bandits.
- **Beast:** Non-sapient natural or magically-touched fauna, regardless of size. Wolves, giant rats, trolls, ogres, dire wolves — Scale handles "how big," Type just confirms "it's an animal, not a person."
- **Dragon:** True dragons and wyrm-kin. Apex predators defined by hoarding intelligence, imposing Scale, and an elemental breath weapon or equivalent.
- **Fey:** Bound to the old pacts and capricious natural law of the wild places. Hag-covens, will-o'-wisps, thorn-court nobles.
- **Elemental:** A living embodiment of raw primal force — fire, water, earth, air, or the violent compound of two.
- **Undead:** The restless dead, animated by necromancy, grief, or unfinished business. Zombies, skeletons, wraiths, ghosts.
- **Vampire:** Undead predators sustained by the blood or life-force of the living. Broken out from common Undead because their cunning, regeneration, and domination-style abilities usually need their own Bane and Trait interactions rather than inheriting Undead's wholesale.
- **Lycanthrope:** Humanoids cursed or blessed with a beast-shifted second nature. Broken out from Beast for the same reason Vampire is broken out from Undead — the curse itself, not the claws, is usually what a Bane or ritual needs to target.
- **Daemon:** Infernal or otherworldly entities of deliberate, contractual malice. Bound to pacts, hierarchies, and Hells (or their local equivalent).
- **Void-Touched:** Entities whose existence itself violates natural law through contact with the Outer Dark — the product side of the Demonology/Void Magic paradigm (see Manipulating the Void).
- **Ooze:** Amorphous, usually mindless, and often corrosive. Gelatinous cubes, black puddings, creeping molds. (Pair with the existing Amorphous trait when a single-target weapon shouldn't be able to Wound it.)
- **Construct:** Artificial or animated bodies without a natural life cycle. Golems, animated armour, clockwork sentinels.
- **Mutant:** Flesh warped by alchemy, radiation, or forbidden transmutation into something no longer wholly natural.

#####  Core Integration Rules

**Enemy Budget by Party Standing**

Budgets are measured in **Skill points** — the sum of every Skill rank on the sheet. Attributes are deliberately excluded. They do not contribute to any roll; they set Skill ceilings and drive derived stats, and they cost 5 DP against a Skill rank's 1–3, so summing the two would be adding unlike currencies. What a creature rolls is its Skills, and what a PC rolls is theirs — that is the only number worth comparing.

Budgets scale with the party's current Standing (see The Marrow, Character Creation — "Milestone Standing"). Find the party's Standing, then use that row for whichever tier is being built.

| Party Standing | Typical PC Skill points | Fodder | Grunt | Elite | Dread/Boss |
|---|---|---|---|---|---|
| Green | 8 | 1–2 | 4–6 | 9–12 | 13–17 |
| Blooded | 9 | 1–2 | 5–6 | 10–13 | 15–19 |
| Veteran | 10–11 | 2–3 | 5–7 | 12–15 | 17–22 |
| Hardened | 12–14 | 2–3 | 6–8 | 15–18 | 20–26 |
| Storied | 15+ | 3–4 | 7–10 | 18–22+ | 24–30+ |

The logic behind each column:
- **Fodder** barely moves — it's disposable chaff by design, and a Fodder mook that scaled with the party would stop being Fodder. The only growth is a token bump by Storied so a late-campaign mob scene doesn't look absurd next to everything else on the field. Roughly 15–25% of a PC's Skill total.
- **Grunt** tracks the party's *current* Standing, at roughly 50–70% of their typical total — enough to force a Momentum spend from a single PC, credible in numbers, still meant to lose to focused attention.
- **Elite** is budgeted as roughly the party's *next* Standing tier up — a literal reading of the tier's own text, "a few advances ahead of the characters at all times." At Green, Elite is budgeted like a Blooded PC; at Hardened, like a Storied one.
- **Dread/Boss** is budgeted roughly two Standing tiers ahead, with a wide, GM-discretion range. A solo Boss has to "rival a highly optimized player" while getting acted on 3–5 times for every one of its own actions, so its raw stat budget needs real headroom over Elite, not a marginal bump.

**The Gate Test (free Special Actions vs. Momentum-costed abilities)**

Not every special ability needs to cost Momentum. Before writing one, ask what already limits it:
- If it replaces a creature's regular action for the turn (an alternate Strike, an alternate Activation), or its trigger is already rare enough to be self-limiting (a reaction to taking a Wound, say), it's a **Special Action** — free, no Momentum cost needed.
- If it's a bonus layered on top of an action the creature already gets to take (extra Impact or a control effect on a clash it already won), gate it with a **Margin threshold** (3+ / Clean or better) rather than a Momentum cost — the same math already governing every other Clash in this system.
- Only when an ability is genuinely free-standing — a true Free Action that stacks on top of a full normal turn, or a Lair Action that happens outside any creature's turn at all — does it actually need a **Momentum cost**, paid from the creature's own Bank, as its gate. This is rare, and should mostly be reserved for Dread Entities/Bosses.

- **Fodder:** 1 - 2 Traits. 1 Special Action (self-gated per the test above — no Momentum cost).
	- 1 wound.
	- stress as core rule defined.    
    - _Example (Zombie):_ Melee +1, Prowess +1. _(Strikes and grabs at +1, everything else is +0). Undead_

- **Grunt:** 1 - 2 Traits.
	- 1 Special Action, same self-gating rule as Fodder.
	- 2 wounds.
	- stress as core rule defined.

    - _Example (Orc Line-Breaker):_ Melee +4, Block +2. _(Strikes at +4, blocks at +2. Activation Order 5 — reduced from the base 6 by its Greataxe's Cumbersome tag. Magic defense is +0)._

- **Elite:** 2 - 3 Traits.
	- 1 - 2 Special Actions — reach for a Margin 3+ threshold before reaching for a Momentum cost when the ability is a bonus on top of an already-resolved action.
	- 3 - 4 wounds.
	- stress as core rule defined +1.

    - _Example (Cultist Assassin):_ Melee +2, Acrobatics +4, Stealth +4, Notice +1. _(Strikes at +2, Dodges at +4 — Dodge is Acrobatics — Stealths at +4. Prowess is +0)._

- **Dread Entities / Bosses (The Behemoths):** Skills can exceed the +6 mortal ceiling.
	- 2 - 4 Traits.
	- 3+ Special Actions — this is the tier where a genuinely Momentum-costed ability (a Free Action stacked on a full turn, or a Lair Action outside the turn order) actually belongs.
	- A genuinely free-standing ability at this tier may carry a **Momentum cost**, paid from the creature's own Bank.
	- 4+ wounds.
	- stress as core rule defined + 2

    - _Example (Arch-Devil Malaphar):_ Melee +7, Arcana +4, Resolve +4. _(Strikes at +7, casts at +4, resists mental magic at +4. Still has Activation Order 6 — he acts last).

**Core-Species Humanoids (Built Like a PC, Run Like an NPC)**

A Humanoid of one of the six core species — Human, Half-Elf, Half-Orc, Halfling, Elf, Dwarf — is built with the same rules as a player character (see The Marrow): its species traits, its Feats, and its spells all come from the players' own lists, and its derived stats use the players' own formulas. Monsters and non-core humanoids (goblins, orcs, lizardmen, skinks) keep bespoke Traits and Special Actions.

Construction comes from The Marrow. Runtime stays here. Specifically:

- **Attributes** are allocated per tier, not from the Skill budget: **Fodder 1 · Grunt 2 · Elite 4 · Dread/Boss 6+** (a Boss may exceed the +3 mortal cap). Kept deliberately lean so derived stats stay in line with the rest of the roster — Attributes feed Wound Threshold and Stress Limit, and because NPC Stress is binary, a larger Stress Limit is a straight durability gain with no Winded penalty to offset it. Be aware these points do three jobs at once: they set Skill ceilings, meet Feat prerequisites, and drive the derived stats. At Fodder and Grunt the Ceiling Rule is effectively inert — a +3 ceiling applies even at Attribute 0, and those Skill budgets can't reach past +3 — so the points go to derived stats as intended. From Elite up, a specialist build can find every point already committed to a ceiling or a prerequisite before durability gets a look in; the Stress Limit floor below is what catches that.
- **Skills** use the Enemy Budget by Party Standing table above, unchanged.
- **Feats, spells and Traits share one allowance**, sized by tier: **Fodder 2 · Grunt 2 · Elite 3 · Dread/Boss 4**. Spend it in any mix — a Feat or spell from the players' own lists, or a Trait from the Manifest below, whichever actually serves the creature. Feats and spells come from The Marrow and Manipulating The Void, with a feat tier ceiling of Grunt Tier 1, Elite Tier 1–2, Dread/Boss any; spells must still satisfy their own Arcana/Faith rank prerequisites, and Paradigm Mastery works exactly as it does for a PC — within the chosen Paradigm only. Where a creature's signature mechanic has no equivalent on the players' lists (Skittering, Ambusher, Cunning Leader), spend the allowance on the Trait and don't contort the build to avoid it.
- **Species traits are free** and sit outside the allowance entirely; they are read from The Marrow. Species *drawbacks* come along with them — a Human NPC really does have a smaller Momentum Bank, a Dwarf really can't run anyone down, and a Half-Orc really is worse at talking to strangers.
    - **A trait that modifies the *creation* Skill budget is inert on an NPC.** The Human's **Adaptable** ("1 extra Skill **DP** at character creation" — a creation budget of 9 rather than 8) is the only case today: an NPC's Skills come from the Enemy Budget by Party Standing table, never from a creation budget, so there is nothing for it to modify — the same way the Ceiling Rule is inert at Fodder and Grunt. Its paired drawback still applies in full. Don't add a skill point for it.
- **Momentum Bank:** **every creature has one** — core-species and monster alike — at the normal **4 + Reflex**, earned and spent exactly as a PC's: on its own Traits', Feats' and Special Actions' Momentum costs and on Iron Core's generic spends (Shake It Off, The Blood Price, Adrenaline Flush, The Surge). This applies at every tier including Fodder. **Momentum is the only currency in the game; there is no GM Threat pool and no Vessel Limit** — a Bank is already a spend cap. How each tier *earns* Momentum is asymmetric and lives in GM Tools' Momentum Economy: Fodder and Grunts earn only from their own Traits and Feats, Elites add a Clash won by Margin 5+, and Dread/Boss add 1 at the start of every round.
- **Wound Slots stay on the tier scale** (Fodder 1 · Grunt 2 · Elite 3–4 · Boss 4+), not the PC's flat 3. Wound Slots are what makes Fodder disposable.
- **Stress stays binary** — Functional/Broken per the GM Tools NPC Stress rules. No Winded, no Breaking penalty, regardless of how the creature was built.
- **Stress Limit has a tier floor — core-species builds only:** **Fodder 4 · Grunt 4 · Elite 6 · Dread/Boss 8.** Use the higher of the derived formula or the floor. Same principle already applied to Wound Slots — a tier baseline the PC formula can't drop below. It exists because a core-species build often spends its whole Attribute allowance on Skill ceilings and Feat prerequisites, leaving Will and Wits at zero; without a floor, a specialist Elite ends up with a lower breaking point than a Grunt purely as a side-effect of what it's good at.
    - **Monsters are exempt.** They have no Ceiling Rule and no Feat prerequisites competing for their Attribute points, so a monster's low Stress Limit is a deliberate build choice, not residue. The floor is a remedy for a problem monsters don't have — the Frost-Cave Troll and the Barrow-Fang sit at 5 by design.
    - **Wound Threshold gets no floor either**, for anyone. A fragile talker *should* read as fragile, and Wounds carry that fiction where binary Stress doesn't.
    - **Scale and Species modifiers apply after the floor and may take a core-species build below it.** A chosen drawback carrying fiction is not leftover budget, and the floor exists to catch the latter.
- **Special Actions** remain per the Gate Test, on top of the picks above.

*A trained caster is not an innate one.* A core-species Arcanist needs the **Arcane Awakening** feat (spending a pick), a Grimoire, and a free hand, and suffers Blind Casting without them. A monster with the **Innate Magic** trait — the Lizardman Shaman — bypasses all of that.

---

## Traits
### DEFENSIVE & PHYSIOLOGICAL TRAITS

 - _Sinking Gravity:_ The ground immediately within the creatures Threat Zone is perpetually treated as Mire (Difficult Terrain), halving movement and imposing disadvantage to all mobility checks.

- _Resilient:_ Increases the creature’s Stress Limit by +2. May spend **up to 2 Momentum per incoming Strike** from its own Bank to Mitigate damage, reducing that Strike's Impact by 2 per point spent.

**Plated**
- Thick hide, rusted iron carapace, or heavy plate scales shield vital locations.

- Reduces all incoming standard Impact damage by a flat -1.

**Skittering**
- Unnatural speed, shifting limbs, or erratic reflexes make them slippery targets.

- This Creature may move out of Threat zone without  requiring a test, or causing a free strike.

**Massive**
- Massive: Weapons without Sunder, Brutal, or Armour-Piercing have their Impact halved before comparing to its Wounds threshold.

**Flying**
- Wings, unnatural levitation, or a body built for the air.
- Grants a Fly Move (listed in the stat block). While airborne, ignores ground-level Difficult Terrain and obstacles. See Iron World's Movement rules for how this interacts with a land Move.

**Wall-Crawler**
- Moves across walls and ceilings as easily as open ground — never needs an Athletics check to climb, never falls if a climbing surface is disrupted, and can attack from unexpected angles above or beside a Threat Zone.

---

### OFFENSIVE & MARTIAL TRAITS

**Brute**
- Heavy, sweeping strikes designed to shatter shields and break bones.

- When this creature wins an attack action, it inflicts +1 Impact and forces the target back 1 square/5ft. If the target hits a wall or solid obstacle, they immediately take 1 Dissonant Stress from the concussive force.

**First Blood**
- A duellist's opening move, practised until it needs no thought.

- Once per Scene, gains Advantage on the first Melee Strike roll it makes in a fight.

**Vicious**
- Jagged fangs, rusted serrated daggers, or disease-ridden claws that leave lingering wounds.

- If this creature inflicts damage on a player character, the target must immediately make a Prowess check. If they fail they gain the Bleeding condition.

**Swarm:**
- The Swarm gains a +1 bonus to their Clash roll for every additional swarm ally currently engaged with the same target.

**Amorphous**
- Single-target weapons (daggers, arrows, spears) can never inflict a Wound on the Swarm.

---

###  TACTICAL & PSYCHOLOGICAL TRAITS
**Fear Inducing**
- A frightening vision - whether a horrifying beast, or scene of heretical ritual.
-  When a PC engages with this creature or it activates within line of sight, the PC must immediately roll a Resolve check against TN 8.    

- Failure: The PC immediately gains the *Fear*  condition.

**Terrifying**
- A harrowing presence—whether an eldritch abomination or a faceless, silent headsman—that cracks the human mind.

- When a PC engages with this creature or it activates within line of sight, the PC must immediately roll a Resolve check against TN 8.    

- Failure: The PC immediately gains the *Terrified* condition.

_**Fanatical:** Immune to being Intimidated.

**Ambusher:**_ Gains Advantage on the Clash roll if attacking an unaware target from Stealth.

**Cunning Leader**
- A ruthless commander or pack alpha who reads the battlefield with chilling tactical precision.

- At the beginning of the Round, this creature can pass its own position in the Activation order to any allied Fodder unit within its line of sight, allowing the minions to strike with unexpected coordination. Additionally, whenever an ally within its line of sight dies, **this creature banks 1 Momentum** out of pure malice or tactical adaptation. No tier gate is needed — its own Momentum Bank is the cap.

**Whisper Network**
- Somebody in the room always owes this creature a favour.

- At the start of a Scene, as a Free Action, it may name one piece of tactical information the GM would otherwise withhold — an ambush position, a gap in a patrol rotation, which of the party's contacts already sold them out.

**Unstable Volatility**
- A creature bloated with volatile arcane radiation, alchemical compounds, or demonic instability.

- If this creature is struck by a Fates Bounty(meaning the attack roll against it was a Fates bounty), or if it rolls Snake Eyes (fumbles) on its own action, its containment ruptures. All characters (allies and enemies alike) within a 10ft radius must defend against an immediate burst of raw energy, taking 2 points of Locked Stress (if magical) or Dissonant Stress (if alchemical/fire).

**Skittish**
- An animal that has not been broken to violence. The default state of any beast that is not a predator or specifically trained.

- While a fight is underway within 30 ft, at the start of each of the rider's Activations the rider must pass a **Ride check vs TN 8** or the mount **bolts**: it spends its Activation running directly away from the nearest threat at full Move, and the rider may take no action that Activation. *(A **Military saddle** grants Advantage on this check — Hardware.)* An unridden Skittish animal simply flees.

**Battle-Broke**
- What combat training buys, and the only thing it buys.

- The creature loses **Skittish** entirely — it does not bolt, and it can be fought from. It gains **Melee +1** if it had no Melee skill at all, and it ignores the first instance of **Fear** each Scene.

- **Combat training does not make an animal stronger.** Brawn, Wound Threshold, Stress Limit and Move are unchanged. A trained horse is a braver horse, not a bigger one.

**Glamour**
- A face worth following into the trees or across the dunes — and not the one she was born with.

- While the Glamour holds, the creature has **Advantage on Influence checks**, and a PC who declares an Aggressor action **targeting** it must first pass a **Resolve check vs TN 8**. On a failure the action is not lost: the PC cannot bring themselves to strike, and must turn that action on another target or take a non-Aggressor action instead. On a pass, that PC sees through the Glamour for the rest of the Scene and never checks again. An area effect that merely includes the creature does not target it and needs no check.

- **The Glamour drops** for the rest of the Scene the moment the creature takes a Wound, takes Impact from a **Cold Iron** weapon (Hardware) whether or not it Wounds, or is Broken. When it drops, every PC who can see the true face beneath must pass a **Resolve check vs TN 8** or gain the **Fear** condition. A PC who had already seen through it is not spared — knowing it was a mask is not the same as seeing what was under it.

---

### ARCANE TRAITS

**Innate Magic**
- The magic is bone-deep, not book-bound.

- This creature casts Arcane spells without a Grimoire and without a free hand, and never suffers Blind Casting's Disadvantage or Dissonant Stress. Every one of its Innate Spells is treated as under **Paradigm Mastery**, whatever Paradigm (or none) the spell belongs to: a Messy result — Margin 1–2 on a Clash, Margin 0–2 on a Margin of Manifestation or Sustain check — resolves as Clean and costs no Dissonant Stress. Its power was never learned, so it was never imperfect.

- **What it costs.** One pick from the allowance, and it brings **up to three Novice spells** with it — the counterpart of Arcane Awakening's four, one fewer because Mastery here covers every spell rather than one Paradigm and there is no Grimoire to steal. **Each Adept or Master spell costs one further pick** and needs the Arcana rank its tier requires (Adept 2+, Master 3+ — The Marrow, Advancement). List them under **Innate Spells**; each is a full Aggressor or Activation action, one per turn like any other creature's.

---

## Example enemies

### Fodder

#### The Goblin Scrapper

> _Scrawny, twitchy, and desperate. They prefer to strike from the shadows and retreat the moment the tide of battle turns against them._

##### Vital Statistics

- **Tier:** Fodder
- **Type:** Humanoid
- **Move:** 30 ft
- **Attributes (derived only):** Reflex 2 → Activation Order 8 _(Assumed Zero: everything else — incredibly difficult to hit, but folds the moment it's caught.)_
- **Skills:** Acrobatics +2. _(Its preferred defense is Dodge, at 2d6+2.)_
- **Derived stats:**
    - Wound Threshold: **5** _(Base 4 + 1 Leather)_
    - Wound Slots: **1**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 + 0 Fodder)_
    - Momentum Bank: **6** _(4 + Reflex 2)_
- **Equipment:** Leather armour (+1 to Wound Threshold). Rusty Shortsword — Power 2, Sidearm, Finesse; Shoddy Quality (becomes Damaged on a failed or fumbled roll, Ruined if already Damaged). Strike Roll: 2d6.
- **Traits (1):**
    - **Swarm:** The Scrapper gains a +1 bonus to their Clash roll for every additional Goblin ally currently engaged with the same target.
- **Special Actions (1):**
    - **Sabotage:** Instead of a regular attack action, the scrappy, opportunistic goblins try to swipe supplies from the target. Target must pass a TN 8 Acrobatics check or the Community Supply Die is reduced by 1 step.

##### Phases

- **Behaviour when unbroken:** Strikes from the shadows and leans on Swarm's stacking bonus rather than trading blows head-on — more likely to open with Sabotage than commit to a straight Clash.
- **Behaviour when Broken:** Per the GM Tools NPC Stress rules, resolves as **The Rout** — the moment its Stress Limit maxes out, it drops what it's carrying and flees the fight outright.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

---

#### The Corpse-Trench Rat Brood

> _A writhing, starving mass that exists purely to drain Momentum and Wounds before the real threat arrives._

##### Vital Statistics

- **Tier:** Fodder
- **Type:** Beast
- **Move:** 30 ft
- **Attributes (derived only):** Reflex 1 → Activation Order 7 _(Assumed Zero: everything else — quick, but nothing props up a grapple or a mental defense; both resolve at +0.)_
- **Skills:** Melee +1, Acrobatics +1. _(Its preferred defense is Dodge, at 2d6+1.)_
- **Derived stats:**
    - Wound Threshold: **4** _(Base 4 + Brawn 0)_
    - Wound Slots: **1**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 + 0 Fodder)_
    - Momentum Bank: **5** _(4 + Reflex 1)_
- **Equipment:** None — natural bite/claw swarm attacks only. Strike Roll: 2d6+1 (Melee +1).
- **Traits (2):**
    - **Amorphous:** Single-target weapons (daggers, spears, arrows) cannot inflict a Wound. Only Area of Effect (AOE) attacks or weapons with the _Devastating_ or _Siege_ tag can kill them.
    - **Swarm:** The Swarm gains a +1 bonus to their Clash roll for every additional swarm ally currently engaged with the same target.
- **Special Actions (1):**
    - **Passive — Hive Mind:** If three or more swarms are engaged with a single target, they automatically inflict 1 Dissonant Stress on the target, representing the rats crawling over armour and finding gaps.

##### Phases

- **Behaviour when unbroken:** Presses forward as a mass, relying on Amorphous to shrug off single-target weapons and Hive Mind to punish anyone who lets three or more of the brood pile onto them.
- **Behaviour when Broken:** Per the GM Tools NPC Stress rules, resolves as **The Rout** — the brood scatters and flees rather than fighting to the last rat.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

---

#### Imp

> _A wiry knot of red hide, bat-wings, and barbed tail, spat out of the rift laughing — it doesn't fight to win, it fights to make you flinch._

##### Vital Statistics

- **Tier:** Fodder
- **Type:** Daemon
- **Move:** Fly 30 ft (no land Move — always airborne)
- **Attributes (derived only):** Reflex 2 → Activation Order 8 _(Assumed Zero: everything else — quick and erratic, but folds if it's actually caught.)_
- **Skills:** Melee +1, Acrobatics +1. _(Its preferred defense is Dodge, at 2d6+1.)_
- **Derived stats:**
    - Wound Threshold: **4** _(Base 4 + Brawn 0)_
    - Wound Slots: **1**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 + 0 Fodder)_
    - Momentum Bank: **6** _(4 + Reflex 2)_
- **Equipment:** None — natural weapon only. Claws/barbed tail (Power 0). Strike Roll: 2d6+1 (Melee +1).
- **Traits (2):**
    - **Flying:** Bat-wings grant a Fly Move (see above). While airborne, ignores ground-level Difficult Terrain and obstacles.
    - **Skittering:** Unnatural speed, shifting limbs, or erratic reflexes make them slippery targets. This creature may move out of a Threat Zone without requiring a test, or causing a free strike.
- **Special Actions (1):**
    - **Hellfire Needle:** _Trigger:_ Instead of a regular attack, declared against a target within 30 ft. _Effect:_ The Imp spits a mote of hellfire. Target must pass a TN 8 Prowess check or suffer 1 Dissonant Stress and gain the Ablaze condition.

##### Phases

- **Behaviour when unbroken:** Darts in and out of range using Skittering to avoid free strikes, peppering PCs with Hellfire Needle rather than closing to melee.
- **Behaviour when Broken:** Resolves as **The Rout** — once its Stress maxes out, it flees back toward whatever rift or shadow it came through rather than keep tormenting a fight it can't win.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

#### Skink

> _Quick, quiet, and half your size — it was never going to fight you fair, and it doesn't have to._

##### Vital Statistics

- **Tier:** Fodder
- **Type:** Humanoid
- **Size:** Small (Scale -1)
- **Move:** 35 ft
- **Attributes (derived only):** Reflex 2 → Activation Order 8 _(Assumed Zero: everything else.)_
- **Skills (2):** Ranged +1, Stealth +1.
- **Derived stats:**
    - Wound Threshold: **3** _(Base 4 - 1 Small + Brawn 0)_
    - Wound Slots: **1**
    - Stress Limit: **3** _(4 - 1 Small + 0 Fodder)_
    - Momentum Bank: **6** _(4 + Reflex 2)_
- **Equipment:** Blowgun (Power 0, 2H, Ranged Short/20 ft, Concealable). Shoot Roll: 2d6+1 (Ranged +1), Impact = Margin + 0. _Its real threat is Numbing Venom below, which needs no Clash at all — the plain Shoot is what the Ranged rank makes possible._
- **Traits (1):**
    - **Skittering:** Unnatural speed, shifting limbs, or erratic reflexes make them slippery targets. This creature may move out of a Threat Zone without requiring a test, or causing a free strike.
- **Special Actions (1):**
    - **Numbing Venom:** _Trigger:_ Instead of a regular attack, declared against a target within 20 ft. _Effect:_ A dart tipped with numbing jungle toxin strikes the target. Target must pass a TN 8 Prowess check or gain the Rigor condition, denying Parry or Dodge on their next defense.

##### Phases

- **Behaviour when unbroken:** Stays hidden and lets Stealth do the work, leading with Numbing Venom from range and falling back on a plain dart once the venom is spent, rather than closing to melee — retreating through gaps and crevices too small for a Standard-Scale pursuer.
- **Behaviour when Broken:** Resolves as **The Rout** — vanishes into tunnels only something Small-Scale can follow.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

#### Giant Spider

> _Bloated on temple rats and worse, it hangs motionless in the dark until the webbing twitches — then it's already moving._

##### Vital Statistics

- **Tier:** Fodder
- **Type:** Beast
- **Size:** Large (Scale +1)
- **Move:** 30 ft
- **Attributes (derived only):** Reflex 1 → Activation Order 7 _(Assumed Zero: everything else.)_
- **Skills:** Melee +1, Stealth +1.
- **Derived stats:**
    - Wound Threshold: **6** _(4 + Scale +2 + Brawn 0)_
    - Wound Slots: **1**
    - Stress Limit: **4** _(4 + 0 Fodder)_
    - Momentum Bank: **5** _(4 + Reflex 1)_
- **Equipment:** None — natural weapon only. Fangs (Power 1). Strike Roll: 2d6+1 (Melee +1).
- **Traits (2):**
    - **Wall-Crawler:** Moves across walls and ceilings as easily as open ground — never needs an Athletics check to climb, never falls if a climbing surface is disrupted, and can attack from unexpected angles above or beside a Threat Zone.
    - **Swarm:** Gains a +1 bonus to its Clash roll for every additional Giant Spider currently engaged with the same target.
- **Special Actions (1):**
    - **Silk Snare:** _Trigger:_ Instead of a regular attack, declared against a target within Reach. _Effect:_ Target must pass a TN 8 Acrobatics check or gain the Anchored condition, webbed fast until they break free (per Anchored's normal rules).

##### Phases

- **Behaviour when unbroken:** Lurks on the walls or ceiling using Wall-Crawler for a surprise angle, Silk-Snares whoever gets too close, and lets Swarm's stacking bonus punish anyone who lingers once more spiders close in.
- **Behaviour when Broken:** Resolves as **The Rout** — scuttles back up into the webbing and cracks overhead.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

#### Gutter Rat

> _A blur of small hands and someone else's coin purse. You notice the knife after you notice the purse is gone._

##### Vital Statistics

- **Tier:** Fodder
- **Type:** Humanoid (Halfling)
- **Size:** Small (Scale -1)
- **Move:** 30 ft
- **Attributes (1 — Fodder allowance):** Reflex 1.
- **Skills (2):** Stealth +2.
- **Derived stats:**
    - Wound Threshold: **3** _(Base 4 - 1 Small + Brawn 0)_
    - Wound Slots: **1**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 + 0 Fodder — no Scale penalty: a Halfling's Small Stature explicitly exempts them from the usual Small-Scale Stress reduction, per The Marrow.)_
    - Activation Order: **7** _(6 + Reflex 1)_
    - Momentum Bank: **5** _(4 + Reflex 1)_
- **Equipment:** Punching Dagger (Power 0, 1H, Concealable, Close-Quarters, Inertia). Strike Roll: 2d6 (Melee +0).
- **Species Traits (free — see The Marrow):**
    - **Underfoot:** Gains Advantage on Stealth checks as long as it has cover, is Obscured, or is moving through the space of a larger creature.
    - **Halfling Luck:** Once per session, may completely ignore the mechanical effects of a Fumble (Snake Eyes). The action still fails; the Stress penalty doesn't land.
- **Feats / Spells (0 of 2 picks spent — Fodder, Tier 1 ceiling):** None.
- **Special Actions (1):**
    - **Sucker Stab:** _Trigger:_ Instead of a regular attack, declared against a target within 5 ft. _Effect:_ A short blade driven up under the ribs. The target must pass a TN 8 Prowess check or take 2 Dissonant Stress — enough, from a standing start, to push most Green characters to the Winded threshold on its own.

##### Phases

- **Behaviour when unbroken:** Works the edges — never the first into a fight and never alone, leaning on Underfoot to stay unseen until someone is already occupied, then knifing whoever is distracted.
- **Behaviour when Broken:** Resolves as **The Rout** — scatters into the crowd, the drain, or the gap between two buildings that nobody larger can follow.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

#### Back-Alley Brawler

> _Rented muscle, paid enough to hurt you and not one copper more. Hitting it does not make it stop; hitting it makes it pay attention._

##### Vital Statistics

- **Tier:** Fodder
- **Type:** Humanoid (Half-Orc)
- **Size:** Standard
- **Move:** 30 ft
- **Attributes (1 — Fodder allowance):** Brawn 1.
- **Skills (2):** Melee +2.
- **Derived stats:**
    - Wound Threshold: **5** _(Base 4 + Brawn 1)_
    - Wound Slots: **1**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 + 0 Fodder)_
    - Activation Order: **6** _(6 + Reflex 0)_
    - Momentum Bank: **4** _(4 + Reflex 0)_
- **Equipment:** Club (Power 0, 1H, Bash — improvised, always available). Strike Roll: 2d6+2 (Melee +2).
- **Species Traits (free — see The Marrow):**
    - **Blood Frenzy:** When this creature suffers a Wound, the adrenaline spikes — it immediately clears 1 Dissonant Stress. Injuring it clears its panic and focuses its rage.
    - **Menacing:** Gains Advantage on Influence checks when attempting to intimidate anyone smaller or weaker than itself.
- **Feats / Spells (0 of 2 picks spent — Fodder, Tier 1 ceiling):** None.
- **Special Actions (1):**
    - **Haymaker:** _Trigger:_ Instead of a regular attack. _Effect:_ A wild, overcommitted swing — +1 Impact on a hit, but the Brawler suffers Disadvantage on its next Reactor roll.

##### Phases

- **Behaviour when unbroken:** Closes immediately and swings, using Menacing to pick the smallest-looking target in the room and Haymaker whenever it thinks the fight is nearly over.
- **Behaviour when Broken:** Resolves as **Frenzy** — the dynamic Blood Frenzy already implies. It loses its defensive options entirely but gains Advantage on all Strike rolls until it drops.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

#### Watch Patrolman

> _Paid to be seen, not to win. The whistle around his neck is the dangerous part of him._

##### Vital Statistics

- **Tier:** Fodder
- **Type:** Humanoid (Human)
- **Size:** Standard
- **Move:** 30 ft
- **Attributes (1 — Fodder allowance):** Brawn 1.
- **Skills (2):** Melee +2.
- **Derived stats:**
    - Wound Threshold: **6** _(Base 4 + Brawn 1 + Leather 1)_
    - Wound Slots: **1**
    - Stress Limit: **5** _(4 + Will 0 + Wits 0 + 1 Indomitable Spirit + 0 Fodder)_
    - Activation Order: **6** _(6 + Reflex 0)_
    - Momentum Bank: **3** _(4 + Reflex 0, then -1 for Steady, Not Sharp)_
- **Equipment:** Sap (Power 2, 1H, **non-Lethal**, Concealable), Leather (+1 Armour, Light). Strike Roll: 2d6+2 (Melee +2). _His Sap can only ever inflict Stress — a Patrolman cannot Wound anyone, no matter how well he rolls. The Watch subdues; it does not kill._
- **Species Traits (free — see The Marrow):**
    - **Indomitable Spirit:** Base Stress Limit increased by +1 (already folded into the derived stat above).
    - **Steady, Not Sharp (Drawback):** Momentum Bank cap reduced by 1 (already folded in above).
- **Feats / Spells (0 of 2 picks spent — Fodder, Tier 1 ceiling):** None.
- **Special Actions (1):**
    - **Baton Charge:** _Trigger:_ Instead of a regular attack. _Effect:_ He closes the distance and swings in one motion — move up to his full Move and Strike, at Disadvantage on the Clash.

##### Phases

- **Behaviour when unbroken:** Never fights alone and never leads. Closes with Baton Charge when he has a partner already engaged, otherwise holds ground and shouts for the Sergeant.
- **Behaviour when Broken:** Resolves as **The Rout** — the pay is not good enough. He runs for the nearest other Patrolman, then past him.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

#### The Rooftop Slinger

> _Never comes down, never closes in, never runs out of roof tiles. The gang pays him to make the street feel narrow._

##### Vital Statistics

- **Tier:** Fodder
- **Type:** Humanoid (Dwarf)
- **Size:** Standard
- **Move:** 30 ft
- **Attributes (1 — Fodder allowance):** Reflex 1.
- **Skills (2):** Ranged +2.
- **Derived stats:**
    - Wound Threshold: **5** _(Base 4 + Brawn 0 + 1 Stone-Bones)_
    - Wound Slots: **1**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 + 0 Fodder)_
    - Activation Order: **7** _(6 + Reflex 1)_
    - Momentum Bank: **5** _(4 + Reflex 1)_
- **Equipment:** Sling (Power 0, 1H, Ranged — Max Medium / 50 ft, Sidearm). Shoot Roll: 2d6+2 (Ranged +2). Impact = Margin + 0 — he is not trying to kill anyone, and mostly can't.
- **Species Traits (free — see The Marrow):**
    - **Stone-Bones:** Base Wound Threshold increased by +1 (already folded into the derived stat above).
    - **Subterranean Senses:** Advantage on Notice checks while underground, or when examining stonework.
    - **Stumpy (Drawback):** Disadvantage on Athletics checks when sprinting across open ground or in a chase. _Costs him nothing in this role — he does not chase, and that is the point._
- **Feats / Spells (0 of 2 picks spent — Fodder, Tier 1 ceiling):** None.
- **Special Actions (1):**
    - **Keep Their Heads Down:** _Trigger:_ Instead of a regular Shoot, declared against one target he can see within Medium range. _Effect:_ The stone cracks off the wall beside their head. The target must pass a **Resolve** check (TN 8) or gain **Suppressed** (Iron Core) — Disadvantage on any action other than Attack, Block, Brace or Regroup, plus 1 Dissonant Stress for breaking cover. No Clash: this is pressure, not a hit.

##### Phases

- **Behaviour when unbroken:** Takes high ground before the fight starts and never leaves it. Leads with Keep Their Heads Down on whoever looks most likely to reposition — a caster, a flanker — and only Shoots for Impact once the street is already committed.
- **Behaviour when Broken:** Resolves as **The Rout** — drops the sling and goes over the ridgeline. Stumpy means anyone who gets onto the roof will catch him, which is the trade for a full fight spent untouchable.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

#### The Wretch

> _What the marsh, the barrow or the dunes left behind when it was finished with someone. It does not remember being a person. It remembers being cold, or drowning, or thirsty._

##### Vital Statistics

- **Tier:** Fodder
- **Type:** Undead
- **Size:** Standard
- **Move:** 30 ft
- **Attributes (derived only):** Brawn 1 _(Assumed Zero: everything else.)_
- **Skills (1):** Melee +1.
- **Derived stats:**
    - Wound Threshold: **5** _(Base 4 + Brawn 1)_
    - Wound Slots: **1**
    - Stress Limit: **4** _(4 + 0 Fodder)_
    - Activation Order: **6** _(6 + Reflex 0)_
    - Momentum Bank: **4** _(4 + Reflex 0)_
- **Equipment:** Claws (Power 1). Strike Roll: 2d6+1 (Melee +1), Impact = Margin + 1.
- **Traits (1):**
    - **Vicious:** If this creature inflicts damage on a player character, the target must immediately pass a Prowess check or gain the **Bleeding** condition.

##### Environmental Skins

A Wretch is made by the place that killed it, and it carries that place with it. **A Wretch is immune to the Hazard Check of its own terrain** (_Iron World_, Environmental Hazards) — it accrues no Locked Stress from the blizzard, the desert or the water that made it, while that same ground is costing the party 1d3 a failure. Everything else below is a descriptor and **one rider that is inert outside its home ground**. No skin changes Brawn, Wound Threshold, Wound Slots, Stress Limit, Move or Power. _A Bog-Wretch is a wetter Wretch, not a stronger one._

| Skin | Terrain | Claws | Rider (inert elsewhere) |
| --- | --- | --- | --- |
| **Bog-Wretch** | freezing water — marsh, flooded sluice, tidal mud | waterlogged | Ignores difficult terrain from mud and standing water. **Advantage on its Clash against a Drowned target.** |
| **Grave-Wretch** | a blizzard — snowfield, frost cave, barrow ice | frost-cracked | Ignores difficult terrain from ice and snow. **Advantage on its Clash against a target suffering Rigor.** |
| **Dust-Wretch** | a scorching desert — dunes, salt pan, dry tomb | sun-split | Ignores difficult terrain from sand and scree. **Desiccated: fire attacks against it gain +2 Impact.** |

##### Phases

- **Behaviour when unbroken:** Advances on whoever is nearest, in a straight line. No tactics, no hesitation, no self-preservation. Field them three or four at a time: individually they are harmless, and their entire job is pressure layered underneath something else — a hazard, a pursuit, a Drowned party still coughing up water.
- **Behaviour when Broken:** Resolves as **The Rout**, undead-flavoured — it does not flee and it does not yield. At maximum Stress the animating force gutters out and it comes apart where it stands, removed from the encounter rather than destroyed by anyone's hand. _(Mechanically identical to a Rout: it stops being a combatant without being killed. Same shape as the Grave-Warden's construct-flavoured Rout.)_
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

#### Riding Horse

> "It will carry you all day and twenty miles further than you deserve. It will not carry you into a fight."

##### Vital Statistics

- **Tier:** Fodder
- **Type:** Beast
- **Size:** Large (+1) | **Move:** 40 ft (8 squares)
- **Attributes (derived only):** Brawn 1 → Wound Threshold; Reflex 1 → Activation Order 7, Momentum Bank 5 _(Assumed Zero: Wits, Will — it is an animal, and a nervous one.)_
- **Skills:** Athletics +2. **No Melee — it will not fight.**
- **Derived stats:**
    - Wound Threshold: **7** _(4 + Brawn 1 + Scale +2)_
    - Wound Slots: **1**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 + 0 Fodder)_
    - Activation Order: **7** _(6 + Reflex 1)_
    - Momentum Bank: **5** _(4 + Reflex 1)_
- **Equipment:** whatever tack its owner bought (Hardware).
- **Traits (1):**
    - **Skittish.** See the Trait Manifest. **Combat training replaces this with Battle-Broke** and costs +50% of the animal's price (Hardware).

##### Phases

- **Behaviour when unbroken:** It does what it is pointed at, until something frightens it. It is transport, not a weapon — a Riding Horse in a fight is a liability its rider has to keep passing Ride checks to hold on to.
- **Behaviour when Broken:** **Rout**, and completely. A panicking horse is not a combatant; it is a large animal leaving.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

---

### Grunt

#### Orc Line-Breaker

> _A wall of scarred green muscle and notched iron, swinging a two-handed axe built to open gaps in a shield wall — where the Line-Breaker plants its feet, formations stop holding._

##### Vital Statistics

- **Tier:** Grunt
- **Type:** Humanoid
- **Move:** 30 ft
- **Attributes (derived only):** Brawn 2 → Wound Threshold; Reflex 0 → Activation Order 6, reduced to **5** by the Greataxe's Cumbersome tag _(Assumed Zero: Dodge, Notice, Resolve, Arcana — hits hard and blocks well, but is terrible at dodging or resisting mind-altering Arcana.)_
- **Skills:** Melee +4, Block +2.
- **Derived stats:**
    - Wound Threshold: **6** _(Base 4 + Brawn 2)_
    - Wound Slots: **2**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 + 0 Grunt)_
    - Momentum Bank: **4** _(4 + Reflex 0)_
- **Equipment:** Greataxe (Power 5, 2H, Inertia, Cumbersome). No shield — Block is fought bare-handed here: it still contests the Clash at +2, but with no Shield Value to subtract from the Impact on a loss. Strike Roll: 2d6+4 (Melee +4).
- **Traits (1):**
    - **Plated:** Reduces all incoming standard Impact damage by a flat -1.
- **Special Actions (1):**
    - **Unstoppable Mass:** _Trigger:_ Declared on a successful Melee clash with a Margin of 3+ (Clean or better). _Effect:_ Taxes player for 1Momentum or violently shoves them 10ft out of position.

##### Phases

- **Behaviour when unbroken:** Holds the line with wide, two-handed axe swings, leaning on Plated to shrug off incoming Impact and triggering Unstoppable Mass on a clean clash win to tax Momentum or shove a PC out of formation.
- **Behaviour when Broken:** Per the GM Tools NPC Stress rules, resolves as **Frenzy** rather than The Rout — it loses Block entirely but gains Advantage on all Strike rolls until it dies.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

---

#### Lizardman

> _A temple guardian in scale and spear, patient enough to let the pit trap and the skinks do the thinning before it ever has to fight._

##### Vital Statistics

- **Tier:** Grunt
- **Type:** Humanoid
- **Move:** 30 ft
- **Attributes (derived only):** Brawn 2 → Wound Threshold _(Assumed Zero: everything else.)_
- **Skills:** Melee +3, Block +2.
- **Derived stats:**
    - Wound Threshold: **6** _(Base 4 + Brawn 2)_
    - Wound Slots: **2**
    - Stress Limit: **4** _(4 + 0 Grunt)_
    - Activation Order: **6** _(6 + Reflex 0)_
    - Momentum Bank: **4** _(4 + Reflex 0)_
- **Equipment:** Spear (Power 2, Reach, Thrown) and a Kite/Round Shield (4 SV, Cover). Strike Roll: 2d6+3 (Melee +3).
- **Traits (1):**
    - **Plated:** Natural scaled hide reduces all incoming standard Impact damage by a flat -1.
- **Special Actions (1):**
    - **Snapping Counter:** _Trigger:_ Declared when this creature wins a Clash as the Reactor (Block) with a Margin of 3+ (Clean or better). _Effect:_ Instead of merely holding the line, it lunges with a vicious bite alongside the block — the attacker takes 1 Dissonant Stress from the sudden retaliation.

##### Phases

- **Behaviour when unbroken:** Holds its Spear's Reach behind the Shield, using Snapping Counter to punish anyone who presses the attack rather than chasing them down.
- **Behaviour when Broken:** Resolves as **The Rout** — breaks and flees deeper into the temple, straight toward the inner chamber, giving whatever guards it there fair warning.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

#### Knuckle-Duster

> _A working professional. Nothing personal — unless you make it personal, and people who make it personal stop being seen around here._

##### Vital Statistics

- **Tier:** Grunt
- **Type:** Humanoid (Human)
- **Move:** 30 ft
- **Attributes (2 — Grunt allowance):** Brawn 2.
- **Skills (5):** Melee +3, Prowess +2.
- **Derived stats:**
    - Wound Threshold: **6** _(Base 4 + Brawn 2)_
    - Wound Slots: **2**
    - Stress Limit: **5** _(4 + Will 0 + Wits 0 + 1 Indomitable Spirit + 0 Grunt)_
    - Activation Order: **6** _(6 + Reflex 0)_
    - Momentum Bank: **3** _(4 + Reflex 0, then -1 for Steady, Not Sharp)_
- **Equipment:** Sap (Power 2, 1H, non-Lethal, Concealable). Strike Roll: 2d6+3 (Melee +3).
- **Species Traits (free — see The Marrow):**
    - **Indomitable Spirit:** A slightly higher breaking point — base Stress Limit increased by +1 (already folded into the derived stat above).
    - **Steady, Not Sharp (Drawback):** Momentum Bank cap reduced by 1 (already folded in above). He burns slow and steady; he is the last one in the room to reach a 3-Momentum spend.
- **Feats / Spells (1 pick — Grunt, Tier 1 ceiling):**
    - **Lethal Strikes** _(Tier 1; prereq Melee 1 ✓)_ — his unarmed strikes deal Lethal Impact and can inflict physical Wounds. The Sap is non-Lethal by design; his hands are not. Which one you get is his decision, made fresh each round.
- **Traits (1):**
    - **Brute:** Heavy, sweeping strikes designed to shatter shields and break bones. When this creature wins an attack action, it inflicts +1 Impact and forces the target back 1 square/5 ft. If the target hits a wall or solid obstacle, they immediately take 1 Dissonant Stress from the concussive force.
- **Special Actions (1):**
    - **Debt Collector's Grip:** _Trigger:_ Declared after a successful Melee clash with a Margin of 3+ (Clean or better). _Effect:_ Instead of dealing normal Impact, it takes a fistful of collar and shoves the target against the nearest wall — the target gains the **Anchored** condition. You're not going anywhere until this conversation is finished.

##### Phases

- **Behaviour when unbroken:** Picks one target and stays on them, using Brute to walk them backwards into a wall or an alley mouth and Debt Collector's Grip to pin whoever is trying to leave. The Sap is deliberate — a body is paperwork, a broken hand is a message.
- **Behaviour when Broken:** Resolves as **The Rout** — a professional, not a martyr. Disappears into streets he knows far better than the party does.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

#### The Bouncer

> _Holds the door like it's the only thing in the world worth holding. For the length of his shift, it is._

##### Vital Statistics

- **Tier:** Grunt
- **Type:** Humanoid (Dwarf)
- **Move:** 30 ft
- **Attributes (2 — Grunt allowance):** Brawn 2.
- **Skills (5):** Melee +2, Block +3.
- **Derived stats:**
    - Wound Threshold: **7** _(Base 4 + Brawn 2 + 1 Stone-Bones)_
    - Wound Slots: **2**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 + 0 Grunt)_
    - Activation Order: **6** _(6 + Reflex 0)_
    - Momentum Bank: **4** _(4 + Reflex 0)_
- **Equipment:** Club (Power 0, 1H, Bash — improvised, always available). No shield — Block is fought bare-handed here, per the Orc Line-Breaker precedent: it still contests the Clash at +3, but with no Shield Value to subtract from the Impact on a loss. Strike Roll: 2d6+2 (Melee +2).
- **Species Traits (free — see The Marrow):**
    - **Stone-Bones:** Dense enough to shrug off what would drop a taller man — base Wound Threshold increased by +1 (already folded into the derived stat above).
    - **Subterranean Senses:** Gains Advantage on Notice checks while underground, or when examining stonework and engineering — cellars, sewer runs, and back rooms are his native ground.
    - **Stumpy (Drawback):** Disadvantage on Athletics checks during a chase or sprinting across open ground. He does not pursue, and everyone involved knows it.
- **Feats / Spells (1 pick — Grunt, Tier 1 ceiling):**
    - **Iron Grip** _(Tier 1; prereq Melee 1 or Prowess 1 ✓)_ — when a Clash ties and the weapons bind, he automatically banks 1 Momentum as he secures the better footing. A doorman whose entire job is jamming people up generates Momentum from doing exactly that.
- **Special Actions (1):**
    - **Choke the Doorway:** _Trigger:_ Declared when this creature is the sole occupant of a doorway, alley mouth, stairwell, or similarly narrow chokepoint (GM's call) and wins a Block Clash as the Reactor. _Effect:_ Rather than simply absorbing the hit, he puts his shoulder into it — the attacker is shoved back 1 square and cannot re-engage this activation.

##### Phases

- **Behaviour when unbroken:** Never leaves the chokepoint voluntarily. Lets the party come to him, blocks rather than swings, and relies on Choke the Doorway to make a narrow space cost more than it's worth.
- **Behaviour when Broken:** Resolves as **Surrender** — a working stiff who yields rather than dies for a boss who isn't even in the room. Perfectly willing to discuss where that boss is, for the right consideration.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

#### Watch Sergeant

> _Twenty years of telling people what the law is. He has never once had to raise his voice twice._

##### Vital Statistics

- **Tier:** Grunt
- **Type:** Humanoid (Human)
- **Size:** Standard
- **Move:** 30 ft
- **Attributes (2 — Grunt allowance):** Brawn 1, Wits 1.
- **Skills (5):** Melee +3, Influence +2. _(Ceilings: Melee 4 (Brawn 1); Influence 3 (Will 0) — both in band.)_
- **Derived stats:**
    - Wound Threshold: **6** _(Base 4 + Brawn 1 + Leather 1)_
    - Wound Slots: **2**
    - Stress Limit: **6** _(4 + Will 0 + Wits 1 + 1 Indomitable Spirit + 0 Grunt)_
    - Activation Order: **6** _(6 + Reflex 0)_
    - Momentum Bank: **3** _(4 + Reflex 0, then -1 for Steady, Not Sharp)_
- **Equipment:** Shortsword (Power 2, 1H, Sidearm, Finesse), Sap (Power 2, 1H, **non-Lethal**, Concealable), Leather (+1 Armour, Light). Strike Roll: 2d6+3 (Melee +3). _He carries both on purpose: the Sap for an arrest, the Shortsword once it stops being one. Which one he draws is the scene's escalation dial._
- **Species Traits (free — see The Marrow):**
    - **Indomitable Spirit:** Base Stress Limit increased by +1 (already folded into the derived stat above).
    - **Steady, Not Sharp (Drawback):** Momentum Bank cap reduced by 1 (already folded in above).
- **Allowance (2 — Grunt): 1 Trait + 1 Feat.**
    - **Cunning Leader** _(Trait)_ — at the beginning of the Round, he can pass his own position in the Activation order to any allied Fodder unit within his line of sight, letting the Patrolmen strike with unexpected coordination. Additionally, whenever an ally within his line of sight dies, **he banks 1 Momentum**. His Bank of 3 is the cap — no tier gate required.
    - **Battlefield Orator** _(Feat, Tier 1 — prerequisite Influence 2, met)_ — spend an Action to shout orders or hurl insults. Choose one: an ally immediately clears 1d6 Dissonant Stress, OR an engaged enemy suffers -2 on their next Defense roll.
- **Special Actions (1):**
    - **Hold the Line:** _Trigger:_ Instead of a regular attack. _Effect:_ He plants and calls the formation in. Every allied Watch member within 10 ft, himself included, gains +1 to Block rolls until the start of his next activation.

##### Phases

- **Behaviour when unbroken:** Fights last and talks first. Opens with Battlefield Orator to strip a Defense roll, uses Cunning Leader to let two Patrolmen swing before he does, and draws the Shortsword only once someone has drawn steel on him.
- **Behaviour when Broken:** Resolves as **Surrender** — a professional, not a fanatic. He calls the withdrawal and expects to be obeyed, and will trade information for being allowed to walk.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

#### The Grave-Warden

> _A rusted, robed shape that was once a mourning-effigy, animated to guard both a patriarch's bones and his hidden coin from grasping relatives and thieves alike._

##### Vital Statistics

- **Tier:** Grunt
- **Type:** Construct
- **Size:** Standard
- **Move:** 30 ft
- **Attributes (derived only):** Brawn 2 → Wound Threshold _(Assumed Zero: everything else. Activation Order 6 — it does not hurry, and it cannot be hurried.)_
- **Skills (4):** Melee +4.
- **Derived stats:**
    - Wound Threshold: **6** _(Base 4 + Brawn 2)_
    - Wound Slots: **2**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 + 0 Grunt — monster build, exempt from the core-species Stress Limit floor)_
    - Activation Order: **6** _(6 + Reflex 0)_
    - Momentum Bank: **4** _(4 + Reflex 0)_
- **Equipment:** Ancient bone blade (Power 2). Strike Roll: 2d6+4 (Melee +4).
- **Traits (1):**
    - **Fear Inducing:** When a PC engages with it or it activates within line of sight, that PC must immediately roll a **Resolve** check against TN 8. Failure: the PC gains the *Fear* condition. _(Cleared per Iron Core — Regroup out of sight or cover of the source, or automatically if the source is destroyed.)_
- **Special Actions (1):**
    - **Grinding Assault:** _Trigger:_ Declared immediately after the Warden wins a Strike's Clash with a Margin of 3+ (Clean or better). _Effect:_ It bears down and grinds the blade along the target's guard — 1 Dissonant Stress in addition to the normal Impact.

##### Phases

- **Behaviour when unbroken:** Advances in a straight line toward whoever stands closest to what it guards. No tactics, no flanking, no hesitation — it is not afraid and does not need to be clever. It will walk through a flanking position rather than avoid one.
- **Behaviour when Broken:** Resolves as **The Rout**, construct-flavoured — it does not flee and it does not yield. At maximum Stress the binding fails and it seizes up mid-swing, frozen in place and removed from the tactical equation for the rest of the encounter. _(Mechanically identical to a Rout: it stops being a combatant without being destroyed.)_
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

#### The Crossbow Enforcer

> _He does not want the room. He wants the doorway, from forty feet away, with something already loaded._

##### Vital Statistics

- **Tier:** Grunt
- **Type:** Humanoid (Half-Orc)
- **Size:** Standard
- **Move:** 30 ft
- **Attributes (2 — Grunt allowance):** Reflex 1, Brawn 1.
- **Skills (5):** Ranged +3, Stealth +1, Notice +1.
- **Derived stats:**
    - Wound Threshold: **6** _(Base 4 + Brawn 1 + Leather 1)_
    - Wound Slots: **2**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 + 0 Grunt)_
    - Activation Order: **10** _(6 + Reflex 1, +3 from Quick)_
    - Momentum Bank: **5** _(4 + Reflex 1)_
- **Equipment:** Light Crossbow (Power 3, 2H, Ranged — Max Long / 120 ft, **Armour Piercing**, **Reload**), Leather (+1 Armour, Light). Shoot Roll: 2d6+3 (Ranged +3). Impact = Margin + 3, **ignoring 2 points of the target's Armour Value**. _No melee skill at all — 2d6+0 the moment anyone reaches him. Closing the distance is the answer to him, and it is meant to be._
- **Species Traits (free — see The Marrow):**
    - **Blood Frenzy:** When he suffers a Wound, the adrenaline spikes — he immediately clears 1 Dissonant Stress.
    - **Menacing:** Advantage on Influence checks when attempting to intimidate anyone smaller or weaker than himself.
    - **Outcast (Drawback):** Disadvantage on social checks when dealing with civilised strangers who don't know him.
- **Allowance (2 — Grunt): 1 Feat + 1 Trait.**
    - **Quick** _(Feat, Tier 1; prereq Reflex 1 ✓)_ — +3 to Activation Order, and breaks ties against anyone without it. He shoots before the party has closed.
    - **Ambusher** _(Trait)_ — gains Advantage on the Clash roll if attacking an unaware target from Stealth. The opening bolt is the dangerous one.
- **Special Actions (1):**
    - **Brace and Reload:** _Trigger:_ Instead of a regular action — which the **Reload** tag already obliges him to spend. _Effect:_ He winds the crank braced against cover and sets his stance while he does it: his next Shoot this encounter gains **+2** to the Clash. Turns the dead half of his firing cycle into a threat rather than a gap.

##### Phases

- **Behaviour when unbroken:** Opens from Stealth with Ambusher for an Advantaged first bolt, then alternates Brace and Reload with Shoot — one threatening shot every two rounds rather than a steady stream. Backs away from anyone closing and will trade ground freely to keep forty feet of it.
- **Behaviour when Broken:** Resolves as **Frenzy** — Blood Frenzy already points this way. He drops the crossbow and, having no melee skill whatsoever, throws himself at the nearest PC with Advantage on Strikes and 2d6+0 behind it.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

#### Heavy Horse (Warhorse)

> "Bred for weight, not speed. It has been taught that the noise and the smell mean work, not danger."

##### Vital Statistics

- **Tier:** Grunt
- **Type:** Beast
- **Size:** Large (+1) | **Move:** 35 ft (7 squares)
- **Attributes (derived only):** Brawn 3 → Wound Threshold; Reflex 1 → Activation Order 7, Momentum Bank 5 _(Assumed Zero: Wits, Will.)_
- **Skills:** Melee +2 _(iron-shod hooves)_, Athletics +2.
- **Derived stats:**
    - Wound Threshold: **9** _(4 + Brawn 3 + Scale +2)_
    - Wound Slots: **2**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 — monster build, exempt from the core-species Stress Limit floor)_
    - Activation Order: **7** _(6 + Reflex 1)_
    - Momentum Bank: **5** _(4 + Reflex 1)_
- **Equipment:** tack per Hardware. **Barding** is priced at 2× the base armour's cost and applies the same tag penalties a rider would suffer; its Armour Value adds to the Wound Threshold above.
- **Traits (1):**
    - **Skittish** _(a warhorse that has not actually been trained is still a horse)_. **Combat training replaces this with Battle-Broke** and costs +50% of the animal's price (Hardware). A **Battle-Broke** warhorse is the standard cavalry mount.

##### Phases

- **Behaviour when unbroken:** Heavier and slower than a Riding Horse, and it hits — Melee +2 off the hooves, with Overwhelming Force applying against any Standard-scale defender (Metal meet Flesh). Its value is **Brawn 3**: the Wound Threshold to survive being shot at, and the carrying capacity for barding.
- **Behaviour when Broken:** **Rout** if Skittish; a **Battle-Broke** warhorse **Frenzies** instead — it has been taught that the answer to fear is forward.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

#### The Hag

> _Something old that learned to wear a woman's shape — badly, or far too well, depending on where it lives. Every hag curses. What changes between the sea and the sand is the face she does it with._

##### Vital Statistics

- **Tier:** Grunt
- **Type:** Fey, Humanoid _(Cold Iron's Bane applies — Hardware.)_
- **Size:** Standard
- **Move:** 30 ft
- **Attributes (derived only):** Brawn 1, Wits 1 _(Assumed Zero: Reflex, Will — older than she is quick, and more cunning than steady.)_
- **Skills (5):** Arcana +3, Melee +1, Influence +1. _(Casts at 2d6+3, claws and Parries at 2d6+1. **Resolve +0** — she curses far better than she resists one, and a party Witch can out-hex her.)_
- **Derived stats:**
    - Wound Threshold: **5** _(Base 4 + Brawn 1 — **4** against a Cold Iron weapon)_
    - Wound Slots: **2**
    - Stress Limit: **5** _(4 + Will 0 + Wits 1 + 0 Grunt — monster build, exempt from the core-species Stress Limit floor)_
    - Activation Order: **6** _(6 + Reflex 0)_
    - Momentum Bank: **4** _(4 + Reflex 0)_
- **Equipment:** None — Talons (Power 1), iron-hard and never clean. Strike Roll: 2d6+1 (Melee +1), Impact = Margin + 1. No Grimoire and no focus: Innate Magic needs neither.
- **Allowance (2 — Grunt): 2 Traits.**
    - **Innate Magic** _(Trait — see Arcane Traits)_ — her two Innate Spells, below, cast without book or free hand; every Messy result resolves Clean.
    - **Her Guise** _(Trait — fixed by her Skin, below)_ — **Fear Inducing** for the Bog-Hag and Brine-Hag, **Glamour** for the Briar-Hag and Mirage-Hag.
- **Innate Spells (2 — Novice, Witch Magic and Hedge Craft):** each a full action, one per turn.
    - **The Evil Eye** _(Aggressor)_ — Arcane Clash, Arcana vs. the target's Resolve, Short Range. Any win resolves Clean under Innate Magic: the target gains **Hexed**, and if that Hexed roll then fails, the backlash inflicts 1 Dissonant Stress on them.
    - **Warding Knot** _(Activation)_ — Unopposed Arcana vs. TN 8, self or one ally by touch. The next enemy to land a Strike on the warded creature suffers Disadvantage on its next roll; on a Margin 5+ the knot survives one triggering. _She ties it onto whatever is standing between her and the party._
- **Special Action (1):** fixed by her Skin — see **Hag Skins**, below. All four replace her regular action, so none needs a Margin gate (Gate Test).

> [!note] Designer's Note
> **Confusion is withheld at Grunt on purpose.** Under Innate Magic every won Confusion Clash resolves Clean, and a Clean Confusion deletes the target's next Activation outright. At Arcana +3 she wins that Clash **66%** of the time against a Resolve +1 PC and **76%** against Resolve +0 — a turn lost most rounds, from a Grunt. It belongs on the Matriarch.

##### Hag Skins

A hag is made by the place she lives, the same way a Wretch is made by the place that killed it. **A Skin never changes Attributes, Skills, Wound Threshold, Wound Slots, Stress Limit, Move or Power** — _a Brine-Hag is a wetter hag, not a stronger one._ What a Skin sets is her **Guise**, her **Special Action**, **one rider that is inert outside her home ground**, and — for the Matriarch only — her **signature spell**.

**Each hag is immune to the Hazard Check of her own terrain** (_Iron World_, Environmental Hazards), exactly as a Wretch is. The exception is the Briar-Hag: woodland has no Hazard Check in Iron World to be immune to, so her rider does that job instead.

| Skin | Home ground | Face | Guise | Special Action | Matriarch's signature spell |
| --- | --- | --- | --- | --- | --- |
| **Bog-Hag** | freezing water — marsh, fen, flooded sluice | unlovely | Fear Inducing | Sucking Mire | The Creeping Ague _(Adept)_ |
| **Brine-Hag** | freezing water — sea, surf, tidal caves | unlovely | Fear Inducing | Brine in the Lungs | Sympathetic Effigy _(Adept)_ |
| **Briar-Hag** | woodland — no Hazard Check | lovely | Glamour | Beckon | Choking Bramble _(Adept)_ |
| **Mirage-Hag** | a scorching desert — dunes, salt pan, dry oasis | lovely | Glamour | Drink Them Dry | Malefic Reflection _(Master)_ |

_Appearance is the axis the Guise turns on, and it is mechanical rather than cosmetic. The unlovely hags are frightening from the first moment (**Fear Inducing**, a canon Trait). The lovely ones are frightening at the **last** moment — **Glamour** holds the party's hand off her until the mask drops, and the drop itself forces the same Fear check. Both halves of the roster end up making the party roll Resolve; they just disagree about when._

**Bog-Hag** — _the fen-mother. Leeches in her hair, peat under her nails, and a smell that arrives before she does._
- **Guise — Fear Inducing.**
- **Special Action — Sucking Mire:** _Trigger:_ Instead of a regular action. _Effect:_ One target within Short Range that she can see must pass an **Athletics check vs TN 8** or gain **Anchored** as the ground under them turns to peat — cleared by Regroup, per Iron Core.
- **Home rider (inert elsewhere):** Ignores difficult terrain from mud and standing water. **A target that is Anchored on her home ground is Drowned as well** — the peat takes them under the black water. _This is the hag the Bog-Wretch was waiting for: its own rider grants Advantage against a Drowned target._

**Brine-Hag** — _barnacled, slack-skinned, hair like drowned rope. Sailors' stories make her prettier than she is._
- **Guise — Fear Inducing.**
- **Special Action — Brine in the Lungs:** _Trigger:_ Instead of a regular action. _Effect:_ One target within Short Range who can hear her must pass an **Athletics check vs TN 8** or gain **Drowned** — on dry land, if need be, as their lungs fill with seawater. It clears exactly as Drowned always does (Athletics vs TN 8, made by the target or by an adjacent ally spending an Action); on dry land, "reaching the surface" means coughing it up.
- **Home rider (inert elsewhere):** Ignores difficult terrain from surf and water. **Tide-Born:** if she starts her activation standing in water, she clears 1 Stress. _The sea is the only thing that has ever been kind to her._

**Briar-Hag** — _a woman at the edge of the trees, barefoot, holding a lantern that is the wrong colour. She knows your name._
- **Guise — Glamour.**
- **Special Action — Beckon:** _Trigger:_ Instead of a regular action. _Effect:_ One target within Medium Range who can see her must pass a **Resolve check vs TN 8**, or on their next Activation they spend their Move walking toward her by the most direct path — through difficult terrain, brambles and Threat Zones alike (leaving a Threat Zone still provokes). They stop short of a fall or open flame, and may still take their Action at the end of the walk. **A PC who has seen through her Glamour is immune.**
- **Home rider (inert elsewhere):** Ignores difficult terrain from undergrowth and roots. **Green Shroud:** in woodland she counts as **Obscured** (Iron World) to any attacker more than 10 ft away.

**Mirage-Hag** — _the woman at the well that should not be there, offering a cup. The water is sand. So is she, nearly._
- **Guise — Glamour.**
- **Special Action — Drink Them Dry:** _Trigger:_ Instead of a regular action. _Effect:_ One target within Short Range must pass an **Athletics check vs TN 8** or gain **Fatigued** (1 Locked Stress, cleared only by a Long Rest or magical Restoration — Iron Core). A target she has already Fatigued this Scene is immune. _In the open desert this lands on top of the Hazard Check's own Locked Stress, which is the point of fighting her there._
- **Home rider (inert elsewhere):** Ignores difficult terrain from sand and scree. **Her Glamour survives taking a Wound** — the heat-shimmer holds the lie together. Cold Iron and Breaking still drop it.

##### Phases

- **Behaviour when unbroken:** Never closes to melee by choice; the Talons are for when she is cornered. Opens with her Skin's Special Action, ties a Warding Knot onto whatever stands in front of her, and puts the Evil Eye on whoever is about to swing at her. The lovely ones open by **talking** — Glamour gives Advantage on Influence, and a party that stops to parley has handed her the first activation. Field her behind something with a body: her sisters, or Wretches from the same ground — Bog-Wretches for a Bog-Hag, Dust-Wretches for a Mirage-Hag.
- **Behaviour when Broken:** Set by her Guise.
    - **Fear Inducing (Bog, Brine): The Rout.** She goes under — into the mire or the surf — and on her home ground she does not come up anywhere the party is looking. Off it, she runs for the nearest water.
    - **Glamour (Briar, Mirage): Frenzy.** The Glamour drops (with its Fear check) and what was underneath comes at the nearest PC: she loses her Parry, gains Advantage on all Strikes, and stops casting.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

---

### Elite

#### Lizardman Shaman

> _The idol's keeper does not fight for the temple. It fights for whatever is still listening underneath it._

##### Vital Statistics

- **Tier:** Elite
- **Type:** Humanoid
- **Move:** 30 ft
- **Attributes (derived only):** Wits 1 → Stress Limit _(Assumed Zero: everything else. Activation Order 6.)_
- **Skills:** Arcana +4, Resolve +3, Melee +1, Notice +1.
- **Derived stats:**
    - Wound Threshold: **4** _(Base 4 + Brawn 0)_
    - Wound Slots: **3**
    - Stress Limit: **6** _(4 + Will 0 + Wits 1 + 1 Elite)_
    - Momentum Bank: **4** _(4 + Reflex 0)_
- **Equipment:** None — channels raw spirit-force directly. Bite/claws (Power 1) as a last resort.
- **Traits (2):**
    - **Innate Magic:** The magic is bone-deep, not book-bound. This creature casts Arcane spells without a Grimoire and without needing a hand free, and never suffers Blind Casting's Disadvantage or Dissonant Stress penalty for an unmet casting requirement. All of its Innate Spells are treated as if under Paradigm Mastery, regardless of which Paradigm (or none) the spell belongs to: any Messy result (Margin 1–2, whether on a Clash, an initial cast, or a Sustain check) is treated as Clean, paying no Dissonant Stress. Its power was never learned, so it was never imperfect to begin with.
    - **Plated:** Scaled hide reduces all incoming standard Impact damage by a flat -1.
- **Innate Spells (3):** each is a full Aggressor or Activation action — one per turn, same as any other creature only getting one action.
    - **Burst** _(ordinary attack, Aggressor):_ Arcane Clash, Arcana vs. each target's Defense. Spell Power 1, 10ft cone. Margin 1–2 (treated as Clean per Innate Magic): Impact = Margin + 1 (Spell Power), no Dissonant Stress. Margin 3+ (Clean): as above.
    - **Ward of Scales** _(Activation, to raise; Reactor, to use)_ — _Arcane Protection:_ Unopposed Arcana vs. TN 8. Clean (Margin 3+, or Margin 1–2 treated as Clean per Innate Magic): hostile spells targeting the Shaman suffer Disadvantage to cast. As a Reactor action against an incoming hostile spell, the Shaman may Block using Arcana instead of a normal Reactor stat. Sustained per the normal Channelling Rule (Arcana vs. TN 8 each Activation and on taking a Wound) — a Messy Sustain is likewise treated as Clean.
    - **Call of the Deep Green** _(Aggressor)_ — _Beast Friend:_ Targets a Giant Spider or other Beast-type creature within Short Range. Arcane Clash, Arcana vs. the beast's Resolve. Margin 1+ (treated as Clean per Innate Magic): the beast becomes the Shaman's ally for the scene, communicating telepathically and seeing through its eyes for the scene.

##### Phases

- **Behaviour when unbroken:** Opens by raising Ward of Scales rather than attacking immediately, then alternates Burst to hold the party at range and Call of the Deep Green to drag a Giant Spider onto its side.
- **Behaviour when Broken:** Resolves as **Frenzy**, reflavored for a caster — Ward of Scales drops the instant it Breaks and can't be re-raised, but the Shaman gains Advantage on all spell Clash rolls until it dies, channelling without any care for its own burnout.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

#### Cultist Assassin

##### Vital Statistics

- **Tier:** Elite
- **Type:** Humanoid (Human)
- **Move:** 30 ft
- **Attributes (4 — Elite allowance):** Reflex 3, Wits 1. _(Assumed Zero: Brawn, Will — practically untouchable by standard strikes, but rolls 2d6+0 if forced into a Grapple.)_
- **Skills (11):** Melee +2, Acrobatics +4, Stealth +4, Ranged +1. _(Dodges at 2d6+4 — Dodge is Acrobatics, per Metal meet Flesh.)_
- **Derived stats:**
    - Wound Threshold: **4** _(Base 4 + Brawn 0)_
    - Wound Slots: **3**
    - Stress Limit: **7** _(4 + Will 0 + Wits 1 + 1 Indomitable Spirit + 1 Elite)_
    - Activation Order: **9** _(6 + Reflex 3)_
    - Momentum Bank: **6** _(4 + Reflex 3, then -1 for Steady, Not Sharp)_
- **Equipment:** Dagger (Power 0, 1H, Concealable, Close-Quarters, Finesse, Thrown, Sidearm) — Strike Roll: 2d6+2 (Melee +2). Shortbow (Power 2, 2H, Volley) for ranged work before closing in — Shoot Roll: 2d6+1 (Ranged +1), Impact = Margin + 2. Opened from Stealth against an unaware target, **Ambusher** makes that first arrow an Advantaged roll.
- **Species Traits (free — see The Marrow):**
    - **Indomitable Spirit:** Base Stress Limit increased by +1 (already folded into the derived stat above).
    - **Steady, Not Sharp (Drawback):** Momentum Bank cap reduced by 1 (already folded in above).
- **Allowance (3 — Elite): 1 Feat, 2 Traits**
    - **Shadow-Weaver** _(Feat, Tier 1; prereq Stealth 1 ✓)_ — ignores the standard penalty for moving quickly while trying to remain hidden. It can sprint out of a Threat Zone at full Move and still be hidden enough at the end of it to Vanish.
    - **Ambusher** _(Trait)_ — gains Advantage on the Clash roll if attacking an unaware target from Stealth.
    - **Skittering** _(Trait)_ — unnatural speed, shifting limbs, or erratic reflexes make them slippery targets. This creature may move out of a Threat Zone without requiring a test, or causing a free strike.
- **Special Actions (2):**
    - **Vanish:** _Trigger:_ At the end of its movement this activation, if it ends that movement in an Obscured or Heavily Obscured position (per Iron World's Cover rules). _Effect:_ The Assassin blends into the shadows, becoming effectively totally obscured — finding them again requires a successful Notice check.
    - **Throat Slit:** _Trigger:_ On a successful Melee clash with a Margin of 3+. _Effect:_ The target immediately suffers a Minor Wound, bypassing their normal Impact Threshold.

##### Phases

- **Behaviour when unbroken:** Opens with the Shortbow or from Stealth with Ambusher, closing in for the Margin-3 opening that triggers Throat Slit — then uses Skittering to slip out of the Threat Zone it just created and Shadow-Weaver to run at full speed without breaking cover, Vanishing if that retreat ends somewhere obscured. Never sticks around for a fair fight it doesn't need to have.
- **Behaviour when Broken:** Resolves as **The Rout** — Vanish is already its escape valve, so once Stress maxes out it uses that same instinct to disappear from the fight for good rather than keep pressing a lost contract.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

---

#### The Bandit Captain

> _A serious threat that requires party synergy to defeat. He doesn't fight fair; he commands the battlefield with a heavy halberd, barking orders from behind a wall of cutthroats._

##### Vital Statistics

- **Tier:** Elite
- **Type:** Humanoid (Half-Orc)
- **Move:** 30 ft
- **Attributes (4 — Elite allowance):** Brawn 2, Wits 1, Reflex 1. _(Assumed Zero: Will — a hardened commander who braces against hits, but his heavy armour and cumbersome weapon make him terrible at dodging out of the way of AOE attacks or fast projectiles.)_
- **Skills (9):** Melee +4, Prowess +3, Notice +1, Resolve +1.
- **Derived stats:**
    - Wound Threshold: **9** _(Base 4 + Brawn 2 + Breastplate 3)_
    - Wound Slots: **3**
    - Stress Limit: **6** _(4 + Will 0 + Wits 1 + 1 Elite)_
    - Activation Order: **6** _(6 + Reflex 1, reduced by 1 for the Halberd's Cumbersome tag — same treatment as the Orc Line-Breaker's Greataxe)_
    - Momentum Bank: **5** _(4 + Reflex 1)_
- **Equipment:** Breastplate (+3 Armour). Masterwork Halberd (Power 3+1 masterwork = 4, Reach, Cumbersome). Strike Roll: 2d6+4 (Melee +4).
- **Species Traits (free — see The Marrow):**
    - **Blood Frenzy:** When he suffers a Wound, he immediately clears 1 Dissonant Stress. Hurting him steadies him — which matters a great deal on a commander whose Broken state is Surrender.
    - **Menacing:** Advantage on Influence checks when intimidating anyone smaller or weaker than him.
    - **Outcast (Drawback):** Disadvantage on Influence checks when dealing with civilised strangers who don't already know him. He recruits from people who have run out of better options; that is not entirely a choice.
- **Allowance (3 — Elite): 2 Feats, 1 Trait**
    - **Relentless Momentum** _(Feat, Tier 2; prereq Brawn 2 ✓)_ — whenever he inflicts a Minor or Major Wound, he instantly gains 1 Momentum.
    - **Sweep** _(Feat, Tier 2; prereqs Brawn 1 ✓, Reflex 1 ✓, Melee 1 ✓)_ — on winning a Strike with a melee weapon, he may spend 1 Momentum to apply his full Impact to every enemy adjacent to the primary target. On a Reach halberd swung from behind his own line, this is the "opens gaps in a shield wall" threat made real, and Relentless Momentum is what pays for it.
    - **Cunning Leader** _(Trait)_ — a ruthless commander who reads the battlefield with chilling tactical precision. At the beginning of the Round, he can pass his own position in the Activation order to any allied Fodder unit within his line of sight, letting the minions strike with unexpected coordination. Additionally, whenever an ally within his line of sight dies, **he banks 1 Momentum** out of pure malice or tactical adaptation.
- **Special Actions (2):**
    - **Call for Reinforcements:** _Trigger:_ Instead of a regular action, declared on the Captain's activation. _Effect:_ The Captain shouts for backup. One additional Fodder (Bandit) arrives at the edge of the battlefield next round, OR — if reinforcements aren't narratively available — all currently engaged Fodder immediately gain the benefit of the Flanking Bonus as if one more ally were present (representing the Captain directing the formation).
    - **Hook and Drag:** _Trigger:_ Declared after a successful Melee clash with his Halberd with a Margin of 3+ (Clean or better). _Effect:_ Instead of dealing normal Impact, the Captain hooks the player's legs. The target is immediately knocked Prone and dragged 5 feet directly into an adjacent Fodder's Threat Zone.

##### Phases

- **Behaviour when unbroken:** Commands from behind his line rather than leading it, using Cunning Leader to hand his activation to a Fodder ally for a coordinated strike, and Call for Reinforcements or Hook and Drag to keep the fight on his terms. Once the party clusters up to deal with his cutthroats, the halberd comes out: a Wound banks Momentum via Relentless Momentum, and that Momentum buys a **Sweep** across the whole cluster. Punishing the party for bunching is his actual win condition.
- **Behaviour when Broken:** Resolves as **Surrender** — a serious threat, not a fanatic or a beast; once his Stress maxes out, he reads the battle as lost and yields rather than dies for a cause he doesn't share.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

---

#### The Frost-Cave Troll

> _A towering, territorial brute of dense muscle and thick frost-bitten hide. It swings a shattered pine tree with horrifying speed, its wounds knitting together almost as fast as they are opened._

##### Vital Statistics

- **Tier:** Elite
- **Type:** Beast
- **Size:** Large (Scale +1)
- **Move:** 40 ft
- **Attributes (derived only):** Brawn 3 → Wound Threshold; Reflex 1 → Activation Order 7 _(Assumed Zero: Dodge, Notice, Arcana, Resolve — acts surprisingly fast and hits like a siege weapon, but is entirely defenseless against mind-altering magic or illusions.)_
- **Skills:** Melee +6, Prowess +4.
- **Derived stats:**
    - Wound Threshold: **9** _(4 + Brawn 3 + Scale +2)_
    - Wound Slots: **3**
    - Stress Limit: **5** _(4 + Will 0 + Wits 0 + 1 Elite — monster build, exempt from the core-species Stress Limit floor)_
    - Momentum Bank: **5** _(4 + Reflex 1)_
- **Equipment:** None — natural weapon only. Tree Trunk (Power 3, Reach, Brutal). Strike Roll: 2d6+6 (Melee +6).
- **Traits (1):**
    - **Troll-Blood Regeneration:** At the start of the Troll's activation, it automatically heals 1 Wound Slot and clears 1 Stress. _Weakness:_ If the Troll takes any Impact damage from a Fire source (such as a _Naphtha Fire-Flask_ or Pyromancy), this trait is entirely suppressed until the end of the next round.
- **Special Actions (2):**
    - **Vicious Frenzy:** _Trigger:_ Declared immediately after the Troll wins a Strike's Clash with a Margin of 3+ (Clean or better). _Effect:_ The Troll follows up its lumbering tree trunk attack with a sudden, tearing claw swipe. It makes an immediate, secondary Strike at an adjacent target (Treat the claws as Power 1, Vicious).
    - **Sweeping Uproot:** _Trigger:_ Instead of a standard single-target Strike, declared before the Troll attacks with its Tree Trunk. _Effect:_ The Troll drags its tree trunk through the earth. This Strike gains the _Cleave_ tag, forcing every player in its frontal arc to defend against the same Strike roll. Furthermore, any player who loses the Clash is knocked Prone.

##### Phases

- **Behaviour when unbroken:** Leans on Troll-Blood Regeneration to shrug off attrition, alternating Vicious Frenzy's follow-up claw swipe with Sweeping Uproot to catch multiple PCs in one Cleave.
- **Behaviour when Broken:** Resolves as **Frenzy** — a mindless, territorial beast with nothing to surrender and nowhere it would flee to; it loses its Block/Dodge entirely but gains Advantage on all Strike rolls until it dies.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

---

#### The Rotting Fen-Goliath

> _A towering, decapitated mass of waterlogged flesh, rusted iron chains, and tangled mangrove roots. It does not feel pain; it only seeks to pull living warmth down into the freezing mud._

##### Vital Statistics

- **Tier:** Elite
- **Type:** Undead
- **Size:** Huge (Scale +2)
- **Move:** 30 ft
- **Attributes (derived only):** Brawn 3 → Wound Threshold; Reflex 0 → Activation Order 6 _(Assumed Zero: Dodge, Notice, Arcana, Resolve — a lumbering behemoth that swings at +6 and braces against physical blows at +5, but is completely defenseless against Agility or Mind-targeting magic.)_
- **Skills:** Melee +6, Prowess +5.
- **Derived stats:**
    - Wound Threshold: **11** _(4 + Brawn 3 + Scale +4)_
    - Wound Slots: **4** _(3 base + 1 Huge Scale)_
    - Stress Limit: **7** _(4 + Will 0 + Wits 0 + 1 Elite + 2 Resilient)_
    - Momentum Bank: **4** _(4 + Reflex 0)_
- **Equipment:** None — natural weapon only. A mass of rusted chains and mangrove roots (Power 3, Reach, Brutal). Strike Roll: 2d6+6 (Melee +6).
- **Traits (2):**
    - **Sinking Gravity:** The ground immediately within the Goliath's Threat Zone is perpetually treated as Mire (Difficult Terrain), halving movement and imposing disadvantage to all mobility checks due to the supernatural rot and water bleeding from its body.
    - **Resilient:** Increases the creature's Stress Limit by +2 (already folded into the total above). May spend **up to 2 Momentum per incoming Strike** from its own Bank to Mitigate damage, reducing that Strike's Impact by 2 per point spent.
- **Special Actions (2):**
    - **Corpse-Gas Rupture:** _Trigger:_ Declared immediately when the Goliath takes a physical Wound. _Effect:_ The wound forcefully expels highly toxic swamp gas. The player who delivered the Wound instantly suffers the _Rigor_ condition as their lungs violently seize up, completely denying them the ability to Parry or Dodge on the Goliath's next turn.
    - **Sweeping Uproot:** _Trigger:_ Instead of a standard single-target Strike, declared before the Goliath attacks. _Effect:_ The Goliath drags its mass of chains and roots through the earth. This Strike gains the _Cleave_ tag, forcing every player in its frontal arc to defend against the same Strike roll. Furthermore, any player who loses the Clash is knocked Prone.

##### Phases

- **Behaviour when unbroken:** Plants itself in one spot, using Sinking Gravity to keep PCs mired in its Threat Zone and triggering Corpse-Gas Rupture or Sweeping Uproot to punish anyone who closes in or lines up in its front arc.
- **Behaviour when Broken:** Resolves as **Frenzy** — it doesn't feel pain and has nothing to surrender or flee toward; once its Stress maxes out it thrashes with pure Advantage-fueled violence until it's destroyed.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

---

#### The Barrow-Fang

> _"The howls stopped an hour before it found us. That's when Corvis said we should've kept moving."_

##### Vital Statistics

- **Tier:** Elite
- **Type:** Lycanthrope, Humanoid
- **Size:** Large (Scale +1)
- **Move:** 50 ft
- **Attributes (derived only):** Brawn 2, Reflex 2 → Wound Threshold 8, Activation Order 8 _(Wits and Will are zero — whatever reasoned it out died the first time it changed.)_
- **Skills:** Melee +4, Acrobatics +3, Notice +2 _(Assumed Zero: everything else. Its preferred defense is Dodge, at 2d6+3.)_
- **Derived stats:**
    - Wound Threshold: **8** _(4 + Brawn 2 + Scale +2)_
    - Stress Limit: **5** _(4 + Will 0 + Wits 0 + 1 Elite — monster build, exempt from the core-species Stress Limit floor)_
    - Momentum Bank: **6** _(4 + Reflex 2)_
- **Equipment:** None — natural weapons only. Bite & Claw (Power 2). Strike Roll: 2d6 + 4 (Melee +4).
- **Traits (3):**
    - **Cursed Regeneration:** At the start of the Barrow-Fang's activation, it automatically heals 1 Wound Slot and clears 1 Stress. _Weakness:_ any Wound inflicted by a weapon carrying a Lycanthrope Bane effect (Silvered Edge, per Hardware) permanently suppresses this trait for the rest of the encounter — the same shape as the Frost-Cave Troll's fire weakness, with silver standing in for flame.
    - **Vicious:** If the Barrow-Fang inflicts damage on a PC, the target must immediately pass a Prowess check (TN 8) or gain the Bleeding condition.
    - **Ambusher:** Gains Advantage on the Clash roll if attacking an unaware target from Stealth.
- **Special Actions (2):**
    - **Howl of the Hunt:** _Trigger:_ Instead of a regular action, declared at the start of the Barrow-Fang's activation. _Effect:_ Every player within 30 ft who can hear it must pass a Resolve check vs. TN 8 or gain the Fear condition (targeting the Barrow-Fang) for the rest of the encounter.
    - **Rend and Pin:** _Trigger:_ Declared on a successful Melee Clash with a Margin of 3+. _Effect:_ In addition to normal Impact, the target is knocked Prone and pinned — they cannot stand or take a Move Action until they win an opposed Prowess check against the Barrow-Fang (attempted as a Free Action on their own activation).

##### Phases

- **Behaviour when unbroken:** Hunts with patient, almost human cunning before the change fully takes hold — uses Ambusher to open the fight from cover rather than announcing itself, closing to melee only once an opening is certain. The Howl is a closer's move, not an opener: spent once it's confident the fight is already lost for its prey.
- **Behaviour when Broken:** Per the GM Tools NPC Stress rules, this resolves as **Frenzy**, not Surrender — the wolf, not the person, is what's left once the mind goes: it loses Dodge and Block entirely but gains Advantage on all Strike rolls until it dies. _If your table wants a tragic "still human underneath" beat instead, this is the specific creature to house-rule to Surrender — but the trope reading is Frenzy._
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

---

---

#### The Fixer

> _She doesn't carry a weapon if she can help it. She rarely needs to — by the time a room turns violent, she has usually already sold it to someone._

##### Vital Statistics

- **Tier:** Elite
- **Type:** Humanoid (Half-Elf)
- **Move:** 30 ft
- **Attributes (4 — Elite allowance):** Wits 2, Will 1, Reflex 1. _(Wits 2 meets Silver-Tongued Viper's prerequisite; Will 1 is what lifts her Influence ceiling to +4 under the Ceiling Rule.)_
- **Skills (9):** Influence +4, Melee +2, Resolve +2, Notice +1.
- **Derived stats:**
    - Wound Threshold: **3** _(Base 4 + Brawn 0 - 1 Hollow-Boned, inherited with Fey Reflexes via Split Heritage)_
    - Wound Slots: **3**
    - Stress Limit: **8** _(4 + Will 1 + Wits 2 + 1 Elite)_
    - Activation Order: **7** _(6 + Reflex 1)_
    - Momentum Bank: **5** _(4 + Reflex 1)_
- **Equipment:** Dagger (Power 0, 1H, Concealable, Finesse, Thrown). Strike Roll: 2d6+2 (Melee +2).
- **Species Traits (free — see The Marrow):**
    - **Silver-Tongued:** Gains Advantage on Influence checks when persuading, de-escalating a fight, negotiating, or gathering information.
    - **Fey Reflexes:** Gains Advantage on Acrobatics checks to avoid environmental hazards, traps, or area-of-effect abilities. Taken via Split Heritage — the Hollow-Boned drawback above travels with it.
    - **Between Worlds (Drawback):** Disadvantage on Influence checks against an insular or homogeneous community with little contact with outsiders. Her whole operation runs on being known; where she isn't, she is worse than a stranger.
- **Feats / Spells (2 picks — Elite, Tier 1–2 ceiling):**
    - **Battlefield Orator** _(Tier 1; prereq Influence 2 ✓)_ — spend an Action to shout orders or hurl insults. Either an ally immediately clears 1d6 Dissonant Stress, or an engaged enemy suffers **-2** to their next Defense roll.
    - **Silver-Tongued Viper** _(Tier 2; prereqs Wits 2 ✓, Influence 2 ✓)_ — on a Massive Success (Margin 5+) on an opposed Influence vs. Resolve check, she bypasses the one-step limit and flips an NPC **three steps** in either direction, bending them to her agenda for the scene. This is what "cutting a deal" actually looks like when she is good at it.
- **Special Actions (1):**
    - **Exploit the Opening:** _Trigger:_ Declared after winning a Melee clash with a Margin of 3+ (Clean or better). _Effect:_ She finds the undefended nerve without wasted motion — the target takes 1 Dissonant Stress.

##### Phases

- **Behaviour when unbroken:** Talks first, and keeps talking — Battlefield Orator to strip the defense off whoever is about to be hit, Silver-Tongued Viper aimed at whichever enemy looks least invested in dying for their employer. Fights only when cornered, and badly.
- **Behaviour when Broken:** Resolves as **Surrender** — she is a broker, not a soldier. Immediately offers whatever she has (names, routes, the location of the money) rather than die for an operation she doesn't own.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

---

#### The Duelist

> _Fast enough that fair fights bore her. She is paid to stand slightly behind someone more important and be the reason nobody reaches them._

##### Vital Statistics

- **Tier:** Elite
- **Type:** Humanoid (Elf)
- **Move:** 30 ft
- **Attributes (4 — Elite allowance):** Reflex 2, Brawn 2. _(Brawn 2 is what lifts her Melee ceiling to +5 under the Ceiling Rule; Reflex 2 meets Quick's prerequisite and drives her Activation Order.)_
- **Skills (9):** Melee +5, Acrobatics +3, Notice +1.
- **Derived stats:**
    - Wound Threshold: **5** _(Base 4 + Brawn 2 - 1 Hollow-Boned)_
    - Wound Slots: **3**
    - Stress Limit: **6** _(4 + Will 0 + Wits 0 + 1 Elite = 5, raised to the core-species Elite floor of 6 — both her Attribute points went to Melee's ceiling and Quick's prerequisite, so Will and Wits got nothing)_
    - Activation Order: **11** _(6 + Reflex 2, +3 from Quick)_
    - Momentum Bank: **6** _(4 + Reflex 2)_
- **Equipment:** Shortsword (Power 2, 1H, Finesse, Sidearm). Strike Roll: 2d6+5 (Melee +5). Dodges at 2d6+3 (Acrobatics +3), Parries at 2d6+5 (Melee +5).
- **Species Traits (free — see The Marrow):**
    - **Fey Reflexes:** Gains Advantage on Acrobatics checks to avoid environmental hazards, traps, or area-of-effect abilities.
    - **Trance:** Needs only 4 hours of meditation for a full night's rest. She takes the watch nobody else wants, every night.
- **Feats / Spells (2 picks — Elite, Tier 1–2 ceiling):**
    - **Riposte** _(Tier 2; prereq Melee 2 ✓)_ — if she wins a Parry in a melee Clash, she instantly inflicts Impact on the attacker, calculated exactly as though she had won a Strike (her Margin of victory + weapon Power). Her defense *is* her offence.
    - **Quick** _(Tier 1; prereq Reflex 1 ✓)_ — +3 to Activation Order, and she breaks ties against anyone without Quick. Already folded into the Activation Order above.
- **Special Actions (1):**
    - **Blade Dance:** _Trigger:_ Instead of a regular attack, declared when at least two enemies are adjacent to her. _Effect:_ Two separate Melee Clash rolls at -1 each, one against each of two different adjacent targets.

##### Phases

- **Behaviour when unbroken:** Acts first in almost every round (Activation Order 11) and holds position between the party and whoever she's guarding. **Parries rather than dodges, deliberately** — Riposte turns every won Parry into a full Strike, so standing still and inviting the attack is the optimal play, not a failure of nerve. Blade Dance when flanked, rather than trying to escape the pincer.
- **Behaviour when Broken:** Resolves as **The Rout** — a professional withdrawal. Her employer's life is a contract, not a cause, and a dead duelist collects nothing.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

#### The Gallows Shot

> _She has been on that rooftop since before you were told the meeting place. Elves do not need to sleep, and she has never once needed to be close._

##### Vital Statistics

- **Tier:** Elite
- **Type:** Humanoid (Elf)
- **Size:** Standard
- **Move:** 30 ft
- **Attributes (4 — Elite allowance):** Reflex 3, Wits 1. _(Reflex 3 lifts her Ranged ceiling to 6 and drives both Activation Order and Bank; Wits 1 is what puts her Stress Limit on the Elite floor rather than under it.)_
- **Skills (11):** Ranged +5, Stealth +3, Notice +2, Acrobatics +1.
- **Derived stats:**
    - Wound Threshold: **4** _(Base 4 + Brawn 0 + Leather 1 - 1 Hollow-Boned)_
    - Wound Slots: **3**
    - Stress Limit: **6** _(4 + Will 0 + Wits 1 + 1 Elite — exactly the core-species Elite floor)_
    - Activation Order: **12** _(6 + Reflex 3, +3 from Quick)_
    - Momentum Bank: **7** _(4 + Reflex 3)_
- **Equipment:** Longbow (Power 3, 2H, Ranged — Max Extreme / 125+ ft, **Volley**), Dagger (Power 0, 1H, Sidearm, Concealable) as a last resort, Leather (+1 Armour, Light). Shoot Roll: 2d6+5 (Ranged +5). Impact = Margin + 3. Dodges at 2d6+1 (Acrobatics +1), and swings the dagger at 2d6+0.
- **Species Traits (free — see The Marrow):**
    - **Fey Reflexes:** Advantage on Acrobatics checks to avoid environmental hazards, traps, or area-of-effect abilities.
    - **Trance:** Four hours of meditation replaces a full night's rest. She has been watching the meeting point for two days.
    - **Hollow-Boned (Drawback):** Base Wound Threshold reduced by 1 (already folded into the derived stat above).
- **Allowance (3 — Elite): 3 Feats.**
    - **Quick** _(Feat, Tier 1; prereq Reflex 1 ✓)_ — +3 to Activation Order, and breaks ties against anyone without it. She acts at 12, before any Green party.
    - **Long Eye** _(Feat, Tier 1; prereqs Ranged 1 ✓, Notice 1 ✓)_ — she ignores the Disadvantage the **Long** band imposes, so her whole working envelope out to 120 ft is penalty-free. **Extreme** range still costs her Disadvantage and still requires the target be completely in the open.
    - **The Chain** _(Feat, Tier 2; prereqs Reflex 2 ✓, Ranged 2 ✓)_ — on winning a Clash by a Margin of 5+, she may immediately spend 1 Momentum to make a free secondary Shoot against a **different** valid target in range.
- **Special Actions (1):**
    - **Loose and Withdraw:** _Trigger:_ Instead of a regular Shoot. _Effect:_ She looses at Disadvantage and then moves her full Move without provoking a free Strike. Her answer to anyone who closes.

> [!note] GM's Note
> **Running her — the Chain loop.** As an Elite she banks 1 Momentum on any Clash she wins by Margin 5+, and **The Chain** costs 1 Momentum on that same trigger. A Margin-5+ shot therefore pays for its own follow-up: net zero Momentum, one extra Shoot at a second target. Against a Green party's Dodge she clears Margin 5+ roughly a third of the time, so she chains about every third shot and can do it all fight. Nothing here is a new rule — it is the earning table and the feat meeting — but it is the sharpest interaction on the Elite roster.

##### Phases

- **Behaviour when unbroken:** Opens from concealment at the far edge of **Long** range — 120 ft, penalty-free under Long Eye — before the party knows a fight has started. Holds that distance with Loose and Withdraw, and chains onto a second target whenever a shot lands by 5+. She will shoot at Extreme range if she has to, and eats the Disadvantage for it. She will give up any amount of ground and never a yard of range.
- **Behaviour when Broken:** Resolves as **The Rout** — she is a professional at three hundred feet and nothing at all at five. Once her Stress maxes out she leaves, and she leaves early.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

#### The Hag Matriarch

> _Every coven has one who was there first. The others are hers the way her teeth are hers._

##### Vital Statistics

- **Tier:** Elite
- **Type:** Fey, Humanoid _(Cold Iron's Bane applies — Hardware.)_
- **Size:** Standard
- **Move:** 30 ft
- **Skin:** one of the four **Hag Skins** (see The Hag, Grunt). Her Skin sets her Guise, her first Special Action, her home-ground rider and her signature spell, and changes nothing else.
- **Attributes (derived only):** Brawn 1, Wits 1, Will 1 _(Assumed Zero: Reflex.)_
- **Skills (11):** Arcana +4, Influence +2, Resolve +2, Melee +2, Notice +1. _(Casts at 2d6+4, resists other witches at 2d6+2, claws and Parries at 2d6+2.)_
- **Derived stats:**
    - Wound Threshold: **5** _(Base 4 + Brawn 1 — **4** against a Cold Iron weapon)_
    - Wound Slots: **3**
    - Stress Limit: **7** _(4 + Will 1 + Wits 1 + 1 Elite — monster build, exempt from the core-species Stress Limit floor)_
    - Activation Order: **6** _(6 + Reflex 0)_
    - Momentum Bank: **4** _(4 + Reflex 0)_
- **Equipment:** None — Talons (Power 1). Strike Roll: 2d6+2 (Melee +2), Impact = Margin + 1.
- **Allowance (3 — Elite): 2 Traits + 1 spell.**
    - **Innate Magic** _(Trait — see Arcane Traits)_ — brings the three Novice spells below; every Messy result resolves Clean.
    - **Her Guise** _(Trait — fixed by her Skin)_ — **Fear Inducing** (Bog, Brine) or **Glamour** (Briar, Mirage).
    - **Her signature spell** _(one pick, per Innate Magic's costing)_ — fixed by her Skin. Arcana +4 meets both the Adept (2+) and Master (3+) rank.
- **Innate Spells (4):** each a full action, one per turn. Read every one from Manipulating The Void; under Innate Magic, every Messy result resolves Clean.
    - **Confusion** _(Novice, Aggressor)_ — Arcane Clash, Arcana vs. Resolve, Short Range. Any win: **Confused**, and the target loses its next Activation outright.
    - **The Evil Eye** _(Novice, Aggressor)_ — as The Hag.
    - **Warding Knot** _(Novice, Activation)_ — as The Hag.
    - **Signature spell, by Skin:**
        - _Bog-Hag:_ **The Creeping Ague** _(Adept, Aggressor)_ — marsh-fever. Any win resolves Clean: the target forfeits its whole next turn to Regroup, retching; an Elite or Boss target also cannot spend Momentum until it recovers.
        - _Brine-Hag:_ **Sympathetic Effigy** _(Adept, Activation, TN 10)_ — a poppet of driftwood, kelp and a drowned sailor's hair. The next Wound the linked creature would suffer snaps the poppet instead; on a Margin 5+ the one who dealt it suffers **Impact 4**. _She ties it to herself first, then to a sister._
        - _Briar-Hag:_ **Choking Bramble** _(Adept, Activation, TN 10)_ — a 15 ft radius of iron-hard briars for the Scene. Any success resolves at least Clean: her allies move through freely, and an enemy who declares a Strike from inside takes 1 Dissonant Stress first.
        - _Mirage-Hag:_ **Malefic Reflection** _(Master, Aggressor)_ — you strike the mirage, and the mirage strikes back. Any win resolves Clean: for the Scene, whenever the target deals Impact to anyone, they suffer Impact of the full same amount themselves.
- **Special Actions (2):**
    - **Her Skin's Special Action** — Sucking Mire, Brine in the Lungs, Beckon or Drink Them Dry, exactly as The Hag.
    - **Sister's Blood:** _Trigger:_ She would suffer a Wound while another hag is within 30 ft — once per round. _Effect:_ That hag suffers the Wound in her place; the coven pays for its mother. **A Wound dealt by a Cold Iron weapon cannot be passed** — iron cuts the thread. _Self-limiting by trigger, so free under the Gate Test. Its whole job is to make the party kill the sisters first, and to give a Cold Iron weapon a second reason to exist._

> [!note] GM's Note
> **Running her — Resolve is the soft target.** Every one of her Clash spells is Arcana vs. Resolve, and Resolve is the thinnest defence on most Green sheets. At Arcana +4 she wins **76%** of those Clashes against Resolve +1 and **84%** against Resolve +0 — and, being Elite, she banks 1 Momentum on a Margin 5+, which she clears on **34%** of casts against Resolve +1. That is on a par with the Gallows Shot's Chain loop, the roster's sharpest earner — and it comes from the spell list and the earning table meeting, not from any new rule. Her ceiling is the action economy: one spell a turn, and Confusion or the Ague costs her the same action it costs the target.

##### Phases

- **Behaviour when unbroken:** Stands at the back of the coven, inside Short Range of the fight and never inside a Threat Zone. Opens with **Confusion** on whoever the party is built around, then plays her Skin:
    - _Bog:_ **Sucking Mire** on home ground — Anchored becomes Drowned — and lets the Bog-Wretches do the rest; **the Ague** for anyone who breaks free.
    - _Brine:_ **Sympathetic Effigy** on herself before anyone reaches her, then **Brine in the Lungs** every turn it isn't needed.
    - _Briar:_ **Choking Bramble** between herself and the party, then **Beckon** them into it, one at a time.
    - _Mirage:_ **Malefic Reflection** on the heaviest hitter, then **Drink Them Dry** on everyone else, while the desert does its own work.

    Keeps her sisters within 30 ft at all times, because Sister's Blood only works while they are.
- **Behaviour when Broken:** **Surrender — she names her price.** If she wears a Glamour it drops first, with its Fear check. Then she offers a bargain for her life: a true answer, a curse lifted, safe passage through her ground. She is Fey, "bound to the old pacts" (Creature Types) — whether she keeps the bargain to its letter, its spirit, or not at all is the GM's call.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

---

### Dread / Boss

#### Arch-Devil Malaphar

##### Vital Statistics

- **Tier:** Boss
- **Type:** Daemon
- **Move:** 30 ft
- **Attributes (derived only):** Brawn 4, Will 3, Wits 2 → Wound Threshold 12, Stress Limit 11; Reflex 0 → Activation Order 6 _(Assumed Zero: Dodge — a lumbering powerhouse of physical and magical pressure, but acts last in combat and cannot dodge out of the way of AOE attacks.)_
- **Skills:** Melee +7, Arcana +4, Resolve +4.
- **Derived stats:**
    - Wound Threshold: **12** _(4 + Brawn 4 + Armour 4)_
    - Wound Slots: **5**
    - Stress Limit: **11** _(4 + Will 3 + Wits 2 + 2 Dread/Boss)_
    - Momentum Bank: **4** _(4 + Reflex 0)_
- **Equipment:** Brimstone Plate (+4 Armour, immune to Damage, immune to fire). Hell-forge Greatsword (Power 5; after inflicting a Wound, target must pass a Resolve check at -2 or gain the Ablaze condition). Strike Roll: 2d6+7 (Melee +7).
- **Traits (3):**
    - **Terrifying:** A harrowing presence — whether an eldritch abomination or a faceless, silent headsman — that cracks the human mind. When a PC engages with this creature or it activates within line of sight, the PC must immediately roll a Resolve check against TN 8. Failure: the PC immediately gains the Terrified condition.
    - **Cunning Leader:** A ruthless commander or pack alpha who reads the battlefield with chilling tactical precision. At the beginning of the Round, this creature can pass its own position in the Activation order to any allied Fodder unit within its line of sight, allowing the minions to strike with unexpected coordination. Additionally, whenever an ally within its line of sight dies, **Malaphar banks 1 Momentum** out of pure malice or tactical adaptation.
    - **Hubris (Passive Momentum Engine):** The Arch-Devil feeds on mortal desperation. **Malaphar banks 1 Momentum every single time a player spends Momentum from their own bank** — a direct transfer, in one currency: he is literally eating their adrenaline.
- **Special Actions (1):**
    - **Furnace Rebuke:** _Trigger:_ Declared when Malaphar wins a Clash as the Reactor (Defense) with a Margin of 3+ (Clean or better). _Effect:_ Malaphar deflects the player's blow with such friction that the player's weapon or hands burst into flames. The player instantly gains the Ablaze condition.
- **Momentum-Costed Abilities (2):** both are free-standing bonus effects with no action economy or Margin gate available to lean on instead. Both are paid out of his **Momentum Bank of 4**.
    - **Cost 2 Momentum — The Devil's Mandate:** _Trigger:_ Declared as a Free Action on Malaphar's turn — genuinely stacks on top of his normal Strike, so the Momentum cost is the only thing limiting it. _Effect:_ Malaphar speaks a word of absolute authority, targeting one player. That player must pass a TN 8 Resolve check at -2, or drop to their knees in submission (gaining the Prone and Anchored conditions).
    - **Cost 3 Momentum — Lair Action (Gehenna's Grip):** _Trigger:_ Declared at the absolute start of a combat round — outside any creature's turn entirely, so there's no action economy here either. _Effect:_ The veil tears, and chains of molten iron erupt. Every player must make an immediate, unopposed Melee or Dodge check against TN 8. Failure means they are violently dragged 10 feet toward Malaphar.

##### Phases

- **Behaviour when unbroken:** Rules through overwhelming pressure rather than urgency — lets Hubris farm Momentum passively as the players spend theirs, opens rounds with Gehenna's Grip to drag stragglers in, uses Devil's Mandate to take a problem PC out of the fight outright, and punishes anyone who attacks him directly with Furnace Rebuke.
- **Behaviour when Broken:** Per the GM Tools NPC Stress rules, a Boss's Broken state resolves as a Phase Change rather than a Rout, Surrender, or Frenzy — see below.
- **Dread Entity/Boss Phase changes — Gehenna Unbound:** _Trigger:_ The instant Malaphar's Stress Limit maxes out. _Effect:_ The veil doesn't just tear — it fails outright. A 60 ft radius centered on Malaphar becomes a literal fragment of Hell for the rest of the encounter. **Environmental Hazard:** at the start of each round, brimstone and hellfire lash every non-Daemon creature in the radius — resolved as a Hazard Roll (GM Tools): 2d6+2 (Hazard Power 2) against the character's Wound Threshold; a hit inflicts a Wound, a miss still inflicts 1 Stress. **Imps Erupt:** 3 Imps (Fodder tier — see Imp) tear through the rift and join the fight at the edge of the battlefield.

---

#### Halgrim the Unburied

> "He does not raise his voice. He has had three hundred years to learn that silence frightens the living more than any war-cry ever did."

##### Vital Statistics

- **Tier:** Dread Entity / Boss
- **Type:** Undead _(a dwarven warlord-king, centuries dead and unwilling to lie down)_
- **Size:** Standard | **Move:** 30 ft
- **Attributes (derived only):** Brawn 3, Will 2 → Wound Threshold 9, Stress Limit 8; Reflex 0 → Activation Order 6, Momentum Bank 4. _(Assumed Zero: Wits — slow and mentally uncomplicated. Illusions, Arcana debuffs and anything requiring him to out-think rather than out-endure a target land on him easily; he is never racing anyone to act, so Reflex 0 costs him nothing tactically.)_
- **Skills:** Melee +5, Resolve +4, Prowess +3.
- **Derived stats:**
    - Wound Threshold: **9** _(4 + Brawn 3 + Armour 2)_
    - Wound Slots: **4**
    - Stress Limit: **8** _(4 + Will 2 + Wits 0 + 2 Dread/Boss)_
    - Activation Order: **6** _(6 + Reflex 0)_
    - Momentum Bank: **4** _(4 + Reflex 0)_
- **Equipment:** Ancient Grave-Plate (+2 Armour, Medium, **Bulky** — −1 Athletics, Stealth and Arcana). The Frost-Bitten Maul (Power 4, **Brutal** — each natural 4 on his 2d6 adds +1 to the Impact it generates). Strike Roll: **2d6+5**.
- **Traits (3 of an allowance of 4):**
    - **Fear Inducing:** When a PC engages with him or he activates within line of sight, that PC must immediately roll a **Resolve** check against TN 8. Failure: the PC gains the *Fear* condition. _(Cleared per Iron Core — Regroup out of sight or cover of the source, or automatically if the source is destroyed.)_
    - **Sovereign's Malice (Passive Momentum Engine):** Halgrim banks **1 Momentum every time a PC spends Momentum from their own Bank** — the mechanism that taxes the party for rebuilding toward a Decisive Blow, capped by his Bank of 4 rather than open-ended.
    - **Grave-Locked Resilience:** Once per round, Halgrim may spend up to **2 Momentum from his own Bank** to reduce incoming Impact by 2 per point spent. **Rises to 3 once Broken.**
- **Special Actions (2):**
    - **Grip of the Barrow (free):** _Trigger:_ wins a Melee Clash with **Margin 3+**. _Effect:_ the target is **Anchored** (0 movement) until they spend a full Aggressor action tearing free.
    - **Reaver's Bite (free):** _Trigger:_ wins a Melee Clash with **Margin 5+**. _Effect:_ **Direct Wound** — bypasses Wound Threshold, filling 1 Wound Slot automatically.
- **Momentum-Costed Abilities (1):**
    - **Cost 2 Momentum — Winter's Judgment:** _Trigger:_ declared on Halgrim's activation. _Effect:_ 2 **Direct Dissonant Stress** to one target in his Threat Zone, bypassing Wound Threshold entirely.

##### Phases

- **Behaviour when unbroken:** Deliberate and patient, no wasted motion. Opens toward whoever is more mobile. His two free Special Actions are deliberately split across the Margin bands — **Grip of the Barrow on any Margin 3+ win, Reaver's Bite only on Margin 5+** — so control lands on a good hit and execution only on a great one. Against a typical Green defense that is roughly **44% of his attacks Anchoring and 24% also inflicting a Wound**. Only Winter's Judgment and Grave-Locked Resilience are Bank-limited, so those are the two calls that need GM judgment mid-fight. As a Boss he banks **1 Momentum at the start of every round** on top of Sovereign's Malice, so his Bank refills whether or not the party co-operates.
- **Behaviour when Broken:** Per the GM Tools NPC Stress rules, a Boss's Broken state resolves as a Phase Change rather than a Rout, Surrender or Frenzy — see below.
- **Dread Entity/Boss Phase change — The Frost Cracks:** _Trigger:_ the instant his Stress Track maxes out. _Effect:_ the frost binding him cracks audibly. He **loses Fear Inducing** and **loses his Prowess bonus on Brace** (post-break, Brace rolls a flat 2d6), but **gains Advantage on all Melee Strikes**, and **Grave-Locked Resilience's per-round cap rises to 3** for the rest of the fight. He is not weaker after breaking — he is spending everything he has left rather than accept a second death.

> [!note] Designer's Note
> **Deliberately built under his own band.** His 12 Skill points sit at the top of the **Green Elite** band (9–12) and **one point under the flat Green Boss floor of 13**. That is deliberate, not an error: the Boss band assumes an action economy ("acted on 3–5 times for every one of its own actions") that a small party does not supply, and the bet is that his Special Action kit and durability cover the gap.

**He is the source of Halgrim's Grave-Crown** (Hardware, Relic tier) — though the Crown is a GM-placed Relic and does not require this encounter to be run.

---

# Appendices

# Appendix A — Building Enemies

*The Enemy Template*

## Enemy Name:

> "Insert a narrative line about the enemy."

### Vital Statistics
- **Tier:** Fodder | Grunt | Elite | Dread Entity/Boss
- **Type:** one or more of the canonical Creature Types (see Bestiary): Humanoid, Beast, Dragon, Fey, Elemental, Undead, Vampire, Lycanthrope, Daemon, Void-Touched, Ooze, Construct, Mutant. Type is the hook Bane effects, Domain Tags and resistances key off — pick from this list, don't invent one.
- **Species:** core-species Humanoids only (Human, Half-Elf, Half-Orc, Halfling, Elf, Dwarf). If present, build per **Core-Species Humanoids** in the Core Integration Rules. If absent, this is a monster — bespoke Traits and Special Actions, no Feats. It still has a Momentum Bank; every creature does.
- **Size:** per the Scale rules (Metal meet Flesh). Standard needs no note.
- **Move:** land and/or Fly Move in feet; 30 ft is the unremarkable default.
- **Attributes:** Brawn | Reflex | Wits | Will — derived only, never added to a roll.
	- *Monsters:* list only non-zero values, then state "Assumed Zero: everything else."
	- *Core-species:* allowance by tier — **Fodder 1 · Grunt 2 · Elite 4 · Dread/Boss 6+** (a Boss may exceed the +3 mortal cap). These points do three jobs at once: they set Skill ceilings, meet Feat prerequisites, and drive the derived stats below. Spend them deliberately.
- **Skills:** list only non-zero. Total per the **Enemy Budget by Party Standing** table (Core Integration Rules); bought 1:1 regardless of Attribute.
	- *Brawn:* Melee | Athletics | Block | Prowess
	- *Reflex:* Ranged | Stealth | Thievery | Acrobatics | Ride
	- *Wits:* Notice | Insight | Medicine | Crafting | Lore | Arcana
	- *Will:* Influence | Faith | Survival | Resolve
	- **Ceiling Rule (core-species builds):** no Skill may exceed its Associated Attribute **+3** — Attribute 0→3, 1→4, 2→5, 3→6. Note that a ceiling of 3 applies even at Attribute 0, so only *specialisation above +3* costs Attribute points. Monsters are exempt.
	- **There is no Dodge skill.** Dodge is 2d6 + Acrobatics, Block is 2d6 + Block, Parry is 2d6 + Melee, Brace is 2d6 + Prowess. If a creature's preferred defense is worth signalling, say so in prose.
- **Derived stats:** show the calculation for each.
	- Wound Threshold: 4 + Brawn + Armour Value ± Species/Scale
	- Wound Slots: by tier — Fodder 1 · Grunt 2 · Elite 3–4 · Boss 4+ (never the PC's flat 3)
	- Stress Limit: 4 + Will + Wits + Species bonus + tier bonus (Elite +1, Boss +2). **Core-species builds only:** then raised to the tier floor if lower — **Fodder 4 · Grunt 4 · Elite 6 · Dread/Boss 8**. Monsters are exempt: they have no Ceiling Rule and no Feat prerequisites competing for their Attribute points, so a low monster Stress Limit is a build choice, not residue. Scale and Species modifiers apply after the floor and may take a core-species build below it. In practice this only ever fires at Elite and above, since Fodder and Grunt already sit at the base 4.
	- Activation Order: 6 + Reflex (−1 for a Cumbersome weapon)
	- Momentum Bank: 4 + Reflex — **every creature**, earned and spent exactly as a PC's. Momentum is the game's only currency; there is no GM Threat pool and no Vessel Limit. Earning is asymmetric by tier (GM Tools, Momentum Economy): Fodder and Grunt from their own Traits and Feats only, Elite adds a Clash won by Margin 5+, Dread/Boss adds 1 at the start of every round.
- **Equipment:** weapons with Power and tags, armour with Armour Value, and the resulting Strike Roll.
- **Species Traits:** core-species only — free, and outside the allowance below. Read them from The Marrow. **Drawbacks come along with them.**
- **Allowance — Feats, spells and Traits share one pool:** Fodder 2 · Grunt 2 · Elite 3 · Dread/Boss 4.
	- *Monsters* spend the whole pool on Traits from the Trait Manifest.
	- *Core-species* may spend it on Feats and spells from the players' own lists (The Marrow, Manipulating The Void) or on Traits, in any mix. Feat tier ceiling: Grunt Tier 1, Elite Tier 1–2, Dread/Boss any. Spells must still meet their own Arcana/Faith rank prerequisites, and a trained caster needs **Arcane Awakening**, **Arcane Dabbler**, **Divine Conduit** or **Ritualist** (and the focus it grants) — only the Innate Magic trait bypasses that.
	- Where a signature mechanic has no equivalent on the players' lists (Skittering, Ambusher, Cunning Leader), spend the slot on the Trait rather than contorting the build around it.
- **Special Actions:** per the **Gate Test** — free if it replaces the creature's regular action or its trigger is self-limiting; if it's a bonus layered on an action the creature already took, gate it behind a **Margin 3+** threshold instead. Fodder/Grunt 1 · Elite 1–2 · Dread/Boss 3+.
- **Momentum-Costed Abilities:** *Dread/Boss almost exclusively.* Only for a genuinely free-standing ability — a true Free Action stacked on a full turn, or a Lair Action outside the turn order. Paid from the creature's own Momentum Bank, which is the only cap; if an ability needs a tighter per-use limit, write it into the ability.
	- **Cost N Momentum — *name*:** (description of ability, narrative and mechanics)

### Phases
- **Behaviour when unbroken:** how the enemy narratively plays at full health and unbroken Stress — name the abilities it actually leads with, not just its mood.
- **Behaviour when Broken:** **Rout**, **Surrender** or **Frenzy** — chosen to fit the creature, not locked by tier or type. List any mechanical changes.
- **Dread Entity/Boss Phase changes:** how it plays as each Wound track fills; list any mechanical changes. N/A for Fodder, Grunt and Elite.

# Appendix B — Sample Characters

*Pregenerated Player Characters*

*Every character below is tagged with a Standing (Green / Blooded / Veteran / Hardened / Storied) and a Milestone count. Full definitions live in The Marrow, Character Creation, under "Milestone Standing — Tracking Advancement." Short version: Milestone count is the exact, countable number of 3-DP Milestone Rewards a character has received; Standing is the shorthand band over that count, for table talk only — it gates nothing by itself.*

---

## Green

### Helga Stonewright — Dwarf Female, Faith Caster (Law Domain)

*"The law doesn't need your permission to apply to you."*

#### Vital Statistics
- **Species:** Dwarf
- **Standing:** Green (Milestone 0 — 0 DP earned; pure creation build)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 1 | Reflex 0 | Wits 0 | Will 3
- **Skills:** Faith 3 | Resolve 1 | Influence 2 | Melee 1 | Block 1 *(8 ranks, 8 DP. Ceilings: Faith/Resolve/Influence 6 (Will 3); Melee/Block 4 (Brawn 1))*
- **Wound Threshold:** 8 *(4 base + 1 Brawn + 2 Chainmail/Scale + 1 Stone-Bones)*
- **Stress Limit:** 9 *(4 base + 0 Wits + 3 Will + 2 Stoic Resolve feat)*
- **Wound Slots:** 3 | **Momentum Bank:** 4 *(4 + Reflex 0)* | **Activation Order:** 6 *(6 + Reflex 0)*
- **Inventory Slots:** 9 *(8 + 1 Brawn)*

#### Species Traits (Dwarf)
- **Stone-Bones:** +1 Wound Threshold (already applied above).
- **Subterranean Senses:** Advantage on Notice checks underground or examining stonework/engineering.
- **Stumpy (Drawback):** Disadvantage on Athletics checks during chases or open-ground sprints.

#### Feats
- **Divine Conduit — The Covenant, Domain of Law.** Grants a Holy Symbol, the **Smite Corruption** Domain Tag (targeting Undead/Daemons/Mutants treats their Wound Threshold as 1 lower), and the 4 Novice Prayers below.
- **Stoic Resolve** *(Will +2, Resolve +1)*: +2 Stress Limit (already applied above). When taking the Reprieve action, or spending Momentum on Adrenaline Flush, clear 1 extra point of the relevant Stress type.

#### Equipment
- **Armour:** Chainmail/Scale (+2 Armour, Medium, **Bulky** — -1 Athletics/Stealth/Arcana; doesn't touch Faith, so this costs her nothing she was using)
- **Weapons/Shield (two 1H items):** Mace (Power 2, Bash) + Kite/Round Shield (4 SV, **Cover** — Advantage on defense vs. ranged)
- **Holy Symbol** (granted by Divine Conduit — outside the purse)
- **Starting Purse: 80 sp** — Chainmail/Scale 45 + Mace 8 + Kite Shield 18 = **71 sp spent, 9 sp remaining.** 2 sp on a bedroll, 3 sp on a hooded lamp (Dwarven habit — always carry your own light underground), 4 sp in her pocket.

#### Prayers (Tithe of Will = 2d6 + Faith = **2d6+3**, vs. TN 8 Novice)
- **The Architect's Decree** — 1 Locked Stress, Free Reaction (an enemy tries to Move or leave your Threat Zone). Pass: target instantly Anchored, speed drops to 0 for the round — bypasses saves entirely. Fail: as Pass + 1 Encroachment.

- **Sanctuary of the Zenith** — 1 Locked Stress, Activation, 3x3 zone, Scene duration. Pass: no character inside can gain Advantage or Disadvantage on any roll — Flanking, Obscurement, Prone penalties all suppressed. Fail: as Pass + 1 Encroachment.

- **Writ of Protection** — 1 Locked Stress, Free Reaction (an enemy declares an attack on a warded ally). Pass: the attack is forbidden from targeting them — redirects or is wasted. Fail: as Pass + 1 Encroachment.

- **The Binding Oath** — 1 Locked Stress, Activation, touch, one willing character. Pass: the target's spoken promise is bound — knowingly breaking its letter costs them 2 Dissonant Stress. Fail: as Pass + 1 Encroachment.

#### Combat Math Quick-Ref
Tithe of Will 2d6+3 | Strike (Mace) 2d6+1, Impact = Margin+2 | Block 2d6+1 (modest; if lost, Kite Shield's SV 4 subtracts from Impact before comparing to her WT 8) | Dodge 2d6+0 (she blocks, she doesn't dance) | Resolve 2d6+1 | Influence 2d6+2 | Activation Order 6

---

### Faelan Rook — Half-Elf Male, Arcana Caster (Shadow Sorcery)

*"Everyone assumes the smiling half-breed is the safe one to talk to. That's rather the point."*

#### Vital Statistics
- **Species:** Half-Elf (Split Heritage: took Fey Reflexes, and its paired Hollow-Boned drawback)
- **Standing:** Green (Milestone 0 — 0 DP earned; pure creation build)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 0 | Reflex 1 | Wits 3 | Will 0
- **Skills:** Arcana 3 | Stealth 1 | Acrobatics 1 | Notice 1 | Insight 1 | Thievery 1 *(8 ranks, 8 DP. Ceilings: Arcana/Notice/Insight 6 (Wits 3); Stealth/Acrobatics/Thievery 4 (Reflex 1))*
- **Wound Threshold:** 4 *(4 base + 0 Brawn + 1 Leather - 1 Hollow-Boned)*
- **Stress Limit:** 7 *(4 base + 3 Wits + 0 Will)*
- **Wound Slots:** 3 | **Momentum Bank:** 5 *(4 + Reflex 1)* | **Activation Order:** 7 *(6 + Reflex 1)*
- **Inventory Slots:** 8 *(8 + 0 Brawn)*

#### Species Traits (Half-Elf)
- **Silver-Tongued:** Advantage on Influence checks to persuade, de-escalate, negotiate, or gather information.
- **Fey Reflexes** *(chosen Split Heritage trait)*: Advantage on Acrobatics checks vs. hazards, traps, AoE.
- **Between Worlds (Drawback):** Disadvantage on Influence in insular/xenophobic communities.
- **Hollow-Boned (Drawback, comes with Fey Reflexes):** -1 Wound Threshold (already applied above).

#### Feats
- **Arcane Awakening** *(Paradigm: Shadow Sorcery)*. Grimoire below — three picks in-Paradigm, the fourth drawn from the Common list.
- **Whispers in the Dark** *(Stealth +1, Notice +1)*: While successfully hidden, Advantage on Notice checks to eavesdrop, read lips, or observe details without breaking cover.

#### Equipment
- **Armour:** Leather (+1 Armour, Light — no Arcana penalty)
- **Weapons (two 1H items):** Grimoire (Repository — granted by Arcane Awakening, outside the purse) + Dagger (Finesse — reroll a natural 1 in a Clash; with Melee 0 he is rerolling into a +0 either way, but it is free)
- **Starting Purse: 80 sp** — Leather 12 + Dagger 5 = **17 sp spent, 63 sp remaining.** 5 sp on a signet ring (a different name and seal in every city, which is rather the point), 2 sp on ink/paper/sealing wax, 16 sp on 2 Grave-Dust Poultices (Field Medicine — Full Action, instantly clears 1 filled Wound Slot; Athletics TN 8 or 1 Dissonant Stress), 40 sp banked.

#### Grimoire (Arcana = **2d6+3**)
- **Deflection** *(Paradigm, Mastery-eligible)* — **Reactor only; never raised in advance.** Arcane Clash (Arcana) opposed against the incoming attack, **self only**, **Scene** duration — it stands until the next Breather or a lost Clash, and is **not** a Sustain effect, so it needs no maintenance roll and doesn't occupy the Channelling slot. Margin 0–2 *(a tie counts here)*: attack deflected, 1 Dissonant Stress. Margin 3–4: deflected at no cost, and attacks against him take −2 while it stands. Margin 5+: as Clean, but the penalty is full Disadvantage. **Lose the Clash and the attack lands for full Impact with no mitigation — no Shield Value, no armour — and the ward falls.**

- **Stitch the Silhouette** *(Paradigm, Clash-resolution, Mastery-eligible)* — Arcane Clash vs. Prowess, Short Range, Aggressor. Margin 1–2: target Anchored until they tear free (1 Dissonant Stress to themselves doing so); costs Faelan 1 Dissonant Stress. Margin 3+ (Clean, or Mastery-upgraded from 1–2): as above, and target also loses Dodge as an option until free — no cost.

- **Flicker-Step** *(Paradigm, Mastery-eligible)* — Unopposed vs. TN 8, Self, 30ft teleport, ignores Threat Zones entirely. Margin 0–2: teleports, but arrives gasping — 1 Dissonant Stress. Margin 3–4: silent and flawless. Margin 5+: also generates 1 Momentum or grants Advantage on his next Strike.

- **Havoc** *(Common, not Mastery-eligible)* — Arcane Clash vs. each target's Prowess + Athletics/Acrobatics, 10ft radius, Short Range, Aggressor. Margin 1–2: target pushed 5ft and takes 1 Dissonant Stress; he also takes 1 Dissonant Stress from the strain. Margin 3+ (Clean): target pushed 10ft, knocked Prone, and takes 1 Dissonant Stress.

#### Combat Math Quick-Ref
Arcane Clash/Manifestation 2d6+3 (incl. Havoc) | Dagger Strike 2d6+0 *(Melee 0; Finesse lets him reroll a natural 1)* | Dodge 2d6+1 | Notice 2d6+1 | Activation Order 7

---

### Pillit Thistlewood — Halfling Female, Ranged Skirmisher

*"By the time you hear the string, I'm already three trees away."*

#### Vital Statistics
- **Species:** Halfling — **Size:** Small (Scale -1)
- **Standing:** Green (Milestone 0 — 0 DP earned; pure creation build)
- **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 0 | Reflex 3 | Wits 1 | Will 0 *(Spike array)*
- **Skills:** Ranged 3 | Stealth 2 | Acrobatics 1 | Notice 1 | Thievery 1 *(8 ranks, 8 DP. Ceilings: Ranged/Stealth/Acrobatics/Thievery 6 (Reflex 3); Notice 4 (Wits 1))*
- **Wound Threshold:** 4 *(4 base + 0 Brawn + 1 Leather - 1 Scale)*
- **Stress Limit:** 5 *(4 base + 1 Wits + 0 Will — Halflings are exempt from the Scale Stress penalty)*
- **Wound Slots:** 3 | **Momentum Bank:** 7 *(4 + Reflex 3)* | **Activation Order:** 12 *(6 + Reflex 3, +3 Quick)*
- **Inventory Slots:** 8 *(8 + 0 Brawn)*

#### Species Traits (Halfling)
- **Underfoot:** Advantage on Stealth with cover, obscurement, or moving through a larger creature's space.
- **Halfling Luck:** Once per session, ignore a Fumble's Stress penalty entirely (the action still fails).
- **Small Stature (Drawback):** Cannot wield weapons carrying the Cumbersome tag. (Shortbow isn't Cumbersome, so this is legal.) Also exempt from the Scale −1 Stress Limit penalty, see The Marrow.

#### Feats
- **Quick** *(Reflex 1)*: +3 to your Activation Order — shoot and reposition before melee closes the gap.
- **Shadow-Weaver** *(Stealth 1)*: Ignores the Rushed penalty for moving quickly while trying to stay hidden — kite and re-hide in the same turn without a Stealth tax.

#### Equipment
- **Armour:** Leather (+1 Armour, Light — keeps Stealth/Acrobatics clean)
- **Weapon (one 2H item):** Shortbow (Power 2, **Volley** — requires both hands, no Shield or Grimoire while wielding it)
- **Starting Purse: 80 sp** — Leather 12 + Shortbow 15 = **27 sp spent, 53 sp remaining.** 4 sp on a bag of Caltrops (scatter them behind her while kiting), 2 sp on hemp rope, arrows and a spare bowstring, **47 sp in reserve.**

#### Combat Math Quick-Ref
Ranged Strike 2d6+3, Impact = Margin+2 (Shortbow) | Dodge 2d6+1 | Stealth 2d6+2 | Activation Order 12 (Quick)

---

### Vrenna Ashfist — Half-Orc Female, Arcana Caster (Pyromancy)

*"Fire doesn't ask permission to burn. Neither do I."*

#### Vital Statistics
- **Species:** Half-Orc
- **Standing:** Green (Milestone 0 — 0 DP earned; pure creation build)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 1 | Reflex 0 | Wits 3 | Will 0 *(Spike array)*
- **Skills:** Arcana 3 | Melee 1 | Athletics 1 | Notice 1 | Insight 1 | Resolve 1 *(8 ranks, 8 DP. Ceilings: Arcana/Notice/Insight 6 (Wits 3); Melee/Athletics 4 (Brawn 1); Resolve 3 (Will 0))*
- **Wound Threshold:** 7 *(4 base + 1 Brawn + 2 Chain Shirt + 0 Species)*
- **Stress Limit:** 7 *(4 base + 3 Wits + 0 Will — Half-Orcs carry no Stress bonus of their own)*
- **Wound Slots:** 3 | **Momentum Bank:** 4 *(4 + Reflex 0)* | **Activation Order:** 6 *(6 + Reflex 0)*
- **Inventory Slots:** 9 *(8 + 1 Brawn)*

#### Species Traits (Half-Orc)
- **Blood Frenzy:** Suffering a Wound instantly clears 1 Dissonant Stress.
- **Menacing:** Advantage on Influence checks to intimidate anyone smaller or weaker.
- **Outcast (Drawback):** Disadvantage on social checks with civilized strangers who don't know her.

#### Feats
- **Arcane Awakening** *(Paradigm: Pyromancy).* Grimoire below — three picks in-Paradigm, the fourth drawn from the Common list.
- **Lethal Strikes** *(Melee 1)*: Her unarmed strikes can deal Lethal Impact and cause physical Wounds — the mechanical half of the "own knuckles" line in Wreath of Embers below; without it, her fists are just fists.

#### Equipment
- **Armour:** Chain Shirt (+2 Armour, Light — no Arcana penalty)
- **Weapons:** None carried by choice. Grimoire (Repository — granted by Arcane Awakening, outside the purse) sits in one hand; the other stays free to strike unarmed, which is exactly the hand the Casting Requirement was already demanding she keep open.
- **Starting Purse: 80 sp** — Chain Shirt 50 = **50 sp spent, 30 sp remaining.** 3 sp on a tinderbox and oil flask she doesn't strictly need, 2 sp on bandages, 25 sp banked.

#### Grimoire (Arcana = **2d6+3**)
- **Thermal Detonation** *(Pyromancy, Novice, Crowd Control — Creation)* — Arcane Clash (Arcana vs. every engaged enemy's Defense), 5ft radius centered on self, Spell Power 1. Margin 1–2: Impact = Margin+1, enemy thrown 5ft back out of her Threat Zone, she takes 1 Dissonant Stress. Margin 3+ (Clean): as above, enemy thrown 10ft and knocked Prone, plus 1 Dissonant Stress from the ruptured eardrums (to her).
- **Ember Lance** *(Pyromancy, Novice, Direct Strike — Creation)* — Arcane Clash (Arcana vs. Target's Defense), Medium Range, Spell Power 2. Margin 1–2: Impact = Margin+2, she takes 1 Dissonant Stress. Margin 3+ (Clean): as above, target also suffers Disadvantage on their next Aggressor Strike.
- **Wreath of Embers** *(Pyromancy, Novice, Weapon Ignition — Creation)* — Unopposed Arcana vs. TN 8, Activation, Scene duration, self or one weapon (she targets her own knuckles). Margin 0–2 (Messy): +1 Impact as fire for the scene, she takes 1 Dissonant Stress. Margin 3–4 (Clean): as above, no cost. Margin 5+ (Massive): the first enemy she strikes each round must also resist **Ablaze** (Iron Core) — the condition carries its own per-turn cost.
- **Havoc** *(Common, not Mastery-eligible)* — Arcane Clash vs. each target's Prowess + Athletics/Acrobatics, 10ft radius, Short Range, Aggressor. Margin 1–2: target pushed 5ft and takes 1 Dissonant Stress; she also takes 1 Dissonant Stress from the strain. Margin 3+ (Clean): target pushed 10ft, knocked Prone, and takes 1 Dissonant Stress.

#### Combat Math Quick-Ref
Arcane Clash/Manifestation 2d6+3 | Unarmed Strike 2d6+1 *(Melee; Lethal Strikes makes it count)* — Impact = Margin, or Margin+1 while Wreath of Embers is active | Dodge 2d6+0 | Notice 2d6+1 | Insight 2d6+1 | Resolve 2d6+1 | Activation Order 6

---

### Bram Ashcroft — Human Male, Sword-and-Board Fighter

*"Let them break their teeth on my shield."*

#### Vital Statistics
- **Species:** Human
- **Standing:** Green (Milestone 0 — 0 DP earned; pure creation build)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 3 | Reflex 1 | Wits 0 | Will 0 *(Spike array)*
- **Skills:** Melee 3 | Block 3 | Prowess 1 | Resolve 1 | Notice 1 *(9 ranks, 9 DP with Adaptable. Ceilings: Melee/Block/Prowess/Athletics 6 (Brawn 3); Resolve 3 (Will 0); Notice 3 (Wits 0))*
- **Wound Threshold:** 9 *(4 base + 3 Brawn + 2 Chainmail/Scale + 0 Species)*
- **Stress Limit:** 5 *(4 base + 0 Wits + 0 Will + 1 Indomitable Spirit)*
- **Wound Slots:** 3 | **Momentum Bank:** 4 *(4 + Reflex 1, −1 Steady Not Sharp)* | **Activation Order:** 7 *(6 + Reflex 1)*
- **Inventory Slots:** 11 *(8 + 3 Brawn)*

#### Species Traits (Human)
- **Adaptable:** +1 Skill **DP** at creation (already applied — a Human's creation Skill budget is 9, not 8).
- **Indomitable Spirit:** +1 Stress Limit (already applied above).
- **Steady, Not Sharp (Drawback):** −1 to your Momentum Bank cap (already applied above).

#### Feats
- **Iron Grip** *(Melee +1 — Creation)*: ties on a Clash where the weapons bind auto-bank him 1 Momentum — his engine for a character with no other Momentum generator.
- **Trench Fighter** *(Brawn +1 — Creation)*: ignores Difficult Terrain's Disadvantage entirely, and drawing a weapon while engaged doesn't take the usual penalty.

#### Equipment
- **Armour:** Chainmail/Scale (+2 Armour, Medium, Bulky — the Bulky penalty hits Athletics/Stealth/Arcana, and he has zero ranks in any of the three, so it costs him nothing)
- **Weapon:** Shortsword (Power 2, Sidearm, Finesse)
- **Shield:** Kite/Round Shield (4 SV, Cover)
- **Starting Purse: 80 sp** — Chainmail/Scale 45 + Shortsword 10 + Kite Shield 18 = **73 sp spent, 7 sp remaining.** Sunrod (5 sp) for light, 2 sp banked.

#### Combat Math Quick-Ref
Melee Clash 2d6+3 | Block 2d6+3 (if lost, Kite Shield's SV 4 subtracts from Impact before comparing to WT 9) | Prowess 2d6+1 | Resolve 2d6+1 | Notice 2d6+1 | Activation Order 7

---

### Aeric Thorne — Half-Elf Male, Berserker

*"You don't win a fight. You make sure you're the last thing standing in it."*

#### Vital Statistics
- **Species:** Half-Elf (Split Heritage: took Fey Reflexes, and its paired Hollow-Boned drawback)
- **Standing:** Green (Milestone 0 — 0 DP earned; pure creation build)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 2 | Reflex 2 | Wits 0 | Will 0 *(Twin array)*
- **Skills:** Melee 3 | Athletics 2 | Prowess 2 | Resolve 1 *(8 ranks, 8 DP. Ceilings: Melee/Athletics/Prowess/Block 5 (Brawn 2); Resolve 3 (Will 0))*
- **Wound Threshold:** 6 *(4 base + 2 Brawn + 1 Leather − 1 Hollow-Boned)*
- **Stress Limit:** 4 *(4 base + 0 Wits + 0 Will)*
- **Wound Slots:** 3 | **Momentum Bank:** 6 *(4 + Reflex 2)* | **Activation Order:** 7 *(6 + Reflex 2, −1 Cumbersome)*
- **Inventory Slots:** 10 *(8 + 2 Brawn)*

#### Species Traits (Half-Elf, Split Heritage)
- **Fey Reflexes** *(chosen Split Heritage trait)*: Advantage on Acrobatics checks vs. hazards, traps, AoE.
- **Between Worlds (Drawback):** Disadvantage on Influence in insular/xenophobic communities.
- **Hollow-Boned (Drawback, comes with Fey Reflexes):** −1 Wound Threshold (already applied above).

#### Feats
- **Desperate Edge** *(Resolve +1 — Creation)*: when a lone die in a 2d6 check shows a 6 while at half-or-more Stress Limit in Dissonant Stress, or on his final Wound Slot, it explodes — roll an extra d6 and add it.
- **Trench Fighter** *(Brawn +1 — Creation)*: ignores Difficult Terrain's Disadvantage, and drawing a weapon while engaged doesn't take the usual penalty.

#### Equipment
- **Armour:** Leather (+1 Armour, Light)
- **Weapon:** Greataxe (Power 5, 2H, Heavy Hitter, Cumbersome, Scarce)
- **Starting Purse: 80 sp** — Leather 12 + Greataxe 40 = **52 sp spent, 28 sp remaining.** Grave-Dust Poultice (8 sp) + Witch-Spur Salve (12 sp) = 20 sp, **8 sp banked.**

#### Combat Math Quick-Ref
Melee Clash 2d6+3 *(Power 5; **Heavy Hitter** — every natural 6 on his 2d6 counts as a 7, and neither Fate's Bounty nor Desperate Edge's exploding die applies to this axe)* | Athletics 2d6+2 | Prowess 2d6+2 | Resolve 2d6+1 | Activation Order 7

---

### Elowen Vex — Elf Female, Thief

*"You never saw me. That's the whole point."*

#### Vital Statistics
- **Species:** Elf
- **Standing:** Green (Milestone 0 — 0 DP earned; pure creation build)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 0 | Reflex 3 | Wits 1 | Will 0 *(Spike array)*
- **Skills:** Thievery 3 | Stealth 3 | Acrobatics 1 | Melee 1 *(8 ranks, 8 DP. Ceilings: Thievery/Stealth/Acrobatics 6 (Reflex 3); Melee 3 (Brawn 0))*
- **Wound Threshold:** 4 *(4 base + 0 Brawn + 1 Leather − 1 Hollow-Boned)*
- **Stress Limit:** 5 *(4 base + 1 Wits + 0 Will)*
- **Wound Slots:** 3 | **Momentum Bank:** 7 *(4 + Reflex 3)* | **Activation Order:** 9 *(6 + Reflex 3)*
- **Inventory Slots:** 8 *(8 + 0 Brawn)*

#### Species Traits (Elf)
- **Fey Reflexes:** Advantage on Acrobatics checks to avoid environmental hazards, traps, or AoE.
- **Trance:** Only needs 4 hours of meditation instead of a full night's rest to clear Stress and stabilize Wounds.
- **Hollow-Boned (Drawback):** −1 Wound Threshold (already applied above).

#### Feats
- **Shadow-Weaver** *(Stealth 1 — Creation)*: ignores the standard penalty for moving quickly while trying to stay hidden.
- **Scavenger's Eye** *(Wits +1, Stealth +1 — Creation)*: a Massive Success (Margin 5+) on an exploration or scouting check banks 2 Momentum instead of 1.

#### Equipment
- **Armour:** Leather (+1 Armour, Light)
- **Weapons:** Twin Daggers — 2× Dagger/Knife (5 sp each, Concealable, Close-Quarters, Finesse, Thrown, Sidearm), wielded in the **Twin-Blade Stance** (Off-Hand Parry; the Twin Strike maneuver for 1 Momentum)
- **Starting Purse: 80 sp** — Leather 12 + 2× Dagger 10 = **22 sp spent, 58 sp remaining.** Smokestick (15 sp) + Tanglefoot Bag (20 sp) = 35 sp, **23 sp banked.**

#### Combat Math Quick-Ref
Melee Clash (Daggers) 2d6+1 | Thievery 2d6+3 | Stealth 2d6+3 | Acrobatics 2d6+1 | Dodge 2d6+1 | **Notice 2d6+0** | Activation Order 9

---

### Brynja Frostvow — Dwarf Female, Faith/Ranged Hybrid (Winter & Wilds Domain)

*"The wolf doesn't need faith. It just needs a clean shot."*

#### Vital Statistics
- **Species:** Dwarf
- **Standing:** Green (Milestone 0 — 0 DP earned; pure creation build)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 1 | Reflex 1 | Wits 1 | Will 1 *(Flat array)*
- **Skills:** Faith 3 | Ranged 3 | Survival 1 | Notice 1 *(8 ranks, 8 DP. Ceilings: Faith/Resolve/Influence 4 (Will 1); Ranged/Stealth/Thievery/Acrobatics 4 (Reflex 1); Notice/Insight/Medicine/Crafting/Lore/Arcana 4 (Wits 1); Melee/Athletics/Block/Prowess 4 (Brawn 1) — every ceiling in her sheet is the same number, the one thing only Flat can do)*
- **Wound Threshold:** 7 *(4 base + 1 Brawn + 1 Leather + 1 Stone-Bones)*
- **Stress Limit:** 6 *(4 base + 1 Wits + 1 Will)*
- **Wound Slots:** 3 | **Momentum Bank:** 5 *(4 + Reflex 1)* | **Activation Order:** 7 *(6 + Reflex 1)*
- **Inventory Slots:** 9 *(8 + 1 Brawn)*

#### Species Traits (Dwarf)
- **Stone-Bones:** +1 Wound Threshold (already applied above).
- **Subterranean Senses:** Advantage on Notice checks underground or examining stonework/engineering.
- **Stumpy (Drawback):** Disadvantage on Athletics checks during chases or open-ground sprints.

#### Feats
- **Divine Conduit** *(The Covenant, Domain of Winter & Wilds — Creation)*. Grants a Holy Symbol, the **Chilling Frost** Domain Tag (an offensive prayer numbs its target — they can't Move next turn unless they take 1 physical Stress to snap free), and the 4 Novice Prayers below.
- **Scavenger's Eye** *(Wits +1, Survival +1 — Creation)*: a Massive Success (Margin 5+) on an exploration or scouting check banks 2 Momentum instead of 1 — pairs directly with Kaelen's Eye below.

#### Equipment
- **Armour:** Leather (+1 Armour, Light — doesn't touch Faith or Ranged)
- **Weapon (one 2H item):** Shortbow (Power 2, **Volley** — requires both hands, no Shield or Grimoire while wielding it; Holy Symbol still works one-handed and isn't a Grimoire)
- **Holy Symbol** (granted by Divine Conduit — outside the purse)
- **Starting Purse: 80 sp** — Leather 12 + Shortbow 15 = **27 sp spent, 53 sp remaining.** Antitoxin (20 sp) + Sunrod (5 sp) = 25 sp, **28 sp banked** for arrows, a spare bowstring, and rope.

#### Prayers (Tithe of Will = 2d6 + Faith = **2d6+3**, vs. TN 8 Novice)
- **Rime-Fang's Bite** *(2 Locked Stress, Aggressor, Short Range)* — Pass: target fails a Prowess+Athletics check (TN 8) or takes 2 Dissonant Stress and gains Rigor as the cold seizes its joints. Fail: as Pass + 1 Encroachment. Snake Eyes: convert the 2 Locked Stress into 2 direct Wounds, reset Encroachment.
- **Howl of the Rime-Fang** *(2 Locked Stress, Aggressor, 15ft radius, Short Range)* — Pass: every enemy in range fails a Resolve check (TN 8) or gains Fear. Fail: as Pass + 1 Encroachment. Snake Eyes: convert to 2 direct Wounds, reset Encroachment.
- **Wolf's Ward** *(1 Locked Stress, Activation, touch, Scene)* — Pass: target ignores Stress and penalties from extreme environmental hazards (per Iron World's Hazard Check rules) for the scene. Fail: as Pass + 1 Encroachment. Snake Eyes: convert to 1 direct Wound, reset Encroachment.
- **Kaelen's Eye** *(1 Locked Stress, Activation, self, Scene)* — Pass: reads the wild like Kaelen did — Advantage on Survival or Notice checks to track a specific creature or navigate harsh terrain. Fail: as Pass + 1 Encroachment. Snake Eyes: convert to 1 direct Wound, reset Encroachment.

#### Combat Math Quick-Ref
Tithe of Will 2d6+3 | Ranged Strike (Shortbow) 2d6+3, Impact = Margin+2 | Survival 2d6+1 | Notice 2d6+1 | Dodge 2d6+0 | Activation Order 7

---

### Maren Solvei — Half-Elf Female, Envoy (Social/Support)

*"A blade wins the fight. A word wins everything after it."*

#### Vital Statistics
- **Species:** Half-Elf (Split Heritage: took Adaptable, and its paired Steady, Not Sharp drawback)
- **Standing:** Green (Milestone 0 — 0 DP earned; pure creation build)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 0 | Reflex 1 | Wits 1 | Will 2 *(Broad array)*
- **Skills:** Influence 3 | Medicine 2 | Insight 2 | Notice 1 | Resolve 1 *(9 ranks, 9 DP with Adaptable. Ceilings: Influence/Faith/Survival/Resolve 5 (Will 2); Medicine/Insight/Notice/Crafting/Lore/Arcana 4 (Wits 1); Ranged/Stealth/Thievery/Acrobatics/Ride 4 (Reflex 1); Melee/Athletics/Block/Prowess 3 (Brawn 0))*
- **Wound Threshold:** 5 *(4 base + 0 Brawn + 1 Leather)*
- **Stress Limit:** 7 *(4 base + 1 Wits + 2 Will)*
- **Wound Slots:** 3 | **Momentum Bank:** 4 *(4 + Reflex 1, −1 Steady Not Sharp)* | **Activation Order:** 7 *(6 + Reflex 1)*
- **Inventory Slots:** 8 *(8 + 0 Brawn)*

#### Species Traits (Half-Elf, Split Heritage)
- **Silver-Tongued:** Advantage on Influence checks to persuade, de-escalate, negotiate, or gather information.
- **Adaptable** *(chosen Split Heritage trait)*: +1 Skill **DP** at creation (already applied — a Half-Elf who takes Adaptable has a creation Skill budget of 9, not 8).
- **Steady, Not Sharp (Drawback, comes with Adaptable):** −1 to your Momentum Bank cap (already applied above).
- **Between Worlds (Drawback):** Disadvantage on Influence checks with an insular or homogeneous community that's had little outside contact.

#### Feats
- **Cold Reader** *(Insight +1, Notice +1 — Creation)*: on entering a tense social situation, a Free Action Insight check (TN 8) reveals which NPC present has the lowest Resolve — Advantage on her first Influence check against them.
- **Battlefield Orator** *(Influence +2 — Creation)*: spend an Action in combat to shout orders or hurl insults. Choose one: an ally immediately clears 1d6 Dissonant Stress, or an engaged enemy suffers a -2 penalty to their next Defense roll.

#### Equipment
- **Armour:** Leather (+1 Armour, Light)
- **Weapon:** Dagger (Concealable, Close-Quarters, Finesse, Thrown, Sidearm)
- **Starting Purse: 80 sp** — Leather 12 + Dagger 5 = **17 sp spent, 63 sp remaining.** Grave-Dust Poultice (8 sp) + a merchant's scale (3 sp, Advantage on Insight/Notice to catch a rigged deal or counterfeit coin) = 11 sp, **52 sp banked** — she carries coin, not gear, and spends it on people rather than steel.

#### Combat Math Quick-Ref
Influence 2d6+3 | Medicine 2d6+2 | Insight 2d6+2 | Notice 2d6+1 | Resolve 2d6+1 | Melee (Dagger) 2d6+0, Impact = Margin | Dodge 2d6+0 | Activation Order 7

---

### Corvin Ashgrave — Human Male, Bravo (Duelist)

*"You are not losing to me. You are losing to the fact that you brought one weapon."*

#### Vital Statistics
- **Species:** Human
- **Standing:** Green (Milestone 0 — 0 DP earned; pure creation build)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 2 | Reflex 2 | Wits 0 | Will 0 *(Twin array)*
- **Skills:** Melee 4 | Acrobatics 3 | Prowess 1 | Notice 1 *(9 ranks, 9 DP with Adaptable. Ceilings: Melee/Prowess/Block/Athletics 5 (Brawn 2); Acrobatics/Stealth/Ranged 5 (Reflex 2); everything under Wits or Will 3)*
- **Wound Threshold:** 6 *(4 base + 2 Brawn + 0 Gambeson)*
- **Stress Limit:** 5 *(4 base + 0 Wits + 0 Will + 1 Indomitable Spirit)*
- **Wound Slots:** 3 | **Momentum Bank:** 5 *(4 + Reflex 2, −1 Steady Not Sharp)* | **Activation Order:** 11 *(6 + Reflex 2, +3 Quick)*
- **Inventory Slots:** 10 *(8 + 2 Brawn)*

#### Species Traits (Human)
- **Adaptable:** +1 Skill **DP** at creation (already applied — a Human's creation Skill budget is 9, not 8).
- **Indomitable Spirit:** +1 Stress Limit (already applied above).
- **Steady, Not Sharp (Drawback):** −1 to your Momentum Bank cap.

#### Feats
- **Iron Grip** *(Melee +1 — Creation)*: when a Clash ties and the weapons bind, automatically bank 1 Momentum. His Momentum engine — a Twin-array duelist has a small bank and needs to fill it without spending actions.
- **Quick** *(Reflex 1 — Creation)*: +3 to your Activation Order.

#### Equipment
- **Armour:** Gambeson (+0 Armour, Light, Cushioned) — his actual creation-day kit; upgraded to Leather during Downtime after Milestone 1, per his Blooded sheet.
- **Starting Purse: 80 sp** — Gambeson 5 + Shortsword 10 + Dagger 5 = **20 sp spent, 60 sp remaining.**
- **Weapons (two 1H items):** Shortsword (Power 2, **Sidearm**, **Finesse**) + Dagger (Power 0, **Sidearm**, **Finesse**, Concealable, Close-Quarters, Thrown) — qualifies for **Twin-Blade Stance**.

#### Combat Math Quick-Ref
Strike (Shortsword) 2d6+4, Impact = Margin+2 | Parry 2d6+4 | Dodge 2d6+3 | **Finesse on both** — reroll a natural 1 in any Clash with either blade, attacking or defending | **Off-Hand Parry:** the Dagger reduces incoming Impact by 1, stacking with the Shortsword | **Twin Strike:** 1 Momentum on a won Clash for an off-hand follow-up | Prowess 2d6+1 | Notice 2d6+1 | **Resolve 2d6+0** | Activation Order 11

---

### Dorin Hollowmark — Dwarf Male, Arcana Caster (Demonology and Void Magic)

*"The mountain has secrets even the Ancestors were wise enough to leave buried. I dug them up anyway."*

#### Vital Statistics
- **Species:** Dwarf
- **Standing:** Green (Milestone 0 — 0 DP earned; pure creation build)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 0 | Reflex 0 | Wits 3 | Will 1 *(Spike array — 3/1/0/0)*
- **Skills:** Arcana 3 | Notice 2 | Insight 2 | Lore 1 *(8 ranks, 8 DP. Ceilings: Arcana/Notice/Insight/Medicine/Crafting/Lore 6 (Wits 3); Resolve/Influence/Faith 4 (Will 1); everything under Brawn or Reflex 3)*
- **Wound Threshold:** 6 *(4 base + 0 Brawn + 1 Leather + 1 Stone-Bones)*
- **Stress Limit:** 8 *(4 base + 3 Wits + 1 Will)*
- **Wound Slots:** 3 | **Momentum Bank:** 4 *(4 + Reflex 0)* | **Activation Order:** 6 *(6 + Reflex 0)*
- **Inventory Slots:** 8 *(8 + 0 Brawn)*

#### Species Traits (Dwarf)
- **Stone-Bones:** +1 Wound Threshold (already applied above).
- **Subterranean Senses:** Advantage on Notice checks underground or examining stonework/engineering.
- **Stumpy (Drawback):** Disadvantage on Athletics checks during chases or open-ground sprints.

#### Feats
- **Arcane Awakening** *(Paradigm: Demonology and Void Magic — Creation)*. Grimoire below — 2 picks in-Paradigm, 1 from Witch Magic and Hedge Craft, 1 from Common; per the feat's own text every Arcane Awakening character takes at least 1 off-Paradigm spell among their starting 4, since each Paradigm's Novice tier holds exactly 3. Dorin goes one further than the minimum, trading a third Demonology pick for a second off-Paradigm one.
- **Ledger of the Deep** *(Insight +1, Lore +1 — Creation)*: on a Massive Success (Margin 5+) on an Insight or Lore check made to identify a creature, curse, or occult phenomenon, he immediately banks 1 Momentum. His only Momentum engine — nothing else on the sheet generates it.

#### Equipment
- **Focus:** Grimoire (1H, **Repository**) — 15 sp — held in his off hand, plus a **Wand** (1H, **Conduit**, **Sidearm**) — 10 sp — in his casting hand. The Grimoire satisfies the Repository requirement; Conduit means the hand holding the Wand still counts as free for the somatic component. Both Casting Requirements met, no Blind Casting penalty, and no hand left over.
- **Armour:** Leather (+1 Armour, Light) — 12 sp. Light armour carries no Arcana penalty.
- **Starting Purse: 80 sp** — Grimoire 15 + Wand 10 + Leather 12 = 37 sp. Black-Root Draught 15 + Philter of Focus 20 + Grave-Dust Poultice 8 = 43 sp. **80 sp spent, 0 sp remaining.**

#### Grimoire (Arcana = **2d6+3**)
- **Fear** *(Demonology, Paradigm, Mastery-eligible)* — Arcane Clash, Arcana vs. Target's Resolve, one character or 10ft area, Short Range, Aggressor. Margin 1–2: target suffers 2 Dissonant Stress and must spend their next Activation fleeing at max speed; he takes 1 Dissonant Stress from the strain. Margin 3+ (Clean, or Mastery-upgraded from 1–2): as above, and a Fodder-tier target immediately Routs instead of just fleeing.
- **Void Rend** *(Demonology, Paradigm, Mastery-eligible)* — Arcane Clash, Arcana vs. Target's Defense, Medium Range, Spell Power 2, Aggressor. Margin 1–2: Impact = Margin+2, ignoring 1 point of the target's Shield Value or Armour; he takes 1 Dissonant Stress. Margin 3+ (Clean, or Mastery-upgraded from 1–2): as above, no cost.
- **The Evil Eye** *(Witch Magic and Hedge Craft, off-Paradigm — no Mastery)* — Arcane Clash, Arcana vs. Target's Resolve, Short Range, Aggressor. Margin 1–2: target is Hexed — Disadvantage on their next Aggressor Strike or Reactor defense roll; he takes 1 Dissonant Stress. Margin 3+ (Clean): as above, and if the Hexed roll then fails, the target also suffers 1 Dissonant Stress from the backlash.
- **Arcane Protection** *(Common — no Mastery)* — Unopposed vs. TN 8, **Activation to raise only; it can never be cast as a Reactor**, **self only**, Sustain (see The Channelling Rule — no Locked Stress cost; roll to maintain each Activation and on taking a Wound). Margin 0–2: ward holds, he takes 1 Dissonant Stress. Margin 3–4: ward holds, hostile spells targeting him suffer Disadvantage on their casting roll. Margin 5+: as Clean, and the ward gains SV 2 against the next hostile spell's Impact. Special: while the ward stands he may use **Arcana as his defense** against an incoming hostile spell in place of his normal Reactor stat — at every band, Messy included. *Spell* is the generic term, so this answers hostile **Prayers** too.

#### Combat Math Quick-Ref
Arcane Clash/Manifestation 2d6+3 | Notice 2d6+2 | Insight 2d6+2 | Lore 2d6+1 | Dodge 2d6+0 *(no Acrobatics investment)* | Activation Order 6

---

## Blooded

### Wren Ashcombe — Halfling Female, Cutthroat (Thief)

*"I've never once needed to win a fight I could just... not have."*

#### Vital Statistics
- **Species:** Halfling — **Size:** Small (Scale -1)
- **Standing:** Blooded (Milestone 1 — 3 DP earned, 0 banked)
- **Attributes:** Brawn 0 | Reflex 3 | Wits 1 | Will 0 *(Spike array)*
- **Skills:** Melee 1 | Stealth 3 | Thievery 2 | Acrobatics 2 *(8 ranks, 8 DP. Ceilings: Melee 3 (Brawn 0); Stealth/Thievery/Acrobatics 6 (Reflex 3))*
- **Wound Threshold:** 4 *(4 base + 0 Brawn + 1 Leather − 1 Scale)*
- **Stress Limit:** 5 *(4 base + 1 Wits + 0 Will — Halflings are exempt from the Scale Stress penalty)*
- **Wound Slots:** 3 | **Momentum Bank:** 7 *(4 + Reflex 3)* | **Activation Order:** 12 *(6 + Reflex 3, +3 Quick)*
- **Inventory Slots:** 8 *(8 + 0 Brawn)*
- **Stress Track (Limit 5):** [/][ ][ ][ ][ ] — 1 box permanently Locked to Attunement (Whisper-Kissed Leathers).
- **Attunement:** 1 slot *(Attunement Slots = Will score, minimum 1 — at Will 0 she gets the floor)*. The Leathers fill it. She cannot attune a second Enchanted or Relic item at any price until Will rises.

#### Species Traits (Halfling)
- **Underfoot:** Advantage on Stealth with cover or obscurement, or when moving through a larger creature's space.
- **Halfling Luck:** Once per session, ignore a Fumble's Stress penalty.
- **Small Stature (Drawback):** Cannot wield weapons carrying the Cumbersome tag — irrelevant to this build. Also exempt from the Scale −1 Stress Limit penalty (see The Marrow).

#### Feats
- **Quick** *(Reflex 1 — Creation)*: +3 to your Activation Order.
- **Shadow-Weaver** *(Stealth 1 — Creation)*: ignores the Rushed Stealth penalty for moving quickly while hidden.
- **Parasitic Momentum** *(Cutthroat, Tier 2; Tier 1 feat ✓ — Quick and Shadow-Weaver both qualify — Milestone 1)*: when an enemy within 30 ft rolls a Fumble, instantly bank 1 Momentum.

#### Equipment
- **Armour:** Leather (+1 Armour, Light).
- **Weapons:** Twin Daggers (1H/1H, **Concealable, Close-Quarters, Finesse, Thrown, Sidearm** — per Hardware's Dagger/Knife entry) — qualifies for **Twin-Blade Stance** (Off-Hand Parry, Twin Strike). *Finesse rerolls a natural 1 on any Clash she makes or defends with them, which on a Twin build applies to Strike, Parry and Off-Hand Parry alike.*
- **Starting Purse: 80 sp** — Twin Daggers 10 + Leather 12 + Thieves' Tools 20 + Grappling hook 3 + Rope, hemp 50 ft 2 = **47 sp spent, 33 sp remaining** at creation, plus chalk at a copper. Thieves' Tools are not optional kit: without them a Thievery check against a lock or mechanism is made at Disadvantage regardless of rank. The remaining 33 sp is a working float she has been careful not to spend down.
- **Acquired in play (Milestone 1):** main-hand dagger fitted with **Cold Iron Weapon** (Charmed, 25 sp, no Attunement): Bane (Fey, Daemon). Leather fitted with **Whisper-Kissed Leathers** (Enchanted — **Legendary band, Commission-gated**, 1 Locked Stress Attunement; requires a Light armour base, which her Leather satisfies). *Neither could have been bought at creation: enchanted gear of any tier is barred at Green (see The Starting Purse, The Marrow). The Cold Iron came off the job that earned her first Milestone. The Leathers did not — a Commission-gated item is made to order and never drops as generic loot, so they came off the body of whoever commissioned them, which is the only route onto a Blooded sheet.* **GM note:** a Legendary item at Milestone 1 is a deliberate story award, not what Blooded is expected to carry. Do not read the roster as promising it.
- **Spell list:** N/A (non-caster).
- **Belt (3 max):** Twin Daggers (2 slots) — 1 slot free. **Pack:** 6 slots free.

#### Combat Math Quick-Ref
Dagger Strike 2d6+1 | Dodge 2d6+2 | Stealth 2d6+3 | Thievery 2d6+2 | **Melee 2d6+1** | Activation Order 12

---

### Corvin Ashgrave — Human Male, Bravo (Duelist)

*"You are not losing to me. You are losing to the fact that you brought one weapon."*

#### Vital Statistics
- **Species:** Human
- **Standing:** Blooded (Milestone 2 — 6 DP earned, 0 banked)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 2 | Reflex 2 | Wits 0 | Will 0 *(**Twin** array)*
- **Skills:** Melee 4 | Acrobatics 3 | Prowess 1 | Notice 1 *(9 ranks, 9 DP with Adaptable. Ceilings: Melee/Prowess/Block/Athletics 5 (Brawn 2); Acrobatics/Stealth/Ranged 5 (Reflex 2); everything under Wits or Will 3)*
- **Wound Threshold:** 7 *(4 base + 2 Brawn + 1 Leather)*
- **Stress Limit:** 5 *(4 base + 0 Wits + 0 Will + 1 Indomitable Spirit)*
- **Wound Slots:** 3 | **Momentum Bank:** 5 *(4 + Reflex 2, −1 Steady Not Sharp)* | **Activation Order:** 11 *(6 + Reflex 2, +3 Quick)*
- **Inventory Slots:** 10 *(8 + 2 Brawn)*

#### Species Traits (Human)
- **Adaptable:** +1 Skill **DP** at creation (already applied — a Human's creation Skill budget is 9, not 8).
- **Indomitable Spirit:** +1 Stress Limit (already applied above).
- **Steady, Not Sharp (Drawback):** −1 to your Momentum Bank cap.

#### Feats
- **Iron Grip** *(Melee +1 — Creation)*: when a Clash ties and the weapons bind, automatically bank 1 Momentum. His Momentum engine — a Twin-array duelist has a small bank and needs to fill it without spending actions.
- **Quick** *(Reflex 1 — Creation)*: +3 to your Activation Order.
- **Riposte** *(Melee 2 — Milestone 2)*: winning a Parry inflicts Impact on the attacker outright.
- **The Insulting Deflection** *(Bravo, Tier 2; Reflex +2, Melee +2 — Milestone 2)*: on a Parry won by Margin 5+, spend 1 Momentum to inflict Surprised on the Aggressor.

#### Equipment
- **Armour:** Leather (+1 Armour, Light) — Gambeson at creation, upgraded during Downtime after Milestone 1.
- **Starting Purse: 80 sp** — Gambeson 5 + Shortsword 10 + Dagger 5 = **20 sp spent, 60 sp remaining.** The cheapest kit on the roster by some distance, and entirely on purpose: a duelist's Wound Threshold comes from not being hit. He spent the difference on a wardrobe good enough to get him invited to the sort of rooms where the work is, and kept the rest liquid. The Leather upgrade at Milestone 1 cost him 12 sp of that float.
- **Weapons (two 1H items):** Shortsword (Power 2, **Sidearm**, **Finesse**) + Dagger (Power 0, **Sidearm**, **Finesse**, Concealable, Close-Quarters, Thrown) — qualifies for **Twin-Blade Stance**.

#### Combat Math Quick-Ref
Strike (Shortsword) 2d6+4, Impact = Margin+2 | Parry 2d6+4 | Dodge 2d6+3 | **Finesse on both** — reroll a natural 1 in any Clash with either blade, attacking or defending | **Off-Hand Parry:** the Dagger reduces incoming Impact by 1, stacking with the Shortsword | **Twin Strike:** 1 Momentum on a won Clash for an off-hand follow-up | Prowess 2d6+1 | Notice 2d6+1 | **Resolve 2d6+0** | Activation Order 11

---

## Veteran

### Aeric Thorne — Half-Elf Male, Berserker

*"You don't win a fight. You make sure you're the last thing standing in it."*

#### Vital Statistics
- **Species:** Half-Elf (Split Heritage: took Fey Reflexes, and its paired Hollow-Boned drawback)
- **Standing:** Veteran (Milestone 3 — 9 DP earned via Advancement, 0 banked)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 3 | Reflex 2 | Wits 0 | Will 0 *(Twin array)*
- **Skills:** Melee 3 | Athletics 2 | Prowess 2 | Resolve 2 *(9 ranks — 8 from Creation, 1 from Advancement. Ceilings: Melee/Athletics/Prowess/Block 6 (Brawn 3); Resolve 3 (Will 0))*
- **Wound Threshold:** 7 *(4 base + 3 Brawn + 1 Leather − 1 Hollow-Boned)*
- **Stress Limit:** 4 *(4 base + 0 Wits + 0 Will)*
- **Wound Slots:** 3 | **Momentum Bank:** 6 *(4 + Reflex 2)* | **Activation Order:** 7 *(6 + Reflex 2, −1 Cumbersome)*
- **Inventory Slots:** 11 *(8 + 3 Brawn)*

#### Species Traits (Half-Elf, Split Heritage)
- **Fey Reflexes** *(chosen Split Heritage trait)*: Advantage on Acrobatics checks vs. hazards, traps, AoE.
- **Between Worlds (Drawback):** Disadvantage on Influence in insular/xenophobic communities.
- **Hollow-Boned (Drawback, comes with Fey Reflexes):** −1 Wound Threshold (already applied above).

#### Feats
- **Desperate Edge** *(Resolve +1 — Creation)*: when a lone die in a 2d6 check shows a 6 while at half-or-more Stress Limit in Dissonant Stress, or on his final Wound Slot, it explodes — roll an extra d6 and add it.
- **Trench Fighter** *(Brawn +1 — Creation)*: ignores Difficult Terrain's Disadvantage, and drawing a weapon while engaged doesn't take the usual penalty.
- **The Red Mist** *(Berserker, Tier 2; Brawn 2, Resolve 2 — Milestone 2)*: if he suffers a Minor or Major Wound from a melee attack, his nervous system rejects the shock — he may immediately spend 1 Momentum to perform a brutal, retaliatory Strike against the attacker, instantly, before the Engagement ends and before he takes any associated Stress.

#### Equipment
- **Armour:** Leather (+1 Armour, Light)
- **Weapon:** Greataxe (Power 5, 2H, Heavy Hitter, Cumbersome, Scarce)
- **Starting Purse: 80 sp** — Leather 12 + Greataxe 40 = **52 sp spent, 28 sp remaining.** Grave-Dust Poultice (8 sp) + Witch-Spur Salve (12 sp) = 20 sp, **8 sp banked.** *(No Downtime purchases assumed across the three Milestones — every DP went into the archetype, not the kit.)*

#### Combat Math Quick-Ref
Melee Clash 2d6+3 *(Power 5; **Heavy Hitter** — every natural 6 on his 2d6 counts as a 7, and neither Fate's Bounty nor Desperate Edge's exploding die applies to this axe)* | Athletics 2d6+2 | Prowess 2d6+2 | Resolve 2d6+2 | Activation Order 7

---

### Brynja Frostvow — Dwarf Female, Faith/Ranged Hybrid (Winter & Wilds Domain)

*"The wolf doesn't need faith. It just needs a clean shot."*

#### Vital Statistics
- **Species:** Dwarf
- **Standing:** Veteran (Milestone 3 — 9 DP earned via Advancement, 0 banked)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 1 | Reflex 1 | Wits 2 | Will 1 *(Flat array at creation — no longer flat)*
- **Skills:** Faith 3 | Ranged 3 | Survival 2 | Notice 1 *(9 ranks — 8 from Creation, 1 from Advancement. Ceilings: Faith/Resolve/Influence 4 (Will 1); Ranged/Stealth/Thievery/Acrobatics 4 (Reflex 1); Notice/Insight/Medicine/Crafting/Lore/Arcana 5 (Wits 2); Melee/Athletics/Block/Prowess 4 (Brawn 1))*
- **Wound Threshold:** 7 *(4 base + 1 Brawn + 1 Leather + 1 Stone-Bones)*
- **Stress Limit:** 7 *(4 base + 2 Wits + 1 Will)*
- **Wound Slots:** 3 | **Momentum Bank:** 5 *(4 + Reflex 1)* | **Activation Order:** 7 *(6 + Reflex 1)*
- **Inventory Slots:** 9 *(8 + 1 Brawn)*

#### Species Traits (Dwarf)
- **Stone-Bones:** +1 Wound Threshold (already applied above).
- **Subterranean Senses:** Advantage on Notice checks underground or examining stonework/engineering.
- **Stumpy (Drawback):** Disadvantage on Athletics checks during chases or open-ground sprints.

#### Feats
- **Divine Conduit** *(The Covenant, Domain of Winter & Wilds — Creation)*. Grants a Holy Symbol, the **Chilling Frost** Domain Tag, and the 4 Novice Prayers below.
- **Scavenger's Eye** *(Wits +1, Survival +1 — Creation)*: a Massive Success (Margin 5+) on an exploration or scouting check banks 2 Momentum instead of 1.
- **Predator's Rhythm** *(Stalker, Tier 2; Wits 2, Survival 2 — Milestone 3)*: when she successfully kills or Incapacitates a Fodder or Grunt-level enemy, she may immediately clear 1 Dissonant Stress or bank 1 Momentum, her choice — triggers off a Shortbow kill or a Prayer kill equally.

#### Equipment
- **Armour:** Leather (+1 Armour, Light — doesn't touch Faith or Ranged)
- **Weapon (one 2H item):** Shortbow (Power 2, **Volley**)
- **Holy Symbol** (granted by Divine Conduit — outside the purse)
- **Starting Purse: 80 sp** — Leather 12 + Shortbow 15 = **27 sp spent, 53 sp remaining.** Antitoxin (20 sp) + Sunrod (5 sp) = 25 sp, **28 sp banked.** *(No Downtime purchases assumed across the three Milestones.)*

#### Prayers (Tithe of Will = 2d6 + Faith = **2d6+3**, vs. TN 8 Novice)
- **Rime-Fang's Bite** *(2 Locked Stress, Aggressor, Short Range)* — Pass: target fails a Prowess+Athletics check (TN 8) or takes 2 Dissonant Stress and gains Rigor. Fail: as Pass + 1 Encroachment. Snake Eyes: convert to 2 direct Wounds, reset Encroachment.
- **Howl of the Rime-Fang** *(2 Locked Stress, Aggressor, 15ft radius, Short Range)* — Pass: every enemy in range fails a Resolve check (TN 8) or gains Fear. Fail: as Pass + 1 Encroachment. Snake Eyes: convert to 2 direct Wounds, reset Encroachment.
- **Wolf's Ward** *(1 Locked Stress, Activation, touch, Scene)* — a fixed-duration effect, not a Flowing Prayer: no per-Activation maintenance roll. Pass: target ignores Stress and penalties from extreme environmental hazards for the scene. Fail: as Pass + 1 Encroachment. Snake Eyes: convert to 1 direct Wound, reset Encroachment.
- **Kaelen's Eye** *(1 Locked Stress, Activation, self, Scene)* — also fixed-duration, not Flowing. Pass: Advantage on Survival or Notice checks to track a specific creature or navigate harsh terrain. Fail: as Pass + 1 Encroachment. Snake Eyes: convert to 1 direct Wound, reset Encroachment.

#### Combat Math Quick-Ref
Tithe of Will 2d6+3 | Ranged Strike (Shortbow) 2d6+3, Impact = Margin+2 | Survival 2d6+2 | Notice 2d6+1 | Dodge 2d6+0 | Activation Order 7

---

## Hardened

### Uzgar "Ox" Bellows — Half-Orc Male, Frontline Anchor

*"You want to know what breaks first — my line, or their nerve? Ask the last three things that tried."*

#### Vital Statistics
- **Species:** Half-Orc
- **Standing:** Hardened (Milestone 6 — 18 DP earned via Advancement, 0 banked)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 3 | Reflex 0 | Wits 0 | Will 2
- **Skills:** Melee 3 | Block 2 | Prowess 2 | Resolve 2 *(9 ranks. Ceilings: Melee/Block/Prowess/Athletics 6 (Brawn 3); Resolve/Influence/Faith/Survival 5 (Will 2))*
- **Wound Threshold:** 9 *(4 base + 3 Brawn + 2 Chain Shirt + 0 Species)*
- **Stress Limit:** 8 *(4 base + 0 Wits + 2 Will + 2 Stoic Resolve feat)*
- **Wound Slots:** 3 | **Momentum Bank:** 4 *(4 + Reflex 0 — Half-Orc carries no cap penalty; his Reflex does)* | **Activation Order:** 6 *(6 + Reflex 0)*
- **Inventory Slots:** 11 *(8 + 3 Brawn)*

#### Species Traits (Half-Orc)
- **Blood Frenzy:** Suffering a Wound instantly clears 1 Dissonant Stress.
- **Menacing:** Advantage on Influence checks to intimidate anyone smaller or weaker.
- **Outcast (Drawback):** Disadvantage on social checks with civilized strangers who don't know him.

#### Feats
- **Iron Grip** *(Tier 1; Melee 1 ✓ — Creation)*: when a Clash ties and the weapons bind, automatically bank 1 Momentum. On a Momentum Bank of 4 with Reflex 0, this is his only reliable income that doesn't cost him an action.
- **Trench Fighter** *(Tier 1; Brawn 1 ✓ — Creation)*: ignores the Disadvantage penalty from Difficult Terrain, and drawing a weapon while engaged carries no Disadvantage. An anchor who can't be made to fight badly on bad ground.
- **Juggernaut** *(Tier 2; Brawn 2 ✓, Tier 1 feat ✓ — Milestone 3)*: Spend 1 Momentum to add 2 to Wound Threshold against one incoming attack. Stacks with Brace.
- **Giant Feller** *(Tier 2; Brawn 2 ✓, Prowess 2 ✓, Tier 1 feat ✓ — Milestone 4)*: May Grab/Shove creatures up to two Scale steps larger. Ignores the automatic 1 Stress penalty when Blocking a larger enemy's attack.
- **Stoic Resolve** *(Tier 1; Will 2 ✓, Resolve 1 ✓ — Milestone 5)*: +2 Stress Limit (already applied above). The Reprieve and Adrenaline Flush clear 1 extra point of the relevant Stress type.
- **Iron Conviction** *(Tier 2; Will 2 ✓, Resolve 2 ✓, Tier 1 feat ✓ — Milestone 6)*: The Blood Price (Momentum's 1-cost Wound→2 Dissonant Stress conversion) costs no Momentum.

#### Equipment
- **Armour:** Chain Shirt (+2 Armour, Light — chosen over the heavier Chainmail/Scale specifically so nothing taxes his Athletics), fitted with **Armour Spikes** (15 sp, bought during Downtime after Milestone 4) — anyone who loses a Grab/Shove Clash against him takes 1 Dissonant Stress.
- **Starting Purse: 80 sp** — Chain Shirt 50 + Battleaxe 12 + Kite Shield 18 = **80 sp spent, 0 sp remaining.** He walked out of character creation with the best armour a Town will sell him, a shield, an axe, and not one silver piece left over. Everything else on this sheet — both sets of spikes — was bought later, out of money earned in play.
- **Weapons/Shield (two 1H items):** Battleaxe (Power 2, **Brutal**, **Inertia**) + Kite Shield (4 SV, **Cover**), the shield fitted with **Shield Spikes** (8 sp, same Downtime trip) — a won Shove with the shield deals +1 Impact.
    - *Inertia:* +2 Power on a Margin 5+ win. *Brutal:* each natural 4 showing on his 2d6 in a Clash adds +1 to the Impact the axe generates, so double 4s add +2.

#### Combat Math Quick-Ref
Melee Strike (Battleaxe) 2d6+3, Impact = Margin+2 (+2 more on Margin 5+ from Inertia; +1 per natural 4 from Brutal) | Block 2d6+2 (Kite Shield's 4 SV eats Impact before it hits WT 9 on a loss) | Grab/Shove/Brace 2d6+2 (Prowess — what Giant Feller rides on) | Dodge 2d6+0 (he blocks, he doesn't dance) | Resolve 2d6+2 | Influence (intimidation) 2d6+0, Advantage vs. smaller/weaker | Activation Order 6

---

### Morwenna Duskhollow — Elf Female, Arcana Caster (Necromancy)

*"The dead don't lie to me. They're far too tired for games the living still play."*

#### Vital Statistics
- **Species:** Elf
- **Standing:** Hardened (Milestone 7 — 21 DP earned via Advancement, 2 banked)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 0 | Reflex 0 | Wits 3 | Will 2
- **Skills:** Arcana 4 | Notice 2 | Insight 2 | Resolve 2 | Medicine 1 | Lore 1 *(12 ranks. Ceilings: Arcana/Notice/Insight/Lore 6 (Wits 3); Resolve 5 (Will 2); Medicine 6 (Wits 3))*
- **Wound Threshold:** 4 *(4 base + 0 Brawn + 1 Leather − 1 Hollow-Boned)*
- **Stress Limit:** 9 *(4 base + 3 Wits + 2 Will)*
- **Wound Slots:** 3 | **Momentum Bank:** 4 *(4 + Reflex 0)* | **Activation Order:** 6 *(6 + Reflex 0)*
- **Inventory Slots:** 8 *(8 + 0 Brawn)*

#### Species Traits (Elf)
- **Fey Reflexes:** Advantage on Acrobatics checks to avoid environmental hazards, traps, or AoE.
- **Trance:** Only needs 4 hours of meditation instead of a full night's rest to clear Stress and stabilize Wounds.
- **Hollow-Boned (Drawback):** −1 Wound Threshold (already applied above).

#### Feats
- **Arcane Awakening** *(Paradigm: Necromancy — Creation)*. Grimoire below.
- **Scholarly Resonance** *(Arcana 2 — Creation)*: While holding at least 1 point of Locked Stress, +1 SV against magical effects.
- **Euclidean Nightmare** *(Wits +2, Arcana +2 — Milestone 6)*: On a successful Arcana spell, spend 1 Momentum to leave a residual glyph in an adjacent square; any enemy that enters or starts its turn there takes 1 Dissonant Stress.

#### Equipment
- **Armour:** Leather (+1 Armour, Light — no Arcana penalty)
- **Weapons (two 1H items):** Grimoire (Repository — granted by Arcane Awakening, outside the purse) + Dagger (Finesse — the natural-1 reroll applies, though with Melee 0 it is rescuing a +0; Sidearm/Concealable/Thrown are why she carries it)
- **Starting Purse: 80 sp** — Leather 12 + Dagger 5 = **17 sp spent, 63 sp remaining** at creation. 5 sp on a surgeon's tool roll (feeds Medicine), 3 sp on grave-wax candles and ritual chalk, 55 sp in reserve. The Cloak below was bought much later, out of earnings.
- **Loot acquired in play:** **Cloak of Still Water** (35 sp, Rare — bought during Downtime after Milestone 5) — Advantage on Stealth checks while moving at half Move or slower. Bought for exactly the reason you'd expect: robbing graves quietly takes patience, not speed.

#### Grimoire (Arcana = **2d6+4**)
- **Marrow Siphon** *(Necromancy, Novice, Attrition — Creation)* — Unopposed vs. TN 8, Activation, **one freshly dead corpse at Short Range** (died this Scene; never a living creature), Instantaneous. **A successful cast spends the corpse.** Fail (<8): 1 Dissonant Stress to her, corpse untouched. Margin 0–2: clears 2 Dissonant Stress but feeds 1 back — a net gain of one slot. Margin 3–4 (Clean, or Mastery-upgraded from 0–2): clears 2 cleanly at no cost, corpse reduced to ash. Margin 5+: as Clean, and she generates 1 Momentum.
- **Rigor Mortis** *(Necromancy, Novice, Clash-resolution — Creation)* — Arcane Clash vs. Target's Resolve, Short Range, Aggressor. Margin 1–2: target's speed halved, no Dodge next turn; she takes 1 Dissonant Stress. Margin 3+ (Clean, or Mastery-upgraded): target fully Anchored, −2 to their next Aggressor Strike.
- **Calcify Armour** *(Necromancy, Novice, Utility/Buff — Creation)* — Unopposed vs. TN 8, self or one ally, touch, until the end of the encounter. Margin 0–2: target gains +1 SV, but takes 1 Dissonant Stress from the agonizing process. Margin 3–4 (Clean, or Mastery-upgraded): forms flawlessly, +1 SV, no cost. Margin 5+: enemies who fail a Block/Parry against the target suffer Impact 4 from the jagged bone.
- **Arcane Protection** *(Common, Novice, Sustain — Creation)* — Not Mastery-eligible (Common list). Unopposed vs. TN 8, **Activation to raise only; never castable as a Reactor**, **self only**, Sustain (no Locked Stress; re-roll vs. TN 8 each Activation and on taking a Wound). Margin 0–2: holds, 1 Dissonant Stress. Margin 3–4: holds, hostile spells targeting her suffer Disadvantage. Margin 5+: as Clean, ward gains SV 2 against the next hostile spell. Special: while it stands she may use **Arcana as her defense** against an incoming hostile spell in place of her normal Reactor stat, at every band including Messy — and *spell* being generic, that covers hostile **Prayers**.
- **Corpse Bloom** *(Necromancy, Adept — Milestone 3)* — Unopposed vs. TN 10, one corpse in sight, 10ft radius, Spell Power 3. Everyone in the radius (friend or foe) takes Impact = Margin + 3. Margin 0–2 (Mastery-upgraded to Clean): detonation is delayed/unpredictable rather than instant.
- **Zombie** *(Necromancy, Master — Milestone 5)* — Unopposed vs. TN 12, touch, requires a corpse within reach. Margin 0–2 (Mastery-upgraded to Clean): corpse rises as an NPC Undead under her control for the Scene (Wound Threshold 6, no Stress Limit). Margin 3–4: as above, no cost. Margin 5+: she may Lock 5 Stress to make the servant permanent instead of letting it end with the Scene.

#### Combat Math Quick-Ref
Arcane Manifestation/Clash 2d6+4 | Dagger Strike 2d6+0 | Dodge 2d6+0 (she has no defense to speak of — the whole build is "win before they close the distance") | Resolve 2d6+2 | Notice 2d6+2 | Activation Order 6

---

### Perpetua Vane — Human Female, Faith Caster (Mercy & Healing Domain)

*"Pain has to go somewhere. Better it comes to me than stays with you."*

#### Vital Statistics
- **Species:** Human
- **Standing:** Hardened (Milestone 8 — 24 DP earned via Advancement, 2 banked)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 1 | Reflex 0 | Wits 1 | Will 3 *(raised from 2 through Advancement)*
- **Skills:** Faith 4 | Medicine 2 | Resolve 2 | Influence 2 | Melee 1 | Notice 2 *(13 ranks. Ceilings: Faith/Resolve/Influence 6 (Will 3); Medicine/Notice 4 (Wits 1); Melee 4 (Brawn 1))*
- **Wound Threshold:** 7 *(4 base + 1 Brawn + 2 Chain Shirt + 0 Species)*
- **Stress Limit:** 9 *(4 base + 1 Wits + 3 Will + 1 Indomitable Spirit)*
- **Wound Slots:** 3 | **Momentum Bank:** 3 *(4 + Reflex 0, −1 Steady, Not Sharp)* | **Activation Order:** 6 *(6 + Reflex 0)*
- **Inventory Slots:** 9 *(8 + 1 Brawn)*

#### Species Traits (Human)
- **Adaptable:** +1 Skill **DP** at creation (already applied — a Human's creation Skill budget is 9, not 8).
- **Indomitable Spirit:** +1 Stress Limit (already applied above).
- **Steady, Not Sharp (Drawback):** −1 to your Momentum Bank cap.

#### Feats
- **Divine Conduit** *(The Covenant, Domain of Mercy & Healing — Creation)*. Grants a Holy Symbol, the **Pure Martyrdom** Domain Tag (casting Healing/Stabilize: take 1 Locked Stress herself to clear an additional Wound Slot on the target), and the 4 Novice Prayers below.
- **Dung-Healer's Salve** *(Medicine +1 — Creation)*: A Breather can't normally heal Wounds — this is the exception. Mundane foraged supplies let a Medicine check heal a Wound Slot during a Breather anyway; the patient takes 1 Locked Stress from the crude treatment.
- **Gallows Humour** *(Influence +1 or Resolve +1 — Milestone 6)*: Recounting a harrowing story during a Breather lets her and every ally participating each clear 1 point of **clearable** Locked Stress — never the Attunement kind (Iron Core, Golden Rules).

#### Equipment
- **Armour:** Chain Shirt (+2 Armour, Light)
- **Weapon (one 1H item):** Mace (Power 2, Bash) — the off-hand stays free for her Holy Symbol and battlefield triage rather than a shield.
- **Holy Symbol** (granted by Divine Conduit — outside the purse)
- **Starting Purse: 80 sp** — Chain Shirt 50 + Mace 8 = **58 sp spent, 22 sp remaining.** 6 sp on bandages and a suture kit, 2 sp on clean spirits for wound-cleaning, 14 sp in reserve. Skipping the shield to keep her off-hand free is what paid for the better armour — a medic who cannot reach the patient is no medic, so she bought the survivability instead of the shield.

#### Prayers (Tithe of Will = Faith = **2d6+4**, vs. tiered TN)
- **Healing/Stabilize** *(Common, Novice — Creation)* — Tithe vs. TN 8, 2 Locked Stress. Pass: clears 1 Wound Slot; if the target is Incapacitated, also Stabilizes them. A character can't benefit from a second Healing-type Prayer in the same Scene.
- **Elara's Comfort** *(Domain, Novice — Creation)* — Tithe vs. TN 8, 1 Locked Stress. Pass: target clears 2 Dissonant Stress.
- **Bolster the Faithful** *(Domain, Novice — Creation)* — Tithe vs. TN 8, 1 Locked Stress. Pass: target gains Blessed.
- **Elara's Vigil** *(Domain, Novice — Creation)* — Tithe vs. TN 8, 1 Locked Stress, touch, requires uninterrupted downtime. Pass: halves the target's next natural Wound-Slot recovery time, or auto-succeeds a downtime Medicine check made on her behalf.
- **Wrathful Light** *(Domain, Novice — Milestone 4)* — Tithe vs. TN 8, 2 Locked Stress. Pass: target must pass Resolve (TN 8) or take 2 Dissonant Stress; Undead/Daemon/Mutant targets also gain Fear. Her one offensive option.
- **Elara's Burden** *(Domain, Adept — Milestone 3)* — Tithe vs. TN 10, 2 Locked Stress. Pass: transfers 1 Wound from an ally directly onto her.
- **The Weeping Communion** *(Domain, Adept — Milestone 5)* — Tithe vs. TN 10, 2 Locked Stress. Pass: every ally within 15ft gains Blessed for the Scene.
- **Bless** *(Common, Novice — Milestone 8)* — Tithe vs. TN 8, 1 Locked Stress. Pass: target gains +1 to their next Clash roll within a minute.

#### Combat Math Quick-Ref
Tithe of Will 2d6+4 *(2d6+3 at creation)* | Mace Strike 2d6+1, Impact = Margin+2 | Block 2d6+0 | Dodge 2d6+0 | Resolve 2d6+2 | Medicine 2d6+2 | Notice 2d6+2 | Activation Order 6

---

## Storied

### Faelan Rook — Half-Elf Male, Arcana Caster (Shadow Sorcery)

*"Everyone assumes the smiling half-breed is the safe one to talk to. That's rather the point."*

#### Vital Statistics
- **Species:** Half-Elf (Split Heritage: took Fey Reflexes, and its paired Hollow-Boned drawback)
- **Standing:** Storied (Milestone 10 — 30 DP earned via Advancement, 0 banked)
- **Size:** Standard | **Move:** 30 ft / 6 squares
- **Attributes:** Brawn 0 | Reflex 2 | Wits 3 | Will 0
- **Skills:** Arcana 6 | Stealth 1 | Acrobatics 1 | Notice 1 | Insight 1 | Thievery 1 *(11 ranks — 8 from Creation, 3 from Advancement. Ceilings: Arcana/Notice/Insight 6 (Wits 3) — Arcana is now at its hard ceiling; Stealth/Acrobatics/Thievery 5 (Reflex 2))*
- **Wound Threshold:** 4 *(4 base + 0 Brawn + 1 Leather − 1 Hollow-Boned)*
- **Stress Limit:** 7 *(4 base + 3 Wits + 0 Will)*
- **Wound Slots:** 3 | **Momentum Bank:** 6 *(4 + Reflex 2)* | **Activation Order:** 8 *(6 + Reflex 2)*
- **Inventory Slots:** 8 *(8 + 0 Brawn)*

#### Species Traits (Half-Elf)
- **Silver-Tongued:** Advantage on Influence checks to persuade, de-escalate, negotiate, or gather information.
- **Fey Reflexes** *(chosen Split Heritage trait)*: Advantage on Acrobatics checks vs. hazards, traps, AoE.
- **Between Worlds (Drawback):** Disadvantage on Influence in insular/xenophobic communities.
- **Hollow-Boned (Drawback, comes with Fey Reflexes):** −1 Wound Threshold (already applied above).

#### Feats
- **Arcane Awakening** *(Paradigm: Shadow Sorcery — Creation)*. Grimoire below.
- **Whispers in the Dark** *(Stealth +1, Notice +1 — Creation)*: While successfully hidden, Advantage on Notice checks to eavesdrop, read lips, or observe details without breaking cover.
- **Euclidean Nightmare** *(Arcanist, Tier 2; Wits 2, Arcana 2 — Milestone 1)*: after successfully casting an Arcana spell, may spend 1 Momentum to leave a residual, jagged glyph in an adjacent square. Any enemy that enters or starts its turn in that square takes 1 Dissonant Stress from the impossible angles.

#### Equipment
- **Armour:** Leather (+1 Armour, Light — no Arcana penalty)
- **Weapons (two 1H items):** Grimoire (Repository — granted by Arcane Awakening, outside the purse) + Dagger (Finesse)
- **Starting Purse: 80 sp** — Leather 12 + Dagger 5 = **17 sp spent, 63 sp remaining.** 5 sp on a signet ring, 2 sp on ink/paper/sealing wax, 16 sp on 2 Grave-Dust Poultices, 40 sp banked. *(No Downtime purchases assumed across the ten Milestones — every DP went into the Grimoire and the archetype, not the kit.)*

#### Grimoire (Arcana = **2d6+6**)
- **Deflection** *(Paradigm, Mastery-eligible)* — **Reactor only; never raised in advance.** Arcane Clash (Arcana) opposed against the incoming attack, **self only**, **Scene** duration — it stands until the next Breather or a lost Clash, and is **not** a Sustain effect, so it needs no maintenance roll and doesn't occupy the Channelling slot. Margin 0–2 *(a tie counts here)*: attack deflected, 1 Dissonant Stress. Margin 3–4: deflected at no cost, and attacks against him take −2 while it stands. Margin 5+: as Clean, but the penalty is full Disadvantage. **Lose the Clash and the attack lands for full Impact with no mitigation — no Shield Value, no armour — and the ward falls.**
- **Stitch the Silhouette** *(Paradigm, Clash-resolution, Mastery-eligible)* — Arcane Clash vs. Prowess, Short Range, Aggressor. Margin 1–2: target Anchored until they tear free (1 Dissonant Stress to themselves doing so); costs Faelan 1 Dissonant Stress. Margin 3+ (Clean, or Mastery-upgraded from 1–2): as above, and target also loses Dodge as an option until free — no cost.
- **Flicker-Step** *(Paradigm, Mastery-eligible)* — Unopposed vs. TN 8, Self, 30ft teleport, ignores Threat Zones entirely. Margin 0–2: teleports, but arrives gasping — 1 Dissonant Stress. Margin 3–4: silent and flawless. Margin 5+: also generates 1 Momentum or grants Advantage on his next Strike.
- **Havoc** *(Common, not Mastery-eligible)* — Arcane Clash vs. each target's Prowess + Athletics/Acrobatics, 10ft radius, Short Range, Aggressor. Margin 1–2: target pushed 5ft and takes 1 Dissonant Stress; he also takes 1 Dissonant Stress from the strain. Margin 3+ (Clean): target pushed 10ft, knocked Prone, and takes 1 Dissonant Stress. *(Picked at creation over Illusion specifically to give him a genuine offensive option — the rest of his kit is control and escape.)*
- **Disguise** *(Paradigm, Adept, Mastery-eligible — Milestone 2)* — Unopposed vs. TN 10, Self, Scene; anyone suspicious rolls Notice vs. his Margin to see through it. Margin 0–4 (Mastery resolves any success Clean): holds, no cost. Margin 5+ (Massive): the veil extends to up to 3 allies within Short Range.
- **Invisibility** *(Paradigm, Adept, Mastery-eligible — Milestone 3)* — Unopposed vs. TN 10, self or one ally, touch, Scene or until broken. Margin 0–4 (Mastery: Clean): target is invisible — attackers suffer Disadvantage targeting them, target gains Advantage on Stealth; drops the instant they attack or cast. No cost. Margin 5+ (Massive): remains invisible even after attacking — attacking only reveals general position, removing attackers' Disadvantage for 1 round instead of dropping the spell.
- **Creeping Dusk** *(Paradigm, Adept, Mastery-eligible — Milestone 4)* — Unopposed vs. TN 10, 15ft radius, Short Range, Scene. Margin 0–4 (Mastery: Clean): the zone forms perfectly — magical darkness breaks line of sight, ranged attacks can't cross it, attacking an unseen enemy inside costs the attacker -2 Clash. Margin 5+ (Massive): the shadows turn hostile — any enemy starting its turn inside must pass a TN 8 Resolve check or take 1 Dissonant Stress.
- **Blade of Paranoia** *(Paradigm, Adept, Mastery-eligible — Milestone 5)* — Arcane Clash vs. Target's Wits or Resolve, Short Range, Aggressor. Bypasses Shield Value and armour entirely — attacks the Stress track directly, zero physical Impact. Resolves Clean at any success via Mastery: target suffers 2 Dissonant Stress, and that creature must discard 1 Momentum from its own Bank if it has any. No cost to Faelan.
- **Umbral Execution** *(Paradigm, Master capstone of Blade of Paranoia, Mastery-eligible — Milestone 7)* — Arcane Clash vs. Target's Wits or Resolve, Short Range, Aggressor. Requires the target to currently be unable to see him — invisible, in darkness (magical or mundane), totally concealed, or successfully Stealthed; pairs directly with Creeping Dusk and Invisibility above. Bypasses SV/armour entirely. Resolves Clean at any success via Mastery: target suffers 4 Dissonant Stress; if this brings them to or past Breaking, the shock is total and they're Incapacitated outright instead of the normal Break effects. No cost to Faelan.

#### Combat Math Quick-Ref
Arcane Clash/Manifestation 2d6+6 (incl. Havoc) | Dagger Strike 2d6+0 *(Melee 0; Finesse lets him reroll a natural 1)* | Dodge 2d6+1 | Notice 2d6+1 | Activation Order 8

---

