# USPTO (uspto)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
