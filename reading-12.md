## CR-

## Hmmm..you say something?

## No

## It sure sounded like you did

# CRUD
## CREAT,READ, UPDATE, and DELETE

## [Status Codes Based on REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
1. In your own words, describe what each group of status code represents:
- 100’s = Header was recieved but either a different protocol is needed or the body is not going make it back in the response

- 200’s = Successin the facts that it fit the "lock"

- 300’s = Redirection. Something has changed at that thing is no longer here

- 400’s = client problem. They did not have the right key to "fit" the lock

- 500’s = server problem. Something on the back end is not working as it should
2. What is a status code 202?
- Status code 202 is accepted. It has made the pinky promise to do the things the url asked of it.

3. What is a status code 308?
- Permanent Redirect: askjeeves.com => ask.com

4. What code would you use if an update didn’t return data to a client?
- Status 204 No Content

5. What code would you use if a resource used to exist but no longer does?
- 410 Gone / 404 not found. Gone means we know and want you to know. 404 could be they know and dont what you to know.

6. What is the ‘Forbidden’ status code?
- Status 403 is the **FORBIDDEN**

## [REST API WITH NODE.JS, EXPRESS, AND MONGODB](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)
1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
- We want to protect our database string because it has sensitive information. Its why we have .env on the gitignore

2. What is middleware?
- It is the code in the "middle" between the request and before it is past to the route.

3. What does app.use(express.json()) do?
- Allows the server to accept JSON as a body instead of a post

4. What does the /:id mean in a route?
- Acts a a parameter and will get a specific piece of data.

5. What is the difference beween PUT and PATCH?
- PATCH only updates based on the information passed to it. PUT would add an entire model not just part.

6. How do you make a defalut value in a schema?
- use the key of deafualt in the Schema

7. What does a 500 error status code mean?
- Server Error

8. What is the difference between a status 200 and a status 201?
- 200 is a basic status saying things are OK - 201 means something was created with this route

[Return Home](README.md)
