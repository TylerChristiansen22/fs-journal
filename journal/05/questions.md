# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > Create, Read, Update, and Delete

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > Post, Get, Put, Delete

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > Object-Relational Mapping. We use mongoose when interacting with MongoDB

04. Which two `HTTP` request types include a body?

  > Post and Put

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > Asynchronous, Synchronous

06. What are the three types of data relationships? Provide an example of each.

  > One to One, One to Many, and Many to Many. One to One would be something like Person and their SSN. One to many would be something like a planet and their moons, and many to many would be something like a student and classes. A student can take multiple classes and a class can have multiple students

07. What is middleware?

  > Middleware is something like Auth0, that communicates with both the Front and Back end

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > ?

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > BASEURL/api/seasons?tag=winter

10. What is a ***virtual property***?

  >A virtual property is found on the Model, it refrences parts of two seperate properties to then create a new property that we can populate / append to an object.
