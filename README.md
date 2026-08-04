# Check Point Software (check-point)

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

Check Point Software Technologies is a cybersecurity vendor providing integrated network, cloud, workspace, and AI security products including next-generation firewalls, SD-WAN, threat intelligence, endpoint, email, and mobile protection. Check Point exposes REST-based Management, GAIA, and Spark Management APIs for automating policy, object, gateway, and appliance administration across Quantum Security Management and SMB deployments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/check-point/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/check-point/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Security
- Cybersecurity
- Firewall
- Network Security
- Cloud Security
- Endpoint Security
- Threat Intelligence

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Check Point Management API

REST API for Check Point Security Management Server that automates configuration of security policies, rulebases, network and service objects, gateways, VPN communities, and access roles. Authentication uses administrator credentials or an API key to obtain a session ID (sid) returned by /web_api/login.

- **Human URL:** [https://sc1.checkpoint.com/documents/latest/APIs/index.html](https://sc1.checkpoint.com/documents/latest/APIs/index.html)
- **Base URL:** `https://{management_server}/web_api`

#### Tags

- Security Management
- Policies
- Rulebases
- Network Objects
- Gateways
- VPN
- Session Auth

#### Properties

- [Documentation](https://sc1.checkpoint.com/documents/latest/APIs/index.html)
- [API Reference](https://sc1.checkpoint.com/documents/latest/api_reference/index.html)
- [Python  S D K](https://github.com/CheckPointSW/cp_mgmt_api_python_sdk)
- [Postman Collection](collections/check-point.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/check-point.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Check Point GAIA API

REST API for managing Check Point GAIA operating system on security gateways and management servers, covering system configuration, interfaces, routing, users, software updates, and Clish-equivalent operations.

- **Human URL:** [https://sc1.checkpoint.com/documents/latest/GaiaAPIs/](https://sc1.checkpoint.com/documents/latest/GaiaAPIs/)
- **Base URL:** `https://{gaia_host}/gaia_api`

#### Tags

- GAIA
- Operating System
- System Configuration
- Networking

#### Properties

- [Documentation](https://sc1.checkpoint.com/documents/latest/GaiaAPIs/)
- [Postman Collection](collections/check-point.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/check-point.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Check Point Spark Management API

REST API for Check Point Spark Management used to administer SMB appliances and gateways at scale, covering devices, policies, objects, and reporting for small and medium business deployments.

- **Human URL:** [https://sc1.checkpoint.com/documents/latest/SmpAPIs/](https://sc1.checkpoint.com/documents/latest/SmpAPIs/)
- **Base URL:** `https://{spark_management}/web_api`

#### Tags

- Spark Management
- SMB
- Appliances
- Policies

#### Properties

- [Documentation](https://sc1.checkpoint.com/documents/latest/SmpAPIs/)
- [Postman Collection](collections/check-point.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/check-point.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/check-point-software-technologies)
- [Website](https://www.checkpoint.com)
- [Documentation](https://sc1.checkpoint.com/documents/latest/APIs/index.html)
- [Support  Center](https://supportcenter.checkpoint.com/)
- [User  Center](https://usercenter.checkpoint.com/)
- [Research](https://research.checkpoint.com/)
- [GitHub Organization](https://github.com/CheckPointSW)
- [Contact](https://www.checkpoint.com/about-us/contact-us/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
