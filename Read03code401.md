3 cases
1-Authentication
2-Data management
3-Error handling

True or false: The route handler is middleware?
False, the route handler not midlleware when it  without next() 

To End Req-Res Cycle
it must call next() to pass control to the next middleware.

At what point in the request lifecycle can you “inject” middleware?
Btw The Req and Res

What can cause express to error with “Request headers sent twice, cannot start a second response”
The error "Error: Can't set headers after they are sent." means that you're already in the Body or Finished state,
but some function tried to set a header or statusCode. When you see this error, try to look for anything that tries to send a header after some of the body has already been written.

### Middleware :- is a software that acts as an intermediary between two applications or services to facilitate their communication.

### Request Object :- object represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers, and so on.

### Response Object :- object represents the HTTP response that an Express app sends when it gets an HTTP request.

### Application Middleware :- application that apllaying middleware

### Routing Middleware :- Route that apllaying midlleware

### TDD :-Test-driven development (TDD) is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases. 

### BDD :-Behavioral Driven Development (BDD) is a software development approach that has evolved from TDD (Test Driven Development). It differs by being written in a shared language, which improves communication between tech and non-tech teams and stakeholders (Btw owner and technical)
