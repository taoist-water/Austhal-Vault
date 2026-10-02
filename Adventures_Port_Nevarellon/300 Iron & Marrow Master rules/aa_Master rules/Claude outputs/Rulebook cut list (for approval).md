# Iron & Marrow Rulebook — cut list for approval

The book is generated from the vault's rules files, and none of those files were changed. The sections below are everything that differs between the vault and the book. In total there are 128 edits, and each one is an exact-match rule in `edits.py`. If a vault file later changes under one of them, the rebuild stops instead of silently skipping it.

**Categories**

- **DEV**: a `(dev note)`, `[DEV NOTE]` or "Dev note" block.
- **META**: commentary about the document, the audit or the design process, including instructions aimed at editors or Claude ("do not correct this in a consistency pass", "copy that wording", "the corpus already does so").
- **HISTORY**: how a rule used to be, or what it replaced.
- **PLAYTEST**: references to playtests or to something not yet being tested.
- **SIDEBAR**: a Designer's Note that was kept and reformatted as a shaded box. Process-only sentences inside it were trimmed.
- **FORMAT**: a layout change with no change to the wording.
- **DANGLING / STALE**: a reference fixed because its target was cut, or because the vault had already made the note untrue.

## Calls I need from you

1. **The four Example Spells in *Embracing the Abyss*** (Choking Vapor, Mire, Brittle-Iron Aura, Ward of the Threshold) are cut, because your own dev note marks them as "not folded into the arcane spell lists". Two other places mention them:
   - The Bestiary's Creature Types paragraph named "spells like Ward of the Threshold". I removed that phrase.
   - The Marrow's *Dungeon Chemistry* (Volatile Concoction) still says "like *Choking Vapor* or *Choking Brambles*". I left that line as written.

   **My recommendation is to keep them cut** and change Dungeon Chemistry's example to *Choking Bramble* only. The other option is to print them as a short "Example Environmental Spells" appendix.
2. **The *Consecrated* condition** was entirely inside a dev note and nothing references it, so it is cut. The other option is to print it as a plain one-line condition.
3. **Appendix B (Sample Characters)** drops every Table Note and Advancement Ledger, the Design Notes section, and the rationale prose after each purse line. What remains for each character is the quote, stats, traits, feats, gear, spells or Prayers, and the Quick-Ref.

## Things I noticed in the vault but did not change

The book reproduces the vault exactly, so these appear in it as they are. Fixing them is for you to decide, in the vault.

- **The Activation Order fossil survives in Iron Core.** Under Snake Eyes, *Catastrophic Exposure* gives enemies "Advantage on their opening Activation order rolls", but Activation Order is static (`6 + Reflex`).
- **Falling contradicts Unaware traps (Iron World).** An Unaware fall "becomes Impact directly… no Defense allowed". The Unaware Target rule two sections earlier lets the target Dodge at Disadvantage.
- **The skill-stacking fossil is still on the sample-character sheets.** Havoc on Faelan (×2) and Vrenna reads "Prowess + Athletics/Acrobatics", but the spell list says "Athletics or Acrobatics". Rime-Fang's Bite on Brynja (×2) reads "Prowess+Athletics check". This is audit item 1.2, fixed in the spells but not in The Meat.
- **Faelan's Blade of Paranoia and Umbral Execution resist with "Wits or Resolve".** Wits is an Attribute, and Attributes are never rolled.
- **Three Tier 3 feats have no Tier gate line:** Flesh Weaver, Perfect Nullification and The Oracle's Burden. All three had dev notes, and every other Tier 3 feat carries "plus any two Tier 2 feats".
- **Brace in *Metal meet Flesh* writes the Wound Threshold as "[T]".** Your sheet ruling is that it is always "WT".
- **Design-voice prose was kept as written** ("we should root them in…", "If we want to keep the engine unified…"). It is your own voice, not commentary. A later style pass could turn it into rulebook voice.

---

## Iron Core (Core Rules).md

