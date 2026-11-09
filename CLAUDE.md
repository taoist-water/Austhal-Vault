# Iron & Marrow vault — rules for Claude

This vault is highest-priority data. Months of work. Act accordingly.

## Writing to files
- Never write, edit, move, or delete a vault file without first showing TheTao the exact diff and getting explicit approval for that change.
- Subagents are read-only. Only the main session writes, and only after approval.
- Before a session that may write anything, check `git status` is clean and suggest a commit if it is not.

## Silos
- Rules design and worldbuilding are kept separate. Do not pull setting/worldbuilding content into rules work (or the reverse) unless TheTao explicitly says to integrate.

## Rules pipeline
When TheTao asks for a new or changed mechanic, run this sequence and stop for approval at the end:
1. `rules-drafter` — produce the draft and proposed edits.
2. `rules-breaker` — attack the draft. If it returns "rethink" or any Broken finding, report back before going further.
3. `continuity-auditor` — check the (possibly revised) draft against the rulebook and list ripple edits.
4. Present to TheTao: final rules text, breaker findings, auditor table, and a diff of every file that would change. Wait for approval.

TheTao may also call any agent on its own, e.g. "use rules-breaker on the Scrounger feat tree".
