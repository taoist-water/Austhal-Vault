# The Dynamic Trait Manifest
Design Philosophy: Keep stat blocks simplified. Let traits dictate tactical behaviour, stress interaction, and threat usage.

Enemies use the similar character generation rules as players, the difference is the skills are bought a a 1:1 ratio regardless of the parent attribute value. Once an enemy is generated populate their stat block using the same derived stats as players, only list the stats that are most important, such as WT and Stress limit. The stats that have no modifier to not get listed and are assumed to be zero. 

# Creature Types

Every stat block declares one or more Creature Types alongside its Tier. Type carries no inherent stat effect on its own — its entire job is to be a hook for other things to reference: Bane effects (Hardware: Enchantments), Domain Tags like Smite Corruption, spells like Ward of the Threshold, and any future resistance/vulnerability trait. A creature can carry more than one Type where the fiction demands it (a reanimated golem is both Undead and Construct; a hag-blooded cultist could be both Humanoid and Fey) — treat it the same way multiple Traits stack on one stat block.

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
- **Construct:** Artificial or animated bodies without a natural life cycle. Golems, animated armor, clockwork sentinels.
- **Mutant:** Flesh warped by alchemy, radiation, or forbidden transmutation into something no longer wholly natural.


####  Core Integration Rules

**Enemy Budget by Party Standing**

The budgets below used to be a single flat number per tier, calibrated against a Milestone-0 (Green) party and never revisited as PCs advance. That undersells every tier once a party has spent even a few Milestones — Ox, Morwenna, and Perpetua (Hardened, Milestone 6–9, see The Meat) each sit at 16–17 total Attribute+Skill points on their own, comfortably past the old Dread/Boss ceiling of 14, before the rest of the party is even counted.

Budgets now scale with the party's current Standing (see The Marrow, Character Creation — "Milestone Standing"). Find the party's Standing, then use that row for whichever tier is being built. "Typical PC total" is the same Attribute+Skill sum documented there.

| Party Standing | Typical PC total | Fodder | Grunt | Elite | Dread/Boss |
|---|---|---|---|---|---|
| Green | 12 | 1–2 | 3–4 | 11–14 | 15–20 |
| Blooded | 13 | 1–2 | 3–5 | 12–15 | 17–22 |
| Veteran | 14 | 2–3 | 4–5 | 15–18 | 19–25 |
| Hardened | 17 | 2–3 | 4–6 | 17–21 | 22–28 |
| Storied | 19+ | 3–4 | 5–7 | 20–24+ | 26–34+ |

The logic behind each column:
- **Fodder** barely moves — it's disposable chaff by design, and a Fodder mook that scaled with the party would stop being Fodder. The only growth is a token bump by Storied so a late-campaign mob scene doesn't look absurd next to everything else on the field.
- **Grunt** tracks the party's *current* Standing, at roughly 25–30% of their typical total — enough to force a Momentum spend from a single PC, credible in numbers, still meant to lose to focused attention.
- **Elite** is budgeted as roughly the party's *next* Standing tier up — a literal reading of the tier's own text, "a few advances ahead of the characters at all times." At Green, Elite is budgeted like a Blooded PC; at Hardened, like a Storied one. This is the largest change from the old flat number (5–8), because that number never actually matched its own "almost equivalent to the characters' capabilities" description — 5–8 against a 12-point Green party is only 42–67%. The new range makes that description true at Green and keeps it true as the party advances.
- **Dread/Boss** is budgeted roughly two Standing tiers ahead, with a wide, GM-discretion range. A solo Boss has to "rival a highly optimized player" while getting acted on 3–5 times for every one of its own actions, so its raw stat budget needs real headroom over Elite, not a marginal bump.

**Two existing examples, checked against the new numbers:**
- **Arch-Devil Malaphar** (Dread, below — Brawn +4/Will +3/Wits +2/Melee +4/Arcana +3/Resolve +3 = 19 points) previously *exceeded* even the old flat ceiling of 14 by 5 points, flagged separately as a likely pre-Standing-system inconsistency. It now sits cleanly inside the Green-party Dread range (15–20), and inside every later row too. No changes needed — the recalibration resolves it without any edits to the statblock itself.
- **Cultist Assassin** (Elite, below — Reflex +3/Wits +1/Melee +2/Dodge +1/Stealth +1 = 8 points) no longer clears the new floor at any Standing (Green Elite starts at 11). Unlike Malaphar, this one needs an actual rebuild, not just a note — its Traits and Threat Abilities were tuned around the old 5–8 budget, and inflating the raw numbers without revisiting those would likely leave it either redundant with Grunt or clumsily overtuned. Flagging rather than patching it here; it deserves its own pass.

