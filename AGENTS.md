# Codex Agent Instructions

## Scope and planning

- Inspect the repository and clarify the task scope before making changes.
- Preserve existing behavior and avoid unrelated edits.
- Do not introduce a programming language, framework, runtime, or dependency without a concrete requirement.
- Prefer small, understandable and reversible changes.

## Security

- Never commit API keys, passwords, access tokens, private keys or other secrets.
- Use secret management or environment variables when credentials are needed.
- Avoid printing secrets in logs, test outputs, or pull requests.
- Request network access only for required domains and justify access.
- Never add secrets to `README.md`, `AGENTS.md`, or example configuration files.

## Dependencies and environment

- Keep setup scripts empty until the project requires installation steps.
- Install only packages required for the current task; explain their purpose.
- Pin or lock dependencies according to the selected ecosystem when appropriate.
- Document exact setup, run, and test commands after the project stack is chosen.

## Testing

- Run applicable checks after changes and summarize their actual results.
- If no tests exist, explicitly say so; do not claim tests passed.
- Diagnose errors and record unresolved issues.
- Check that sensitive files and generated artifacts are not accidentally committed.

## Git workflow

- Work on a separate feature or setup branch, not directly on `main`.
- Make focused commits with descriptive messages.
- Submit proposed changes through a pull request.
- Do not merge into `main` without explicit user approval.

## Reporting

Provide the final report in Korean, including:
1. Modified files
2. Added or removed dependencies
3. Commands executed and validation results
4. Errors, limitations, and unresolved issues
5. Items requiring user review before publishing
