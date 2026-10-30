# renovate-config

Shared [Renovate](https://docs.renovatebot.com/) preset for repos owned by
`dominics`. Renovate finds a `renovate-config` repo with a `default.json` in
the owning account and has each onboarding PR extend it, so a repo's
`renovate.json` is just:

```json
{
  "extends": ["local>dominics/renovate-config"]
}
```

Change behaviour for every repo by editing `default.json` here.
