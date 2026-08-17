# Inventory Slot Assignments

The Inventory section in *Hardware* defines the Slot system itself (8 + Prowess Modifier, max 13; Belt holds 3, the rest is Pack) and gives illustrative examples — "a one-handed weapon," "a cluster of 3 potions" — but no item in the Weapons, Armor, or Alchemical Wares tables has ever actually been assigned a number. This fills that gap, applying the existing rule's own logic consistently rather than inventing a new standard.

## The Governing Logic (Restated, Then Applied)

Per the existing rule:
- **1 Slot:** A one-handed weapon, a shield, a coiled rope, a Grimoire, a lantern, a cluster of 3 potions.
- **2 Slots:** A heavy two-handed weapon, a bulky trophy, a small treasure chest.
- **0 Slots:** Pocket-sized micro-items, unless stacked in bulk (100 coins = 1 Slot).
- **Worn armor:** 0 Slots while worn; 3 Slots if carried unworn.

The job here is just extending that logic item-by-item so a player filling out a sheet never has to guess.

________________________________________________________________________

## Weapons

| Weapon | Slots | Reasoning |
|---|---|---|
| Unarmed | 0 | Not a carried object |
| Dagger / Knife | 1 | Baseline 1H weapon; "Concealable" tag doesn't reduce this — concealment is about *detection*, not bulk |
| Shortsword | 1 | Baseline 1H |
| Hand Axe | 1 | Baseline 1H |
| Mace / Bludgeon | 1 | Baseline 1H |
| Spear | 1 (1H grip) / 2 (2H grip) | Matches its dual Grip listing — track whichever grip it's currently being carried/wielded in |
| Longsword | 1 (1H) / 2 (2H, per Versatile) | Same logic as Spear — Versatile already lets it flex grip, so it should flex Slot cost too |
| Warhammer | 2 | 2H baseline |
| Greatsword | 2 | 2H baseline; Cumbersome is already a combat penalty, not an extra Slot tax — don't double-dip |
| Halberd / Poleaxe | 2 | 2H baseline |
| Shortbow | 1 | 2H but a bow is not "heavy" in the way a Greatsword is — sized like a Spear's 1H end, not a Warhammer |
| Longbow | 2 | Larger frame than a Shortbow; consistent with the "bulky" 2-Slot category |
| Light Crossbow | 2 | 2H, mechanically bulky (Reload tag implies a stock and mechanism) |
| Heavy Arbalest | 2 | 2H, explicitly the bulkiest ranged weapon in the line (Heavy Reload, windlass) |
| Grimoire | 1 | Matches the rule's own explicit example |
| Mage Staff | 2 | 2H, and "Reach, Anchor" implies a long, awkward item — matches Halberd-tier sizing |
| Wand | 0 | A wand is pocket/sleeve-sized — this is the one Arcane Focus that should be a true micro-item, distinguishing it meaningfully from the Grimoire and Staff |

**Ammunition (arrows, bolts) is intentionally not assigned a Slot cost.** Per the existing Community Supply Die rules, ammunition is already abstracted into that shared resource track rather than tracked as discrete inventory — giving arrows their own Slot cost on top of the Supply Die would be double-tracking the same resource through two different systems.

________________________________________________________________________

## Armor & Shields

| Item | Slots (Worn) | Slots (Carried) | Reasoning |
|---|---|---|---|
| Padded / Gambeson | 0 | 1 | Light cloth — even unworn, it bundles small |
| Leather | 0 | 2 | Stiffer hide pieces don't compress as small as padding |
| Chainmail / Scale | 0 | 3 | Matches the base rule's explicit worn-armor example exactly |
| Plate Armor | 0 | 3 | Matches Chainmail's carried cost — Plate is heavier in play (Restricted tag) but a full plate harness doesn't physically take *more* pack space than a hauberk, just more effort to don |
| Buckler | 1 | 1 | A shield is a shield whether strapped to the arm or slung on the back — matches the base rule's explicit shield example |
| Kite / Round Shield | 1 | 1 | Same logic as Buckler — shields don't get a worn/carried split since they're never "worn" the way armor is |
| Tower Shield | 2 | 2 | Explicitly the largest, most cumbersome shield (Bulwark, Obstructive) — the one shield that earns the heavier 2-Slot tier |

