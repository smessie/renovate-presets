# Renovate Presets

This is a repository for reusable configs for the [Renovate](https://renovate.whitesourcesoftware.com/) automated dependency updater bot.

## JavaScript Preset

Makes sure that major updates always go via a PR, and other changes will be auto-merged if tests pass.
Dependencies will be checked every morning.
Updates will be grouped together.

To use this, create `renovate.json` in your repo with the following contents:
```json
{
  "extends": [
    "github>smessie/renovate-presets:js"
  ]
}
```
