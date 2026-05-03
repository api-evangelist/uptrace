# Uptrace

Uptrace is an open source APM and distributed tracing platform powered by OpenTelemetry for monitoring application traces, metrics, and logs. The Uptrace API provides programmatic access to annotations, Prometheus metrics ingestion, PromQL querying, alert rules, project management, and dashboards.

**Website:** https://uptrace.dev
**Documentation:** https://uptrace.dev/get/get-started.html
**GitHub:** https://github.com/uptrace/uptrace

## APIs

| API | Description |
|---|---|
| [Uptrace API](openapi/uptrace-openapi.yml) | REST API for annotations, alerts, projects, dashboards, and Prometheus metrics ingestion |

## OpenAPI Specifications

| Spec | Description |
|---|---|
| [uptrace-openapi.yml](openapi/uptrace-openapi.yml) | Uptrace API covering annotations, Prometheus ingestion/querying, alerts, projects, and dashboards |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [uptrace-rules.yml](rules/uptrace-rules.yml) | Spectral ruleset enforcing Uptrace API conventions including /api/ prefix, bearer auth, and path naming |

## Naftiko Capabilities

### Shared Definitions

| File | APIs Covered |
|---|---|
| [shared/uptrace.yaml](capabilities/shared/uptrace.yaml) | Uptrace API (annotations, alerts, projects, dashboards, Prometheus) |

### Workflow Capabilities

| Workflow | Description | Tools |
|---|---|---|
| [observability-and-monitoring.yaml](capabilities/observability-and-monitoring.yaml) | End-to-end observability — projects, annotations for deployments, alert rules, and dashboards | 13 tools |

## JSON Schemas

| Schema | Description |
|---|---|
| [uptrace-annotation-schema.json](json-schema/uptrace-annotation-schema.json) | Chart annotation resource |
| [uptrace-alert-schema.json](json-schema/uptrace-alert-schema.json) | Alert rule resource |

## JSON Structure

| Structure | Description |
|---|---|
| [uptrace-annotation-structure.json](json-structure/uptrace-annotation-structure.json) | Field-level documentation for the Annotation resource |

## JSON-LD

| Context | Description |
|---|---|
| [uptrace-context.jsonld](json-ld/uptrace-context.jsonld) | Linked data context mapping Uptrace resources to schema.org and OpenTelemetry concepts |

## Examples

| Example | Description |
|---|---|
| [uptrace-create-annotation-example.json](examples/uptrace-create-annotation-example.json) | POST /api/v1/annotations deployment annotation request and response |
| [uptrace-create-alert-example.json](examples/uptrace-create-alert-example.json) | POST /api/v1/alerts alert rule creation request and response |

## Vocabulary

| File | Description |
|---|---|
| [uptrace-vocabulary.yml](vocabulary/uptrace-vocabulary.yml) | Domain vocabulary for Uptrace APM including OpenTelemetry, tracing, PromQL, and observability concepts |

## Links

- **Website:** https://uptrace.dev
- **Documentation:** https://uptrace.dev/get/get-started.html
- **GitHub:** https://github.com/uptrace/uptrace
- **Docker Hub:** https://hub.docker.com/r/uptrace/uptrace

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
