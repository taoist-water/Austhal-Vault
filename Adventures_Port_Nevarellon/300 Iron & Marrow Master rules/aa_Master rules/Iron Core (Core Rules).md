# Design concept
- A gritty, High fantasy realism role playing game.
- a brutal, psychologically driven fantasy RPG built around opposed rolls, Momentum, and the interaction between physical trauma and mental collapse
- Rolls are either opposed or against a static target number, with contextually applied modifiers.
- Unopposed rolls always resolve with a margin of success or scaler.
- rule system that is simple, yet detailed. When dealing with combat.
- trying to reduce cognitive load on the GM and Players.

#  The Golden Rules:
- Bonuses to Wound Threshold from magical sources (Spells, Auras, Enchanted Equipment) do not stack. A character only benefits from the highest single bonus. This does not apply to Shield Value.
- Bane effects (a flat reduction to a target's Wound Threshold against one specific Creature Type — see the Bestiary's Creature Types list) do not stack with each other against the same target; only the single highest Bane reduction applies. Bane reduces Wound Threshold before Impact is compared against it — this is a separate step from the Massive trait's Impact-halving, and the two apply independently rather than cancelling out.
- **Attunement Locked Stress is absolute.** Locked Stress committed to an item's Attunement (see Hardware: Enchantments) **cannot be cleared, unlocked, converted, transferred, reduced or otherwise removed by any means whatsoever while the item remains attuned** — not by the Reprieve, a Long Rest, a Breather, Religious Pursuit, any Downtime Pursuit or any number of nights, any alchemical preparation, any Feat, any spell or Prayer, and not by any future effect that clears Locked Stress. **Breaking passes it over** rather than converting it to Dissonant. There is exactly one release: the item is **deliberately unattuned**. An attuned item costs a permanent slice of the character's Stress track, and that permanence is the entire price of the item.
- Locked Stress paid for a Prayer that is currently **Flowing** cannot be targeted by the Reprieve or Religious Pursuit, and releases when the Prayer ends. Unlike Attunement it *is* reachable by alchemical override (Hardware, Alchemical Wares) — a Priest can force it open at a price, which is what those preparations are for. Locked Stress from a Prayer that has already resolved is clearable by the normal routes. Arcane **Sustain** commits no Locked Stress at all and is never subject to this rule.
- Situational Modifiers are applied at GM’s discretion, +2, -2, -4.
- Advantage and Disadvantage do not stack. If you have multiple sources of Disadvantage, you still only roll 1 extra die and drop the highest. If you have both Advantage and Disadvantage, they cancel each other out entirely.
- Wounds Threshold Bypassing effects cannot target creatures of Scale +3 or higher without a weapon carrying Devastating or Siege.

# Dice Mechanics

- The Check: 2d6 + Skill vs. TN (or Opposed).
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

## The Margin-Focused Resolution (Unopposed Checks)

Instead of artificially inflating the Target Number to combat high modifiers, we accept that highly skilled characters will succeed at standard tasks. The dice roll dictates the collateral damage, the speed, or the Momentum generated.

**TN 8 is the default.** Whenever a player makes an unopposed roll (like picking a lock, tending to a wound, or deciphering a grimoire), the Target Number is 8 unless something sets it higher or lower. Rules can and will override it: the GM may set TN 10 or 12 for a harder task (see *Tools for the Nameless*), and spellcasting sets its TN by the spell's Level (see *Embracing the Abyss*). When a rule names its own TN, use that number everywhere below; when it names none, use 8.

The Resolution Ladder You calculate the Margin (Total Result - TN) and apply the outcome:

- Failure (Total below the TN): The task fails outright. Time is wasted, and a consequence triggers (e.g., the lock picks snap, or you take 1 Dissonant Stress from frustration).
    
- Messy Success (Margin 0–2): You accomplish the task, but it costs you. You pick the lock, but it takes 10 minutes and your torch burns out. You forge the armour, but you must spend an extra 5 Silver Pieces on wasted materials.
    
