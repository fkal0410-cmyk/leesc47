# Codex Cloud Development Workspace

A minimal, language-agnostic repository for developing projects with OpenAI Codex Cloud.

## Project status

- No programming language, framework, runtime or dependencies have been selected.
- There is no application to run and no automated test suite yet.
- No project secrets are stored in this repository.

## Repository files

- `README.md`: project overview and development workflow
- `AGENTS.md`: instructions for Codex and coding agents

## Development workflow

1. Define the requirements before choosing a language or framework.
2. Create a separate branch for each change; avoid committing directly to `main`.
3. Install only required dependencies and document why they are necessary.
4. Add documented setup, run, and test commands after selecting a runtime.
5. Run relevant checks; report missing tests and failures accurately.
6. Open a pull request to review changes before merging.

## Codex Cloud configuration

Use the default cloud environment initially, without a custom setup script. Configure a runtime, dependency installation, and required network domains only when the project needs them. Add sensitive values using environment secrets rather than tracked files.

## Validation

At this stage, verify that `README.md` and `AGENTS.md` exist, and review their contents. No executable tests are available until application code is added.

See `AGENTS.md` for further rules.
