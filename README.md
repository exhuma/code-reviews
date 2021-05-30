# code-reviews

PR-Traget for arbitrary code-reviews.

This project provides a location for code-reviews of any github code-base.

The `main` branch on this repository will always reamain empty (except this README) file.

No pull-request will ever be merged into this repository. Once the review is finished, they will simply be closed.

## Starting a New Review

* Fork this project
* Create a new branch prefixing it with `<github-username>/...`
* Copy the code that you want to be reviewed into this branch and commit.
* submit this as a new pull-request against `main`.
* Reviews will be done live @ https://twitch.tv/exhuma

## Notes

* Languages: Python & Javascript will be reviewed in more depth, but other languages will be more high-level.
* This is currently an "experiment" to see if this workflow is acceptable for code-reviews.
* As the code needs to be copied, any commits on this "review-project" will not flow into the original code-base.
* `git` is very flexible, and if you're adept at using it, there should be a way to transfer single commits from the review-branch onto the original code-base (`cherry-pick`, `format-patch`, ...). None of them have been tested yet.
