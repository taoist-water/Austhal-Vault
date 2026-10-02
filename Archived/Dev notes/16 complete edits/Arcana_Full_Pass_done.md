# Arcana: Full Mechanical Pass

This addresses the contradiction flagged in the original review — Spell Power is declared as a stat that adds to the Strike roll, but no spell in *Manipulating the Void* uses it; all 15 Arcane Clash spells use flat per-Margin Impact instead. Fixing that cleanly required also resolving three smaller things load-bearing on the same paragraph: which stat the target defends with, what "Desperate Edge" actually is, and how Sustain's existing fail-state interacts with all of it. Each is addressed in turn below.

________________________________________________________________________

## 1. Spell Power — Deprecated, Not Patched

**The problem:** *Embracing the Abyss* states spells have "a Power rating exactly like weapons, which is added directly to the Arcanist's Strike roll." This was written before — or in parallel with — the per-Margin Impact design that every actual spell in *Manipulating the Void* ended up using. Right now both exist in the text and only one of them is actually implemented anywhere.

**The fix:** Kill Spell Power as a concept entirely rather than trying to retrofit it onto 15 already-written spells. The per-Margin Impact model is doing real design work that a flat Power stat can't:

- It lets a single spell deal *more* on a clean hit and *less* on a scraped win (Furnace Lance: 3 Impact at Margin 1–2, 4 Impact at Margin 3+) — a flat Power number can't flex like that without a second sub-table.
- It keeps spells legible against the weapon table without needing a "this spell is secretly a Power 3 weapon" conversion step every time a player asks "how hard does this hit."

**Replacement language for *Embracing the Abyss*, "The Arcane Clash" section:**

> When an Arcanist casts an offensive spell (like *Furnace Lance* or *Astral Piercer*), they enter a Clash using Wits + Arcana against the target's chosen Reactor action. Spells do not have a flat Power rating the way weapons do. Instead, each spell's effect entry defines its own Impact directly, scaled to the Margin of the Clash — consult the spell's own Margin Scaler for the exact numbers. This is why Arcane Clash spells read differently from weapon Strikes: the "weapon" is the spell itself, and its damage profile is bespoke rather than templated.

This also retroactively explains something that was previously just an inconsistency: why none of the 15 Clash spells list a Power number. Now that's a documented design choice instead of an oversight.

________________________________________________________________________

## 2. What Does an Arcane Clash Spell Actually Target? (The Defense/Wits/Resolve Problem)

**The problem:** Across 15 spells, the defending value is written as "Target's Defense" (11 times), "Target's Wits or Defense" (2 times), "Target's Resolve or Defense" (2 times), and "Target's Prowess or Defense" (1 time, for *Wind-Shear*) — with no rule anywhere explaining what "Defense" actually *is* as a stat, or why some spells let the caster choose between two defending values and others don't.

**The fix — define Defense, then make the "or" intentional rather than accidental:**

> **Defense (New Derived Term):** When a spell's resolution reads "vs. Target's Defense," the target rolls **2d6 + the most relevant Reactor action available to them** — typically Block, Dodge, or Brace, exactly as if they were defending against a weapon Strike. "Defense" is shorthand for "the target picks their best applicable Reactor roll," not a separate derived stat the target has sitting on their sheet. This keeps Arcane Clashes using the same Reactor toolkit as physical combat, which is the whole point of routing magic through the unified Clash engine in the first place.

> **The "or" Clauses Are Intentional Counters, Not Loose Language:** A spell that says "vs. Target's Wits or Defense" is explicitly telling the GM that *this specific spell* lets the target substitute a mental stat for a physical Reactor roll — usually because the spell is attacking perception or cognition rather than the body (*Rigor Mortis*, *Blade of Paranoia*). A spell that says "vs. Target's Resolve or Defense" is doing the same thing for willpower-based resistance (*The Evil Eye*, *The Creeping Ague*, *Euclidean Fracture*). In all three cases, **the target chooses whichever roll is more favorable to them** — Wits/Resolve checks don't replace Defense, they sit alongside it as an alternate Reactor option specific to that spell's fictional target (the mind, not the armor).

This single fix turns what looked like inconsistent phrasing into a genuinely good piece of design: certain spells are *supposed* to bypass physical defense and attack the mind instead, and the "or" clause was always quietly doing that job — it just needed the rule spelled out once instead of implied 15 separate times.

