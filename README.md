# Source Code Analysis devroom at FOSDEM site

The site should gather all the relevant devroom material available.

## Build

The site currently only contains a markdown based page
that it's generated with [grip](https://github.com/joeyespo/grip).
To install it, simply:

```
$ pip install grip
```

To (re)generate the site, just run:

```
$ grip INDEX.md --export index.html
```

Once `index.html` is good enough, commit and push to get it published.

**NOTE**: We'll migrate to a better solution ([gitbook](https://www.gitbook.com/), [jekyll](https://jekyllrb.com/) or similar) in the near future.
