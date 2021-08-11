# Data Modeling .
> Data modeling is the process of creating a visual representation of either a whole information system or parts of it to communicate connections between data points and structures. ... This provides a common, consistent, and predictable way of defining and managing data resources across an organization, or even beyond

## Name 3 advantages to Test Driven Development ?
>1. Writing the tests first requires you to really consider what do you want from the code.

> 2. Bugs are reduced.

>3. The programmer’s productivity is increased.

## In what case would you need to use beforeEach() or afterEach() in a test suite?

> The difference is beforeEach()/afterEach() automatically run before and after each tests, which 1. removes the explicit calls from the tests themselves, and 2. invites inexperienced users to share state between tests.
> beforeEach(): If the function returns a promise, Jest waits for that promise to resolve before running the test. This is often useful if you want to reset some global state that will be used by many tests.

> afterEach():
Runs a function after each one of the tests in this file completes. If the function returns a promise or is a generator, Jest waits for that promise to resolve before continuing.

![](https://miro.medium.com/max/602/0*1tcmCgrMAoZtwjUh)



## What is one downside of Test Driven Development ?
> Probably, the strongest argument against TDD is that the tests need to be maintained because the code has got to. Whenever requirements change, you would like to vary the code and tests. ... So, actually, this disadvantage is that the same as before when writing code that apparently takes an extended time.


## What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?

- Classes :
> 
ES6 Classes formalize the common JavaScript pattern of simulating class-like inheritance hierarchies using functions and prototypes. ... Classes (as shipped in Chrome) support prototype-based inheritance, constructors, super calls, instance and static methods.

![](https://miro.medium.com/max/700/1*yiS2QvVKIpYCb0fqvrsXZQ.png)

- Constructor:
>The constructor method is a special method for creating and initializing an object created with a class. There can only be one special method with the name "constructor" in a class. A SyntaxError will be thrown if the class contains more than one occurrence of a constructor method.
A constructor can use the super keyword to call the constructor of the super class.

![](https://i.stack.imgur.com/cEbBB.png)

- Prototype :
> Advertisements. The prototype property allows you to add properties and methods to any object (Number, Boolean, String and Date, etc.). Note − Prototype is a global property which is available with almost all the objects.
ES6 prototype methods can be inherited by children classes to simulate an object oriented behaviour in JavaScript but under the hood, the inheritance feature is simply a function of the existing prototype .

![](https://i.stack.imgur.com/4pCXC.png)

## Why REST?
- REST :
> REST stands for representational state transfer and was created by computer scientist Roy Fielding. An API is a set of definitions and protocols for building and integrating application software. ... You can think of an API as a mediator between the users or clients and the resources or web services they want to get.One of the key advantages of REST APIs is that they provide a great deal of flexibility. Data is not tied to resources or methods, so REST can handle multiple types of calls, return different data formats and even change structurally with the correct implementation of hypermedia .

![](https://miro.medium.com/max/1400/0*WQZTR7gIwhiIIbnh.png)


## Document the following Vocabulary Terms

1. functional programming :
> In computer science, functional programming is a programming paradigm where programs are constructed by applying and composing functions. ... When a pure function is called with some given arguments, it will always return the same result, and cannot be affected by any mutable state or other side effects

2. object-oriented programming (OOP)
> 
Object-oriented programming is based on the concept of objects. In object-oriented programming data structures, or objects are defined, each with its own properties or attributes. Each object can also contain its own procedures or methods. Software is designed by using objects that interact with one another.

3. class :
> Classes are a template for creating objects. They encapsulate data with code to work on that data. Classes in JS are built on prototypes but also have some syntax and semantics that are not shared with ES5 class-like semantics.

4. super :
> Definition and Usage. The super keyword refers to the parent class. It is used to call the constructor of the parent class and to access the parent's properties and methods .

5. this :
> The JavaScript this keyword refers to the object it belongs to. ... Alone, this refers to the global object. In a function, this refers to the global object. In a function, in strict mode, this is undefined . In an event, this refers to the element that received the event.

6. Test Driven Development (TDD)
> In layman's terms, Test Driven Development (TDD) is a software development practice that focuses on creating unit test cases before developing the actual code. It is an iterative approach that combines programming, the creation of unit tests, and refactoring

7. Jest :
> Jest is a JavaScript testing framework maintained by Facebook, Inc. designed and built by Christoph Nakazawa with a focus on simplicity and support for large web applications. It works with projects using Babel, TypeScript, Node.js, React, Angular, Vue.js and Svelte

8. Continuous Integration (CI)
> CI stands for continuous integration, a fundamental DevOps best practice where developers frequently merge code changes into a central repository where automated builds and tests run. But CD can either mean continuous delivery or continuous deployment.

9. REST :
> 
A REST API (also known as RESTful API) is an application programming interface (API or web API) that conforms to the constraints of REST architectural style and allows for interaction with RESTful web services. REST stands for representational state transfer and was created by computer scientist Roy Fielding.

10. Data Model :
> A data model (or datamodel) is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities. ... So the "data model" of a banking application may be defined using the entity-relationship "data model"






[APIDOC](https://apidocjs.com/)

[Dev QA](https://devqa.io/difference-put-patch-requests/)

[Java Guides](https://www.javaguides.net/2018/07/difference-between-soap-vs-rest-web-services.html)


[stackoverflow](https://stackoverflow.com/questions/7042340/error-cant-set-headers-after-they-are-sent-to-the-client?rq=1)



**so the thing is what you abeal to do and achive to undersatnd your coworker team**




for more info please visit my github
[qusaiqeisi](https://github.com/qusaiqeisi)
 
 ***best regard*** 
