# Convert a folder to an HTML site

> [https://github.com/joakin/markdown-folder-to-html](https://github.com/joakin/markdown-folder-to-html)

This tool will duplicate a folder (the new folder with be prefixed by an underscore) and convert any `.md` files (whatever the folder's structure) and will convert to `.html`. The new folder will have an `index.html` page and a navigation tree so you can browse your content directly from a browser.

## Installation

1. Run `npm install -g markdown-folder-to-html` to install the tool globally
2. Go to a folder where you've markdown files like a wiki project f.i. (let's say `c:\christophe\wiki\your-project`)
3. In the root folder run `markdown-folder-to-html .` to convert the entire folder to HTML files. You'll then get a copy into `c:\christophe\wiki\_your-project`
4. Open a browser and surf to `c:\christophe\wiki\_your-project`.
