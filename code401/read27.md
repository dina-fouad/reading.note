# What is JSON Web Token?
JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

## When should you use JSON Web Tokens?
- Information Exchange:

 JSON Web Tokens are a good way of securely transmitting information between parties.

- Authorization: 

This is the most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token.

## What is the JSON Web Token structure?
In its compact form, JSON Web Tokens consist of three parts separated by dots (.), which are:

- Header
- Payload
- Signature

## Why should we use JSON Web Tokens?
Let's talk about the benefits of JSON Web Tokens (JWT) when compared to Simple Web Tokens (SWT) and Security Assertion Markup Language Tokens (SAML).

As JSON is less verbose than XML, when it is encoded its size is also smaller, making JWT more compact than SAML. This makes JWT a good choice to be passed in HTML and HTTP environments.

## How JWT Works?
The JWT is just an authorization token that should be included in all requests:
```
curl http://127.0.0.1:8000/hello/ -H 'Authorization: Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b2tlbl90eXBl
```

## Django Runserver Is Not Your Production Server
You’ve built your Django web app and are working on deploying it.

You’ve been running your app locally with python manage.py runserver. That’s a fine command, built for development convenience, but it’s not meant to be used as part of a production setup.

## How Does Django Fit In?
Your Django app does not actually run as you would think a server would - waiting for requests and reacting to them. Your project provides a uwsgi.py file, which contains a function to be called by the application server. This function gets a Python object representing the incoming request.

