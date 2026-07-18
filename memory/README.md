# Memory Map

The agent uses these Markdown files as persistent memory.

| File | Purpose |
| --- | --- |
| `current-state.md` | Small, always-read snapshot of the latest state |
| `canon.md` | Enduring facts confirmed by the player or at the table |
| `build-decisions.md` | Character choices, alternatives, and reasoning |
| `inventory.md` | Current equipment, coins, and acquisition history |
| `sheet-audit.md` | Reconciliation notes for imported character sheets |
| `party.md` | Party members, capabilities, relationships, and coordination |
| `npcs.md` | Named non-player characters and what is actually known about them |
| `quests.md` | Active, completed, failed, and rumored objectives |
| `timeline.md` | One-line index of campaign sessions and major events |
| `open-questions.md` | Choices or ambiguities that still need player/DM answers |
| `sessions/` | Detailed, dated session notes |

Character mechanics live in `character/`. Memory records what became true and
why. Suggestions stay in character draft files or are labeled Proposed.

## After a Session

The player can paste rough notes in any format. The agent should:

1. Create `sessions/YYYY-MM-DD-session-NN.md` from the template.
2. Separate witnessed facts from theories and unclear recollections.
3. Update the timeline, party, NPC, and quest ledgers.
4. Update current HP, resources, equipment, spells, and money only when the notes
   establish their values.
5. Add unresolved contradictions to `open-questions.md` instead of guessing.
