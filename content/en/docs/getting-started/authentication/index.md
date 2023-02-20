---
title: "Authentication"
description: ""
lead: ""
date: 2020-10-06T08:48:57+00:00
lastmod: 2020-10-06T08:48:57+00:00
draft: false
images: []
menu:
  docs:
    parent: "getting-started"
weight: 101
toc: true
---
The Bearer authentication (also known as token authentication) is the authentication method used by Signalmash APIs. Signalmash supports standard token authentication methods for installed, client-side, web server, and mobile application applications.

Obtain API token credentials from the Signalmash Portal to get started. Then, your client application asks the Signalmash API for an access token, takes a session token out of the response, and sends it to the Signalmash API you want to access.

### Basic Authentication Steps

#### 1. Obtain API token credentials from Signalmash Portal.

To get token credentials, such as a **Token Name** and **API KEY** that are known to both Signalmash and your application, go to the Signalmash Portal (go to the API Menu and select "[Tokens](https://portal.signalmash.com//api/tokens)" from the submenu).

![Signalmash Portal API tokens](api-keys.png)

#### 2. Obtain a session token from Signalmash API login.

#### 3. Send the access token to an API.

#### 4. Refresh the access token, if necessary.

### Revoking API Token

An application's access may occasionally be revoked by a user. By visiting Signalmash Portal, selecting "[Tokens](https://portal.signalmash.Com//api/tokens)" from the submenu, and clicking the delete icon, a user can revoke access.
