# 🗒️ Class 15

## What is OAuth

- What is OAuth?

> Oauth is a open-standard authentication protocol created and stronly supported by Twitter, Google and other companies. 

- Give an example of what using OAuth would look like.

> WHen you go to a website and try to log onto it and it offers the ability to logon using another service such as Github, google, or twitter.

- How does OAuth work? What are the steps that it takes to authenticate the user?

>> User selects what sercive they want to use to connect to the first website with. The service provider will generate a token and secret and sends it to the first website. Once approved, the first website will get an access token and secret that will allow them to connect using the selected service provider.

- What is OpenID?

> simply put, OpenID is a service used for humans logging into a machine (server) where as Oauth is a machine logging into a machine.

## Authorization and Authentication flows

- What is the difference between authorization and authentication?

> Auhorization is what you are allowed to access in an applicaiton and authentication is verifying who the user is.

- What is Authorization Code Flow?

> Authorization code flow is the process of exchanging Authorization codes for tokens and granting access.

- What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

> An authorization method that uses a different grant type because the application doesnt support soring of client secrets. Instead it uses an authorization server, such as Code Verifier, to generate a secret. 

- What is Implicit Flow with Form Post?

> A method that uses an authorization code flow from the backend to create an ID Token. This method eliminates the need for secrets and any additional backend calls.

- What is Client Credentials Flow?

> A method that allows an application to authenticate and authorize using only a client ID and Secret

- What is Device Authorization Flow?

> Device authorization flow provides the user with a link to their device or email and they access that link via their smart phone or thorugh the email.

- What is Resource Owner Password Flow?

> A resource owner password flow is a method that requests the user to provide their username and password and get sent to the backend to be authenticated and then exchanged for an access token.
