# CircleCI (circleci)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
