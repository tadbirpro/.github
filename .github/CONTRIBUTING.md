# Contributing

Thank you for contributing. This guide applies to every repository in the organization unless a repository provides its own `CONTRIBUTING.md`.

## Before you start

- Search existing issues to avoid duplicates.
- Make sure the work is tracked by an issue created from the appropriate issue form. See [SUPPORT.md](SUPPORT.md) for which form to use.
- For larger or uncertain changes, agree on the approach in the issue before starting implementation.

## Issue hierarchy

```text
Epic
└── Feature
    └── Story
        └── Task
```

Link child issues to their parent as sub-issues. Bugs, Tech Debt, and Spikes can be linked to any related parent.

## Pull requests

- Keep each pull request focused on a single issue.
- Link the issue using a closing keyword such as `Closes #123` when the pull request fully resolves it.
- Complete the pull request template. Tick the "no impact" option in sections that do not apply rather than deleting them.
- Add or update tests for behavior changes.
- Update documentation, business rules, and ADRs when behavior or contracts change.
- Make sure CI passes before requesting review.

## Sensitive data

- Never commit secrets, credentials, or customer data.
- Sanitize logs, screenshots, and other evidence attached to issues and pull requests.
- Report security vulnerabilities privately as described in [SECURITY.md](SECURITY.md).

## Code of conduct

All contributors are expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
