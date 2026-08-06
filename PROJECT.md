# Aetheris Development Project

## Purpose

Build Aetheris as a durable, internally consistent setting that inspires wonder, mystery, and exploration.

The current priority is the **world codex**. A campaign and individual session preparation will be developed as separate products that consume the codex without redefining it.

## Source of Truth

The Git repository is the canonical source of truth.

Chat conversations are design meetings. Decisions become durable only when they are written into the repository and committed.

## Product Boundaries

### Codex

Describes the setting as though no player characters exist. It contains world truths, common beliefs, disputed accounts, deliberate mysteries, places, people, factions, systems, and history.

### Campaign

Describes one possible story told within Aetheris. Campaign material may reference the codex but must not silently redefine it.

### Session Prep

Contains only what is needed to run a specific session: scenes, encounters, clues, likely NPCs, and table-facing notes.

## Workflow

1. Select a small, testable piece of work from the backlog.
2. Discuss its purpose and dependencies.
3. Update the relevant Markdown files.
4. Review the change against the Constitution and Design Philosophy.
5. Record canon decisions and known debt where appropriate.
6. Commit the finished work.

Finished work should not remain only in chat.

## Branching

`main` should remain coherent and usable.

Optional feature branches may use names such as:

- `feature/port-meridian`
- `feature/skyships`
- `feature/arcane-currents`
- `feature/void`

A lightweight workflow is preferred over process for its own sake.

## Definition of Done

A codex article is ready when:

- it has one clear purpose;
- it does not contradict existing canon;
- known facts, rumours, and GM-only information are distinguishable;
- deliberate mysteries remain deliberate;
- it provides enough usable detail for its current milestone;
- related articles are linked or named rather than duplicated.

## Worldbuilding Debt

Not every unfinished question requires an immediate answer.

Use the backlog for information that should eventually be developed. Use `TECHNICAL_DEBT.md` for temporary assumptions, placeholders, contradictions, or systems that work for now but need revision.

A deliberate mystery is not technical debt.
