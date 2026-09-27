# The Dynamic Trait Manifest
Design Philosophy: Keep stat blocks simplified. Let traits dictate tactical behaviour, stress interaction, and Momentum usage.

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

Budgets are measured in **Skill points** — the sum of every Skill rank on the sheet. Attributes are deliberately excluded. They no longer contribute to any roll; they set Skill ceilings and drive derived stats, and they cost 5 DP against a Skill rank's 1–3, so summing the two would be adding unlike currencies. What a creature rolls is its Skills, and what a PC rolls is theirs — that is the only number worth comparing.

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
- **Grunt** tracks the party's *current* Standing, at roughly 50–70% of their typical total — enough to force a Momentum spend from a single PC, credible in numbers, still meant to lose to focused attention. That percentage looks far higher than the 25–30% quoted under the old Attribute+Skill metric, but nothing about a Grunt actually changed: the Orc Line-Breaker struck at +4 then and strikes at +4 now. The old figure was understated because a PC's 12 included 4 Attribute points that were also feeding their rolls. Measured on what both sides actually roll, a Grunt has always been this close to a PC on its one good number, and short of them everywhere else.
- **Elite** is budgeted as roughly the party's *next* Standing tier up — a literal reading of the tier's own text, "a few advances ahead of the characters at all times." At Green, Elite is budgeted like a Blooded PC; at Hardened, like a Storied one. The four Elites below land at 9–11 Skill points against a Green party's 8, which makes the tier's "almost equivalent to the characters' capabilities" description true as written for the first time.
- **Dread/Boss** is budgeted roughly two Standing tiers ahead, with a wide, GM-discretion range. A solo Boss has to "rival a highly optimized player" while getting acted on 3–5 times for every one of its own actions, so its raw stat budget needs real headroom over Elite, not a marginal bump.

**The existing roster, checked against the new numbers:**

| Creature | Tier | Skill points | Green band | Verdict |
|---|---|---|---|---|
| Goblin Scrapper | Fodder | 2 | 1–2 | in band |
| Corpse-Trench Rat Brood | Fodder | 2 | 1–2 | in band |
| Imp | Fodder | 2 | 1–2 | in band |
| Skink | Fodder | 2 | 1–2 | in band |
| Giant Spider | Fodder | 2 | 1–2 | in band |
| Orc Line-Breaker | Grunt | 6 | 4–6 | in band |
| Lizardman | Grunt | 5 | 4–6 | in band |
| Lizardman Shaman | Elite | 9 | 9–12 | in band |
| Bandit Captain | Elite | 9 | 9–12 | in band |
| Frost-Cave Troll | Elite | 10 | 9–12 | in band |
| Cultist Assassin | Elite | 11 | 9–12 | in band |
| Rotting Fen-Goliath | Elite | 11 | 9–12 | in band |
| The Barrow-Fang | Elite | 9 | 9–12 | in band |
| Arch-Devil Malaphar | Boss | 15 | 13–17 | in band |
| Gutter Rat | Fodder | 2 | 1–2 | in band |
| Back-Alley Brawler | Fodder | 2 | 1–2 | in band |
| Knuckle-Duster | Grunt | 5 | 4–6 | in band |
| The Bouncer | Grunt | 5 | 4–6 | in band |
| The Fixer | Elite | 9 | 9–12 | in band |
| The Duelist | Elite | 9 | 9–12 | in band |

- **Cultist Assassin** was previously flagged as needing a rebuild for falling under the Elite floor. It no longer does. The flag was an artefact of the old metric double-counting a shared Attribute: its Reflex +3 was propping up both Dodge and Stealth but only counted once. At 11 Skill points it sits comfortably mid-band, and its Traits and Special Actions were correctly tuned all along. **No rebuild required — flag withdrawn.**
- **The Barrow-Fang** was mislabeled Dread in this table — its own statblock reads Tier: Elite, and its build (3 Traits, 2 Special Actions) matches Elite's spec, not Dread/Boss's 3+ Special Action minimum. Measured against the correct Elite floor it was short by 1 Skill point (8 vs. 9); Notice raised from +1 to +2 closes that gap. No rebuild needed once the tier label itself is fixed.
- **Arch-Devil Malaphar** carries an internal contradiction predating this conversion: an earlier worked example in this section cited Melee +4 / Resolve +3 (old Attribute+Skill notation), and an earlier statblock revision had Melee +3 / Resolve +1. Both are superseded — the current statblock reads Melee +7 / Arcana +4 / Resolve +4, which is what a GM actually runs. At 15 Skill points he sits at the top of the Green Dread band and inside every later row through Veteran. Against a Hardened or Storied party he is under-budgeted and would need a pass.

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
    
    - _Example (Cultist Assassin — flag resolved, see above):_ Melee +2, Acrobatics +4, Stealth +4, Notice +1. _(Strikes at +2, Dodges at +4 — Dodge is Acrobatics — Stealths at +4. Prowess is +0)._
    
