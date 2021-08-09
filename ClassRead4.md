# Express REST API

## Review, Research, and Discussion


### Name 3 real world use cases where you’d want to change the request with custom middleware

>1. As name suggests it comes in middle of something and that is request and response cycle


>2. Middleware has access to request and response object


>3. Middleware has access to next function of request-response life cycle.

![](https://miro.medium.com/max/1400/1*wIkLR_9twvmG-LitHYoftw.png)

### True or false: The route handler is middleware?
> that is true.

### In what ways can a middleware function end the process and send data to the browser?
> Execute any code.
Make changes to the request and the response objects.
End the request-response cycle.
Call the next middleware in the stack.


![](https://expressjs.com/images/express-mw.png)


### At what point in the request lifecycle can you “inject” middleware?
> Express middleware are one-way handlers that mostly process requests and there is no first-class facility to handle responses. We would love to support Koa style middleware that use async/await to allow cascading behaviors.
Express middleware are added by the order of app.use() and it’s hard to contribute middleware from other modules.
Express does not allow dependency injection. We would like to enable injection of middleware configurations.


![](https://loopback.io/pages/en/lb4/imgs/middleware.png)

### What can cause express to error with “Request headers sent twice, cannot start a second response”
> it is happened when we use async in wrong way that cases the problem .



### Document the following Vocabulary Terms ?

* Middleware :
> Middleware functions are functions that have access to the request object ( req ), the response object ( res ), and the next middleware function in the application's request-response cycle. The next middleware function is commonly denoted by a variable named next .

* Request Object :
> The request object is the main entry point for an application to issue a request to the Library - all operations on a URL must use a Request object. The request object is application independent in that both servers and clients use the same Request class.

* Response Object :
> One of the most important objects in ASP is the Response object. It is the object which communicates between the server and the output which is sent to the client. ... DLL, parsing it so that instead of the client seeing <% Response.
.

* Application Middleware :
> Middleware in the context of distributed applications is software that provides services beyond those provided by the operating system to enable the various components of a distributed system to communicate and manage data. Middleware supports and simplifies complex distributed applications.

* Routing Middleware :
> Routing defines the way in which the client requests are handled by the application endpoints. And when you make some routers in separate file, you can use them by using middleware.
.


* Test Driven Development :
> Test-driven development (TDD) is a development technique where you must first write a test that fails before you write new functional code. TDD is being quickly adopted by agile software developers for development of application source code and is even being adopted by Agile DBAs for database development.


* Behavioral Testing :
> Specification-based testing technique is also known as 'black-box' or input/output driven testing techniques because they view the software as a black-box with inputs and outputs. The testers have no knowledge of how the system or component is structured inside the box.





[APIDOC](https://apidocjs.com/)

[Dev QA](https://devqa.io/difference-put-patch-requests/)

[Java Guides](https://www.javaguides.net/2018/07/difference-between-soap-vs-rest-web-services.html)


[stackoverflow](https://stackoverflow.com/questions/7042340/error-cant-set-headers-after-they-are-sent-to-the-client?rq=1)



**so the thing is what you abeal to do and achive to undersatnd your coworker team**




for more info please visit my github
[qusaiqeisi](https://github.com/qusaiqeisi)
 
 ***best regard*** 




