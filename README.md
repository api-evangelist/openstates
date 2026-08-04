# Open States (openstates)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Open States is a civic technology project that aggregates and publishes legislative data for all 50 US states, Washington DC, Puerto Rico, and select municipal governments. It provides a REST API (v3) and a deprecated GraphQL API (v2) for programmatic access to bill text, sponsors, votes, legislators, committee information, and legislative events. Data is also available via bulk downloads. The project is maintained by Plural Policy as open civic infrastructure.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/openstates/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/openstates/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Government
- Legislative Data
- Civic Technology
- State Legislature
- Bills
- Legislators
- Committees
- Open Data
- REST
- GraphQL

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Open States API v3

REST API providing programmatic access to US state legislative data including jurisdictions, legislators, bills, committees, and events. Requires an API key obtained from open.pluralpolicy.com. Responses are in JSON. Interactive documentation is available via Swagger UI and ReDoc.

- **Human URL:** [https://docs.openstates.org/api-v3/](https://docs.openstates.org/api-v3/)
- **Base URL:** `https://v3.openstates.org/`

#### Tags

- Legislative Data
- Bills
- Legislators
- Committees
- Events
- REST
- Government

#### Properties

- [Documentation](https://docs.openstates.org/api-v3/)
- [OpenAPI](https://v3.openstates.org/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Swagger U I](https://v3.openstates.org/docs/)
- [Re Doc](https://v3.openstates.org/redoc/)
- [GitHub Repository](https://github.com/openstates/api-v3)

### Open States GraphQL API (v2 - Deprecated)

Legacy GraphQL API providing access to Open States legislative data. This API has been deprecated in favour of API v3. Existing integrations should migrate to the REST v3 API.

- **Human URL:** [https://docs.openstates.org/graphql/](https://docs.openstates.org/graphql/)
- **Base URL:** `https://openstates.org/graphql/`

#### Tags

- GraphQL
- Deprecated
- Legislative Data

#### Properties

- [Documentation](https://docs.openstates.org/graphql/)
- [Graph Q L](graphql/openstates-graphql.md)
- [Graph Q L Schema](graphql/openstates-schema.graphql)

## Common Properties

- [Website](https://pluralpolicy.com/open)
- [Documentation](https://docs.openstates.org/)
- [Git Hub Org](https://github.com/openstates)
- [Blog](https://blog.openstates.org/)
- [Pricing](https://open.pluralpolicy.com/accounts/profile/)
- [X (Twitter)](https://twitter.com/openstates)
- [Plans](plans/openstates-plans-pricing.yml)
- [Rate Limits](rate-limits/openstates-rate-limits.yml)
- [Fin Ops](finops/openstates-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
