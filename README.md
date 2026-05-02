# Restate (restate)

Restate is a low-latency durable execution engine for building resilient applications that tolerate all infrastructure faults. It provides durable execution for workflows, event-driven handlers, and stateful orchestration of microservices with exactly-once semantics, automatic retries, and built-in state management.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Durable Execution
- Workflows
- Microservices
- Orchestration
- Distributed Systems

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-02

## APIs

### Restate Admin API

The Restate Admin API provides endpoints for managing service deployments, services, invocations, Kafka subscriptions, and cluster health. It enables operators to register service deployments, inspect service metadata, manage in-flight invocations, and configure event-driven subscriptions.

**Human URL:** [https://restate.dev/](https://restate.dev/)
**Base URL:** [http://localhost:9070](http://localhost:9070)

#### Tags

- Deployments
- Services
- Invocations
- Administration

#### Properties

| Type | URL |
|------|-----|
| OpenAPI | [restate-admin-api.yml](openapi/restate-admin-api.yml) |
| JSONSchema | [restate-deployment-schema.json](json-schema/restate-deployment-schema.json) |
| JSONSchema | [restate-invocation-schema.json](json-schema/restate-invocation-schema.json) |
| Vocabulary | [restate-vocabulary.yml](vocabulary/restate-vocabulary.yml) |
| Documentation | [https://docs.restate.dev/](https://docs.restate.dev/) |
| GitHub Repository | [https://github.com/restatedev/restate](https://github.com/restatedev/restate) |
| KubernetesCRD | [crd/restateclusters.yaml](crd/restateclusters.yaml) |
| KubernetesCRD | [crd/restatedeployments.yaml](crd/restatedeployments.yaml) |
| KubernetesCRD | [crd/restatecloudenvironments.yaml](crd/restatecloudenvironments.yaml) |

## Artifacts

| Type | File |
|------|------|
| OpenAPI Spec | [openapi/restate-admin-api.yml](openapi/restate-admin-api.yml) |
| JSON Schema (Deployment) | [json-schema/restate-deployment-schema.json](json-schema/restate-deployment-schema.json) |
| JSON Schema (Invocation) | [json-schema/restate-invocation-schema.json](json-schema/restate-invocation-schema.json) |
| JSON Structure (Invocation) | [json-structure/restate-invocation-structure.json](json-structure/restate-invocation-structure.json) |
| JSON Structure (Deployment) | [json-structure/restate-deployment-structure.json](json-structure/restate-deployment-structure.json) |
| JSON-LD Context | [json-ld/restate-context.jsonld](json-ld/restate-context.jsonld) |
| Examples | [examples/](examples/) |
| Spectral Rules | [rules/restate-rules.yml](rules/restate-rules.yml) |
| Capabilities (Shared) | [capabilities/shared/restate-admin.yaml](capabilities/shared/restate-admin.yaml) |
| Capabilities (Workflow) | [capabilities/service-operations.yaml](capabilities/service-operations.yaml) |
| Vocabulary | [vocabulary/restate-vocabulary.yml](vocabulary/restate-vocabulary.yml) |
| Kubernetes CRDs | [crd/](crd/) |

## Kubernetes CRDs

Restate provides Kubernetes Custom Resource Definitions via the Restate Operator for deploying and managing Restate clusters on Kubernetes.

| CRD | File |
|-----|------|
| RestateCluster | [crd/restateclusters.yaml](crd/restateclusters.yaml) |
| RestateDeployment | [crd/restatedeployments.yaml](crd/restatedeployments.yaml) |
| RestateCloudEnvironment | [crd/restatecloudenvironments.yaml](crd/restatecloudenvironments.yaml) |

## Capabilities

### Shared Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/restate-admin.yaml](capabilities/shared/restate-admin.yaml) | Full Restate Admin API — deployments, services, invocations, subscriptions |

### Workflow Capabilities

| File | Description |
|------|-------------|
| [capabilities/service-operations.yaml](capabilities/service-operations.yaml) | Service registration, deployment management, invocation control, and Kafka subscription management |

## Common Properties

| Type | URL |
|------|-----|
| Website | [https://restate.dev/](https://restate.dev/) |
| Documentation | [https://docs.restate.dev/](https://docs.restate.dev/) |
| GitHub Organization | [https://github.com/restatedev](https://github.com/restatedev) |
| TypeScript SDK | [https://github.com/restatedev/sdk-typescript](https://github.com/restatedev/sdk-typescript) |
| Python SDK | [https://github.com/restatedev/sdk-python](https://github.com/restatedev/sdk-python) |
| Java SDK | [https://github.com/restatedev/sdk-java](https://github.com/restatedev/sdk-java) |
| Go SDK | [https://github.com/restatedev/sdk-go](https://github.com/restatedev/sdk-go) |
| Rust SDK | [https://github.com/restatedev/sdk-rust](https://github.com/restatedev/sdk-rust) |
| Examples | [https://github.com/restatedev/examples](https://github.com/restatedev/examples) |
| Discord | [https://discord.gg/skW3AZ6uGd](https://discord.gg/skW3AZ6uGd) |
| Blog | [https://restate.dev/blog/](https://restate.dev/blog/) |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
