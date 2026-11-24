# Contributing to Engineering Notes

Thank you for taking the time to contribute. Engineering Notes publishes technical articles in which every measured claim is backed by code in this organisation. That shapes how contributions work: the goal is reproducible results, explained clearly.

This guide applies to every repository in the organisation. A repository may add its own `CONTRIBUTING.md` with setup details for its code. Where the two differ, the repository's guide wins.

## Ways to contribute

| You want to | Do this |
|---|---|
| Report code that fails, or gives results different from an article | Open a **Bug report** issue in that series repository |
| Point out an error in an article | Open an **Article correction** issue, with a source for the correct statement |
| Suggest a new experiment, scenario or improvement | Open an **Improvement** issue |
| Propose a topic, ask a question or share how you used something | Start a thread in [Discussions](https://github.com/orgs/Engineering-Notes/discussions) |
| Report a security problem | Follow the [security policy](SECURITY.md). Never open a public issue |

For anything larger than a small fix, open an issue first so the approach can be agreed before you spend time on it.

## Standards for code changes

1. **Results must be reproducible.** Every experiment must produce the same result on every run, or the README must say which numbers vary with timing and by how much.
2. **Explain any change to a published number.** If your change alters a figure quoted in an article, say which one, why, and whether the article needs a correction.
3. **Keep each folder self-contained.** One article, one folder, its own `package.json` and lockfile, its own `npm test`.
4. **Tests guard the claim.** `npm test` must exit non-zero if the approach the article recommends ever produces a wrong result.
5. **No secrets.** Use environment variables and placeholder credentials. Mocks of real services must say they are mocks.

## Commits and pull requests

- Use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/): `type(scope): summary`, where the scope is the article number or area, for example `fix(08): reject callbacks with mismatched amounts` or `docs(readme): update article table`.
- Allowed types: `feat`, `fix`, `test`, `docs`, `refactor`, `perf`, `ci`, `chore`, `build`.
- Keep commits small and focused. One logical change per commit.
- Name branches `type/short-description`, for example `fix/08-amount-check` or `feat/ds-03-raft-election`.
- Open the pull request against `main`, fill in the template, and make sure every CI check passes. Pull requests are merged with **rebase and merge**, so each commit lands on `main` as written.

## Writing standards for documentation

- Plain, precise English. Short sentences. No marketing language.
- Cite primary sources: specifications, RFCs, official documentation, papers.
- Units and conditions with every number: what was measured, on what, how many runs.

## Review

The maintainers review every pull request. Expect a first response within five working days. Reviews focus on correctness, reproducibility and clarity. Disagreement about technical claims is settled with evidence: a source, a specification or a reproducible run.

## Licence

By contributing, you agree that your contributions are licensed under the licence of the repository you contribute to, which is MIT unless stated otherwise.
