# CircleCI (circleci)
CircleCI is a continuous integration and continuous delivery (CI/CD) platform that automates software build, test, and deployment pipelines. Their developer platform provides REST APIs, a self-hosted runner API, webhooks for real-time event notifications, and a registry of reusable configuration packages called Orbs.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - CI/CD, Continuous Integration, DevOps, Pipelines, Workflows

## Timestamps

- **Created:** 2025-03-05
- **Modified:** 2026-03-20

## APIs

### CircleCI REST API v2
The CircleCI REST API v2 provides programmatic access to CircleCI services for managing pipelines, projects, workflows, jobs, and users. Developers can trigger pipelines, retrieve build status, manage contexts and environment variables, and access usage reports. The API uses token-based authentication via a Circle-Token header and returns JSON responses. It supports operations for project configuration, workflow management, artifact retrieval, and insights into build performance.

**Human URL:** [https://circleci.com/docs/api/v2/](https://circleci.com/docs/api/v2/)


#### Tags:

 - CI/CD, Continuous Integration, Pipelines, Workflows, DevOps

#### Properties

- [Documentation](https://circleci.com/docs/api/v2/)
- [OpenAPI](openapi/circleci-rest-api-v2-openapi.yml)

### CircleCI REST API v1
The CircleCI REST API v1 is the legacy API that provides access to build information, project details, and user data. While still available, CircleCI recommends migrating to the v2 API for newer features and improved functionality. The v1 API supports operations for retrieving build details, triggering builds, managing SSH keys, and accessing test metadata. Authentication is handled through API tokens passed as query parameters or HTTP headers.

**Human URL:** [https://circleci.com/docs/api/v1/](https://circleci.com/docs/api/v1/)


#### Tags:

 - CI/CD, Continuous Integration, Legacy, Builds

#### Properties

- [Documentation](https://circleci.com/docs/api/v1/)
- [OpenAPI](openapi/circleci-rest-api-v1-openapi.yml)

### CircleCI Self-Hosted Runner API
The CircleCI Self-Hosted Runner API enables management and execution of jobs on self-hosted runner infrastructure. It provides endpoints for listing available runners, managing runner tasks, and querying resource classes. The API is hosted separately from the main CircleCI API at runner.circleci.com and supports multiple authentication methods depending on the endpoint. Developers can use this API to integrate self-hosted runner management into their infrastructure automation workflows.

**Human URL:** [https://circleci.com/docs/runner-api/](https://circleci.com/docs/runner-api/)


#### Tags:

 - CI/CD, Runners, Self-Hosted, Infrastructure

#### Properties

- [Documentation](https://circleci.com/docs/runner-api/)
- [OpenAPI](openapi/circleci-runner-api-openapi.yml)

### CircleCI Webhooks
CircleCI Webhooks allow developers to receive real-time notifications about events in their CI/CD pipelines by configuring HTTP callbacks. Webhooks can be set up through project settings to notify external services when workflows and jobs complete, fail, or change status. This enables integration with monitoring systems, chat platforms, and custom automation workflows. Webhooks deliver JSON payloads containing event details to configured endpoint URLs.

**Human URL:** [https://circleci.com/docs/webhooks/](https://circleci.com/docs/webhooks/)


#### Tags:

 - CI/CD, Webhooks, Events, Notifications

#### Properties

- [Documentation](https://circleci.com/docs/webhooks/)
- [AsyncAPI](asyncapi/circleci-webhooks-asyncapi.yml)

### CircleCI Orbs Registry
CircleCI Orbs are shareable, reusable packages of CircleCI configuration that simplify build setup and integration with third-party tools. The Orbs Registry on the CircleCI Developer Hub provides a searchable catalog of community and certified orbs. Developers can browse, publish, and consume orbs to automate repeated processes, speed up project configuration, and integrate services like AWS, Docker, Slack, and Kubernetes into their CI/CD pipelines.

**Human URL:** [https://circleci.com/developer/orbs](https://circleci.com/developer/orbs)


#### Tags:

 - CI/CD, Configuration, Packages, Reusable

#### Properties

- [Documentation](https://circleci.com/developer/orbs)

## Common Properties

- [Website](https://circleci.com/)
- [Portal](https://circleci.com/developer)
- [Documentation](https://circleci.com/docs/)
- [Status](https://status.circleci.com/)
- [Support](https://support.circleci.com/)
- [Blog](https://circleci.com/blog/)
- [Privacy Policy](https://circleci.com/privacy/)
- [Terms of Service](https://circleci.com/terms-of-service/)
- [Login](https://app.circleci.com/)
- [JSON-LD Context](json-ld/circleci-context.jsonld)
- [Pipeline JSON Schema](json-schema/circleci-pipeline-schema.json)
- [Workflow JSON Schema](json-schema/circleci-workflow-schema.json)
- [Webhook Event JSON Schema](json-schema/circleci-webhook-event-schema.json)
- [Spectral Ruleset](rules/circleci-rules.yml)
- [Naftiko Capabilities](capabilities/circleci-capabilities.yml)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
