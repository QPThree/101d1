# Authentication

## In this Article

[What is OAuth?](#topic1)

[Authorization and Flow](#topic2)

[Things I Want To Know](#topic3)

---

<a name="topic1"></a>

## OAuth

* What is OAuth?

An open-standar framework that allows users to use a single sign-on (SSO) across a range of sites and services.

* Give an example of what using OAuth would look like.

Going to login to a website, and you are given the option of logging in or signing up with your google, apple, or other account. 

* How does OAuth work? What are the steps that it takes to authenticate the user?

The user wishes to access or complete a transaction on one site. In order to do so, they must sign on with credentials from another site. The site they are accessing reaches out to the site that contains the user's information. The site with the user's information asks the user to verify their identity by entering credentials. Once accepted, that site returns a certificate to the site the user is accessing that says the user has been verified. 

4. What is OpenID?

OpenID is another security technology that as the site puts it, "is for humans logging into machines".

<a name="topic2"></a>

## Authorization and Flow

* What is the difference between authorization and authentication?

Authentication is verifying who the user actually *is*. Authorization is verifying the content that the authenticated person has access to.

* What is Authorization Code Flow?

Essentially the steps taken from user login to the user getting the information requested. It exchanges an Authorization code for a token.

* What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

A way of using ACF with mobile applications or single page applications. 

* What is Implicit Flow with Form Post?

IFwFP is used for public clients, or situations where the clients secret is unable to be stored securely.

* What is Client Credentials Flow?

This is used for applications where communication is between two machines (machine to machine). In these instances, entering a username or password wouldn't make sense of be done by the user. Instead, the system 

* What is Device Authorization Flow?

Device authorization flow is used for devices where user input would make for a poor experience. Instead, users are asked to go to a website on their phone or computer and enter their information that way. Logging in to an app on my TV comes to mind.

* What is Resource Owner Password Flow?



<a name="topic3"></a>

## Things I Want to Know More About


~ QP3

[Home](../README.md)

Information put into my own words came from *https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html* & *https://auth0.com/docs/flows*
