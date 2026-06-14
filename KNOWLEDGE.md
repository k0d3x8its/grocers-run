# Grocer's Run Knowledge

> Curated facts about this codebase. Promoted via /checkpoint or /remember.
> Committed with the repo — not a session file.

---

## Engine
- Built on Godot 4.4, now on **Godot 4.6**. The engine rewrote `*.import` metadata
  and bumped `project.godot` (`config/features` → 4.6, boot_splash config). Verified
  the game still runs after the upgrade (manual test, 2026-06-14).
- `*.import` files are required and tracked — Godot generates one per imported asset;
  they hold import settings + the `uid://` that scenes reference. Do not delete.