- **Fodder:** 1 - 2 Traits. 1 Threat Abilities. 
	- vessel limit 1. 
	- Fodder cannot spend Threat unless led by a leader or a tag allows them too. 
	- 1 wound. 
	- 0 stress, breaking the core rule.
    
    - _Example (Zombie):_ Brawn +1. _(Strikes and grabs at +1, everything else is +0). Undead_
    
- **Grunt:** 1 - 2 Traits. 
	- 1 Threat Abilities. 
	- vessel limit 1. 
	- 2 wounds. 
	- stress as core rule defined.
    
    - _Example (Orc Line-Breaker):_ Brawn +2, Melee +2. _(Strikes at +4. Activation/Reflex is +0. Magic defense is +0)._
    
- **Elite:** 2 - 3 Traits. 
	- 1 - 2 Threat Abilities. 
	- vessel limit 2 - 3.  
	- 3 - 4 wounds. 
	- stress as core rule defined +1.
    
    - _Example (Cultist Assassin — flagged above, needs a rebuild to the new budget):_ Reflex +3, Wits +1 | Melee +2, Dodge +1, Stealth +1. _(Strikes at +2, Dodges at +4, Stealths at +4. Brawn/Prowess is +0)._
    
- **Dread Entities / Bosses (The Behemoths):** Attributes can exceed +3.
	- 2 - 4 Traits. 
	- 3+ Threat Abilities. 
	- vessel limit 2 - 4. 
	- 4+ wounds. 
	- stress as core rule defined + 2
    
    - _Example (Arch-Devil Malaphar):_ Brawn +4, Will +3, Wits +2 | Melee +4, Arcana +3, Resolve +3. _(Strikes at +8, casts at +5, resists mental magic at +6. Still has a +0 in Reflex).
    

________________________________________________________________________
# Traits
## DEFENSIVE & PHYSIOLOGICAL TRAITS

 - _Sinking Gravity:_ The ground immediately within the creatures Threat Zone is perpetually treated as Mire (Difficult Terrain), halving movement and imposing disadvantage to all mobility checks. 
        
- _Resilient:_ Increases the creature’s Stress Limit by +2. Can spend Threat to Mitigate damage, reducing incoming Impact by 2 per point spent (up to its Vessel limit).
        

**Plated** 
- Thick hide, rusted iron carapace, or heavy plate scales shield vital locations.
    
- Reduces all incoming standard Impact damage by a flat -1. 
    

**Skittering** 
- Unnatural speed, shifting limbs, or erratic reflexes make them slippery targets.
    
- This Creature may move out of Threat zone without  requiring a test, or causing a free strike.
    
**Massive**
- Massive: Weapons without Sunder, Brutal, or Armour-Piercing have their Impact halved before comparing to its Wounds threshold.
---

## OFFENSIVE & MARTIAL TRAITS

**Brute**
- Heavy, sweeping strikes designed to shatter shields and break bones.
    
- When this creature wins an attack action, it inflicts +1 Impact and forces the target back 1 square/5ft. If the target hits a wall or solid obstacle, they immediately take 1 Dissonant Stress from the concussive force.
    

**Vicious**
- Jagged fangs, rusted serrated daggers, or disease-ridden claws that leave lingering wounds.
    
- If this creature inflicts damage on a player character, the target must immediately make a Brawn check (A check using only their Brawn attribute). If they fail they gain the Bleeding condition. 
    
**Swarm:** 
- The Swarm gains a +1 bonus to their Clash roll for every additional swarm ally currently engaged with the same target.

    
**Amorphous**
- Single-target weapons (daggers, arrows, spears) can never inflict a Wound on the Swarm.

---