- **Dread Entities / Bosses (The Behemoths):** Skills can exceed the +6 mortal ceiling.
	- 2 - 4 Traits. 
	- 3+ Special Actions — this is the tier where a genuinely Momentum-costed ability (a Free Action stacked on a full turn, or a Lair Action outside the turn order) actually belongs. 
	- A genuinely free-standing ability at this tier may carry a **Momentum cost**, paid from the creature's own Bank. 
	- 4+ wounds. 
	- stress as core rule defined + 2
    
    - _Example (Arch-Devil Malaphar):_ Melee +7, Arcana +4, Resolve +4. _(Strikes at +7, casts at +4, resists mental magic at +4. Still has Activation Order 6 — he acts last).
    

**Core-Species Humanoids (Built Like a PC, Run Like an NPC)**

A Humanoid of one of the six core species — Human, Half-Elf, Half-Orc, Halfling, Elf, Dwarf — is built with the same rules as a player character (see The Marrow): its species traits, its Feats, and its spells all come from the players' own lists, and its derived stats use the players' own formulas. Monsters and non-core humanoids (goblins, orcs, lizardmen, skinks) keep bespoke Traits and Special Actions as before.

Construction comes from The Marrow. Runtime stays here. Specifically:

- **Attributes** are allocated per tier, not from the Skill budget: **Fodder 1 · Grunt 2 · Elite 4 · Dread/Boss 6+** (a Boss may exceed the +3 mortal cap). Kept deliberately lean so derived stats stay in line with the rest of the roster — Attributes feed Wound Threshold and Stress Limit, and because NPC Stress is binary, a larger Stress Limit is a straight durability gain with no Winded penalty to offset it. Be aware these points do three jobs at once: they set Skill ceilings, meet Feat prerequisites, and drive the derived stats. At Fodder and Grunt the Ceiling Rule is effectively inert — a +3 ceiling applies even at Attribute 0, and those Skill budgets can't reach past +3 — so the points go to derived stats as intended. From Elite up, a specialist build can find every point already committed to a ceiling or a prerequisite before durability gets a look in; the Stress Limit floor below is what catches that.
- **Skills** use the Enemy Budget by Party Standing table above, unchanged.
- **Feats, spells and Traits share one allowance**, sized by tier: **Fodder 2 · Grunt 2 · Elite 3 · Dread/Boss 4**. Spend it in any mix — a Feat or spell from the players' own lists, or a Trait from the Manifest below, whichever actually serves the creature. Feats and spells come from The Marrow and Manipulating The Void, with a feat tier ceiling of Grunt Tier 1, Elite Tier 1–2, Dread/Boss any; spells must still satisfy their own Arcana/Faith rank prerequisites, and Paradigm Mastery works exactly as it does for a PC — within the chosen Paradigm only. Where a creature's signature mechanic has no equivalent on the players' lists (Skittering, Ambusher, Cunning Leader), spend the allowance on the Trait and don't contort the build to avoid it.
- **Species traits are free** and sit outside the allowance entirely. Don't restate the species lists here; they live in The Marrow and are read from there, so the two documents can't drift. Species *drawbacks* come along with them — a Human NPC really does have a smaller Momentum Bank, a Dwarf really can't run anyone down, and a Half-Orc really is worse at talking to strangers.
    - **A trait that modifies the *creation* Skill budget is inert on an NPC.** The Human's **Adaptable** ("1 extra Skill Point at character creation") is the only case today: an NPC's Skills come from the Enemy Budget by Party Standing table, never from a creation budget, so there is nothing for it to modify — the same way the Ceiling Rule is inert at Fodder and Grunt. Its paired drawback still applies in full. Don't add a skill point for it, and don't "correct" an existing Human NPC upward on the strength of it.
