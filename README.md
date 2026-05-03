# Timoni

Timoni is a package manager for Kubernetes powered by CUE that provides a type-safe alternative to Helm charts. It enables software vendors to define complex application deployments packaged as Modules using CUE definitions, distributed as OCI artifacts in container registries with semantic versioning and cryptographic signing.

## APIs

### Timoni Module Registry API

Timoni modules are distributed as OCI artifacts in container registries. The registry API provides operations for listing module tags, retrieving OCI manifests, and downloading module blobs containing CUE definitions and Kubernetes configurations.

- **Documentation:** [https://timoni.sh/](https://timoni.sh/)
- **GitHub Repository:** [https://github.com/stefanprodan/timoni](https://github.com/stefanprodan/timoni)
- **Base URL:** `https://ghcr.io`

## Features

- Type-safe Kubernetes configuration via CUE
- OCI artifact distribution and signing
- Semantic versioning for modules
- Bundle-based multi-instance management
- Kubernetes CRD lifecycle management
- Drift detection and correction
- Bundle Runtime API for dynamic configuration
- Cryptographic signing and verification

## Use Cases

- Kubernetes application packaging and distribution
- Type-safe alternative to Helm charts
- Multi-service deployment orchestration
- GitOps-compatible application delivery
- Kubernetes module versioning and rollback

## Artifacts

| Type | File |
|---|---|
| OpenAPI | [timoni-openapi.yml](openapi/timoni-openapi.yml) |
| JSON Schema | [timoni-module-schema.json](json-schema/timoni-module-schema.json) |
| JSON Structure | [timoni-module-structure.json](json-structure/timoni-module-structure.json) |
| JSON-LD Context | [timoni-context.jsonld](json-ld/timoni-context.jsonld) |
| Vocabulary | [timoni-vocabulary.yml](vocabulary/timoni-vocabulary.yml) |

## Examples

- [List Module Tags Example](examples/timoni-list-module-tags-example.json)

## Integrations

- GitHub Container Registry (ghcr.io)
- Docker Hub
- Any OCI-compatible container registry
- Kubernetes clusters
- Flux CD

## Solutions

- Cloud-native application delivery
- Kubernetes package management
- Infrastructure as code
- CUE-based configuration management

## Links

- **Website:** [https://timoni.sh/](https://timoni.sh/)
- **Documentation:** [https://timoni.sh/](https://timoni.sh/)
- **Getting Started:** [https://timoni.sh/quickstart/](https://timoni.sh/quickstart/)
- **Concepts:** [https://timoni.sh/concepts/](https://timoni.sh/concepts/)
- **GitHub:** [https://github.com/stefanprodan/timoni](https://github.com/stefanprodan/timoni)
