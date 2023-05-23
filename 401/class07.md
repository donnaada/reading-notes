# 🗒️ Class 07 - Bearer Authorization

## Readings

### Intro to JWT

- What is a JSON Web Token (JWT)?
  > A JWT is a standard that defines self-contained way to securely tranmit between server and client as a json object.

- When should we use JSON Web Tokens?
  > JWT should be used during authorization and information exchange

- Claims are expected in which structural component of a JWT?
  > Claims are expected in the Payload Area.THere are 3 types of claims, registered, public, and private.

### Are JWTs Secure?

- If I get a JWT and I can decode the payload, how can we call that secure?
  > It is still secure because without knowing what the private key is, the content becomes read-only.

- If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
  >   `Hash(payload + secret)`
  
- Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
  > By sending a hash that contains the content concatenated with the secret, we can ensure that the information will remain confidenial and if in the event of a interception, we can be assured that the content will not be albe to be changed.

## Videos

### JWTs Explained

- Why use JWT?
  > Because it allows for information to be transferred securely between two systems. Also, they are digitally signed so the information is trusted and secure.

- JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
  > Because it is compact, it can be sent via a URL and is fast to be transferred. Self contained makes it so we can avoid querying the database more than we need to.

- What are the three components (the structure) of a JWT signature?
  > Header, Payload, Signature
