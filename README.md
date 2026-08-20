# .github

Organization-wide GitHub profile and default community health files for [Macro Evidence](https://github.com/macro-evidence).

## Purpose

This is Macro Evidence's public special `.github` repository. It owns the organization profile README and supplies default community health files to repositories that do not define their own corresponding files.

GitHub applies repository-local community health files before these defaults. Issue-template defaults have a stricter override rule: if a repository contains any files in its own `.github/ISSUE_TEMPLATE/` directory, GitHub does not use the default issue-template directory from this repository.

See GitHub's documentation on [default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) for platform behavior and precedence.

## Contents

| Path | Purpose |
|---|---|
| `profile/README.md` | Public organization profile content |
| `CODE_OF_CONDUCT.md` | Default contributor conduct policy |
| `CONTRIBUTING.md` | Default contribution guidelines |
| `SECURITY.md` | Default vulnerability-reporting policy |
| `PULL_REQUEST_TEMPLATE.md` | Default pull request template |
| `.github/ISSUE_TEMPLATE/bug_report.yml` | Default bug-report issue form |
| `.github/ISSUE_TEMPLATE/feature_request.yml` | Default feature-request issue form |
| `.github/ISSUE_TEMPLATE/config.yml` | Default issue-template chooser configuration |

This repository must remain public for GitHub to apply the supported defaults organization-wide.

## Ownership

Repository-specific setup, development, and usage documentation belongs in each repository's own `README.md`. Organization mission and platform scope, governance, documentation standards, and trademark policy are maintained in the [governance repository](https://github.com/macro-evidence/governance).

## License

Content in this repository is licensed under the [Creative Commons Attribution 4.0 International License](LICENSE) (CC BY 4.0).

That license governs the repository content; it does not itself grant rights to use Macro Evidence's names, marks, or visual identity. See the separate [Trademarks Policy](https://github.com/macro-evidence/governance/blob/main/TRADEMARKS.md).
