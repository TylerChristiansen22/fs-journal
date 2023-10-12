# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > To Organize classes and have better intelisense

02. What is the difference between a `class` and an `interface`?

  > A class can be instantiated (objects of a class can be created.) An Interface cannot be instantiated (objects cannot be created)

03. What is the method that returns an instance of a class, yet it has no return type?

  > void

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

  > Public 

06. In the Car example what is `string` an indication of?

  > the return type

07. In the Car example what is `abstract` preventing?

  > ?

08. In a SQL table, what is the difference between information in a row and information in a column?

  > a row contains information about one single object while a column contains information across objects about one property

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > CREATE TABLE
    IF NOT EXISTS characters(
        id INT AUTO_INCREMENT NOT NULL PRIMARY KEY,
        name varchar(500) NOT NULL,
>       age varchar(500) NOT NULL,
>       description(1000) NOT NULL,
    ) default charset utf8 COMMENT '';

10. In SQL how can you query more than a single table? Provide an example.

  > You can query more than one table by aliasing the tables out ande JOINing them. The below example is from PostIt-Sharp
> SELECT alb.*, act.*
FROM albums alb
    JOIN accounts act ON act.id = alb.creatorId;

