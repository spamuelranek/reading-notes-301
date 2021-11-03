## API

## C

## ...what?

## You know A PEA I SEE?

## Why is learning such learning process with you

# [API BEST Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)
1. What does REST stand for?
- Representation State Transfer (REST)

2. REST APIs are designed around a ____.
- REST APIs are designed around resources

3. What is an identifer of a resource? Give an example.
- An identifier is a unique name on to the resource
``https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design``
- any of the strings between the `/` are an identifier

4. What are the most common HTTP verbs?
- GET
- POST
- DELETE
- PUT
- PATCH

5. What should the URIs be based on?
- URIS should be based around individual resources/ nouns

6. Give an example of a good URI.
- `http://everyoneiscool.com/list` as compared to `http://everyoneiscool.com/generate-list`

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
- Chatty refers to having may small requests to the api.
- This can be bad if it is happening to the point of becoming a load on the web server
- This can be avoided by sending over larger collections of data, but this needs to be balanced with not giving the user too much data

8. What status code does a successful GET request return?
- successful GET request returns status 200
9. What status code does an unsuccessful GET request return?
- unsuccessful GET request returns status 404(not found)

10. What status code does a successful POST request return?
- successful POST request returns 200 or 204(no content)

11. What status code does a successful DELETE request return?
- successful DELETE request returns 204(no content)

[Return Home](README.md)