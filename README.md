# Cisco Voice Portal (cisco-voice-portal)

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
