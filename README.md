# @typehut/renovate-config [![Actions Status: test](https://github.com/typehut/renovate-config/workflows/Test/badge.svg)](https://github.com/typehut/renovate-config/actions?query=workflow%3A"Test")

[Shareable config](https://renovatebot.com/docs/config-presets/) for [Renovate](https://renovatebot.com).

## Setup

Enable Renovate in your repo and `extends` in `renovate.json`.

### Default preset

```json5
{
  "extends": ["@typehut"]
}
```

Note: Don't necessary to do `npm i -D @typehut/renovate-config`

### Maintenance preset

```json5
{
  "extends": [
    "@typehut:maintenance"
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
