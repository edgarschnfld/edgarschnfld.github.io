Static HTML site, borrowing heavily from https://github.com/henrik/henrik.nyh.se.

## Development

Install dependencies (once):

```
bundle
```

CSS is being generated from SCSS (Sass). To automatically convert SCSS on edit, run this in a separate (tmux) window:

```
script/watch
```

If something doesn't appear to work, watch that window for errors and warnings.

Or just do this in an macOS terminal:
```
open index.html
```
