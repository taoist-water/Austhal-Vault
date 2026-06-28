# The Universal Spell List — Rebuilt

This replaces the SWADE-derived draft. Every Arcana entry now resolves through the Margin Scaler — no flat Stress taxes. Standard convention used throughout, to avoid repeating it 36 times: **on an unopposed roll, a Failure (<8) means the spell fails and the caster takes 1 Dissonant Stress** — that default is only restated below where a spell deviates from it. Margin complications and backfires are always **Dissonant** Stress; only the ongoing cost of a Sustain spell is **Locked** Stress, per the Iron Core definition ("the mathematical heat of casting").

Two corrections from the last sorting pass: *Invisibility* and *Light/Darkness* were missing from the triage entirely. Invisibility joins Shadow Sorcery below (it fits the concealment identity cleanly); Light/Darkness stays Common, since half its effect is the literal opposite of Shadow Sorcery's theme.

**Spell Power update:** Bolt, Blast, and Burst below now use the **Spell Power** formula (`Impact = Clash Margin + Spell Power`) instead of a flat Impact number per tier — see the companion patch file (Spell_Power_Patch.md) for the full rule and why it was necessary. This formula and the rule definition belongs in Embracing the Abyss alongside the rest of the Arcane Clash mechanics; it's used here but defined there.

---

# PART 1 — Common Arcane Tier
*Available to any Arcanist regardless of chosen Paradigm. Standard DP cost. Never benefits from Paradigm Mastery.*

### Arcane Protection (Common)
The air around the target thickens into a dull, shimmering haze, dampening the resonance of hostile sorcery.

- **Level:** Novice
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation (to raise) / Reactor (to use)
- **Duration:** Sustain — Lock 1 Stress to maintain

**The Margin Scaler:**
- Margin 0–2 (Messy): The ward holds, but the caster takes 1 Dissonant Stress from the backlash.
- Margin 3–4 (Clean): The ward holds. Hostile spells targeting the protected character suffer Disadvantage on their casting roll.
- Margin 5+ (Exceptional): As Clean, and the ward gains SV 2 against the next hostile spell's Impact.

**Special Interactions:** As a Reactor action against an incoming hostile spell, the protected character may Block using Wits + Arcana instead of their normal Reactor stat.

---

### Bolt (Common)
A concentrated bolt of raw energy streaks from the caster's hand toward a single foe. This is the floor every Arcanist stands on — Pyromancy and Shamanism both build sharper, paradigm-exclusive versions of this same idea.

- **Level:** Novice
- **Resolution:** Arcane Clash, Wits + Arcana vs. Target's Defense
- **Spell Power:** 1
- **Target/Range:** One character, Medium Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Impact = Margin + 1 (Spell Power).
- Margin 3+ (Clean): As above, no complication.

---

### Blast (Common)
The caster hurls a ball of energy that explodes on impact, catching multiple foes in its radius.

- **Level:** Adept
- **Resolution:** Arcane Clash, Wits + Arcana vs. each target's Defense (caster rolls once; every target in the radius defends)
- **Spell Power:** 2
- **Target/Range:** A point within Medium Range, 10ft radius
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Impact = Margin + 2 (Spell Power) to every target who loses.
- Margin 3+ (Clean): As above, and the blast ignores the first point of Armor on anyone caught at the radius's center.

---

### Barrier (Common)
The caster conjures a physical or energetic wall to block passage and protect allies.

- **Level:** Adept
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** A 10ft line within Short Range
- **Action Type:** Activation
- **Duration:** Until destroyed

**The Margin Scaler:**
- Margin 0–2 (Messy): The barrier forms (Full Cover, Wound Threshold 8, 3 Wound Slots before it collapses), but the caster takes 1 Dissonant Stress from the strain.
- Margin 3–4 (Clean): The barrier forms exactly as described.
- Margin 5+ (Exceptional): The barrier's Wound Threshold increases to 10.

---

### Blind (Common)
A flash of light, a cloud of soot, or a veil of shadow robs the target of sight.

