---
title: Azure SDK for JavaScript (January 2020)
layout: post
date: January 2020
tags: javascript typescript
sidebar: releases_sidebar
repository: azure/azure-sdk-for-js
---

The Azure SDK team is pleased to make available the January 2020 client library release. This represents the seventh release of the ground-up rewrite of the client libraries to ensure consistency, idiomatic design, and excellent developer experience and productivity. This release includes:
- libraries that are moving out of the preview stage.
    - Azure Event Hubs
    - Azure Key Vault for Certificates
    - Azure App Configuration
- new preview for Azure Text Analytics

## Installation Instructions
To install the packages, copy and paste the below into a terminal.

    $> npm install @azure/app-configuration
    $> npm install @azure/keyvault-certificates
    $> npm install @azure/event-hubs
    $> npm install @azure/eventhubs-checkpointstore-blob
    $> npm install @azure/ai-text-analytics

## Feedback
If you have a bug or feature request for one of the libraries, please post an issue at the [azure-sdk-for-js repository](https://github.com/azure/azure-sdk-for-js/issues)

## Changelog
Detailed change logs are linked to in the Quick Links below.

## Quick Links

{% assign packages = site.data.releases.latest.js-packages %}
{% include js-packages.html %}

{% include refs.md %}
