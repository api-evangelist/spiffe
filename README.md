# SPIFFE (spiffe)
Secure Production Identity Framework for Everyone (SPIFFE) is a set of open-source standards for securely identifying software systems in dynamic and heterogeneous environments through platform-agnostic, cryptographic identities. SPIFFE defines the SPIFFE ID URI format, the X.509 SVID and JWT SVID identity document formats, and the Workload API for issuing and rotating identities without secrets or passwords.

**URL:** [Visit APIs.json URL](https://spiffe.io/)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Security, Identity, Authentication, Zero Trust, Cloud Native, Graduated

## Timestamps

- **Created:** 2025 
- **Modified:** 2026-03-18 

## APIs

### SPIFFE Workload API
The SPIFFE Workload API is a gRPC-based interface through which workloads request and receive SPIFFE Verifiable Identity Documents (SVIDs) including X.509-SVIDs and JWT-SVIDs, as well as trust bundle updates. It enables software to obtain cryptographic identities at runtime without requiring secrets to be embedded in configuration or code.

**Human URL:** [https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Workload_API.md](https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Workload_API.md)


#### Tags:

 - gRPC, Identity, X.509, JWT, Workload

#### Properties

- [Documentation](https://spiffe.io/docs/latest/spiffe-about/spiffe-concepts/)
- [Reference](https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Workload_API.md)
- [AsyncAPI](asyncapi/spiffe-workload-asyncapi.yml)
- [GitHubRepository](https://github.com/spiffe/spiffe)

### SPIFFE X.509 SVID
The SPIFFE X.509 SVID (SPIFFE Verifiable Identity Document) is a standard for encoding SPIFFE identities into X.509 certificates. The Subject Alternative Name field carries the SPIFFE ID URI, enabling mutual TLS authentication between workloads using standard X.509 certificate validation libraries.

**Human URL:** [https://github.com/spiffe/spiffe/blob/main/standards/X509-SVID.md](https://github.com/spiffe/spiffe/blob/main/standards/X509-SVID.md)


#### Tags:

 - X.509, Identity, mTLS, Security, Certificate

#### Properties

- [Documentation](https://spiffe.io/docs/latest/spiffe-about/svid/)
- [Reference](https://github.com/spiffe/spiffe/blob/main/standards/X509-SVID.md)
- [GitHubRepository](https://github.com/spiffe/spiffe)

### SPIFFE JWT SVID
The SPIFFE JWT SVID standard defines a format for encoding SPIFFE identities as JSON Web Tokens. JWT-SVIDs are used in scenarios where X.509 certificates are not practical, such as HTTP header-based authentication between services or for passing identity across trust domain boundaries.

**Human URL:** [https://github.com/spiffe/spiffe/blob/main/standards/JWT-SVID.md](https://github.com/spiffe/spiffe/blob/main/standards/JWT-SVID.md)


#### Tags:

 - JWT, Identity, Security, Authentication

#### Properties

- [Documentation](https://spiffe.io/docs/latest/spiffe-about/svid/)
- [Reference](https://github.com/spiffe/spiffe/blob/main/standards/JWT-SVID.md)
- [GitHubRepository](https://github.com/spiffe/spiffe)

### SPIFFE Federation API
The SPIFFE Federation API defines how SPIFFE trust domains exchange trust bundle information to enable cross-domain workload authentication. It specifies the SPIFFE Trust Domain and Bundle endpoint format, allowing systems in different trust domains to establish mutual trust and authenticate workloads across organizational or infrastructure boundaries.

**Human URL:** [https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Trust_Domain_and_Bundle.md](https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Trust_Domain_and_Bundle.md)


#### Tags:

 - Federation, Trust Domain, Identity, Security, Cross-Domain

#### Properties

- [Documentation](https://spiffe.io/docs/latest/spiffe-about/spiffe-concepts/)
- [Reference](https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Trust_Domain_and_Bundle.md)
- [OpenAPI](openapi/spiffe-federation-openapi.yml)
- [GitHubRepository](https://github.com/spiffe/spiffe)

## Common Properties

- [JSONSchema](json-schema/spiffe-svid-schema.json)
- [JSON-LD](json-ld/spiffe-context.jsonld)
- [Website](https://spiffe.io/)
- [Documentation](https://spiffe.io/docs/latest/)
- [Getting Started](https://spiffe.io/docs/latest/spiffe-about/spiffe-concepts/)
- [GitHub Organization](https://github.com/spiffe)
- [GitHubRepository](https://github.com/spiffe/spiffe)
- [Community](https://spiffe.io/community/)
- [Slack](https://slack.spiffe.io)
- [Blog](https://spiffe.io/blog/)
- [Security](https://github.com/spiffe/spiffe/blob/main/SECURITY.md)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spiffe)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
