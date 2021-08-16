# Access Control (ACL)
![](https://miro.medium.com/max/700/0*1NYLRuQasMhwDr0n.jpg)

# Review, Research, and Discussion

**When is Basic Authorization used vs. Bearer Authorization?**

- basic authorization used when in sign-in process, after signing-up.
- bearer authorization used after basic auth done. for every request will use a bearer auth to verfiy if token match user token or not.

**What does the JSON Web Token package do?**

- generates a token that we can use with authorization and information exchange.

![](https://miro.medium.com/max/1200/1*tW-8Y2edq04b4__zF0Jm9Q.png)

**What considerations should we make when creating and storing a SECRET?**

- don't create a weak secret.
- don't store it in a plain text.
- don't share your secret with anyone.
- make a rotation for your secret.
- don't use same secret for different accounts.

![](https://www.ekransystem.com/sites/default/files/secrets_management/figure-3.png)

# Document the following Vocabulary Terms

**encryption:** it is a process that convert our passwords to hashed ones, with characters representation. to make our passwords secured. we use the bcrybt library to do this.

**token:** it an encoded json, that we use in beare authorization to ensure if the user is authorized or not.

**bearer:** it is an authorization process, that use the header, and create and compare the token for the users, to allow them to reach a certain endpionts or not.

**secret:** it is a signiture for the developper that make his token secure and no one can access his data when his secret is exists.

**JSON Web Token:** it is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

# Preparation Materials

# RBAC tutorial

- role based access control : that is means every user should has a type of role, and based on this role type will be able to access certain files or resources or do some actions.

- this RBAC come after ensuring this user authorized or not; if yes, then check if he has a role, then will access certain files, but if he hasn't, then he can't access anything even though he is an authorized user.

![](https://docs.oracle.com/cd/E39820_01/doc.11121/gateway_docs/content/images/rbac/rbac_overview.png)

# 5 steps to RBAC

- RBAC is important to make our system more secure, espicaliy if one of the users has been hacked, then our system will still safe, becuase the user has a limitted access to our application.

- Access control lists (ACL) : it is a process that specify a user or gruop of users to access certain object or data.

- Attribute-based access control (ABAC): or policy-based access control, here you can use many attributes to determine who can access the data like; location, time, user department, ..etc. this make the system more secure also.

- steps to implement RBAC :

1. Inventory your systems: by definig your data and sort them, what should be accessd and who can access them.

2. Analyze your workforce and create roles: define your role types.

3. Assign people to roles.

4. Never make one-off changes

5. Audit: every period of time check the users and their roles, check your accessable data, change or remove or update unnecessary users or change their roles.

![](https://docs.confluent.io/platform/current/_images/rbac-overview.png)


# wiki - RBAC

- When defining an RBAC model, the following conventions are useful:

- S = Subject = A person or automated agent
- R = Role = Job function or title which defines an authority level
- P = Permissions = An approval of a mode of access to a resource
- SE = Session = A mapping involving S, R and/or P
- SA = Subject Assignment
- PA = Permission Assignment
- RH = Partially ordered Role Hierarchy. RH can also be written: ≥ (The notation: x ≥ y means that x inherits the permissions of y.)



**A subject can have multiple roles.**


**A role can have multiple subjects.**


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