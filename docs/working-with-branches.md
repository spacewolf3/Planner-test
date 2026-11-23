# Working with branches

A short guide for this repository.

- **Repository**: the whole project, with its full history.
- **Branch**: a separate line of work. Changes on a branch don't affect `main` until they're merged, so it's safe to experiment there.
- **`main`**: the agreed current version. GitHub shows it first.
- **Pull request**: a request to bring a branch's changes into `main`. It shows exactly what changes, so it can be reviewed before merging.
- **Merge**: accepting a pull request. The branch's changes become part of `main`.

## The usual flow

1. Start a branch from `main` for one change (Claude Code does this automatically; its branches start with `claude/`).
2. Make and test the change on that branch.
3. Open a pull request into `main`, review it, and merge it.
4. Delete the branch. GitHub offers a "Delete branch" button on the merged pull request.

Keeping to one branch per change, and deleting it after merging, keeps the branch list short and `main` always up to date.
