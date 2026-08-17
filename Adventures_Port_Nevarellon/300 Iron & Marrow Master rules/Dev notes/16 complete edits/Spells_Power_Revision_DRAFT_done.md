# DRAFT REVISION — Spell Power Rescaling
*Replaces the Spell Power lines and associated Margin Scaler text for the spells below, within Manipulating The Void (Spells).md. All spell effects, conditions, levels, and non-Impact text are unchanged — only the Power number and the arithmetic that references it.*

**Design intent:** Keep Spell Power exactly anchored to the new Weapon Power tiers, so a maxed Arcanist and a maxed Fighter remain doing comparable raw Impact per action. Same three tiers, same jump sizes, same reasoning as the weapon table.

| Tier | Old Power | New Power |
| --- | --- | --- |
| Tier 1 | 1 | **2** |
| Tier 2 | 2 | **3** |
| Tier 3 | 3 | **5** |

---

## Tier 1 (Power 1 → 2)

### Bolt (Common)
*(Add explicit stat line — currently implied only by the scaler text.)*
- **Spell Power: 2**

**The Margin Scaler:**
- Margin 1–2: Impact = Margin + 2 (Spell Power).
- Margin 3+ (Clean): As above, no complication.

### Burst (Common)
- **Spell Power: 2**

**The Margin Scaler:**
- Margin 1–2: Impact = Margin + 2 (Spell Power) to every target who loses.
- Margin 3+ (Clean): As above, no complication.

### Caustic Deluge (Alchemy — 1)
- **Spell Power: 2**

**The Margin Scaler (Based on Clash Margin):**
- Margin 1–2: Impact = Margin + 2 (Spell Power). If the target used a shield to Block, the shield permanently loses 1 SV for the rest of the campaign (or until repaired via Downtime).
- Margin 3+ (Clean): As above, and the target's armor immediately gains the Damaged tag, permanently disabling special tags like Ablative Carapace or Construct plating.

### Wildfire Proliferation (Pyromancy — 2)
- **Spell Power: 2**
*(Effect text unchanged apart from the referenced number: "...automatically suffers Impact equal to that fixed Margin + Spell Power...")*

### Thermal Detonation (Pyromancy — 4)
- **Spell Power: 2**

**The Margin Scaler (Based on Clash Margin):**
- Margin 1–2: Impact = Margin + 2 (Spell Power). The concussive wave violently throws the enemy 5 feet backward, removing them from the caster's Threat Zone and breaking the Swarm Bonus.
- Margin 3+ (Clean): As above, and the enemy is thrown 10 feet backward, knocked Prone, and suffers 1 Dissonant Stress from the ruptured eardrums.

---

## Tier 2 (Power 2 → 3)

### Blast (Common)
- **Spell Power: 3**

**The Margin Scaler:**
- Margin 1–2: Impact = Margin + 3 (Spell Power) to every target who loses.
- Margin 3+ (Clean): As above, and the blast ignores the first point of Armor on anyone caught at the radius's center.

### Fulminating Strike (Shamanism — 1)
- **Spell Power: 3**

**The Margin Scaler (Based on Clash Margin):**
- Margin 1–2: Impact = Margin + 3 (Spell Power). The sheer voltage causes the target to drop their weapon or shield; they must spend a Free Action on their next turn picking it up.
- Margin 3+ (Clean): As above, and the electrical surge cooks the target inside their armor — they instantly suffer 1 Dissonant Stress in addition to the physical Wound damage.

### Corpse Bloom (Necromancy — 3)
- **Spell Power: 3**
*(Effect text unchanged apart from the referenced number: "...suffers Impact equal to the casting Margin + Spell Power.")*

### Astral Piercer (Astromancy — 2)
- **Spell Power: 3**

**The Margin Scaler (Based on Clash Margin):**
- Margin 1–2: Impact = Margin + 3 (Spell Power). The flash is blinding, stripping the target of their peripheral vision and denying them the flanking Bonus or Pack Tactics on their next turn.
- Margin 3+ (Clean): As above, and the sheer kinetic force instantly knocks the target Prone.

### Euclidean Fracture (Demonology — 4)
- **Spell Power: 3**

**The Margin Scaler (Based on Clash Margin):**
- Margin 1–2: The target is Anchored (0 movement). Any melee attack they attempt against an adjacent player automatically suffers a -2 penalty, as their weapon swings through warped space.
- Margin 3+ (Clean): The target is trapped. If they attempt to move or use an Aggressor action, they instantly suffer Impact equal to the original casting Margin + 3 (Spell Power) as the twisted geometry physically tears their muscles, and must spend their entire turn taking the Regroup action just to let the space stabilize.

---

## Tier 3 (Power 3 → 5)

### Flay the Veil (Demonology — 1)
- **Spell Power: 5**

**The Margin Scaler (Based on Clash Margin):**
- Margin 1–2: Impact = Margin + 5 (Spell Power). The target is chilled to the bone, suffering Disadvantage on their next physical Strike roll.
- Margin 3+ (Clean): As above, and the target loses a piece of their physical form to the void. If it is an Elite or Boss, they permanently lose one of their Rule-Breaking Tags (e.g., Pack Tactics or Ablative Armor) as it is sucked into the tear.

### The Furnace Lance (Pyromancy — 1)
- **Spell Power: 5**

**The Margin Scaler (Based on Clash Margin):**
- Margin 1–2: Impact = Margin + 5 (Spell Power). The raw heat causes the target to panic, forcing them to drop any wooden weapon or shield they are holding.
- Margin 3+ (Clean): As above, and the target is Ablaze — until they waste a full Aggressor action to put themselves out (the Regroup action), they suffer 1 Impact at the start of every turn.

---

## Confirmed unaffected
- **Overcharge** (Embracing the Abyss): "Lock 1 Stress to add +2 to that spell's Spell Power for this casting only" — still functions identically on the new base values; no change needed.
- All non-Impact utility/control spells (Barrier, Blind, Entangle, Havoc, etc.) — these never had a Spell Power rating and aren't touched by this pass.
- Master Miracle Impact values (Wrathful Light's flat 2, Banish's Stress-based resolution) — Faith magic runs on the Tithe of Will, not the Margin/Power model, and is intentionally out of scope here.

## Sanity check against the Boss-protection requirement
Max weapon Power (5) still equals max Spell Power (5) — a maxed Pyromancer's Furnace Lance and a maxed Fighter's Greatsword remain doing identical raw Impact per hit before situational modifiers, preserving martial/arcane parity at the new, higher baseline.
