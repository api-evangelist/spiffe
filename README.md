# SPIFFE (spiffe)

Secure Production Identity Framework for Everyone (SPIFFE) is a set of open-source standards for securely identifying software systems in dynamic and heterogeneous environments through platform-agnostic, cryptographic identities. SPIFFE defines the SPIFFE ID URI format, the X.509 SVID and JWT SVID identity document formats, and the Workload API for issuing and rotating identities without secrets or passwords. SPIFFE is a graduated CNCF project.

**APIs.json:** [https://spiffe.io/](https://spiffe.io/)

## Scope

- **Type:** Index

## Tags

- Authentication
- Cloud Native
- Graduated
- Identity
- Security
- Zero Trust

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-19

## APIs

### SPIFFE Workload API

The SPIFFE Workload API is a gRPC streaming interface through which workloads request and receive SPIFFE Verifiable Identity Documents (SVIDs) including X.509-SVIDs and JWT-SVIDs, as well as trust bundle updates. It enables software to obtain cryptographic identities at runtime without requiring secrets to be embedded in configuration or code.

- **Human URL:** [https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Workload_API.md](https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Workload_API.md)

#### Tags

- gRPC
- Identity
- JWT
- Workload
- X.509

#### Properties

- [Documentation](https://spiffe.io/docs/latest/spiffe-about/spiffe-concepts/)
- [Reference](https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Workload_API.md)
- [AsyncAPI](asyncapi/spiffe-workload-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [GitHub Repository](https://github.com/spiffe/spiffe)
- [Postman Collection](collections/spiffe-federation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spiffe-federation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SPIFFE X.509 SVID

The SPIFFE X.509 SVID (SPIFFE Verifiable Identity Document) is a standard for encoding SPIFFE identities into X.509 certificates. The Subject Alternative Name field carries the SPIFFE ID URI, enabling mutual TLS authentication between workloads using standard X.509 certificate validation libraries.

- **Human URL:** [https://github.com/spiffe/spiffe/blob/main/standards/X509-SVID.md](https://github.com/spiffe/spiffe/blob/main/standards/X509-SVID.md)

#### Tags

- Certificate
- Identity
- mTLS
- Security
- X.509

#### Properties

- [Documentation](https://spiffe.io/docs/latest/spiffe-about/svid/)
- [Reference](https://github.com/spiffe/spiffe/blob/main/standards/X509-SVID.md)
- [GitHub Repository](https://github.com/spiffe/spiffe)
- [Postman Collection](collections/spiffe-federation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spiffe-federation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SPIFFE JWT SVID

The SPIFFE JWT SVID standard defines a format for encoding SPIFFE identities as JSON Web Tokens. JWT-SVIDs are used in scenarios where X.509 certificates are not practical, such as HTTP header-based authentication between services or for passing identity across trust domain boundaries.

- **Human URL:** [https://github.com/spiffe/spiffe/blob/main/standards/JWT-SVID.md](https://github.com/spiffe/spiffe/blob/main/standards/JWT-SVID.md)

#### Tags

- Authentication
- Identity
- JWT
- Security

#### Properties

- [Documentation](https://spiffe.io/docs/latest/spiffe-about/svid/)
- [Reference](https://github.com/spiffe/spiffe/blob/main/standards/JWT-SVID.md)
- [GitHub Repository](https://github.com/spiffe/spiffe)
- [Postman Collection](collections/spiffe-federation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spiffe-federation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SPIFFE Federation API

The SPIFFE Federation API defines how SPIFFE trust domains exchange trust bundle information to enable cross-domain workload authentication. It specifies the SPIFFE Trust Domain and Bundle endpoint format, allowing systems in different trust domains to establish mutual trust and authenticate workloads across organizational or infrastructure boundaries.

- **Human URL:** [https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Trust_Domain_and_Bundle.md](https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Trust_Domain_and_Bundle.md)

#### Tags

- Cross-Domain
- Federation
- Identity
- Security
- Trust Domain

#### Properties

- [Documentation](https://spiffe.io/docs/latest/spiffe-about/spiffe-concepts/)
- [Reference](https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Trust_Domain_and_Bundle.md)
- [OpenAPI](openapi/spiffe-federation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spiffe-federation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spiffe-federation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [GitHub Repository](https://github.com/spiffe/spiffe)
- [Spectral Rules](rules/spiffe-rules.yml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/spiffe-secure-production-identity-framework-for-everyone)
- [JSON Schema](json-schema/spiffe-svid-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/spiffe-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/spiffe-rules.yml)
- [Vocabulary](vocabulary/spiffe-vocabulary.yml)
- [Website](https://spiffe.io/)
- [Documentation](https://spiffe.io/docs/latest/)
- [Getting Started](https://spiffe.io/docs/latest/spiffe-about/spiffe-concepts/)
- [GitHub Organization](https://github.com/spiffe)
- [GitHub Repository](https://github.com/spiffe/spiffe)
- [Community](https://spiffe.io/community/)
- [Slack](https://slack.spiffe.io)
- [Blog](https://spiffe.io/blog/)
- [Security](https://github.com/spiffe/spiffe/blob/main/SECURITY.md)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spiffe)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
