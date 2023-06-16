# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | var, let, const |

02. What is the definition of a function?

    > | reusable code which can be called anywhere in your program.  |

03. What are the `SOLID` principles?

    > | it references object oriented programing, the serve as a set of rules for best practices to follow: 
-The Single Responsibility Principle
-The Open-Closed Principle
-The Liskov Substitution Principle
-The Interface Segregation Principle
-The Dependency Inversion Principle|

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | let removedFruit = fruit.splice(2,1); |

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > | you.friends.push(them);
        them.friends.push(you);  |

06. Give an example of a JavaScript `Conditional`:

    > | var person = { age: 33 };
        if (person.age >= 18) {
        console.log ("Adult"); |
        }
07. What is the main difference between `parameters` and `arguments`?

    > | The values that are declared within a function when the function is called are known as an argument. Whereas, the variables that are defined when the function is declared are known as a parameter. |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | code small, test small|

09. What is the difference between a `primitive` value and a `reference` value?

    > | reference is pointing to a shallow copy|

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | for (let num = -100; num <= 100; num++) {
    console.log(num);
} |
