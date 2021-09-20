# setup-node-project-action

## Usage

```yaml
steps:
  - name: 'Setup'
    uses: verkstedt/setup-node-project-action@v1
```

### Parameters

- `fetch-depth`
  By default fetches only latest commit. Set to `0` to fetch full history.
  See [checkout](https://github.com/actions/checkout) action for more details.
