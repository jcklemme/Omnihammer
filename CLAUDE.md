# CLAUDE.md — OmniHammer Project Instructions

This file provides persistent context for Claude across all sessions working on this project.
Read this file at the start of every session before doing anything else.

---

## Project

**OmniHammer** is a fan-made fork of ProHammer Classic — a simulationist tabletop miniatures wargame
built on the Warhammer 40,000 3rd–7th edition rule set. It is not affiliated with Games Workshop.

**Repository:** https://github.com/jcklemme/Omnihammer

**Core rules source:** Omnihammer/CORE RULES/*.md
Always read the source document before making claims about specific rules.
Do NOT assume OmniHammer rules match any official Games Workshop edition.

---

## Role

Claude assists with:

- **Converting rules chapters to Markdown** — converting `.docx` source content into clean `/rules/*.md` files
- **Drafting rule change proposals** — writing up proposed changes for discussion, grounded in the rules text
- **Reviewing and critiquing rule text** — identifying ambiguities, contradictions, or edge cases
- **Managing Issues and PRs** — drafting Issue text, PR descriptions, labels, and responses to community feedback
- **Writing codex content** — drafting unit datasheets and codex entries compatible with OmniHammer rules

The **project owner (you) makes all design decisions.** Claude analyzes, drafts, and proposes.
Claude does not commit to design conclusions without your sign-off.

---

## Repository Structure

```
/Core ruless/          — One .md file per section
/CODES/           — Folders for faction rules and profiles
CLAUDE.md        — This file
CHANGELOG.md     — Append-only record of all rule changes
```

---

## Key Files to Check Each Session

- `CHANGELOG.md` — What has changed recently
- The relevant `/CORE RULES/*.md` chapter if working on a specific section
- The relevant `/CODEX/*/*.md` files if working on faction specific information

---

## Locked Design Decisions

The following are intentional design pillars. **Claude must never propose changing these.**
If a rule change would undermine one of these, flag it explicitly rather than silently working around it.

1. **No pre-measuring** — Players commit to actions before measuring distances. This is core to the simulationist identity of OmniHammer.
2. **Reaction system** — Return Fire!, Stand & Shoot!, and Overwatch are fundamental to breaking up "I go, you go" gameplay. Do not propose removing or significantly weakening them.
3. **Simulationist over gamified** — Rules should model war, not optimize for speed-rolling or abstraction. When trade-offs arise, favor the simulationist option.
4. **Structure points replacing hull points** — The structure point system for vehicles is locked. Do not propose reverting to hull points.

---

## Rules Formatting Conventions

All rules Markdown must follow these conventions, drawn from the source document's own formatting system:

| Element | Markdown | Example |
|---------|----------|---------|
| Universal Special Rules | `***bold-italic***` | ***Fleet*** |
| Key Terms | `**BOLD UPPERCASE**` | **UNIT** |
| Rule cross-references | `**BOLD UPPERCASE**` | See **COHERENCY** |
| Important notes | `**Bold sentence.**` | **Models may not move through enemy models.** |
| Optional rules | blockquote with OPTIONAL RULE! prefix | see below |
| Tables | Standard Markdown tables | — |

Optional rule format:
```markdown
> **OPTIONAL RULE! RULE NAME**
> Rule text here.
```

---

## Working Conventions

- **Always read the source document before writing rules content.** Do not rely on memory of official 40K editions.
- **One change at a time.** When drafting rule proposals, address one rule or interaction per proposal.
- **Ask before assuming.** If a rule is ambiguous and the correct interpretation affects the work at hand, ask rather than picking one silently.
- **Reference the design principles.** When critiquing or proposing rules, ground the reasoning in OmniHammer's stated design principles (from `01-introduction.md`).
- **Flag locked decision conflicts explicitly.** If a community Issue or proposal would require changing a locked decision, say so clearly rather than finding a workaround.

---

## Commit / File Discipline

Claude cannot push to GitHub directly. The project owner manages all commits.
Claude generates file content; the owner copies it into the repo.

When providing file content:
- Always specify the exact file path
- Provide the complete file content, not just a diff, unless the file is very long
- Note in the conversation what changed and why, so the owner can write an accurate commit message

---

## Design Principles (Summary)

From the OmniHammer Core Rules introduction — these guide all rules work:

1. Celebrate the epic drama of Warhammer 40k and gritty infantry battles
2. Reward clever play over list building
3. Balance fairness with excitement — surprising but not punitive
4. Emphasize intuitive rules — simple is good, not at the expense of logic
5. **Simulationist over gamified** *(locked)*
6. Emphasize position, maneuver, and terrain
7. Everyone is here — if there was a model for it, there should be rules for it
8. A love letter to 40k — pull the best from 2nd–10th edition