##  TACTICAL & PSYCHOLOGICAL TRAITS
**Fear Inducing**
- A frightening vision - whether a horrifying beast, or scene of heretical ritual.
-  When a PC engages with this creature or it activates within line of sight, the PC must immediately roll a Will + Resolve check against TN 8.    

- Failure: The PC immediately gains the *Fear*  condition.

**Terrifying**
- A harrowing presence—whether an eldritch abomination or a faceless, silent headsman—that cracks the human mind.
    
- When a PC engages with this creature or it activates within line of sight, the PC must immediately roll a Will + Resolve check against TN 8.    

- Failure: The PC immediately gains the *Terrified* condition.
    
_**Fanatical:** Immune to being Intimidated.
        
**Ambusher:**_ Gains Advantage on the Clash roll if attacking an unaware target from Stealth.

**Cunning Leader**
- A ruthless commander or pack alpha who reads the battlefield with chilling tactical precision.
    
- At the beginning of the Round, this creature can pass its own postion in the Activation order to any allied Fodder unit within its line of sight, allowing the minions to strike with unexpected coordination. Additionally, whenever an ally within its line of sight dies, the GM gains 1 Threat out of pure malice or tactical adaptation.
    

**Unstable Volatility**
- A creature bloated with volatile arcane radiation, alchemical compounds, or demonic instability.
    
- If this creature is struck by a Fates Bounty(meaning the attack roll against it was a Fates bounty), or if it rolls Snake Eyes (fumbles) on its own action, its containment ruptures. All characters (allies and enemies alike) within a 10ft radius must defend against an immediate burst of raw energy, taking 2 points of Locked Stress (if magical) or Dissonant Stress (if alchemical/fire).
    
___________________________________________________________________
# Example enemies

### The Goblin Scrapper (Fodder)

_Scrawny, twitchy, and desperate. They prefer to strike from the shadows and retreat the moment the tide of battle turns against them._

- **Wound Threshold:** 5 _(Base 4 + 1 Leather)_ | **Wound Slots:** 1 | **Stress Limit:** 0
    
- **Stats:** Reflex +2 | Melee +0. _(Assumed Zero: Everything else. They are incredibly difficult to hit/dodge, but if they get caught, they fold immediately)._
    
- **Traits (1):**
    
    - _Swarm:_ The Scrapper gains a +1 bonus to their Clash roll for every additional Goblin ally currently engaged with the same target.
        
- **Threat Abilities:** _Passive._ Fodder cannot spend Threat unless led by a leader.
	- Threat Cost 1: instead of a regular attack action, The scrappy, opportunistic goblins try to swipe supplies from the target. Sabotage: Target Must pass a TN8 Reflex test, Fail and reduce the community supply die by 1 order.
    
- **Vessel Limit:** 1
___________________________________________________________________________________________________________________________________________________________________________________
### The Corpse-Trench Rat Brood (Fodder)

_A writhing, starving mass that exists purely to drain Momentum and Wounds before the real threat arrives._

- **Wound Threshold:** 4 | **Wound Slots:** 1 | **Stress Limit:** 0
    
- **Stats:** Reflex +1 | Melee +1. _(Assumed Zero: Everything else. They are quick, but their total lack of Brawn or Wits makes them pathetic in a direct grapple or against mental effects)._
    
- **Traits (1):**
    
    - _Amorphous:_ Single-target weapons (daggers, spears, arrows) cannot inflict a Wound. Only Area of Effect (AOE) attacks or weapons with the _Heavy_ or _Siege_ tag can kill them.
    -  Swarm:  The Swarm gains a +1 bonus to their Clash roll for every additional swarm ally currently engaged with the same target.
        
- **Threat Abilities (1):**
    
    - **Passive - Hive Mind:** Fodder cannot spend Threat unless led by a leader. However, if three or more swarms are engaged with a single target, they automatically inflict 1 Dissonant Stress on the Target. represnting the rats crawling over armor and finding gaps).
        
- **Vessel Limit:** 1
  ________________________________________________________________________________________________________________________________________________________________________________________________________________
### Orc Line-Breaker (Grunt)

- **Budget Used:** 4 points.
    
