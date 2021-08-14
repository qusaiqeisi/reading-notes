# Authentication

## Explain what a “Singleton” is (in Computer Science terms)


> A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance. It contains static variables that can accommodate unique and private instances of itself. ... The singleton pattern is used in programming languages such as Java and JS

![](https://media.geeksforgeeks.org/wp-content/uploads/SINGLEton.png)

## Explain how the Singleton pattern can be used with Node modules, specifically with classes
>* Caching
Modules are cached after the first time they are loaded. This means (among other things) that every call to require('foo') will get exactly the same object returned, if it would resolve to the same file.Multiple calls to require('foo') may not cause the module code to be executed multiple times. This is an important feature. With it, "partially done" objects can be returned, thus allowing transitive dependencies to be loaded even when they would cause cycles.If you want to have a module execute code multiple times, then export a function, and call that function.

>* Module Caching Caveats
Modules are cached based on their resolved filename. Since modules may resolve to a different filename based on the location of the calling module (loading from node_modules folders), it is not a guarantee that require('foo') will always return the exact same object, if it would resolve to different files.Additionally, on case-insensitive file systems or operating systems, different resolved filenames can point to the same file, but the cache will still treat them as different modules and will reload the file multiple times. For example, require('./foo') and require('./FOO') return two different objects, irrespective of whether or not ./foo and ./FOO are the same file

![](https://res.cloudinary.com/practicaldev/image/fetch/s--0sNCbGQe--/c_imagga_scale,f_auto,fl_progressive,h_720,q_auto,w_1280/https://cl.ly/cc61c62f0938/download/Image%25202018-12-05%2520at%252011.41.22%2520AM.png)


## If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?
> Bind application-level middleware to an instance of the app object by using the app.use() and app.METHOD() functions, where METHOD is the http/https method of the request that the middleware function handles such as GET, PUT, or POST in lowercase
![](https://miro.medium.com/max/1400/1*fbe04fcynkBuLo_CADxxHQ.png)


## Document the following Vocabulary Terms

1. Router Middleware:
> The term is composed of 2 words router and middleware. Middleware. It is a piece of code that comes in the middle of request and response . It kind of hijacks your request so that you can do anything that you want with your request or response eg: Modify the data or call the next middleware.

2. Dynamic Module Loading
> Dynamic loading is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.

3. Singleton Pattern
> In software engineering, the singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton

4. CRUD -> REST Method Matches
> Create, Read, Update, and Delete 

5. Mock Testing
> Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones. ... Such a service can be replaced with a mock object


[APIDOC](https://apidocjs.com/)

[Dev QA](https://devqa.io/difference-put-patch-requests/)

[Javas Guides](https://www.javaguides.net/2018/07/difference-between-soap-vs-rest-web-services.html)


[stackoverflow](https://stackoverflow.com/questions/7042340/error-cant-set-headers-after-they-are-sent-to-the-client?rq=1)



**so the thing is what you abeal to do and achive to undersatnd your coworker team**




for more info please visit my github
[qusaiqeisi](https://github.com/qusaiqeisi)
 
 ***best regard*** 
