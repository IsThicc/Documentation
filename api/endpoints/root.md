---
description: Work in progress Documentation for our API.
---

# Root endpoint 

{% api-method method="get" host="https://isthicc.dev" path="/api" %}
{% api-method-summary %}
View information about IsThicc Software, and our API.
{% endapi-method-summary %}

{% api-method-description %}
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}

<!-- 
{% api-method-path-parameters %}
{% api-method-parameter name="id" type="string" %}
ID of the cake to get, for free of course.
{% endapi-method-parameter %}
{% endapi-method-path-parameters %} 
-->

{% api-method-headers %}
{% api-method-parameter name="None" type="string" required=false %}
We do not require any headers.
{% endapi-method-parameter %}
{% endapi-method-headers %}

<!--
{% api-method-query-parameters %}
{% api-method-parameter name="recipe" type="string" %}
The API will do its best to find a cake matching the provided recipe.
{% endapi-method-parameter %}

{% api-method-parameter name="gluten" type="boolean" %}
Whether the cake should be gluten-free or not.
{% endapi-method-parameter %}
{% endapi-method-query-parameters %} 
-->

{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}

<!-- 
{% api-method-response-example-description %}
Cake successfully retrieved.
{% endapi-method-response-example-description %} 
-->

```
{
    "info":"The IsThicc API is a REST API to interact with IsThicc Software(services, products, etc.).",
    "main_urls":{
        "Information":["/api/v1/info", "/api/v1/information"],
        "Licensing":["/api/v1/license", "/api/v1/licensing"],
        "Main":["/api/v1"], 
        "Status":["/api/v1/status"],
        "Updates":["/api/v1/update/", "/api/v1/updates"]
        },
    "redirect_urls":{
        "api":"https://isthicc.dev/api",
        "cdn":"https://isthicc.dev/cdn",
        "github":"https://github.com/IsThicc/"
        },
    "api_time": "2021-07-06 01:09:56.658914",
    "endpoint": "/api",
    "name":"IsThicc API",
    "website":"https://isthicc.dev/"
}
```
{% endapi-method-response-example %}

<!-- 
{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Could not find a cake matching this query.
{% endapi-method-response-example-description %}

```
{    "message": "Ain't no cake like that."}
```
{% endapi-method-response-example %} 
-->

{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}
