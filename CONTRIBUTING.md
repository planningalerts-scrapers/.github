# Contributing to planningalerts-scrapers

This org hosts scrapers, written by the OpenAustralia Foundation and the
community, that feed data into [PlanningAlerts](https://www.planningalerts.org.au/).

We follow the same day-to-day workflow OAF uses across its own repositories --
see [openaustralia/.github's CONTRIBUTING.md](https://github.com/openaustralia/.github/blob/main/.github/CONTRIBUTING.md)
for the fuller rationale. The short version:

## Workflow: GitHub Flow

- `main` is always production-ready.
- Branch off `main` and open a pull request early -- as a draft while it's
  still in progress -- so others can see what's changing.
- Make sure the checks in `.github/workflows` pass before taking a pull
  request out of draft.
- Once reviewed and passing, merge. The author normally does the merging.

## Branches

Name branches with a type prefix, an issue number, and a short description,
for example:

- `feature/123-add-postcode-search`
- `bugfix/890-fix-pagination`
- `chore/21-update-dependencies`

## Pull requests

- Fill in the pull request template: what changed, why, and how it was tested.
- Assign the pull request to yourself so it's clear who's driving the change.
- Link to any related issue.

## Reviews

Repositories use a `CODEOWNERS` file to request reviews from the right
people. A review is about understanding and improving the change together,
not gatekeeping.

---

This file is maintained locally rather than synced from
`openaustralia/.github`: planningalerts-scrapers is a separate GitHub org with
its own contributors, so it doesn't carry OAF's Contributor Licence Agreement
or commit sign-off requirement. The issue and pull request templates in
`.github/` *are* synced automatically -- see
`.github/workflows/sync-templates.yml`.
