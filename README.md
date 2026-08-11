# .github

Org-wide default community health files for the `planningalerts-scrapers`
GitHub org. Any repository in this org that doesn't provide its own
`CONTRIBUTING.md`, issue templates, or pull request template inherits the
ones here.

- `CONTRIBUTING.md` is maintained locally in this repo -- see that file for
  why it isn't synced from upstream.
- `.github/ISSUE_TEMPLATE/` and `.github/PULL_REQUEST_TEMPLATE.md` are synced
  automatically from [openaustralia/.github](https://github.com/openaustralia/.github)
  by `.github/workflows/sync-templates.yml`, which opens a pull request here
  whenever the upstream templates change.

## One-time setup

The sync workflow needs Actions to be able to create pull requests. This is
an org-wide setting (`planningalerts-scrapers` disables it by default, and it
can't be overridden per repo) -- enabled 2026-08-11 under Organization
settings -> Actions -> General -> Workflow permissions -> "Allow GitHub
Actions to create and approve pull requests".

The workflow itself uses only `actions/checkout` and the `gh` CLI, not any
third-party action, because this org's Actions policy allows only
GitHub-owned/verified actions.
