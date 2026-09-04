# Croner Staging

Public GitHub Pages staging artifact for [Croner](https://croner.dev).

- Frontend: <https://travellervs.github.io/croner-dev-staging/>
- API: <https://vander-spring-cron-api-staging.onrender.com>
- Source branch: private `TravellerVS/vander-engineering-website` `develop`
- Source commit: `fd8d36b80ba33ec0258dbf6cc11e9b2af6cd0e34`

This environment is stateless, uses no database, is visibly marked **Staging**,
and is blocked from search indexing. Generated files in this repository should
not be edited directly.

Promotion flow: validate `develop` here, merge the approved source to `master`,
then build and publish the tagged production artifact to
`TravellerVS/croner-dev`.
Public GitHub Pages staging deployment for Croner