- **Stats:** Brawn +2 | Melee +2. _(Assumed Zero: Reflex, Wits, Will. They hit hard and block well, but are terrible at dodging or resisting mind-altering Arcana).
- **Wound Threshold:** 6 | **Wound Slots:** 2 | **Stress Limit:** 4
    
- **Traits (1):**
    
    - _Plated_ : Reduces all incoming standard Impact damage by a flat -1. 
        
- **Threat (1) - Unstoppable Mass (Cost 1):** _Trigger:_ Declared on a successful Melee clash. _Effect:_ Taxes player Momentum or violently shoves them out of position.
    
- **Vessel Limit:** 1
    ___________________________
### Cultist Assassin (Elite)

- **Budget Used:** 8 points.
    
- **Stats:** Reflex +3, Wits +1 | Melee +2, Dodge +1, Stealth +1. _(Assumed Zero: Brawn, Prowess, Will. They are practically untouchable by standard strikes, but if forced into a Grapple, they roll 2d6 + 0).
- **Wound Threshold:** 4 | **Wound Slots:** 3 | **Stress Limit:** 6
    
- **Traits (2):**
    
    - _Fanatical:_ Immune to being Intimidated.
        
    - _Ambusher:_ Gains Advantage on the Clash roll if attacking an unaware target from Stealth.
        
- **Threat Abilities (2):**
    
    - **Cost 1 Threat - vanish** _Trigger:_when obsurced _Effect:_ The Assassin blends into the shadows, the assassin is effectively totally obscured, requiring a successful notice check to find.
        
    - **Cost 2 Threat - Throat Slit:** _Trigger:_ On a successful Melee clash with a Margin of 3+. _Effect:_ The target immediately suffers a Minor Wound, bypassing their normal Impact Threshold.
        
- **Vessel Limit:** 2
_______________________________

### The Bandit Captain (Elite)

_A serious threat that requires party synergy to defeat. He doesn’t fight fair; he commands the battlefield with a heavy halberd, barking orders from behind a wall of cutthroats._

- **Wound Threshold:** 9 _(Base 4 + 2 Brawn + 3 Breastplate)_ | **Wound Slots:** 3 | **Stress Limit:** 6 
    
- **Stats:** Brawn +2, Wits +1, Reflex +1 | Melee +2, Prowess +1, Resolve +1. _(Assumed Zero: Dodge, Will, Arcana. He is a hardened commander who braces against hits, but his heavy armor and cumbersome weapon make him terrible at dodging out of the way of AOE attacks or fast projectiles)._
    
- **Traits (2):**
    
    - _Cunning Leader:_
        
    - _Brute:_ 
        
- **Weapons:** * _Masterwork Halberd (Power 3+1 masterwork (4), Reach, Cumbersome)._ **Strike Roll:** `2d6 + 4` _(Brawn 2 + Melee 2)_.
    
- **Threat Abilities (2):**
    
    - **Cost 1 Threat - Call for Reinforcements:** _Trigger:_ Declared on the Captain's activation. _Effect:_ The Captain shouts for backup. One additional Fodder (Bandit) arrives at the edge of the battlefield next round, OR — if reinforcements aren't narratively available — all currently engaged Fodder immediately gain the benefit of the Flanking Bonus as if one more ally were present (representing the Captain directing the formation).
        
    - **Cost 1 Threat - Hook and Drag:** _Trigger:_ Declared after a successful Melee clash with his Halberd. _Effect:_ Instead of dealing normal Impact, the Captain hooks the player's legs. The target is immediately knocked Prone and dragged 5 feet directly into an adjacent Fodder's Threat Zone.
        
- **Vessel Limit:** 2
  

---

### The Frost-Cave Troll (Elite)

_A towering, territorial brute of dense muscle and thick frost-bitten hide. It swings a shattered pine tree with horrifying speed, its wounds knitting together almost as fast as they are opened._

- **Wound Threshold:** 9 (4 + Brawn 3 + Scale 2 ) | **Wound Slots:** 3 | **Stress Limit:** 4
    
- **Stats:** Brawn +3 | Melee +3, Prowess +1, Reflex +1. _(Assumed Zero: Dodge, Wits, Will, Arcana, Resolve. It acts surprisingly fast and hits like a siege weapon, but it is entirely defenseless against mind-altering magic or illusions)._
    