- **Momentum Bank:** **every creature has one** — core-species and monster alike — at the normal **4 + Reflex**, earned and spent exactly as a PC's: on its own Traits', Feats' and Special Actions' Momentum costs and on Iron Core's generic spends (Shake It Off, The Blood Price, Adrenaline Flush, The Surge). This applies at every tier including Fodder. **Momentum is the only currency in the game; there is no GM Threat pool and no Vessel Limit** — a Bank is already a spend cap. How each tier *earns* Momentum is asymmetric and lives in GM Tools' Momentum Economy: Fodder and Grunts earn only from their own Traits and Feats, Elites add a Clash won by Margin 5+, and Dread/Boss add 1 at the start of every round.
- **Wound Slots stay on the tier scale** (Fodder 1 · Grunt 2 · Elite 3–4 · Boss 4+), not the PC's flat 3. Wound Slots are what makes Fodder disposable.
- **Stress stays binary** — Functional/Broken per the GM Tools NPC Stress rules. No Winded, no Breaking penalty, regardless of how the creature was built.
- **Stress Limit has a tier floor — core-species builds only:** **Fodder 4 · Grunt 4 · Elite 6 · Dread/Boss 8.** Use the higher of the derived formula or the floor. Same principle already applied to Wound Slots — a tier baseline the PC formula can't drop below. It exists because a core-species build often spends its whole Attribute allowance on Skill ceilings and Feat prerequisites, leaving Will and Wits at zero; without a floor, a specialist Elite ends up with a lower breaking point than a Grunt purely as a side-effect of what it's good at.
    - **Monsters are exempt.** They have no Ceiling Rule and no Feat prerequisites competing for their Attribute points, so a monster's low Stress Limit is a deliberate build choice, not residue. The floor is a remedy for a problem monsters don't have — the Frost-Cave Troll and the Barrow-Fang sit at 5 by design.
    - **Wound Threshold gets no floor either**, for anyone. A fragile talker *should* read as fragile, and Wounds carry that fiction where binary Stress doesn't.
    - **Scale and Species modifiers apply after the floor and may take a core-species build below it.** A chosen drawback carrying fiction is not leftover budget, and the floor exists to catch the latter.
- **Special Actions** remain per the Gate Test, on top of the picks above.

*A trained caster is not an innate one.* A core-species Arcanist needs the **Arcane Awakening** feat (spending a pick), a Grimoire, and a free hand, and suffers Blind Casting without them. A monster with the **Innate Magic** trait — the Lizardman Shaman — bypasses all of that. That distinction is now mechanical rather than flavour, and it is the cleanest reason to keep the two construction methods separate.

________________________________________________________________________
# Traits
## DEFENSIVE & PHYSIOLOGICAL TRAITS

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

## OFFENSIVE & MARTIAL TRAITS

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

##  TACTICAL & PSYCHOLOGICAL TRAITS
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
    
___________________________________________________________________
# Example enemies

## Fodder

### The Goblin Scrapper

> _Scrawny, twitchy, and desperate. They prefer to strike from the shadows and retreat the moment the tide of battle turns against them._

#### Vital Statistics

