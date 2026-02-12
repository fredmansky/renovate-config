# renovate config
> Shared `Renovate` configuration for Fredmansky projects.
---

[Renovate][1] is a tool that automates dependency updates.

## Setup

* Create a `renovate.json` file in the root of the repository.
* Enable the [`Renovate`][2] GitHub app on the repository.
* Enable [Dependabot Alerts][3] and [Dependency Graph][4] on the repository to enable security-related PRs.
* Consult the [official documentation][1] for more information.

## Configuration

**renovate.json**
```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>fredmansky/renovate-config"]
}
```

## Development

* [Mend Developer Portal](https://developer.mend.io/)
* [Package Rules Guide](https://docs.mend.io/wsk/renovate-package-rules-guide)

[1]: https://docs.renovatebot.com/
[2]: https://github.com/apps/renovate
[3]: https://docs.github.com/en/code-security/concepts/supply-chain-security/about-dependabot-alerts
[4]: https://docs.github.com/en/code-security/concepts/supply-chain-security/about-the-dependency-graph
