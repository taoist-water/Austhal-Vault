# The Inventory
### 1. The Visual Slot System

Instead of tracking weight, a character’s carrying capacity is defined by a hard limit of physical "Slots" drawn on their character sheet as literal boxes.

- Total Capacity: Every character has a base of 8 Slots, plus their Brawn (Max 13 total slots).    
- Item Sizing:    

- 1 Slot: A one-handed weapon, a shield, a coiled rope, a Grimoire, a lantern, a cluster of 3 potions.    
- 2 Slots: A heavy two-handed weapon, a bulky Bestiary trophy (a Gorgon's head), a small treasure chest.    
- 0 Slots (Micro-Items): Things you can hide in a pocket don't take slots unless stacked in bulk. (e.g., 100 gold coins = 1 Slot).    

- Worn Armor Exemption: The armor a character is actively wearing does not take up Slots, but heavy armor inherently limits movement or stealth. If they take it off to carry it, it consumes 3 Slots.
    
**Containers Don't Multiply Slots:**
A container's listed Slot cost is for **the object itself**, full stop. Owning one never grants extra carrying capacity — it isn't a nested storage space, it's an item like any other. One 2-Slot chest consumes 2 - slots of Inventory and has a volume of 2-Slots. If the box is stolen or lost, any contents is stolen or lost with it.

**What decides whether an _empty_ container costs a Slot at all:**
- **Rigid/bulky-shaped** containers (Basket, Chest, Barrel) hold their shape and bulk whether full or empty, so they cost their listed Slots regardless of contents.
- **Soft/collapsible** containers (Sack, Belt Pouch, the Backpack itself) fold to nothing when unstuffed, so they're 0 Slots — until something with its own Slot cost goes inside, at which point you're tracking _that item's_ cost, not an extra charge for the sack around it.

**The Backpack** is still 0 Slots and worn-exempt, but to be explicit: it doesn't add capacity either. It's the fictional wrapper for the Pack designation, not a bag of holding — the Pack's actual size is fixed entirely by the character's Brawn-derived Slot total, independent of what container physically holds it.

### 2. The Belt vs. The Pack (Action Economy)

To stop players from instantly accessing a dozen different items during a sword fight, the Slots are divided into two physical locations with strict action costs.

- The Belt (Readied Gear): 3 Slots maximum. These are items hung on the belt, bandoliers, or sheaths. A character can draw an item from The Belt as a Free action during combat.
    
- The Pack (Stowed Gear): The remaining Slots. These are items strapped to the back or buried in a rucksack. Retrieving an item from The Pack mid-combat is practically impossible while dodging blows—it requires the player to forfeit their entire turn and take the Regroup action just to rummage through their bag.
    

Tactical Result: If the Pyromancer has a healing potion in their Pack, they cannot simply drink it while being attacked. They have to retreat, take the Regroup action to dig it out, and hope the Fighter holds the line.

### 3. The Attrition Tax (Wounds Limit Gear)

This is where the encumbrance system ties directly into your Death Spiral. As a character gets physically destroyed, their ability to bear weight collapses.

- The Mechanic: Every time a character suffers a Wound, they must immediately permanently cross out 1 Inventory Slot on their sheet.
    
- The Choice: If that Slot currently holds an item, the player must immediately drop an item in the dirt, or suffer 1 Dissonant Stress every single turn they continue to drag the excruciating weight.
    
- Narrative Impact: This forces agonizing decisions. Do you drop the heavy bag of gold you just found to carry your bleeding ally, or do you leave the ally behind to keep the treasure?
    
_______________________________________________________________________
# The Community Die
**The Community Supply Die**
_Hardware_ abstracts the party's shared consumables into the Community Die so nobody tracks individual arrows, torches, or waterskins. Concretely, that's:

- **Ammunition** — arrows, bolts, sling stones, thrown weapons you don't bother retrieving.
- **Light & Fuel** — torch stubs, lantern oil, flint-and-steel strikes, tindertwigs.
- **Field Rations & Water** — trail rations, waterskin refills.
- **Field Medicine** — the bandages and clean linen that make a Breather actually work. This is why a Depleted die specifically blocks Breathers from clearing Dissonant Stress — there's nothing left to bind the wounds with.

**The dividing line:** if it's _used up in the doing_ — an arrow loosed, oil burnt, a ration eaten, a bandage wound around a cut — it's the Die's problem. If it _still exists and still works_ after you use it — a bow, a lantern, a crowbar, a coil of rope — it's a normal Slotted item, tracked individually.

**Does the Die itself take a Slot?** No. It isn't a discrete object on any one character's sheet — it's already distributed as flavor across everyone's belts and packs collectively. Don't write "1× Supply Die" under anyone's inventory.

Instead of tracking every torch, bandage, and arrow, the entire party relies on a single shared abstraction of their collective resources.

- The Die Track: A fully stocked party enters the dungeon with a d10 Supply Die. The degradation track is: d10 $\rightarrow$ d8 $\rightarrow$ d6 $\rightarrow$ d4 $\rightarrow$ Depleted.
    
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
### When to Roll the Die

1. The Breather: the party must roll the Supply Die at the exact end of a 30-minute Breather. This represents the bandages used, the rations eaten, and the torch fuel burned while resting.
    
2. The Catastrophic Failure: If a player rolls a Natural 2 (Double 1s) while firing a ranged weapon or navigating a physical hazard, the GM can force a Supply Die roll as arrows shatter, bowstrings snap, or a pack falls into the mud.

________________________________________________________________________
# Quality
**MERCANTILE CRAFTSMANSHIP STATUS**

Items found in local markets carry tags denoting the skill of the artisan who hammered them together.

*Shoddy Quality* 
- Cost Modifier: -50% to base price.
    
- 2d6 Rule: Rusted iron, green wood, or poor craftsmanship. If a character rolls a fumble (Snake Eyes) or even just a standard failure while using a Shoddy item, the item is immediately Damaged. If it is already Damaged, it shatters completely and is Ruined.
    

*Balanced Quality* 
- Cost Modifier: +100% to base price.
    
- 2d6 Rule: Perfectly weighted pommels or expertly aligned shafts. Once per scene, when rolling a Clash or Attribute check using this item, the player can reroll a single die that landed on a '1', mitigating low-end variance.
    

*Masterwork Quality* 
- Cost Modifier: +300% to base price (Requires a specialized Commission downtime action).
    
- 2d6 Rule: Folded steel or bespoke custom-molded plating. Weapons gain a permanent +1 to their Power profile. Armor pieces grant their mechanical defensive bonuses but completely suppress one negative tag associated with them (e.g., a Masterwork Chainmail shirt loses its Bulky penalty).
__________________________________________________________________
# Gear Condition

**DAMAGED AND RUINED (THE CONDITION TRACK)**

Quality (above) describes how good a piece of gear was *when new*. Condition describes what's happened to it since. Every weapon, armor piece, shield, or tool — regardless of its Quality tier — can degrade along the same two-step track: **Damaged**, then **Ruined**.

*Damaged (Tag)*

- **The Effect:** The item suffers a flat **-1 penalty** to whatever numeric value it normally contributes to a roll or calculation. A Damaged weapon applies -1 to its Power. Damaged armor applies -1 to its Armor Value. A Damaged shield applies -1 to its Shield Value (SV). A Damaged tool kit applies -1 to the relevant skill check it would normally assist.
    
- **The Fiction:** The item still works — a cracked breastplate still stops most of a blow, a notched blade still cuts — but it's compromised. This is what separates Damaged from Ruined: Damaged gear is degraded but still usable in a fight without needing repair first.
    
- **Stacking:** Damaged does not stack with itself. An already-Damaged item that would be Damaged again is immediately **Ruined** instead (see below) — the second failure is what finally breaks it past the point of limping along.

*Ruined (Tag)*

- **The Effect:** The item is **non-functional**. A Ruined weapon deals no Power (Unarmed-equivalent only), Ruined armor grants no Armor Value, a Ruined shield grants no SV, and a Ruined tool cannot be used to assist any check at all.
    
- **The Fiction:** Shattered, snapped, or warped beyond field use. This isn't a -1 anymore — it's gone until someone puts real work into it.
    
- **Repair:** A Ruined item cannot be restored mid-dungeon by any of the temporary battlefield fixes below — it requires a **Hammer & Forge** downtime action back in civilization (or an equivalent feat/Momentum spend that explicitly says it can strip the tag, such as Cannibalize Gear) to become functional again.

**Getting From Damaged Back to Working**

- **Temporary Field Fixes** (e.g., The Patch Job) let a character ignore the -1 Damaged penalty for the duration of the current encounter only. The penalty returns the moment the fight ends — wire and sap aren't a permanent solution.
- **Permanent Field Repair** (e.g., Cannibalize Gear) strips the Damaged tag entirely, mid-dungeon, at the cost of cannibalizing a separate piece of equipment. This is the only way to permanently clear Damaged without returning to town.
- **Downtime Repair** (Hammer & Forge) is the standard, no-cost-beyond-time way to clear either Damaged or Ruined once back in civilization.

________________________________________________________________________
# Enchantments

## The Third Axis

Quality (above) describes how good an item was when it was forged. Condition describes what's happened to it since. **Enchantment is a third, fully independent axis** — a Balanced-Quality, Damaged-Condition, Enchanted longsword is a perfectly coherent item, and all three lines are answered separately. Magic in Iron & Marrow does not stack flat bonuses on top of the existing Power/Wound Threshold math — that headroom is already spent (see the rescaled Weapon Power tiers, and the Golden Rule that Wound Threshold bonuses from magical sources don't stack). Instead, enchanted items grant **tags, Momentum-gated abilities, or Bane effects** — the same vocabulary spells and Domain Tags already use elsewhere in the system.

