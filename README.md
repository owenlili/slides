# Link check

Checks every day that the external links cited in the [CS 329Z learning notes](https://github.com/bohr109/cs329z-learning-notes) still open.

## What is checked

[links.json](links.json) lists the links, grouped by type:

- `course`: the course site and lecture slides.
- `papers`: papers cited in the notes.
- `articles`: articles and technical documents cited in the notes.

To check another link, add an entry with a `title` and `url` to the right group.

## When it runs

A [workflow](.github/workflows/links.yml) checks every URL in `links.json` each day at 07:17 Taiwan time (23:17 UTC), and whenever `links.json` changes. GitHub may start it later than that when it is busy. It can also be started from the Actions tab.

If a URL no longer opens, the workflow opens an issue labeled `broken-links`, or updates that issue if it is already open. Once every URL opens again, the workflow closes the issue.

This repository stores only links; it does not host the slides, papers, or articles.
