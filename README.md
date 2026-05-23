# setup-fontforge

Setup Fontforge for GH-Actions

## Usage

```yaml
- uses: MihailJP/setup-fontforge@v1
  with:
    # Fontforge repository name with owner
    # Default: fontforge/fontforge
    repository: fontforge/fontforge

    # Branch, tag, or SHA to checkout
    # Note that Fontforge still uses `master` as default branch, not `main`.
    # Default: master
    ref: master

    # Relative path under $GITHUB_WORKSPACE to checkout Fontforge repository
    # Default: fontforge
    path: fontforge
```
