# Contributing to FireDrone

This is the default guidance for FireDrone repositories. Follow a repository's
own `CONTRIBUTING.md` or `AGENTS.md` when it gives more specific instructions.

## Branches and merges

- Use a short-lived feature branch and a focused pull request for larger work
  or changes that benefit from review. Work-in-progress commits on the branch
  do not need to be polished individually.
- Squash merge the pull request into `main` with a descriptive Conventional
  Commit title, such as `feat(portal): add thermal camera status`.
- Small, isolated fixes may be committed directly to `main` when that
  repository's rules allow it.
- Keep upstream commits intact when synchronizing a vendor fork if their
  history is needed to track the upstream base.

Run the repository's relevant build and checks before proposing a merge.
