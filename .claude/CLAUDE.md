# Grocer's Run — Claude Config

## Project Overview
**Type:** Game (Godot)
**Stack:** GDScript + Godot 4.6
**Goal:** Arcade-style game where you slide a grocery cart left/right to catch falling groceries and avoid the mascot

## Conventions
- Commit format: conventional commits (feat:, fix:, docs:, chore:)
- Branch naming: feature/, fix/, docs/, chore/
- NEVER add `Co-Authored-By` lines to commit messages
- Code comments: explain the why, not the what

## Trello
- Board: Grocer's Run

## Skills
**Plan & design**
- `/brainstorm`   — design a feature from a rough idea (→ /grill-me → /write-plan)
- `/grill-me`     — stress-test a design before building (→ .work/FINDINGS.md)
- `/write-plan`   — turn a grilled design into .work/PLAN.md
- `/plan`         — create/update .work/PLAN.md
- `/sync-trello`  — push .work/PLAN.md Goals to the Grocer's Run board

**Build, debug, verify**
- `/tdd`              — red-green-refactor for features/bug fixes
- `/diagnose`         — disciplined bug/regression loop ([BUG] tag)
- `/run`              — launch the Godot game to see a change working
- `/verify`           — confirm a change behaves correctly in-app
- `/trust-but-verify` — evidence gate before any done/works/fixed claim
- `/code-review`      — review the current diff before a PR

**Ship & track**
- `/changelog`     — log changelog-worthy changes to CHANGELOG.md
- `/release-notes` — generate GitHub release prose from CHANGELOG
- `/remember`      — capture a durable fact to KNOWLEDGE.md
- `/dev-brief`     — morning/context-switch brief across projects

**Session lifecycle**
- `/handoff` / `/handoff-return` — fork a tangent / merge it back
- `/close`                       — lightweight session close (resume prompt)
- `/checkpoint`                  — durable end-of-session log + triage

## Session Rules
- Always read .work/PLAN.md, .work/FINDINGS.md, and .work/PROGRESS.md if they exist
- When I paste a re-entry prompt, treat it as ground truth for project state

## Current State
See .work/PLAN.md for active goals and progress.
See .memory/SESSION-LOG.md for recent session history.
