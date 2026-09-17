# Movement in the world:

- Scale: 1 Square = 5ft. Medium creatures occupy 1 square and move 30 ft (6 squares) per action.
    
- Threat zone: Threaten all adjacent 8 squares (5ft radius).
    
- Provoking: Leaving a Threat Zone normally grants the enemy a Aggressor action - strike with Advantage.
    
- The flanking Bonus (outnumbered): If you outnumber an opponent in melee, you have Advantage on the Clash.

- Rushed Stealth: Moving faster than half your Movement value whilst using Stealth imposes a disadvantage to your Stealth rolls.
    
- Difficult Terrain: Moving through difficult terrain (deep mire, heavy snow, shifting rubble) halves your Movement value and imposes disadvantage on all checks requiring mobility (such as Athletics or Acrobatics checks) made within it.
    
- Drawing a weapon is an free action. 

- Move is a per-creature stat, not a formula off Scale — a Small creature can outrun a Large one and vice versa (see Hardware's Mounts table: a Guard Dog outruns a Donkey despite matching Scale). 30 ft (6 squares) is the default for an unremarkable Standard-Scale creature; adjust it up or down when the fiction calls for it.

- Flying: A creature with the Flying Trait has a Fly Move value, used in place of its land Move while airborne. While flying, it ignores ground-level Difficult Terrain and obstacles entirely. A creature with both a land Move and a Fly Move picks one mode at the start of its movement each activation and can't mix the two in a single move. Leaving an enemy's Threat Zone by flying away still triggers the normal Provoking rule (a free Aggressor strike) unless another Trait, such as Skittering, says otherwise.
________________________________________________________________________
# The Environment:

## Illumination (Light & Sight)

Every square is in one of three light bands. They don't add a new modifier of their own — Dimly Lit and Pitch Black plug directly into Cover's existing Obscured tiers below, so "dim lighting" and "pitch black" in the Cover rules specifically mean these bands.

- **Well Lit:** Full, unobstructed light. No modifier.
- **Dimly Lit:** Equivalent to **Obscured** (see Cover, below) — Attacker has Disadvantage on the Attack. Also grants Advantage on Stealth checks made within it.
- **Pitch Black:** Equivalent to **Heavily Obscured** (see Cover, below) — Attacker has Disadvantage, target gains +2 to Defense. Also grants Advantage on Stealth checks made within it, and counts as an Obscured/Heavily Obscured position for anything that keys off one (e.g. the Cultist Assassin's Vanish).
- **No light source, no ambient light: Pitch Black.**

**Light source radii:**

| Source | Well Lit radius | Dimly Lit radius (beyond Well Lit) |
|---|---|---|
| Torch, Candle, Tindertwig (Community Supply Die abstraction), Lamp (common), Everburning Torch | 20 ft | 10 ft |
| Sunrod | 30 ft | 15 ft |
| Hooded Bullseye Lantern | 30 ft, forward cone only | None — hooded and directional, no ambient spill |

- **The halving rule:** Unless a source says otherwise, its Dimly Lit ring extends half again as far as its own Well Lit radius (the baseline torch: 20 ft Well Lit, then 10 ft more of Dimly Lit — 30 ft total before Pitch Black).
- **Overlapping light:** Where two sources' radii overlap, use whichever band is brighter for that square. Light doesn't stack past Well Lit.

## Cover (The Environmental Shield)

Being Obscured acts as a direct negative modifier to the attacker's roll. 

-  **Obscured (Thick underbrush, dim lighting [see Illumination, above], smoke):** You can track the target, but you are guessing their movements.
    
    - **The Mechanic:** Attacker has **Disadvantage** on the Attack.
        
- **Heavily Obscured (Pitch black [see Illumination, above], dense fog, swirling magical static):** You are effectively fighting blind. You might know they are in the zone, but you cannot pinpoint them.
    
    - **The Mechanic:** Attacker suffers **Disadvantage** on the Attack, and the target gains a **+2 bonus to their Defense roll**, representing the attacker’s inability to find a viable opening.

Physical barriers reduce the power of an incoming attack. They are rated by how much Impact they absorb.

-  **Partial Cover (Crates, low walls, a thin pillar):** The target is protected by a solid object, but not fully enveloped.
    
    - **The Mechanic:** When the target is hit, they may spend their **Block** or **Brace** action value to reduce the incoming Impact by 2.
        
- **Full Cover (Stone walls, reinforced iron doors, heavy portcullis):** The target is entirely hidden behind a physical object that can stop projectiles and heavy strikes.
    
    - **The Mechanic:** You cannot Strike a target in Full Cover unless you first spend an Action to destroy or bypass the cover. If an area-of-effect ability is used, the cover absorbs the full Impact value of the attack before the target is affected.
    

### \[DEV NOTE\] Material Penetration (Optional Realism Rule) 

- If a character is behind a wooden door (Light Cover, -2), and an attacker hits them using an armor-piercing weapon (like a Heavy Arbalest) or  maneuver like Deadly Aim, the shot completely shatters the cover. The target takes full damage, and the cover is destroyed for the rest of the fight.
    \[/DEV NOTE\] 

### Firing Into Combat (The Risk of Friendly Fire)

When a character shoots at an enemy that is actively engaged in melee with an ally, two things happen:

- *The Chaos Penalty:* The attacker suffers disadvantage to their attack roll. (The shifting bodies essentially act as obscured).
    
- *The Friendly Fire Trigger:* If the attack roll fails, and either of the 2d6 dice shows a natural "1", the projectile strikes an engaged ally instead.
    

- *The Resolution:* You immediately compare that same failed attack total against your Ally's Wound Threshold and resolve impact as normal. 
    
________________________________________________________________________
### ENVIRONMENTAL HAZARDS (Survival & Athletics)

High Fantasy heroes journey across brutal landscapes. In this system, the environment attacks your Stress track before it attacks your Wounds.

- *The Mechanic:* When facing severe conditions (a blizzard, a scorching desert, freezing water), the GM calls for a Hazard Check—usually 2d6 + Survival to navigate it safely, or 2d6 + Athletics to physically endure it, against TN 8.
    
- *The Cost of Failure:* Failing a Hazard check inflicts 1d3 Locked Stress (or more, depending on severity).
    
- *The Death Spiral:* if a character's Stress limit is maxed out by a Hazard, any further Stress instantly converts into Wounds. This means a character can literally freeze to death or die of exhaustion without ever taking a sword swing.
_______________________________________________________________________
# The Hazard Roll (Trap Resolution)

Traps and environmental hazards do not deal flat damage. When triggered, the GM makes a Hazard Roll (2d6 + the trap's Hazard Power) to generate a Strike Total, representing the speed, weight, or lethality of the mechanism.

How the trap resolves depends entirely on the player's awareness.

#### 1. The Unaware Target (The Ambush)

The player fails to spot the tripwire, or opens the chest without checking for a poison needle.

- The Resolution: The player is caught flat-footed, but not helpless — they may still act as the Reactor in a Clash against the trap's Hazard Roll, at Disadvantage, using Dodge only. A body that never saw the threat coming can still flinch away from it; it can't raise a shield or intercept a blade it never registered, so Block and Parry stay off the table regardless of what a given trap allows an Aware target.
- The Math: As with an Aware target, the Margin between the trap's Hazard Roll and the player's (Disadvantaged) Dodge determines the final Impact. A Margin 3+ win still avoids the hazard entirely and generates 1 Momentum — a lucky flinch is still a lucky flinch.
- The Armor Check: On a loss, compare the resulting Impact against the player's Wound Threshold as normal — meeting or exceeding it inflicts a Wound, falling short inflicts 1 Dissonant Stress.
    

#### 2. The Aware Target (The Desperate Reaction)

The player spots the pressure plate but is forced to leap across it, or they deliberately trigger the swinging axe to study its timing.

- The Resolution: The player knows the threat is coming and acts as the Reactor in a standard Clash against the trap's Hazard Roll.
    
- Choosing the Defense: Unless the specific trap dictates a required reaction (e.g., a room-filling poison gas might strictly require a Dodge to reach the door), the player can choose their defense:
    

- Dodge: Attempting to completely physically avoid the mechanism.
    
- Block: Raising a heavy shield to absorb a dart volley or falling rocks (subtracting their Shield Value from the Impact, per the standard Block Reactor action, if they lose the Clash).
    
- Parry: Using a weapon to jam the gears or bat away a swinging blade.
    

- The Math: Just like in combat, the mathematical Margin between the trap's roll and the player's defense roll determines the final Impact. If the player wins the Clash, they avoid the hazard entirely and generate 1 Momentum for their flawless reflexes.
    

### Example Hazards in the Engine

- Corpse-Rust Dart Trap (Hazard Power +3):
    

- Specifics: A hidden wall-shooter.
    
- Aware Requirement: If aware, the player can Block or Dodge, but cannot Parry the tiny projectiles.
    

- Crushing Iron Portcullis (Hazard Power +6):
    

- Specifics: A massive gate dropping from the ceiling.
    
- Aware Requirement: Must Dodge to roll under it. Attempting to Block or Parry such massive weight automatically fails, resulting in the player becoming Anchored beneath the iron.

### Falling (Height as a Hazard)

A fall is resolved as a Hazard Roll like any other trap — the ground doesn't care whether the drop came from a trap, a shove, or a bad jump.

| Fall Height | Hazard Power |
|---|---|
| Short (10–20 ft) | +2 |
| Medium (20–40 ft) | +4 |
| Long (40 ft+) | +6 |

- **Aware (a controlled fall):** A character who chooses to fall, or sees it coming with enough time to react, resolves it as an Aware target: Dodge only — you can't Block or Parry a landing. Winning the Clash means a hard but controlled landing; the Margin sets the final Impact per the standard Aware rules.
- **Unaware (a genuine surprise):** Shoved from behind, a trapdoor sprung with no warning, or falling unconscious — resolved as Unaware per the normal rules: the Hazard Roll total becomes Impact directly against Wound Threshold, no Defense allowed.
- **Landing on something worse than ground:** If the fall ends on spikes, rubble, or another hazard, add that hazard's own Hazard Power to the fall's rather than rolling twice.


________________________________________________________________________
# THE SOCIAL ENGINE (Influence & Resolve)

# THE SOCIAL ENGINE (Influence & Resolve) — Revised

In High Fantasy Realism, a silver tongue is just as dangerous as a drawn sword, but it isn't mind control. Social encounters use Influence (to push your agenda) opposed by the target's Resolve (or simply Will, if they lack the skill).

### The Stance System

NPCs have four basic social stances, forming a single ladder: **Hostile → Unfriendly → Neutral → Friendly.**

- **Hostile:** Actively opposed. Will act against the party — refuse service, raise an alarm, draw a weapon, sabotage where possible.
- **Unfriendly:** Wary, distrustful, uncooperative — but not yet acting against the party. The default state for someone who has reason to dislike or distrust the party but hasn't been pushed to outright opposition.
- **Neutral:** No strong opinion either way. The default starting state for anyone the party hasn't meaningfully interacted with.
- **Friendly:** Genuinely won over. Will help, vouch, take modest risks on the party's behalf.

**The Mechanic:** To change an NPC's stance or convince them to do something risky, roll an opposed check: **2d6 + Influence vs. 2d6 + Resolve.**

- **Standard Success (Margin 0–4):** Shift the NPC's stance **one step** toward the direction you were pushing (e.g., Hostile → Unfriendly, or Neutral → Friendly). Alternatively, if not attempting a stance shift, they agree to a request that doesn't put them in immediate danger.
    
- **High Success (Margin 5+):** Shift the NPC's stance **two steps** toward the direction you were pushing. This is a deliberate, flat rule — a High Success always moves exactly two rungs, never jumping straight to the opposite pole regardless of where the NPC started. Going from Hostile all the way to Friendly in a single roll still requires either two separate successful checks, or one High Success from an Unfriendly starting position.
    
- **Leverage (Modifiers):** The GM applies a +2 or -2 modifier based on the fiction. Bribing a greedy guard is +2. Threatening a fanatical cultist is -2.


________________________________________________________________________

## Touchpoint: Existing Feats, Spells, and Effects Referencing "Hostile" or "Friendly"

Any existing rule that triggers off an NPC being specifically "Hostile" or "Friendly" should be re-checked under this revision, since Hostile now sits one additional rung further from Neutral than it did before — a creature that was "almost Hostile" under the old 3-state model may now sit at Unfriendly instead, which doesn't trigger the same effects. No specific touchpoints have been identified yet requiring a fix, but this is the kind of terminology drift worth a deliberate audit pass rather than assuming it's silently fine.

    
(dev note) think about using the below success ladder.
- Messy Success (Margin 0–2): You shift their stance up one level, or they agree to a minor request—but there is a complication. They demand a bribe, hold a grudge, or agree but warn others about you.

- Clean Success (Margin 3–4): You successfully shift their stance up one level, or they agree to a request that doesn't put them in immediate danger, with no strings attached.

- Exceptional Success (Margin 5+): They are entirely won over or deeply terrified. They will take significant risks for you, immediately surrender, or become Friendly.
    

- *Leverage (Modifiers):* The GM applies a +2 or -2 modifier based on the fiction. Bribing a greedy guard is +2. Threatening a fanatical cultist is -2.
(/dev note)