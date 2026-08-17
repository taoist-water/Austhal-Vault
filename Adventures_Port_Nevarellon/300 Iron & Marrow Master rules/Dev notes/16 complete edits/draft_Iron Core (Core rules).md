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
- Locked Stress committed to a Sustained spell/Miracle, or to an item's Attunement (see Hardware: Enchantments), cannot be targeted by Grounding, the Reprieve, or Religious Pursuit. It only releases when the effect is voluntarily ended, the Miracle drops, or the item is deliberately unattuned.
- Situational Modifiers are applied at GM’s discretion, +2, -2, -4.
- Advantage and Disadvantage do not stack. If you have multiple sources of Disadvantage, you still only roll 1 extra die and drop the highest. If you have both Advantage and Disadvantage, they cancel each other out entirely.
- Wounds Threshold Bypassing effects cannot target creatures of Scale +3 or higher without a weapon carrying Heavy or Siege.

# Dice Mechanics

- The Check: 2d6 + Attribute + Skill vs. TN 8 (or Opposed).
	- When opposed in Combat, using a weapon is resolved as follows;
		- The Currently Active character chooses an Attack action, like strike or shoot.
		- roll 2d6 + Prowess/Reflex + melee/ranged
		- The target choose an Defensive action, like parry, and rolls 2d6 + Ability + Skill.
		- the Higher roll wins.
		- the difference between the winner and the loser is the Impact (when attacking).
		- Impact is compared to the losers Wound Threshold.
  	    
- **Fates Bounty (double 6s):** When a natural double 6 is rolled, the player (or Elite/boss NPC)  rolls an additional die and adds it to the total. This is only done once.
- **Snake Eyes (natural 2):** Automatic failure. The character immediately suffers 1 Stress, and additional contextual penalties.
- **Desperate Edge (a single natural 6):** When exactly one of the two dice in a 2d6 check shows a 6, the roller may treat that die as exploding: roll one additional d6 and add it to the total. Unlike Fates' Bounty (which triggers on *both* dice showing 6 and immediately grants an extra full die with no further conditions), Desperate Edge triggers on rolling a single 6 **only while the character is in a qualifying desperate state** — at half or more of their Stress Limit in Dissonant Stress, at their final Wound Slot, or under a specific feat/spell that explicitly lowers the threshold (such as *Embrace the Void*, which extends this to natural 5s as well). Outside a qualifying desperate state, a lone natural 6 is just a 6 — solid, unremarkable, no explosion.

- \[dev note\]Perfect Sequence (Universal Combat Rule): If a Prowess or Reflex check results specifically in a 3 and a 4 (creating a natural 7), the character achieves "Perfect Form". They may immediately perform a Free Shift (move 1 square) without triggering a Reactor action from the enemy. \[/dev note\]

## The Margin-Focused Resolution (Unopposed Checks)

Instead of artificially inflating the Target Number to combat high modifiers, we accept that highly skilled characters will succeed at standard tasks. The dice roll dictates the collateral damage, the speed, or the Momentum generated.

The Universal TN 8 Baseline Whenever a player makes an unopposed roll (like picking a lock, tending to a wound, or deciphering a grimoire), the Target Number is always 8.

The Resolution Ladder You calculate the Margin (Total Result - 8) and apply the outcome:

- Failure (Total 7 or less): The task fails outright. Time is wasted, and a consequence triggers (e.g., the lock picks snap, or you take 1 Dissonant Stress from frustration).
    
- Messy Success (Margin 0–2): You accomplish the task, but it costs you. You pick the lock, but it takes 10 minutes and your torch burns out. You forge the armor, but you must spend an extra 5 Silver Pieces on wasted materials.
    
- Clean Success (Margin 3–4): Flawless execution. You achieve the exact desired result with no complications.
    
- Exceptional Success (Margin 5+): You absolutely dominate the challenge. You achieve the result and generate 1 Momentum, or you gain a Prep Tag for an upcoming encounter.
_____________________________________________________________________

Passive Notice
Not every threat announces itself with a die roll. When a character isn't actively searching — walking down a corridor, mid-conversation, sprinting through a firefight — the world still needs a number to test their awareness against, without pausing the game for a check nobody declared.

