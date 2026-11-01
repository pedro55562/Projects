# Petrobras — Development Guidelines

## Git Workflow

**Follow the established branching and collaboration strategy.**

When applicable, use the following conventions:
- `main`: stable releases.
- `dev`: integration and staging.
- `feat/<name>`: new features.
- `fix/<name>`: bug fixes.
- `refactor/<name>`: code restructuring.
- `docs/<name>`: documentation changes.

Development branches should generally originate from `dev`, with pull requests targeting `dev`.


## Git Submodules

**Treat submodules as independent repositories, each with its own development workflow.**

- Commit and push inside the submodule first, then update the pointer in the parent.
- Before opening a PR, check that every submodule pointer references a pushed commit (`git submodule status`).


## GitHub Issues and Pull Requests

**Use the established templates and keep project tracking consistent.**

Shared templates are located in:

- `~/Projects/petrobras/.templates/issue.md` — development tasks.
- `~/Projects/petrobras/.templates/pull_request.md` — pull request descriptions.

When drafting issues or pull requests:

- Follow the corresponding template.
- Write pull request titles and descriptions in English.
- Write GitHub issues in Brazilian Portuguese (pt-BR).