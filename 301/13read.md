# Main Head

## In this Article

[Status Codes](#topic1)

---

<a name="topic1"></a>

## Status Codes

* In your own words, describe what each group of status code represents:
  100’s = No issues so far...
  200’s = We have successfully received your message!
  300’s = We are out of the office, temporarily but possibly permanently.
  400’s = You made an error in how you requested information from us.
  500’s = We had an error in the server and were unable to properly respond.

* What is a status code 202?

  **Accepted**. Used for asynchronous processing and essentially says "the request was valid, but we are still working on it".

* What is a status code 308?

  The endpoint has permanently been moved/changed. **Permanent Redirect**.

* What code would you use if an update didn’t return data to a client?

  **204** *No Content*

* What code would you use if a resource used to exist but no longer does?

  **410** *Gone*

* What is the ‘Forbidden’ status code?

  **403** The use does not have authority to access the resource. 

~ QP3

[Home](../README.md)

Information put into my own words came from *https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/* 
