# Slide redirect

Stable links to course slide PDFs, opened at a given page.

```
https://owenlili.github.io/slides/?doc=lecture01&page=18
```

redirects to page 18 of the deck listed as `lecture01` in [slides.json](slides.json). Leave out `page` to open the deck at its first page.

When a deck moves, change its `url` in `slides.json`. Every link that uses this page follows the new URL; nothing else needs to change. A weekly workflow checks that each URL in `slides.json` still opens and opens an issue if one does not.

This repository stores only links to slides that the course publishes; it does not host the slides.
