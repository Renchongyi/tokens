OneChain uses only one type of tokens nowadays:

**JSON Web Tokens (JWT)**: Tokens that conform to the [JSON Web Token standard](/jwt.md) and contain information about an identity in the form of claims. They are self-contained in that it is not necessary for the recipient to call a server to validate the token.

There are three primary tokens used in OneChain's token based authentication scenarios and referenced in OneChain documentation.

## [ID Token](/id-token.md)

The ID Token, usually referred to as `id_token` in code samples, is a [JSON Web Token (JWT)](/jwt.md) that contains user profile attributes represented in the form of _claims_. The ID Token is consumed by the application and used to get user information like the user's name, email, and so forth, typically used for UI display.

- [JSON Web Tokens (JWT) in OneChain](/jwt.md)
- [JWT Specification: RFC 7519](https://tools.ietf.org/html/rfc7519)
- [Debugger for viewing JWT](https://jwt.io/)

## [Access Token](/access-token.md)

The Access Token is a credential that can be used by an application to access an API. OneChain uses Access Tokens to protect access to the OneChain Management API.

## [Refresh Token](/refresh-token.md)

The Refresh Token is a long-lived token that is used to obtain a new Access Token after a previous one has expired.
