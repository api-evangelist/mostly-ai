# MOSTLY AI (mostly-ai)

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

MOSTLY AI provides a synthetic data platform for high-fidelity, privacy-safe tabular data. It ships an open-source Python SDK (mostlyai, Apache 2.0) that runs in LOCAL mode for on-prem training or CLIENT mode against the hosted MOSTLY AI Platform, plus a REST API used by both the SDK and the web app. The SDK is powered by the TabularARGN model architecture and supports differential privacy.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mostly-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mostly-ai/refs/heads/main/apis.yml)

## Tags

- Synthetic Data
- Privacy
- Tabular
- Differential Privacy
- Python SDK
- REST
- Apache 2.0

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### MOSTLY AI REST API

REST API for the hosted MOSTLY AI Platform. Lets you manage connectors, generators, synthetic datasets, and runs. API keys are issued from the user profile menu in the web application.

- **Human URL:** [https://api-docs.mostly.ai/](https://api-docs.mostly.ai/)
- **Base URL:** `https://app.mostly.ai`

#### Tags

- REST
- Synthetic Data
- Generators
- Connectors

#### Properties

- [Documentation](https://api-docs.mostly.ai/)
- [Product Docs](https://mostly.ai/docs)
- [Postman Collection](collections/mostly-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mostly-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### MOSTLY AI Synthetic Data SDK

Open-source Python SDK (mostlyai, Apache 2.0) for training generators and producing synthetic data. Runs in LOCAL mode on user compute or CLIENT mode against the MOSTLY AI Platform. Powered by the TabularARGN model.

- **Human URL:** [https://mostly-ai.github.io/mostlyai/](https://mostly-ai.github.io/mostlyai/)
- **Base URL:** `https://github.com/mostly-ai/mostlyai`

#### Tags

- SDK
- Python
- Open Source
- Apache 2.0

#### Properties

- [Documentation](https://docs.mostly.ai/python-sdk)
- [API Reference](https://mostly-ai.github.io/mostlyai/api_client/)
- [Source Code](https://github.com/mostly-ai/mostlyai)
- [Py P I](https://pypi.org/project/mostlyai/)
- [License](Apache 2.0)
- [Postman Collection](collections/mostly-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mostly-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://mostly.ai/)
- [Documentation](https://mostly.ai/docs)
- [A P I Docs](https://api-docs.mostly.ai/)
- [Git Hub](https://github.com/mostly-ai)
- [LinkedIn](https://www.linkedin.com/company/mostly-ai)
- [Plans](plans/mostly-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/mostly-ai-rate-limits.yml)
- [Fin Ops](finops/mostly-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
