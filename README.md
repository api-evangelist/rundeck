# Rundeck (rundeck)

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

Rundeck is an open source runbook automation service with a web console, command line tools, and a REST WebAPI. It enables IT teams to easily run automation tasks across a set of nodes, providing self-service operations, job scheduling, and execution history. Rundeck is developed by PagerDuty and supports enterprise runbook automation with role-based access control, multi-tenant project management, and integrations with popular DevOps tools including Jenkins, Ansible, Chef, and Puppet. The REST API is versioned and supports authentication via API tokens, password-based session tokens, and JWT (commercial).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rundeck/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rundeck/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Automation
- DevOps
- Job Scheduling
- Orchestration
- Workflow
- Runbook
- Open Source
- IT Operations

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-02

## APIs

### Rundeck API

The Rundeck REST API provides programmatic access to job execution, project management, node management, execution history, user management, ACL policies, system administration, cluster operations, and log storage. The current API version is 58, with a base URL of $RUNDECK_SERVER_URL/api/58. Authentication is performed via X-Rundeck-Auth-Token header or authtoken query parameter. The API returns JSON responses and supports webhook integrations for event-driven automation workflows.

- **Human URL:** [https://docs.rundeck.com/docs/api/](https://docs.rundeck.com/docs/api/)
- **Base URL:** `http://localhost:4440/api`

#### Tags

- Automation
- DevOps
- Job Scheduling
- Orchestration
- Workflow
- Projects
- Executions
- Jobs
- Nodes

#### Properties

- [Documentation](https://docs.rundeck.com/docs/api/)
- [OpenAPI](openapi/rundeck-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.rundeck.com/docs/api/#authentication)
- [Versioning](https://docs.rundeck.com/docs/api/#api-versioning)
- [GitHub Repository](https://github.com/rundeck/rundeck-api-specs)
- [Spectral  Rules](rules/rundeck-rules.yml)
- [Vocabulary](vocabulary/rundeck-vocabulary.yml)
- [JSON Schema](json-schema/rundeck-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/rundeck-job-structure.json)
- [JSON-LD](json-ld/rundeck-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rundeck)
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
