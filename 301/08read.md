# API's

## Question

1. What does REST stand for?

Representational State Transfer

2. REST APIs are designed around a ____.

Resource. e.g. object, data, services.

3. What is an identifer of a resource? Give an example.

An identifier is a URI that specifically and uniquely defines a resource. An example might be *https://example-resource.com/Data/1*

4. What are the most common HTTP verbs?

GET, POST, PUT, PATCH, and DELETE

5. What should the URIs be based on?

URI's should be based on nouns, and not the verbs.

6. Give an example of a good URI.

*https://example-site.com/orders*

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

Chatty implies there are multiple or many requests, each gathering small bits of data. This is poor practice as at large scales this can tie up resources. A better design would be to have fewer requests that recieve bigger allotments of data.

8. What status code does a successful GET request return?

A 200 (OK) code. 

9. What status code does an unsuccessful GET request return?

A 404 error.
 
10. What status code does a successful POST request return?

A 201 (CREATED code.

11. What status code does a successful DELETE request return?

A 204 (NO CONTENT) code.

~ QP3

[Home](../README.md)

Information put into my own words came from *https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design*
