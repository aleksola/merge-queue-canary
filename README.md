
# Merge Queue Canary

This public repository provides durable, low-risk evidence for the Zcash
Foundation's GitHub merge queue configuration. It contains no production code,
secrets, packages, or deployment credentials.

Pull requests can add these marker files to exercise queue behavior:

- `.canary/fail-merge-group` fails only the integrated queue check.
- `.canary/slow-merge-group` delays only the integrated queue check.

The repository intentionally retains test pull requests and workflow runs as
evidence for future queue changes.
Public canary for GitHub merge queue and merge-freeze integrations
