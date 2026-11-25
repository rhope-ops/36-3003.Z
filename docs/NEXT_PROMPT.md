# Next prompt: 36-3003.Z

Updated: 2026-11-25. Keep this file at 40 lines or fewer. The current request overrides it.

## State

- Kit: 11.1.0 (a629550), merged by PR 15 (2026-11-24). Check: `scripts/check.sh --kit-install`, then `python3 scripts/check_lock.py --status`.
- Role word: the Maintainer (kit 11.0.0). `.check` has `dod-security: on`.
- Package mode: on, merged by PR 16 (2026-11-24). 28 kit scripts come from the `archimedes-kit` package; the SessionStart hook installs it (`.claude/skills/kit-update/SKILL.md` "Package mode").

## Open (in order)

1. Kit follow-ups: SECURITY.md names docs/threat-model.md, which the kit does not sync; security.yml runs bandit without `--kit-install`, so it does not scan the package scripts.
2. Add the first project rules to AGENTS.md "Project rules".

## Needs the Maintainer

- None.

## Do not

- None yet.
