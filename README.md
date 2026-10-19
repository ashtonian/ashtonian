## Go libraries

| Project | What it does |
|---|---|
| [mqttv5](https://github.com/ashtonian/mqttv5) | MQTT v5 client: automatic reconnects, session resumption, typed payloads, multi-broker failover, optional persistence across restarts. |
| [pkg/config](https://github.com/ashtonian/pkg/tree/main/config) | Typed configuration from defaults, files, environment and flags. Validated, hot-reloadable, redacted when printed. Built on koanf. |
| [pkg/httpx](https://github.com/ashtonian/pkg/tree/main/httpx) | Retries, circuit breakers, ETag caching, compression and rate limits for a plain `http.Client`, as composable `RoundTripper` layers. |
| [pkg/gowalker](https://github.com/ashtonian/pkg/tree/main/gowalker) | Struct-tag plumbing for libraries configured by tags: field naming conventions, per-type metadata, field readers and writers. |

`config`, `httpx` and `gowalker` are independently versioned modules in [pkg](https://github.com/ashtonian/pkg).

## Tools and infrastructure

| Project | What it does |
|---|---|
| [gitten](https://github.com/ashtonian/gitten) | Find, clone and sync repos across GitHub, GitLab and Gitea/Forgejo, with per-account identities and separate workspaces for coding agents. |
| [technitium-configurator](https://github.com/ashtonian/technitium-configurator) | Configure Technitium DNS Server from YAML, or export a running server's configuration. Runs from a shell, CI, Docker or a Kubernetes Job. |
| [argo-fleet](https://github.com/ashtonian/argo-fleet) | Argo CD ApplicationSet patterns for Kubernetes fleets: shared applications, group overrides, per-cluster addons. |

Also: [charmap](https://github.com/ashtonian/charmap), value substitution for manifests before rendering.
