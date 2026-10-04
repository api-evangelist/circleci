---
name: circleci-job-management
description: Retrieve details of a job and optionally cancel it.
api: openapi/circleci-job-api-openapi.yml
operations:
- getJob
- cancelJob
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/circleci-job-api-openapi.yml ; every operationId checked against the contract
---

# circleci-job-management

Retrieve details of a job and optionally cancel it.

## Steps

1. 1. Use `getJob` with path parameters `project-slug` and `job-number`, and include the `Circle-Token` header for authentication.
2. 2. Use `cancelJob` with the same `project-slug` and `job-number` path parameters, and include the `Circle-Token` header for authentication.

## Rules

- Authentication: Provide the API token in the `Circle-Token` header (apiToken scheme).
- Both operations require the `project-slug` and `job-number` path parameters.
