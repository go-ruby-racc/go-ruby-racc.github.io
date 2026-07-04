<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-racc/brand/main/social/go-ruby-racc.png" alt="go-ruby-racc/go-ruby-racc.github.io" width="720"></p>

# go-ruby-racc.github.io

The organization's institutional landing page, served at
<https://go-ruby-racc.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-racc/docs](https://github.com/go-ruby-racc/docs), served at
<https://go-ruby-racc.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
