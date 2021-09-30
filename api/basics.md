---
description: Work in progress Documentation for our API.
---

# API Basics

## Authentication

Authentication has been moved to [this](https://docs.isthicc.dev/api/authentication) article!

## Response Standards 

All endpoints are required to respond with the following items:

| Key | Value |
| ------- | ------- |
| api_time | The time when the API created the response, in UTC. |
| endpoint | The endpoint that was requested. |
| info | Basic description of the API and/or endpoint. |
| name | Name of the API. |

In addition to these items, often the data requested will be returned in the "details" key.
