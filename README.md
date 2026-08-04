# Cisco Voice Portal (cisco-voice-portal)

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

Cisco Voice Portal (CVP) is an enterprise-class Voice XML (VXML) browser and call control platform that enables self-service applications for voice, video, and multimodal interactions.

**APIs.json:** [https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html](https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html)

## Tags

- Contact Center
- IVR
- Telephony
- Voice
- VXML

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Cisco Voice Portal Call Control API

Provides programmatic access to call control functions on the CVP Call Server including active call management, call routing, transfers, SIP session monitoring, and health status of the call processing component.

- **Human URL:** [https://developer.cisco.com/docs/voice-portal/](https://developer.cisco.com/docs/voice-portal/)
- **Base URL:** `https://cvp-callserver.example.com:8000/cvp/rest`

#### Tags

- Call Control
- Routing
- Session Management
- SIP

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html)
- [OpenAPI](openapi/cisco-voice-portal-call-control-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-voice-portal-call-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-voice-portal-call-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Voice Portal Reporting API

Access to call detail records (CDRs), real-time call statistics, historical reporting data, and report template execution through the CVP Reporting Server.

- **Human URL:** [https://developer.cisco.com/docs/voice-portal/](https://developer.cisco.com/docs/voice-portal/)
- **Base URL:** `https://cvp-reporting.example.com:8111/cvp-reporting/rest`

#### Tags

- Analytics
- CDR
- Reporting
- Statistics

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html)
- [OpenAPI](openapi/cisco-voice-portal-reporting-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-voice-portal-reporting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-voice-portal-reporting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Voice Portal Administration API

The CVP OAMP (Operations, Administration, Maintenance, and Provisioning) REST API for managing devices, applications, dialed number patterns, SIP server groups, system configuration, user management, and deployment operations.

- **Human URL:** [https://developer.cisco.com/docs/voice-portal/](https://developer.cisco.com/docs/voice-portal/)
- **Base URL:** `https://cvp-oamp.example.com:9443/oamp/rest`

#### Tags

- Administration
- Configuration
- Management
- OAMP
- Provisioning

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html)
- [OpenAPI](openapi/cisco-voice-portal-administration-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-voice-portal-administration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-voice-portal-administration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Voice Portal VXML Services API

Management and monitoring of the CVP VXML Server including application deployment, activation, configuration, session monitoring, micro-application management, media file management, and grammar management.

- **Human URL:** [https://developer.cisco.com/docs/voice-portal/](https://developer.cisco.com/docs/voice-portal/)
- **Base URL:** `https://cvp-vxmlserver.example.com:7443/CVP/rest`

#### Tags

- Call Studio
- IVR
- Micro-Applications
- Voice Applications
- VXML

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html)
- [OpenAPI](openapi/cisco-voice-portal-vxml-services-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cisco-voice-portal-vxml-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-voice-portal-vxml-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cisco Voice Portal Call Events API

Event-driven interface for consuming real-time CVP call lifecycle events, system alerts, device status changes, and operational notifications via JMS messaging and syslog.

- **Human URL:** [https://developer.cisco.com/docs/voice-portal/](https://developer.cisco.com/docs/voice-portal/)
- **Base URL:** `tcp://cvp-callserver.example.com:61616`

#### Tags

- Call Lifecycle
- Events
- JMS
- Monitoring
- Notifications

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html)
- [AsyncAPI](asyncapi/cisco-voice-portal-call-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/cisco-voice-portal-administration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-voice-portal-administration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cisco-voice-portal-call-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-voice-portal-call-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cisco-voice-portal-reporting.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-voice-portal-reporting.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/cisco-voice-portal-vxml-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cisco-voice-portal-vxml-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Developer Portal](https://developer.cisco.com/)
- [Authentication](https://developer.cisco.com/docs/voice-portal/#!authentication)
- [Status Page](https://status.cisco.com/)
- [Support](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/tsd-products-support-series-home.html)
- [Terms of Service](https://www.cisco.com/c/en/us/about/legal/terms-conditions.html)
- [Privacy Policy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [Documentation](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/tsd-products-support-series-home.html)
- [Getting Started](https://developer.cisco.com/site/devnet/)
- [Blog](https://blogs.cisco.com/developer)
- [GitHub Organization](https://github.com/CiscoDevNet)
- [Sign Up](https://developer.cisco.com/join/devnet)
- [Release Notes](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-release-notes-list.html)
- [JSON Schema](json-schema/cisco-voice-portal-call-detail-record.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cisco-voice-portal-device.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cisco-voice-portal-application.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cisco-voice-portal-dialed-number-pattern.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html)
- [Use Cases](https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html)
- [Integrations](https://developer.cisco.com/ecosystem/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
