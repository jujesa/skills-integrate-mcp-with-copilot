Title: Implement authorization checks (roles/permissions)

Description:
Add server-side authorization mechanisms to restrict admin operations (create/edit/delete) to authorized users.

Acceptance Criteria:
- Role model (e.g., `admin`, `staff`, `student`) stored per user.
- Authorization checks enforced on admin mutations/endpoints.
- Tests proving unauthorized users cannot perform protected actions.

Labels: enhancement