- **HISTORY** — removed/changed: “a real job at last:” → “a real job:”
- **HISTORY** — removed/changed: “This is the *structural damage reduction* the **Estoc** already names, and it is the object equivalent of” → “It is the object equivalent of”
- **SIDEBAR (moved below the list)** — removed/changed: “- *Design note — a deliberate exception.* This is the one roll in the game that adds an Attribute rather than a Skill. Attributes are derived-only everywhere else, and that rule stands; the Bleed-Out Check is carved out on purpose. Clinging to life isn't a trained competency — there is no skill for  …”
- **SIDEBAR** — removed/changed: “- **Fumble (Two natural 1s):** The trauma is too severe. You instantly die.” → “- **Fumble (Two natural 1s):** The trauma is too severe. You instantly die. ⏎  ⏎ [Designer's Note sidebar] This is the one roll in the game that adds an Attribute rather than a Skill. Attributes are d …”
- **DEV (unfinished, unreferenced condition)** — removed/changed: “- *Consecrated:* (dev note) Undead creatures suffer disadvantage when interacting with you.(/dev note)”

## The Marrow (Character Creation).md

- **FORMAT (step list rendered as a list)** — removed/changed: “Step 1: Select Race.   ⏎ Step 2: Determine Attributes (Raw Potential).   ⏎ 	- 4 DP to spend ⏎ Step 3: Distribute skill points (Practical Training).   ⏎ 	- 8 DP to spend (9 for a Human, or a Half-Elf who took Adaptable) ⏎ Step 4: Select 2 Feats.  ⏎ 	-  Tier 1 only. ⏎ Step 5: Outfit the character.” → “- Step 1: Select Race. ⏎ - Step 2: Determine Attributes (Raw Potential). ⏎ 	- 4 DP to spend ⏎ - Step 3: Distribute skill points (Practical Training). ⏎ 	- 8 DP to spend (9 for a Human, or a Half-Elf w …”
- **META** — removed/changed: “— no rule currently in the corpus does; the term is defined here ahead of that need”
- **SIDEBAR** — removed/changed: “_(Design note: any future feat or item that grants "additional Prayers from your Domain" should be read as "from any Domain's list" for a character on the Heretic's Path.)_” → “[Designer's Note sidebar] Any future feat or item that grants "additional Prayers from your Domain" should be read as "from any Domain's list" for a character on the Heretic's Path.”
- **DEV** — removed/changed: “**Flesh Weaver** (dev note) might need re doing as I am looking to tweak healing wounds during downtime. something like a tiered system where its 3 days without any intervention. stages of intervention reduce the time and volume of wounds recovered. (/dev note)” → “**Flesh Weaver**”
- **DEV** — removed/changed: “**Perfect Nullification** (dev note) this feels like a riposte?(/dev note)” → “**Perfect Nullification**”
- **DEV** — removed/changed: “**The Oracle’s Burden** (dev note) I like this. its something that doesn't revolve around combat and is engaging with the narrative. I want to sprinkle more of these kinds of interactions throughout the rule set. options that engage the narrative of a story rather than immediate mechanical interacti …” → “**The Oracle’s Burden**”
- **META (instruction to editors)** — removed/changed: “That second barrier is intended — don't lower either Attribute to "open it up."”
- **META (instruction to editors)** — removed/changed: “Don't lower either Attribute.”
- **META (design-backlog reference)** — removed/changed: “*(A per-turn Momentum-spend cap is tracked in design-backlog.md — this is one of the abilities it would affect.)*”
- **META (design-backlog reference)** — removed/changed: “— see design-backlog.md for the permanent injuries/mutations/diseases system this is waiting on”
- **HISTORY** — removed/changed: “- *Two existing patterns already work this way and are unchanged: **Desperate Edge** is named directly by four higher-tier feats, and **The Scrounger's** three feats extend one shared list of Momentum spends, so each genuinely requires the one below it rather than merely suggesting it.*”
- **HISTORY** — removed/changed: “They no longer contribute to a roll, and at 5 DP” → “They do not contribute to a roll, and at 5 DP”
- **META (audit commentary on pregens)** — removed/changed: “**Morwenna** (Elf) and **Faelan** (Half-Elf, took Fey Reflexes) are the independently-built creation characters that land on exactly 8. Perpetua is **not** evidence for this figure: she is a Human with a budget of 9, and sits on 8 only because 1 DP is currently unspent on her sheet.”

## Iron World (Environmental rules).md

- **DEV** — removed/changed: “### \[DEV NOTE\] Material Penetration (Optional Realism Rule)  ⏎  ⏎ - If a character is behind a wooden door (Light Cover, -2), and an attacker hits them using an armour-piercing weapon (like a Heavy Arbalest) or  maneuver like Deadly Aim, the shot completely shatters the cover. The target takes ful …”
- **META + DEV (Touchpoint audit note and the unadopted success-ladder draft)** — removed/changed: “________________________________________________________________________ ⏎  ⏎ ## Touchpoint: Existing Feats, Spells, and Effects Referencing "Hostile" or "Friendly" ⏎  ⏎ Any existing rule that triggers off an NPC being specifically "Hostile" or "Friendly" should be re-checked under this revision, si …”

## Hardware (Equipment).md

- **FORMAT (LaTeX arrows)** — removed/changed: “$\rightarrow$” → “→”
- **FORMAT (LaTeX arrows)** — removed/changed: “$\rightarrow$” → “→”
- **FORMAT (LaTeX arrows)** — removed/changed: “$\rightarrow$” → “→”
- **FORMAT (LaTeX arrows)** — removed/changed: “$\rightarrow$” → “→”
- **HISTORY** — removed/changed: “(see the rescaled Weapon Power tiers,” → “(see the Weapon Power tiers,”
- **HISTORY** — removed/changed: “This tier now spans two price bands: a Rare tier for a first real magic item, and the original Legendary tier for late-campaign power.” → “This tier spans two price bands: a Rare tier for a first real magic item, and a Legendary tier for late-campaign power.”
- **META (referred to a pregen by name)** — removed/changed: “(The item version of Ox's Blood Frenzy trait” → “(The item version of the Half-Orc's Blood Frenzy trait”
- **SIDEBAR (pricing guide kept; history phrases cut)** — removed/changed: “*[DESIGN NOTE] Pricing a new weapon.* The melee list above was priced by hand and is not perfectly regular. These are the bands it settles around, written down so the next weapon added to it does not drift. **Base cost, two-handed, one tag:** Power 0 ≈ 4 sp · Power 2 ≈ 8 sp · Power 3 ≈ 18 sp · Power …” → “[Designer's Note sidebar] **Pricing a new weapon.** These are the bands the melee list settles around. **Base cost, two-handed, one tag:** Power 0 ≈ 4 sp · Power 2 ≈ 8 sp · Power 3 ≈ 18 sp · Power 5 ≈ …”
- **DEV** — removed/changed: “- *Dev note — ship-to-ship combat is not designed. It needs a hull Wound Threshold and a vessel-scale procedure; out of scope for this pass.*”
- **META** — removed/changed: “— the corpus has no climbing-a-creature rule yet”
- **META (instruction to editors)** — removed/changed: “; don't let this quietly become a "+1 Faith" item later, or it breaks parity with Domains that have no silver-symbol equivalent”

## Embracing the Abyss (Magic Mechanics).md

- **META** — removed/changed: “, and the corpus already does so wherever it matters.” → “.”
- **HISTORY** — removed/changed: “no longer target a flat TN 8” → “do not target a flat TN 8”
- **HISTORY** — removed/changed: “*(Note: Faith's Prayer tiers are Novice / Adept / Master, matching Arcana's naming exactly — the tier previously labeled "Apprentice" is renamed to Adept throughout, so both systems read off the same table above.)*”
- **META** — removed/changed: “*(Correction: this previously cited "Litany of Nails" as the Flowing example — that's the Zealot's Tier 2 Archetype Feat name from The Marrow, not a Prayer, and it isn't listed in any Domain.)*”
- **DEV (four example spells marked as not folded into the spell lists)** — removed/changed: “________________________________________________________________________ ⏎ # Example Spells (dev note) these examples are not folded into the arcane spell lists (/dev note) ⏎  ⏎ Here are four traditional environmental spells designed to integrate seamlessly into the Iron & Marrow chassis. ⏎  ⏎ ### 1 …”

## Manipulating The Void (Spells).md

- **META** — removed/changed: “, and it is justified here rather than left silent, as that rule requires”
- **META (instruction to editors)** — removed/changed: “TheTao's call, 30 Sep — do not "correct" this to 2.”
- **META (instruction to editors)** — removed/changed: “Recorded 30 Sep; do not "correct" this to 3.”
- **HISTORY** — removed/changed: “**Designer Note:** New condition, Suppressed — see Iron Core.” → “**Designer Note:** Suppressed — see Iron Core.”
- **PLAYTEST** — removed/changed: “Worth a look in actual play against a room full of Fodder/Grunts specifically, but it's consistent with existing precedent rather than a new power ceiling.” → “It is consistent with existing precedent rather than a new power ceiling.”
- **HISTORY** — removed/changed: “What the roll now determines” → “What the roll determines”
- **HISTORY** — removed/changed: “, and it's now backed by the same cost-not-outcome” → “, backed by the same cost-not-outcome”
- **META** — removed/changed: “in the corpus” → “in the game”
- **META** — removed/changed: “in the corpus” → “in the game”
- **META** — removed/changed: “in the corpus” → “in the game”
- **HISTORY** — removed/changed: “*(Converted from a Faith-3 feat previously in The Marrow — removed from that document, as it's now Domain-locked here instead of open to any Faith-3 build.)*”
- **SIDEBAR (Designer Note → shaded sidebar)** — removed/changed: “**Designer Note — a justified deviation.** Spell Power stays at the full Adept **3** rather than the **2** the zone/multi-target reduction would give it (*Embra …” → “[sidebar]”
- **SIDEBAR (Designer Note → shaded sidebar)** — removed/changed: “**Designer Note — a justified deviation, downward.** Spell Power is **2** where the Adept default is **3** (*Embracing the Abyss*), and the missing point was sp …” → “[sidebar]”
- **SIDEBAR (Designer Note → shaded sidebar)** — removed/changed: “**Designer Note:** Suppressed — see Iron Core. Doesn't lock movement like Anchored or halve it like Rigor; instead it taxes anything that isn't holding the line …” → “[sidebar]”
- **SIDEBAR (Designer Note → shaded sidebar)** — removed/changed: “**Designer Note:** Ties directly into the Domain Tag (Tactical Horizon), which already deals in Momentum — this gives Strategy a second, distinct hook into that …” → “[sidebar]”
- **SIDEBAR (Designer Note → shaded sidebar)** — removed/changed: “**Designer Note:** Costed and scoped like Long Winter and Sovereign Tide — same "guaranteed AoE condition, no save" power level as the other Master zone Prayers …” → “[sidebar]”
- **SIDEBAR (Designer Note → shaded sidebar)** — removed/changed: “**Designer Note:** This is elite battlefield control. It bypasses saving throws entirely — the target stops moving regardless of the roll. What the roll determi …” → “[sidebar]”
- **SIDEBAR (Designer Note → shaded sidebar)** — removed/changed: “**Designer Note:** This forces the core 2d6 + Attribute + Skill math to be played completely flat. If a Boss relies on stacked passive Advantages, or a pack of  …” → “[sidebar]”
- **SIDEBAR (Designer Note → shaded sidebar)** — removed/changed: “**Designer Note:** Fills a gap Law otherwise leaves open — a single-target protection Prayer. Not making an ally harder to hit, but making them briefly illegal  …” → “[sidebar]”
- **SIDEBAR (Designer Note → shaded sidebar)** — removed/changed: “**Designer Note:** This directly hooks into the Dynamic Trait Manifest — Bosses and Elites derive their threat from these Traits. Paying 2 Locked Stress to turn …” → “[sidebar]”
- **SIDEBAR (Designer Note → shaded sidebar)** — removed/changed: “**Designer Note:** Reuses the existing Cursed condition rather than inventing a new debuff — turns Law into the Domain that shuts down an enemy healer's whole j …” → “[sidebar]”
- **SIDEBAR (Designer Note → shaded sidebar)** — removed/changed: “**Designer Note:** This is the absolute peak of the Faith philosophy — Certainty vs. Volatility. For 4 Locked Stress, the Priest can look at a Boss rolling doub …” → “[sidebar]”

## Soothing the soul (Downtime).md

- **HISTORY** — removed/changed: “This keeps the actual dice-facing procedure exactly as previously defined — nothing about *how a single Pursuit resolves* has changed — while giving the GM three new dials” → “This gives the GM three dials”
- **SIDEBAR** — removed/changed: “*Why the cap: without it the modifiers generate the currency rather than the rolls. A Friendly City stacks **+4** onto Acquisition, and Acquisition is the cheapest Pursuit at 1 PP — so a character with Influence +4 mints Momentum on **83%** of attempts and banks four to six in a single Full Week, en …” → “[Designer's Note sidebar] **Why the cap:** without it the modifiers generate the currency rather than the rolls. A Friendly City stacks **+4** onto Acquisition, and Acquisition is the cheapest Pursuit …”
- **HISTORY** — removed/changed: “*(This replaces two earlier versions. The first compressed the week-long Time Cost, which per Section 1 never gated anything. The second cut the Commission's PP cost by 2 — which made the top rung of this ladder the only one whose payout was simply **more PP**, a currency a Full Week already hands o …”
- **META** — removed/changed: “Each entry below formalizes a Pursuit already referenced elsewhere in the rules. Where a feat or item already specifies a detail (a time cost, a bonus, an output), that detail is preserved exactly — this section is filling the gaps around existing text, not overwriting it.”
- **SIDEBAR (reasoning kept; 'do not correct this in a consistency pass' cut)** — removed/changed: “> **Design note — result 66 outperforms a successful Tithe of Will, deliberately.** Iron Core states that a Long Rest should never outperform a successful Tithe. Carousing 66 clears **3** Locked Stress for 1 PP with **no check at all**, which beats a Priest who rolled well. This is known and is bein …” → “[Designer's Note sidebar] **Result 66 outperforms a successful Tithe of Will, deliberately.** Iron Core states that a Long Rest should never outperform a successful Tithe. Carousing 66 clears **3** Lo …”
- **HISTORY** — removed/changed: “via the Selling procedure now defined under Acquisition below.” → “via the Selling procedure under Acquisition below.”
- **META** — removed/changed: “, a separate gap worth addressing later”
- **META (document-about-itself wording)** — removed/changed: “This Pursuit does not exist independently — it is unlocked by a specific feat (already referenced, not included in this document) that allows a character to spend Progress Momentum to bypass the standard 3-day Tend to the Flesh cycle. Per the existing Flesh Weaver feat text already in *The Marrow*:  …” → “This Pursuit does not exist independently — it is unlocked by the **Flesh Weaver** feat (*The Marrow*), which allows a character to spend Progress Momentum to bypass the standard 3-day Tend to the Fle …”
- **HISTORY** — removed/changed: “— and now its mirror: turning loot into coin.” → “— and its mirror: turning loot into coin.”
- **SIDEBAR** — removed/changed: “*Why this exists: a capped sale otherwise made the best result on the ladder pay **nothing at all**. Above **50 sp** in a Hamlet, **100 sp** in a Town and **400 sp** in a City, the 65% and 50% rates both flatten onto the cap and are identical — so a Massive Success bought no extra coin, and once Pro …” → “[Designer's Note sidebar] **Why the Draft exists:** a capped sale otherwise made the best result on the ladder pay **nothing at all**. Above **50 sp** in a Hamlet, **100 sp** in a Town and **400 sp**  …”
- **HISTORY** — removed/changed: “**The Slot Check (New):**” → “**The Slot Check:**”

## Tools for the Nameless (GM Tools).md

- **META (instruction to editors)** — removed/changed: “**The Goblin Scrapper's `Sabotage` is this ability, already statted in the Bestiary — copy that wording rather than reinventing it.**” → “**The Goblin Scrapper's `Sabotage` (Bestiary) is this ability.**”
- **META (commentary praising the design)** — removed/changed: “Allowing non-casters to still use the _Arcana_ and _Faith_ skills is a brilliant piece of lateral design.”
- **HISTORY** — removed/changed: “Example Revision (Ablaze)” → “Example (Ablaze)”
- **HISTORY** — removed/changed: “Example Revision (Gehenna's Grip)” → “Example (Gehenna's Grip)”
- **HISTORY** — removed/changed: “What changed and why: once core-species Humanoids started building like PCs, most of the Bestiary already had Momentum Banks, and Threat was left running two statblocks. A whole parallel economy for two creatures is not worth the rules it takes to explain.”
- **HISTORY** — removed/changed: “**A Bank is already a spend cap**, which is why there is no Vessel Limit any more.” → “**A Bank is already a spend cap.**”
- **HISTORY** — removed/changed: “The round-start point is Dread/Boss only, and it replaces the old Vanguard Escalation.” → “The round-start point is Dread/Boss only.”
- **HISTORY** — removed/changed: “— the cap does the limiting that a tier restriction used to do. That is the single biggest simplification this change buys: an ability that generates resource no longer has to ask what tier is holding it.” → “— the cap does the limiting, so an ability that generates Momentum never has to ask what tier is holding it.”
- **HISTORY** — removed/changed: “This was already true for core-species NPCs; it is now true for all of them.”
- **META (instruction to editors)** — removed/changed: “**Point budgets for all four tiers, and the full Gate Test for Special Actions, now live in one place only: the Bestiary's "Core Integration Rules" section.** They get retuned as the roster grows, so a second copy here would just be another place for the two documents to drift out of sync — exactly  …” → “**Point budgets for all four tiers, and the full Gate Test for Special Actions, live in the Bestiary's "Core Integration Rules" section.**”

## Beasts Monsters Mutants (Bestiary).md

- **DANGLING (Ward of the Threshold was only in the cut Example Spells)** — removed/changed: “Domain Tags like Smite Corruption, spells like Ward of the Threshold, and any future” → “Domain Tags like Smite Corruption, and any future”
- **HISTORY** — removed/changed: “They no longer contribute to any roll;” → “They do not contribute to any roll;”
- **HISTORY** — removed/changed: “That percentage looks far higher than the 25–30% quoted under the old Attribute+Skill metric, but nothing about a Grunt actually changed: the Orc Line-Breaker struck at +4 then and strikes at +4 now. The old figure was understated because a PC's 12 included 4 Attribute points that were also feeding  …”
- **META** — removed/changed: “The four Elites below land at 9–11 Skill points against a Green party's 8, which makes the tier's "almost equivalent to the characters' capabilities" description true as written for the first time.”
- **META (audit table: 'the existing roster, checked against the new numbers' + three audit bullets)** — removed/changed: “**The existing roster, checked against the new numbers:** ⏎  ⏎ | Creature | Tier | Skill points | Green band | Verdict | ⏎ |---|---|---|---|---| ⏎ | Goblin Scrapper | Fodder | 2 | 1–2 | in band | ⏎ | Corpse-Trench Rat Brood | Fodder | 2 | 1–2 | in band | ⏎ | Imp | Fodder | 2 | 1–2 | in band | ⏎ | Sk …”
- **META** — removed/changed: “_Example (Cultist Assassin — flag resolved, see above):_” → “_Example (Cultist Assassin):_”
- **HISTORY** — removed/changed: “keep bespoke Traits and Special Actions as before.” → “keep bespoke Traits and Special Actions.”
- **META (instruction to editors)** — removed/changed: “**Species traits are free** and sit outside the allowance entirely. Don't restate the species lists here; they live in The Marrow and are read from there, so the two documents can't drift.” → “**Species traits are free** and sit outside the allowance entirely; they are read from The Marrow.”
- **META (instruction to editors)** — removed/changed: “, and don't "correct" an existing Human NPC upward on the strength of it”
- **HISTORY** — removed/changed: “That distinction is now mechanical rather than flavour, and it is the cleanest reason to keep the two construction methods separate.”
- **HISTORY** — removed/changed: “- _The Lizardman Shaman (Elite) was the first creature built on this trait and carries it inline: Innate Magic and Plated for 2 of its 3 picks, three Novice spells. It already fits the costing above; nothing about it changes._”
- **PLAYTEST + META** — removed/changed: “_The three terrains are_ Iron World's _own — its Hazard Check rule names "a blizzard, a scorching desert, freezing water" — so the skins hook onto an existing rule rather than introducing a biome list. Both riders reach for conditions that already exist and already fit:_ Drowned _is what the Ledger  …”
- **SIDEBAR (moved below the list)** — removed/changed: “- _**Confusion** is withheld at Grunt on purpose. Under Innate Magic every won Confusion Clash resolves Clean, and a Clean Confusion deletes the target's next Activation outright. At Arcana +3 she wins that Clash **66%** of the time against a Resolve +1 PC and **76%** against Resolve +0 — a turn los …”
- **SIDEBAR** — removed/changed: “- **Special Action (1):** fixed by her Skin — see **Hag Skins**, below. All four replace her regular action, so none needs a Margin gate (Gate Test).” → “- **Special Action (1):** fixed by her Skin — see **Hag Skins**, below. All four replace her regular action, so none needs a Margin gate (Gate Test). ⏎  ⏎ [Designer's Note sidebar] **Confusion is with …”
- **HISTORY** — removed/changed: “The 11th point moved from Notice to Ranged so the Shortbow its tactics already depend on can actually hit something; Melee stays at +2 because **Throat Slit** needs a Melee Clash won by Margin 3+.”
- **HISTORY** — removed/changed: “; without this, Rushed Stealth was taxing the exact manoeuvre the creature is built around.” → “.”
- **SIDEBAR (GM advice kept; 'watch it before it gets reused' cut)** — removed/changed: “> _**Running her — the Chain loop.** As an Elite she banks 1 Momentum on any Clash she wins by Margin 5+, and **The Chain** costs 1 Momentum on that same trigger. A Margin-5+ shot therefore pays for its own follow-up: net zero Momentum, one extra Shoot at a second target. Against a Green party's Dod …” → “[GM's Note sidebar] **Running her — the Chain loop.** As an Elite she banks 1 Momentum on any Clash she wins by Margin 5+, and **The Chain** costs 1 Momentum on that same trigger. A Margin-5+ shot the …”
- **SIDEBAR (GM advice kept; playtest instruction cut)** — removed/changed: “> _**Running her — Resolve is the soft target.** Every one of her Clash spells is Arcana vs. Resolve, and Resolve is the thinnest defence on most Green sheets. At Arcana +4 she wins **76%** of those Clashes against Resolve +1 and **84%** against Resolve +0 — and, being Elite, she banks 1 Momentum on …” → “[GM's Note sidebar] **Running her — Resolve is the soft target.** Every one of her Clash spells is Arcana vs. Resolve, and Resolve is the thinnest defence on most Green sheets. At Arcana +4 she wins * …”
- **HISTORY** — removed/changed: “the two genuine exceptions in the retuned roster — both are” → “both are”
- **HISTORY** — removed/changed: “, which is exactly the Vessel Limit they used to draw against”
- **STALE (the Imp stat block now exists)** — removed/changed: “3 Imps (Fodder tier — stat block not yet designed)” → “3 Imps (Fodder tier — see Imp)”
- **SIDEBAR (design reasoning kept; playtest re-run instruction cut)** — removed/changed: “> **Design note — deliberately built under his own band, and not yet re-tested.** His 12 Skill points sit at the top of the **Green Elite** band (9–12) and **one point under the flat Green Boss floor of 13**. That is a logged experiment, not an error: the Boss band assumes an action economy ("acted  …” → “[Designer's Note sidebar] **Deliberately built under his own band.** His 12 Skill points sit at the top of the **Green Elite** band (9–12) and **one point under the flat Green Boss floor of 13**. That …”

## Template - Enemies.md

- **META (instruction to editors)** — removed/changed: “rather than restating them here, so the two documents can't drift”

## The Meat (Player Characters).md

- **META** — removed/changed: “(every Paradigm sits at exactly 3 Novice spells, so this is now true of every Arcane Awakening character, not a gap specific to him)”
- **META** — removed/changed: “(every Paradigm sits at exactly 3 Novice spells, so this is now true of every Arcane Awakening character, not a gap specific to her)”
- **META (purse rationale)** — removed/changed: “She took the Bulky armour over the Chain Shirt deliberately: 5 sp cheaper, and the -1 it costs lands on Athletics, Stealth, and Arcana, none of which she uses. Her Faith is untouched.”
- **META (purse rationale)** — removed/changed: “The lightest kit on the roster buys the deepest pockets — which for a confidence man is not a consolation prize, and now buys him a little insurance too.”
- **META (purse rationale)** — removed/changed: “Light armour and a cheap weapon is the archer's bargain: she is buying range instead of Wound Threshold, and the purse lets her buy a great deal of everything else with the difference.”
- **META (inline table note)** — removed/changed: “**Table note:** Firing while an enemy occupies her own 5 ft Threat Zone imposes Disadvantage on the shot (Metal meet Flesh — Ranges), and the **Shortbow is 2H with no Sidearm tag**, so she has no item answer to it. Quick and Shadow-Weaver both exist to keep her out of that situation rather than to f …”
- **META (purse rationale)** — removed/changed: “Skipping a weapon entirely bought her the roster's best-armoured caster for the price — Faelan and Morwenna both sit at Wound Threshold 4; she's at 7 without spending a single silver on steel.”
- **META** — removed/changed: “*Same character as the Blooded build below, reconstructed backward from his own Advancement Ledger — the roster's first Standing pair built in this direction, rather than advanced forward from an existing Green sheet.*”
- **META (purse rationale)** — removed/changed: “The same deliberately light kit his Blooded Table Notes already describe — this is where that float started, before 12 sp of it went to the Leather upgrade.”
- **HISTORY** — removed/changed: “*(Downgraded from the Mage Staff, which is Rare and not purchasable at Green at any price — see Availability at character creation, Hardware. He loses **Bound**, so the book must now actually be held, and loses **Reach** and **Grounding Rod** outright — but the Wand's **Sidearm** tag answers the sam …”
- **HISTORY** — removed/changed: “, and the 20 sp freed by dropping the Staff pays for it without touching the alchemy”
- **HISTORY** — removed/changed: “Every item is Common or Scarce, so the entire loadout is purchasable from a Town at Green — which the Mage Staff never was.”
- **META** — removed/changed: “*(**Twin** array — the roster's first non-Spike build)*” → “*(**Twin** array)*”
- **META** — removed/changed: “*Same character as the Green build above, advanced three Milestones and kept side by side deliberately — this is the Twin-array-at-a-higher-Standing comparison Design Note 4 flagged as the next useful test, run against Aeric's own earlier self rather than a different character.*”
- **META (design-backlog reference)** — removed/changed: “*(A per-turn Momentum-spend cap tracked in design-backlog.md would touch this ability — see that doc.)*”
- **META** — removed/changed: “*Same character as the Green build above, advanced three Milestones and kept side by side — the roster's third same-character comparison after Aeric and Faelan.*”
- **META** — removed/changed: “Ox is the roster's demonstration of what the purse is for: he walked out” → “He walked out”
- **HISTORY** — removed/changed: “(Prowess — this is what Giant Feller actually rides on, and now it clears the feat's own Prowess 2 gate)” → “(Prowess — what Giant Feller rides on)”
- **DANGLING (Advancement Ledgers are not reprinted)** — removed/changed: “*(started at 2 — see Advancement Ledger)*” → “*(raised from 2 through Advancement)*”
- **HISTORY** — removed/changed: “, and hers is now actually spent: the 9th DP went to Notice, which had been left unspent”
- **DANGLING (Table Notes are not reprinted)** — removed/changed: “; see Table Notes”
- **DANGLING (Advancement Ledgers are not reprinted)** — removed/changed: “*(2d6+3 at creation — see Advancement Ledger)*” → “*(2d6+3 at creation)*”
- **META** — removed/changed: “*Same character as the Green build above, advanced ten Milestones and kept side by side deliberately, the same way Aeric is shown at Green and Veteran. The roster's first Storied character.*”
- **META (the 'Design Notes' section, 12 numbered notes)** — removed/changed: “## Design Notes ⏎  ⏎ **4. Focus vs. spread — superseded by the Attribute restructure.** This note originally compared each character built twice: once maxing the core Attribute at 3, once capped at 2 with the freed point spent elsewhere, and concluded that one point off the signature roll bought rou …”
- **META (every '### Table Note' subsection — 17 removed)** — removed/changed: “### Table Note …”
- **META (every '### Advancement Ledger' subsection — 7 removed)** — removed/changed: “### Advancement Ledger …”
