# Technical Specifications

APEX Cloud has the following technical specifications.

## General

| Parameters | Defaults  | Can be increased/decreased? (Quotas) |
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

## Supported TLS Version and Cipher Suites

| TLS Protocol Version | TLS Ciphers |
| -- | -- |
| Protocol-TLSv1.2 | ECDHE-ECDSA-AES128-GCM-SHA256<br> ECDHE-ECDSA-AES256-GCM-SHA384<br> ECDHE-RSA-AES128-GCM-SHA256<br> ECDHE-RSA-AES256-GCM-SHA384<br>
