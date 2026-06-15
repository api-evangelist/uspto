# USPTO (uspto)

The United States Patent and Trademark Office (USPTO) is the federal agency responsible for granting U.S. patents and registering trademarks. USPTO provides a suite of developer APIs through the Open Data Portal (developer.uspto.gov) and data.uspto.gov for programmatic access to patent applications, granted patents, PTAB trial proceedings, trademark status, patent assignments, office actions, and citation data. All USPTO APIs are open government data and return JSON and XML responses. An ODP API key is required for most endpoints.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/uspto/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/uspto/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Government
- Intellectual Property
- Open Data
- Patents
- Regulatory
- Trademarks
- USPTO

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### USPTO Patent & Trademark API

The United States Patent and Trademark Office (USPTO) provides REST APIs for patent search, PTAB trial proceedings, trademark status lookup, and patent citation data. APIs are hosted at developer.uspto.gov and data.uspto.gov. An ODP API key is required for most endpoints.

- **Human URL:** [https://developer.uspto.gov/](https://developer.uspto.gov/)
- **Base URL:** `https://data.uspto.gov/api/v1`

#### Tags

- Assignments
- Government
- Patents
- PTAB
- Regulatory
- Trademarks

#### Properties

- [Documentation](https://developer.uspto.gov/)
- [Reference](https://developer.uspto.gov/api-catalog)
- [OpenAPI](openapi/uspto-patent-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uspto-patent-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uspto-patent-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/uspto-patent-schema.json) — [JSON Schema](https://json-schema.org/specification)

### USPTO Patent Trial and Appeal Board (PTAB) API

The USPTO PTAB API provides access to Patent Trial and Appeal Board proceedings data including inter partes reviews (IPR), post-grant reviews (PGR), and covered business method (CBM) reviews. Returns trial status, petitions, decisions, and related documents.

- **Human URL:** [https://data.uspto.gov/ptab](https://data.uspto.gov/ptab)

#### Tags

- Government
- PTAB
- Patents
- Regulatory

#### Properties

- [Documentation](https://data.uspto.gov/ptab)
- [OpenAPI](https://data.uspto.gov/swagger/index.html) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uspto-patent-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uspto-patent-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPTO Trademark Status and Document Retrieval (TSDR) API

The USPTO Trademark Status and Document Retrieval (TSDR) API enables programmatic access to trademark case status, filing history, and associated documents. Returns status information for trademark applications and registrations.

- **Human URL:** [https://developer.uspto.gov/swagger/tsdr-api-v1](https://developer.uspto.gov/swagger/tsdr-api-v1)

#### Tags

- Government
- Regulatory
- Trademarks

#### Properties

- [Documentation](https://developer.uspto.gov/swagger/tsdr-api-v1)
- [OpenAPI](https://developer.uspto.gov/swagger/tsdr-api-v1) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uspto-patent-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uspto-patent-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPTO Patent Assignment Search API

The USPTO Patent Assignment Search API retrieves patent assignment information including ownership transfers, recorded assignments, and assignment history for individual patents and patent portfolios.

- **Human URL:** [https://developer.uspto.gov/api-catalog](https://developer.uspto.gov/api-catalog)

#### Tags

- Assignments
- Government
- Patents
- Regulatory

#### Properties

- [Documentation](https://developer.uspto.gov/api-catalog)
- [Postman Collection](collections/uspto-patent-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uspto-patent-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPTO Office Action Text Retrieval API

The USPTO Office Action Text Retrieval API provides access to the full text of USPTO patent examiner office actions. Returns rejection text, claims analysis, and prior art citations for patent applications under examination.

- **Human URL:** [https://developer.uspto.gov/ds-api-docs/index.html?url=https%3A//developer.uspto.gov/ds-api/swagger/docs/oa_actions.json](https://developer.uspto.gov/ds-api-docs/index.html?url=https%3A//developer.uspto.gov/ds-api/swagger/docs/oa_actions.json)

#### Tags

- Government
- Office Actions
- Patents
- Regulatory

#### Properties

- [Documentation](https://developer.uspto.gov/ds-api-docs/index.html?url=https%3A//developer.uspto.gov/ds-api/swagger/docs/oa_actions.json)
- [OpenAPI](https://developer.uspto.gov/ds-api/swagger/docs/oa_actions.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uspto-patent-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uspto-patent-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPTO Enriched Citation API

The USPTO Enriched Citation API provides enriched citation reference metadata for patent documents including non-patent literature and patent citations. Returns structured citation data for patent analysis, competitive intelligence, and IP research.

- **Human URL:** [https://developer.uspto.gov/ds-api-docs/index.html?url=https%3A//developer.uspto.gov/ds-api/swagger/docs/enriched_cited_reference_metadata.json/V3](https://developer.uspto.gov/ds-api-docs/index.html?url=https%3A//developer.uspto.gov/ds-api/swagger/docs/enriched_cited_reference_metadata.json/V3)

#### Tags

- Citations
- Government
- Patents
- Regulatory

#### Properties

- [Documentation](https://developer.uspto.gov/ds-api-docs/index.html?url=https%3A//developer.uspto.gov/ds-api/swagger/docs/enriched_cited_reference_metadata.json/V3)
- [OpenAPI](https://developer.uspto.gov/ds-api/swagger/docs/enriched_cited_reference_metadata.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/uspto-patent-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/uspto-patent-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/USPTO)
- [LinkedIn](https://www.linkedin.com/company/uspto)
- [Portal](https://developer.uspto.gov/)
- [Documentation](https://developer.uspto.gov/)
- [Getting Started](https://developer.uspto.gov/api-catalog)
- [Developer Tools](https://data.uspto.gov/)
- [Privacy Policy](https://www.uspto.gov/privacy-policy)
- [Website](https://www.uspto.gov/)
- [JSON Schema](json-schema/uspto-patent-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/uspto-context.jsonld)
- [JSON Structure](json-structure/uspto-patent-structure.json)
- [Spectral Rules](rules/uspto-rules.yml)
- [Vocabulary](vocabulary/uspto-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
