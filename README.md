# Keycloak-Guide
Knowledge about keycloak

# Tokens in keycloak
There are three types of tokens
### ID Token
- Used to indentify a user/entity
- Selv contained token (JWT)
- Lifespan is shorter than refresh token
- Generated as a result of OpenID Connect flow

### Access Token
- User to access a thrird party system (for authorization purpose)
- Self contained or opaque
- Life span is shorter than refresh token
- Generated as a result of Open Authorization flow

### Refresh Token
- User to refresh an access token or ID token
- Self contained or opaque
- Life span is higher than access & ID tokens
