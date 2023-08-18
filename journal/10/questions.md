# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > | To organize code into logical groups and to prevent name collisions that can occur especially when your code base includes multiple libraries |

02. What is the difference between a `class` and an `interface`?

  > | A class is a blueprint from which we can create objects that share the same configuration - properties and methods. An interface is a group of related properties and methods that describe an object, but neither provides implementation nor initialisation for them. |

03. What is the method that returns an instance of a class, yet it has no return type?

  > | Constructor |

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > | Public |

06. In the Car example what is `string` an indication of?

  > | Return Type |

07. In the Car example what is `abstract` preventing?

  > | Instantiation of the Car class. |

08. In a SQL table, what is the difference between information in a row and information in a column?

  > | Information in a row represents a specific record or instance, while information in a column represents a specific attribute or property. |

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > | CREATE TABLE characters (
      id INT PRIMARY KEY,
      name VARCHAR(255),
      age VARCHAR(50),
      description VARCHAR(500)
      ); |

10. In SQL how can you query more than a single table? Provide an example.

  > | You can query more than a single table using SQL JOIN operations. 
    SELECT
    orders.order_id,
    customers.customer_name
    FROM
    orders
    INNER JOIN
    customers ON orders.customer_id = customers.customer_id;

   |
