# 🗒️ Class 06 - Authentication

## Readings

### Securing Passwords

- Explain to a non-technical friend how you would safely hash and store a password.
  > Passwords are hashed by using an algorithm to take in your password and generating a completely different string of character that represents the password.

- What is Bcrypt?
  > BCrypt is a Slow but strong method to protech passwords. It is an adaptive hash function that uses Key Stretching to make brute force attacks slower and to help minimize the impact.

- Why might you use something like Bcrypt?
  > I would use BCrypt because it is extremely resistant to brute force attacks.

### Basic Authentication

- What is Basic Authentication?
  > Basic Authentication is a method used by a web browser to provide a username and apssword. It is the simplest way to enforce access controls to web resources.

- What properties are necessary in the header of a Basic Auth request?
  > `Authorization: Basic <credentials>` where the credentials ID and Password joined by a single colon, encoded with `Base64`

- How are `username:password` in Basic Auth encoded?
  > It is encoded using `Base64`

### OWASP Auth Cheatsheet

- Define the authentication process to a non-technical recruiter.
  > Authentication is an application's way of verifying that a user is who they say they are.

- How should your error messaging respond (both HTTP and HTML)? Why?
  > Responds need to be done in a generic manner.
