
# Github Blog Comments Test

This repo is a place for playing around with ways to use github as a source for blog comments.

## Rough Idea
Can I get a flow going where people comment by opening a PR and I moderate comments by merging them?

We could have a directory in which there is a sub-directory per post (or more boradly, per comment target). In each directory there is a file per comment. A valid comment PR would create a new comment file (and nothing else). When the PR is merged, an action would append the contents to an aggregated comment file.

## Steps
- [] Make an action which runs on merge into main and performs per-directory aggregations
