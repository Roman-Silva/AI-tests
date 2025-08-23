# AGENTS.md
This file guides Codex when generating or modifying code in this repository.

## Project Setup
- Always initialize the repo as a Python project if empty.
- Create a `main.py` as the entry point with example code.
- Add a `requirements.txt` file with pinned versions for dependencies.
- Add a `.gitignore` for Python (ignore venv, __pycache__, build, etc.).
- Provide a `README.md` with:
  - Setup instructions
  - How to run the app
  - How to run tests

## Coding Conventions
- Follow PEP8 style guidelines.
- Use type hints for all functions.
- Write clear docstrings for public functions, classes, and modules (Google-style).
- Keep functions small and modular.

## Testing
- Use `pytest` for all tests.
- Place tests in a `tests/` directory.
- Every new feature must include at least one unit test.
- Ensure `pytest` passes before committing.

## Dependencies
- Use `requirements.txt` for dependencies.
- Pin versions explicitly (e.g., `numpy==1.26.4`).
- Use standard library modules whenever possible to reduce dependencies.

## Documentation
- Update `README.md` when new functionality is added.
- Include short code examples in the README for new modules.
- If functionality is complex, generate a `docs/` folder with Markdown docs.

## Commit & Pull Requests
- Commit messages should be short and descriptive:
  - Example: `Add function to filter even numbers with pytest test`
- Group related changes into a single commit.
- Open a Pull Request if changes affect multiple modules or introduce new features.

## Additional Notes
- Code must be compatible with **Python 3.10+**.
- Ensure the code runs cross-platform (Linux, macOS, Windows).
- Prefer dependency management via `venv` or `poetry` (if explicitly requested).
