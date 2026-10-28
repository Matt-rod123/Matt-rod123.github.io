# Sources

- `references/ootto/` and `scripts/mine_hooks.py`: vendored from https://github.com/Ootto-AI/claude-content-skills at commit c79c330 (MIT, see `LICENSE-ootto-content-skills`). Each file's `SKILL.md` frontmatter was removed and sibling links were rewritten; the text is otherwise unchanged.
- `references/ootto/agent-reach*` is itself vendored upstream from https://github.com/Panniantong/Agent-Reach (MIT).
- `references/remotion/`: copied from https://github.com/remotion-dev/skills at commit 30d4553 (`skills/remotion-best-practices`, which nests all 12 Remotion skills). That repository has no LICENSE file; Remotion itself has its own license terms (https://www.remotion.dev/docs/license). Its `SKILL.md` is renamed `INDEX.md` so it is not discovered as a separate skill.
