# Hardware & Downtime: Cost/Availability Pass

Drop-in edits for *Hardware (Equipment)* and *Soothing the Soul (Downtime)*. Each section names the target document and can be pasted over the existing table/entry.

---

## 1. Rationale (read before pasting)

The core Weapons and Armor tables had no Cost or Availability columns, which silently broke two other systems:

- **Acquisition** (Downtime) resolves purchases "at standard listed price" and gates them by Settlement Tier (Hamlet auto-fails anything above Common, Town caps at Scarce, City/Capital open Rare). No price/tier on a Longsword means a GM can't adjudicate a player buying one.
- **Hammer & Forge** ("25% of the item's base value") and **Masterwork Commission** ("+300% to base price") both math off a base value that doesn't exist for most items.

**Price bands** (anchored to existing priced items — Barbed Spear 25sp/Common, Estoc 45sp/Scarce, Heavy Arbalest 80sp/Rare, Masterwork Apothecary Kit 50sp/Rare):

| Availability | Sourced from              | Price band | Logic                                               |
| ------------ | ------------------------- | ---------- | --------------------------------------------------- |
| Common       | Hamlet+                   | 1–25 sp    | Village smith/herbalist, ordinary materials         |
| Scarce       | Town+                     | 15–50 sp   | Needs a proper forge, market, or trained specialist |
| Rare         | City+                     | 50–200+ sp | Guild-level craftsmanship, exotic materials         |
| Legendary    | Capital, Commission-gated | GM-set     | One-of-a-kind, not a market good                    |

Bands deliberately overlap — Availability tracks *how often the world stocks it*, price tracks *how good it is*. Same orthogonal relationship your Quality tags (Shoddy/Balanced/Masterwork) already use.

**On Arcane Focus items (Grimoire/Wand/Mage Staff):** placed at Scarce/Rare not because Arcana is illegal, but because they require specialized crafters — warding ink and proper binding for a Grimoire, an actual enchanter for a Wand or Staff. Same logic that puts Chainmail at Scarce because it needs a real forge, not a village smith.

**Flag for later:** *Embracing the Abyss* still opens with "Arcana... is highly illegal." If that's no longer true, that line needs a separate correction pass in the Magic Mechanics doc — not touched here, since it's outside Hardware/Downtime scope.

---

## 2. Target: Hardware.md — Weapons table (full replacement)

| Weapon Name                           | Specialization Group | Power | Grip  | Range / Threat                  | Tags & Attributes                                                                                                                                                                           | Cost  | Availability     |
| ------------------------------------- | -------------------- | ----- | ----- | ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----- | ---------------- |
| Unarmed (fists/feet/knees and elbows) | Unarmed              | 0     | 1H/2H | 5 ft Threat                     | Non-lethal, sidearm                                                                                                                                                                         | —     | Always available |
| Dagger / Knife                        | Blades               | 0     | 1H    | 5 ft Threat / 30 ft Thrown      | Concealable, Close-Quarters, Precise, Thrown, Sidearm                                                                                                                                       | 5 sp  | Common           |
| Shortsword                            | Blades               | 1     | 1H    | 5 ft Threat                     | Sidearm                                                                                                                                                                                     | 10 sp | Common           |
| Hand Axe                              | Axes                 | 1     | 1H    | 5 ft Threat / 30 ft Thrown      | Brutal, Thrown, Sidearm                                                                                                                                                                     | 8 sp  | Common           |
| Mace / Bludgeon                       | Bludgeons            | 1     | 1H    | 5 ft Threat                     | Bash                                                                                                                                                                                        | 8 sp  | Common           |
| Spear                                 | Polearms             | 1     | 1H/2H | 10 ft Threat / 60 ft Thrown     | Reach, Thrown                                                                                                                                                                               | 10 sp | Common           |
| Longsword                             | Blades               | 2     | 1H/2H | 5 ft Threat                     | Versatile                                                                                                                                                                                   | 25 sp | Scarce           |
| Warhammer                             | Bludgeons            | 2     | 2H    | 5 ft Threat                     | Bash, Sunder                                                                                                                                                                                | 30 sp | Scarce           |
| Greatsword                            | Blades               | 3     | 2H    | 5 ft Threat                     | Inertia, Cumbersome                                                                                                                                                                         | 45 sp | Scarce           |
| Halberd / Poleaxe                     | Polearms             | 3     | 2H    | 10 ft Threat                    | Reach, Cumbersome                                                                                                                                                                           | 45 sp | Scarce           |
| Shortbow                              | Bows                 | 1     | 2H    | Ranged (Max: Long / 120 ft)     | Volley                                                                                                                                                                                      | 15 sp | Common           |
| Longbow                               | Bows                 | 2     | 2H    | Ranged (Max: Extreme / 125+ ft) | Volley                                                                                                                                                                                      | 35 sp | Scarce           |
| Light Crossbow                        | Crossbows            | 2     | 2H    | Ranged (Max: Long / 120 ft)     | Armor Piercing, Reload                                                                                                                                                                      | 30 sp | Scarce           |
| Grimoire                              | Arcane Focus         | —     | 1H    | —                               | Repository: Holds your spells. If casting while open, you may spend 1 Momentum to cast a Novice spell without Locking a Stress slot for the first round (Reading it straight off the page). | 15 sp | Scarce           |
| Mage Staff                            | Arcane Focus         | —     | 2H    | —                               | Reach, Bound, grounding rod.                                                                                                                                                                | 45 sp | Rare             |
| Wand                                  | Arcane Focus         | —     | 1H    | —                               | Conduit, Focus, Sidearm.                                                                                                                                                                    | 35 sp | Rare             |