- **Traits (2):**
    
    - _Large (Scale +1):_
        
    - _Troll-Blood Regeneration:_ At the start of the Troll's activation, it automatically heals 1 Wound Slot and clears 1 Stress. _Weakness:_ If the Troll takes any Impact damage from a Fire source (such as a _Naphtha Fire-Flask_ or Pyromancy), this trait is entirely suppressed until the end of the next round.
        
- **Threat Abilities (2):**
    
    - **Cost 1 Threat - Vicious Frenzy:** _Trigger:_ Declared immediately after the Troll completes a Strike. _Effect:_ The Troll follows up its lumbering tree trunk attack with a sudden, tearing claw swipe. It makes an immediate, secondary Strike at an adjacent target (Treat the claws as Power 1, Vicious).
        
    - **Cost 2 Threat - Sweeping Uproot:** _Trigger:_ Declared before the Troll makes a Strike with its Tree Trunk (Power 3, Reach, Brutal). _Effect:_ The Troll drags its massive club through the earth. This Strike gains the _Cleave_ tag, forcing every player in its frontal arc to defend against the same Strike roll. Furthermore, any player who loses the Clash is knocked Prone.
        
- **Vessel Limit:** 2
___________________________________________________________________
### The Rotting Fen-Goliath (Elite)

_A towering, decapitated mass of waterlogged flesh, rusted iron chains, and tangled mangrove roots. It does not feel pain; it only seeks to pull living warmth down into the freezing mud._

- **Wound Threshold:** 11 (4 + Brawn 3 + Scale 4 )| **Wound Slots:** 4(3 base + 1 Scale), Huge scale (+2)|**Stress Limit** 4.
    
- **Stats:** Brawn +3 | Melee +3, Prowess +2. _(Assumed Zero: Reflex, Dodge, Wits, Will, Arcana. A lumbering behemoth. It swings at a +6 and braces against physical blows at a +5, but is completely defenseless against Agility or Mind-targeting magic)._
    
- **Traits (2):**
    
    - _Sinking Gravity:_ The ground immediately within the Goliath’s Threat Zone is perpetually treated as Mire (Difficult Terrain), halving movement and imposing disadvantage to all mobility checks due to the supernatural rot and water bleeding from its body.
        
    - _Resilient:_ Increases the creature’s Stress Limit by +2. Can spend Threat to Mitigate damage, reducing incoming Impact by 2 per point spent (up to its Vessel limit).
        
- **Threat Abilities (2):**
    
    - **Cost 1 Threat - Corpse-Gas Rupture:** _Trigger:_ Declared immediately when the Goliath takes a physical Wound. _Effect:_ The wound forcefully expels highly toxic swamp gas. The player who delivered the Wound instantly suffers the _Rigor_ condition as their lungs violently seize up, completely denying them the ability to Parry or Dodge on the Goliath's next turn.
        
    - **Cost 2 Threat - Sweeping Uproot:** _Trigger:_ Declared before the Goliath makes a Strike. _Effect:_ The Goliath drags its massive club through the earth. This Strike gains the _Cleave_ tag, forcing every player in its frontal arc to defend against the same Strike roll. Furthermore, any player who loses the Clash is knocked Prone.
        
- **Vessel Limit:** 2
__________________________________________________________________
## The Barrow-Fang

> _"The howls stopped an hour before it found us. That's when Corvis said we should've kept moving."_

### Vital Statistics

- **Tier:** Elite
- **Type:** Lycanthrope, Humanoid
- **Size:** Large (Scale +1)
- **Stats:** Brawn +2, Reflex +2 _(Assumed Zero: Wits, Will — whatever reasoned it out died the first time it changed.)_
- **Skills:** Melee +2, Dodge +1, Notice +1 _(Assumed Zero: everything else.)_
- **Derived stats:**
    - Wound Threshold: **8** _(4 + Brawn 2 + Scale +2)_
    - Stress Limit: **5** _(4 + Will 0 + Wits 0 + 1 Elite)_
