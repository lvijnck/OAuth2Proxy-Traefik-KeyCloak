
# OAuth2-Proxy Integration with Keycloak and Web Application

An example of how to use Traefik ForwardAuth with OAuth2-Proxy and the Keycloak provider to give authentication capability in any kind of web application.

## Features
- Integrate Traefik ForwardAuth with OAuth2-Proxy
- Use KeyCloak-oidc provider
- Forward ID token to service

## Usage

Run the following command to spin up the deployment:

```shell
docker compose up
```

- Navigate to `landing.test.localhost` in your browser
- You will be redirected to login page of KeyCloak. Login using test1/pass123
- If successful, you will be redirected to the echo container that displays the full HTTP request.

## Feedback
For feedback and feature request, please raise issues in the issue section of the repository. Enjoy!
