### Go libraries

- [pkg](https://github.com/ashtonian/pkg): batteries and glue code for Go services, each package an independent module with its own releases
  - [config](https://github.com/ashtonian/pkg/tree/main/config): typed configuration on koanf: defaults, files, environment and flags validated in one pipeline, hot reload that publishes only a config that passed, and output that never prints a secret
- [mqttv5](https://github.com/ashtonian/mqttv5): low-overhead MQTT v5 client for Go (allocation-free PUBLISH decoding), with reconnect and session resume built in, QoS 1/2 that survives restarts, and multi-broker failover and fan-out

### GitOps and infrastructure

- [argo-fleet](https://github.com/ashtonian/argo-fleet): Argo CD ApplicationSet patterns for fleet-scale, multi-cluster GitOps
- [charmap](https://github.com/ashtonian/charmap): replace `<::KEY::>` tokens in files with explicitly named values, all or nothing, for GitOps render paths
- [technitium-configurator](https://github.com/ashtonian/technitium-configurator): declarative YAML for Technitium DNS Server: settings, zones, records, apps, users and clusters applied idempotently, so a fresh server bootstraps and re-runs change nothing; exports a running server back to YAML

### Developer tools

- [gitten](https://github.com/ashtonian/gitten): find, clone and keep in sync every repo you work on across GitHub, GitLab and Gitea/Forgejo, then launch coding agents on them side by side
