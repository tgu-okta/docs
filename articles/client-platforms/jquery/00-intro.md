---
title: Introduction
description: A multi-step quickstart guide to setup and manage authentication in your jQuery app using Auth0.
---

This multistep quickstart guide will walk you through setting up and managing authentication in your jQuery apps using Auth0.

## 1. Create an Application

<%= include('../../_includes/_new_app') %>_

![App Dashboard](/media/articles/angularjs/app_dashboard.png)

## 2. Dependencies

To integrate your jQuery application with Auth0, you will need to add the following dependency:

- [Lock Widget](/libraries/lock) is the default authentication widget provided by Auth0.

  From [npm](https://www.npmjs.com/package/auth0-lock):

  `npm install --save auth0-lock`

  From [bower](http://bower.io):

  `bower install auth0-lock`

  Or the Auth0 CDN:

  `<script src="http://cdn.auth0.com/js/lock/10.2/lock.min.js"></script>`