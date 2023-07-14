# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > | CREATE, READ, UPDATE and DELETE |

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > | Create = PUT with a new URI
        POST to a base URI returning a newly created URI
      Read   = GET
      Update = PUT with an existing URI
      Delete = DELETE |

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > | Object-relational mapping |

04. Which two `HTTP` request types include a body?

  > | PUT and POST |

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > | asynchronous model |

06. What are the three types of data relationships? Provide an example of each.

  > | One-to-One Relationship: Each person can have only one corresponding address, and each address belongs to only one person.
      One-to-Many Relationship: A department can have multiple employees, but each employee can belong to only one department.
      Many-to-Many Relationship: student can enroll in multiple courses, and each course can have multiple students. |

07. What is middleware?

  > | Middleware is software that acts as a bridge between different applications, systems, or layers of an application stack, facilitating communication, data processing, and integration. |

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > | The client-to-server pipeline delivers information from the client, while the server-to-client pipeline returns it. |

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > | http://example.com/path?tag=winter
 |

10. What is a ***virtual property***?

  > | A property that does not directly correspond to a field or attribute stored in the underlying data structure or database. Instead, a virtual property is dynamically computed or derived based on other properties or logic defined within the program. It provides a way to access or manipulate data that is not explicitly stored but can be generated or calculated on the fly when needed. |
