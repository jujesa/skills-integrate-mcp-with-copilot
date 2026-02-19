Title: Add file upload support (e.g., instructor photos, attachments)

Description:
Allow uploading files from frontends to the server, store them (S3 or local) and expose URLs in the API.

Acceptance Criteria:
- Upload endpoint supporting multipart/form-data.
- Files stored and retrievable via public or signed URLs.
- Validation for file size and type.

Labels: enhancement
