# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > let, const, var

02. What is the definition of a function?

    > a set of statements that performs a task

03. What are the `SOLID` principles?

    > 1. The Single Responsibility Principle
    2. The Open-Closed Principle
    3. The Liskov Substitution Principle
    4. The Interface Segregation Principle
    5. The Dependency Inversion Principle

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > fruit.splice(2,1)

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

    > you.push(them.name) 
    them.push(you.name)

06. Give an example of a JavaScript `Conditional`:

    > if, else if, and else are all conditionals found in JavaScript

07. What is the main difference between `parameters` and `arguments`?

    > Parameters are the number of variables in a function, while arguments are the values that is read by the function

08. Instead of writing everything to the console, what is a better way to debug your code?

    > by using the debugger tool

09. What is the difference between a `primitive` value and a `reference` value?

    > I do not know, I can tell you if something is a primitive or reference value, but I don't know the difference between the two. 

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for (let i = -100; i >= 100; i++){
        console.log(i)
    }