- **Level:** Novice
- **Resolution:** Arcane Clash, Wits + Arcana vs. Target's Dodge (Reflex + Acrobatics)
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Target is Blinded for 1 round.
- Margin 3+ (Clean): Target is Blinded for 3 rounds.

---

### Burst (Common)
A cone of raw elemental energy erupts from the caster's hands.

- **Level:** Novice
- **Resolution:** Arcane Clash, Wits + Arcana vs. each target's Defense
- **Spell Power:** 1
- **Target/Range:** 10ft cone
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Impact = Margin + 1 (Spell Power) to every target who loses.
- Margin 3+ (Clean): As above, no complication.

---

### Damage Field (Common)
Energy lashes out from the caster's skin, punishing any who approach or strike them.

- **Level:** Adept
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** Self, 5ft radius
- **Action Type:** Activation
- **Duration:** Sustain — Lock 1 Stress to maintain

**The Margin Scaler:**
- Margin 0–2 (Messy): The field holds; any character ending their turn adjacent to the caster, or hitting them in melee, suffers 1 Impact. The caster also takes 1 Dissonant Stress from the initial surge.
- Margin 3–4 (Clean): As above, no self-cost.
- Margin 5+ (Exceptional): Impact increases to 2.

---

### Darksight (Common)
The caster's eyes take on a predatory sheen, piercing the deepest gloom.

- **Level:** Novice
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): Recipient ignores penalties for Dim or Dark illumination, but suffers 1 Dissonant Stress as their eyes adjust violently.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Exceptional): The recipient can also detect invisible entities and active spell effects within 30 feet.

---

### Dispel (Common)
With a sharp gesture and a word of negation, the caster severs the threads of a nearby enchantment.

- **Level:** Adept
- **Resolution:** Opposed Wits + Arcana vs. the original caster's recorded casting roll
- **Target/Range:** One active spell effect, Short Range
- **Action Type:** Activation or Reactor

**The Margin Scaler:**
- Margin 1–2: The targeted spell is suppressed for 1 round.
- Margin 3+ (Clean): The targeted spell ends immediately.

---

### Divination (Common)
The caster enters a trance, seeking answers from the echoes of the world.

- **Level:** Master
- **Resolution:** Unopposed Wits + Arcana vs. TN 8 (requires 1 minute of concentration)
- **Target/Range:** Self
- **Action Type:** Activation
- **Duration:** Instantaneous

**The Margin Scaler:**
- Margin 0–2 (Messy): The GM provides a cryptic but useful vision; the caster takes 1 Dissonant Stress from the mental strain.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Exceptional): The vision is lucid. The caster gains Advantage on the next Notice or Investigation check related to it, for the rest of the scene.

---

### Entangle (Common)
The ground erupts with grasping vines, shadow-tendrils, or chains.

- **Level:** Novice
- **Resolution:** Arcane Clash, Wits + Arcana vs. Target's Dodge
- **Target/Range:** One character or 10ft area, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Target is Anchored. They lose the Dodge action until they break free (a full Aggressor action, or 1 Momentum).
- Margin 3+ (Clean): As above, and the bindings are thorned — the target suffers 1 Dissonant Stress at the start of each turn they remain Anchored.

*(This reuses Anchored rather than inventing a new condition — Anchored already does everything "Restrained" was going to do.)*

---

### Farsight (Common)
The caster's vision stretches across the horizon with impossible clarity.

- **Level:** Adept
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): Recipient ignores Range penalties on ranged attacks and gains Advantage on sight-based Notice checks, but takes 1 Dissonant Stress from the strain of the working.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Exceptional): The recipient can also see through up to 5 feet of solid, non-magical material.

---

### Environmental Shield (Common)
A thin membrane of energy stabilizes the air and temperature around the recipient.

- **Level:** Novice
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): The recipient ignores Stress and penalties from extreme environmental hazards (per the Iron World Hazard Check rules) for the scene, but the caster takes 1 Dissonant Stress raising it.
- Margin 3–4 (Clean): As above, no cost. The recipient's Wound Threshold is also treated as +2 higher specifically against environmental Direct Wounds (lava, freezing water, acid).
- Margin 5+ (Exceptional): The Wound Threshold bonus increases to +4.

---

