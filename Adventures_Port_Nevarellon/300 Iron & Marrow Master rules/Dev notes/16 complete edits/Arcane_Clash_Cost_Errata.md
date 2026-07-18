# Arcane Clash — Cost Errata

Fixes the gap: Arcane Clash (combat spell) resolution currently charges the caster nothing on any outcome, while the Margin of Manifestation (utility spell) resolution charges 1 Dissonant Stress on a Messy Success. This also resolves the earlier Paradigm Mastery flag — Fear's Margin 1–2 result is now the "Messy" tier Mastery is defined to upgrade, so Ilyrean's signature Demonology pick actually benefits from Mastery as intended.

---

## 1. Core Rule — add to *Embracing the Abyss*, "The Arcane Clash (Combat Spells)" section

Insert directly after the Impact formula / Overcharge paragraph:

> **Cost:** A Margin 1–2 result costs the caster 1 Dissonant Stress — this is the Clash-spell equivalent of the Margin of Manifestation's Messy Success, and it's the tier Paradigm Mastery upgrades to Margin 3+ (Clean) for in-Paradigm casters, paying no cost. Margin 3+ (Clean) costs nothing. Losing the Clash outright (the target's roll is higher) costs nothing beyond the lost action — same as whiffing a mundane Strike, you only pay to land a rough hit, not to miss. The Snake Eyes Backfire (natural double-1s: 1 Wound + 1 Dissonant Stress + a battlefield hazard) applies to any Arcana casting roll, Clash or unopposed, exactly as it already does for the Margin of Manifestation.

That one paragraph is the actual fix. Everything below is the checklist confirming it lands cleanly on all 28 existing Clash spells with no conflicts.

---

## 2. Per-spell markup

For each spell below, append the bracketed note to its existing **Margin 1–2** bullet. Nothing changes on the Margin 3+ (Clean) bullet — cost-free is already the implicit default there, matching how every Clean/Exceptional tier in the document already reads.

- **Common spell** (never benefits from Mastery): append *"The caster also takes 1 Dissonant Stress from the strain."*
- **Paradigm spell** (benefits from Mastery when in-Paradigm): append *"The caster also takes 1 Dissonant Stress from the strain — Paradigm Mastery upgrades this to Margin 3+/Clean for in-Paradigm casters, paying no cost."*

| # | Spell | List | Level | Insertion |
|---|-------|------|-------|-----------|
| 1 | Bolt | Common | Novice | Common wording |
| 2 | Blast | Common | Adept | Common wording |
| 3 | Blind | Common | Novice | Common wording |
| 4 | Burst | Common | Novice | Common wording |
| 5 | Havoc | Common | Novice | Common wording |
| 6 | Entangle | Common | Novice | Common wording |
| 7 | Drain Stress | Necromancy | Master | Paradigm wording |
| 8 | Puppet | Necromancy | Master | Paradigm wording |
| 9 | Rigor Mortis | Necromancy | Novice | Paradigm wording |
| 10 | Blade of Paranoia | Shadow Sorcery | Adept | Paradigm wording |
| 11 | Stitch the Silhouette | Shadow Sorcery | Novice | Paradigm wording |
| 12 | Beast Friend | Shamanism | Novice | Paradigm wording |
| 13 | Fulminating Strike | Shamanism | Adept | Paradigm wording |
| 14 | Wind-Shear | Shamanism | Novice | Paradigm wording |
| 15 | Boost/Lower Trait | Alchemy and Transmutation | Novice | Paradigm wording — see note below |
| 16 | Growth/Shrink | Alchemy and Transmutation | Adept | Paradigm wording — see note below |
| 17 | Caustic Deluge | Alchemy and Transmutation | Adept | Paradigm wording |
| 18 | Solder Joints | Alchemy and Transmutation | Adept | Paradigm wording — see note below |
| 19 | **Fear** | Demonology and Void Magic | Novice | Paradigm wording *(this is Ilyrean's spell — Mastery now does something)* |
| 20 | Flay the Veil | Demonology and Void Magic | Master | Paradigm wording |
| 21 | Euclidean Fracture | Demonology and Void Magic | Adept | Paradigm wording |
| 22 | Confusion | Witch Magic and Hedge Craft | Novice | Paradigm wording |
| 23 | The Evil Eye | Witch Magic and Hedge Craft | Novice | Paradigm wording |
| 24 | The Creeping Ague | Witch Magic and Hedge Craft | Adept | Paradigm wording |
| 25 | Astral Piercer | Astromancy | Adept | Paradigm wording |
| 26 | Tidal Lock | Astromancy | Adept | Paradigm wording |
| 27 | The Furnace Lance | Pyromancy | Master | Paradigm wording |
| 28 | Thermal Detonation | Pyromancy | Novice | Paradigm wording |

---

## 3. Edge cases (3 spells, flagged rather than silently patched)

- **Boost/Lower Trait (#15) and Growth/Shrink (#16)** are dual-path: Arcane Clash against an unwilling target, or unopposed Margin of Manifestation against a willing one. Their Margin bullets are already merged ("Margin 1–2 / 0–2 (Messy)") and don't currently state *either* path's cost inline — they've been silently relying on the general rule. Once the Core Rule above is added, both paths correctly inherit their respective cost (1 Dissonant Stress at that tier) without any wording change needed. No action required beyond adding the Core Rule.

- **Solder Joints (#18)** resolves as "Arcane Clash (treat like a target number) vs. Target's Wound Threshold" rather than an opposed roll against a Defense/Resolve stat. It's still explicitly labeled Arcane Clash, so the Core Rule applies the same way — flagging only because the resolution mechanic is unusual enough that it's worth double-checking against the Combat chapter separately; not a cost exception.

- **Dispel (Common, Adept)** is *not* labeled "Arcane Clash" — its Resolution line reads "Opposed Wits + Arcana vs. the original caster's recorded casting roll," and it deals no Impact. Left out of this errata deliberately rather than folded in by assumption. Worth a ruling on which cost model (if any) it should use, since it's currently the one opposed-but-not-Clash spell in the document and doesn't cleanly fit either existing bucket.

---

## 4. What this changes at the table

Ilyrean's *Fear* (2d6+6 vs. Target's Will+Resolve): a Margin 1–2 win now costs him 1 Dissonant Stress — unless it's a Clean win already, or Paradigm Mastery upgrades it, in which case it's free and he gets the stronger Margin 3+ effect (Fodder auto-Rout) into the bargain. Bolt, being Common, always costs 1 Dissonant Stress on a rough hit with no Mastery escape hatch — which is the correct relative positioning: the paradigm-exclusive pick should feel more reliable than the generic one, not identical to it.
