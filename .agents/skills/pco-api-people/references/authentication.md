# Authentication

This document describes the authentication methods supported by this API.

## oauth2

**Type:** oauth2

**authorizationCode flow:**
- Authorization URL: https://api.planningcenteronline.com/oauth/authorize
- Token URL: https://api.planningcenteronline.com/oauth/token
- Scopes:
  - `people`: Required scope for accessing via OAuth 2

## personal_access_token

**Type:** http

Provide your Personal Access Token Client ID as the HTTP Basic username
and your Secret as the HTTP Basic password.

Example header:
Authorization: Basic BASE64(client_id:secret)"


- **Scheme:** basic