## Attunement

Wearing or carrying an Enchanted or Relic item permanently isn't free — a sliver of the magic occupies a corner of the wielder's mind.

- **Trinkets and Charmed items never require Attunement.** Wear or carry as many as you like.
- **Enchanted and Relic items cost 1 Locked Stress each to Attune.** This Stress is locked for as long as the item is bonded to its wielder, exactly like a Sustained spell, and falls under the same Golden Rule: it cannot be cleared by Grounding, the Reprieve, or Religious Pursuit — only by physically unattuning.
- **Unattuning takes 10 minutes of uninterrupted handling** — safe to do during a Breather or downtime, impossible mid-combat.
- **Attunement Slots = Will score (minimum 1).** A character cannot be Attuned to more Enchanted/Relic items at once than this.
- Losing an Attuned item mid-combat (disarmed, stolen, Sundered) does not instantly refund the Stress — it releases at the start of the wielder's next Activation, the same beat as any other Sustain dropping.

## The Four Tiers

| Tier          | Availability                   | Attunement                                    | Power Level                                                                                          |
| ------------- | ------------------------------ | --------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| **Trinket**   | Common/Scarce                  | None                                          | Flavor only, or a single trivial non-combat nudge — the "Cantrip" of magic items.                    |
| **Charmed**   | Scarce/Rare                    | None                                          | One tag grant, or a narrow situational bonus — roughly Common-spell strength.                        |
| **Enchanted** | Rare/Legendary                 | 1 Locked Stress                               | A real ability, or a Momentum-gated active — Adept-spell strength.                        |
| **Relic**     | Legendary, unique, GM-authored | 1 Locked Stress + a bespoke built-in drawback | Master Miracle/Tier 3 Feat strength. Not purchasable — a campaign fixture with a name and a history. |

**On Relics specifically:** the Locked Stress cost alone isn't enough of a toll for Master-tier power. Per the same logic already used for Resurrection's Soul Scar and Half-Elf's inherited drawbacks, a Relic's cost should be written into the item itself, not just paid for in Stress. Don't hand out a Relic without also handing out its hook.
___________________________________________________________________
### Trinkets (No Attunement)

**Ever-Warm Hearthstone** — 8 sp | Common
A fist-sized river stone that radiates gentle warmth and never needs fuel. No mechanical effect — a comfort item only. Cold-weather Survival Hazard Checks (per Iron World) are still made normally; this just makes camp pleasant.

**Chorus Locket** — 15 sp | Scarce
A hinged locket that records up to 10 seconds of whispered sound and replays it once when opened. No combat application — a message-passing or narrative tool only.

**Prattling Bauble** — 6 sp | Common
Jewellery that shifts through a slow spectrum of colours when tapped, or a stone that releases a wisp of perfume when rubbed. Common "adventurer curiosity" loot, worth exactly what a buyer will pay for a conversation piece.

