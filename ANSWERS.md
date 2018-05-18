<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
  * Middle ware are modules that can extend the funcitonality of your  code
  * Express Sessions are a way to authorize clients to access certain areas of the server where unauthorized personnel would be redirected.
  * bcrypt is a library that allows us to encrypt anything confidential.
  * json web tokens allow us to no longer store encrypted data on a clients cookies but in the clients local storage instead which adds a bit more security.
2.  What does bcrypt do in order to prevent attacks?
  * bcrypt hashes confidential data in many different cryptography algorithms.
3.  What are the three parts of the JSON Web Token?
  * no longer using cookies to store confidential data,
  * can be used across domains
  * no longer using database tables like sessions.
  * might i add that also json web tokens are still some what risky as the secret key is still exposed within the server and thus is let open to be possibly leaked.
