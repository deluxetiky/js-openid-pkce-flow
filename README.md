# SPA - Code Flow With PKCE - Sample

## Config

The oopenid config file is located at index.html. DemoIdentity server used.

```txt
var settings = {
            authority: identityDomain,
            client_id: "supersavvy-web-dev",
            response_type: "code",
            scope: "openid profile",

            redirect_uri: "http://localhost:5003/callback.html",
            post_logout_redirect_uri: "http://localhost:5003/index.html",
            
            automaticSilentRenew: false,
            silent_redirect_uri: "http://localhost:5003/silent.html"
        };
```

## Run

```sh
npm run server
```
