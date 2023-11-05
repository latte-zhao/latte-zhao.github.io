# latte-zhao.github.io

### Development Environment Setup

To develop, first install bundle.

```
https://jekyllrb.com/docs/
```

If this installation fails on macOS, it's probably because some paths that previously had 755 access modes are no longer touchable.
You can mostly still do `brew install ruby` instead.
For more details, see [troubleshooting](https://jekyllrb.com/docs/troubleshooting/#jekyll--macos).

### Running locally

After installation, run this to host the blog locally:

```
bundle exec jekyll serve
```

Browser points to `http://localhost:4000`
