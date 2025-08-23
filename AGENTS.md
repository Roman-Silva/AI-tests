# AGENTS.md
This file guides Codex (AI agent) when generating or modifying code in this repository.

## Project Setup
- Always initialize a clean project structure if the repo is empty.
- Include a `README.md` with setup and usage instructions.
- Add a `.gitignore` suitable for the language/framework.

## Coding Conventions
- Follow language-specific best practices (e.g., PEP8 for Python, StandardJS for Node).
- Use clear, descriptive variable and function names.
- Document public functions and modules with docstrings/comments.

## Testing
- Every new feature should include at least one unit test.
- Use the recommended test framework for the language:
  - Python → pytest
  - Node.js → Jest
  - Rust → cargo test
- Ensure `npm test`, `pytest`, or `cargo test` passes before committing.

## Dependencies
- Use minimal dependencies; prefer standard libraries when possible.
- Pin versions in requirements files (`requirements.txt`, `package.json`, `Cargo.toml`).

## Documentation
- Update `README.md` when adding new features.
- Include code examples in docs when useful.

## Commit & Pull Requests
- Commit messages should be concise but descriptive (e.g., "Add reverseWords function with unit tests").
- Open a Pull Request if the change touches multiple files or is non-trivial.

## Additional Notes
- Prefer cross-platform solutions (Linux, macOS, Windows).
- Always run linting/formatting before committing.