### Charmed (No Attunement)

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
- **Effect:** Bane (Fey, Daemon). The wielder treats a Fey or Daemon target's Wound Threshold as 1 point lower.
- *The one deliberate exception to "one Creature Type per Charmed item": cold iron's dual reach is a single, unified material property, not two separate wards bundled together, so it doesn't strain the logic that keeps Enchanted-tier breadth capped. Priced and gated below Silvered Edge and Blessed Edge for the same reason — no blessing, no silversmithing, just the metal itself, worked pure.*

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
- *Named for the same underlying idea as the Arcanist's Grounding action and the Mage Staff's Grounding Rod tag — venting raw, ungoverned energy safely to earth, just applied outward through a strike instead of inward through a caster's own mind.*

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
- *Worth being honest about this one's ceiling: several written Void-Touched abilities (Flay the Veil, most notably) already bypass Wound Threshold and Armor entirely by design. Leadglass Ward still matters in any fight that comes down to ordinary Impact-vs-Threshold math, but it isn't the reliable answer Silvered Edge is against a Lycanthrope — useful, not a silver bullet.*

**Quicksilver-Traced Edge** (weapon add-on) — 35 sp | Rare
Requires a weapon. A hair-thin vein of quicksilver run along the fuller or edge — an old alchemist's belief that the thing which unmakes flesh can also unmake what remade it.
- **Effect:** Bane (Mutant) — see Bestiary: Creature Types. The wielder treats a Mutant target's Wound Threshold as 1 point lower.

**Cloak of Still Water** (armor add-on) — 35 sp | Rare
A grey, unremarkable cloak that seems to drink ambient noise.
- **Effect:** The wearer gains Advantage on Stealth checks while moving at half their Move value or slower — turning the existing Rushed Stealth penalty (Iron World) into a non-issue for anyone patient enough to earn it, rather than granting a new kind of bonus outright.

### Enchanted (1 Locked Stress Attunement)

**Sigil-Etched Blade** — ~150 sp | Legendary, Commission-gated
A longsword (or similar) inlaid with warding sigils that glow faintly hot to the touch of anything unnatural.
- **Effect:** Bane (Undead, Daemon). Once per Scene, the wielder may spend 1 Momentum on a successful hit against a Bane-eligible target to also inflict the Fear condition (per the Bestiary Trait of the same name).

**Blade of the Undertow** — ~150 sp | Legendary, Commission-gated
A weapon that always smells faintly of brine, regardless of how far from the sea it travels.
- **Effect:** Once per Scene, the wielder may spend 1 Momentum on a successful hit to force the target into an unopposed Brawn + Prowess check vs. TN 8; on a failure, the target is shoved 1 Zone and knocked Prone. (Reuses Havoc's and the Domain of Sea & Storms' existing push/shove language rather than inventing new physics.)

**Sigil-Bound Wand (Single-Charge)** — 40 sp for a stored Novice spell, scaling to Legendary for Master-tier | Rare–Legendary
A single-use wand pre-loaded with one specific spell by an Arcanist during downtime (treat the loading process as a Commission). This is the formal version of the "activate an alchemical wand looted off a dead Boss" scenario GM Tools already gestures at — any character can trigger it, not just casters.
- **Activation:** The activator makes that spell's normal Resolution roll (Wits + Arcana, opposed or unopposed per the spell's own entry), whether or not they possess the Arcane Awakening feat.
- **If the activator has Arcane Awakening:** only a Snake Eyes destroys the wand (it gains the Ruined condition). A standard Failure just fizzles — the charge remains for a later attempt.
- **If the activator does not have Arcane Awakening** (using invested Arcana skill points per the Non-Caster Usage of Faith and Arcana rules in GM Tools): any Failure, not just Snake Eyes, destroys the wand. An untrained hand can't channel it precisely enough to survive a botch.
- *This item costs the activator no personal Stress win or lose — that's the whole point, it's what makes it safely usable by non-casters. The destruction risk on a failed roll is what stops it from being strictly better than casting the spell yourself.*

