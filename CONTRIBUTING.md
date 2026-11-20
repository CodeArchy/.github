# Contributing to CodeArchy

Thanks for your interest in CodeArchy! This is the default guide for every repository in the [CodeArchy organization](https://github.com/CodeArchy). If a repository has its own `CONTRIBUTING.md`, read that one too. It covers setup, building and testing for that project.

## Ways to contribute

- **Report a bug or request a feature.** Open an issue using one of the templates.
- **Ask a question or share an idea.** Use [Discussions](https://github.com/CodeArchy/codearchy/discussions).
- **Improve the docs.** Typos, clarifications and examples are all welcome.
- **Send code.** Look for issues labelled `good first issue` or `help wanted`. For larger changes, open an issue or discussion first so we can agree on the approach before you invest time.

## Pull request workflow

1. Fork the repository and create a branch from `main`.
2. Keep each PR focused on one change. Add or update tests where it makes sense.
3. Write the PR title in [Conventional Commits](https://www.conventionalcommits.org/) style, for example `feat: add Kotlin import resolution` or `fix: handle empty workspace`. PRs are squash-merged, so the title becomes the commit message.
4. Make sure every commit is signed off (see below).
5. Open the PR and fill in the template. A maintainer will review it.

## Developer Certificate of Origin (DCO)

CodeArchy uses the [Developer Certificate of Origin](https://developercertificate.org/) instead of a CLA. By signing off a commit, you certify that you wrote the change, or otherwise have the right to submit it, under the project's open-source license.

Sign off by adding `-s` when you commit:

```bash
git commit -s -m "fix: handle empty workspace"
```

This adds a line like `Signed-off-by: Your Name <you@example.com>` to the commit message. The name and email must match the commit author. An automated DCO check runs on every pull request.

Forgot to sign off? Fix the most recent commit with `git commit --amend -s --no-edit`, or all commits on your branch with `git rebase --signoff main`, then force-push your branch.

## Code of Conduct

Everyone taking part in CodeArchy is expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Security issues

Please **don't** open public issues for security vulnerabilities. See [SECURITY.md](SECURITY.md).
