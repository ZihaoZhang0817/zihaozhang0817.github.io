# ZihaoZhang.github.io

Personal homepage of Zihao Zhang. Single static page, no build step.

## Editing

- **Everything lives in `index.html`.** Bio and social links are in the hero section; news items are plain HTML in `#news`; experience and education are plain HTML in `#experience`.
- **Publications and awards** are JavaScript arrays (`pubs`, `awards`) near the bottom of `index.html`. Each entry has `t` (title), `u` (URL, `""` if none yet), `a` (authors HTML), `v` (venue label), `vc` (badge class), and optional `img`, `extra` badges, and `links`.
- **Photo:** put a square-ish image at `figures/zihao.jpg`. Until it exists the page shows initials instead.
- **CV:** replace `CV_Zihao_Zhang.pdf` to update the CV link.

## Local preview

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

Design adapted from [Rulin Shao's homepage](https://rulinshao.github.io/).
