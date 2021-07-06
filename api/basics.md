---
description: Work in progress Documentation for our API.
---

# API Basics

## Authentication 

Not all endpoints require authentication. To view which require authentication visit [this](/api/basics) documentation article!

In order to authenticate against the API you will need an API token. To get a token you will need a dashboard account [here](https://isthicc.dev/login)! After you create an account you can create a token [here](https://isthicc.dev/dash/api). In order to use your token, verify the endpoint you are trying to use requires authentication, after you've done that, supply your API token in the "Authentication" header. 

## Response Standards 

All endpoints are required to respond with the following items:

| Key | Value |
| ------- | ------- |
| api_time | The time when the API created the response, in UTC. |
| endpoint | The endpoint that was requested. |
| info | Basic description of the API and/or endpoint. |
| name | Name of the API. |

In addition to these items, often the data requested will be returned in the "details" key.
