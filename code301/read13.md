## CRUD
1 - In your own words, describe what each group of status code represents:

- 100’s =  Continue informational status response code,also it indicates that everything so okay.
- 200’s =to tell the client that its request was accepted. 
- 300’s =  the request has more than one possible responses
- 400’s =its a client error codes,such as wrong URI, missing authentication.
- 500’s =its an error response code also this error means there is a problem on the server side



2 - What is a status code 202?

 its Created success status response code indicates that the request has succeeded and has led to the creation of a resource

3 - What is a status code 308?

 Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource

4 - What code would you use if an update didn’t return data to a client?

its Error 204 => no content

5 - What code would you use if a resource used to exist but no longer does?

 its Error 307 => Temporary Redirect



6 - What is the ‘Forbidden’ status code?

its pointed that the server understood the request but refuses to authorize it.