# Write the following steps in the correct order:

Register your application to get a client_id and client_secret
Ask the client if they want to sign in via a third party
Redirect to a third party authentication endpoint
Make a request to the third-party API endpoint
Receive authorization code
Make a request to the access token endpoint
Receive access token


What can you do with an authorization code?

decoding the code and dealing with the data and comparing it with my db 

What can you do with an access token?

samething but the token will be specific

What’s a benefit of using OAuth instead of your own basic authentication?
to more secure and protect app from hacker 

Client ID :- A unique identification number used when sending data to a specific client. Clients that are standardized for use in generic applications are allocated standard client IDs (listed in this standard)..

Client Secret :- is a secret used by the OAuth Client to Authenticate to the Authorization Server. The Client Secret is a secret known only to the OAuth Client and the Authorization Server.

Endpoint authentication  : - is an authentication mechanism used to verify the identity of a network's external or remote connecting device.

A token endpoint :-  is an HTTP endpoint that micropub clients can use to obtain an access token given an authorization code.

API Endpoint :-is one end of a communication channel. When an API interacts with another system, the touchpoints of this communication are considered endpoints. 

Authorization Code :- is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space.

access token  :- contains the security credentials for a login session and identifies the user, the user's groups, the user's privileges, and, in some cases, a particular application. Typically one may be asked to enter the access token .

# JWT
JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed.

# JWT INTRO
JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

#jwt secure
WTs can be either signed, encrypted or both. If a token is signed, but not encrypted, everyone can read its contents, but when you don't know the private key, you can't change it. Otherwise, the receiver will notice that the signature won't match anymore.

Answer to your comment: I'm not sure if I understand your comment the right way. Just to be sure: do you know and understand digital signatures? I'll just briefly explain one variant (HMAC, which is symmetrical, but there are many others).

Let's assume Alice wants to send a JWT to Bob. They both know some shared secret. Mallory doesn't know that secret, but wants to interfere and change the JWT. To prevent that, Alice calculates Hash(payload + secret) and appends this as signature.

