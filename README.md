# actions-js-getRelease

This action get GitHub release by tag and set `upload_url` output

## Inputs

### `tag`

**Required** The tag name of the release.

## Outputs

### `upload_url`

URL where to upload assets.

## Example usage

```
uses: zebra-lucky/actions-js-getRelease@0.0.3
with:
  tag: ${{ github.ref }}
```
