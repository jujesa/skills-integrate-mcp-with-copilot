Title: Implement cascading activation/deactivation logic

Description:
When a center or group is deactivated, cascade changes to related groups, students and instructors (set `active=false` when no other associations exist).

Acceptance Criteria:
- Deactivation of center updates child groups and related user records per rules.
- Tests for cascading behavior when deleting or deactivating centers/groups.

Labels: enhancement
