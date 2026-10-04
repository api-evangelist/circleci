---
name: circleci-manage-workflow
description: Retrieve a workflow, view its jobs, and perform common actions such as approving, canceling, or rerunning it.
api: openapi/circleci-workflow-api-openapi.yml
operations:
- getWorkflow
- listWorkflowJobs
- approveWorkflowJob
- cancelWorkflow
- rerunWorkflow
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/circleci-workflow-api-openapi.yml ; every operationId checked against the contract
---

# circleci-manage-workflow

Retrieve a workflow, view its jobs, and perform common actions such as approving, canceling, or rerunning it.

## Steps

1. 1. Retrieve the workflow details using `getWorkflow` (requires `Circle-Token` header).
2. 2. List the jobs in the workflow with `listWorkflowJobs` (requires `Circle-Token` header).
3. 3. Approve a pending job using `approveWorkflowJob` (requires `Circle-Token` header).
4. 4. Cancel the workflow if needed via `cancelWorkflow` (requires `Circle-Token` header).
5. 5. Rerun the workflow using `rerunWorkflow` (requires `Circle-Token` header).

## Rules

- Auth: Include the API token in the `Circle-Token` header (apiToken scheme).
- Pagination: `listWorkflowJobs` may return paginated results; follow pagination links provided in response headers.
- Idempotency: No explicit idempotency keys are defined for these endpoints.
