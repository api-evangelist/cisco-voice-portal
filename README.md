# Cisco Voice Portal (cisco-voice-portal)
Cisco Voice Portal (CVP) is an enterprise-class Voice XML (VXML) browser and call control platform that enables self-service applications for voice, video, and multimodal interactions.

**URL:** [Visit APIs.json URL](https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html)

## Tags:

 - Contact Center, IVR, Telephony, Voice, VXML

## Timestamps

- **Created:** 2024 
- **Modified:** 2026-04-19 

## APIs

### Cisco Voice Portal Call Control API
Provides programmatic access to call control functions on the CVP Call Server including active call management, call routing, transfers, SIP session monitoring, and health status.

**Human URL:** [https://developer.cisco.com/docs/voice-portal/](https://developer.cisco.com/docs/voice-portal/)

#### Tags:

 - Call Control, Routing, Session Management, SIP

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html)
- [OpenAPI](openapi/cisco-voice-portal-call-control-openapi.yml)

### Cisco Voice Portal Reporting API
Access to call detail records (CDRs), real-time call statistics, historical reporting data, and report template execution.

**Human URL:** [https://developer.cisco.com/docs/voice-portal/](https://developer.cisco.com/docs/voice-portal/)

#### Tags:

 - Analytics, CDR, Reporting, Statistics

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html)
- [OpenAPI](openapi/cisco-voice-portal-reporting-openapi.yml)

### Cisco Voice Portal Administration API
The CVP OAMP REST API for managing devices, applications, dialed number patterns, SIP server groups, and system configuration.

**Human URL:** [https://developer.cisco.com/docs/voice-portal/](https://developer.cisco.com/docs/voice-portal/)

#### Tags:

 - Administration, Configuration, Management, OAMP, Provisioning

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html)
- [OpenAPI](openapi/cisco-voice-portal-administration-openapi.yml)

### Cisco Voice Portal VXML Services API
Management and monitoring of the CVP VXML Server including application deployment, activation, configuration, and session monitoring.

**Human URL:** [https://developer.cisco.com/docs/voice-portal/](https://developer.cisco.com/docs/voice-portal/)

#### Tags:

 - Call Studio, IVR, Micro-Applications, Voice Applications, VXML

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html)
- [OpenAPI](openapi/cisco-voice-portal-vxml-services-openapi.yml)

### Cisco Voice Portal Call Events API
Event-driven interface for consuming real-time CVP call lifecycle events, system alerts, and device status changes.

**Human URL:** [https://developer.cisco.com/docs/voice-portal/](https://developer.cisco.com/docs/voice-portal/)

#### Tags:

 - Call Lifecycle, Events, JMS, Monitoring, Notifications

#### Properties

- [Documentation](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-programming-reference-guides-list.html)
- [AsyncAPI](asyncapi/cisco-voice-portal-call-events-asyncapi.yml)

## Common Properties

- [DeveloperPortal](https://developer.cisco.com/)
- [Authentication](https://developer.cisco.com/docs/voice-portal/#!authentication)
- [StatusPage](https://status.cisco.com/)
- [Support](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/tsd-products-support-series-home.html)
- [TermsOfService](https://www.cisco.com/c/en/us/about/legal/terms-conditions.html)
- [PrivacyPolicy](https://www.cisco.com/c/en/us/about/legal/privacy-full.html)
- [GettingStarted](https://developer.cisco.com/site/devnet/)
- [Blog](https://blogs.cisco.com/developer)
- [GitHubOrganization](https://github.com/CiscoDevNet)
- [SignUp](https://developer.cisco.com/join/devnet)
- [ReleaseNotes](https://www.cisco.com/c/en/us/support/customer-collaboration/voice-portal/products-release-notes-list.html)
- [Features](https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html)
- [UseCases](https://www.cisco.com/c/en/us/products/customer-collaboration/voice-portal/index.html)
- [Integrations](https://developer.cisco.com/ecosystem/)

## Capabilities

### Shared Definitions

| File | API |
|---|---|
| `capabilities/shared/call-control.yaml` | Cisco Voice Portal Call Control API |
| `capabilities/shared/reporting.yaml` | Cisco Voice Portal Reporting API |
| `capabilities/shared/administration.yaml` | Cisco Voice Portal Administration API |
| `capabilities/shared/vxml-services.yaml` | Cisco Voice Portal VXML Services API |

### Workflow Capabilities

| Workflow | APIs Combined | Tools |
|---|---|---|
| `capabilities/contact-center-operations.yaml` | Call Control + Reporting + Administration + VXML Services | 10 |

## Maintainers

**FN:** Kin Lane, **Email:** kin@apievangelist.com
