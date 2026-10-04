---
name: circleci-webhook-management
description: Create, view, update, list, and delete CircleCI webhooks.
api: openapi/circleci-webhook-api-openapi.yml
operations:
- createWebhook
- listWebhooks
- getWebhook
- updateWebhook
- deleteWebhook
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/circleci-webhook-api-openapi.yml ; every operationId checked against the contract
---

# circleci-webhook-management

Create, view, update, list, and delete CircleCI webhooks.

## Steps

1. 1. `createWebhook` – requires body fields as defined in the contract and the `Circle-Token` header.
2. 2. `listWebhooks` – uses the `Circle-Token` header; no request body.
3. 3. `getWebhook` – requires path parameter `webhook-id` and the `Circle-Token` header.
4. 4. `updateWebhook` – requires path parameter `webhook-id`, body fields as defined, and the `Circle-Token` header.
5. 5. `deleteWebhook` – requires path parameter `webhook-id` and the `Circle-Token` header.

## Rules

- Auth: Include the `Circle-Token` header with a valid API token (apiToken scheme).
- All endpoints require the `Circle-Token` header; no additional pagination or idempotency headers are specified.
