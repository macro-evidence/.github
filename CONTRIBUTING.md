# Contributing to Macro Evidence

Thanks for your interest. This guide applies to every repository in the Macro Evidence organization unless a repository defines its own `CONTRIBUTING.md`.

## Current state

Macro Evidence is built and maintained by a single developer. There is no team yet, no formal review board, and no guaranteed response time on issues or pull requests. Treat this as an early-stage, solo-maintained project rather than one with an established maintainer team — that will change as the organization grows.

## Before opening an issue

- Search existing issues first — duplicates slow things down more than they help.
- For bugs: state what you expected, what happened instead, and how to reproduce it.
- For security vulnerabilities: **do not open a public issue.** See [SECURITY.md](SECURITY.md).

## Before opening a pull request

Given the current single-maintainer stage, unsolicited large pull requests are unlikely to be reviewed quickly, if at all. Open an issue first to discuss the change before investing significant time in it.

Small, self-contained pull requests — typos, broken links, a clear bug with an obvious fix — are welcome directly.

## Engineering standards

Repositories under this organization, starting with Macro Data Observatory, follow a documented set of engineering principles:

- **Necessity over novelty** — new tools, dependencies, and features are added only when they provide measurable value.
- **Simplicity over unnecessary complexity.**
- **Reproducibility** — environments and pipelines run on modest, free-tier hardware, without hidden or paid dependencies.
- **Documentation-first** — architectural decisions and non-trivial changes are documented alongside the code, not after it.

## Commit conventions

Commits follow [Conventional Commits](https://www.conventionalcommits.org/): `feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, `test:`, followed by a concise, present-tense description.

## Development environment

Platform repositories are built on Python, PostgreSQL, and Pandas, using free and open-source tools only. Setup instructions specific to a given repository live in that repository's own README.

## Questions

Open an issue, or reach the maintainer directly at [siddharth.chauhan@macro-evidence.com](mailto:siddharth.chauhan@macro-evidence.com).
