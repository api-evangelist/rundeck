# Rundeck

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

Rundeck is an open source runbook automation service with a web console, command line tools, and a REST WebAPI. It enables IT teams to easily run automation tasks across a set of nodes, providing self-service operations, job scheduling, and execution history. Rundeck is developed by PagerDuty and supports enterprise runbook automation with role-based access control, multi-tenant project management, and integrations with popular DevOps tools including Jenkins, Ansible, Chef, and Puppet. The REST API is versioned and supports authentication via API tokens, password-based session tokens, and JWT (commercial).

**Areas:** Automation · DevOps · Job Scheduling · Orchestration · Workflows · Runbook · Open Source · IT Operations · Scheduling

## Rundeck on APIs.io

Everything profiled for Rundeck is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/rundeck/](https://apis.io/providers/rundeck/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Rundeck ACL Policies API](https://apis.io/apis/rundeck/rundeck-acl-policies-api/) — Manage Access Control List (ACL) policies for fine-grained permission control.
- [Rundeck Executions API](https://apis.io/apis/rundeck/rundeck-executions-api/) — Monitor running executions, retrieve execution history, and manage execution state.
- [Rundeck Jobs API](https://apis.io/apis/rundeck/rundeck-jobs-api/) — List, create, import, export, run, and delete automation jobs.
- [Rundeck Nodes API](https://apis.io/apis/rundeck/rundeck-nodes-api/) — Query and manage nodes (target machines) associated with Rundeck projects.
- [Rundeck Projects API](https://apis.io/apis/rundeck/rundeck-projects-api/) — Create and manage Rundeck projects which organize jobs and node configurations.
- [Rundeck System API](https://apis.io/apis/rundeck/rundeck-system-api/) — Access system information, health checks, execution modes, metrics, and configuration.
- [Rundeck Tokens API](https://apis.io/apis/rundeck/rundeck-tokens-api/) — Create, list, and delete API authentication tokens.
- [Rundeck Users API](https://apis.io/apis/rundeck/rundeck-users-api/) — Manage user profiles, roles, and API token generation.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (1)

The data models the API reads and writes.

- [Rundeck Job](https://apis.io/schemas/rundeck/rundeck-job/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Rundeck Job Structure](https://apis.io/json-structure/rundeck/rundeck-job-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Rundeck Context](https://apis.io/jsonld/rundeck/rundeck-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Rundeck Runbook Automation Vocabulary](https://apis.io/vocabularies/rundeck/rundeck-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Rundeck List Jobs Example](https://apis.io/examples/rundeck/rundeck-list-jobs-example/)
- [Rundeck Run Job Example](https://apis.io/examples/rundeck/rundeck-run-job-example/)

#### Collections (8)

Postman and Open Collection request collections.

- [Rundeck ACL Policies API](https://apis.io/collections/rundeck/open-rundeck-acl-policies-api/)
- [Rundeck Executions API](https://apis.io/collections/rundeck/open-rundeck-executions-api/)
- [Rundeck Jobs API](https://apis.io/collections/rundeck/open-rundeck-jobs-api/)
- [Rundeck Nodes API](https://apis.io/collections/rundeck/open-rundeck-nodes-api/)
- [Rundeck Projects API](https://apis.io/collections/rundeck/open-rundeck-projects-api/)
- [Rundeck System API](https://apis.io/collections/rundeck/open-rundeck-system-api/)
- [Rundeck Tokens API](https://apis.io/collections/rundeck/open-rundeck-tokens-api/)
- [Rundeck Users API](https://apis.io/collections/rundeck/open-rundeck-users-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Rundeck — jsonschema rules](https://apis.io/rules/rundeck/rundeck-jsonschema-spectral-rules/)
- [Rundeck API Rules](https://apis.io/rules/rundeck/rundeck-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Rundeck Domain Security](https://apis.io/security/rundeck/rundeck-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Rundeck Plans Pricing](https://apis.io/plans/rundeck/rundeck-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Rundeck Rate Limits](https://apis.io/rate-limits/rundeck/rundeck-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Rundeck Finops](https://apis.io/finops/rundeck/rundeck-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.rundeck.com)
- [Documentation](https://docs.rundeck.com)
- [Pricing](https://www.rundeck.com/pricing)
- [Support](https://www.rundeck.com/support)
- [Blog](https://www.rundeck.com/blog)
- [GitHub](https://github.com/rundeck)

## API Evangelist rating

**Kin Score 29.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 54.3 |
| Contract governance | 27.3 |
| Operational transparency | 26.3 |
| Developer ergonomics | 28.6 |
| Access clarity | 7.9 |

**Agent readiness 16.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/rundeck/](https://apis.io/providers/rundeck/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Rundeck: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/rundeck/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
