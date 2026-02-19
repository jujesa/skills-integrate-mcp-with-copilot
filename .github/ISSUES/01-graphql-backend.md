Title: Add GraphQL backend

Description:
Replace or complement the current REST endpoints with a GraphQL API exposing queries and mutations for activities, signups, students and admin operations.

Acceptance Criteria:
- GraphQL endpoint available at `/graphql` with GraphiQL enabled in dev.
- Queries: `activities`, `activity(id)`, and pagination support.
- Mutations: `signupActivity`, `unregisterActivity`, plus admin mutations.
- Type definitions and resolver structure present.

Labels: enhancement
