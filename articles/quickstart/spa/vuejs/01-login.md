---
title: Login
description: This tutorial demonstrates how to add user login to a Vue.JS application using Auth0.
budicon: 448
topics:
  - quickstarts
  - spa
  - vuejs
  - login
github:
  path: 01-Login
contentType: tutorial
useCase: quickstart
---

<%= include('../_includes/_getting_started', { library: 'Vue.js', callback: 'http://localhost:3000/callback', returnTo: 'http://localhost:3000', showLogoutInfo: true, showWebOriginInfo: true }) %>

<%= include('_includes/_centralized_login') %>
