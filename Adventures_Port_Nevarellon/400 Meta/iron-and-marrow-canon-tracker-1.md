# Iron & Marrow — Canon Tracker

A running reference for everything established in the world. Check new content against this before adding it; update this file whenever new content is confirmed as canon.

Keep entries to one line where possible. This is a lookup tool, not a wiki — link out to fuller documents rather than duplicating prose here.

*Consolidated 2026-07-22 from two parallel tracker files. The prior "canon-tracker1" (dated 2026-07-15, covering the full Golden Company build-out, Envoy Corps, four new NPCs, the Sunken Ward restructure, and Shades retirement) forms the base, since it was the actively-maintained, comprehensive version. The older "canon-tracker" file was merged in — it turned out to contain a cluster of Location entries (named ducal seats + a road) not found in the newer file. See "Merge findings" below — one of these is a live discrepancy that needs a decision.*

---

## ⚠️ Merge findings (read first)

1. ~~**Orphaned ducal-seat names — need a decision.**~~ → **RESOLVED 2026-08-17.** All five seat names and the road are now fully written into prose in the Five Duchies source document, with travel times, and echoed independently in Framework - The Three Layers.md. The finding is closed; the rows below are promoted from *proposed* to **confirmed canon**.
   **What landed:** **Castle Iron-Spire** (De Vonce), **Millhaven** (Aerthos), **Saltmere** (Valerius), **Granite Spire** (Stonereach), **Corvus Spire** (Corvus, buried), plus **The Ducal Concord Road**. The source document additionally carries an explicit *note on the seat names* establishing the "-Spire" convention as deliberate in-world logic: a spire is the **natural formation**, not the building, and the seats were cut into standing rock because it was cheaper than quarried stone and could not be undermined. That is a canon rule, not just a naming habit — apply it to any future seat.
   **Still outstanding from this cluster:** none of the five seats has a dedicated file. Castle Iron-Spire remains a confirmed empty stub.
2. **Castle Iron-Spire entry reconciled.** Both trackers had a row for this; merged into one below. It carries over the older tracker's fuller region description (northern foothills of the Jagged Spine) plus the newer tracker's more conservative sourcing (only actually named in Tythius_De_Vonce.md; the file itself is confirmed empty — I checked it directly).
3. Everything else in the older tracker file (empty Factions/NPCs/Deities/Timeline/Artifacts/Terminology tables) was already superseded by the newer file's populated versions — no further merge needed there.

---

## 🔁 Retcon log

**2026-08-17 — The Chalced Kingdom → The Twelgorn Kingdom.** Renamed, and the underlying history changed. The exiled royal children no longer *found* a kingdom in the south; they flee through the Silted Marshes with what portable wealth they can carry and **buy asylum** in the already-ancient Twelgorn Kingdom, where they are hosted as "guests" of its sitting King. Twelgorn is established as a centuries-old maritime slaving realm that predates the Whispering Coast's settlement entirely.

- **Why it matters beyond the name:** the old canon had a kingdom founded 58 years ago by fugitives which nonetheless possessed a standing navy of "floating fortress" warships, royal treasure galleons, naval conscription, an entrenched aristocratic officer corps, generational slave-branding, and a territorial claim on the southern marshes. Haren Twarde was conscripted into a navy younger than she is; Telorna Belaar carries brands from an institution that barely had time to exist. **The retcon resolves a plausibility failure that was already live across five files.**
- **The threat model changed.** The danger from the south is no longer a returning dynasty. The exiles have no army, no treasury and no realm — only a claim, and that claim is an asset in a foreign King's strongroom. Any move north is a war of conquest wearing a legitimacy costume, with a compliant claimant in the baggage train.
- **Executed across 11 files** (18 references, zero residual): History.md, Silted Marshes.md, Captain Haren Twarde.md, The Wyvern-tail Pirates.md, Telorna Belaar.md, Maccorrack.md, Divtown.md, Lord Kelf Thorne.md, Greywater Lagoon.md, Austhal.md, Framework - The Three Layers.md.
- **Wikilink paths normalised.** Three inconsistent targets (`100 Society/The Chalced Kingdom`, `000 Atlas/The Chalced Kingdom`, `000 Atlas/Chalced`) now all resolve to a single canonical target: **`000 Atlas/The Twelgorn Kingdom`**.
- **⚠️ ONE REFERENCE NOT YET FIXED.** `The Golden Company.md` contains a **"The Chalced Question"** bullet under Vulnerabilities, linking `[[100 Society/The Chalced Kingdom|Chalced]]`. It is present in the project index but the file mount returns it as **zero bytes**, so it could not be edited in the same pass. **Manual fix required:** rename the bullet to *"The Twelgorn Question"*, repoint the link, and reword — the vulnerability is now sharper, since the Contract's founding purpose was suppressing a *domestic* return to kingship and a Twelgorn invasion is unambiguously foreign.
- **Open thread, not yet canon:** portable wealth is finite and 58 years is two to three generations. Whether the exiles are now impoverished dependents, a Twelgorn court faction, or married into the dynasty outright is undecided. Deliberately left out of History.md pending a call.

---

## 🧪 File integrity (audit 2026-08-17)

Run during the Twelgorn/ducal-seat reconcile. **These are process problems, not lore problems, but they cause lore problems** — a stale or empty file silently drops out of any vault-wide sweep, which is exactly how the "Chalced Question" reference survived an 11-file retcon pass.

