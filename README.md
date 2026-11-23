# Home

Small web apps our household uses day to day. Each app is a single HTML file that runs as a [claude.ai](https://claude.ai) artifact; there is nothing to install or build.

| App | Folder | What it does |
| --- | --- | --- |
| **Family Planner** | [`planner/`](planner/) | Who has the kids, school and no-school days, calendar, weather, meals, groceries and to-dos, shared between both parents. |
| **House Book** | [`house-book/`](house-book/) | Cleaning and upkeep schedule, appliances, and the house cleaners' visits. |

## How this repository is organized

- **`main`** is the current version of everything. Each app lives in its own folder with its own README.
- New work happens on a separate branch, then comes into `main` through a pull request once it's reviewed. Branches are deleted after they're merged.
- `docs/` holds notes that cover more than one app.

## Data and privacy

The code is here; the data is not. Each app stores its data with the artifact on claude.ai, under the owner's account. Nothing personal (names, schedules, calendar entries) is committed to this repository. Keep it that way: don't paste real family details into code, READMEs or commit messages.

## Updating an app

1. Ask Claude Code to make the change on a new branch.
2. Claude republishes the artifact at the same link, so the live app updates and its data stays as it was.
3. Review the pull request on GitHub and merge it into `main`.