- **Equipment:** None — natural weapons only. Bite & Claw (Power 2). Strike Roll: 2d6 + 4 (Brawn 2 + Melee 2).
- **Traits (3):**
    - **Cursed Regeneration:** At the start of the Barrow-Fang's activation, it automatically heals 1 Wound Slot and clears 1 Stress. _Weakness:_ any Wound inflicted by a weapon carrying a Lycanthrope Bane effect (Silvered Edge, per Hardware) permanently suppresses this trait for the rest of the encounter — the same shape as the Frost-Cave Troll's fire weakness, with silver standing in for flame.
    - **Vicious:** If the Barrow-Fang inflicts damage on a PC, the target must immediately pass a Brawn check or gain the Bleeding condition.
    - **Ambusher:** Gains Advantage on the Clash roll if attacking an unaware target from Stealth.
- **Vessel Limit:** 2
- **Threat Abilities (2):**
    - **Cost 1 Threat — Howl of the Hunt:** _Trigger:_ Declared at the start of the Barrow-Fang's activation. _Effect:_ Every player within 30 ft who can hear it must pass a Will + Resolve check vs. TN 8 or gain the Fear condition (targeting the Barrow-Fang) for the rest of the encounter.
    - **Cost 2 Threat — Rend and Pin:** _Trigger:_ Declared on a successful Melee Clash with a Margin of 3+. _Effect:_ In addition to normal Impact, the target is knocked Prone and pinned — they cannot stand or take a Move Action until they win an opposed Brawn + Prowess check against the Barrow-Fang (attempted as a Free Action on their own activation).

### Phases

- **Behaviour when unbroken:** Hunts with patient, almost human cunning before the change fully takes hold — uses Ambusher to open the fight from cover rather than announcing itself, closing to melee only once an opening is certain. The Howl is a closer's move, not an opener: spent once it's confident the fight is already lost for its prey.
- **Behaviour when Broken:** Per the GM Tools NPC Stress rules, this resolves as **Frenzy** (Beasts & Monsters), not Surrender (Humanoid Elites) — a deliberate call given the dual Type. The wolf, not the person, is what's left once the mind goes: it loses Dodge and Block entirely but gains Advantage on all Strike rolls until it dies. _If your table wants a tragic "still human underneath" beat instead, this is the specific creature to house-rule to Surrender — but the trope reading is Frenzy._
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

---


_______________________________
### Boss: Arch-Devil Malaphar

- **Budget Used:** 14 points.
    
- **Stats:** Brawn +4, Will +3, Wits +2 | Melee +3, Arcana +2, Resolve +1. _(Assumed Zero: Reflex, Dodge. A lumbering powerhouse of physical and magical pressure, but acts last in combat and cannot dodge out of the way of AOE attacks)._
- **Wound Threshold:** 12 (4 + Brawn 4 + armour 4 )| **Wound Slots:** 5| **Stress Limit** 11.
- **Equipment:** Brimstone Plate (+4 Armour, armour immune to damage, immune to fire) , Hell-forge Great sword (Power 5, after inflicting a wound target must pass a Resolve check at -2 or gain Ablaze condition.)
- **Traits (3):**
    
    - _Terrifying_ & _Cunning Leader_.
        
    - _Hubris (Passive Threat Engine):_ The Arch-devil feeds on mortal desperation. The GM instantly generates 1 Threat every single time a player spends Momentum from their bank.
        
- **Threat Abilities (3+):**
    
    - **Cost 1 Threat - Furnace Rebuke:** _Trigger:_ Declared when Malaphar wins a Clash as the Reactor (Defense). _Effect:_ The Sovereign deflects the player's blow with such friction that the player's weapon or hands burst into flames. The player instantly gains the Ablaze condition.
        
    - **Cost 2 Threat - The Devil's Mandate:** _Trigger:_ Declared as a Free Action on Malaphar's turn. _Effect:_ Malaphar speaks a word of absolute authority, targeting one player. That player must pass a TN8 will + resolve check at -2, OR drop to their knees in submission (gaining the Prone and Anchored conditions).
        
    - **Cost 3 Threat - Lair Action (Gehenna's Grip):** _Trigger:_ Declared at the absolute start of a combat round. _Effect:_ The veil tears, and chains of molten iron erupt. Every player must make an immediate, unopposed Brawn + Melee/Dodge check against TN 8. Failure means they are violently dragged 10 feet toward Malaphar.
        
- **Vessel Limit:** 4.