**1. Zero-byte files (12).** Some are genuine intentional stubs; at least one is not.
`The_Golden_Company.md`, `Castle_Iron-Spire.md`, `The_Drowned_Rat_Tavern.md`, `The_Great_Expanse.md`, `Sun-Iron.md`, `Wastelands.md`, `The_Black_Mast_Warehouse.md`, `Nightshade.md`, `The_Brine-Glow_Lanterns.md`, `The_High_Alchemist_Guild.md`, `The_Shard-Blade.md`, `Untitled.md`.
- **`The_Golden_Company.md` is confirmed desync, not a stub** — the project index holds the full built-out faction document (force structure, rank ladder, Envoy Corps, the Vulnerabilities list). Anything reading from the file rather than the index sees nothing. **Do not trust a zero-byte result as evidence a file is empty.**
- `Untitled.md` should be identified and either named or deleted.

**2. Two stale wikilink targets for the Five Duchies document.** In-vault links point at *three different names* for what should be one file:
- `The Five Duchies of the Whispering Coast` — the correct target (used by The Inner Sea.md).
- `draft2_The Five Duchies of the Whispering Coast` — **stale**, used by High Captain Marco.md. Repoint it.
- The mount additionally exposes the file as `The_Five_Duchies_of_the_Whispering_Coast_1.md`; if a duplicate `_1` copy genuinely exists in the vault, delete the stale one before it diverges further.

**3. Corvus Spire is wikilinked to the wrong document.** Framework - The Three Layers.md flags that Corvus Spire is linked as `[[The Inner Sea#🪓 Resource & Industry|Corvus Spire]]` — pointing the ducal seat at a section of a *different* region's document that merely references it. Recommend a bold unlinked term until Corvus Spire gets a stub of its own.

---

## Locations

