# MemScope marketing assets

Public mirror of marketing screenshots + the binding LICENSE
for [`memscope-fw`](https://pypi.org/project/memscope-fw/).

The MemScope source repository is private; this repo only
hosts (a) the LICENSE file (mirrored verbatim from the source
repo so PyPI's sidebar "License" link resolves to readable
text) and (b) screenshots referenced from the project's
`README.md` so they render correctly on PyPI and on the
github.com README of the (private) source repo for
unauthenticated viewers.

## Layout

- `LICENSE` — the binding MemScope Software License Agreement.
  Deliberately unversioned here: this label went stale the
  moment the LICENSE was revised, and the mirrored file
  states its own version. The
  authoritative copy lives in the source repo and ships
  inside every `memscope-fw` wheel; this is a public mirror
  for evaluation convenience.
- `screenshots/analyze-hero.png` — headline view of the
  analyze HTML report (above-the-fold)
- `screenshots/analyze-html-report.png` — full-page version
  of the analyze report
- `screenshots/diff-html-report.png` — build-to-build
  comparison report

## Permitted use of the screenshots in this repo

The software-side use rights are governed by the binding
[LICENSE](LICENSE). The screenshots have an additional
reasonable-use scope — they are graphics, not the software:

You may:
  - Embed the screenshots at original aspect ratio with
    attribution to "MemScope" in reviews, blog posts,
    Stack Overflow answers, technical articles, training
    material, and conference slides.
  - Hot-link to the raw URLs in this repo from third-party
    pages.

You should not, without prior written permission:
  - Modify a screenshot and present the modified version as
    MemScope's official material.
  - Use the screenshots to promote a derivative or competing
    product.
  - Re-host the screenshots at scale (a CDN-style mirror,
    an app-store gallery) without attribution and a link
    back to <https://pypi.org/project/memscope-fw/>.

## How updates land here

This repo is **auto-generated** from a private source. PRs and
direct edits here will be overwritten on the next sync.
Screenshots are regenerated from demo fixtures in the source
repo (`docs/demo/`) and pushed via
`.github/workflows/publish-assets.yml` whenever
`docs/assets/screenshots/**` or `LICENSE` changes on `main`.
