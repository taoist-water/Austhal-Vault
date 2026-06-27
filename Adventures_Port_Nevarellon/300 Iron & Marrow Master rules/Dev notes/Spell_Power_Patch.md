# Spell Power Patch — Fixing the Wound Threshold Floor Problem

## The Problem, Concretely

Every Arcane Clash combat spell currently deals a **flat** Impact number per Margin tier, completely decoupled from how well the Clash was actually won — unlike weapons, where `Impact = (Winner Roll − Loser Roll) + Weapon Power` scales naturally with the margin. Wound Threshold has a floor of 4 (`4 + Prowess + Armor + Species + Scale`). The result: **Furnace Lance**, the hardest-hitting spell in the game, caps at 4 Impact on a Clean Success — exactly at the floor, and below the Wound Threshold of essentially every named monster in the Bestiary (Rotting Fen-Goliath: WT 11, Malaphar: WT 13). No Arcane Clash spell as currently written can ever Wound either of them, on any roll, ever.

## The Fix

**New universal rule — place in Embracing the Abyss, replacing/amending the "Arcane Clash (Combat Spells)" intro paragraph:**

> When an Arcanist casts an offensive spell that deals Impact, calculate it the same way a weapon does:
>
> **Impact = (Margin of the Clash, or Margin over TN 8 for an unopposed spell) + Spell Power**
>
> Each spell's entry lists a flat **Spell Power** rating, exactly like a weapon's Power. The Margin Scaler no longer defines the Impact number directly — it defines the *special effect* that comes with each tier (a condition, a debuff, a status). Impact itself now scales with how well the roll went, the same way it does for every weapon Strike in the game.

**New universal option — place immediately after, as the Arcanist's answer to "this enemy is too armored":**

> **Overcharge:** Once per casting, before resolving the Clash, an Arcanist may Lock 1 Stress to add +2 to that spell's Spell Power for this casting only. Same shape as Power Strike for weapons — push the math, pay a price.

**Note on what this does *not* change:** several spells deal a small, fixed (usually 1-point) Impact as a narrow, triggered punishment rather than as their primary damage output — Calcify Armor's retaliation spikes, Stitch the Silhouette's escape tax, Sympathetic Effigy's reflect, Tidal Lock's distance violation, Choking Bramble's thorns, Vitrify's caltrops. Those are intentionally flat chip-damage flavor, not meant to threaten a Wound on their own, and are left untouched. The fix below only applies to spells whose actual job is to deal damage.

---

## Drop-in Replacements

*Each of these replaces only the Resolution/Margin Scaler portion of the existing entry in Manipulating_The_Void__Spells_.md — flavor text and Effect descriptions above each are unchanged and not reproduced here.*

### Necromancy → Corpse Bloom
- Resolution: Unopposed Wits + Arcana vs. TN 8. (Requires a corpse within sight).
- **Spell Power: 2**
- The Effect: The targeted corpse explodes, spraying razor-sharp bone shrapnel and toxic bile in a 10-foot radius. Every creature (friend or foe) in the radius suffers Impact equal to the casting Margin + Spell Power.
- The Margin Scaler:
  - Margin 0–2 (Messy): The explosion is delayed or unpredictable. The GM shifts the center of the blast 5 feet in a random direction before calculating who is hit.
  - Margin 3–4 (Clean): The corpse detonates perfectly as planned.
  - Margin 5+ (Exceptional): The blast area becomes Mire (difficult terrain) for the remainder of the encounter.

