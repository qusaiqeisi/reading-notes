# Authorization/Authentication :
![](https://s3.ap-south-1.amazonaws.com/afteracademy-server-uploads/authentication-vs-authorization-diff-a7acc34e88679381.png)

## Review, Research, and Discussion

1. What header(s) are used in authentication and authorization
> The WWW-Authenticate and Proxy-Authenticate response headers define the authentication method that should be used to gain access to a resource. They must specify which authentication scheme is used, so that the client that wishes to authorize knows how to provide the credentials.

> The HTTP Authorization request header contains the credentials to authenticate a user agent with a server, usually, but not necessarily, after the server has responded with a 401 Unauthorized status and the WWW-Authenticate header.

![](https://assets.postman.com/postman-docs/basic-autogenerated-header.jpg)


2. What is safe to put into a JWT
>* Registered claims like sub, iss, exp or nbf

>* Public claims with public names or names registered by IANA which contain values that should be unique like email, address or phone_number. See full list

>* Private claims to use in your own context and values can collision .

![](https://www.appknox.com/hs-fs/hubfs/JWT.jpg?width=1999&name=JWT.jpg)


3. How are JWTs validated
> Check signature. The last segment of a JWT is the signature, which is used to verify that the token was signed by the sender and not altered in any way. The Signature is created using the Header and Payload segments, a signing algorithm, and a secret or public key (depending on the chosen signing algorithm).

![](https://miro.medium.com/max/700/1*u82FodMDIigzaLa2HPgFmQ.png).


## Document the following Vocabulary Terms

* RBAC : Role-based access control (RBAC) is a method of restricting network access based on the roles of individual users within an enterprise.

* User Roles: are permission sets that control access to areas and features within the Professional Archive Platform.

* JWT Token : JSON Web Token (JWT) access tokens conform to the JWT standard and contain information about an entity in the form of claims. They are self-contained therefore it is not necessary for the recipient to call a server to validate the token.



**A role can have many permissions.**


**A permission can be assigned to many roles.**


[APIDOC](https://apidocjs.com/)

[Dev QA](https://devqa.io/difference-put-patch-requests/)

[Javas Guides](https://www.javaguides.net/2018/07/difference-between-soap-vs-rest-web-services.html)


[stackoverflow](https://stackoverflow.com/questions/7042340/error-cant-set-headers-after-they-are-sent-to-the-client?rq=1)



**so the thing is what you abeal to do and achive to undersatnd your coworker team**




for more info please visit my github
[qusaiqeisi](https://github.com/qusaiqeisi)
 
 ***best regard*** 