The Formula: Passive Notice = 7 + Wits + Notice, modified by any applicable Situational Modifier (+2/-2/-4, per Tools for the Nameless).

The baseline of 7 (rather than a flat TN8) anchors Passive Notice to the statistical average of 2d6, keeping it consistent with the actual odds of an active roll. An unmodified character's Passive Notice sits just below TN8 — matching the fact that they'd fail an active TN8 check more often than not. Passive Notice should never make an untrained bystander more perceptive than a trained character actively rolling to look.

Advantage/Disadvantage Conversion: Because Passive Notice doesn't roll dice, sources of Advantage or Disadvantage on Notice checks (e.g. the Dwarf's Subterranean Senses, or the Whispers in the Dark feat) apply as a flat +2 or -2 to the Passive Notice score instead — consistent with the existing Situational Modifier scale (Advantageous = +2, Difficult = -2).

The Winded Penalty: Passive Notice stands in for a roll, not an exemption from one. It takes the standard -1 Winded penalty if the character's Dissonant Stress is at or above 50% of their Stress Limit, exactly as an active roll would.

Resolution Modes:

Opposed (detecting a person): Compare Passive Notice directly against the sneaking creature's Stealth roll (2d6 + Reflex + Stealth), or against a fixed Concealment Rating. This mirrors the existing Illusion/Disguise pattern of comparing a static value against a banked roll or Margin.
Unopposed (detecting a hazard or feature): Passive Notice + Situational Modifier vs. TN8 flat.
This mechanic resolves the Aware/Unaware fork in Iron World's Hazard Roll, the Bestiary's Ambusher trait, and the Cultist Assassin's Vanish ability — see those entries for specific application.

_____________________________________________________________________
## The "Snake Eyes" Rule (Natural 2)

When a player rolls a Natural 2 (two 1s) on a 2d6 check, the result is an Automatic Catastrophic Failure, regardless of their Attributes, Skills, or Gear modifiers. The total margin is irrelevant; the world intervenes in the worst possible way.

When this happens on an unopposed check, the GM immediately applies one of the following consequences based on the context of the action:

- Gear Degradation: The tool being used is pushed beyond its physical limit. If picking a lock, the picks snap off inside the mechanism, permanently jamming it. If using an Alchemist's Kit, the vials shatter. The item immediately gains the Damaged tag (or is Ruined if already Damaged).
    
- The Panic Reflex: The character realizes they have made a catastrophic error. They instantly suffer 1 point of Dissonant Stress, immediately ticking them closer to the Death Spiral.
    
- The Momentum Drain: The sheer embarrassment or shock of the failure kills the party's forward drive. The party instantly loses 1 banked Momentum. If they have no Momentum to lose, the active character takes 1 Dissonant Stress instead.
    
- Catastrophic Exposure: If the roll was related to Stealth or Scouting, the failure is loud and undeniable. The character is completely exposed, and all enemies in the upcoming encounter gain Advantage on their opening Activation order rolls.

________________________________________________________________________
# The Momentum Economy

## The Momentum Bank

Momentum represents tactical flow, adrenaline, and sudden strokes of genius. Each player maintains a personal bank capped at **5 Momentum**.

- **Generation:** Players earn 1 Momentum by winning an Attack Action, evading a trap, or executing an ambush.
    
- **Spending (The Rule-Breakers):** Momentum is never spent to add a "+1" to a die. It is spent to break the rules. Players can spend Momentum to instantly clear debilitating conditions (like _Anchored_), construct improvised alchemical explosives mid-dungeon, rapidly patch _Damaged_ armor with spit and twine, or bend the narrative via flashbacks.

## Gaining Momentum

### 1. The Skill Pillar (The Margin of Success)

 If we want to keep the engine unified, Momentum generation should be directly tied to the Margin math we have built. It shouldn't be arbitrary; it should be the mechanical reward for overwhelming success.

-  Combat: Winning a Clash by a Margin of 5+ (High Success, 1 Momentum) 
    
- Magic: hitting that Margin of 5+ on an unopposed Arcana check generates Momentum because the caster executed the spell flawlessly.
    