| Name | Region/Map Position | One-line summary | Established in | Notes/Conflicts |
|---|---|---|---|---|
| Austhal | Top-level continent | The known continent; contains Whispering Coast, Silted Marshes, Inner Sea, Twelgorn Kingdom, Wastelands | Austhal.md, History - The Broken Crown of Austhal.md | Region list conflicts with Whispering Coast.md's own hierarchy — see next row. **Still open.** |
| The Whispering Coast | Region within Austhal | Coastal region containing Port Nevarellon + the Five Duchies; borders Silted Marshes, Ubaraz Kingdom, Kald Mountain Territory, Inner Sea | Whispering Coast.md | **CONFLICT (still open):** Austhal.md lists this and the Five Duchies as sibling regions; Whispering Coast.md lists the Five Duchies as its own child location. Recommend: Five Duchies = political subdivision *within* Whispering Coast |
| The Five Duchies of the Whispering Coast | Political subdivision of Whispering Coast | Five ancestral human duchies (De Vonce, Aerthos, Valerius, Stonereach, Corvus) bound by the Ducal Accord, banned from the title "King" | The Five Duchies of the Whispering Coast.md | See conflict above |
| Duchy of De Vonce (Iron Court) | Northern Five Duchies, foothills of Jagged Spine | Iron/timber militarist duchy; largest feudal levy; resents reliance on the Golden Company | Five Duchies.md, Tythius De Vonce.md | — |
| Castle Iron-Spire | Duchy of De Vonce, northern foothills of the Jagged Spine | Ancestral seat of House De Vonce; cut directly into the foothills; northern terminus of the Ducal Concord Road before the Stonereach leg | Tythius De Vonce.md; The Five Duchies of the Whispering Coast.md; Framework - The Three Layers.md | **CONFIRMED** (sourcing upgraded — the earlier "named only in Tythius De Vonce.md" note is superseded). **File is still a confirmed empty stub** — now the most-referenced empty file in the vault. Travel time: ~3–4 days by horse from Port Nevarellon, 7–9 by loaded wagon |
| Duchy of Aerthos (Breadbasket) | Eastern Five Duchies | Agricultural monopoly; flat, indefensible terrain; politically passive | Five Duchies.md | Confirmed as one of the Golden Company's most reliable Envoy standing-retainer clients (see The Golden Company.md) |
| Millhaven | Duchy of Aerthos, where the main river breaks into the barge channels | Ducal seat of Aerthos; fortified grain-hub feeding Port Nevarellon's barge trade | The Five Duchies of the Whispering Coast.md; Framework - The Three Layers.md | **CONFIRMED.** No dedicated file yet. **Closest ducal seat to the city** — ~2–3 days by horse via the Concord Road's river spur, 4–5 by loaded barge with the current. Framework argues this proximity plus flat terrain is *why* Aerthos is passive — fear, not temperament |
| Duchy of Valerius (Gilded Coast) | Southern coastal Five Duchies | Maritime/salt/wine economy; closest financial ties to the Council of Five | Five Duchies.md | Also confirmed as a reliable Envoy standing-retainer client. Valerius Family.md is still an unfilled template — no named members |
| Saltmere | Duchy of Valerius, coastal cliffs above the salt-refining pans | Ducal seat of Valerius; walled port town | The Five Duchies of the Whispering Coast.md; Framework - The Three Layers.md | **CONFIRMED.** No dedicated file yet. ~1 day from the Basin by coastal galley along the Coastal Meridian (2 in poor weather); 4–5 days overland, cliff roads punish wagons. **The only ducal seat that does not need the Concord Road** — Framework flags this as unwritten strategic leverage and the real reason Valerius behaves like a syndicate |
| Duchy of Stonereach (High Shields) | Northeastern Five Duchies, borders Ubaraz Kingdom | Granite quarrying; dwarven-influenced architecture; isolated survivalist culture | Five Duchies.md | Its neighbor Ubaraz Kingdom.md is an unfilled template — can't cross-check border claims yet |
| Granite Spire | Duchy of Stonereach, mountain passes bordering the Ubaraz Kingdom | Ducal seat of Stonereach; dwarven-engineered citadel cut into the passes | The Five Duchies of the Whispering Coast.md; Framework - The Three Layers.md | **CONFIRMED.** No dedicated file yet. Furthest seat: ~6–8 days by horse via the Concord Road, longer or impassable in deep winter; 10–14 days for a loaded masonry wagon train |
| Duchy of Corvus / The Corvus Scar (Fallen Crown) | Formerly northern Five Duchies, now ash wasteland | House Corvus rendered "functionally extinct" by the Cataclysm 50 years ago; land poisoned by the Ash-Blight | Five Duchies.md, History - The Broken Crown of Austhal.md | Epigraph ("one rules an ossuary") may imply a claimant on the Corvus seat — confirm if intentional hook or just phrasing |
| Corvus Spire | Buried beneath the Corvus Scar | Ancestral seat of House Corvus; buried by the mountain collapse 50 years ago, never excavated or resettled | The Five Duchies of the Whispering Coast.md; The Inner Sea.md | **CONFIRMED.** No dedicated file yet. Named for the peak that fell on it. **Explicitly disambiguated in canon** from The Broken Spires in the Inner Sea — drowned peaks, not masonry; what they share is the heat-scarred fracturing along the same seam. No lawful road or travel time exists; the only figure on record is tactical (De Vonce's border levy could reach the Scar's edge in ~1–2 days) |
| The Ducal Concord Road | Overland highway: Port Nevarellon → Castle Iron-Spire → northeast to Granite Spire, with a maintained river spur east to Millhaven | The only infrastructure the merchant oligarchy and the old nobility have ever built together; jointly funded and garrisoned by the Council of Five and the four standing Duchies. Terminates at the De Vonce border watch-towers facing the Corvus Scar — no road runs into the ash | The Five Duchies of the Whispering Coast.md; Framework - The Three Layers.md | **CONFIRMED.** Complements rather than replaces the Coastal Meridian sea-lane (The Inner Sea.md), which remains Saltmere's primary route. **Two live hooks:** (1) a jointly-garrisoned road has no arbitrating office — Framework recommends a single named road-warden with deliberately ambiguous appointing authority; (2) the Road shares its corridor with the city aqueduct, meaning Council-funded soldiers sit on a De Vonce chokepoint year-round, and neither party has ever said aloud that this is why the Council co-funded a road into a duchy it distrusts |
| The Inner Sea / The Great Expanse | Region east of Whispering Coast | Shallow inner sea sheltered by the Shield Atolls; home to Leviathans, Oakhaven Cove | The Inner Sea.md | **DUPLICATE:** The Great Expanse.md is an empty stub of the same region — recommend deleting the stub |
| The Shield Atolls | Sub-location within the Inner Sea | Barrier islands sheltering the inner basin; scattered stilt-village communities | The Inner Sea.md | No separate file — documented inline, which is fine |
| Oakhaven Cove | Settlement within Inner Sea / Shield Atolls | Great Northern Township; master port for the deep-sea monster-hunting fleets | Referenced in The Inner Sea.md, Divtown.md, Morgran the Abomination.md | No dedicated file exists — gap |
| Silted Marshes | Region south of Whispering Coast | Labyrinthine delta; no roads; Iron-Burl timber trade; marsh-fever | Silted Marshes.md | — |
| Divtown | Settlement within Silted Marshes | Smuggler shanty-town / logging outpost ruled by Lord Kelf Thorne | Divtown.md | — |
| Grey Water Lagoon | Sub-location adjacent to Divtown | Hidden deep-water pirate anchorage; base of the Wyvern Tail Pirates | Greywater Lagoon.md | Filename "Greywater" vs. in-text "Grey Water" — standardize spelling |
| The Jagged Spine | Region, northern mountain border of Austhal | Site of the Corvus cataclysm; source of Winter Moon storms | Referenced in History.md, Five Duchies.md, The Inner Sea.md | File is an unfilled template — major gap. Now also the subject of High Captain Marco's standing (and unfunded) strategic concern, per High Captain Marco.md |
| Ubaraz Kingdom | Region east, dwarven nation | Engineered the Great Anchor Basin's seawalls; Morgran's kin/origin | Referenced in The Great Anchor Basin.md, Morgran the Abomination.md, Five Duchies.md | File is an unfilled template — gap |
| The Kald Mountain Territory | Region bordering Whispering Coast | No detail established | Referenced only in Whispering Coast.md | File unfilled — gap; unclear if distinct from Jagged Spine/Ubaraz Kingdom |
| Wastelands | Region within Austhal | No detail established | Referenced only in Austhal.md's region list | File completely empty — gap, no border/terrain info at all |
| The Twelgorn Kingdom | Region south of Silted Marshes | Ancient maritime slaving realm predating the Whispering Coast's settlement; hosts the exiled royal line as "guests"; standing navy and treasure galleons; sends "Retrievers" north | Referenced in History.md, Silted Marshes.md, Captain Haren Twarde.md, Telorna Belaar.md, Maccorrack.md, Divtown.md, Greywater Lagoon.md, The Wyvern-tail Pirates.md, Lord Kelf Thorne.md, Austhal.md, Framework - The Three Layers.md, The Golden Company.md | **NO FILE EXISTS — the single highest-priority location gap; now confirmed as **12** referencing documents, not 5.** Renamed and retconned from "The Chalced Kingdom" — see Retcon log. One stale reference remains unfixed in The Golden Company.md |
| Port Nevarellon | Settlement, Free City-State on Whispering Coast | ~35,000 pop. maritime trade hub; governed by Council of Five; enforced by Golden Company | Port Nevarellon.md | Confirmed **Five** Districts, not six — see Sunken Ward and Shades rows below |
| The High Quarter | District of Port Nevarellon | Old nobility; clean water vaults; northern limestone cliffs | Port Nevarellon.md; The High Quarter.md | Dedicated file is an unfilled template |
| The Trade Plazas | District of Port Nevarellon | Commercial heart; banking houses, guilds, upscale markets | Port Nevarellon.md; The Trade Plazas.md | Dedicated file is an unfilled template |
| The Sunken Ward | District of Port Nevarellon | Home to the city's most impoverished underclass, including Corvus refugee descendants; contains the Muddy Docks (developed) and Cinder Row (stub) | The Sunken Ward.md | Formal District-tier parent of Muddy Docks |
| The Muddy Docks | Neighborhood within The Sunken Ward, Port Nevarellon | Working-class waterfront boardwalk sprawl; Iron-Anchor Syndicate territory; the Sunken Ward's economic engine | The Muddy Docks.md | Nested under The Sunken Ward; content itself unchanged, only its parent field |
| The Foundry Slips | District of Port Nevarellon | Industrial sector; shipyards, smokehouses, refineries | Port Nevarellon.md; The Foundry Slips.md | Dedicated file is an unfilled template |
| ~~The Shades (district)~~ | *(retired)* | *(retired — was a low-lying reclaimed-marshland slum)* | *(formerly Port Nevarellon.md)* | **RETIRED.** Confirmed by the author to be an early draft that evolved into what is now Muddy Docks; no longer listed in Port Nevarellon.md's district list. Row kept here only for institutional memory — do not resurrect as a separate location |
| The Shades (brothel) | Building within The Muddy Docks | Waterfront brothel/gambling den/black bank run by the Dolly Sisters | The Shades.md | Only "Shades" in canon going forward — no naming collision |
| The Great Anchor Basin | District of Port Nevarellon | High-security deep-water harbor; garrisoned directly by the Golden Company | The Great Anchor Basin.md | District #5 of five (was #6 of six) following the Shades retirement. Also location of The Sovereign's Gate — see below |
| The Sovereign's Gate | Building within The Great Anchor Basin | Fortified garrison and toll-keep; headquarters of the Golden Company | The Golden Company.md | Deliberately placed within the Basin's existing Toll Gates infrastructure rather than inventing new geography |
| The Rusty Tankard | Building within The Great Anchor Basin | Waterfront tavern / Cobalt Feather dead-drop, fronted by Kaleb | The Rusty Tankard.md | — |
| The Drowned Rat Tavern | Building within The Muddy Docks | Referenced as Maeve's hidden ledger office / Iron-Anchor-linked tavern | Referenced in The Iron-Anchor Syndicate.md, The Muddy Docks.md | File completely empty — gap |
| The Black Mast Warehouse | Building, northern wharf, Muddy Docks | Iron-Anchor Syndicate HQ; Garrick's and Maeve's residence | Referenced in The Iron-Anchor Syndicate.md, Garrick the Keelhauler.md, Maeve the Scribe.md | File completely empty — significant gap: a major faction's HQ has no content |
| The Rusty Anchor Foundry | Building, district unclear | Silas Bane's base above the fighting pits | Referenced in Silas Bane.md | File does not exist — gap |
| Cinder Row | Sub-location/neighborhood within The Sunken Ward | Inland refugee tenement blocks, distinct from the waterfront Muddy Docks | The Sunken Ward.md | **Intentional stub.** Left undeveloped by design — placeholder for future material, not an oversight |
| The Low-Tide Market | Sub-location, Muddy Docks (within Sunken Ward) | Bazaar held on exposed mudflats at low tide | Referenced in The Muddy Docks.md | No file — minor gap |
| Slipway Seven | Sub-location, Muddy Docks (within Sunken Ward) | Commercial drydock/repair yard | Referenced in The Muddy Docks.md | No file — minor gap |
| The Brine-Glow Depot | Sub-location, Muddy Docks (within Sunken Ward) | Alchemical maintenance workshop for street lanterns | Referenced in The Muddy Docks.md | No file — minor gap, related to Brine-Glow Lanterns item gap below |
| The Broken Spires | Drowned ridge in the northern Inner Sea | A submerged ridge of petrified stone spires — **mountain, not masonry**. Divers report the same glassy, heat-scarred fracturing found along the collapsed Corvus peaks | The Inner Sea.md; The Five Duchies of the Whispering Coast.md | **Row corrected.** The earlier summary ("petrified ruin matching Corvus Spire architecture") was wrong and is superseded — canon now explicitly disambiguates these from Corvus Spire. The implication is *not* that anything came through out here: it is that **the seam that opened at Corvus does not end at Corvus**, running northeast beneath the Inner Sea, unmapped. Load-bearing for Marco's northern-sky anxiety |
| The Sunken Causeway | Ruined point of interest, Silted Marshes | Submerged remains of an ancient royal highway | Silted Marshes.md | Documented inline — fine as is |

