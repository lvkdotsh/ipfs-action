# ipfs-action

## Inputs

### `path`

**Required** Directory's path to upload.

### `host`

IPFS host. Default `ipfs.komputing.org`

### `port`

IPFS host's port. Default `443`

### `protocol`

IPFS host's protocol. Default `https`

### `verbose`

Level of verbosity [`false` - quiet, `true` - verbose]. Default `false`

## Outputs

### `hash`

IPFS root's hash.

## Example usage

```
uses: aquiladev/ipfs-action@v1
with:
  path: ./
```