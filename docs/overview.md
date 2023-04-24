# APEX Cloud Overview

APEX Cloud is a full-fledged API management solution that allows developers, product teams, agencies and, businesses to manage APIs across various stages – from registration to publication to retirement. 

APEX Cloud is accessible from both the intranet and the internet and is compliant with ICT&SS management guidelines (formerly known as IM8) as well as various governance standards. 

## Benefits

APEX Cloud offers the following important benefits:

- Provides an Identity and Access Management (IAM) platform and access control of APIs for government-to-government (G2G) & government-to-business (G2B) API programmes. 
- Supports both TechPass (government users and vendors) and Corppass (for businesses) access.
- Established workflow for requesting and approving API subscriptions.
- API keys are securely distributed throughout APEX Cloud’s portals.
- Provides template dashboards and log management through the following features.

    - The Elastic, Logstash and, Kibana (ELK) stack is offered through StackOps and this provides template dashboards for reporting.
    - The ELK stack also comes with a comprehensive search function to support tracing and debugging
Facilities collaboration between agencies and encourages discovery of WOG API offerings.

- With over 30 agencies onboard APEX Cloud, users can experience a diversity of APIs and cross-sharing
Security compliant with cross-zone support for internet and intranet environments.

- APEX Cloud is security-compliant and keeps up with policy changes and updates on a regular basis
Integration of APEX Cloud with best practices and standards helps users keep up with the latest API and security best practices
Incorporation of industry standardisation and best practices for user security.

- Mutual Transport Layer Security (TLS) with JWKS (JSON Web Key Sets) and secured data exchange with JWT (JSON Web Token) for same and cross-zone exchange
API sandbox to promote discovery and self service sampling of APIs.

To know more about APEX Cloud's key features, see [Features](https://docs.developer.tech.gov.sg/docs/apex-cloud-getting-started-guide/docs/features).

## Technical Specifications

APEX Cloud has the following technical specifications.

| **APEX Cloud**  | Defaults  | Can be increased/decreased? (Quotas) |
| -------------------------------- | ---------------------------- | ----------------------------------- |
| **Authentication**  | Inbound:<br>API Key + JWT<br>Outbound: <br>API Key, TLS, MTLS,<br>AWS Signature v4,<br>custom policies | Not Applicable |
| **Authorization**   | Token-based AuthZ with OAuth,<br>OAuth with Singpass/Corppass  | Not Applicable                      |
| **Protocols Supported** | SOAP, REST, JSON, XML | Not Applicable  |
| **Payload Size Limit (send)**    | 10 MB  | No   |
| **Payload Size Limit (receive)** | 10 MB  | No   |
| **Concurrent connections**       | 128    | Yes  |
| **Connection timeout**           | 30 seconds    | Yes   |
| **Active timeout**               | 30 seconds    | Yes   |