## Go libraries

| Project | When to use it |
|---|---|
| [mqttv5](https://github.com/ashtonian/mqttv5) | MQTT v5 clients with built-in reconnects and session resumption, typed payloads, and multi-broker failover or parallel connections. Optional persistence supports recovery across restarts. |
| [httpx](https://github.com/ashtonian/pkg/tree/main/httpx) | Add retries/backoff, circuit breakers, ETag caching, compression and rate/concurrency limits to an ordinary `http.Client` using composable `http.RoundTripper` layers. |
| [config](https://github.com/ashtonian/pkg/tree/main/config) | Load typed configuration from defaults, files, environment and flags, with validation, hot reload and redacted inspection. Built on koanf. |

`httpx` and `config` live in [pkg](https://github.com/ashtonian/pkg), where
each module has its own dependencies, versions and releases. Their READMEs
link to quick starts, detailed guides and API references.

## Tools and infrastructure

| Project | When to use it |
|---|---|
| [gitten](https://github.com/ashtonian/gitten) | Find, clone and sync repos across GitHub, GitLab and Gitea/Forgejo; manage account identities, back up uncommitted work and launch coding agents in separate workspaces. |
| [technitium-configurator](https://github.com/ashtonian/technitium-configurator) | Configure Technitium DNS Server from YAML or export a running server's configuration. Run from a shell, CI, Docker Compose or a Kubernetes Job. |
| [argo-fleet](https://github.com/ashtonian/argo-fleet) | Compare and run Argo CD ApplicationSet patterns for Kubernetes fleets: shared applications, group overrides and addons on selected clusters. |
| [charmap](https://github.com/ashtonian/charmap) | Substitute explicitly supplied values into files or stdin before rendering manifests; reject missing values and malformed tokens. |
