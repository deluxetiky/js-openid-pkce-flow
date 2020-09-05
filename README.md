# SPA - Code Flow With PKCE - Sample

## Config

The oopenid config file is located at index.html. DemoIdentity server used.

```txt
var settings = {
            authority: <identityDomain>,
            client_id: <client_id>,
            response_type: "code",
            scope: "openid profile",

            redirect_uri: "http://localhost:5000/callback.html",
            post_logout_redirect_uri: "http://localhost:5000/index.html",
            
            automaticSilentRenew: false,
            silent_redirect_uri: "http://localhost:5000/silent.html"
        };
```

## Run

```sh
npm run server
```
