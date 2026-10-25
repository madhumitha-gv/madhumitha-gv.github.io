# Portfolio

Static site. No build step, no dependencies: plain HTML and one stylesheet.

```
index.html                         portfolio
energy-demand-forecasting.html     case study
hvac-energy-optimization.html      case study
large-cohort-risk-prediction.html  case study
style.css                          shared styles
```

`_artifact-index.html` is only for previewing on claude.ai, which supplies its own
document skeleton. GitHub Pages ignores it; delete it if you prefer.

## Publish on GitHub Pages

1. Create a repository named `madhumitha-gv.github.io`.
2. Copy the contents of this folder into it (the files, not the folder).
3. Commit and push to `main`.
4. In the repository, open **Settings → Pages**, set **Source** to *Deploy from a
   branch*, branch `main`, folder `/ (root)`, and save.

The site goes live at `https://madhumitha-gv.github.io` within a few minutes.

To host it in an existing repository instead, put these files in a `docs/` folder
and choose `/docs` as the Pages folder. The URL is then
`https://madhumitha-gv.github.io/<repository-name>/`.

## Editing

Text lives in the HTML. Colors, type and spacing are tokens at the top of
`style.css`, under `:root` for the light theme and repeated in the two dark blocks
below it. Change a value in all three places and the whole site follows.
