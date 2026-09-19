---
tags: [brute, log]
---

# Reconciliation Log

Parent: [[00-Persona]]

Purpose: this log exists so the **next** update to this vault doesn't have to re-derive what changed and why. When you fold in a new memo, rework, or case-history update, add an entry here first, then edit the affected rule file(s) directly — do not let the source memo circulate as a separate stale copy once it's merged in.

## 2026-09-19 — Vault created from consolidated Master Reference

**Sources folded into this baseline** (as identified by the user at creation time):

- Original Master AI Assistant Prompt
- July 28, 2026 — Demand Figures rework → merged into [[07-Damages-Valuation-Remedies]]
- July 30, 2026 — DOAS Coverage Findings memo → merged into [[08-Authority-and-Legal-Findings]]
- July 30, 2026 — harmonized Master Reference (the document that reconciled the above two)
- Case history through August 17, 2026

**What happened:** the harmonized Master Reference text (as it stood after the July 30 reconciliation) was split into the ten rule files in this vault ([[01-Role-and-Purpose]] through [[10-Lawful-Boundaries]]), given the persistent persona **B.R.U.T.E.** ([[00-Persona]]), and structured as an Obsidian vault + `CLAUDE.md` loader so future edits happen in one place per topic instead of in a linear monolithic prompt.

**Why split instead of kept as one file:** the original was a single long document; splitting by rule-category makes future updates (e.g. a new damages memo, a new coverage-findings memo) land in exactly one file each, and the wikilinks keep the cross-references (e.g. "loopholes must be labeled per the accuracy rules") explicit instead of implicit.

**Nothing substantive was changed** in this pass — this is a reorganization + persona wrapper, not a rewrite of the rules. If a future review finds the split introduced a drift from the source Master Reference, fix it here and note the correction below.

**Open items for the next update:**
- No prior versions of the Master AI Assistant Prompt, Demand Figures rework, or DOAS Coverage Findings memo were provided as separate files to this session — only the already-harmonized text. If those source documents still exist elsewhere (e.g. Google Drive, Notion), consider archiving or marking them superseded so they don't re-enter circulation as if current.
- Confirm jurisdiction(s) this vault is meant to cover (civil law only, no jurisdiction was specified) and add a `12-Jurisdiction-Notes.md` file if the user wants jurisdiction-specific carve-outs tracked separately from the general rules.

---

<!-- Add new entries above this line, newest first is fine as long as each entry is dated and says what changed / which files it touched. -->
