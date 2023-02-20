---
title: "Introduction"
description: "Welcome to the Signalmash API docs! This is the place to find official information on how to use Signalmash services and products in your app."
lead: ""
date: 2020-10-06T08:48:57+00:00
lastmod: 2020-10-06T08:48:57+00:00
draft: false
images: []
menu:
  docs:
    parent: "getting-started"
weight: 100
toc: true
---
Welcome to the Signalmash API docs! This is the place to find official information on how to use Signalmash services and products in your app.

This site provides comprehensive documentation for all of our APIs and you’ll find everything you need to know about working with a particular API in the corresponding section.

However, there are some fundamental concepts that you need to understand and tools that might help you that apply across all our APIs. Here, we'll give you this information and get you up and running as quickly as possible.

##### What you will learn:

* Signing up for an account
* Accessing API Token information
* Experimenting with our APIs
* Working with Webhooks
* What to do next

### Signing up for an account

To work with our APIs, you will need to [sign up](https://portal.signalmash.com/#/signup) for an account. This will give you an API token and key that you can use to access our APIs.

### Accessing API Token information

Every API request authenticates the user, which you may do through the user's site by creating tokens. Users can now use the same or different tokens for each activity they make, thanks to a single management location.

Log in to the portal, then go to the API Menu and select "Tokens" from the submenu. To make a token, go to the right upper corner and click "Add Token." There will be a pop-up window. Choose the function (s) to link to the token.

### Authentication

When using the Signalmash APIs your requests need to be authenticated. Typically this is done using [**Bearer Authentication**]({{< relref "docs/getting-started/authentication" >}}).

**Bearer authentication** (also called token authentication) is an HTTP authentication scheme that involves security tokens called bearer tokens.

The client must send this token in the Authorization header when making requests to protected resources:

`Authorization: Bearer <session-token>`

### Experimenting with our APIs

Ultimately, you’re going to want to build an app in your chosen programming language. But to start with, you might want to make some sample requests to our APIs to check that you have provided the correct parameters and that you are getting back the responses you want.

If you are familiar with the command-line tool Curl, you will find Curl snippets for each of our APIs that you can copy, paste and modify.

#### Postman

Various GUI tools exist that are easier to use than Curl. A popular one is Postman. Signalmash also provides a set of Postman collections, which provides a way to start using the APIs immediately.

### Working with Webhooks

### What to do next

This guide introduced you to some of the fundamental concepts and tools that you should know about when working with our APIs.

Once you understand these fundamental concepts and have installed the tools you intend to use, you are ready to start building! View the documentation for your chosen API to get started, or try out some of the following starter tasks:

* SMS API: Send an SMS
* Voice API: Make an outbound call

We take pride in our documentation, but are always looking to make it better. So if you find anything that is unclear or lacking the information you require, then please submit feedback for the topic in question. If we’ve done a good job on a particular section then please let us know!