### Havoc (Common)
A concussive wave of force throws enemies into disarray.

- **Level:** Novice
- **Resolution:** Arcane Clash, Wits + Arcana vs. each target's Prowess + Athletics or Reflex + Acrobatics
- **Target/Range:** 10ft radius, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Target is pushed 5 feet and suffers 1 Dissonant Stress.
- Margin 3+ (Clean): Target is pushed 10 feet, knocked Prone, and suffers 1 Dissonant Stress.

---

### Illusion (Common)
Light and sound are woven into a convincing facade.

- **Level:** Novice
- **Resolution:** Unopposed Wits + Arcana vs. TN 8. Anyone inspecting it rolls Wits + Notice vs. the caster's original Margin to see through it.
- **Target/Range:** 10ft area, Short Range
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): The illusion forms, but the caster takes 1 Dissonant Stress from holding the image steady.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Exceptional): The illusion is "True" — it includes scent and resists touch — and cannot be seen through except by physically disrupting it.

---

### Elemental Manipulation (Common)
Minor feats of elemental control — lighting a candle, cooling a drink, kicking up dust.

- **Level:** Cantrip
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** 10ft radius, Short Range
- **Action Type:** Activation

**The Margin Scaler:**
- Margin 0–4: A single harmless elemental effect occurs, granting Advantage on one relevant skill check this scene.
- Margin 5+ (Exceptional): The effect sustains itself for the rest of the scene without further concentration.

---

### Mind Link (Common)
A telepathic bridge forms between the caster and their allies.

- **Level:** Novice
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** Self and up to [Wits] allies, anywhere in the same Scene
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–4: Linked characters communicate telepathically for the scene and gain Advantage on group Activation Order rolls while in line of sight of one another.
- Margin 5+ (Exceptional): Linked allies may also share their Momentum bank with one another for the scene.

---

### Smite (Common)
The caster imbues a weapon with crackling energy or holy light.

- **Level:** Novice
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** One weapon, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): Weapon's Power increases by +1; the wielder takes 1 Dissonant Stress from the rough working.
- Margin 3–4 (Clean): Weapon's Power increases by +2.
- Margin 5+ (Exceptional): As Clean, and the weapon gains the Precise tag for the scene (per Hardware: ignores 1 point of Armor).

---

### Warrior's Gift (Common)
Echoes of ancient battles flow into the recipient, granting mastery they have not earned.

- **Level:** Adept
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): Recipient gains one Martial weapon tag they don't already have (e.g., Cleave, Sunder, Brutal); they take 1 Dissonant Stress as the borrowed memory settles violently.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Exceptional): Recipient gains two tags instead of one.

---

### Light/Darkness (Common)
The caster either ignites a beacon of radiance or conjures a void that swallows sight.

- **Level:** Novice
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** 10ft radius or one object, Short Range
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): The chosen effect (Light or Darkness) manifests at half radius.
- Margin 3–4 (Clean): Full 10ft radius. If Darkness, creatures inside suffer Disadvantage on Notice and Attack rolls unless they have Darksight.
- Margin 5+ (Exceptional): Radius doubles to 20ft.

---

# PART 2 — Paradigm-Exclusive Additions
*Each entry below joins one Paradigm's existing 4-spell list as a 5th or 6th signature spell. In-Paradigm casters get the standard DP cost and Paradigm Mastery (a Messy Success resolves as Clean). Off-Paradigm casters can still learn these at double DP cost, with neither benefit.*

## Alchemy and Transmutation — +3

### Boost/Lower Trait
The caster reaches into a body's fundamental rhythm, quickening it or grinding it to a crawl.

- **Level:** Novice
- **Resolution:** Arcane Clash, Wits + Arcana vs. Target's Will + Resolve (if unwilling) — unopposed vs. TN 8 if willing
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor (unwilling) or Activation (willing)
- **Duration:** Sustain — Lock 1 Stress to maintain

**The Margin Scaler:**
- Margin 1–2 / 0–2 (Messy): Target gains a +1 (Boost) or -1 (Lower) modifier to one chosen Attribute.
- Margin 3+ / 3–4 (Clean): As above, with no complication.
- Margin 5+ (Exceptional, unopposed only): Magnitude increases to +/-2.

