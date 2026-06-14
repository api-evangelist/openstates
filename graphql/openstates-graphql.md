# Open States GraphQL API

The Open States GraphQL API (v2) provides programmatic access to US state legislative data through a flexible GraphQL interface. The API exposes data covering all 50 states, Washington DC, and Puerto Rico, including bills, legislators, committees, jurisdictions, legislative sessions, and voting records. Queries support filtering by jurisdiction, session, chamber, subject, sponsor, and date, as well as geolocation-based legislator lookups using latitude and longitude coordinates.

Authentication is required via an API key, which can be obtained from open.pluralpolicy.com. The API uses Relay-style cursor-based pagination for list fields, with a maximum of 100 items per request enforced on connections for bills, people, and organizations. The schema follows the Open Civic Data (OCD) data model, with entities identified by OCD-style URIs (e.g., `ocd-jurisdiction/...`).

Note: This GraphQL API (v2) is deprecated in favour of the REST API v3 available at v3.openstates.org. Existing integrations should migrate to the v3 API. The endpoint redirects from `https://openstates.org/graphql/` to `https://open.pluralpolicy.com/graphql/` and requires a valid API key for all queries.

**Endpoint:** https://openstates.org/graphql/

**Documentation:** https://docs.openstates.org/graphql/

**References:**

- Documentation: https://docs.openstates.org/graphql/
- GettingStarted: https://docs.openstates.org/api-v3/
- Reference: https://github.com/openstates/openstates.org/tree/main/graphapi