---

## 3. Target: Hardware.md — Armour table (full replacement)

| Armor / Shield Name | Value     | Type   | Tags & Attributes    | Cost           | Availability |
| ------------------- | --------- | ------ | -------------------- | -------------- | ------------ |
| Padded / Gambeson   | +0 Armor  | Light  | Cushioned            | 5 sp           | Common       |
| Leather             | +1 Armour | Light  | —                    | 12 sp          | Common       |
| Chainmail / Scale   | +2 Armor  | Medium | Bulky                | 45 sp          | Scarce       |
| Plate Armor         | +4 Armor  | Heavy  | Restricted           | 200 sp (10 gs) | Rare         |
| Buckler             | 2 SV      | Shield | Nimble               | 8 sp           | Common       |
| Kite / Round Shield | 4 SV      | Shield | Cover                | 18 sp          | Common       |
| Tower Shield        | 5 SV      | Shield | Bulwark, Obstructive | 40 sp          | Scarce       |

Plate at 200sp deliberately outcosts the Heavy Arbalest (80sp) — a full suit of armor should cost more than a single weapon — and 10 gs matches the existing fluff that gold is "held only by nobility and wealthy cartels."

---

## 4. Target: Hardware.md — Alchemical Wares table (fill blank rows only)

Replace these three rows in the existing table; leave the rest of the table untouched.

| Item Name            | Cost  | Avail. | Mechanical 2d6 & Resource Output                                                                                                                                                                                                                                                              |
| -------------------- | ----- | ------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Corpse-Weed Resin    | 6 sp  | Common | Lethargy: For the first combat encounter after the Breather, the user cannot generate Momentum, as their nervous system is too dulled. Clears 1 Locked Stress. Can be smoked during a 30-minute Breather.                                                                                     |
| Marrow-Glass Ampoule | 40 sp | Rare   | The Crash: At the end of the combat encounter, the user immediately suffers 1 Minor physical Wound from the violent chemical shock to their heart. Instant Override: Can be injected mid-combat as a Free Reaction. Converts all currently Locked Stress back into standard Dissonant Stress. |
| Surgical Spirits     | 10 sp | Common | Tremors: The user permanently suffers Disadvantage on any Prowess or Arcana rolls requiring fine motor skills until they return to a town to fully detox. Taken during a Breather. Numbness allows the user to clear 2 Locked Stress.                                                         |

Marrow-Glass sits at Rare rather than Common/Scarce specifically because it's the only item on the table with a guaranteed downside (a Wound, not just a risk) — that severity should be harder to get your hands on, not sold next to rope and torches.

---

## 5. Target: Hardware.md — Rename existing item

**"Masterwork Apothecary Field Kit" → "Field Surgeon's Kit."**

*Soothing the Soul (Downtime)* already refers to this item as "Field Surgeon's Kit" twice (Tend to the Flesh's Equipment Interaction, and the Acquisition entry's parenthetical). The Hardware name never matches. Renaming in Hardware is the smaller edit and avoids confusion with the unrelated Masterwork Quality tag — this kit isn't Masterwork-quality gear, it's just a well-stocked kit. Cost (50 sp) and Availability (Rare) are unchanged.

---

## 6. Target: Hardware.md — New entry (add to Tactical Expedition Gear)

#### Holy Symbol
- **Cost:** 5 sp | **Availability:** Common
- **Rules:** Required to manifest Miracles — per *The Marrow*'s Divine Conduit feat, a Priest must "speak the litany and bear your symbol" to cast. A Symbol bound to a Domain via the Covenant path can never hold a different entity's Miracles (no later switching, per Divine Conduit). 0 Slots — worn/carried, per the Inventory micro-item exemption.

This closes a real gap: Divine Conduit hard-requires a Holy Symbol to function at all, and nothing in Hardware previously priced, stocked, or slotted one.

---

## 7. Target: Downtime.md — Hamlet Acquisition Modifier (fix dead text)

**Current text** makes the -2 modifier meaningless — it says apply -2 *and* auto-fail, so the -2 never triggers:

> "Acquisition Modifier: -2 to the Acquisition check for anything beyond Common availability... Treat a roll that would otherwise succeed as automatically failing if the item's Availability rating exceeds Common."

**Replace with:**

> **Acquisition Modifier:** **-2** to the Acquisition check for Common-tier goods — a hamlet's stock is thin, and there's little room to haggle or substitute. Anything above Common isn't a modifier problem, it's a hard gate: automatically fails regardless of the roll — a hamlet simply doesn't stock Scarce, Rare, or Legendary goods, full stop.

This gives the -2 an actual job (making even *routine* hamlet shopping worse than baseline) while keeping the hard gate for anything the settlement genuinely can't supply.

---

## Summary of open items not addressed here

1. *Embracing the Abyss* still states Arcana is "highly illegal" — needs a decision and edit if that's no longer canon.
2. No touchpoint issues found for Faith implements beyond the Holy Symbol gap above.