- **Tier:** Fodder
- **Type:** Humanoid
- **Move:** 30 ft
- **Attributes (derived only):** Reflex 2 → Activation Order 8 _(Assumed Zero: everything else — incredibly difficult to hit, but folds the moment it's caught.)_
- **Skills:** Acrobatics +2. _(Its preferred defence is Dodge, at 2d6+2.)_
- **Derived stats:**
    - Wound Threshold: **5** _(Base 4 + 1 Leather)_
    - Wound Slots: **1**
    - Stress Limit: **4** _(4 + Will 0 + Wits 0 + 0 Fodder)_
    - Momentum Bank: **6** _(4 + Reflex 2)_
- **Equipment:** Leather armor (+1 to Wound Threshold). Rusty Shortsword — Power 2, Sidearm, Finesse; Shoddy Quality (becomes Damaged on a failed or fumbled roll, Ruined if already Damaged). Strike Roll: 2d6.
- **Traits (1):**
    - **Swarm:** The Scrapper gains a +1 bonus to their Clash roll for every additional Goblin ally currently engaged with the same target.
- **Special Actions (1):**
    - **Sabotage:** Instead of a regular attack action, the scrappy, opportunistic goblins try to swipe supplies from the target. Target must pass a TN 8 Acrobatics check or the Community Supply Die is reduced by 1 step.

#### Phases

- **Behaviour when unbroken:** Strikes from the shadows and leans on Swarm's stacking bonus rather than trading blows head-on — more likely to open with Sabotage than commit to a straight Clash.
- **Behaviour when Broken:** Per the GM Tools NPC Stress rules, resolves as **The Rout** — the moment its Stress Limit maxes out, it drops what it's carrying and flees the fight outright.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.
___________________________________________________________________________________________________________________________________________________________________________________
### The Corpse-Trench Rat Brood

> _A writhing, starving mass that exists purely to drain Momentum and Wounds before the real threat arrives._

#### Vital Statistics

- **Tier:** Fodder
- **Type:** Beast
- **Move:** 30 ft
- **Attributes (derived only):** Reflex 1 → Activation Order 7 _(Assumed Zero: everything else — quick, but nothing props up a grapple or a mental defence; both resolve at +0.)_
- **Skills:** Melee +1, Acrobatics +1. _(Its preferred defence is Dodge, at 2d6+1.)_
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
    - **Passive — Hive Mind:** If three or more swarms are engaged with a single target, they automatically inflict 1 Dissonant Stress on the target, representing the rats crawling over armor and finding gaps.

#### Phases

- **Behaviour when unbroken:** Presses forward as a mass, relying on Amorphous to shrug off single-target weapons and Hive Mind to punish anyone who lets three or more of the brood pile onto them.
- **Behaviour when Broken:** Per the GM Tools NPC Stress rules, resolves as **The Rout** — the brood scatters and flees rather than fighting to the last rat.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.
  ________________________________________________________________________________________________________________________________________________________________________________________________________________

### Imp

> _A wiry knot of red hide, bat-wings, and barbed tail, spat out of the rift laughing — it doesn't fight to win, it fights to make you flinch._

#### Vital Statistics

- **Tier:** Fodder
- **Type:** Daemon
- **Move:** Fly 30 ft (no land Move — always airborne)
- **Attributes (derived only):** Reflex 2 → Activation Order 8 _(Assumed Zero: everything else — quick and erratic, but folds if it's actually caught.)_
- **Skills:** Melee +1, Acrobatics +1. _(Its preferred defence is Dodge, at 2d6+1.)_
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

#### Phases

- **Behaviour when unbroken:** Darts in and out of range using Skittering to avoid free strikes, peppering PCs with Hellfire Needle rather than closing to melee.
- **Behaviour when Broken:** Resolves as **The Rout** — once its Stress maxes out, it flees back toward whatever rift or shadow it came through rather than keep tormenting a fight it can't win.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

### Skink

> _Quick, quiet, and half your size — it was never going to fight you fair, and it doesn't have to._

#### Vital Statistics

- **Tier:** Fodder
- **Type:** Humanoid
- **Size:** Small (Scale -1)
- **Move:** 35 ft
- **Attributes (derived only):** Reflex 2 → Activation Order 8 _(Assumed Zero: everything else.)_
- **Skills:** Stealth +2.
- **Derived stats:**
    - Wound Threshold: **3** _(Base 4 - 1 Small + Brawn 0)_
    - Wound Slots: **1**
    - Stress Limit: **3** _(4 - 1 Small + 0 Fodder)_
    - Momentum Bank: **6** _(4 + Reflex 2)_
- **Equipment:** Blowgun (Power 0, 2H, Ranged Short/20 ft, Concealable). Strike Roll: 2d6 (Ranged +0).
- **Traits (1):**
    - **Skittering:** Unnatural speed, shifting limbs, or erratic reflexes make them slippery targets. This creature may move out of a Threat Zone without requiring a test, or causing a free strike.
- **Special Actions (1):**
    - **Numbing Venom:** _Trigger:_ Instead of a regular attack, declared against a target within 20 ft. _Effect:_ A dart tipped with numbing jungle toxin strikes the target. Target must pass a TN 8 Prowess check or gain the Rigor condition, denying Parry or Dodge on their next defense.

#### Phases

- **Behaviour when unbroken:** Stays hidden and lets Stealth do the work, sniping with Numbing Venom from range rather than closing to melee, retreating through gaps and crevices too small for a Standard-Scale pursuer.
- **Behaviour when Broken:** Resolves as **The Rout** — vanishes into tunnels only something Small-Scale can follow.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

### Giant Spider

> _Bloated on temple rats and worse, it hangs motionless in the dark until the webbing twitches — then it's already moving._

#### Vital Statistics

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

#### Phases

- **Behaviour when unbroken:** Lurks on the walls or ceiling using Wall-Crawler for a surprise angle, Silk-Snares whoever gets too close, and lets Swarm's stacking bonus punish anyone who lingers once more spiders close in.
- **Behaviour when Broken:** Resolves as **The Rout** — scuttles back up into the webbing and cracks overhead.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

### Gutter Rat

> _A blur of small hands and someone else's coin purse. You notice the knife after you notice the purse is gone._

#### Vital Statistics

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

#### Phases

- **Behaviour when unbroken:** Works the edges — never the first into a fight and never alone, leaning on Underfoot to stay unseen until someone is already occupied, then knifing whoever is distracted.
- **Behaviour when Broken:** Resolves as **The Rout** — scatters into the crowd, the drain, or the gap between two buildings that nobody larger can follow.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

### Back-Alley Brawler

> _Rented muscle, paid enough to hurt you and not one copper more. Hitting it does not make it stop; hitting it makes it pay attention._

#### Vital Statistics

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

#### Phases

- **Behaviour when unbroken:** Closes immediately and swings, using Menacing to pick the smallest-looking target in the room and Haymaker whenever it thinks the fight is nearly over.
- **Behaviour when Broken:** Resolves as **Frenzy** — the dynamic Blood Frenzy already implies. It loses its defensive options entirely but gains Advantage on all Strike rolls until it drops.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

### Watch Patrolman

> _Paid to be seen, not to win. The whistle around his neck is the dangerous part of him._

#### Vital Statistics

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

#### Phases

- **Behaviour when unbroken:** Never fights alone and never leads. Closes with Baton Charge when he has a partner already engaged, otherwise holds ground and shouts for the Sergeant.
- **Behaviour when Broken:** Resolves as **The Rout** — the pay is not good enough. He runs for the nearest other Patrolman, then past him.
- **Dread Entity/Boss Phase changes:** N/A — Fodder tier, no phase structure.

## Grunt

### Orc Line-Breaker

> _A wall of scarred green muscle and notched iron, swinging a two-handed axe built to open gaps in a shield wall — where the Line-Breaker plants its feet, formations stop holding._

#### Vital Statistics

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

#### Phases

- **Behaviour when unbroken:** Holds the line with wide, two-handed axe swings, leaning on Plated to shrug off incoming Impact and triggering Unstoppable Mass on a clean clash win to tax Momentum or shove a PC out of formation.
- **Behaviour when Broken:** Per the GM Tools NPC Stress rules, resolves as **Frenzy** rather than The Rout — it loses Block entirely but gains Advantage on all Strike rolls until it dies.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.
    ___________________________

### Lizardman

> _A temple guardian in scale and spear, patient enough to let the pit trap and the skinks do the thinning before it ever has to fight._

#### Vital Statistics

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

#### Phases

- **Behaviour when unbroken:** Holds its Spear's Reach behind the Shield, using Snapping Counter to punish anyone who presses the attack rather than chasing them down.
- **Behaviour when Broken:** Resolves as **The Rout** — breaks and flees deeper into the temple, straight toward the inner chamber, giving whatever guards it there fair warning.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

### Knuckle-Duster

> _A working professional. Nothing personal — unless you make it personal, and people who make it personal stop being seen around here._

#### Vital Statistics

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

#### Phases

- **Behaviour when unbroken:** Picks one target and stays on them, using Brute to walk them backwards into a wall or an alley mouth and Debt Collector's Grip to pin whoever is trying to leave. The Sap is deliberate — a body is paperwork, a broken hand is a message.
- **Behaviour when Broken:** Resolves as **The Rout** — a professional, not a martyr. Disappears into streets he knows far better than the party does.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

### The Bouncer

> _Holds the door like it's the only thing in the world worth holding. For the length of his shift, it is._

#### Vital Statistics

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

#### Phases

- **Behaviour when unbroken:** Never leaves the chokepoint voluntarily. Lets the party come to him, blocks rather than swings, and relies on Choke the Doorway to make a narrow space cost more than it's worth.
- **Behaviour when Broken:** Resolves as **Surrender** — a working stiff who yields rather than dies for a boss who isn't even in the room. Perfectly willing to discuss where that boss is, for the right consideration.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

### Watch Sergeant

> _Twenty years of telling people what the law is. He has never once had to raise his voice twice._

#### Vital Statistics

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
    - **Battlefield Orator** _(Feat, Tier 1 — prerequisite Influence 2, met)_ — spend an Action to shout orders or hurl insults. Choose one: an ally immediately clears 1d6 Dissonant Stress, OR an engaged enemy suffers -2 on their next Defence roll.
- **Special Actions (1):**
    - **Hold the Line:** _Trigger:_ Instead of a regular attack. _Effect:_ He plants and calls the formation in. Every allied Watch member within 10 ft, himself included, gains +1 to Block rolls until the start of his next activation.

#### Phases

- **Behaviour when unbroken:** Fights last and talks first. Opens with Battlefield Orator to strip a Defence roll, uses Cunning Leader to let two Patrolmen swing before he does, and draws the Shortsword only once someone has drawn steel on him.
- **Behaviour when Broken:** Resolves as **Surrender** — a professional, not a fanatic. He calls the withdrawal and expects to be obeyed, and will trade information for being allowed to walk.
- **Dread Entity/Boss Phase changes:** N/A — Grunt tier, no phase structure.

## Elite

### Lizardman Shaman

> _The idol's keeper does not fight for the temple. It fights for whatever is still listening underneath it._

#### Vital Statistics

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
    - **Burst** _(ordinary attack, Aggressor):_ Arcane Clash, Arcana vs. each target's Defense. Spell Power 2, 10ft cone. Margin 1–2 (treated as Clean per Innate Magic): Impact = Margin + 2 (Spell Power), no Dissonant Stress. Margin 3+ (Clean): as above.
    - **Ward of Scales** _(Activation, to raise; Reactor, to use)_ — _Arcane Protection:_ Unopposed Arcana vs. TN 8. Clean (Margin 3+, or Margin 1–2 treated as Clean per Innate Magic): hostile spells targeting the Shaman suffer Disadvantage to cast. As a Reactor action against an incoming hostile spell, the Shaman may Block using Arcana instead of a normal Reactor stat. Sustained per the normal Channelling Rule (Arcana vs. TN 8 each Activation and on taking a Wound) — a Messy Sustain is likewise treated as Clean.
    - **Call of the Deep Green** _(Aggressor)_ — _Beast Friend:_ Targets a Giant Spider or other Beast-type creature within Short Range. Arcane Clash, Arcana vs. the beast's Resolve. Margin 1+ (treated as Clean per Innate Magic): the beast becomes the Shaman's ally for the scene, communicating telepathically and seeing through its eyes for the scene.

#### Phases

- **Behaviour when unbroken:** Opens by raising Ward of Scales rather than attacking immediately, then alternates Burst to hold the party at range and Call of the Deep Green to drag a Giant Spider onto its side.
- **Behaviour when Broken:** Resolves as **Frenzy**, reflavored for a caster — Ward of Scales drops the instant it Breaks and can't be re-raised, but the Shaman gains Advantage on all spell Clash rolls until it dies, channelling without any care for its own burnout.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

### Cultist Assassin

#### Vital Statistics

- **Tier:** Elite
- **Type:** Humanoid (Human)
- **Move:** 30 ft
- **Attributes (4 — Elite allowance):** Reflex 3, Wits 1. _(Assumed Zero: Brawn, Will — practically untouchable by standard strikes, but rolls 2d6+0 if forced into a Grapple.)_
- **Skills (11):** Melee +2, Acrobatics +4, Stealth +4, Notice +1. _(Dodges at 2d6+4 — Dodge is Acrobatics, per Metal meet Flesh.)_
- **Derived stats:**
    - Wound Threshold: **4** _(Base 4 + Brawn 0)_
    - Wound Slots: **3**
    - Stress Limit: **7** _(4 + Will 0 + Wits 1 + 1 Indomitable Spirit + 1 Elite)_
    - Activation Order: **9** _(6 + Reflex 3)_
    - Momentum Bank: **6** _(4 + Reflex 3, then -1 for Steady, Not Sharp)_
- **Equipment:** Dagger (Power 0, 1H, Concealable, Close-Quarters, Finesse, Thrown, Sidearm) — Strike Roll: 2d6+2 (Melee +2). Shortbow (Power 2, 2H, Volley) for ranged work before closing in — Ranged +0, Strike Roll: 2d6.
- **Species Traits (free — see The Marrow):**
    - **Indomitable Spirit:** Base Stress Limit increased by +1 (already folded into the derived stat above).
    - **Steady, Not Sharp (Drawback):** Momentum Bank cap reduced by 1 (already folded in above).
- **Allowance (3 — Elite): 1 Feat, 2 Traits**
    - **Shadow-Weaver** _(Feat, Tier 1; prereq Stealth 1 ✓)_ — ignores the standard penalty for moving quickly while trying to remain hidden. It can sprint out of a Threat Zone at full Move and still be hidden enough at the end of it to Vanish; without this, Rushed Stealth was taxing the exact manoeuvre the creature is built around.
    - **Ambusher** _(Trait)_ — gains Advantage on the Clash roll if attacking an unaware target from Stealth.
    - **Skittering** _(Trait)_ — unnatural speed, shifting limbs, or erratic reflexes make them slippery targets. This creature may move out of a Threat Zone without requiring a test, or causing a free strike.
- **Special Actions (2):**
    - **Vanish:** _Trigger:_ At the end of its movement this activation, if it ends that movement in an Obscured or Heavily Obscured position (per Iron World's Cover rules). _Effect:_ The Assassin blends into the shadows, becoming effectively totally obscured — finding them again requires a successful Notice check.
    - **Throat Slit:** _Trigger:_ On a successful Melee clash with a Margin of 3+. _Effect:_ The target immediately suffers a Minor Wound, bypassing their normal Impact Threshold.

#### Phases

- **Behaviour when unbroken:** Opens with the Shortbow or from Stealth with Ambusher, closing in for the Margin-3 opening that triggers Throat Slit — then uses Skittering to slip out of the Threat Zone it just created and Shadow-Weaver to run at full speed without breaking cover, Vanishing if that retreat ends somewhere obscured. Never sticks around for a fair fight it doesn't need to have.
- **Behaviour when Broken:** Resolves as **The Rout** — Vanish is already its escape valve, so once Stress maxes out it uses that same instinct to disappear from the fight for good rather than keep pressing a lost contract.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.
_______________________________

### The Bandit Captain

> _A serious threat that requires party synergy to defeat. He doesn't fight fair; he commands the battlefield with a heavy halberd, barking orders from behind a wall of cutthroats._

#### Vital Statistics

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

#### Phases

- **Behaviour when unbroken:** Commands from behind his line rather than leading it, using Cunning Leader to hand his activation to a Fodder ally for a coordinated strike, and Call for Reinforcements or Hook and Drag to keep the fight on his terms. Once the party clusters up to deal with his cutthroats, the halberd comes out: a Wound banks Momentum via Relentless Momentum, and that Momentum buys a **Sweep** across the whole cluster. Punishing the party for bunching is his actual win condition.
- **Behaviour when Broken:** Resolves as **Surrender** — a serious threat, not a fanatic or a beast; once his Stress maxes out, he reads the battle as lost and yields rather than dies for a cause he doesn't share.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.
  

---

### The Frost-Cave Troll

> _A towering, territorial brute of dense muscle and thick frost-bitten hide. It swings a shattered pine tree with horrifying speed, its wounds knitting together almost as fast as they are opened._

#### Vital Statistics

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

#### Phases

- **Behaviour when unbroken:** Leans on Troll-Blood Regeneration to shrug off attrition, alternating Vicious Frenzy's follow-up claw swipe with Sweeping Uproot to catch multiple PCs in one Cleave.
- **Behaviour when Broken:** Resolves as **Frenzy** — a mindless, territorial beast with nothing to surrender and nowhere it would flee to; it loses its Block/Dodge entirely but gains Advantage on all Strike rolls until it dies.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.
___________________________________________________________________
### The Rotting Fen-Goliath

> _A towering, decapitated mass of waterlogged flesh, rusted iron chains, and tangled mangrove roots. It does not feel pain; it only seeks to pull living warmth down into the freezing mud._

#### Vital Statistics

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

#### Phases

- **Behaviour when unbroken:** Plants itself in one spot, using Sinking Gravity to keep PCs mired in its Threat Zone and triggering Corpse-Gas Rupture or Sweeping Uproot to punish anyone who closes in or lines up in its front arc.
- **Behaviour when Broken:** Resolves as **Frenzy** — it doesn't feel pain and has nothing to surrender or flee toward; once its Stress maxes out it thrashes with pure Advantage-fueled violence until it's destroyed.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.
__________________________________________________________________
### The Barrow-Fang

> _"The howls stopped an hour before it found us. That's when Corvis said we should've kept moving."_

#### Vital Statistics

- **Tier:** Elite
- **Type:** Lycanthrope, Humanoid
- **Size:** Large (Scale +1)
- **Move:** 50 ft
- **Attributes (derived only):** Brawn 2, Reflex 2 → Wound Threshold 8, Activation Order 8 _(Wits and Will are zero — whatever reasoned it out died the first time it changed.)_
- **Skills:** Melee +4, Acrobatics +3, Notice +2 _(Assumed Zero: everything else. Its preferred defence is Dodge, at 2d6+3.)_
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

#### Phases

- **Behaviour when unbroken:** Hunts with patient, almost human cunning before the change fully takes hold — uses Ambusher to open the fight from cover rather than announcing itself, closing to melee only once an opening is certain. The Howl is a closer's move, not an opener: spent once it's confident the fight is already lost for its prey.
- **Behaviour when Broken:** Per the GM Tools NPC Stress rules, this resolves as **Frenzy**, not Surrender — the wolf, not the person, is what's left once the mind goes: it loses Dodge and Block entirely but gains Advantage on all Strike rolls until it dies. _If your table wants a tragic "still human underneath" beat instead, this is the specific creature to house-rule to Surrender — but the trope reading is Frenzy._
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

---


---

### The Fixer

> _She doesn't carry a weapon if she can help it. She rarely needs to — by the time a room turns violent, she has usually already sold it to someone._

#### Vital Statistics

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

#### Phases

- **Behaviour when unbroken:** Talks first, and keeps talking — Battlefield Orator to strip the defence off whoever is about to be hit, Silver-Tongued Viper aimed at whichever enemy looks least invested in dying for their employer. Fights only when cornered, and badly.
- **Behaviour when Broken:** Resolves as **Surrender** — she is a broker, not a soldier. Immediately offers whatever she has (names, routes, the location of the money) rather than die for an operation she doesn't own.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

---

### The Duelist

> _Fast enough that fair fights bore her. She is paid to stand slightly behind someone more important and be the reason nobody reaches them._

#### Vital Statistics

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
    - **Riposte** _(Tier 2; prereq Melee 2 ✓)_ — if she wins a Parry in a melee Clash, she instantly inflicts Impact on the attacker, calculated exactly as though she had won a Strike (her Margin of victory + weapon Power). Her defence *is* her offence.
    - **Quick** _(Tier 1; prereq Reflex 1 ✓)_ — +3 to Activation Order, and she breaks ties against anyone without Quick. Already folded into the Activation Order above.
- **Special Actions (1):**
    - **Blade Dance:** _Trigger:_ Instead of a regular attack, declared when at least two enemies are adjacent to her. _Effect:_ Two separate Melee Clash rolls at -1 each, one against each of two different adjacent targets.

#### Phases

- **Behaviour when unbroken:** Acts first in almost every round (Activation Order 11) and holds position between the party and whoever she's guarding. **Parries rather than dodges, deliberately** — Riposte turns every won Parry into a full Strike, so standing still and inviting the attack is the optimal play, not a failure of nerve. Blade Dance when flanked, rather than trying to escape the pincer.
- **Behaviour when Broken:** Resolves as **The Rout** — a professional withdrawal. Her employer's life is a contract, not a cause, and a dead duelist collects nothing.
- **Dread Entity/Boss Phase changes:** N/A — Elite tier, single behavioral break as above.

_______________________________

## Dread / Boss

### Arch-Devil Malaphar

#### Vital Statistics

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
- **Momentum-Costed Abilities (2):** the two genuine exceptions in the retuned roster — both are free-standing bonus effects with no action economy or Margin gate available to lean on instead. Both are paid out of his **Momentum Bank of 4**, which is exactly the Vessel Limit they used to draw against.
    - **Cost 2 Momentum — The Devil's Mandate:** _Trigger:_ Declared as a Free Action on Malaphar's turn — genuinely stacks on top of his normal Strike, so the Momentum cost is the only thing limiting it. _Effect:_ Malaphar speaks a word of absolute authority, targeting one player. That player must pass a TN 8 Resolve check at -2, or drop to their knees in submission (gaining the Prone and Anchored conditions).
    - **Cost 3 Momentum — Lair Action (Gehenna's Grip):** _Trigger:_ Declared at the absolute start of a combat round — outside any creature's turn entirely, so there's no action economy here either. _Effect:_ The veil tears, and chains of molten iron erupt. Every player must make an immediate, unopposed Melee or Dodge check against TN 8. Failure means they are violently dragged 10 feet toward Malaphar.

#### Phases

- **Behaviour when unbroken:** Rules through overwhelming pressure rather than urgency — lets Hubris farm Momentum passively as the players spend theirs, opens rounds with Gehenna's Grip to drag stragglers in, uses Devil's Mandate to take a problem PC out of the fight outright, and punishes anyone who attacks him directly with Furnace Rebuke.
- **Behaviour when Broken:** Per the GM Tools NPC Stress rules, a Boss's Broken state resolves as a Phase Change rather than a Rout, Surrender, or Frenzy — see below.
- **Dread Entity/Boss Phase changes — Gehenna Unbound:** _Trigger:_ The instant Malaphar's Stress Limit maxes out. _Effect:_ The veil doesn't just tear — it fails outright. A 60 ft radius centered on Malaphar becomes a literal fragment of Hell for the rest of the encounter. **Environmental Hazard:** at the start of each round, brimstone and hellfire lash every non-Daemon creature in the radius — resolved as a Hazard Roll (GM Tools): 2d6+2 (Hazard Power 2) against the character's Wound Threshold; a hit inflicts a Wound, a miss still inflicts 1 Stress. **Imps Erupt:** 3 Imps (Fodder tier — stat block not yet designed) tear through the rift and join the fight at the edge of the battlefield.
