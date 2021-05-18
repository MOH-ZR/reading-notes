# Bearer Authorization

## Questions  
**Write the following steps in the correct order:**
1. Ask the client if they want to sign in via a third party
2. Request a third-party API endpoint
3. Redirect to a third party authentication endpoint
4. Register your application to get a client_id and client_secret
5. Receive authorization code
6. Receive access token
7. Request the access token endpoint

**What can you do with an authorization code?**  
The only thing you can do with the authorization code is to make a request to get an access token.
**What can you do with an access token?**  
Access tokens are the thing that applications use to make API requests on behalf of a user. The access token represents the authorization of a specific application to access specific parts of a user’s data.
**What’s a benefit of using OAuth instead of your own basic authentication?** 
it is safer than basic auth.

## Terms  
**Client ID**:  The client_id is a public identifier for apps. Even though it’s public, it’s best that it isn’t guessable by third parties, so many implementations use something like a 32-character hex string. It must also be unique across all clients that the authorization server handles. If the client ID is guessable, it makes it slightly easier to craft phishing attacks against arbitrary applications.  
**Client Secret**:The client_secret is a secret known only to the application and the authorization server. It must be sufficiently random to not be guessable, which means you should avoid using common UUID libraries which often take into account the timestamp or MAC address of the server generating it.  
**Authentication Endpoint**: It is a security mechanism designed to ensure that only authorized devices can connect to a given network, site or service.  
**Access Token Endpoint**: The token endpoint is where apps make a request to get an access token for a user. 
**API Endpoint**: It is a point at which an application program interface (API) -- the code that allows two software programs to communicate with each other -- connects with the software program.  
**Authorization Code**:  It is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space.  
**Access Token**: It is an object encapsulating the security identity of a process or thread. A token is used to make security decisions and to store tamper-proof information about some system entity.  

## JWT (JSON Web Token)  
JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.  