- Exploration: Exceeding an unopposed Target Number (like TN 8 for picking a lock or scaling a wall) by a Margin of 5+ (1 Momentum).
    
### 2. The Engine Pillar (The Exploding Dice)

Because the 2d6 engine only explodes on a Natural 12, that moment is already mechanically rare and highly celebrated at the table.

-  The Trigger: Anytime a player rolls a Natural 12 (Double 6s) on any check—whether it is a Strike, a Parry, or a lore check—they instantly generate 2 Momentum, regardless of the final Margin. It mathematically reinforces that "perfect luck" fuels their adrenaline. This CAN compound with a High success margin (5+) for 3 momentum off 1 roll.
    
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
    
- **Locked Stress:** This represents sustained mental and physiological burdens, such as the mathematical heat of casting spells, suffering through specific negative conditions, or enduring harsh environmental hazards. Crucially, Locked Stress ***does not*** apply the negative -1 penalty to your dice rolls. However, it fills up your Stress Limit and is much harder to clear, requiring specific actions like an Arcanist's Grounding maneuver, a full night's rest, or specific Downtime Endeavours.
    

### The Death Spiral (Dissonant Stress)

_Iron & Marrow_ is a game of psychological and physical attrition. Stress is the primary currency of exhaustion.

- #### The "Squeeze" Mechanic

Think of the character's Stress Limit as a track. Dissonant Stress fills the track from the left, and Locked Stress fills it from the right.

- **Dissonant Stress (The Panic Trigger):** This is the only type of Stress that triggers the mid-tier penalty.
    
    - _The 50% Tier (Winded):_ If a character's **Dissonant Stress** reaches half of their total Stress Limit, they suffer a flat `-1 penalty` to all rolls.
        
- **Locked Stress (The Capacity Drain):** This represents sustained exhaustion or the lingering heat of Arcana. It does not trigger the `-1 penalty`, but it "blacks out" available slots on the track, drastically reducing the character's buffer before they hit the absolute limit.
    
- **Total Capacity (The Breaking Point):**
    
    - _The 100% Tier (Breaking):_ When a character's **Total Stress (Dissonant + Locked)** reaches their maximum Limit their mental focus shatters, and all current Locked Stress immediately becomes Dissonant. They now suffer a flat `-2 penalty`, and any further Stress converts to Wounds.

- When the Stress Track is full and a Character would gain additional stress, it immediately converts to Wounds.

# Wounds

In _Iron & Marrow_, **Wounds** are the brutal, mechanical representation of physical trauma and bodily failure. While Stress represents panic and exhaustion, Wounds are the broken bones, deep lacerations, and punctured organs that eventually pull a character into the grave.

Here is a breakdown of how Wounds function within the system:

## The Wound Slots

Unlike traditional hit point systems that feature inflated health pools, _Iron & Marrow_ uses a strict, low-capacity slot system to maintain high lethality.

- A standard character has exactly 3 Wound slots.
    
- Taking a 4th Wound means you are instantly Incapacitated.
    
- Unlike Dissonant Stress, Wounds do not apply direct stat or dice penalties. Instead, they act as a terrifying countdown to absolute bodily collapse.
    

### Calculating Wounds (Impact vs. Threshold)

To take a Wound, an enemy's attack must overcome your physical durability, represented by your **Wound Threshold [T]** (calculated as 4 + Prowess + Armour Value + Species Bonuses + Scale bonus + Misc.mods). When a character loses a Clash, the resulting Impact dictates the severity of the Wound:

- **Minor Wound:** If the Impact equals or exceeds your Threshold, you take 1 Minor Wound (filling 1 slot).
    
- **Major Wound:** If the Impact equals or exceeds _twice_ your Threshold, you suffer massive trauma, taking 1 Major Wound (filling 2 slots).
    
- **Instant Incapacitation:** If the Impact equals or exceeds _three times_ your Threshold, you are instantly Incapacitated, risking a potential long-term injury or immediate death.
    

### The Death Spiral (Stress Conversion)

Weapons are not the only things that cause Wounds. Wounds are inextricably linked to a character's mental state.