- Clean Success (Margin 3–4): Flawless execution. You achieve the exact desired result with no complications.
    
- Massive Success (Margin 5+): You absolutely dominate the challenge. You achieve the result and generate 1 Momentum, or you gain a Prep Tag for an upcoming encounter.
_____________________________________________________________________

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

_____________________________________________________________________
## The "Snake Eyes" Rule (Natural 2)

When a player rolls a Natural 2 (two 1s) on a 2d6 check, the result is an Automatic Catastrophic Failure, regardless of their Attributes, Skills, or Gear modifiers. The total margin is irrelevant; the world intervenes in the worst possible way.

When this happens on an unopposed check, the GM immediately applies one of the following consequences based on the context of the action:

- Gear Degradation: The tool being used is pushed beyond its physical limit. If picking a lock, the picks snap off inside the mechanism, permanently jamming it. If using an Alchemist's Kit, the vials shatter. The item immediately gains the Damaged tag (or is Ruined if already Damaged).
    
- The Panic Reflex: The character realizes they have made a catastrophic error. They instantly suffer 1 point of Dissonant Stress, immediately ticking them closer to the Death Spiral.
    
- The Momentum Drain: The sheer embarrassment or shock of the failure kills the party's forward drive. The party instantly loses 1 banked Momentum. If they have no Momentum to lose, the active character takes 1 Dissonant Stress instead.
    
- Catastrophic Exposure: If the roll was related to Stealth or Scouting, the failure is loud and undeniable. The character is completely exposed, and all enemies in the upcoming encounter gain Advantage on their opening Activation order rolls.

