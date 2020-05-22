# 30 days of Kotlin
 
Google program to learn kotlin.


# About app


# Kotlin Android CRUD app

This is the Android Studio source for the client side of the Kotlin Android CRUD 

## Setup

You need to fill out `app/src/main/res/raw/okta_app_auth_config.json` with your  Application details.
It should look like this:

```
{
  "client_id": "{CLIENT_ID}",
  "redirect_uri": "com.oktapreview.dev-628819:/callback",
  "scopes": [
    "openid",
    "profile",
    "offline_access"
  ],
  
}
```

Note you also need to have the *server* setup and running locally for this app to work.

## Running

You should be able to run this on an emulator just by pressing Play in Android Studio.