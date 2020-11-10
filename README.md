# @croutonn/renovate-config [![Actions Status: test](https://github.com/croutonn/renovate-config/workflows/test/badge.svg)](https://github.com/croutonn/renovate-config/actions?query=workflow%3A"test")

[Shareable config](https://renovatebot.com/docs/config-presets/) for [Renovate](https://renovatebot.com).

## Setup

Enable Renovate in your repo and `extends` in `renovate.json`.

### Default preset

```json5
{
  "extends": ["@croutonn"]
}
```

Note: Don't necessary to do `npm i -D @croutonn/renovate-config`

### Maintenance preset

```json5
{
  "extends": [
    "@croutonn:maintenance"
  ]
}
```

#### Features

Same features with Default preset.
The only difference from default preset, It does not update major updates.

- Add `{ major: { enabled: false }}`

It aim to less create Pull Request by renovatebot.

## References

- [Renovate Docs](https://renovatebot.com/docs/)
- [Configuration Options \| Renovate Docs](https://renovatebot.com/docs/configuration-options/)
- [Default Presets \| Renovate Docs](https://renovatebot.com/docs/presets-default/)

## License

MIT
