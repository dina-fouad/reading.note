## Authentication

- What is OAuth?

its an Open Authorization and its allows third-party services to exchange your information without you having to give away your password .


- Give an example of what using OAuth would look like.

 OAuth provides clients a "secure delegated access" to server resources on behalf of a resource owner like facebook google and twitter

- How does OAuth work?
 What are the steps that it takes to authenticate the user?

 The User Shows Intent. – The Consumer Gets Permission. – The User Is Redirected to the Service Provider. – The User Gives Permission. – The Consumer Obtains an Access Token.

- What is OpenID?

it is allowing you to use an existing account to sign in to multiple websites, without needing to create new passwords.

- What is the difference between authorization and authentication?

Authentication is the act of validating that users are whom they claim to be. This is the first step in any security process.

Authorization in system security is the process of giving the user permission to access a specific resource or function. This term is often used interchangeably with access control or client privilege.

- What is Authorization Code Flow?

1 - The user clicks Login within the regular web application.

2 -Auth0's SDK redirects the user to the Auth0 Authorization Server (/authorize endpoint).

3 - Your Auth0 Authorization Server redirects the user to the login and authorization prompt.

4 - The user authenticates using one of the configured login options and may see a consent page listing the permissions Auth0 will give to the regular web application.

5 - Your Auth0 Authorization Server redirects the user back to the application with an authorization code, which is good for one use.

6 - Auth0's SDK sends this code to the Auth0 Authorization Server (/oauth/token endpoint) along with the application's Client ID and Client Secret.

7 - Your Auth0 Authorization Server verifies the code, Client ID, and Client Secret.

8 - Your Auth0 Authorization Server responds with an ID Token and Access Token (and optionally, a Refresh Token).

9 - Your application can use the Access Token to call an API to access information about the user.

10 - The API responds with requested data.

- What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

The PKCE-enhanced Authorization Code Flow introduces a secret created by the calling application that can be verified by the authorization server; this secret is called the Code Verifier. Additionally, the calling app creates a transform value of the Code Verifier called the Code Challenge and sends this value over HTTPS to retrieve an Authorization Code. This way, a malicious attacker can only intercept the Authorization Code, and they cannot exchange it for a token without the Code Verifier.

- What is Implicit Flow with Form Post?

Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls. With this method, you don’t need to obtain, maintain, use, and protect a secret in your application.

- What is Client Credentials Flow?

With machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user. For this scenario, typical authentication schemes like username + password or social logins don't make sense. Instead, M2M apps use the Client Credentials Flow (defined in OAuth 2.0 RFC 6749, section 4.4), in which they pass along their Client ID and Client Secret to authenticate themselves and get a token.


- What is Device Authorization Flow?

With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device. This avoids a poor user experience for devices that do not have an easy way to enter text. To do this, device apps use the Device Authorization Flow (ratified in OAuth 2.0), in which they pass along their Client ID to initiate the authorization process and get a token.

- What is Resource Owner Password Flow?

Though we do not recommend it, highly-trusted applications can use the Resource Owner Password Flow (defined in OAuth 2.0 RFC 6749, section 4.3), which requests that users provide credentials (username and password), typically using an interactive form. Because credentials are sent to the backend and can be stored for future use before being exchanged for an Access Token, it is imperative that the application is absolutely trusted with this information.

Even if this condition is met, the Resource Owner Password Flow should only be used when redirect-based flows (like the Authorization Code Flow) cannot be used.
