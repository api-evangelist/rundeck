# Rundeck (rundeck)
Rundeck is an open source runbook automation service with a web console, command line tools, and a REST WebAPI. It enables IT teams to easily run automation tasks across a set of nodes, providing self-service operations, job scheduling, and execution history. Rundeck is developed by PagerDuty and supports enterprise runbook automation with role-based access control, multi-tenant project management, and integrations with popular DevOps tools including Jenkins, Ansible, Chef, and Puppet.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/rundeck/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags:

 - Automation, DevOps, Job Scheduling, Orchestration, Workflow, Runbook, Open Source, IT Operations

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-02

## APIs

### Rundeck API
The Rundeck REST API (version 58) provides programmatic access to job execution, project management, node management, execution history, user management, ACL policies, system administration, cluster operations, and log storage. Authentication is via X-Rundeck-Auth-Token header. The API returns JSON responses and supports webhook integrations for event-driven automation workflows.

**Human URL:** [https://docs.rundeck.com/docs/api/](https://docs.rundeck.com/docs/api/)

**Base URL:** http://localhost:4440/api

#### Tags:

 - Automation, DevOps, Job Scheduling, Orchestration, Workflow, Projects, Executions, Jobs, Nodes

#### Properties

- [Documentation](https://docs.rundeck.com/docs/api/)
- [OpenAPI](openapi/rundeck-openapi.yml)
- [Authentication](https://docs.rundeck.com/docs/api/#authentication)
- [Versioning](https://docs.rundeck.com/docs/api/#api-versioning)
- [GitHub Repository](https://github.com/rundeck/rundeck-api-specs)

## Spectral Rules

- [Rundeck API Rules](rules/rundeck-rules.yml)

## Capabilities

### Shared Definitions

- [Rundeck API](capabilities/shared/rundeck-api.yaml)

### Workflow Capabilities

- [Runbook Automation](capabilities/runbook-automation.yaml) — Job execution, monitoring, node management, project organization, and system administration (14 tools)

## JSON Schema

- [Rundeck Job Schema](json-schema/rundeck-job-schema.json)

## JSON Structure

- [Rundeck Job Structure](json-structure/rundeck-job-structure.json)

## JSON-LD

- [Rundeck Context](json-ld/rundeck-context.jsonld)

## Examples

- [List Jobs Example](examples/rundeck-list-jobs-example.json)
- [Run Job Example](examples/rundeck-run-job-example.json)

## Vocabulary

- [Rundeck Runbook Automation Vocabulary](vocabulary/rundeck-vocabulary.yml)

## Common Properties

- [Website](https://www.rundeck.com)
- [Documentation](https://docs.rundeck.com)
- [GitHub Organization](https://github.com/rundeck)
- [GitHub Repository](https://github.com/rundeck/rundeck)
- [Blog](https://www.rundeck.com/blog)
- [Community](https://community.rundeck.com)
- [Download](https://www.rundeck.com/downloads)
- [Support](https://www.rundeck.com/support)
- [Pricing](https://www.rundeck.com/pricing)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
