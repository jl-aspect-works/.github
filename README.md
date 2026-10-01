# JL Aspect Works GitHub Configuration

Shared organization profile assets and default contribution/security guidance for JL Aspect Works.

## Contents

- [Organization profile](profile/readme.md) and its graphics in `assets/`
- [Default security policy](SECURITY.md)
- [Default contribution guidelines](CONTRIBUTING.md)
- [Bug report and feature request templates](.github/ISSUE_TEMPLATE/)
- [Pull request template](.github/PULL_REQUEST_TEMPLATE.md)
- [Repository checks](.github/workflows/repository-checks.yml) for image integrity, local Markdown links, and immutable Action references

GitHub applies supported community files from this public `.github` repository as defaults when a repository does not provide its own corresponding files. Repository-specific policies take precedence. Repository-specific issue template configuration overrides the default issue template directory. See [GitHub's default community health documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

The repository check workflow validates this repository; it is not automatically inherited by other repositories. This repository does not currently provide organization-wide workflow templates, funding configuration, or CODEOWNERS.

Branch protections and account/security settings are separate GitHub settings. File presence does not establish that those settings are enabled. Their verification record and proposed lightweight-repository rulesets live in [Engineering governance](https://github.com/jl-aspect-works/engineering/blob/main/docs/GITHUB_GOVERNANCE.md).