## Factions

| Name | Territory/Base | One-line summary | Power level (rules ref) | Established in | Notes/Conflicts |
|---|---|---|---|---|---|
| Council of Five | Port Nevarellon | Merchant oligarchy governing the Free City-State; holds the 99-yr Golden Company contract | Not yet defined | Council of Five.md, History.md, Port Nevarellon.md | No named members despite governing the whole city — gap |
| The Golden Company | The Sovereign's Gate (Great Anchor Basin); also a rotating roster of private clients citywide via the Envoy Corps | Two-tier mercenary army (foreign Officer Corps + locally-recruited rank and file) under a 99-year city monopoly; also runs a separate private-contract specialist branch, the Envoy Corps ("the Second Contract") | Not yet defined | History.md, Port Nevarellon.md, The Great Anchor Basin.md, The Golden Company.md | Fully built out: named leadership, force structure, economics, rank ladder, and the Envoy Corps sub-branch. Four named NPCs added (see NPCs table) |
| The Civic Constabulary (The Coppers) | Toll-houses, lower districts | Corrupt, underpaid municipal watch; despised by both Syndicate and Golden Company | Not yet defined | Faction - The Civic Constabulary (The Coppers).md | Formally answerable to Provost Halvard Stross of the Golden Company, who is quietly building a corruption case against Captain Vance |
| The Iron-Anchor Syndicate | The Black Mast Warehouse, Muddy Docks (Sunken Ward) | Blunt-force smuggling/extortion cartel controlling the docks | Not yet defined | The Iron-Anchor Syndicate.md | HQ location file (Black Mast Warehouse) is still empty |
| The Cobalt Feather Syndicate | Alfric's manor + Rusty Tankard dead-drop | White-collar forgery/smuggling network under a strict no-blood mandate | Not yet defined | The Cobalt Syndicate.md, Alfric Danniken.md | Filename "The Cobalt Syndicate.md" vs. in-doc name "The Cobalt Feather Syndicate" — standardize |
| The Wyvern Tail Pirates | Grey Water Lagoon, Divtown | Disciplined commerce-raiding pirate fleet led by Haren Twarde | Not yet defined | The Wyvern tail Pirates.md, Captain Haren Twarde.md | — |
| The Grey Water Pirates | Grey Water Lagoon | "Informal coalition of independent smugglers and privateers" | Not yet defined | Greywater Lagoon.md | **POSSIBLE OVERLAP** with Wyvern Tail Pirates — still unresolved; unclear if this is the general pirate population vs. Haren's militarized fleet within it, or an editing duplicate |
| The Tidespoken Clergy | Lower piers, Port Nevarellon | Religious sect running soup kitchens; keeps peace between gangs; rival to Syndicate recruitment | Not yet defined | Referenced in Religion.md (Domain of Sea & Storms), The Muddy Docks.md, The Iron-Anchor Syndicate.md, The Sunken Ward.md | No dedicated faction file — worth creating given how often it's referenced. Confirmed as the closest thing the Sunken Ward has to a unifying presence |
| The High Alchemist Guild | Port Nevarellon (unspecified location) | Manages the Brine-Glow Lantern municipal lighting system | Not yet defined | Referenced in Port Nevarellon.md, The Iron-Anchor Syndicate.md | File completely empty — gap, especially since Silas Bane's active plot targets this guild directly |
| House De Vonce | Duchy of De Vonce | Ruling ducal house; martial/iron economy | Not yet defined | Tythius De Vonce.md, Five Duchies.md | — |
| House Valerius | Duchy of Valerius | Corporate-syndicate-style noble house; indentured salt labor | Not yet defined | Five Duchies.md | Valerius Family.md unfilled — no named members |
| House Thorne (disowned branch) | Divtown, Silted Marshes | Disgraced nobility running the Divtown fencing operation under Kelf Thorne | Not yet defined | Lord Kelf Thorne.md | — |

