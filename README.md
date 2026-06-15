# metio.wtf hugo theme

[Hugo](https://gohugo.io/) theme for projects @ [metio](https://github.com/metio).

## Parameters

```toml
[params]
  mainSections = ["<SECTION>"]
  author = "<NAME>"
  email = "<EMAIL>"
  matrix = "@<USERNAME>:<HOME_SERVER>"
  github = "<USERNAME>"
  mastodon = "<MASTODON_URL>"
  calendar = "<RELEASE_CALENDAR_URL>"
  legalName = "<NAME>"
  description = "<SITE_DESCRIPTION>"

  # Optional "edit this page" / "history" links in the header of single pages.
  # Both render only when github and editContentPath are set.
  editContentPath = "<PATH_TO_CONTENT_DIR>" # e.g. "docs/content"
  editBranch = "<BRANCH>"                   # optional, defaults to "main"
```

Every social/header entry (`matrix`, `email`, `mastodon`, `github`, `calendar`)
renders only when its parameter is set, so each project opts in to exactly the
links it wants.

Include the theme as a git submodule at `themes/metio` (or `docs/themes/metio`)
and reference it with `theme = "metio"`.

## License

```
To the extent possible under law, the author(s) have dedicated all copyright
and related and neighboring rights to this software to the public domain
worldwide. This software is distributed without any warranty.

You should have received a copy of the CC0 Public Domain Dedication along with
this software. If not, see http://creativecommons.org/publicdomain/zero/1.0/.
```

## Mirrors

* https://github.com/metio/metio-hugo-theme