- If a character's Stress Limit is maxed out, any further Stress they take instantly converts into physical Wounds. This means a character can suffer lethal trauma simply from the systemic shock of freezing temperatures, absolute exhaustion, or the mystical blowback of channelling too much raw Arcane energy.
________________________________________________________________________
# At Deaths Door

When a character takes a Wound and cannot fill a wound slot, they immediately fall Prone, drop their weapons, and gain the **Incapacitated** condition.

**1. The Activation Order (Bottom of the Barrel)** An Incapacitated character no longer rolls for Activation order at the start of a round. They automatically act at the absolute bottom of the turn order. If multiple characters are Incapacitated, they act simultaneously at the end of the round.

**2. The Bleed-Out Check** When the character's activation comes up, they can take no Actions or Free Actions. Instead, they must make a desperate roll to cling to life.

- **The Check:** Roll 2d6 + Prowess (or Will, relying on sheer stubbornness) against TN 8.
    
- **Success (Margin 0-4):** You secure a **Stabilization Mark**.
    
- **High Success (Margin 5+):** Your body forcefully halts the trauma. You instantly gain 3 Stabilization Marks and are Stabilized.
    
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

# Long Rest:

a period of downtime, lasting at least typically 8 hours, during which a character does nothing more strenuous than eating, drinking, uninterrupted sleeping. Depending on the Narrative the GM can allow 1 contextually relevant Pursuit.

________________________________________________________________________
# The Conditions System
## Negative Conditions:


- *Incapacitated:* Prone and Helpless, dying requiring Bleeding out checks.
    
    
-  *Prone:* You are on the ground. You suffer Disadvantage on all Clashes. It costs a Move Action or 1 Momentum to scramble to your feet.
    
- *Blinded:* (Dirt in the eyes, magical darkness). You cannot take attack actions against targets beyond 5 feet. All Reactor Clashes are made with Disadvantage.
    
- *Poisoned:* At the start of your turn, make a Prowess check. On a failure, you instantly take 1 Dissonant Stress. (If you max out your Stress while Poisoned, the toxin causes a Wound).
    
-  *Bleeding:* At the beginning of each of your activations can spend a Momentum to “stem the wound”, or make a Prowess check. Succeed Lose the Bleeding condition. Fail, lose a wound.
    
- *Fatigued:* Gain 1 Locked Stress. If a circumstance causes an additional instance of this condition, gain another locked Stress. If at the stress limit, no more locked stress can be assigned. This condition can only be cleared by a full night's rest or magical Restoration.
    
- *Terrified:* Your mind is clouded by panic. 1 stress is locked. You cannot spend Momentum for any reason. You must spend your turn running away from the object/being causing the Terror, fleeing until you can hide, or break the complete line of sight. When out of sight or hidden from the object/entity you can take a  Will + Resolve check to shake the condition.
    
- *Fear:* 1 stress is locked, until fear condition is lost. Has disadvantage against the object/being causing the Fear condition. must Pass a Will + Resolve check to make Attack actions or interact with the object/being causing the fear. cleared by taking the regroup action when out of sight or has cover from the object/enemy causing fear.
    
- *Distracted:* suffer a - 1 to rolls until next activation, then lose the condition.
    
- *Cursed:* (Magical). Healing magic (like Mend Flesh or Surge of Relief) has no effect on you, and Alchemical draughts taste like ash, providing no benefit.
    
- *In-Fighting:* All 1H weapons without Close-Quarters suffer Disadvantage. 2H weapons cannot be used.
    
- *Surprised:* Rolls suffer Disadvantage.
    
- *Grappled:*  can only take limited actions. Strike: does not break or control the grapple, unless the target becomes incapacitated, then participants loose the grappled condition. Grab: to take control of the Grapple, meaning to maintain grappling, or move the participants 5ft in a chosen direction. Shove: To break free of the Grapple. Cannot Block, Parry, Dodge. 
    
### 1. Anchored (The Movement Lock)

_The physical inability to reposition._

- **The Mechanic:** The character’s movement speed is reduced to 0.
    
