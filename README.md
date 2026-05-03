# USPTO

The United States Patent and Trademark Office (USPTO) is the federal agency responsible for granting U.S. patents and registering trademarks. USPTO provides a suite of developer APIs through the Open Data Portal (developer.uspto.gov) and data.uspto.gov for programmatic access to patent applications, granted patents, PTAB trial proceedings, trademark status, patent assignments, office actions, and citation data.

## Overview

| Property | Value |
|---|---|
| **Type** | Index |
| **Portal** | https://developer.uspto.gov/ |
| **Data Portal** | https://data.uspto.gov/ |
| **Created** | 2025-01-01 |
| **Modified** | 2026-05-03 |

## Tags

`Government` `Intellectual Property` `Open Data` `Patents` `Regulatory` `Trademarks` `USPTO`

## APIs

### USPTO Patent & Trademark API

The core REST API providing patent search, PTAB proceedings, trademark status, and assignment data via the Open Data Portal.

- **Base URL:** https://data.uspto.gov/api/v1
- **Auth:** API key (`X-API-KEY` header)
- **OpenAPI:** [openapi/uspto-patent-api-openapi.yml](openapi/uspto-patent-api-openapi.yml)

#### Operations

| Method | Path | Summary |
|---|---|---|
| GET | `/patent/applications/search` | Search Patent Applications |
| GET | `/patent/applications/{applicationNumber}` | Get Patent Application Details |
| GET | `/patent/grants/{patentNumber}` | Get a Granted Patent |
| GET | `/ptab/trials` | Search PTAB Trial Proceedings |
| GET | `/ptab/trials/{trialNumber}` | Get PTAB Trial Details |
| GET | `/ptab/decisions/search` | Search PTAB Decisions |
| GET | `/trademark/status/{serialNumber}` | Get Trademark Application Status |
| GET | `/patent/assignments/search` | Search Patent Assignments |

### USPTO PTAB API

Access to Patent Trial and Appeal Board proceedings including IPR, PGR, and CBM reviews.

- **URL:** https://data.uspto.gov/ptab
- **OpenAPI:** https://data.uspto.gov/swagger/index.html

### USPTO Trademark Status and Document Retrieval (TSDR) API

Programmatic access to trademark case status, filing history, and associated documents.

- **URL:** https://developer.uspto.gov/swagger/tsdr-api-v1

### USPTO Office Action Text Retrieval API

Full text of USPTO patent examiner office actions including rejection text and prior art citations.

- **OpenAPI:** https://developer.uspto.gov/ds-api/swagger/docs/oa_actions.json

### USPTO Enriched Citation API

Enriched citation reference metadata for patent documents including non-patent literature.

- **OpenAPI:** https://developer.uspto.gov/ds-api/swagger/docs/enriched_cited_reference_metadata.json

## Artifacts

### OpenAPI Specification

- [uspto-patent-api-openapi.yml](openapi/uspto-patent-api-openapi.yml)

### Spectral Rules

Ruleset enforcing USPTO API conventions: versioned paths, license requirements, camelCase operationIds, Title Case summaries, and government data standards.

- [uspto-rules.yml](rules/uspto-rules.yml)

### Naftiko Capabilities

Workflow capabilities for patent and trademark research.

| File | Description |
|---|---|
| [capabilities/patent-research.yaml](capabilities/patent-research.yaml) | Patent research workflow — prior art, PTAB monitoring, trademark clearance, assignment research (7 tools) |
| [capabilities/shared/uspto-patent-api.yaml](capabilities/shared/uspto-patent-api.yaml) | Shared per-API definition for USPTO Patent & Trademark API |

### JSON Schema

- [uspto-patent-schema.json](json-schema/uspto-patent-schema.json)

### JSON Structure

- [uspto-patent-structure.json](json-structure/uspto-patent-structure.json)

### JSON-LD Context

- [uspto-context.jsonld](json-ld/uspto-context.jsonld)

### Examples

| File | Operation |
|---|---|
| [uspto-searchPatentApplications-example.json](examples/uspto-searchPatentApplications-example.json) | Search Patent Applications |
| [uspto-searchPTABTrials-example.json](examples/uspto-searchPTABTrials-example.json) | Search PTAB Trials |
| [uspto-getTrademarkStatus-example.json](examples/uspto-getTrademarkStatus-example.json) | Get Trademark Status |
| [uspto-searchPatentAssignments-example.json](examples/uspto-searchPatentAssignments-example.json) | Search Patent Assignments |

### Vocabulary

- [uspto-vocabulary.yml](vocabulary/uspto-vocabulary.yml)

## Common Properties

- [Developer Portal](https://developer.uspto.gov/)
- [API Catalog](https://developer.uspto.gov/api-catalog)
- [Open Data Portal](https://data.uspto.gov/)
- [Privacy Policy](https://www.uspto.gov/privacy-policy)
- [Website](https://www.uspto.gov/)

## Maintainers

- **Kin Lane** — kin@apievangelist.com