## NPCs

| Name | Affiliation | Role/One-line summary | Stat block? (Y/N + ref) | Established in | Status (alive/dead/unknown) |
|---|---|---|---|---|---|
| Alfric Danniken | Cobalt Feather Syndicate | Founder/leader; forbids assassination, relies on blackmail and debt-traps | N | Alfric Danniken.md | Alive |
| Lord Kelf Thorne | Divtown / Grey Water Pirates | Self-proclaimed Baron of the Silted Marshes; fences pirate goods under his noble seal | N | Lord Kelf Thorne.md | Alive |
| Tythius De Vonce | House De Vonce | Duke of De Vonce; half-elf, 86; carries The Shard-Blade | N | Tythius De Vonce.md | Alive; also the Golden Company's most notable Envoy-refusal holdout |
| Garrick the Keelhauler | Iron-Anchor Syndicate | Grandmaster; aging, pragmatic, seeks legitimization | N | Garrick the Keelhauler.md | Alive; the 99-Year Contract's ~41 remaining years are now the specific clock his "wait out the Company" plan is racing |
| Kaleb | Cobalt Feather Syndicate | Barkeep/manager of the Rusty Tankard; dead-drop liaison | N | Kaleb.md | Alive; **PRONOUN CONFLICT (still unresolved)** — Kaleb.md uses he/him throughout, The Rusty Tankard.md refers to Kaleb as "she" |
| Qasim Al Goor | Cobalt Feather Syndicate | Skipper of *The Curzon*; inland smuggling logistics | N | Qasim Al Goor.md | Alive |
| Maeve the Scribe | Iron-Anchor Syndicate | Chief accountant/auditor; caught between Garrick and Silas | N | Maeve the Scribe.md | Alive |
| Silas Bane | Iron-Anchor Syndicate (Young Bloods) | Enforcer Captain plotting a coup against Garrick | N | Silas Bane.md | Alive; formally tied to a real place of origin — see The Sunken Ward.md |
| Clara Dolly | The Shades (brothel) / Iron-Anchor-adjacent | Co-owner; business/ledger mind; holds the Black Ledger | N | The Dolly Sisters.md | Alive |
| Tessa Dolly | The Shades (brothel) / Iron-Anchor-adjacent | Co-owner; information broker; carries powdered nightshade | N | The Dolly Sisters.md | Alive |
| Captain Haren Twarde | Wyvern Tail Pirates | High Captain; ex-Twelgorn navigator; wields the Wyvern-Hide Banner | N | Captain Haren Twarde.md | Alive |
| Morgran "Fin" Deep-Draught | Independent (Oakhaven Cove) | Mutated dwarven navigator of the Silted Marshes | N | Morgran the Abomination.md | Alive; filename says "Morgran the Abomination," doc header says "Morgran 'Fin' Deep-Draught" — still unresolved |
| Lidda Shoon | Cobalt Feather Syndicate | Halfling jeweler/fence; follower of the Cult of the Crooked Coin | N | Lidda Shoon.md | Alive |
| Maccorrack | Iron-Anchor Syndicate (muscle) | Half-orc stevedore/bodyguard; escaped Twelgorn slave | N | Maccorrack.md | Alive |
| Telorna Belaar | Divtown | Timber forewoman; true operational backbone of Divtown | N | Telorna Belaar.md | Alive |
| Bruiser Ben | The Shades (brothel) | Doorman/muscle for the Dolly Sisters | N | Referenced in The Shades.md, The Dolly Sisters.md | Alive; no dedicated file — minor gap |
| High Captain Marco | The Golden Company | High Captain; senior field commander of the Port Nevarellon garrison; chronic insomnia; fixated on the Corvus Scar threat | N | High Captain Marco.md | Alive |
| Provost Halvard Stross | The Golden Company | Provost overseeing Constabulary conduct citywide; quietly building a case against Captain Vance | N | Provost Halvard Stross.md | Alive |
| First Envoy Isolde Vantry | The Golden Company | Head of the Envoy Corps; Sunken Ward-born, first locally-raised soldier to reach the top of the specialist track | N | First Envoy Isolde Vantry.md | Alive |
| Sergeant Wren Cobb | The Golden Company | Locally-raised NCO on Muddy Docks patrol; quietly lets recognized faces slip through toll checkpoints | N | Sergeant Wren Cobb.md | Alive |

