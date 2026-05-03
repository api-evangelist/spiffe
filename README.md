# SPIFFE

Secure Production Identity Framework for Everyone (SPIFFE) is a set of open-source standards for securely identifying software systems in dynamic and heterogeneous environments through platform-agnostic, cryptographic identities. SPIFFE defines the SPIFFE ID URI format, the X.509 SVID and JWT SVID identity document formats, and the Workload API for issuing and rotating identities without secrets or passwords. SPIFFE is a graduated CNCF project.

**URL:** https://spiffe.io/

## APIs

### SPIFFE Workload API

The SPIFFE Workload API is a gRPC streaming interface through which workloads request and receive SPIFFE Verifiable Identity Documents (SVIDs) including X.509-SVIDs and JWT-SVIDs, as well as trust bundle updates.

- **Specification:** https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Workload_API.md
- **AsyncAPI:** [asyncapi/spiffe-workload-asyncapi.yml](asyncapi/spiffe-workload-asyncapi.yml)

### SPIFFE X.509 SVID

Standard for encoding SPIFFE identities into X.509 certificates with the SPIFFE ID in the Subject Alternative Name field.

- **Specification:** https://github.com/spiffe/spiffe/blob/main/standards/X509-SVID.md

### SPIFFE JWT SVID

Standard for encoding SPIFFE identities as signed JSON Web Tokens for HTTP header-based authentication.

- **Specification:** https://github.com/spiffe/spiffe/blob/main/standards/JWT-SVID.md

### SPIFFE Federation API

Defines how SPIFFE trust domains exchange trust bundle information for cross-domain workload authentication.

- **Specification:** https://github.com/spiffe/spiffe/blob/main/standards/SPIFFE_Trust_Domain_and_Bundle.md
- **OpenAPI:** [openapi/spiffe-federation-openapi.yml](openapi/spiffe-federation-openapi.yml)

## OpenAPI Specifications

| API | File |
|-----|------|
| SPIFFE Federation Bundle Endpoint | [openapi/spiffe-federation-openapi.yml](openapi/spiffe-federation-openapi.yml) |

## AsyncAPI Specifications

| API | File |
|-----|------|
| SPIFFE Workload API | [asyncapi/spiffe-workload-asyncapi.yml](asyncapi/spiffe-workload-asyncapi.yml) |

## Spectral Rules

| Ruleset | File |
|---------|------|
| SPIFFE Rules | [rules/spiffe-rules.yml](rules/spiffe-rules.yml) |

## Capabilities

| Capability | Description | File |
|------------|-------------|------|
| Workload Identity | SPIFFE workload identity and federation workflows | [capabilities/workload-identity.yaml](capabilities/workload-identity.yaml) |

### Shared Definitions

| API | File |
|-----|------|
| Federation | [capabilities/shared/federation.yaml](capabilities/shared/federation.yaml) |

## JSON Schema

| Schema | File |
|--------|------|
| SPIFFE SVID | [json-schema/spiffe-svid-schema.json](json-schema/spiffe-svid-schema.json) |

## JSON Structure

| Structure | File |
|-----------|------|
| SPIFFE SVID | [json-structure/spiffe-svid-structure.json](json-structure/spiffe-svid-structure.json) |

## JSON-LD

| Context | File |
|---------|------|
| SPIFFE Context | [json-ld/spiffe-context.jsonld](json-ld/spiffe-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| Get Trust Bundle | [examples/spiffe-get-trust-bundle-example.json](examples/spiffe-get-trust-bundle-example.json) |

## Vocabulary

| Vocabulary | File |
|------------|------|
| SPIFFE Vocabulary | [vocabulary/spiffe-vocabulary.yml](vocabulary/spiffe-vocabulary.yml) |

## Links

- **Website:** https://spiffe.io/
- **Documentation:** https://spiffe.io/docs/latest/
- **GitHub Organization:** https://github.com/spiffe
- **GitHub Repository:** https://github.com/spiffe/spiffe
- **SPIRE (Reference Implementation):** https://github.com/spiffe/spire
- **Community:** https://spiffe.io/community/
- **Slack:** https://slack.spiffe.io
- **Blog:** https://spiffe.io/blog/
- **Stack Overflow:** https://stackoverflow.com/questions/tagged/spiffe
