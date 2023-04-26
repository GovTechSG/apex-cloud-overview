# Technical Specifications

APEX Cloud has the following technical specifications.

| **APEX Cloud**  | Defaults  | Can be increased/decreased? (Quotas) |
| -------------------------------- | ---------------------------- | ----------------------------------- |
| **Authentication**  | **Inbound:**<br>API Key + JWT<br>**Outbound:** <br>API Key, TLS, MTLS,<br>AWS Signature v4,<br>custom policies | Not Applicable |
| **Authorization**   | Token-based AuthZ with OAuth,<br>OAuth with Singpass/Corppass  | Not Applicable                      |
| **Protocols Supported** | SOAP, REST, JSON, XML | Not Applicable  |
| **Payload Size Limit (Send)**    | 10 MB  | No   |
| **Payload Size Limit (Receive)** | 10 MB  | No   |
| **Concurrent connections**       | 128    | Yes  |
| **Connection timeout**           | 30 seconds    | Yes   |
| **Active timeout**               | 30 seconds    | Yes   |
| **Max Transaction Per Second (API)** | 20 | Yes |
| **Max Transaction Per Second (Application)** | 20 | Yes |