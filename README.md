# Croner Staging

Public GitHub Pages staging artifact for [Croner](https://croner.dev).

- Frontend: <https://staging.croner.dev/>
- API: <https://api-staging.croner.dev/>
- Render origin: <https://vander-spring-cron-api-staging.onrender.com>
- Source branch: private `TravellerVS/vander-engineering-website` `develop`
- Source commit: `637fd272e9e8744298e62a30d4b589b35060d736`

This environment is stateless, uses no database, is visibly marked **Staging**,
and is blocked from search indexing. Generated files in this repository should
not be edited directly.

Promotion flow: validate `develop` here, merge the approved source to `master`,
then build and publish the tagged production artifact to
`TravellerVS/croner-dev`.
Public GitHub Pages staging deployment for Croner
