---
title: "Introduction"
description: "Welcome to the Signalmash API docs! How to use Signalmash services and products in your app can be found here in official Signalmash documentation."
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
Welcome to the Signalmash API docs! How to use Signalmash services and products in your app can be found here in official Signalmash documentation.

For each of our APIs, this site offers thorough documentation, and the section devoted to that API will have all the information you require.

However, there are some fundamental ideas you must comprehend and resources that could be useful that apply to all of our APIs. Here, we'll give you this knowledge and help you get going as soon as possible.

##### What you will learn:

* Signing up for an account
* Accessing API Token information
* Experimenting with our APIs
* Working with Webhooks
* What to do next

### Signing up for an account

You must [sign up](https://portal.signalmash.com/#/signup) for an account in order to use our APIs. You will receive an API token and key as a result, which you can use to access our APIs.

### Accessing API Token information

By creating tokens on the user's website, you can authenticate the user for each API request. Thanks to a single management location, users can now use the same or different tokens for each activity they perform.

After logging into the portal, choose "Tokens" from the submenu under the API Menu. A token can be created by clicking "Add New" in the right upper corner. A pop-up window will appear. Select the function or functions to link to the token.

### Authentication

Your requests need to be authenticated when using the Signalmash APIs. Most often, this is accomplished with [**Bearer Authentication**]({{< relref "docs/getting-started/authentication" >}}).

The HTTP authentication method known as **Bearer Authentication** (also known as "token authentication") uses bearer tokens as security tokens.

When sending requests to protected resources, the client must include this token in the Authorization header:

`Authorization: Bearer <token>`

### Experimenting with our APIs

You should eventually create an app in the programming language of your choice. But first, you might want to send some practice requests to our APIs to make sure you have the right input parameters and are receiving the desired results.

You will find Curl snippets for each of our APIs that you can copy, paste, and alter if you are familiar with the command-line tool Curl.

#### Postman

There are many GUI tools available that are simpler to use than Curl. One of them is Postman. In order to get started using the APIs right away, Signalmash also offers a selection of [Postman collections](https://www.postman.com/abundant-geeks/workspace/signalmash/collection/2741802-d6c11002-9593-4958-b323-8eb0dd39092c?action=share&creator=2741802).

### Working with Webhooks

Webhooks are user-defined HTTP callbacks triggered by an event in a web application. Signalmash uses webhooks to let your application know when events happen, like getting an incoming call or receiving an SMS message and SMS states. Webhooks are triggered asynchronously.

To handle a webhook when you use Signalmash, you need to build a small web application that can accept HTTP POST requests.

### What to do next

In this guide, we've introduced some of the fundamental concepts and resources you should be familiar with before using our APIs.

View the documentation for your chosen API to get started, or try out some of the following starter tasks once you have a firm grasp of these fundamental ideas and have installed the tools you intend to use.

* SMS API: Send an SMS
* Voice API: Make an outbound call

Although we are proud of our documentation, we are constantly looking for ways to improve it. Please provide feedback for the relevant topic if you discover anything that is unclear or lacking the information you need. Let us know if we did a good job if you think a certain section was completed.
