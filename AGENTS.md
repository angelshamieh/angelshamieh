# AGENTS.md

## Cursor Cloud specific instructions

This is a **GitHub profile README repository** — it contains a single `README.md` file with no application code, services, or runtime dependencies.

### Development workflow

- **Lint**: `markdownlint-cli2 README.md` (installed globally via npm).
- **"Build/Run"**: The README renders on GitHub; there is no build step. Preview locally with any Markdown viewer or push to see the rendered result on the GitHub profile page.
- **Tests**: No automated test suite exists. Linting is the primary quality check.

### Notes

- There are no services to start, no databases, and no Docker containers.
- The only meaningful development action is editing `README.md` and validating it with the markdown linter.
