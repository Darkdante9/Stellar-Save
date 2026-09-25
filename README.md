# Project

A full-stack application with a backend API (REST + GraphQL) and a frontend client.

## Documentation

- [Getting Started](docs/guides/getting-started.md)
- [Backend Service Map](backend/docs/service-map.md)
- [API Reference](docs/api/README.md) — external REST/GraphQL reference, versioning and deprecation policy
- [Contracts](contracts/README.md)

## API Reference

The external API reference for the backend REST and GraphQL endpoints is published under [`docs/api/`](docs/api/README.md). It is generated from the existing backend route and schema definitions and includes the versioning and deprecation policy for external consumers.

## Repository Layout

- `backend/` — backend services and API routes
- `frontend/` — frontend client (GraphQL operations under `frontend/src/graphql`)
- `contracts/` — shared API contracts
- `docs/` — project documentation, including the published API reference