## Deities / Pantheon

| Name | Domain | One-line summary | Worshipped by (faction/region) | Established in |
|---|---|---|---|---|
| Saint Senecus the Unyielding | Strategy (Iron Horizon) | Doomed-pass military philosopher; stoic tactical duty over survival | Not yet tied to a specific faction | Religion - The pagan Pantheon and the Faith Domains.md |
| Corvo's Folly (The Grinning Prophet) | Trickery (Crooked Coin) | Cynical smuggler-prophet who bankrupted the old empire's treasury | Lidda Shoon; implicitly the Cobalt Feather Syndicate | Religion.md, Lidda Shoon.md |
| Aurelius the Architect | Law (The Zenith) | Brutal unifier-warlord; ideological root of the High Quarter's claimed authority | The High Quarter elite | Religion.md, Cosmology - The Celestial Graveyard and The war of Creation.md |
| Vael the Mute | Death (Ashen Veil) | Grave-keeper preaching death as mercy, not tragedy | Not yet tied to a specific faction | Religion.md |
| Kaelen the Survivor | Winter & Wilds (Rime-Fang) | Tribal matriarch, primordial winter-drake hunter | Not yet tied to a specific faction | Religion.md |
| Mother Elara of the Mud | Mercy & Healing (Weeping Martyr) | Plague-era martyr who absorbed the dying's suffering into herself | Not yet tied to a specific faction | Religion.md |
| Thalass's Omen | Sea & Storms (Tidespoken) | Apocalyptic rogue wave deified as the ocean's true sovereignty | The Tidespoken Clergy | Religion.md |

## Timeline / Historical Events

