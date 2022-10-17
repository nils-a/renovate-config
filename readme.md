# renovate-config

This is a [shared preset](https://docs.renovatebot.com/config-presets/) to be used across the account.

use it like so:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>nils-a/renovate-config#1.0.0"]
}
```

or, for the bleeding-edge `testing`-preset (if one currently exists), use

```json
{
    "$schema": "https://docs.renovatebot.com/renovate-schema.json",
    "extends": ["github>nils-a/renovate-config:testing"]
}
```

See https://docs.renovatebot.com/config-presets/#github for more information about addressing `presets` or `tags`