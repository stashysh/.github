# Contributing to Stashy

Thanks for your interest in Stashy! Bug reports, ideas, and pull requests are all welcome.

## Before you start

- **Questions and ideas** — start a thread in [Discussions](https://github.com/stashysh/.github/discussions).
- **Bugs** — open an issue in the relevant repository using the bug report template.
- **Larger changes** — open an issue first so we can agree on the approach before you write the code.

## Pull requests

1. Fork the repository and create a branch from `main`.
2. Keep the change focused: one fix or feature per pull request.
3. Make sure the checks pass locally:
   ```bash
   go vet ./...
   go test ./...
   ```
   In [stashy](https://github.com/stashysh/stashy), run `buf generate` first if you changed anything under `proto/`.
   In [desktop](https://github.com/stashysh/desktop), also run `npm run check` in `frontend/`.
4. Update the README or docs if behavior changes.
5. Open the pull request with a clear title — it becomes the commit message, since we squash-merge.

Maintainers label pull requests (`feature`, `fix`, `breaking`, …) to build the release notes.

## License

By contributing, you agree that your contributions are licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
