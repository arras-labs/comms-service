# Comms Service

## Overview
Service responsible for messaging, event handling, and integration with external systems.

## Scope
- Consume and publish events
- Bridge between backend and external endpoints
- Provide retry, dead-letter, and observability

## Tech stack
TBD (e.g., Node.js, Kafka/MQTT, HTTP webhooks)

## Local development
- Install dependencies: `npm ci`
- Run locally: see `package.json` scripts
- Configure broker endpoints via environment variables

## Testing
Unit and integration tests for consumers/producers.

## CI
Lints, tests, and optionally builds a Docker image on push and PR.

## Deployment
Managed via the `deploy` repository.
