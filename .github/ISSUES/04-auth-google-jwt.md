Title: Add Google login + JWT authentication

Description:
Add login via Google OAuth token exchange and issue JWTs for authenticated requests.

Acceptance Criteria:
- Endpoint to accept Google ID token and create/return a signed JWT.
- Middleware verifies JWT and populates `current_user` for protected endpoints.
- Tests for login flow and protected endpoint access.

Labels: enhancement
