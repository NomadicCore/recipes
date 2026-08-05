# Package Request Labels

This document describes the labels used to manage package request workflow in the AerynOS repository.

## Workflow Labels

| Label | Description | When to Apply |
|-------|-------------|---------------|
| `package: request` | New package request awaiting triage | Automatically applied by the issue template |
| `package: approved` | Request approved; ready for packagers to implement | After Staff or Trusted Maintainers confirm package meets Package Addition Policy |
| `package: in-progress` | Recipe is being written or reviewed | When a PR has been opened for this request |
| `package: needs-info` | Requester needs to provide additional information | When clarification is needed from the submitter |
| `package: rejected` | Request denied (does not meet policy) | When the package fails inclusion criteria |
| `package: blocked` | Cannot proceed; waiting on dependency or external factor | When a prerequisite package doesn't exist yet |

## Priority Labels

| Label | Description | When to Apply |
|-------|-------------|---------------|
| `priority: critical` | Security fix or urgent request | Security updates, vulnerabilities |
| `priority: high` | High user demand or strategic importance | Widely requested, aligns with roadmap |
| `priority: normal` | Standard processing | Most requests fall here |
| `priority: low` | Nice-to-have, deferrable | Niche software, low demand |

## Category Labels (Optional)

| Label | Description |
|-------|-------------|
| `category: desktop` | Desktop applications |
| `category: development` | Development tools, libraries |
| `category: server` | Server-side software |
| `category: multimedia` | Audio, video, imaging |
| `category: networking` | Network tools, clients |
| `category: utilities` | System utilities |