| Date/Era | Event | One-line summary | Factions/NPCs involved | Established in |
|---|---|---|---|---|
| Pre-history | The Great Fracture / Deicide | Mortals rebel against and kill their god-Creators, shattering the Sphere into the Great Disk | All mortal races | Cosmology - The Great Fracture.md |
| Pre-Sundering era | The War of Creation / Explosion of Creation | Cosmic civil war between sympathetic gods + mortals vs. rogue gods + manufactured monster races | Origin of orcs, goblins, aberrations | Cosmology - The Celestial Graveyard and The war of Creation.md |
| Generations ago | Founding of the Kingdom of the Whispering Coast | Settler families flee a decaying empire, crown a King, five Ducal families secure the coast | The five founding Ducal houses | History - The Broken Crown of Austhal.md |
| Unspecified (pre-Accord) | The Civil War | Tyrannical kings push the Dukes into rebellion; merchants hire the Golden Company | Golden Company, five Ducal houses, the old Crown | History.md |
| ~58 years ago | The Seat Falls / The Ducal Accord signed / The 99-Year Contract begins | King slain; Golden Company granted 99-yr city monopoly (roughly 41 years now remain on the term); Council of Five formed; "King" title banned | Golden Company, Council of Five, Five Dukes, Tythius De Vonce (signatory) | History.md, The Golden Company.md (pins the specific dating) |
| Same era | Flight of the royal heirs | Several surviving royal children flee south through the Silted Marshes and **buy asylum** in the already-ancient Twelgorn Kingdom, hosted as "guests" of its sitting King. They founded nothing. | The exiled royal line; the King of Twelgorn | History.md |
| 50 years ago | The Cataclysm / Corvus Scar | Demonic incursion breach collapses a Spine peak, burying House Corvus and poisoning the valley | House Corvus (destroyed) | Five Duchies.md, History.md |
| Ongoing since Cataclysm | The Refugee Crisis | Displaced Corvus population forms Port Nevarellon's underclass, now formally located in The Sunken Ward (Muddy Docks + the still-undeveloped Cinder Row) | Corvus refugees | Five Duchies.md, The Sunken Ward.md |
| ~20 years ago | Dolly Sisters found The Shades | Two sisters convert a derelict hull into the port's most secure lounge | Clara & Tessa Dolly | The Dolly Sisters.md |
| ~20 years ago | Garrick's crippling accident | A shifting cargo cannon crushes his leg, leaving a permanent limp | Garrick the Keelhauler | Garrick the Keelhauler.md |
| ~15 years ago | Haren unites the Wyvern Tail Pirates | Mutiny against a Twelgorn naval captain, then consolidation of independent raiders | Haren Twarde, Twelgorn Kingdom Navy | Captain Haren Twarde.md |
| ~13 years ago | Maeve's forgery arrest & recruitment | Garrick pays her execution bounty, brings her in to professionalize the Syndicate's books | Maeve the Scribe, Garrick | Maeve the Scribe.md |
| ~10 years ago | Marco becomes High Captain | Succeeds his mentor as the Company's senior field commander in Port Nevarellon; expands the Envoy Corps program he inherited | High Captain Marco | High Captain Marco.md |
| 5 years ago | Silas Bane's laboratory accident | Chemical burns scar his forearms/neck; source of his chronic cough | Silas Bane | Silas Bane.md |
| Decades ago (unspecified) | Morgran's mutation | Strikes a low-frequency God-Shard while prospecting; warps his dwarven biology | Morgran, Ubaraz Kingdom (his exile) | Morgran the Abomination.md |

## Artifacts / Named Items

| Name | Current location/owner | One-line summary | Mechanical rules ref | Established in |
|---|---|---|---|---|
| The Shard-Blade | Tythius De Vonce | Ancient heavy longsword forged from deep-rift iron | Not yet defined | Tythius De Vonce.md; dedicated file The Shard-Blade.md is empty |
| The Wyvern-Hide Banner | Captain Haren Twarde | Relic banner from a slain god-touched apex predator; channels a "ghost" manifestation in battle | 🔧 Not yet defined — narrative already describes a specific combat effect with no stat-block support | Captain Haren Twarde.md |
| Sun-Iron | Smuggled by the Iron-Anchor Syndicate | Unstable mineral component smuggled from the mountains to unlicensed alchemists | Not yet defined | Referenced in The Iron-Anchor Syndicate.md; dedicated file Sun-Iron.md is empty |
| Brine-Fire | Silas Bane | Volatile alchemical gel that ignites on contact with salt water; carried as glass spheres | 🔧 Not yet defined — narrative implies a specific weapon effect | Silas Bane.md |
| The Black Ledger | Clara & Tessa Dolly (hidden aboard The Shades) | Coded journal blackmailing High Quarter nobles tied to Iron-Anchor smuggling | Not yet defined | The Dolly Sisters.md |
| Iron-Burl | Silted Marshes / Divtown timber trade | Dense black marsh timber immune to sea-rot; core Divtown export | Not yet defined | Silted Marshes.md, Divtown.md, The Wyvern tail Pirates.md |
| Cindin | Common (sailors, laborers) | Sticky narcotic resin, chewed or dissolved in ale to numb pain | Not yet defined | Cindin.md |
| Nightshade (powdered) | Tessa Dolly | Concealed poison carried in a hollow ring | Not yet defined | The Dolly Sisters.md; dedicated file Nightshade.md is empty |
| The Brine-Glow Lanterns | Municipal (High Alchemist Guild) | Bioluminescent algae-lit street lanterns; target of Silas's monopoly plot | Not yet defined | Port Nevarellon.md; dedicated file is empty |
| The Golden Writ (Peace-Bond) | Landed citizens only | Legal permit (5 gold sovereigns) required to carry a martial weapon | Cost defined narratively (1,000 cp) — no mechanical rules-system tie yet | Law - The Council's Edicts.md, Economy - the Price of Survival.md |

## Terminology / Rules Cross-References