________________________________________________________________________

## Alchemical Wares & Consumables

The base rule states "a cluster of 3 potions" = 1 Slot. Applying that ratio consistently:

| Item | Slots | Reasoning |
|---|---|---|
| Grave-Dust Poultice | ⅓ (stacks 3-per-Slot) | Standard potion/vial-sized consumable |
| Black-Root Draught | ⅓ (stacks 3-per-Slot) | Same |
| Witch-Spur Salve | ⅓ (stacks 3-per-Slot) | Same |
| Vitriol Solvent | ⅓ (stacks 3-per-Slot) | Same — small vial despite a dangerous effect |
| Naphtha Fire-Flask | 1 (does not stack) | This is a thrown explosive, not a sipped potion — sized and tracked individually, the way a single Hand Axe would be, rather than bundled 3-to-a-Slot |
| Arcane Salts | ⅓ (stacks 3-per-Slot) | Standard small consumable |
| Philter of Focus | ⅓ (stacks 3-per-Slot) | Same |
| Corpse-Weed Resin | ⅓ (stacks 3-per-Slot) | Smoked/consumed item, vial or pouch sized |
| Marrow-Glass Ampoule | ⅓ (stacks 3-per-Slot) | Same |
| Surgical Spirits | ⅓ (stacks 3-per-Slot) | Same |

**Handling the ⅓-Slot stacking cleanly:** Rather than tracking fractional Slots on a sheet, track these items as "Potion Slots" in groups of three — a single sheet box can hold any combination of up to 3 standard vial/draught items, mixed or matched, and only converts to consuming a full Slot once a 4th item would be added. This is a direct, literal application of the existing rule's own "cluster of 3 potions = 1 Slot" line, just spelled out as a bookkeeping method.

________________________________________________________________________

## Other Equipment (Touchpoints from Elsewhere in Hardware)

| Item | Slots | Reasoning |
|---|---|---|
| Field Surgeon's Kit | 1 | Already described as a kit/case of tools — fits the "lantern"-tier 1-Slot category for a single coherent toolkit |
| Hooded Bullseye Lantern | 1 | Matches the base rule's explicit example exactly |
| Coiled Rope | 1 | Matches the base rule's explicit example exactly |
| 100 Gold Coins | 1 | Matches the base rule's explicit example exactly |

________________________________________________________________________

## Design Notes Worth Flagging

1. **The Versatile/dual-grip weapons (Spear, Longsword) are the one place this system needs an explicit ruling**, since the base Inventory rule never anticipated an item that can be sized two different ways depending on how it's currently held. I've resolved this as "track whichever grip it's currently in," which means a player could theoretically free up a Slot mid-dungeon by switching their Longsword to two-handed grip and repacking — that's a fun, fiddly bit of tactical inventory texture if you want it, or you can simplify to "always costs the higher value" if the bookkeeping isn't worth the flavor.

2. **The Wand's 0-Slot rating is a deliberate differentiator**, not an oversight — right now Grimoire/Staff/Wand have no mechanical distinction beyond their listed tags, and giving the Wand a genuine inventory advantage (doesn't compete for Belt space at all) gives a "duelist caster" build an actual resource-management reason to prefer it over a Staff, beyond pure flavor.

3. **Worn vs. carried armor splits are new structure**, not just restated rule — the base text only gave one example (Chainmail-tier = 3 Slots carried). I extended that logic down to Padded/Leather (lighter, so cheaper carried) and confirmed Plate matches Chainmail's carried cost rather than exceeding it, since Plate's penalty is already fully expressed through its Restricted tag and shouldn't be taxed twice.

4. **Shields deliberately don't get a worn/carried split** the way armor does, since nothing in the base rule suggests a shield is ever "worn" in the armor sense — it's always either equipped (and presumably occupying a hand/Belt slot in combat terms) or stowed, at the same Slot cost either way.