- **The Engine Interaction:** Because their feet are pinned, an Anchored character completely loses the ability to use the **Dodge** action in a Clash. They must rely on **Block** (shield), **Parry** (weapon), or **Brace** (taking the hit).
    
- **Clearance:** Cleared when the effect ends, or by using the _Regroup_ action to physically tear free.
    

### 2. Rigor (The Articulation Lock)

_A severe stiffening of the joints, caused by nervous system shock, extreme cold, or necromancy._

- **The Mechanic:** The character's movement is halved.
    
- **The Engine Interaction:** Because they cannot fluidly articulate their wrists or shift their weight, a character suffering from Rigor completely loses the ability to use the **Parry** or **Dodge** actions. If attacked, they must use **Block** or **Brace**. Furthermore, any Attack action they attempt suffers **Disadvantage**.
    
- **Clearance:** Fades automatically at the end of their next turn as the blood flow normalizes.
    

### 3. Ablaze (The Attrition Tax)

_Active, ongoing environmental destruction to the character's physical body or gear._

- **The Mechanic:** At the absolute start of the character’s turn, before they can move or act, At the start of your turn, the agonizing heat causes you to suffer 2 Dissonant Stress before you can act.
    
- **The Engine Interaction:** It creates a brutal, ticking clock. A player cannot ignore it, or it will mathematically chew through their Stress Limit and push them into the Death Spiral without an enemy ever swinging a sword.
    
- **Clearance:** The character _must_ spend their turn taking the _Regroup_ action (stopping, dropping, and rolling) to extinguish the flames.
    

### 4. Drowned (The Rising Tide)

_The lungs burn, the light above the surface gets smaller, and the pressure keeps mounting._

- **The Mechanic:** The character suffers Disadvantage on all rolls. At the start of their turn, before they can move or act, they suffer 1 Dissonant Stress as their body burns through the last of its air.
    
- **The Engine Interaction:** Slower and quieter than Ablaze's clock, but just as inescapable if ignored — it doesn't force a specific reset action, it just keeps draining until the character gets clear of the water or breaks whatever's holding them under.
    
- **Clearance:** The character (or an adjacent ally spending an Action) may attempt a **Prowess + Athletics check (TN 8)** to reach the surface and clear the condition. Automatically cleared if the character is physically removed from the water.
    

### 5. Suppressed (The Discipline Tax)

_The relentless, disciplined pressure of coordinated fire makes anything but hunkering down feel like an invitation to disaster._

- **The Mechanic:** While Suppressed, if the character takes any action other than Attack, Block, Brace, or Regroup, that action is made with Disadvantage, and the character immediately suffers 1 Dissonant Stress from breaking cover under pressure.
    
- **The Engine Interaction:** Suppressed doesn't stop a character from doing something risky — it makes doing anything except holding their ground and fighting back cost real Stress. It pushes the target toward committing to the exchange rather than repositioning or using utility actions.
    
- **Clearance:** Fades automatically at the start of the Suppressed character's next turn if they're no longer in line of sight of the source. Otherwise cleared via the Regroup action.
    

### 6. Regroup (The Universal Reset Action)

_Regroup is not a condition; it is a universal **Action** available to all characters and enemies._

- **The Mechanic:** Instead of using their turn to declare a Strike, cast a spell, or reposition aggressively, the character spends their entire turn resetting their physical and mental state.
    
- **The Engine Interaction:** Taking the Regroup action allows a character to:
    
    1. Automatically clear physical conditions like _Ablaze_ or _Anchored_.
        
    2. Pick up a dropped weapon or shield.
        
    3. Spend Momentum mid-combat to clear a small amount of Dissonant Stress before they break (acting as a mini-Breather).
        
- **The Tactical Cost:** It costs the player their offensive output for the round, forcing the party to cover them while they recover.
## Positive Conditions:

- *Blessed:* (Granted by Faith magic or holy sites). You feel the weight of the divine. You ignore the first point of Stress you would take in a scene.
    
- *Consecrated:* (dev note) Undead creatures suffer disadvantage when interacting with you.(/dev note)
    
- *Inspired:* gain advantage on non-combat checks for a scene.
