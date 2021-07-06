---
description: Work in progress Documentation for our API.
---

# Status root endpoint 

{% api-method method="get" host="https://isthicc.dev" path="/api/v1/status" %}
{% api-method-summary %}
View information about ThiccStatus. 
{% endapi-method-summary %}

{% api-method-description %}
This endpoint gives details about ThiccStatus, and the related endpoints. This endpoint does not provide any user data access.
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
    "urls": [],
    "api_time": "2021-07-06 01:09:56.658914",
    "endpoint": "/api/v1/status",
    "name":"IsThicc API"
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
