# LoginAppAuth
Spring Boot 3+, Spring Data JPA, Spring Security, Spring Web, and OAuth2Resource server application code that allows users to login or register via HTTP POST requests, then see endpoints according on their responsibilities.

A custom UserDetailsService and AuthenticationManager, as well as Spring Data JPA repositories, are used to authenticate users against a database.

When a user successfully logs in, a JWT is generated and returned to them; the user can use this JWT in the header as a bearer token to access authenticated routes based on their responsibilities.

