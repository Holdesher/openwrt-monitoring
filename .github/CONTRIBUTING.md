# Contributing

Thanks for taking the time to contribute.

## Before you start

- Open an issue to discuss significant changes before implementing them.
- Read and follow the [Code of Conduct](CODE_OF_CONDUCT.md).
- For security issues, do **not** open a public issue — see [SECURITY.md](SECURITY.md).

## Development workflow

1. Fork the repository and clone your fork.
2. Create a branch from the default branch:
   - `feat/<short-description>` for features
   - `fix/<short-description>` for bug fixes
   - `docs/<short-description>` for documentation
   - `chore/<short-description>` for maintenance
3. Install dependencies and set up the project as described in the repository
   `README.md`.
4. Make your changes. Keep them focused: one logical change per pull request.
5. Add or update tests when behavior changes.
6. Run the checks defined by the project (lint, typecheck, tests). See the
   `README.md` and the project configuration for the exact commands.
7. Commit using [Conventional Commits](https://www.conventionalcommits.org/):
   `feat: add ...`, `fix: handle ...`, `docs: update ...`, `chore: bump ...`.

## Pull requests

- Describe **what** changed and **why**, and link the related issue.
- Update documentation, examples, and configuration when behavior changes.
- Keep the diff minimal; avoid unrelated refactors and formatting noise.
- Make sure CI passes.
- A pull request is merged after at least one maintainer approval.

## Code style

Match the existing style of the project. Do not introduce new dependencies or
tooling without discussing it first.

## License

By contributing, you agree that your contributions are licensed under the
terms described in the project's [LICENSE](../LICENSE).
