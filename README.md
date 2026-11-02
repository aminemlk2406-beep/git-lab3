# Git Lab 3

This repository contains the exercises for Lab No. 03 on Git branching, merging, and collaboration.

## Files

- `file.txt`: final result of the merge-conflict exercise.
- `feature.txt`: commits created on the `feature1` branch.
- `bugfix.txt`: change committed on `main` before merging `feature1`.

## Inspect the history

```bash
git log --oneline --graph --all
```

## Contributor workflow

1. Start a new branch from the latest `main`.
2. Make a focused change and commit it on that branch.
3. Push the branch and open a pull request against `main`.
4. Let the project owner review and merge the pull request.
5. Update the local `main` after the merge.

The `add-login-feature` branch is a separate proposed change owned by Amine. It is not part of `main` until its pull request is merged.