**In an opposed Clash**, a Snake Eyes is an automatic loss of the Clash regardless of the actual total rolled, and the roller also suffers the Panic Reflex consequence (1 Dissonant Stress) on top of losing. This overrides any reroll effect that would normally apply to the roll (such as Finesse's natural-1 reroll) — a Snake Eyes can never be rerolled, by any means.

________________________________________________________________________
# The Momentum Economy

## The Momentum Bank

Momentum represents tactical flow, adrenaline, and sudden strokes of genius.
Each player maintains a personal bank capped at **4 + Reflex**.

- **Generation:** Players earn 1 Momentum by winning a Clash — an Attack Action, a Defense, evading a trap, or executing an ambush — **by a Margin of 5+**. A win alone isn't enough; it has to be decisive. See *Gaining Momentum* below for the full ladder, which this line summarises.
    
- **Spending (The Rule-Breakers):** Momentum is never spent to add a "+1" to a die. It is spent to break the rules. Players can spend Momentum to instantly clear debilitating conditions (like _Anchored_), construct improvised alchemical explosives mid-dungeon, rapidly patch _Damaged_ armour with spit and twine, or bend the narrative via flashbacks.

## Gaining Momentum

### 1. The Skill Pillar (The Margin of Success)

 If we want to keep the engine unified, Momentum generation should be directly tied to the Margin math we have built. It shouldn't be arbitrary; it should be the mechanical reward for overwhelming success.

-  Combat: Winning a Clash by a Margin of 5+ (Massive Success, 1 Momentum) 
    
- Magic: hitting that Margin of 5+ on an unopposed Arcana check generates Momentum because the caster executed the spell flawlessly.
    
- Exploration: Exceeding an unopposed Target Number (like TN 8 for picking a lock or scaling a wall) by a Margin of 5+ (1 Momentum).
    
### 2. The Engine Pillar (The Exploding Dice)

Because the 2d6 engine only explodes on a Natural 12, that moment is already mechanically rare and highly celebrated at the table.

-  The Trigger: Anytime a player rolls a Natural 12 (Double 6s) on any check—whether it is a Strike, a Parry, or a lore check—they instantly generate 2 Momentum, regardless of the final Margin. It mathematically reinforces that "perfect luck" fuels their adrenaline. This CAN compound with a Massive Success margin (5+) for 3 momentum off 1 roll.
    
### 3. The Sacrificial Pillar (The Desperate Push)

 In a gritty system like Iron & Marrow, players should have a way to generate Momentum when the dice are failing them, but it must come at a terrible physiological cost.

- The Trigger: A player can voluntarily take 1 or 2 Dissonant Stress to instantly generate 1 Momentum. This perfectly feeds into the Death Spiral. They are burning their own mental threshold to force a tactical advantage, pushing themselves closer to breaking just to survive the current round.
________________________________________________________________________
Momentum must become a currency of Rule-Breaking and Action Economy. Players spend Momentum to temporarily alter the laws of the game.

## Spending Momentum
### Cost 1 Momentum: Tactical Shifts

 These are cheap, immediate physiological or tactical reactions.

- Shake It Off (Condition Clearance): As a Free Reaction at the start of their turn, the player spends 1 Momentum to immediately clear a physical condition like Ablaze, Anchored, or Rigor without having to waste their entire turn taking the Regroup action.
    
    
-  The Blood Price (Triage/Stress Mitigation): When an enemy's Impact exceeds the player's Wound Threshold and is about to cause a physical Wound, the player can spend 1 Momentum to convert the physical trauma into mental trauma. They take 0 Wounds, but instantly take 2 Dissonant Stress instead.
    

### Cost 2 Momentum: Breaking the Engine

 These manipulate the action economy and the Bestiary tags directly.

- The Surge (Action Economy): After successfully winning an Attack Action, the player spends 2 Momentum to immediately take a second, completely free Attack action before the enemy can respond or the turn passes.
    
    
- Adrenaline Flush (Death Spiral Reversal): As a Free Reaction, the player spends 2 Momentum to instantly clear 1 Dissonant Stress. This is the only way to heal the mind mid-combat without casting a spell , finding a safe room for a Breather, or use alchemical resources.
    
    
### Cost 3 Momentum: The Ultimates

 These are massive, encounter-shifting expenditures that drain more than half of their maximum bank.

-  The Decisive Blow (Forcing the Threshold): The player wins an Attack Action, but the math reveals the Impact is lower than the Boss's massive Wound Threshold, meaning it would normally only cause 1 Stress. The player spends 3 Momentum to drive the blade through anyway. The attack automatically inflicts exactly 1 Wound Slot, bypassing the Threshold check entirely. *without equipment and preparation this could be the only way to wound Boss tier entities. Use it!*
    
-  Interrupt / Seize the Initiative: When the GM declares an enemy is about to activate, the player can spend 3 Momentum to literally pause time. The player instantly interrupts the enemy, and moves into the activation order before the enemy taking a full  turn before the enemy's activation. 


_______________________________________________________________________
# Stress vs. Wounds
## Stress
In _Iron & Marrow_, Stress is the primary mechanical representation of a character's mental fortitude, stamina, and panic. It serves as the crucial buffer before taking physical, lethal trauma (Wounds) and acts as the central pacing mechanic for combat, magic, and survival.

### The Stress Limit

A character's capacity to handle pressure before breaking is defined by their Stress Limit, which is calculated as **4 + Will + Wits + Feat Bonus + Species bonus.**

### The Two Categories of Stress

Stress is strictly divided into two types, which affect the character's capabilities in drastically different ways:

- **Dissonant Stress:** This represents immediate panic, physical pain, fumbles, or sudden exhaustion. It simulates a character losing their edge as they are battered and terrified. It can be cleared relatively quickly by spending Momentum, taking a The Breather, or using consumable items.
    
- **Locked Stress:** This represents sustained mental and physiological burdens: the cost a Priest pays to borrow authority, the weight of an Attuned item, an Arcanist's deliberate Overcharge, suffering through specific negative conditions, or enduring harsh environmental hazards. Crucially, Locked Stress ***does not*** apply the negative -1 penalty to your dice rolls. However, it fills up your Stress Limit and is much harder to clear, requiring a specific action like the Reprieve, a Long Rest, or specific Downtime Endeavours — **except the Locked Stress of an Attuned item, which none of those reach at all while the item is worn** (see the Golden Rules).

	*Note the division of currencies: an Arcanist's ordinary casting bleeds **Dissonant** Stress — botched manifestations, Messy margins, failed Sustain checks. Locked Stress is the Priest's bill, and reaches an Arcanist only through Overcharge, Attunement, conditions, and the environment.*
    

### The Death Spiral (The Stress Track)

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

# Wounds

In _Iron & Marrow_, **Wounds** are the brutal, mechanical representation of physical trauma and bodily failure. While Stress represents panic and exhaustion, Wounds are the broken bones, deep lacerations, and punctured organs that eventually pull a character into the grave.

Here is a breakdown of how Wounds function within the system:

## The Wound Slots

Unlike traditional hit point systems that feature inflated health pools, _Iron & Marrow_ uses a strict, low-capacity slot system to maintain high lethality.

- A standard character has exactly 3 Wound slots.
    
- Taking a 4th Wound means you are instantly Incapacitated.
    
- Unlike Dissonant Stress, Wounds do not apply direct stat or dice penalties. Instead, they act as a terrifying countdown to absolute bodily collapse.
    

### Calculating Wounds (Impact vs. Threshold)

To take a Wound, an enemy's attack must overcome your physical durability, represented by your **Wound Threshold (WT)** (calculated as 4 + Brawn + Armour Value + Species Bonuses + Scale bonus + Misc.mods). When a character loses a Clash, the resulting Impact dictates the severity of the Wound:

- **Minor Wound:** If the Impact equals or exceeds your Threshold, you take 1 Minor Wound (filling 1 slot).
    
- **Major Wound:** If the Impact equals or exceeds _twice_ your Threshold, you suffer massive trauma, taking 1 Major Wound (filling 2 slots) + 1 Dissonant Stress.
    
- **Overwhelming Trauma (Instant Incapacitation):** If the Impact equals or exceeds _three times_ your Threshold, the attack bypasses your Wound Slots entirely — it does not fill one, no matter how many you have available (including bonus slots from spells, feats, or magic items; nothing makes a character immune to a single catastrophic blow). Instead, you immediately gain the **Incapacitated** condition exactly as if you'd taken a Wound with no slot to fill it: fall Prone, drop what you're holding, and begin Bleed-Out checks per *At Death's Door*. Also inflicts 2 Dissonant Stress.
    

### Incidental Damage — choosing the right currency

Not every effect that hurts someone is a Strike. A zone's thorns, an item's spikes, a spell's backlash and a Boss's signature blow all need a way to say *this hurts*, and they must not all reach for the same one. **Impact is only the right answer when a number is going to be compared against a Wound Threshold.** Below that comparison it does nothing at all: **the lowest Wound Threshold in the game is 3**, so an effect dealing a flat 1 or 2 Impact can never fill a Wound Slot on anything, and resolves as 1 Dissonant Stress every single time it fires. Writing *"1 Impact"* is a long way of writing *"1 Dissonant Stress"* — and *"ignoring Armour"* attached to such a value is decorative, because Armour is not what stops it. The base 4 is.

**Four rungs. Pick one; do not invent a fifth.**

| Rung | Use it for | Write |
|---|---|---|
| **1. Incidental** | always-on gear, zone ticks, backlash the caster pays, the price a target pays to escape | **1 Dissonant Stress** |
| **2. Condition** | anything that sets an existing condition | **the condition's name and nothing else** — *"the target is Ablaze"* |
| **3. Gated payload** | a once-per-Scene item, or a Margin 5+ rider that has bought the right to matter | **a real Impact value — 4** |
| **4. Signature** | named Boss abilities, Master-tier magic, Snake Eyes tolls, Relic-tier items, environmental extremes | **1 Direct Wound** (GM Tools, *The Lethal Bypass*) |

**Rung 2 never restates the number.** A condition carries its own cost in its own entry — *Ablaze* is 2 Dissonant Stress a turn, see *The Conditions System* below — and an effect that names a number alongside the condition is a contradiction waiting to happen.

**Rung 3 is 4 because 4 is the base Wound Threshold**, so the rule states itself: **a flat Impact 4 Wounds anything with no Brawn and no armour, and Stresses everything else.** Across the Bestiary that is 8 creatures in 29 — the Fodder tier and the unarmoured Elite specialists, the shamans and assassins and marksmen — while everything carrying muscle or metal takes 1 Stress and walks on. It also gives *"ignoring Armour"* a real job at last: measured against `4 + Brawn`, a flat 4 that ignores Armour Wounds any Brawn 0 creature however heavily plated it is.

**Rung 4 is expensive and must stay that way.** *The Decisive Blow* (see *Spending Momentum*, above) prices a threshold bypass at **3 Momentum**. Nothing purchasable below Legendary should hand one out for free.

**`+N Impact` as a rider on a real attack is not on this ladder, and is always fine** — it modifies an Impact that is already being calculated, and it works.

### The Death Spiral (Stress Conversion)

Weapons are not the only things that cause Wounds. Wounds are inextricably linked to a character's mental state.

- If a character's Stress Limit is maxed out, any further Stress they take instantly converts into physical Wounds. This means a character can suffer lethal trauma simply from the systemic shock of freezing temperatures, absolute exhaustion, or the mystical blowback of channelling too much raw Arcane energy.
- **The one exception — `non-Lethal` sources.** Stress from a **`non-Lethal`** weapon or effect never converts. Against a full Stress track it is not applied at all: no Wound, no further Stress. The target gains the **Unconscious** condition instead. This is the whole point of a sap, a cudgel-butt or a chokehold — it is how you take someone alive, and it is the only way a full Stress track resolves without blood.

### Structural Damage and Destruction

Doors, walls, ropes, ships and the sword in an enemy's hand all break under the same maths as a body. **An object has a Wound Threshold and Wound Slots, and Impact is compared to them exactly as it is for a creature.** There is no separate subsystem to learn.

**Objects are Wounds only.** They have no Stress track, no Momentum Bank, and no Activation. Nothing about panic applies to a crate.

**Resolving the attack.**

- **An unattended object does not defend.** Roll the relevant Skill — Melee for a swing, Ranged for a shot, Athletics for a shoulder against a door — as an **unopposed check vs TN 8**, and read Impact off the standard unopposed formula: **Margin over the TN, plus Weapon Power**.
- **A held or worn object defends with its owner.** Striking the blade out of someone's hand, or splitting the shield they are hiding behind, is an **opposed Clash against the wielder**, resolved normally. You are fighting the person, not the object.

**Structural Damage Reduction (SDR).** Fortification-grade material — worked stone, iron plate, packed earthwork — carries a flat **SDR**, subtracted from incoming Impact before it is compared to the Wound Threshold. This is the *structural damage reduction* the **Estoc** already names, and it is the object equivalent of the **Plated** trait's flat reduction. Ordinary objects have none.

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
________________________________________________________________________
# At Deaths Door

When a character takes a Wound and cannot fill a wound slot, they immediately fall Prone, drop their weapons, and gain the **Incapacitated** condition.

**1. The Activation Order (Bottom of the Barrel)** An Incapacitated character's Activation Order is ignored — it is a static value (6 + Reflex, per Metal meet Flesh), not a roll, and nothing about being Incapacitated changes it. They automatically act at the absolute bottom of the turn order. If multiple characters are Incapacitated, they act simultaneously at the end of the round.

**2. The Bleed-Out Check** When the character's activation comes up, they can take no Actions or Free Actions. Instead, they must make a desperate roll to cling to life.

- **The Check:** Roll 2d6 + Brawn (or Will, relying on sheer stubbornness) against TN 8.
    - *Design note — a deliberate exception.* This is the one roll in the game that adds an Attribute rather than a Skill. Attributes are derived-only everywhere else, and that rule stands; the Bleed-Out Check is carved out on purpose. Clinging to life isn't a trained competency — there is no skill for refusing to die — so it runs off raw constitution or raw stubbornness. The Attribute cap of 3 also keeps the death save on a tighter band than a Skill's +6 would, which is the intent: nobody becomes reliably hard to kill. Do not "fix" this to Prowess/Resolve in a consistency pass.
    
- **Success (Margin 0-4):** You secure a **Stabilization Mark**.
    
- **Massive Success (Margin 5+):** Your body forcefully halts the trauma. You instantly gain 3 Stabilization Marks and are Stabilized.
    
- **Failure:** You secure a **Death Mark**. You are bleeding out or slipping into shock.
    
- **Fumble (Two natural 1s):** The trauma is too severe. You instantly die.
    

**3. The Outcomes**

- **3 Stabilization Marks:** You are **Stabilized**. You remain Unconscious and Incapacitated, but you no longer have to make Bleed-Out checks. You will survive the combat unless struck again.
    
- **3 Death Marks:** Your character dies.
    
## External Interventions & Threats

Because the player is stuck at the bottom of the turn order, the rest of the party has a desperate window to save them.

- **Triage (The Save):** An ally can use an Action to perform a _Medicine_ check (TN 8), use an Alchemical Poultice, or cast  _Stabilize_. If successful, the Incapacitated character instantly becomes Stabilized, stopping the Death Marks.
    
- **The Coup de Grâce (The Threat):** If an Incapacitated character is hit by a melee attack action they do not calculate Impact. They immediately suffer 1 automatic Death Mark. If the attacker uses the uses their whole activation, the character is instantly killed.
_______________________________________________________________________

### The Breather (Universal Action)

 The party barricades a room, binds their bleeding, and tries to calm their racing hearts. It is a desperate pause, not a comfortable rest.

- Time Requirement: 30 uninterrupted in-game minutes.
    
-  The Cost: Every participating player immediately empties their Momentum Bank to 0. The adrenaline fades.
    
- The Effect: All accumulated Dissonant Stress is completely wiped away. The Death Spiral is reset, and players lose their negative dice modifiers.
    
- The Limitation: A Breather cannot heal physical Wounds, and it cannot clear Locked Stress.
- At The conclusion of a Breather the party rolls their Community Supply Die (if they have one), if a 1 or 2 is rolled, the die reduces one category. on a 3+ all is ok. 

# Long Rest

A period of secure, undisturbed rest — a night at an inn, a fortified wilderness campsite, anywhere the GM narrates as safe — lasting at least 8 hours, during which a character does nothing more strenuous than eating, drinking, and uninterrupted sleeping. A Long Rest is separate from a Downtime period (see *Soothing the Soul*, Section 1): it needs no PP Budget or Settlement Tier, and can happen mid-adventure between combats, not just in town.

- **Effect:** Clears all accumulated Dissonant Stress, and 1 point of Locked Stress. No check is required.
- **Limitation:** A Long Rest cannot touch **Attunement** Locked Stress — nothing can, while the item is worn (see the Golden Rules). Among the routes that reach *clearable* Locked Stress this is the only one that is free, automatic and available to everyone regardless of Faith; the alchemical preparations in Hardware also reach it, at a cost. It's deliberately modest (Religious Pursuit's own guaranteed floor is Will score, minimum 1, and scales upward), so a Long Rest never outperforms a successful Tithe of Will, only guarantees a small amount to everyone regardless of Faith.
- **Supplies:** At the conclusion of a Long Rest, the party rolls their Community Supply Die exactly once (per Hardware) — the same single roll as a Breather, covering the whole night's consumption rather than scaling with its extra length. If the Die is Depleted, this Long Rest's Stress-clearing effect doesn't happen at all: no clean bandages, no hot food, no real rest either.

________________________________________________________________________
# The Conditions System
## Negative Conditions:


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
    

## Positive Conditions:

- *Blessed:* (Granted by Faith magic or holy sites). You feel the weight of the divine. You ignore the first point of Stress you would take in a scene.
    
- *Consecrated:* (dev note) Undead creatures suffer disadvantage when interacting with you.(/dev note)
    
- *Inspired:* gain advantage on non-combat checks for a scene.