# CircleCI (circleci)

CircleCI is a continuous integration and continuous delivery (CI/CD) platform that automates software build, test, and deployment pipelines. Their developer surface includes the REST API v2 (the recommended modern interface), the legacy v1 REST API, a Self-Hosted Runner API, webhooks for real-time event notifications, and the Orbs Registry of reusable configuration packages. Authentication is via a personal or project Circle-Token sent in the Circle-Token header; responses are JSON.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CI/CD
- Continuous Integration
- Continuous Deployment
- DevOps
- Pipelines
- Workflows

## Timestamps

- **Created:** 2025-03-05
- **Modified:** 2026-05-19

## APIs

### CircleCI REST API V2

The CircleCI REST API v2 provides programmatic access to CircleCI services for managing pipelines, projects, workflows, jobs, and users. Developers can trigger pipelines, retrieve build status, manage contexts and environment variables, and access usage reports. The API uses token-based authentication via a Circle-Token header and returns JSON responses. It supports operations for project configuration, workflow management, artifact retrieval, and insights into build performance.

- **Human URL:** [https://circleci.com/docs/api/v2/](https://circleci.com/docs/api/v2/)
- **Base URL:** `https://circleci.com/api/v2`

#### Tags

- CI/CD
- Continuous Integration
- DevOps
- Pipelines
- Workflows

#### Properties

- [Documentation](https://circleci.com/docs/api/v2/)
- [OpenAPI](openapi/circleci-rest-api-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/circleci-rest-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circleci-rest-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CircleCI REST API V1

The CircleCI REST API v1 is the legacy API that provides access to build information, project details, and user data. While still available, CircleCI recommends migrating to the v2 API for newer features and improved functionality. The v1 API supports operations for retrieving build details, triggering builds, managing SSH keys, and accessing test metadata. Authentication is handled through API tokens passed as query parameters or HTTP headers.

- **Human URL:** [https://circleci.com/docs/api/v1/](https://circleci.com/docs/api/v1/)
- **Base URL:** `https://circleci.com/api/v1.1`

#### Tags

- Builds
- CI/CD
- Continuous Integration
- Legacy

#### Properties

- [Documentation](https://circleci.com/docs/api/v1/)
- [OpenAPI](openapi/circleci-rest-api-v1-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/circleci-rest-api-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circleci-rest-api-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CircleCI Self-Hosted Runner API

The CircleCI Self-Hosted Runner API enables management and execution of jobs on self-hosted runner infrastructure. It provides endpoints for listing available runners, managing runner tasks, and querying resource classes. The API is hosted separately from the main CircleCI API at runner.circleci.com and supports multiple authentication methods depending on the endpoint. Developers can use this API to integrate self-hosted runner management into their infrastructure automation workflows.

- **Human URL:** [https://circleci.com/docs/runner-api/](https://circleci.com/docs/runner-api/)
- **Base URL:** `https://runner.circleci.com`

#### Tags

- CI/CD
- Infrastructure
- Runners
- Self-Hosted

#### Properties

- [Documentation](https://circleci.com/docs/runner-api/)
- [OpenAPI](openapi/circleci-runner-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/circleci-runner-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circleci-runner-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CircleCI Webhooks

CircleCI Webhooks allow developers to receive real-time notifications about events in their CI/CD pipelines by configuring HTTP callbacks. Webhooks can be set up through project settings to notify external services when workflows and jobs complete, fail, or change status. This enables integration with monitoring systems, chat platforms, and custom automation workflows. Webhooks deliver JSON payloads containing event details to configured endpoint URLs.

- **Human URL:** [https://circleci.com/docs/webhooks/](https://circleci.com/docs/webhooks/)
- **Base URL:** `https://api.example.com`

#### Tags

- CI/CD
- Events
- Notifications
- Webhooks

#### Properties

- [Documentation](https://circleci.com/docs/webhooks/)
- [AsyncAPI](asyncapi/circleci-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/circleci-rest-api-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circleci-rest-api-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/circleci-rest-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circleci-rest-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/circleci-runner-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circleci-runner-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CircleCI Orbs Registry

CircleCI Orbs are shareable, reusable packages of CircleCI configuration that simplify build setup and integration with third-party tools. The Orbs Registry on the CircleCI Developer Hub provides a searchable catalog of community and certified orbs. Developers can browse, publish, and consume orbs to automate repeated processes, speed up project configuration, and integrate services like AWS, Docker, Slack, and Kubernetes into their CI/CD pipelines.

- **Human URL:** [https://circleci.com/developer/orbs](https://circleci.com/developer/orbs)
- **Base URL:** `https://api.example.com`

#### Tags

- CI/CD
- Configuration
- Packages
- Reusable

#### Properties

- [Documentation](https://circleci.com/developer/orbs)
- [Postman Collection](collections/circleci-rest-api-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circleci-rest-api-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/circleci-rest-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circleci-rest-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/circleci-runner-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/circleci-runner-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/circleci)
- [LinkedIn](https://www.linkedin.com/company/circleci)
- [Website](https://circleci.com/)
- [Portal](https://circleci.com/developer)
- [Documentation](https://circleci.com/docs/)
- [Status Page](https://status.circleci.com/)
- [Support](https://support.circleci.com/)
- [Blog](https://circleci.com/blog/)
- [Privacy Policy](https://circleci.com/privacy/)
- [Terms of Service](https://circleci.com/terms-of-service/)
- [Login](https://app.circleci.com/)
- [JSON-LD](json-ld/circleci-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/circleci-pipeline-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/circleci-workflow-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/circleci-webhook-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/circleci-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Features](undefined)
- [Integrations](https://circleci.com/integrations/)
- [L L Ms Txt](https://circleci.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
