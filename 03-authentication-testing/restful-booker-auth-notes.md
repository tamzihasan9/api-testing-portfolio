# Authentication Notes

- API uses Cookie-based token auth
- Token generated via POST /auth
- Post-response script auto-saves token:
  pm.environment.set("token", jsonData.token);
- Token passed in headers as:
  Cookie: token={{token}}
- Token must be refreshed each session