### Shamanism → Fulminating Strike
- Resolution: Arcane Clash (Wits + Arcana vs. Target's Dodge or Brace).
- **Spell Power: 2**
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 2 (Spell Power). The sheer voltage causes the target to drop their weapon or shield; they must spend a Free Action on their next turn picking it up.
  - Margin 3+ (Clean): As above, and the electrical surge cooks the target inside their armor — they instantly suffer 1 Dissonant Stress in addition to the physical Wound damage.

### Alchemy and Transmutation → Caustic Deluge
- Resolution: Arcane Clash (Wits + Arcana vs. Target's Defense action).
- **Spell Power: 1**
- The Effect: This spell ignores the target's Shield Value (SV) entirely during the Clash, as the acid simply splashes over and eats through the barrier.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 1 (Spell Power). If the target used a shield to Block, the shield permanently loses 1 SV for the rest of the campaign (or until repaired via Downtime).
  - Margin 3+ (Clean): As above, and the target's armor immediately gains the Damaged tag, permanently disabling special tags like Ablative Carapace or Construct plating.

### Demonology and Void Magic → Flay the Veil
- Resolution: Arcane Clash (Wits + Arcana vs. Target's Dodge action).
- **Spell Power: 3**
- The Effect: This spell completely ignores all physical armor, Shield Values, and Bestiary tags. It is pure, unmitigated erasure. However, if the caster loses the Clash via a target's Dodge, the tear violently snaps shut, and the GM immediately gains 1 Threat point.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 3 (Spell Power). The target is chilled to the bone, suffering Disadvantage on their next physical Strike roll.
  - Margin 3+ (Clean): As above, and the target loses a piece of their physical form to the void. If it is an Elite or Boss, they permanently lose one of their Rule-Breaking Tags (e.g., Pack Tactics or Ablative Armor) as it is sucked into the tear.

### Demonology and Void Magic → Euclidean Fracture
- Resolution: Arcane Clash (Wits + Arcana vs. Target's Wits + Resolve).
- **Spell Power: 2**
- The Effect: You target one Elite or Boss. If you win the Clash, you lock them in a spatial paradox.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: The target is Anchored (0 movement). Any melee attack they attempt against an adjacent player automatically suffers a -2 penalty, as their weapon swings through warped space.
  - Margin 3+ (Clean): The target is trapped. If they attempt to move or use an Aggressor action, they instantly suffer Impact equal to the original casting Margin + 2 (Spell Power) as the twisted geometry physically tears their muscles, and must spend their entire turn taking the Regroup action just to let the space stabilize.

### Astromancy → Astral Piercer
- Resolution: Arcane Clash (Wits + Arcana vs. Target's Defense action).
- **Spell Power: 2**
- The Effect: Because the attack comes from directly above at orbital velocity, traditional horizontal defenses are useless. The target completely loses the ability to use the Parry action against this Strike. They must rely on a heavy shield (Block) or attempt to Dodge.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 2 (Spell Power). The flash is blinding, stripping the target of their peripheral vision and denying them the Swarm Bonus or Pack Tactics on their next turn.
  - Margin 3+ (Clean): As above, and the sheer kinetic force instantly knocks the target Prone.

### Pyromancy → The Furnace Lance
- Resolution: Arcane Clash (Wits + Arcana vs. Target's Defense action).
- **Spell Power: 3**
- The Effect: You cannot cross blades with a blowtorch. The target completely loses the ability to use the Parry action against this Strike. They must rely on a thick shield (Block) or attempt to Dodge.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 3 (Spell Power). The raw heat causes the target to panic, forcing them to drop any wooden weapon or shield they are holding.
  - Margin 3+ (Clean): As above, and the target is Ablaze — until they waste a full Aggressor action to put themselves out (the Regroup action), they suffer 1 Impact at the start of every turn.

### Pyromancy → Wildfire Proliferation
- Resolution: Unopposed Wits + Arcana vs. TN 8.
- **Spell Power: 1**
- The Effect: Creates a 10x10 foot zone of raging fire. The casting Margin is fixed at the moment of casting. Any creature (friend or foe) starting their turn in the fire or moving through it automatically suffers Impact equal to that fixed Margin + Spell Power, for as long as the zone persists. The zone destroys any wooden cover or mundane foliage.
- The Margin Scaler:
  - Margin 0–2 (Messy): The fire is dangerously hungry. The zone forms, but the backdraft instantly singes the caster, dealing 1 Impact to them and destroying one mundane, non-magical item in their inventory (like a rope or torch).
  - Margin 3–4 (Clean): The fire zone is perfectly contained to the 10x10 area.
  - Margin 5+ (Exceptional): At the start of the next combat round, the GM must expand the fire zone by 5 feet in every direction.

### Pyromancy → Thermal Detonation
- Resolution: Arcane Clash (Wits + Arcana vs. Targets' Defense action). Note: This targets every enemy currently engaged in the caster's Threat Zone.
- **Spell Power: 1**
- The Effect: This is the Pyromancer's panic button when swarmed. The caster rolls once, and every enemy within 5 feet must roll to defend.
- The Margin Scaler (Based on Clash Margin):
  - Margin 1–2: Impact = Margin + 1 (Spell Power). The concussive wave violently throws the enemy 5 feet backward, removing them from the caster's Threat Zone and breaking the Swarm Bonus.
  - Margin 3+ (Clean): As above, and the enemy is thrown 10 feet backward, knocked Prone, and suffers 1 Dissonant Stress from the ruptured eardrums.

---

## Reference Table — All Spell Power Values Assigned

| Spell | Paradigm/Tier | Spell Power |
|---|---|---|
| Bolt | Common | 1 |
| Blast | Common | 2 |
| Burst | Common | 1 |
| Corpse Bloom | Necromancy | 2 |
| Fulminating Strike | Shamanism | 2 |
| Caustic Deluge | Alchemy and Transmutation | 1 |
| Flay the Veil | Demonology and Void Magic | 3 |
| Euclidean Fracture | Demonology and Void Magic | 2 |
| Astral Piercer | Astromancy | 2 |
| The Furnace Lance | Pyromancy | 3 |
| Wildfire Proliferation | Pyromancy | 1 |
| Thermal Detonation | Pyromancy | 1 |

Worth noting where this lands thematically: Flay the Veil (Power 3) and Furnace Lance (Power 3) are now your two hardest-hitting single-target spells, which matches how both were already written and flavored as the "ultimate" damage option in their Paradigm — the fix didn't just patch the math, it made the existing flavor text finally true.