| Term | Definition (narrative) | Rules-system definition | Where used narratively | Where defined mechanically |
|---|---|---|---|---|
| Domain Tag | A prayer-effect granted by invoking a Saint/Paragon | Implies a Faith-check subsystem (TN, Pass/Fail resolution) | Religion - The pagan Pantheon...md (all 7 domains) | **NOT YET DEFINED** — specific TNs and resource costs are already written into this lore doc, ahead of any rules text. Still the top rules-crunch flag in the project |
| Momentum | Reward for passing a "Tactical Horizon" Faith check | Implied shared/party resource | Religion.md (Domain Tag: Tactical Horizon) | Not yet defined |
| Stress / Locked Stress | Currency spent or gained during Faith checks and combat fallout | Implied core resolution resource | Religion.md, Template - Faith Spells.md, multiple character docs | Not yet defined |
| TN (Target Number) | Difficulty threshold for a Faith check | Core resolution mechanic | Religion.md ("TN 8") | Not yet defined |
| Wound Threshold / Wound Slot | Physical damage capacity | Core combat mechanic | Religion.md (Pure Martyrdom domain tag), Template - Enemies.md | Not yet defined |
| Prowess / Reflex / Wits / Will | Core character stats | Core stat block | Template - Enemies.md | Not yet defined; no NPC has a filled stat block despite 20 named active NPCs |
| Skills (Melee, Athletics, Block, etc.) | Character skill list | Core stat block | Template - Enemies.md | Not yet defined |
| Landed / Un-Landed | Civic-legal status tied to property/deed ownership | Setting-level social mechanic, not combat/resolution | Law - The Council's Edicts.md; used consistently across Economy.md, Maccorrack.md, Garrick the Keelhauler.md | Well-integrated narratively; low risk, doesn't need a numeric tie |
| **Landed by Commission** | A Golden Company officer's commission is treated as equivalent to a Guild Charter under the Ducal Accord, granting full Landed status without personal property | Extension of the existing Landed/Un-Landed social mechanic, not a new combat/resolution system | High Captain Marco.md, Sergeant Wren Cobb.md, First Envoy Isolde Vantry.md | No mechanical tie needed; note it's a *revocable* status for rank-and-file (lapses on discharge/desertion) |
| **The Second Contract** | Private, individually-negotiated Envoy retainer/engagement contracts, separate from the Company's main 99-Year city Contract | Setting-level economic/legal mechanic, not combat/resolution | The Golden Company.md | Well-integrated; priced in gold sovereigns, consistent with existing currency scale |
| **Writ of Voice** | Council-notarized document defining exactly what a negotiating Envoy may agree to on a client's behalf | Setting-level legal instrument | The Golden Company.md | No mechanical tie needed |

---

## Priority punch-list

### Resolved
1. ~~The Golden Company — empty file~~ → fully built out: faction profile, force structure, rank ladder, the Envoy Corps ("Second Contract"), four named NPCs.
2. ~~"The Shades" name collision~~ → the district-tier entry was a stale draft, retired from Port Nevarellon.md. Only the brothel carries the name now.
3. ~~The Sunken Ward — undefined/ambiguous gap~~ → now a full District, formal parent of Muddy Docks, with Cinder Row flagged as an intentional stub for future material.
4. ~~Two parallel canon-tracker files~~ → consolidated into this one.
5. ~~Chalced Kingdom founding implausibility~~ → resolved by the Twelgorn retcon; an exile-founded state could not plausibly own the navy, conscription and generational slave-brands five files already attributed to it. See Retcon log.
6. ~~Chalced wikilinks split across three inconsistent paths~~ → normalised to `000 Atlas/The Twelgorn Kingdom`.

### Still open, in priority order
1. **The Twelgorn Kingdom** — still no file at all; the single highest-priority remaining gap. Now confirmed as **12** referencing documents (previously recorded as 5), including two region docs, the Golden Company's stated vulnerabilities, and three NPC backstories.
1a. **Stale "Chalced Question" reference in The Golden Company.md** — the one reference the retcon pass could not reach (file mount returned zero bytes). Needs a manual rename and repoint. See Retcon log.
2. **Five ducal seats confirmed but fileless** — the naming question is resolved (see Merge finding #1), but **none of Castle Iron-Spire, Millhaven, Saltmere, Granite Spire or Corvus Spire has a dedicated file.** Castle Iron-Spire is a confirmed empty stub and is now the most-referenced empty file in the vault.
2a. **Vault file-integrity audit (NEW — see File integrity below)** — 12 zero-byte files, at least one of which is a mount/index desync rather than a genuine stub, plus two stale wikilink targets for the Five Duchies document. Should be cleared before the next editing pass.
3. **Whispering Coast / Five Duchies hierarchy conflict** — Austhal.md vs. Whispering Coast.md still disagree on which contains which.
4. **Religion.md's Domain Tags** — still the top instance of rules crunch written into a lore doc ahead of any actual rules text.
5. **Kaleb pronoun conflict** — Kaleb.md (he/him) vs. The Rusty Tankard.md ("she") — quick fix, still open.
6. **Filename/in-text naming mismatches** — Morgran the Abomination.md vs. "Deep-Draught"; The Cobalt Syndicate.md vs. "Cobalt Feather Syndicate"; Greywater Lagoon.md vs. "Grey Water" — none are lore problems, but will eventually cause broken links.
7. **Captain/Sergeant Vance rank inconsistency** — Faction - The Civic Constabulary.md's epigraph calls him "Sergeant Vance, Dock-Watch"; the body text calls him "Captain Elias 'Half-Step' Vance." Possibly two different people, possibly a drift — needs a decision.
8. **Grey Water Pirates vs. Wyvern Tail Pirates** — still unclear whether these are the same group under two names, or a general population vs. an elite fleet within it.
9. **Cinder Row** — intentional stub; needs real development whenever the Sunken Ward becomes central to actual play.

---

## How to use this

- **Before adding anything new**: search this file for the name/concept. If it's close to something existing, extend the existing entry instead of creating a new one.
- **When adding something new**: fill in every column, including "Established in" (which document/session introduced it) — this is what lets future contradictions get traced back to a source.
- **When a stat block or mechanical rule changes**: check the Terminology and Artifacts tables for narrative content that referenced the old version, and flag it for review.
- **Tone check**: new entries should read as high fantasy realism with grimdark stakes and small motes of hope — not generic fantasy sheen, not unrelenting bleakness.