**Special Interactions:** A character can only have one Boost or Lower effect active at a time; a second casting replaces the first.

### Growth/Shrink
The target's physical dimensions warp, swelling to monstrous proportions or collapsing into a diminutive one.

- **Level:** Adept
- **Resolution:** Arcane Clash, Wits + Arcana vs. Target's Will + Resolve (if unwilling) — unopposed vs. TN 8 if willing
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor or Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 1–2 / 0–2 (Messy): Target's Scale shifts by 1 step (per the existing Scale rules — Growth: +2 WT, Advantage on Prowess shoving/grappling, Disadvantage on Stealth; Shrink: -1 WT, Advantage on Stealth, Disadvantage on Prowess).
- Margin 3+ / 3–4 (Clean): As above, no complication.
- Margin 5+ (Exceptional, unopposed only): The shift is extreme — Scale +/-2 instead of 1.

### Burrow
The caster or a chosen ally melts into the earth, moving through soil and stone like water.

- **Level:** Novice
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): Target gains Earth Glide (move through earth at normal Move) and Total Cover from surface attacks while burrowed, but cannot see the surface; the working leaves them disoriented for 1 Dissonant Stress.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Exceptional): Emerging to attack grants Advantage on the first Strike roll of that turn.

---

## Shamanism — +1

### Beast Friend
The caster's spirit resonates with the natural world, commanding the loyalty of beasts.

- **Level:** Novice
- **Resolution:** Arcane Clash, Wits + Arcana vs. the beast's Will + Resolve
- **Target/Range:** One animal, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: The beast becomes an ally for the scene.
- Margin 3+ (Clean): As above, and the caster can communicate telepathically with it and see through its eyes for the scene.

---

## Shadow Sorcery — +3
*Invisibility joins here as the correction noted above — it's a natural extension of Flicker-Step's "ultimate escape button" identity.*

### Deflection
Invisible currents of air or shifting shadows cause incoming attacks to veer off course.

- **Level:** Novice
- **Resolution:** Unopposed Wits + Arcana vs. TN 8 to raise
- **Target/Range:** Self or one ally, Short Range
- **Action Type:** Activation / Reactor
- **Duration:** Sustain — Lock 1 Stress to maintain

**The Margin Scaler:**
- Margin 0–2 (Messy): Attacks targeting the protected character suffer a -2 penalty to their Clash; caster takes 1 Dissonant Stress raising it.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Exceptional): Penalty becomes Disadvantage instead of -2.

**Special Interactions:** As a Reactor action against an incoming Strike, roll 2d6 + Wits + Arcana — win, take no Impact; lose, take full Impact.

### Disguise
Magical energy warps the caster's features and voice to match another.

- **Level:** Adept
- **Resolution:** Unopposed Wits + Arcana vs. TN 8. Anyone suspicious rolls Wits + Notice vs. the caster's Margin to see through it.
- **Target/Range:** Self
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): The disguise holds; caster takes 1 Dissonant Stress from maintaining the false face under scrutiny.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Exceptional): The veil extends to up to three allies within Short Range.

### Invisibility
The target fades from view, replaced by the colors and textures of whatever lies behind them.

- **Level:** Adept
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene, or until broken

**The Margin Scaler:**
- Margin 0–2 (Messy): Target is invisible; attackers suffer Disadvantage targeting them, and they gain Advantage on Stealth. The spell drops the instant they attack or cast a spell. Caster takes 1 Dissonant Stress from the unraveling effort.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Exceptional): The target remains invisible even after attacking — attacking only reveals their general position, removing Disadvantage from attackers for 1 round rather than dropping the spell outright.

---

## Demonology and Void Magic — +1

### Fear
The caster whispers a truth from the outer dark, projecting pure existential dread.

- **Level:** Novice
- **Resolution:** Arcane Clash, Wits + Arcana vs. Target's Will + Resolve
- **Target/Range:** One character or 10ft area, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Target suffers 2 Dissonant Stress and must spend their next Activation moving away from the caster at maximum speed.
- Margin 3+ (Clean): As above, and if it's a Fodder-tier enemy, they immediately Rout (per the NPC Stress rules) rather than just fleeing.

