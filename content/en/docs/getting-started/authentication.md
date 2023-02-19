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
Signalmash APIs use the Bearer authentication (also called token authentication) for authentication. Signalmash supports common token authentication such as those for web server, client-side, installed, and device applications.

To begin, obtain API token credentials from the Signalmash Portal. Then your client application requests an access token from Signalmash API, extracts a session token from the response, and sends the session token to the Signalmash API that you want to access.

### Basic Authentication Steps

#### 1. Obtain API token credentials from Signalmash Portal.

Visit the Signalmash Portal (go to the API Menu and select "[Tokens](https://portal.signalmash.com/#/api/tokens)" from the submenu) to obtain token credentials such as a **Token Name** and **API key** that are known to both Signalmash and your application.

#### 2. Obtain a session token from Signalmash API login.



### Revoking API Token

In some cases a user may wish to revoke access given to an application. A user can revoke access by visiting Signalmash Portal (go to the API Menu and select "[Tokens](https://portal.signalmash.com/#/api/tokens)" from the submenu) and click the delete icon.