**One spell needs a flag, not a fix:** *Wind-Shear*'s "vs. Targets' Prowess or Defense" is the only Clash in the whole spellbook keying off Prowess specifically (a physical stat, not mental) — worth double-checking this wasn't meant to say "Reflex" given the spell is about being shoved by wind, which Reflex/Acrobatics (Dodge) would more naturally resist than raw Prowess. Flagging rather than silently changing, since this might be intentional ("brute strength to stay standing in cyclonic wind" is defensible fiction).

________________________________________________________________________

## 3. Desperate Edge / Exploding 6 — Writing the Rule That Three Feats Already Assume Exists

**The problem:** *Fevered Channelling*, *Embrace the Void*, and *Penance Engine* (the latter belonging to Faith, not Arcana, but triggered by the same missing rule) all reference a named "Desperate Edge" / "Exploding 6" mechanic tied to rolling a natural 6. It is never defined as a base rule. Only Fates' Bounty (natural 12 / double 6s) is defined in *Iron Core*. This is the single most load-bearing gap in the whole Arcana cluster, because *Fevered Channelling* — a Tier 2 feat explicitly built to be "highly valuable" for sustaining Arcane spells per the Sustain rule's own parenthetical — is completely inert without it.

**The fix — add Desperate Edge as a sibling rule to Fates' Bounty in *Iron Core*'s Dice Mechanics section:**

> **Desperate Edge (a single natural 6):** When exactly one of the two dice in a 2d6 check shows a 6, the roller may treat that die as exploding: roll one additional d6 and add it to the total. Unlike Fates' Bounty (which triggers on *both* dice showing 6 and immediately grants an extra full die with no further conditions), Desperate Edge triggers on rolling a single 6 **only while the character is in a qualifying desperate state** — at half or more of their Stress Limit in Dissonant Stress, at their final Wound Slot, or under a specific feat/spell that explicitly lowers the threshold (such as *Embrace the Void*, which extends this to natural 5s as well). Outside a qualifying desperate state, a lone natural 6 is just a 6 — solid, unremarkable, no explosion.

This framing does two things at once: it gives *Fevered Channelling*, *Embrace the Void*, and *Penance Engine* the rule they were always written assuming existed, **and** it explains *why* the rule was named "Desperate" in the first place — it was never meant to be a universal always-on explosion the way Fates' Bounty is. It's a comeback mechanic that only switches on when a character is already in trouble, which fits the system's overall "things get worse, then briefly heroic, then worse" attrition rhythm far better than an unconditional second explosion tier would have.

**Touchpoint — Heavy Hitter weapon tag:** This tag ("you do not Explode on a 6... treated as a 7") now has an actual rule to suppress. No change needed to the tag itself, just confirming it now means something concrete: a Heavy Hitter weapon denies its wielder Desperate Edge specifically, trading the comeback mechanic for raw, unconditional Power. Worth a one-line addition to the tag's text making this explicit, since "Explode" was previously undefined jargon even in the tag that names it.

________________________________________________________________________

## 4. Blood Channeling — Tightening the Optional Modifier

**The problem:** *Embracing the Abyss* proposes Blood Channeling as the Arcanist's parallel to the Priest's sacrifice, but leaves the actual bonus undecided: *"a +2 (or advantage?) modifier."* This is a dev note that never got resolved, and the choice matters more than it looks — +2 and Advantage are not equivalent in this system's math.

**The fix — pick Advantage, not a flat +2, and say why:**

>  Before rolling an Arcane check (Clash or unopposed Margin roll), the Arcanist may voluntarily take 1 Dissonant Stress to gain **Advantage** on that roll.

Reasoning for picking Advantage over a flat +2:

- Per the Golden Rules, multiple sources of Advantage already collapse into a flat +1 bonus to the total rather than stacking — meaning Blood Channeling slots into existing math the system already knows how to resolve when a player has *also* got Advantage from a feat, spell, or condition. A flat +2 modifier would need its own separate stacking ruling.
- A flat +2 is strictly better than Advantage in expected-value terms on 2d6, which makes Blood Channeling a strict numerical upgrade with no actual risk/reward texture — exactly the kind of "this is just a tax you always pay" trap the rest of the Momentum economy works hard to avoid. Advantage keeps the bonus real without making it mathematically mandatory on every single cast.
- It mirrors the existing "Quick" feat (Reflex Advantage on Engagement Draw) and "Fey Reflexes" species trait — the system already has a vocabulary for "pay something, get Advantage," and Blood Channeling should speak that vocabulary rather than introduce a one-off flat bonus that exists nowhere else in the Arcana toolkit.

