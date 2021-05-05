# Express REST API

**Name 3 real world use cases where you’d want to change the request with custom middleware?**  
1. adding current server time to the request
2. override the post method to put or delete
3. encrypt secure data  

**True or false: The route handler is middleware?**  
If the router handler has 'next' argument it's considered as middleware, otherwise it's just a route handler. 

**In what ways can a middleware function end the process and send data to the browser?**  
1. By calling "next" using parameter
2. by Throwing an error  

**At what point in the request lifecycle can you “inject” middleware?**  
You can inject many middleware as you want as long as you don't reach the route handler.  

**What can cause express to error with “Request headers sent twice, cannot start a second response”**  
when trying to send a header after some of the body has already been written. For example, callbacks that are accidentally called twice.  

**Middleware:** function that executes during the lifecycle of a request to the Express server,and has access to the HTTP request and response for each route (or path) it’s attached to.  
**Request Object:** is one half of the request and response cycle to examine calls from the client side, make HTTP requests, and handle incoming data whether in a string or JSON object.   
**Response Object:**  is one half of the request and response cycle to send data from the server to the client-side through HTTP requests.  
**Application Middleware:**  a middleware that bound to an instance of express, using app.use() and app.VERB()  
**Routing Middleware:** a middleware that bound to an instance of express.Router().  
**Test Driven Development:**  is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases. 
**Behavioral Testing:** is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing.

**Which 3 things had you heard about previously and now have better clarity on?** 
1. routing handler
2. middleware
3. request and response objects  

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**  
1. behavioral testing
2. TDD- CI/CD
3. modeling 

**What are you most excited about trying to implement or see how it works?**  
testing units for REST API server 