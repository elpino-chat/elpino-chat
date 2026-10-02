# Contributing to Elpino

Thanks for helping improve Elpino. These are the defaults for every repository in the organization. A repository may
add its own `CONTRIBUTING.md` with more detail, and that one takes precedence.

Please read the [Code of Conduct](CODE_OF_CONDUCT.md). For anything security-related, see
[SECURITY.md](SECURITY.md) and **do not** open a public issue.

## Ground rules

- **Never commit secrets.** No `.env` files, API keys, tokens or customer data. If you commit one by mistake, tell a
  maintainer straight away so it can be rotated. Deleting the commit is not enough.
- **No customer data** in fixtures, screenshots or logs.
- **The brand is not open.** The Elpino name, logos and mascot are trademarks. The open-source licenses cover the
  code only.
- **License.** By opening a pull request you agree that your contribution is released under the license of the
  repository you are contributing to.

## Workflow

1. **Open an issue first** for anything larger than a small fix, so we can agree on the approach.
2. **Branch from `main`** with a short name: `feat/…`, `fix/…`, `docs/…`, `chore/…`.
3. **Keep changes focused.** One concern per pull request, and no unrelated reformatting.
4. **Run the repository's checks** before you push (the repo's own README lists them).
5. **Open a pull request** into `main` that explains what changed and why, and how you tested it.
6. **Address review feedback.** A maintainer merges once it is approved.

## Commit messages

We use [Conventional Commits](https://www.conventionalcommits.org/): `type(scope): summary in the imperative`.
Types: `feat`, `fix`, `perf`, `refactor`, `test`, `docs`, `build`, `ci`, `chore`.

## Good first contributions

Typo and copy fixes, accessibility improvements, documentation, translations and small UI polish are all welcome.
