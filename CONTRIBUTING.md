# Contributing to the Cloud Code Workshop

Thank you for your interest in contributing! To keep the workshop material high‑quality and consistent, please follow these guidelines:

## Pull Request Process

1. **Fork the repository** and create a new branch for your changes.
2. **Make your changes** – ensure they are limited to the appropriate user folder (if applicable) and do not modify unrelated parts of the project.
3. **Add tests** for any new functionality or bug fixes. Tests should be placed under the existing `tests/` directory and must pass locally.
4. **Run the test suite** to confirm everything works:
   ```bash
   npm test   # or the appropriate test command for the language
   ```
5. **Open a Pull Request** against the `main` branch.
6. **Peer Review** – at least one other contributor must review and approve the PR before it can be merged.
7. **Merge** – once approved and all checks pass, the PR can be merged.

## Code Style & Testing

- Follow the project's linting and formatting rules (configured via `.eslintrc`, `prettier`, etc.).
- All new code must include unit tests with clear coverage of the implemented functionality.
- Ensure that CI checks (lint, tests, type checking) pass before requesting review.

## Documentation

- Update relevant documentation files (`README.md`, `AGENTS.md`, etc.) when your changes affect usage or guidelines.
- Keep documentation concise and beginner‑friendly.

Thank you for helping make this workshop a great learning experience!
