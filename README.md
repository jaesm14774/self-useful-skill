# Self-useful Skills

Codex skills that capture repeatable engineering knowledge in a form other people can use without relying on the original author's memory.

## Skills

### `toi-engineering-handover`

Build or review repository-based engineering handover guides. It helps a new maintainer understand the system's purpose, business rules, main paths, safe operating tasks, and unresolved knowledge gaps from inspectable evidence. Version 0.9.0 adds a reader-first layout recipe for data handovers: orient the reader on the first screen, follow one data journey from source to consumer, separate processing strategies and exceptions, then expose operational and code references by task. It keeps the existing coverage gate, evidence boundary, linked multi-page handovers, diagram guidance, and optional contract-based drafting workflow.

The skill is a complete folder: keep `SKILL.md`, `references/`, and `assets/` together when copying or updating it.

## Use a skill

Copy the selected skill folder into your Codex skills directory, usually `$CODEX_HOME/skills/<skill-name>` or `~/.codex/skills/<skill-name>`. Preserve its internal folder structure so linked references and templates remain available.

## Add or update a skill

Keep each skill in its own top-level folder with a `SKILL.md` entrypoint. Put substantial, task-specific guidance in linked `references/` files and reusable output files in `assets/`. Update this index when adding a skill.
