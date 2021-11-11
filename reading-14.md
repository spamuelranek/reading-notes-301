## How to be your authentic self

## What?

## how to be your authentic self... I looked in your notes, and it said Authentication

## And you thought that meant authentic self?

## What else could it mean?

## You are both right and wrong

# Authentication

## [What is Oauth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)
1. What is OAuth?
- OAuth is an authorization protocol or framework that allows for a single-sign on authentication that can be used by different and unrelated websites

2. Give an example of what using OAuth would look like.
- When you use your "sign in with google or facebook" to sign into a service

3. How does OAuth work? What are the steps that it takes to authenticate the user?
  1. The website the user is accessing connects to the website where the user already has authorization.
  2. The second site generates a one-time pass consisting of a token and a "secret?".
  3. The first website gives this to the user
  4. The user then passes this to the authorizing website
  5. The users/client is asked to approve of the authrization
  6. The user is then given an access token
  7. The user/client then gives the access token to the first/requesting website
  8. That website then passes the token back to the second/authorizing website
  9. The first website allows access to user via the second website
4. What is OpenID?
  1. Similiar to Oauth but it acted as a single log on that would manage request for authentification from sites. I has never grown to the size of Oauth and not has a companion called OpenID Connect that works with Oauth

## [Authiorization and Authenication flows](https://auth0.com/docs/authorization/flows)
1. What is the difference between authorization and authentication?
- Authentication is proving you are you. Authorization is saying you are you to another account

2. What is Authorization Code Flow?
- This is the flow described in the basic flow of Oauth
![Authorization Flow](https://images.ctfassets.net/cdy7uua7fh8z/3pstjSYx3YNSiJQnwKZvm5/33c941faf2e0c434a9ab1f0f3a06e13a/auth-sequence-auth-code-pkce.png)

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
- The same flow as before but with an additional system to mitigate the possibility of malicious actors gathering data. The Diagram show one additional step on the behalf of website.

4. What is Implicit Flow with Form Post?
- It has the user sign in to a third party which will send the first webside an ID token for proof of Authentication

5. What is Client Credentials Flow?
- This is used when it is a machine accessing via Auth0. The machine gets a one time access token from Auth0 and then provides this token to the endpoint to get data back

6. What is Device Authorization Flow?
- This is when you authorize a specific device to allow authO do beable to deliever access tokens to a specific device

7. What is Resource Owner Password Flow?
- For trusted sites can have users directly sign in to 0auth to have an access token generated.

[Return Home](README.md)
