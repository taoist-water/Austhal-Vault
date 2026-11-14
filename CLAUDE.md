# Iron & Marrow vault — rules for Claude

This vault is highest-priority data. Months of work. Act accordingly.

## Writing to files
- Never write, edit, move, or delete a vault file without first showing TheTao the exact diff and getting explicit approval for that change.
- Subagents are read-only. Only the main session writes, and only after approval.
- Before a session that may write anything, check `git status` is clean and suggest a commit if it is not.

## Rules and worldbuilding are blended
- Either side may be read freely when working on the other. Reviews check lore against the rules and the rules against lore.
- Worldbuilding decides what is true in the world; the ruleset decides how it plays. Where they disagree, log both sides in the canon tracker and bring it to TheTao. Do not quietly change either to match the other.
- Lore notes point to the rules rather than restating them, and flag `needs crunch` where no rule exists yet.
- Writing is unchanged on both sides: a diff first, per file. A change on one side that has consequences on the other is flagged with the proposed edit, not carried over until TheTao approves it. Rules edits go through the rules pipeline below.

## Rules pipeline
When TheTao asks for a new or changed mechanic, run this sequence and stop for approval at the end:
1. `rules-drafter` — produce the draft and proposed edits.
2. `rules-breaker` — attack the draft. If it returns "rethink" or any Broken finding, report back before going further.
3. `continuity-auditor` — check the (possibly revised) draft against the rulebook and list ripple edits.
4. Present to TheTao: final rules text, breaker findings, auditor table, and a diff of every file that would change. Wait for approval.

TheTao may also call any agent on its own, e.g. "use rules-breaker on the Scrounger feat tree".
