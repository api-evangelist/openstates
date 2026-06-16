# Open States (openstates)

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
