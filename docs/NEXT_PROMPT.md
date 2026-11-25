# Next prompt: 36-3003.Z

Updated: 2026-11-25. Keep this file at 40 lines or fewer. The current request overrides it.

## State

- Kit: 11.1.0 (a629550) on branch `claude/kit-11.1.0-sync`, lane C pull request; merge is for the fleet coordinator (master plan P5). Check: `python3 scripts/check_lock.py --status`.
- Role word: the Maintainer (kit 11.0.0). `.check` has `dod-security: on`.
- Package mode: branch `claude/kit-package-mode`, its own lane C pull request, stacked on the sync branch (`.claude/skills/kit-update/SKILL.md` "Package mode"). After it merges, a new session runs `scripts/check.sh --kit-install` (the SessionStart hook does it).

## Open (in order)

1. Merge the kit 11.1.0 sync pull request (the coordinator).
2. Merge the package mode pull request after the sync (the coordinator).
3. SECURITY.md names docs/threat-model.md, which the kit does not sync: a kit follow-up.
4. Add the first project rules to AGENTS.md "Project rules".

## Needs the Maintainer

- None.

## Do not

- None yet.
