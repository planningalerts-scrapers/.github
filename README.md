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

For the sync workflow to open pull requests, an org owner needs to enable
**Allow GitHub Actions to create and approve pull requests** under this
repo's Settings -> Actions -> General -> Workflow permissions.
