# WarframeStat.us OpenAPI Specification
[![GitHub pages](https://github.com/WFCD/api-spec/actions/workflows/docs.yaml/badge.svg)](https://github.com/WFCD/api-spec/actions/workflows/docs.yaml)

## Links

- [Reference Documentation (ReDoc)](https://docs.warframestat.us)
- [SwaggerUI](https://docs.warframestat.us/swagger-ui/)
- OpenAPI Raw Files: [JSON](https://docs.warframestat.us/openapi.json) [YAML](https://docs.warframestat.us/openapi.yaml)

**Warning:** All above links are updated only after Actions finishes deployment

## Working on specification
### Install

1. Install [Node JS](https://nodejs.org/)
2. Clone repo and run `npm install` in the repo root

### Usage

#### `npm start`
Starts the development server on port [`8080`](http://localhost:8080).

#### `npm run build`
Bundles the spec and prepares web_deploy folder with static assets.

#### `npm test`
Validates the spec.

#### `npm run gh-pages`
Deploys docs to GitHub Pages. You don't need to run it manually if you have Travis CI configured.
