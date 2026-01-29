# cuioss Community Health Files

This repository contains default community health files for the **cuioss** organization.

## What's Included

| File | Purpose |
|------|---------|
| `SECURITY.md` | Security vulnerability reporting policy |
| `CONTRIBUTING.md` | Contribution guidelines |
| `CODE_OF_CONDUCT.md` | Community code of conduct |
| `ISSUE_TEMPLATE/` | Issue templates (bug report, feature request) |
| `PULL_REQUEST_TEMPLATE.md` | Pull request template |
| `profile/README.md` | Organization profile (shown on org page) |

## How It Works

These files are **automatically inherited** by all repositories in the cuioss organization that don't have their own versions.

- If a repo has its own `SECURITY.md` → repo's version is used
- If a repo has no `SECURITY.md` → this org-level file is used

## Customization

Repositories can override any file by creating their own version. For example, a project with specific contribution requirements can have its own `CONTRIBUTING.md`.

## Related

- [cuioss-organization](https://github.com/cuioss/cuioss-organization) - Reusable workflows, scripts, and infrastructure configuration