---

## Astromancy — +1

### Fly
Gravity loses its grip as the target begins to drift, then soar. The escalation of Weightless Step's gravity-defiance.

- **Level:** Master
- **Resolution:** Unopposed Wits + Arcana vs. TN 8
- **Target/Range:** Self or one ally, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): Target gains a Flying Move equal to their land Move and can hover; the working leaves them nauseated for 1 Dissonant Stress.
- Margin 3–4 (Clean): As above, no cost. While airborne, they also gain Advantage on Reflex checks to dodge ground-based or non-flying melee attacks.
- Margin 5+ (Exceptional): Flying Move doubles for the scene.

---

## Witch Magic and Hedge Craft — +1

### Confusion
Whispers of madness scramble the target's thoughts.

- **Level:** Novice
- **Resolution:** Arcane Clash, Wits + Arcana vs. Target's Will + Resolve
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Target suffers Disadvantage on their next Activation Order roll.
- Margin 3+ (Clean): As above, and the target also suffers 1 Dissonant Stress as the curse roots.

---

## Necromancy — +3

### Drain Stress
The caster reaches into a mind, unraveling focus and siphoning spiritual reserve — Marrow Siphon's thesis turned outward onto an enemy.

- **Level:** Master
- **Resolution:** Arcane Clash, Wits + Arcana vs. Target's Will + Resolve
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Target gains 2 Dissonant Stress.
- Margin 3+ (Clean): Target gains 3 Dissonant Stress, and the caster clears 1 of their own Dissonant Stress as the siphoned focus settles.

### Zombie
Dark energy reanimates the dead, forcing cold flesh to serve the living.

- **Level:** Master
- **Resolution:** Unopposed Wits + Arcana vs. TN 8 (requires a corpse within reach)
- **Target/Range:** One corpse, touch
- **Action Type:** Activation
- **Duration:** Scene

**The Margin Scaler:**
- Margin 0–2 (Messy): The corpse rises as an NPC Undead under the caster's control for the scene (Wound Threshold 6, no Stress Limit); the working costs the caster 1 Dissonant Stress.
- Margin 3–4 (Clean): As above, no cost.
- Margin 5+ (Exceptional): The caster may Lock 5 Stress instead of letting the spell end — doing so makes the servant permanent until destroyed or released.

### Puppet
The caster seizes control of the target's motor functions, turning a foe into a marionette.

- **Level:** Master
- **Resolution:** Arcane Clash, Wits + Arcana vs. Target's Will + Resolve
- **Target/Range:** One character, Short Range
- **Action Type:** Aggressor

**The Margin Scaler:**
- Margin 1–2: Caster controls the target's next Activation. The target cannot be forced to directly kill themselves, but can be forced to attack allies or drop their guard.
- Margin 3+ (Clean): As above, and control extends for 1 additional round.

---

# PART 3 — Faith Reassignments
*These three move out of the Arcana structure entirely and into the Domain framework. Cost is the Tithe of Will's flat Locked Stress, per the established Faith chassis — paid on Pass and Fail alike, never on a Margin Scaler.*

### Healing / Stabilize (Common Miracle)
A litany murmured over torn flesh, asking permission to undo what was done. Available to every Priest regardless of Domain — this is the spell several Domain Tags already assumed existed.

- **Level:** Novice Miracle
- **Resolution:** Tithe of Will — Will + Faith vs. TN 8
- **Cost:** 2 Locked Stress
- **Target/Range:** Touch
- **Action Type:** Aggressor

**The Tithe Ladder:**
- Pass: Clears 1 Wound Slot. If the target is Incapacitated, also Stabilizes them and prevents further death checks.
- Fail: As Pass — the Miracle still occurs — and the GM gains 1 Threat.
- Snake Eyes: The Wound clears, but convert this Miracle's Locked Stress cost into an equal number of direct Wounds on the Priest, per the Toll in Flesh rule.

