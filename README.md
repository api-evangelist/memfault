# Memfault

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

Memfault is a device observability and reliability platform for connected products built on MCUs, embedded Linux, and Android. The Memfault Cloud ingests device data (coredumps, logs, metrics, reboots) and provides issue grouping, alerting, charting, fleet analytics, and over-the-air firmware updates. The Memfault REST API exposes organizations, projects, devices, software, releases, deployments, issues, alerts, metrics, and chunk ingestion endpoints.

**Areas:** Alerts · Android · Crash Reporting · Device Management · Embedded · Embedded Linux · Firmware · IoT · Logging · MCU · Metrics · Observability

## Memfault on APIs.io

Everything profiled for Memfault is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/memfault/](https://apis.io/providers/memfault/)** — or go straight to one of the APIs or properties below.

### APIs (15)

- [Memfault Cloud REST API](https://apis.io/apis/memfault/memfault-cloud-rest-api/) — The Memfault Cloud REST API is the primary programmatic interface to the Memfault platform. It covers organization and project administration, device…
- [Memfault Software and Releases API](https://apis.io/apis/memfault/memfault-software-releases-api/) — Manage software types, software versions, OTA releases, deployments, and cohorts that target devices for updates.
- [Memfault Alerts API](https://apis.io/apis/memfault/memfault-alerts-api/) — Configure alert sources and review fired alerts for device fleet conditions and issue thresholds.
- [Memfault Metrics and Charts API](https://apis.io/apis/memfault/memfault-metrics-charts-api/) — Query timeseries metrics, custom charts, and aggregated fleet data collected from devices.
- [Memfault Auth API](https://apis.io/apis/memfault/memfault-auth-api/) — The Auth API from Memfault — 2 operation(s) for auth.
- [Memfault Chunks Ingestion API](https://apis.io/apis/memfault/memfault-chunks-api/) — Upload chunks of data (events, traces, coredumps, metrics) from devices into Memfault, typically called by on-device SDKs or a customer-operated proxy.
- [Memfault Cohorts API](https://apis.io/apis/memfault/memfault-cohorts-api/) — The Cohorts API from Memfault — 3 operation(s) for cohorts.
- [Memfault Deployments API](https://apis.io/apis/memfault/memfault-deployments-api/) — The Deployments API from Memfault — 2 operation(s) for deployments.
- [Memfault Devices API](https://apis.io/apis/memfault/memfault-devices-api/) — List, search, and update devices including hardware version, software version, cohort membership, and metadata.
- [Memfault Files API](https://apis.io/apis/memfault/memfault-files-api/) — The Files API from Memfault — 3 operation(s) for files.
- [Memfault Issues API](https://apis.io/apis/memfault/memfault-issues-api/) — Retrieve and manage grouped issues created from device traces, coredumps, and reboots.
- [Memfault Organizations API](https://apis.io/apis/memfault/memfault-organizations-api/) — Manage Memfault organizations, users, and authentication tokens scoped to an organization.
- [Memfault Projects API](https://apis.io/apis/memfault/memfault-projects-api/) — Create and manage Memfault projects that group devices, software, and releases.
- [Memfault Releases API](https://apis.io/apis/memfault/memfault-releases-api/) — The Releases API from Memfault — 3 operation(s) for releases.
- [Memfault Software API](https://apis.io/apis/memfault/memfault-software-api/) — The Software API from Memfault — 2 operation(s) for software.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Moved to /providers/memfault/](https://apis.io/servers/memfault/memfault/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Memfault Agentic Access](https://apis.io/agentic-access/memfault/memfault-agentic-access/)

#### Collections (12)

Postman and Open Collection request collections.

- [Memfault Cloud REST API](https://apis.io/collections/memfault/open-memfault/)
- [Memfault Cloud REST Auth API](https://apis.io/collections/memfault/open-memfault-auth-api/)
- [Memfault Cloud REST Auth Chunks API](https://apis.io/collections/memfault/open-memfault-chunks-api/)
- [Memfault Cloud REST Auth Cohorts API](https://apis.io/collections/memfault/open-memfault-cohorts-api/)
- [Memfault Cloud REST Auth Deployments API](https://apis.io/collections/memfault/open-memfault-deployments-api/)
- [Memfault Cloud REST Auth Devices API](https://apis.io/collections/memfault/open-memfault-devices-api/)
- [Memfault Cloud REST Auth Files API](https://apis.io/collections/memfault/open-memfault-files-api/)
- [Memfault Cloud REST Auth Issues API](https://apis.io/collections/memfault/open-memfault-issues-api/)
- [Memfault Cloud REST Auth Organizations API](https://apis.io/collections/memfault/open-memfault-organizations-api/)
- [Memfault Cloud REST Auth Projects API](https://apis.io/collections/memfault/open-memfault-projects-api/)
- [Memfault Cloud REST Auth Releases API](https://apis.io/collections/memfault/open-memfault-releases-api/)
- [Memfault Cloud REST Auth Software API](https://apis.io/collections/memfault/open-memfault-software-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Memfault Authentication](https://apis.io/security/memfault/memfault-authentication/)
- [Memfault Domain Security](https://apis.io/security/memfault/memfault-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Memfault Plans Pricing](https://apis.io/plans/memfault/memfault-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Memfault Rate Limits](https://apis.io/rate-limits/memfault/memfault-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Memfault Finops](https://apis.io/finops/memfault/memfault-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://memfault.com/)
- [Documentation](https://api-docs.memfault.com/)
- [Pricing](https://memfault.com/pricing/)
- [Support](https://docs.memfault.com/docs/general/support)
- [Changelog](https://docs.memfault.com/docs/releases)
- [Blog](https://interrupt.memfault.com/)
- [Terms of service](https://memfault.com/legal/terms-of-service/)
- [Privacy policy](https://memfault.com/legal/privacy-policy/)
- [Status](https://status.memfault.com/)

## API Evangelist rating

**Kin Score 34.1** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 45.6 |
| Contract governance | 0.0 |
| Operational transparency | 26.3 |
| Developer ergonomics | 38.1 |
| Access clarity | 15.8 |

**Agent readiness 31.6** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
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
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/memfault/](https://apis.io/providers/memfault/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Memfault: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/memfault/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