________________________________________________________________________

## 5. Sustain — Confirming the Fail-State Holds Up Under the Spell Power Removal

**No change needed here**, but worth confirming explicitly since it touches the same paragraph: the Arcane Sustain check ("`Wits + Arcana vs TN 8`, drop the spell and take 1 Dissonant Stress on a fail") was never dependent on the now-deprecated Spell Power stat — it's a flat TN 8 check unrelated to spell Impact math. It survives this pass completely untouched, and continues to be the clean contrast point against Faith's revised Sustain (Arcana drops the spell on a fail; Faith's revised Sustain lets the Miracle persist but feeds the GM's Threat pool instead). That asymmetry — Arcana loses the spell, Faith loses control of who's really casting it — is good design and this pass preserves it on purpose.

________________________________________________________________________

## 6. Touchpoints: Existing Spells in Manipulating the Void

No spell needs its numbers rewritten — every Margin Scaler entry already works exactly as written once Spell Power is removed as a concept, since none of them were using it anyway. The only textual change needed across all 28 spell entries is conceptual: read "vs. Target's Defense" per the new definition in Section 2 above, rather than as a mystery derived stat.

One spell is worth flagging on its own merits while we're in here: **Astral Piercer**'s effect text says the target "completely loses the ability to use the Parry action" because the strike comes from directly above — this is good, evocative spell-specific defense-denial design, and it's a pattern worth reusing (*Furnace Lance* already does the same thing for Parry vs. a blowtorch). Both spells are quietly building a precedent — "the fiction of how the spell strikes determines which Reactor actions are valid" — that could be called out as an explicit secondary rule alongside the Defense definition in Section 2, rather than left as two coincidentally similar one-off spell texts.

________________________________________________________________________

## 7. Touchpoints: Feats

- **Fevered Channelling (Tier 2):** Now fully functional — Desperate Edge exists, and the feat's own clause ("if you roll a Fumble while channeling, you take 3 Stress but the spell doesn't drop") continues to work as an exception layered on top of the base Sustain fail-state.
- **Combat Scholar (Tier 2 — Arcana):** Unaffected by this pass — keys off Blind Casting Disadvantage, not the Clash resolution itself.
- **Embrace the Void (Tier 3):** Now has a concrete base rule to extend ("Desperate Edge triggers on natural 5s as well as 6s"), rather than modifying an undefined mechanic.
- **Ingrained Arcana (Tier 3):** Unaffected — keys off Locked Stress cost reduction and Blind Casting, neither of which this pass touches.
- **Overchannel (Tier 3):** Worth a small note — "the spell automatically gains a Margin of Success of 5" still functions cleanly under the per-Margin Impact model (it just means the spell resolves at its top Margin Scaler tier), and is actually a cleaner interaction now that Spell Power isn't a second variable competing for relevance alongside Margin.
- **Void Weaver (Tier 2):** Unaffected — its opposed Wits + Arcana check to unweave an enemy spell was already self-contained and never referenced Spell Power.

________________________________________________________________________

## Summary of Concrete Rule Changes

| Area | Before | After |
|---|---|---|
| Spell damage | "Power rating added to Strike roll" (stated, unused) | Deprecated; per-Margin flat Impact confirmed as the only model |
| Defending stat | "Defense" undefined; "or Wits/Resolve" unexplained | Defense = target's best Reactor roll; "or" clauses are intentional mental-attack substitutions |
| Natural 6 | Referenced by 3 feats, no base rule | Desperate Edge defined: single-6 explosion, gated behind a qualifying desperate state |
| Blood Channeling | "+2 (or Advantage?)" undecided | Advantage, confirmed, with reasoning tied to existing Golden Rules stacking |
| Sustain | N/A | Confirmed unchanged and still asymmetric with Faith's revised Sustain, by design |
