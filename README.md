# Croner Staging

Public GitHub Pages staging artifact for [Croner](https://croner.dev).

- Frontend: <https://staging.croner.dev/>
- API: <https://vander-spring-cron-api-staging.onrender.com>
- API custom domain: <https://api-staging.croner.dev/>
- Source branch: private `TravellerVS/vander-engineering-website` `develop`
- Source commit: `68b5dc30f3efc15bb791f94c57e97add7260cd4e`

This environment is stateless, uses no database, is visibly marked **Staging**,
and is blocked from search indexing. Generated files in this repository should
not be edited directly.

Promotion flow: validate `develop` here, merge the approved source to `master`,
then build and publish the tagged production artifact to
`TravellerVS/croner-dev`.
Public GitHub Pages staging deployment for Croner
