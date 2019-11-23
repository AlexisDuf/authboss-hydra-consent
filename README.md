# hydra-consent-flow-client

Minimalist go client for hydra consent flow. Essentially it provides typed wrappers for the following paths. Response models are sourced from ory sdk.

```go
  PathGetLogin  = "/oauth2/auth/requests/login" // LoginRequest
  PathAcceptLogin  = "/oauth2/auth/requests/login/accept"  // RequestHandlerResponse
  PathRejectLogin  = "/oauth2/auth/requests/login/reject" // RequestHandlerResponse
  PathGetConsent  = "/oauth2/auth/requests/consent" // ConsentRequest
  PathAcceptConsent  = "/oauth2/auth/requests/consent/accept" // RequestHandlerResponse
  PathRejectConsent  = "/oauth2/auth/requests/consent/reject" // RequestHandlerResponse
  PathGetLogout  = "/oauth2/auth/requests/logout"   // LogoutRequest
  PathAcceptLogout  = "/oauth2/auth/requests/logout/accept" // RequestHandlerResponse
  PathRejectLogout  = "/oauth2/auth/requests/logout/reject" // RequestHandlerResponse
```