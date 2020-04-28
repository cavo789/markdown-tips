# markdown-link-check

> [https://github.com/tcort/markdown-link-check](https://github.com/tcort/markdown-link-check)

Checks that all of the hyperlinks in a markdown text to determine if they are alive or dead.

The tool has a CLI mode so it's possible to scan one file `markdown-link-check ./README.md` or an entire folder `find . -name \*.md -exec markdown-link-check {} \;` (find will search any `.md` file and run the tool for each retrieved file).
