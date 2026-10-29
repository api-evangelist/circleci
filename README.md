# CircleCI

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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

**Areas:** CI/CD · Continuous Integration · Continuous Deployment · DevOps · Pipelines · Workflows · Developer Tools

## CircleCI on APIs.io

Everything profiled for CircleCI is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/circleci/](https://apis.io/providers/circleci/)** — or go straight to one of the APIs or properties below.

### APIs (18)

- [CircleCI Self-Hosted Runner API](https://apis.io/apis/circleci/runner-api/) — The CircleCI Self-Hosted Runner API enables management and execution of jobs on self-hosted runner infrastructure. It provides endpoints for listing…
- [CircleCI Webhooks](https://apis.io/apis/circleci/webhooks/) — CircleCI Webhooks allow developers to receive real-time notifications about events in their CI/CD pipelines by configuring HTTP callbacks. Webhooks can be…
- [CircleCI Orbs Registry](https://apis.io/apis/circleci/orbs/) — CircleCI Orbs are shareable, reusable packages of CircleCI configuration that simplify build setup and integration with third-party tools. The Orbs Registry…
- [CircleCI Artifact API](https://apis.io/apis/circleci/circleci-artifact-api/) — Endpoints for listing and downloading build artifacts.
- [CircleCI Build API](https://apis.io/apis/circleci/circleci-build-api/) — Endpoints for retrieving build details, triggering builds, retrying builds, and canceling builds.
- [CircleCI Context API](https://apis.io/apis/circleci/circleci-context-api/) — Endpoints for managing contexts, which are used to secure and share environment variables across projects.
- [CircleCI Insights API](https://apis.io/apis/circleci/circleci-insights-api/) — Endpoints for retrieving workflow and job metrics, summary data, and test performance insights.
- [CircleCI Job API](https://apis.io/apis/circleci/circleci-job-api/) — Endpoints for retrieving job details, artifacts, and test metadata associated with pipeline jobs.
- [CircleCI Pipeline API](https://apis.io/apis/circleci/circleci-pipeline-api/) — Endpoints for triggering, retrieving, and managing pipelines and their configurations.
- [CircleCI Project API](https://apis.io/apis/circleci/circleci-project-api/) — Endpoints for listing followed projects and managing project settings.
- [CircleCI Resource Class API](https://apis.io/apis/circleci/circleci-resource-class-api/) — Endpoints for managing runner resource classes, which define the compute resources available for self-hosted runner jobs.
- [CircleCI Runner Task API](https://apis.io/apis/circleci/circleci-runner-task-api/) — Endpoints for querying task counts and managing tasks assigned to self-hosted runners.
- [CircleCI Schedule API](https://apis.io/apis/circleci/circleci-schedule-api/) — Endpoints for creating, updating, and managing scheduled pipeline triggers.
- [CircleCI SSH Key API](https://apis.io/apis/circleci/circleci-ssh-key-api/) — Endpoints for managing SSH keys and checkout keys for projects.
- [CircleCI Test Metadata API](https://apis.io/apis/circleci/circleci-test-metadata-api/) — Endpoints for retrieving test metadata collected during builds.
- [CircleCI User API](https://apis.io/apis/circleci/circleci-user-api/) — Endpoints for retrieving information about the authenticated user.
- [CircleCI Webhook API](https://apis.io/apis/circleci/circleci-webhook-api/) — Endpoints for creating, updating, listing, and deleting outbound webhook subscriptions.
- [CircleCI Workflow API](https://apis.io/apis/circleci/circleci-workflow-api/) — Endpoints for retrieving workflow details, managing workflow status, and rerunning workflows.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (2)

Event-driven and webhook contracts.

- [Circleci Webhooks](https://apis.io/asyncapis/circleci/circleci-webhooks/)
- [CircleCI Webhooks](https://apis.io/asyncapis/circleci/circleci-webhooks-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/webhook](https://apis.io/channels/circleci/webhook/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [circleci](https://apis.io/servers/circleci/circleci/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Circleci Agentic Access](https://apis.io/agentic-access/circleci/circleci-agentic-access/)

#### JSON Schema (83)

The data models the API reads and writes.

- [Artifact](https://apis.io/schemas/circleci/circleci-artifact/)
- [ArtifactList](https://apis.io/schemas/circleci/circleci-artifact-list/)
- [ArtifactList](https://apis.io/schemas/circleci/circleci-artifactlist/)
- [Build](https://apis.io/schemas/circleci/circleci-build/)
- [BuildDetail](https://apis.io/schemas/circleci/circleci-build-detail/)
- [BuildSummary](https://apis.io/schemas/circleci/circleci-build-summary/)
- [BuildDetail](https://apis.io/schemas/circleci/circleci-builddetail/)
- [BuildSummary](https://apis.io/schemas/circleci/circleci-buildsummary/)
- [CheckoutKey](https://apis.io/schemas/circleci/circleci-checkout-key/)
- [CheckoutKeyList](https://apis.io/schemas/circleci/circleci-checkout-key-list/)
- [CheckoutKey](https://apis.io/schemas/circleci/circleci-checkoutkey/)
- [CheckoutKeyList](https://apis.io/schemas/circleci/circleci-checkoutkeylist/)
- [Collaboration](https://apis.io/schemas/circleci/circleci-collaboration/)
- [Context](https://apis.io/schemas/circleci/circleci-context/)
- [ContextList](https://apis.io/schemas/circleci/circleci-context-list/)
- [ContextList](https://apis.io/schemas/circleci/circleci-contextlist/)
- [CreateContextRequest](https://apis.io/schemas/circleci/circleci-create-context-request/)
- [CreateScheduleRequest](https://apis.io/schemas/circleci/circleci-create-schedule-request/)
- [CreateWebhookRequest](https://apis.io/schemas/circleci/circleci-create-webhook-request/)
- [CreateContextRequest](https://apis.io/schemas/circleci/circleci-createcontextrequest/)
- [CreateScheduleRequest](https://apis.io/schemas/circleci/circleci-createschedulerequest/)
- [CreateWebhookRequest](https://apis.io/schemas/circleci/circleci-createwebhookrequest/)
- [EnvironmentVariable](https://apis.io/schemas/circleci/circleci-environment-variable/)
- [EnvironmentVariableList](https://apis.io/schemas/circleci/circleci-environment-variable-list/)
- [EnvironmentVariable](https://apis.io/schemas/circleci/circleci-environmentvariable/)
- …and 58 more published on APIs.io

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Circleci Structure](https://apis.io/json-structure/circleci/circleci-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Circleci Context](https://apis.io/jsonld/circleci/circleci-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [CircleCI Domain Vocabulary](https://apis.io/vocabularies/circleci/circleci-vocabulary/)

#### Collections (34)

Postman and Open Collection request collections.

- [CircleCI REST API v1 Artifact API](https://apis.io/collections/circleci/open-circleci-artifact-api/)
- [CircleCI REST API v1 Artifact Build API](https://apis.io/collections/circleci/open-circleci-build-api/)
- [CircleCI REST API v1 Artifact Context API](https://apis.io/collections/circleci/open-circleci-context-api/)
- [CircleCI REST API v1 Artifact Insights API](https://apis.io/collections/circleci/open-circleci-insights-api/)
- [CircleCI REST API v1 Artifact Job API](https://apis.io/collections/circleci/open-circleci-job-api/)
- [CircleCI REST API v1 Artifact Pipeline API](https://apis.io/collections/circleci/open-circleci-pipeline-api/)
- [CircleCI REST API v1 Artifact Project API](https://apis.io/collections/circleci/open-circleci-project-api/)
- [CircleCI REST API v1 Artifact Resource Class API](https://apis.io/collections/circleci/open-circleci-resource-class-api/)
- [CircleCI REST API v1](https://apis.io/collections/circleci/open-circleci-rest-api-v1/)
- [CircleCI REST API v2](https://apis.io/collections/circleci/open-circleci-rest-api-v2/)
- [CircleCI REST API v1 Artifact Runner API](https://apis.io/collections/circleci/open-circleci-runner-api/)
- [CircleCI REST API v1 Artifact Runner Task API](https://apis.io/collections/circleci/open-circleci-runner-task-api/)
- [CircleCI REST API v1 Artifact Schedule API](https://apis.io/collections/circleci/open-circleci-schedule-api/)
- [CircleCI REST API v1 Artifact SSH Key API](https://apis.io/collections/circleci/open-circleci-ssh-key-api/)
- [CircleCI REST API v1 Artifact Test Metadata API](https://apis.io/collections/circleci/open-circleci-test-metadata-api/)
- [CircleCI REST API v1 Artifact User API](https://apis.io/collections/circleci/open-circleci-user-api/)
- [CircleCI REST API v1 Artifact Webhook API](https://apis.io/collections/circleci/open-circleci-webhook-api/)
- [CircleCI REST API v1 Artifact Workflow API](https://apis.io/collections/circleci/open-circleci-workflow-api/)
- [CircleCI REST API v1 Artifact API](https://apis.io/collections/circleci/postman-circleci-artifact-api/)
- [CircleCI REST API v1 Artifact Build API](https://apis.io/collections/circleci/postman-circleci-build-api/)
- [CircleCI REST API v1 Artifact Context API](https://apis.io/collections/circleci/postman-circleci-context-api/)
- [CircleCI REST API v1 Artifact Insights API](https://apis.io/collections/circleci/postman-circleci-insights-api/)
- [CircleCI REST API v1 Artifact Job API](https://apis.io/collections/circleci/postman-circleci-job-api/)
- [CircleCI REST API v1 Artifact Pipeline API](https://apis.io/collections/circleci/postman-circleci-pipeline-api/)
- [CircleCI REST API v1 Artifact Project API](https://apis.io/collections/circleci/postman-circleci-project-api/)
- …and 9 more published on APIs.io

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Circleci Artifact Api Overlay](https://apis.io/overlays/circleci/circleci-artifact-api-overlay/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [CircleCI — asyncapi rules](https://apis.io/rules/circleci/circleci-asyncapi-spectral-rules/)
- [CircleCI — jsonschema rules](https://apis.io/rules/circleci/circleci-jsonschema-spectral-rules/)
- [CircleCI API Rules](https://apis.io/rules/circleci/circleci-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Circleci Authentication](https://apis.io/security/circleci/circleci-authentication/)
- [Circleci Domain Security](https://apis.io/security/circleci/circleci-domain-security/)
- [Circleci Trust Center](https://apis.io/security/circleci/circleci-trust-center/)
- [Circleci Vulnerability Disclosure](https://apis.io/security/circleci/circleci-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Circleci Plans Pricing](https://apis.io/plans/circleci/circleci-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Circleci Rate Limits](https://apis.io/rate-limits/circleci/circleci-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Circleci Finops](https://apis.io/finops/circleci/circleci-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://circleci.com/)
- [Documentation](https://circleci.com/docs/)
- [API reference](https://circleci.com/docs/guides/getting-started/getting-started/)
- [Pricing](https://circleci.com/pricing/)
- [Support](https://support.circleci.com/)
- [Changelog](https://circleci.com/changelog/)
- [Blog](https://circleci.com/blog/)
- [Security](https://circleci.com/security/)
- [Compliance](https://trust.circleci.com/)
- [Terms of service](https://circleci.com/terms-of-service/)
- [Privacy policy](https://circleci.com/privacy/)
- [GitHub](https://github.com/circleci)
- [Status](https://status.circleci.com/)

## API Evangelist rating

**Kin Score 66.1** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 76.7 |
| Contract quality | 69.5 |
| Contract governance | 31.8 |
| Operational transparency | 60.5 |
| Developer ergonomics | 62.5 |
| Access clarity | 61.8 |

**Agent readiness 56.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 35.3** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/circleci/](https://apis.io/providers/circleci/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for CircleCI: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/circleci/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