**Reliquary Symbol** (Holy Symbol upgrade) — ~150 sp | Legendary, Commission-gated
A Holy Symbol whose Domain-blessing has visibly deepened — filigree that was plain now catches light that isn't there.
- **Effect:** +1 to all Tithe of Will rolls. *(The Faith-side equivalent of the old Wand bonus, translated into Faith's own currency: pushing more rolls over the TN 8 line means fewer Fails, which means less Encroachment, rather than a flat combat bonus Faith's math doesn't otherwise have a slot for.)*

**Whisper-Kissed Leathers** — ~150 sp | Legendary, Commission-gated | 1 Locked Stress Attunement  
Requires a Light armor base (Padded or Leather).

- **Effect:** Once per Scene, when declared the target of an Aggressor action, the wearer may spend 1 Momentum to become **Obscured** (per Iron World's Cover rules) for that single Clash — the attacker suffers Disadvantage, as if striking through smoke, even in the open.
- _Reuses the existing Obscured mechanic rather than inventing a new defensive stat — same logic as Cloak of Still Water reusing Rushed Stealth._

### Relic (1 Locked Stress Attunement + Built-In Drawback)

**The Widow's Needle** (unique dagger) — Not for sale. GM-authored, campaign-specific.
A slim, black dagger that is always slightly warmer than the air around it.
- **Effect:** Functions as a permanent, always-on Vital Strike (ignores Armor value in the Wound Threshold calculation) with no -4 penalty required to use it.
- **The Cost:** Every kill made with the Needle locks 1 additional point of Stress on the wielder that **cannot** be cleared by Grounding, Momentum spend, or a Breather — only a full Religious Pursuit or a Long Rest will do. The blade is hungry, and it remembers who fed it.

___________________________________________________________________

# Currency Standard: 
The primary day-to-day trade currency is the Silver Piece (sp). Copper Pennies (cp) are used by peasants (10 cp = 1 sp). Gold Sovereigns (gs) are held only by nobility and wealthy cartels (1 gs = 20 sp).

_______________________________________________________________________

# Weapons

## Unarmed

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Unarmed (fists/feet/knees and elbows)|0|1H/2H|5 ft Threat|Non-lethal, Sidearm|—|Always available|
|Gauntlet|0|1H|5 ft Threat|Sidearm|2 sp|Common|
|Spiked Gauntlet|0|1H|5 ft Threat|Sidearm, Precise|5 sp|Common|

## Blades

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

## Axes

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Sickle|0|1H|5 ft Threat|Trip|6 sp|Common|
|Hand Axe|2|1H|5 ft Threat / 30 ft Thrown|Brutal, Thrown, Sidearm|8 sp|Common|
|Battleaxe|2|1H|5 ft Threat|Inertia|12 sp|Common|
|Light Pick|2|1H|5 ft Threat|Inertia, Precise|8 sp|Common|
|Heavy Pick|3|1H|5 ft Threat|Inertia, Precise|16 sp|Scarce|
|Greataxe|5|2H|5 ft Threat|Inertia, Cumbersome|40 sp|Scarce|

## Bludgeons

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Club|0|1H|5 ft Threat|Bash|— (improvised, always available)|Common|
|Sap|2|1H|5 ft Threat|non-Lethal, Concealable|3 sp|Common|
|Mace / Bludgeon|2|1H|5 ft Threat|Bash|8 sp|Common|
|Morningstar|2|1H|5 ft Threat|Bash, Precise|12 sp|Common|
|Quarterstaff|2/2|2H|5 ft Threat|Double, Close-Quarters|3 sp|Common|
|Warhammer|3|2H|5 ft Threat|Bash, Sunder|30 sp|Scarce|

## Polearms

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

## Flails 

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Whip|0|1H|10 ft Threat|Reach, Disarm, Trip, non-Lethal|5 sp|Scarce|
|Nunchaku|0|1H|5 ft Threat|Disarm, Concealable|6 sp|Scarce|
|Flail|2|1H|5 ft Threat|Disarm, Trip|16 sp|Scarce|
|Spiked Chain|2|2H|10 ft Threat|Reach, Disarm, Trip, finesse|25 sp|Scarce|
|Heavy Flail|3|2H|5 ft Threat|Disarm, Trip, Precise|35 sp|Scarce|

## Thrown 

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Dart|0|1H|5 ft Threat / 20 ft Thrown|Thrown, Concealable|1 sp (cluster of 3 = 1 Slot)|Common|
|Sling|0|1H|Ranged (Max: Medium / 50 ft)|Sidearm|2 sp|Common|
|Shuriken|0|1H|5 ft Threat / 10 ft Thrown|Thrown, Concealable, Sidearm|8 sp (cluster of 3 = 1 Slot)|Scarce|
|Bolas|0|1H|5 ft Threat / 10 ft Thrown|Thrown, Trip|5 sp|Scarce|
|Net|—|1H|5 ft Threat / 10 ft Thrown|Entangling|20 sp|Scarce|

## Bows

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Blowgun|0|2H|Ranged (Max: Short / 20 ft)|Concealable|5 sp|Common|
|Shortbow|2|2H|Ranged (Max: Long / 120 ft)|Volley|15 sp|Common|
|Longbow|3|2H|Ranged (Max: Extreme / 125+ ft)|Volley|35 sp|Scarce|

## Crossbows

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Hand Crossbow|0|1H|Ranged (Max: Short / 30 ft)|Concealable, Sidearm, Reload|40 sp|Rare|
|Light Crossbow|3|2H|Ranged (Max: Long / 120 ft)|Armor Piercing, Reload|30 sp|Scarce|
|Repeating Heavy Crossbow|3|2H|Ranged (Max: Long / 120 ft)|Volley, Armor-Piercing, Repeating|90 sp|Rare|

## Arcane Focus

|Weapon Name|Power|Grip|Range / Threat|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|---|
|Grimoire|—|1H|—|Repository: Holds your spells. If casting while open, you may spend 1 Momentum to cast a Novice spell without Locking a Stress slot for the first round (Reading it straight off the page).|15 sp|Scarce|
|Mage Staff|—|2H|—|Reach, Bound, grounding rod.|45 sp|Rare|
|Wand|—|1H|—|Conduit, Focus, Sidearm.|35 sp|Rare|

## Weapon Tags

- **Bound:** enables an Arcane caster to cast spells without needing their Grimoire in hand. but it must be on their person. Cast as if the Grimoire is held in one hand.
- **Bash:** If your attack results in a Glancing Hit (Impact < Threshold), it deals +1 additional Dissonant Stress due to blunt force trauma.
- **Brutal:** If the Reactor rolls a Fumble (Natural 2) while defending against this weapon, they take 2 Stress instead of 1.
- **Close-Quarters:** suffers no penalties when In-Fighting.
- **Concealable:** Grants Advantage (3d6 keep 2) on rolls made to hide the weapon on your person.
- **Conduit:** can be used to perform Somatic components. The caster weaves the geometry of the spell using the item itself, meaning their hand does not need to be empty.
- **Cumbersome:** The weapon is heavy and slow to ready. Imposes a -1 penalty on Activation order rolls.
- **Devastating:** A mark of exceptional make — masterwork craft, ancient forging, or magic worked directly into the item — assigned to a specific weapon rather than a weapon category. Enables the weapon to inflict Wounds directly on Scale +3 (Gargantuan) creatures (without it, Strikes against Gargantuan creatures only ever inflict Stress, per the Scale rules in Metal meet Flesh). When targeting a Scale +3 or higher creature, this weapon also ignores that creature's Scale-based Wound Threshold bonus when calculating whether a Strike inflicts a Wound — otherwise a weapon capping out at Power 5 could almost never generate enough Impact to matter against a Gargantuan-scale Wound Threshold. Carries no inherent size, Power, or hands requirement, and grants no bonus against fortifications — a Devastating dagger and a Devastating greatmaul are equally valid. The tag describes what the weapon *is*, not how big it is.
- **finesse:** may use reflex instead of Brawn in clashes.
- **Focus:** Grants +1 to Arcana Clash rolls. If the caster rolls a fumble on a casting check the magic backlash destroys the item, it gains the ruined condition. The caster fails but does not suffer the 1 stress for a fumble.
- **Grounding Rod:** grants Advantage on the Grounding (Wits + Arcana) check to unlock stress slots.
- **Heavy Hitter:** When wielding these weapons, the character does not benefit from "fates bounty". Instead, any natural 6 is treated as a 7.
- **Inertia:** If you win the Clash roll by a High Margin (5+), add +2 Power to the Final Impact.
- **non-Lethal:** strikes with this weapon can only cause Stress regardless of the Impact result, will never spill over into wounds.
- **Precise:** Ignores 1 Point of armour
- **Reach:** Threatens a 10-foot radius (2 grid squares). Forces an opponent with shorter 5-foot weapons to succeed on an opposed Dodge roll to move into their reach. failure stops them at the 10-foot radius.
- **Reload:** After firing, requires an Action to load the next shot.
- **Sidearm:** Can be drawn as a Free Action without penalty.
- **Siege:** Emplaced, crew-served, or vehicle-mounted armament — a ballista, wall gun, cannon, or siege engine — rather than a personal weapon; it isn't carried in Inventory Slots. Like Devastating, it enables inflicting Wounds directly on Scale +3 (Gargantuan) creatures and ignores that creature's Scale-based Wound Threshold bonus when calculating whether a Strike inflicts a Wound; unlike Devastating, it can also damage fortifications and structures.
- **Sunder:** If you inflict a Minor or Major Wound with this weapon, permanently reduce the target's Armor value by 1.
- **Thrown:** Can be hurled using the short range attack band. If used in melee, it retains its 5 ft Threat.
- **Versatile:** can be wielded 1H or 2H. If wielded 2H add 1 to the weapon power.
- **Volley:** Requires two hands and prevents the user from holding a Shield or Grimoire.
- **Armor-Piercing:** Ignores 2 points of the target's Armor Value when calculating Impact — twice Precise's ignore-1.
- **Trip:** As an Aggressor Strike with this weapon, you may forgo Impact on a win to instead knock the target Prone.
- **Disarm:** As an Aggressor Strike with this weapon, you may forgo Impact on a win to force the target to pass a Brawn + Prowess check vs TN 8 or drop what they're holding into an adjacent square.
- **Set:** If this weapon is readied and an enemy voluntarily moves into your Threat Zone, your Strike against them gains a Charge's +2 Clash bonus and tie-break — without the -2 Reactor penalty a real Charge imposes on you.
- **Double:** This two-handed weapon has two striking ends, each with its own Power (listed X/Y). It functions as a built-in Twin-Blade Stance: spend 1 Momentum on a won Clash to immediately follow up with the second Power value as Impact + 1 Stress, without needing a separate Sidearm weapon in your off hand.
- **Repeating:** Holds multiple shots internally; does not require the Reload action between individual shots. Once the magazine is empty, reloading it fully requires a full Action.
- **Entangling:** As an Aggressor action, forgo Impact on a win to instead apply the Anchored condition to the target (identical to the Entangle spell's effect).
(Note on Ranged Weapons: firing a Ranged or Thrown weapon while an enemy is inside your 5-foot Threat Zone imposes Disadvantage on the attack roll).


##  ADVANCED SPECIALIZED WEAPONRY

These variations add specific situational tactical tools to the baseline weapon tables.

#### The Estoc (Tuck)

- Cost: 45 sp | Availability: Scarce
- Stats: Power 2 | 1H | 5 ft Threat
- Tags: Precise, Armor-Piercing
- 2d6 Special Rule: Designed specifically to pass between armor plates. If the Attack roll is a Perfect Form (rolling a natural 3 and 4 on the Clash check), this weapon completely ignores all physical Armor values and structural damage reduction, applying its full Impact raw to the Wound Threshold.

#### The Barbed Spear

- Cost: 25 sp | Availability: Common
- Stats: Power 2 | 1H/2H | 10 ft Threat
- Tags: Reach.
- 2d6 Special Rule: When you win a Clash with this weapon as an attack action, you can forego doing standard Impact damage to execute a Hook. The target is pinned at the tip of your spear; they cannot execute Shift actions until they win an opposed Brawn + Prowess check against you on their activation.

#### The Heavy Arbalest

- Cost: 80 sp | Availability: Rare
- Stats: Power 5 | 2H | Ranged (Max: Long / 120 ft)
- Tags: Armor-Piercing, Cumbersome, Heavy Reload
- 2d6 Special Rule: Requiring a literal windlass to crank. It takes two entire Move Actions to reload this weapon. However, its steel-headed bolts ignore the infantry projectile protections of shields (Cover tags are nullified) and deal +2 Impact against targets with Scale +1 or higher.

## Reserved: Black Powder Ordnance *(placeholder — not designed yet)*

Flagging space for this rather than designing it now. Tentative bucketing, to be revisited:
- **Pistols/hand cannons:** likely slot into the existing Ranged progression alongside Crossbows (Power 2–3 range), possibly trading Reload for a Concealable/Sidearm angle.
- **Wall guns / cannons / siege ordnance:** likely carry **Siege** by default, and are where the still-unbuilt "Siege Engines" subsection belongs — these were always meant to be literal artillery, not a mundane weapon upgrade path.
- No numbers are proposed here; this section exists purely to mark where the category will attach once designed.
________________________________________________________________________

# Armour
|Armor / Shield Name|Value|Type|Tags & Attributes|Cost|Availability|
|---|---|---|---|---|---|
|Padded / Gambeson|+0 Armor|Light|Cushioned|5 sp|Common|
|Leather|+1 Armour|Light|—|12 sp|Common|
|Chain Shirt|+2 Armor|Light|—|70 sp|Scarce|
|Chainmail / Scale|+2 Armor|Medium|Bulky|45 sp|Scarce|
|Breastplate|+3 Armor|Medium|Bulky|120 sp|Rare|
|Plate Armor|+4 Armor|Heavy|Restricted|200 sp (10 gs)|Rare|
|Buckler|2 SV|Shield|Nimble|8 sp|Common|
|Kite / Round Shield|4 SV|Shield|Cover|18 sp|Common|
|Tower Shield|5 SV|Shield|Bulwark, Obstructive|40 sp|Scarce|

## Armour and Shield Tags

- *Bulky:* The weight and noise of the armor make it hard to move gracefully. Imposes a -1 penalty on Athletics and Stealth and Arcana rolls.
- *Bulwark:* The shield's mass lets you root yourself in place. While readied, you cannot be Shoved, knocked Prone, or forced out of your Threat Zone as a result of losing a Clash. Once per Scene, when you lose a Block Clash, you may spend 1 Momentum to reduce that Impact to 0 instead of applying your Shield Value.
- *Cover:* Provides excellent physical obstruction from missiles. Grants Advantage (3d6 Keep 2) to your defense rolls against ranged attacks.
- *Cushioned:* Thick layers of cloth absorb minor impacts. Negates the first point of Dissonant Stress you would take from a Glancing Hit each combat round.
- *Nimble:* Light enough to be actively punched out or used to deflect. Allows the user to roll Reflex instead of Brawn when performing a Block action.
- *Obstructive:* The sheer size of this shield gets in the way of evasive footwork. Imposes a -2 penalty to all Dodge actions.
- *Restricted:* The heavy plates and limited visibility slow your reaction time. You can never be first in the activation order when rolling for activation order. If you roll the highest result, you will slip down to be second, behind the next highest. you will never win activation order ties. Impossible to recreate the intricate movements required in Arcane spell casting, cannot cast Arcane spells whilst wearing. Reduces movement speed by 10ft.

 **CRITICAL UTILITY ARMOR MODIFICATIONS**

Instead of just buying entirely new suits of plate, characters in a low-fantasy setting weld, rivet, and bolt additions to their existing kit.

_Reinforced Riveted Pauldrons (Armor Add-on)_

- Cost: 20 sp | Availability: Common
- Rules: Requires a suit of Medium or Heavy armor to attach. Adds a flat +1 to your Wound Threshold (WT). However, the added shoulder bulk restricts head movement; you suffer a permanent -1 penalty to your activation order rolls.

_Visored Great-Helm (Headpiece Modification)_

- Cost: 35 sp | Availability: Scarce
- Rules: When an enemy achieves an Ace (exploding 6) or a Critical success against you, you can choose to have the helm take the structural brunt. The attack does standard damage instead of critical/bonus damage, but the helm's visor is bent shut. For the remainder of the combat, your actions suffer Disadvantage due to near-total blindness until an action is spent tearing the helm off.

_Oil-Cured Gambeson (Under-layer Layering)_

- Cost: 15 sp | Availability: Common
- Rules: Can be worn under Chainmail or Scale armor. Grants the Cushioned tag (Negates the first point of Dissonant Stress you would take from a Glancing Hit each combat round).

_Armor Spikes (Armor Add-on)_

- Cost: 15 sp | Availability: Scarce
- Rules: When an enemy loses a Grab or Shove Clash against you, they suffer 1 Impact from the spikes.

_Locked Gauntlet (Armor Add-on)_

- Cost: 5 sp | Availability: Common
- Rules: Grants Advantage on Brawn + Prowess checks made to resist being disarmed.

_Shield Spikes (Shield Add-on)_

- Cost: 8 sp | Availability: Common
- Rules: When you win a Shove action using this shield, deal +1 Impact on top of the standard result.


______________________________________________________________________

# Expedition Gear

| Item                                                | Slots    | Cost          | Availability | Notes                                                                                                                                                                                                      |
| --------------------------------------------------- | -------- | ------------- | ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Backpack                                            | 0 (worn) | 3 sp          | Common       | Exempted from Slots like worn armor — it's the frame the Pack lives in, not an item inside it, and grants no bonus capacity.                                                                               |
| Barrel (empty)                                      | 2        | 8 sp          | Common       | Bulky; rigid — costs its Slots even empty (see Section 0b).                                                                                                                                                |
| Basket (empty)                                      | 1        | 1 sp          | Common       | Rigid — costs its Slot even empty.                                                                                                                                                                         |
| Bedroll                                             | 1        | 2 sp          | Common       | —                                                                                                                                                                                                          |
| Bell                                                | 0        | 3 sp          | Common       | —                                                                                                                                                                                                          |
| Blanket, winter                                     | 1        | 3 sp          | Common       | —                                                                                                                                                                                                          |
| Block and tackle                                    | 1        | 12 sp         | Scarce       | Advantage on Athletics checks to lift/hoist loads beyond your own strength.                                                                                                                                |
| Bottle, glass                                       | 0        | 2 sp          | Common       | —                                                                                                                                                                                                          |
| Bucket (empty)                                      | 1        | 2 sp          | Common       | —                                                                                                                                                                                                          |
| Caltrops (bag)                                      | 0        | 4 sp          | Common       | Move Action to scatter across one square. First creature to enter it without noticing (failed Notice vs. your Margin) rolls Reflex + Acrobatics vs TN 8 or takes 1 Stress and half Movement for the round. |
| Candle / Chalk / Firewood / Torch / Tindertwig      | 0        | ~1 cp each    | Common       | Flavor only — light and fuel are tracked by the Community Supply Die during a dungeon crawl. Price these individually only for town/travel bookkeeping.                                                    |
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
| Lamp, common                                        | 0        | 2 sp          | Common       | See Hooded Bullseye Lantern in _Hardware_ (12 sp, Scarce) for the tactical version.                                                                                                                        |
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
| Shovel or spade                                     | 1        | 2 sp          | Common       | —                                                                                                                                                                                                          |
| Spyglass                                            | 1        | 90 sp         | Rare         | Advantage on Notice checks made at Long or Extreme Range.                                                                                                                                                  |
| Tent                                                | 2        | 8 sp          | Common       | —                                                                                                                                                                                                          |
| Water clock                                         | —        | —             | Legendary    | A city fixture, not a carried item. Not normally purchasable by PCs.                                                                                                                                       |
| Waterskin                                           | 0        | 1 sp          | Common       | —                                                                                                                                                                                                          |
| Whetstone                                           | 0        | 1 sp          | Common       | Mundane, feat-free version of the Spit and Twine feat's Patch Job: as a Regroup action, roll Crafting vs TN 8 to ignore the Damaged tag on one weapon for the rest of the encounter.                       |

**TACTICAL EXPEDITION GEAR**

Practical kits that anchor survival and optimize downtime actions.

_Iron Pitons & Sledge (Set of 6)_

- Cost: 5 sp | Availability: Common
- Tactical Rule: During a movement or preparation phase, a player can spend an action to spike a heavy iron door or narrow passageway shut. Enemies attempting to bypass this square or break the door must spend a Full Action and pass a Brawn + Prowess check vs TN 8 to smash the piton out, buying the party vital tactical rounds.

_Field Surgeon Kit_

- Cost: 50 sp | Availability: Rare
- Downtime Rule: Possessing this kit grants a flat +2 bonus to all "Tend to the Flesh" downtime checks. It contains fine bone saws, clean linen sheets, and non-rancid cauterizing irons. Contains enough specialized thread for 6 uses before requiring an acquisition roll to restock.

_Hooded Bullseye Lantern_

- Cost: 12 sp | Availability: Scarce
- Tactical Rule: Illuminates a tight, 30-foot cone directly ahead. Any character standing inside the dark zone outside of this cone has absolute Advantage on stealth. However, if an enemy is caught directly in the beam during a Draw (Initiative phase), they lose any ambush bonuses because their night vision is instantly shattered by the focused beam.

_Holy Symbol_

- **Cost:** 5 sp | **Availability:** Common
- **Rules:** Required to manifest Miracles — per _The Marrow_'s Divine Conduit feat, a Priest must "speak the litany and bear your symbol" to cast. A Symbol bound to a Domain via the Covenant path can never hold a different entity's Miracles (no later switching, per Divine Conduit). 0 Slots — worn/carried, per the Inventory micro-item exemption.

_Holy Symbol, Silver_

- **Cost:** 15 sp | **Availability:** Scarce
- **Rules:** A cosmetic/prestige upgrade over the standard Holy Symbol above — **no mechanical bonus.** 

___________________________________________________________________
## ALCHEMICAL WARES & FIELD CONSUMABLES

Alchemical supplies are highly volatile, unstable, and often act as a mechanical double-edged sword.

| Item Name            | Cost  | Avail.  | Slots | Mechanical 2d6 & Resource Output                                                                                                                                                                                                                                                                        |
| -------------------- | ----- | ------- | ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Grave-Dust Poultice  | 8 sp  | Common  | 1/3   | Field Medicine: Used as a Full Action. Instantly clears 1 filled Wound slot. However, due to the filth of the compounds, the target must roll a Brawn check vs TN 8. On a failure, they take 1 point of Dissonant Stress from spreading infection.                                                    |
| Black-Root Draught   | 15 sp | Scarce  | 1/3   | Caster Exhaustion: Used as a Move Action. Instantly unlocks 2 Locked Stress slots for an Arcane caster. However, it drains physical stamina; at the absolute end of the current scene, the character automatically fills 1 physical Wound slot from systemic toxicity.                                  |
| Witch-Spur Salve     | 12 sp | Scarce  | 1/3   | Nerve Numbing: Rubbed into the temples as a Move Action. Grants absolute immunity to the Terrifying trait and psychological panic checks for the next scene. The Catch: It instantly fills and locks 1 Dissonant Stress slot for the duration of the scene, reducing the user's maximum stress ceiling. |
| Vitriol Solvent      | 25 sp | Rare    | 1/3   | Armor Melt: Applied to a bladed or Armour-piercing weapon as a Full Action. For the next 3 combat rounds, the weapon gains the Sunder tag. If a strike hits a target with the Plated trait, that trait is suppressed for the rest of the encounter.                                                     |
| Naphtha Fire-Flask   | 30 sp | Rare1/3 |       | Zone Control: Can be thrown (Ranged, Max 30ft). Shatters upon a square/zone. Anyone occupying or entering the zone during the next 3 rounds must pass a Reflex + Dodge check vs TN 8 or take a flat 2 Impact damage and 1 Dissonant Stress from chemical burns.                                         |
| Arcane Salts         | 8sp   | common  | 1/3   | A violently harsh alchemical stimulant. Using it as a Move Action instantly unlocks 1 Locked Stress slot, but immediately inflicts 1 normal Dissonant Stress on the user from the chemical shock..                                                                                                      |
| Philter of Focus     | 20sp  | scarce  | 1/3   | Grants **Advantage** on the next Grounding check performed in the scene.                                                                                                                                                                                                                                |
| Corpse-Weed Resin    | 6 sp  | Common  | 1/3   | Lethargy: For the first combat encounter after the Breather, the user cannot generate Momentum, as their nervous system is too dulled. Clears 1 Locked Stress. Can be smoked during a 30-minute Breather.                                                                                               |
| Marrow-Glass Ampoule | 40 sp | Rare    | 1/3   | The Crash: At the end of the combat encounter, the user immediately suffers 1 Minor physical Wound from the violent chemical shock to their heart. Instant Override: Can be injected mid-combat as a Free Reaction. Converts all currently Locked Stress back into standard Dissonant Stress.           |
| Surgical Spirits     | 10 sp | Common  | 1/3   | Tremors: The user permanently suffers Disadvantage on any Brawn or Arcana rolls requiring fine motor skills until they return to a town(long rest/pursuit) to fully detox. Taken during a Breather. Numbness allows the user to clear 2 Locked Stress.                                                |
| Antitoxin (vial)     | 20 sp | Scarce  | 0     | Drunk as a Free Action before a Poison check. Grants Advantage on the next Brawn check made to resist the Poisoned condition this scene.                                                                                                                                                              |
| Everburning Torch    | 40 sp | Rare    | 1     | Permanent arcane light source. Never consumes a Supply Die step.                                                                                                                                                                                                                                        |
| Sunrod               | 5 sp  | Common  | 0     | As Everburning Torch, but burns out at scene's end.                                                                                                                                                                                                                                                     |
| Holy Water (flask)   | 15 sp | Scarce  | 0     | Thrown as a Ranged (Short) attack; only affects targets with the Undead or Void-Touched tag. On a hit, deals 1 Impact ignoring Armor.                                                                                                                                                                   |
| Smokestick           | 15 sp | Scarce  | 0     | Snapped as a Move Action. Creates a 5 ft. radius of Heavily Obscured terrain for 1 round (per the Environmental cover rules in _Iron World_).                                                                                                                                                           |
| Tanglefoot Bag       | 20 sp | Scarce  | 0     | Thrown (Short Range). On a hit, the target is Anchored until they spend a full Aggressor action tearing free — mechanically identical to the Entangle spell's Margin 1–2 result.                                                                                                                        |
| Thunderstone         | 20 sp | Scarce  | 0     | Thrown; explodes in a 10 ft. radius. Everyone caught rolls Brawn vs TN 8 or gains the Distracted condition (-1 to rolls until their next Activation).                                                                                                                                                 |

## Tools & Skill Kits

| Item                           | Slots                                | Cost   | Availability     | Effect                                                                                                                                                                                                                                                                           |
| ------------------------------ | ------------------------------------ | ------ | ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Alchemist's Lab                | — (stationary facility, not carried) | 150 sp | Rare, City-tier+ | Required for reliable Hammer & Forge-style Crafting of Alchemical Wares outside of desperate battlefield chemistry (the Scrounger's Volatile Concoction feat already covers the field-expedient version).                                                                        |
| Artisan's tools (per trade)    | 1                                    | 5 sp   | Common           | Required to attempt a Crafting check in that trade without Disadvantage.                                                                                                                                                                                                         |
| Artisan's tools, masterwork    | 1                                    | 20 sp  | Scarce           | +1 flat bonus to that trade's Crafting check (same logic as Masterwork Quality weapons/armor).                                                                                                                                                                                   |
| Climber's Kit                  | 1                                    | 25 sp  | Scarce           | Advantage on Athletics checks made specifically to climb.                                                                                                                                                                                                                        |
| Disguise Kit                   | 1                                    | 15 sp  | Scarce           | Grants Advantage on the unopposed Wits + Arcana-equivalent roll for a mundane disguise (resolved exactly like the Disguise spell's Illusion check — Notice vs. your Margin to see through it).                                                                                   |
| Healer's Kit                   | 1                                    | 15 sp  | Common           | Cheaper cousin of the Field Surgeon's Kit: +1 (not +2) to Tend to the Flesh checks, and holds only 2 uses before restocking.                                                                                                                                                     |
| Magnifying Glass               | 0                                    | 30 sp  | Scarce           | Advantage on Notice checks made on small or fine details (forgeries, tiny inscriptions).                                                                                                                                                                                         |
| Musical Instrument, common     | 1                                    | 5 sp   | Common           | Flavor.                                                                                                                                                                                                                                                                          |
| Musical Instrument, masterwork | 1                                    | 40 sp  | Scarce           | +1 flat bonus to an Influence check made while performing with it.                                                                                                                                                                                                               |
| Scale, merchant's              | 0                                    | 3 sp   | Common           | Advantage on Insight/Notice checks to catch a rigged deal or counterfeit coin.                                                                                                                                                                                                   |
| Spell Component Pouch          | —                                    | —      | —                | **Not needed.** Grimoire/Wand/Staff already fill the Arcane Focus role; a separate component pouch would be a redundant subsystem.                                                                                                                                               |
| Spellbook, wizard's (blank)    | —                                    | —      | —                | This is just an unfilled Grimoire (15 sp, Scarce, already in _Hardware_) — no separate item.                                                                                                                                                                                     |
| Thieves' Tools                 | 1                                    | 20 sp  | Scarce           | Required to attempt a Thievery check against locks/mechanisms without Disadvantage.                                                                                                                                                                                              |
| Thieves' Tools, masterwork     | 1                                    | 60 sp  | Rare             | As above, +1 flat bonus to the check.                                                                                                                                                                                                                                            |
| Holy Symbol, silver            | 0                                    | 15 sp  | Scarce           | Cosmetic/prestige upgrade over the standard Holy Symbol (5 sp) only — **no mechanical bonus.** Faith runs on the Tithe of Will, not item bonuses; don't let this quietly become a "+1 Faith" item later, or it breaks parity with Domains that have no silver-symbol equivalent. |

## Clothing
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

## Food, Drink & Lodging
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

## Mounts, Tack & Barding
_Combat-trained mounts don't panic from ordinary Fear-Inducing effects (they're bred/drilled for it) but are not immune to Terrifying-tier effects._

| Mount                       | Scale      | Move         | Wound Threshold  | Stress Limit | Cost           | Availability |
| --------------------------- | ---------- | ------------ | ---------------- | ------------ | -------------- | ------------ |
| Donkey / Mule               | Small (-1) | 20 ft (4 sq) | 3                | 3            | 12 sp          | Common       |
| Pony                        | Small (-1) | 25 ft (5 sq) | 3                | 3            | 20 sp          | Common       |
| Guard Dog                   | Small (-1) | 40 ft (8 sq) | 3                | 3            | 15 sp          | Common       |
| Light Horse                 | Large (+1) | 40 ft (8 sq) | 6                | 4            | 60 sp          | Scarce       |
| Light Horse, combat trained | Large (+1) | 40 ft (8 sq) | 8 _(+1 Brawn)_ | 4            | 90 sp          | Scarce       |
| Heavy Horse (warhorse)      | Large (+1) | 35 ft (7 sq) | 8 _(+1 Brawn)_ | 4            | 150 sp         | Rare         |
| Heavy Horse, combat trained | Large (+1) | 35 ft (7 sq) | 8                | 4            | 220 sp (11 gs) | Rare         |

**Tack:**
**Barding:** priced as **2× the base armor's sp cost**, reflecting the extra material a Large-scale mount requires. A barded mount carries the same tag penalties as a rider would (Bulky armor still imposes its usual -1 penalties). Example: Chainmail barding = 90 sp; Plate barding = 400 sp (20 gs), Rare/exotic, warhorse-only.

| Item               | Cost  | Availability | Notes                                                                                                                                                          |
| ------------------ | ----- | ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Bit and bridle     | 3 sp  | Common       | —                                                                                                                                                              |
| Riding saddle      | 8 sp  | Common       | —                                                                                                                                                              |
| Pack saddle        | 5 sp  | Common       | —                                                                                                                                                              |
| Military saddle    | 15 sp | Scarce       | Advantage on the Ride skill check to stay mounted when your mount is Shoved, spooked, or knocked.                                                              |
| Saddlebags         | 6 sp  | Common       | Grants 2 additional Pack-equivalent Slots that live on the mount rather than the rider — still requires a Regroup-equivalent action to dig through mid-combat. |
| Feed (per day)     | 3 cp  | Common       | —                                                                                                                                                              |
| Stabling (per day) | 1 sp  | Common       | —                                                                                                                                                              |

## Transport
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

## Spellcasting, Miracles & Hired Services

| Service             | Cost      | Notes |
| ------------------- | --------- | ----- |
| Coach cab           | 3 cp/mile | —     |
| Messenger           | 2 cp/mile | —     |
| Road or gate toll   | 1 cp      | —     |
| Ship's passage      | 1 sp/mile | —     |
| Hireling, untrained | 5 cp/day  | —     |
| Hireling, trained   | 3 sp/day  | —     |

| Spell/Miracle Level | Price      |
| ------------------- | ---------- |
| Cantrip             | 15 sp      |
| Novice              | 30 sp      |
| Adept               | 60 sp      |
| Master              | 120–150 sp |
_Resurrection is explicitly excluded from this table — at 8 Locked Stress cost to the caster and a Master Miracle to begin with, it should never be a walk-up shop purchase. Treat it as Commission-gated, if available at all._