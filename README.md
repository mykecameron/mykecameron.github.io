# mykecameron.com

Source for my personal landing page: **[mykecameron.com](https://mykecameron.com)**

A single-page professional bio — who I am, what I've built, and how to reach me.
Deliberately simple: hand-written HTML and CSS, no framework, no build step, no
dependencies.

## Layout

| File | Purpose |
|---|---|
| `index.html` | The entire page — bio copy, links, and metadata |
| `styles.css` | Two-column grid that collapses to one column under 650px |
| `me.jpg` | Portrait |
| `github.png`, `linkedin.png` | Social icons |
| `CNAME` | Points the `mykecameron.com` custom domain at GitHub Pages |

## Hosting

GitHub Pages serves this from the `main` branch, so **merging to `main` publishes
to the live site**.

## Local preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>. There's nothing to install or compile.
