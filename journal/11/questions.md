# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > | Enables you to create new classes that reuse, extend, and modify the behavior defined in other classes.  |

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > | The derived class inherits all the members(fields, methods) of the base class, |

3. How does ***accessibility*** affect inheritance?

  > | Private members are visible only in derived classes that are nested in their base class. |

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > | A primary key is a unique identifier for each record in a table. A foreign key establishes a relationship between tables by referencing the primary key of another table. |

5. What is an ***alias***?

  > | Allowing an existing type to go by a different name. |

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > | SELECT p.*
FROM patients p
JOIN patient_doctors pd ON p.id = pd.patientId
JOIN doctors d ON pd.doctorId = d.id
WHERE d.id = <doctor_id>;
 |
