# setup-fontforge

Setup Fontforge for GH-Actions.
This is intended for Python or legacy scripts; GUI features are not installed.

> [!IMPORTANT]
> Use **after** [Setup Python](https://github.com/actions/setup-python) action
> and the Python module will be available.

## Usage

```yaml
- uses: MihailJP/setup-fontforge@v1
  with:
    # Branch, tag, or SHA to checkout
    # Note that Fontforge still uses `master` as default branch, not `main`.
    # Default: master
    ref: master

    # Relative path under $GITHUB_WORKSPACE to checkout Fontforge repository
    # Default: fontforge
    path: fontforge
```
