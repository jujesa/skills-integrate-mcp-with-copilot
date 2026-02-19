Title: Add MongoDB persistence for activities and users

Description:
Persist activities, signups and user records in MongoDB instead of memory so data survives restarts and supports queries.

Acceptance Criteria:
- Add DB connection config via `MONGO_URL` and `DB_NAME`.
- Migrate `activities` to a `activities` collection and `users` to a `users` collection.
- CRUD operations work against MongoDB and tests for basic flows pass.

Labels: enhancement