**Special Interactions:** A character cannot benefit from a second Healing-type Miracle in the same Scene. (This should be added to Iron Core's Golden Rules directly, rather than re-stated on every healing effect that comes along later.)

### Banish (Domain of Law — exclusive)
The caster marks an extra-planar entity with a sigil of rejection, forcing it back to its native realm. Locked to the Domain of Law — it's the mechanical teeth behind Smite Corruption's anti-Undead/Daemon/Mutant theme.

- **Level:** Master Miracle
- **Resolution:** Tithe of Will — Will + Faith vs. TN 8, opposed by the target's Will + Resolve
- **Cost:** 3 Locked Stress
- **Target/Range:** One supernatural entity, Short Range
- **Action Type:** Aggressor

**The Tithe Ladder:**
- Pass: If the Priest also wins the opposed roll, the target is stunned and suffers 3 Stress. If this exceeds the target's Stress Limit, it is immediately banished (Incapacitated). If the Priest loses the opposed roll, the Miracle still occurs but produces no effect beyond a flash of light — the entity resists.
- Fail: As Pass, and the GM gains 1 Threat.
- Snake Eyes: Convert the Locked Stress cost into direct Wounds on the Priest, per the Toll in Flesh rule, regardless of whether the banishment succeeded.

### Resurrection (Domain of Mercy & Healing — exclusive)
The most profound and taxing of all Miracles — reaching into the void to pull a soul back to its broken vessel. Locked to the Domain of Mercy & Healing: only a Domain built on absorbing someone else's agony as your own (per Pure Martyrdom) earns a cost this absolute.

- **Level:** Master Miracle
- **Resolution:** Tithe of Will — Will + Faith vs. TN 8 (requires a full hour of ritual; target must have died within 24 hours)
- **Cost:** 8 Locked Stress
- **Target/Range:** Touch
- **Action Type:** Activation

**The Tithe Ladder:**
- Pass: The target returns to life with 3 Wounds and maximum Stress. The Priest pays the Locked Stress cost — this will almost certainly exceed their Stress Limit, converting the excess into Wounds per the Death Spiral rule. This Miracle is built to cost the caster something severe, not "likely" to — say so plainly to the table before they commit.
- Fail: As Pass, and the GM gains 1 Threat.
- Snake Eyes: Convert the entire Locked Stress cost into direct Wounds, per the Toll in Flesh rule — at 8 points, this is unsurvivable for a Priest who isn't already braced for it.

**Special Interactions:** Soul Scar — the resurrected character permanently loses 1 point of Will as the price of their return.

---

# Summary Table

| Spell | Tier | Level |
|---|---|---|
| Arcane Protection | Common | Novice |
| Bolt | Common | Novice |
| Blast | Common | Adept |
| Barrier | Common | Adept |
| Blind | Common | Novice |
| Burst | Common | Novice |
| Damage Field | Common | Adept |
| Darksight | Common | Novice |
| Dispel | Common | Adept |
| Divination | Common | Master |
| Entangle | Common | Novice |
| Farsight | Common | Adept |
| Environmental Shield | Common | Novice |
| Havoc | Common | Novice |
| Illusion | Common | Novice |
| Elemental Manipulation | Common | Cantrip |
| Mind Link | Common | Novice |
| Smite | Common | Novice |
| Warrior's Gift | Common | Adept |
| Light/Darkness | Common | Novice |
| Boost/Lower Trait | Alchemy and Transmutation | Novice |
| Growth/Shrink | Alchemy and Transmutation | Adept |
| Burrow | Alchemy and Transmutation | Novice |
| Beast Friend | Shamanism | Novice |
| Deflection | Shadow Sorcery | Novice |
| Disguise | Shadow Sorcery | Adept |
| Invisibility | Shadow Sorcery | Adept |
| Fear | Demonology and Void Magic | Novice |
| Fly | Astromancy | Master |
| Confusion | Witch Magic and Hedge Craft | Novice |
| Drain Stress | Necromancy | Master |
| Zombie | Necromancy | Master |
| Puppet | Necromancy | Master |
| Healing/Stabilize | Faith — Common Miracle | Novice |
| Banish | Faith — Domain of Law | Master |
| Resurrection | Faith — Domain of Mercy & Healing | Master |
