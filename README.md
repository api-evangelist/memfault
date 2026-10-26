# Memfault (memfault)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/memfault/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/memfault/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Alerts
- Android
- Crash Reporting
- Device Management
- Embedded
- Embedded Linux
- Firmware
- IoT
- Logging
- MCU
- Metrics
- Observability
- OTA
- Reliability

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Memfault Cloud REST API

The Memfault Cloud REST API is the primary programmatic interface to the Memfault platform. It covers organization and project administration, device management, software versions and releases, OTA deployments and cohorts, issues, alerts, charts, metrics, and chunk ingestion.

- **Human URL:** [https://api-docs.memfault.com/](https://api-docs.memfault.com/)
- **Base URL:** `https://api.memfault.com`

#### Tags

- Alerts
- Devices
- Issues
- Metrics
- Organizations
- OTA
- Projects
- Releases

#### Properties

- [Documentation](https://api-docs.memfault.com/)
- [Postman Collection](collections/memfault.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/memfault.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Memfault Organizations API

Manage Memfault organizations, users, and authentication tokens scoped to an organization.

- **Human URL:** [https://api-docs.memfault.com/#tag/Organizations](https://api-docs.memfault.com/#tag/Organizations)
- **Base URL:** `https://api.memfault.com`

#### Tags

- Administration
- Organizations

#### Properties

- [Documentation](https://api-docs.memfault.com/#tag/Organizations)
- [Postman Collection](collections/memfault.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/memfault.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Memfault Projects API

Create and manage Memfault projects that group devices, software, and releases.

- **Human URL:** [https://api-docs.memfault.com/#tag/Projects](https://api-docs.memfault.com/#tag/Projects)
- **Base URL:** `https://api.memfault.com`

#### Tags

- Administration
- Projects

#### Properties

- [Documentation](https://api-docs.memfault.com/#tag/Projects)
- [Postman Collection](collections/memfault.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/memfault.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Memfault Devices API

List, search, and update devices including hardware version, software version, cohort membership, and metadata.

- **Human URL:** [https://api-docs.memfault.com/#tag/Devices](https://api-docs.memfault.com/#tag/Devices)
- **Base URL:** `https://api.memfault.com`

#### Tags

- Devices
- Fleet Management

#### Properties

- [Documentation](https://api-docs.memfault.com/#tag/Devices)
- [Postman Collection](collections/memfault.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/memfault.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Memfault Software and Releases API

Manage software types, software versions, OTA releases, deployments, and cohorts that target devices for updates.

- **Human URL:** [https://api-docs.memfault.com/#tag/Releases](https://api-docs.memfault.com/#tag/Releases)
- **Base URL:** `https://api.memfault.com`

#### Tags

- Deployments
- OTA
- Releases
- Software

#### Properties

- [Documentation](https://api-docs.memfault.com/#tag/Releases)
- [Postman Collection](collections/memfault.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/memfault.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Memfault Issues API

Retrieve and manage grouped issues created from device traces, coredumps, and reboots.

- **Human URL:** [https://api-docs.memfault.com/#tag/Issues](https://api-docs.memfault.com/#tag/Issues)
- **Base URL:** `https://api.memfault.com`

#### Tags

- Crash Reporting
- Issues

#### Properties

- [Documentation](https://api-docs.memfault.com/#tag/Issues)
- [Postman Collection](collections/memfault.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/memfault.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Memfault Alerts API

Configure alert sources and review fired alerts for device fleet conditions and issue thresholds.

- **Human URL:** [https://api-docs.memfault.com/#tag/Alerts](https://api-docs.memfault.com/#tag/Alerts)
- **Base URL:** `https://api.memfault.com`

#### Tags

- Alerts
- Monitoring

#### Properties

- [Documentation](https://api-docs.memfault.com/#tag/Alerts)
- [Postman Collection](collections/memfault.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/memfault.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Memfault Metrics and Charts API

Query timeseries metrics, custom charts, and aggregated fleet data collected from devices.

- **Human URL:** [https://api-docs.memfault.com/#tag/Metrics](https://api-docs.memfault.com/#tag/Metrics)
- **Base URL:** `https://api.memfault.com`

#### Tags

- Analytics
- Charts
- Metrics

#### Properties

- [Documentation](https://api-docs.memfault.com/#tag/Metrics)
- [Postman Collection](collections/memfault.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/memfault.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Memfault Chunks Ingestion API

Upload chunks of data (events, traces, coredumps, metrics) from devices into Memfault, typically called by on-device SDKs or a customer-operated proxy.

- **Human URL:** [https://docs.memfault.com/docs/mcu/data-from-firmware-to-the-cloud/](https://docs.memfault.com/docs/mcu/data-from-firmware-to-the-cloud/)
- **Base URL:** `https://chunks.memfault.com`

#### Tags

- Chunks
- Ingestion
- Telemetry

#### Properties

- [Documentation](https://docs.memfault.com/docs/mcu/data-from-firmware-to-the-cloud/)
- [Postman Collection](collections/memfault.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/memfault.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://memfault.com/)
- [Developer](https://docs.memfault.com/)
- [Documentation](https://api-docs.memfault.com/)
- [SDK](https://github.com/memfault/memfault-firmware-sdk)
- [C L I](https://pypi.org/project/memfault-cli/)
- [Git Hub](https://github.com/memfault)
- [Blog](https://interrupt.memfault.com/)
- [Pricing](https://memfault.com/pricing/)
- [Status Page](https://status.memfault.com/)
- [Support](https://docs.memfault.com/docs/general/support)
- [Privacy Policy](https://memfault.com/legal/privacy-policy/)
- [Terms of Service](https://memfault.com/legal/terms-of-service/)
- [LinkedIn](https://www.linkedin.com/company/memfault/)
- [Changelog](https://docs.memfault.com/docs/releases)
- [Integrations](https://docs.memfault.com/docs/platform/integrations)
- [L L Ms Txt](https://docs.memfault.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
