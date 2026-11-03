# alai.sh

The landing page at <https://alai.sh/>, a one-page
[zensical](https://zensical.org/) site built from `docs/index.md` and published
by `.github/workflows/pages.yml`.

As this is the organization's Pages site, any `alai-sh` repository with Pages
turned on and no custom domain of its own is served at
`https://alai.sh/<repository>/`. alai's own docs set `docs.alai.sh` instead.

```console
$ uv run zensical serve
```
