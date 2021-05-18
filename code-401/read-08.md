# Access Control (ACL)  

## Questions 

**When is Basic Authorization used vs. Bearer Authorization?**  
The Basic and Digest authentication schemes are dedicated to the authentication using a username and a secret.The Bearer authentication scheme is dedicated to the authentication using a token.  
**What does the JSON Web Token package do?**
It is a standard used to create access tokens for an application. It works this way: the server generates a token that certifies the user identity, and sends it to the client.  
**What considerations should we make when creating and storing a SECRET?**
- Use encryption to store secrets within .git repositories
- Use “Secrets as a service” solutions
- It should be stored securely
- It should be random, not guessable
- It should be a String
  
## Terms
**encryption**: It is the method by which information is converted into secret code that hides the information's true meaning.  
**token**: It is a piece of data that has no meaning or use on its own, but combined with the correct tokenization system, becomes a vital player in securing your application.  
**bearer**: authentication (also called token authentication) is an HTTP authentication scheme that involves security tokens called bearer tokens.  
**secret**:  a string that used to encrypt the token when we create it and identify it when its come back to our server. 
**JSON Web Token**: It is a standard used to create access tokens for an application.  

## Role-based access control (RBAC)
 It is a policy-neutral access-control mechanism defined around roles and privileges. The components of RBAC such as role-permissions, user-role and role-role relationships make it simple to perform user assignments. A study by NIST has demonstrated that RBAC addresses many needs of commercial and government organizations.[5] RBAC can be used to facilitate administration of security in large organizations with hundreds of users and thousands of permissions. Although RBAC is different from MAC and DAC access control frameworks, it can enforce these policies without any complication.