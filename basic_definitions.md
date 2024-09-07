# Python Basics:

<p style="text-align: justify;">
<b>Python is a high-level, interpreted programming language</b> that is known for its simplicity and readability. It is
widely used in various fields, including web development, data science, machine learning, and more. Some basic
concepts of Python include variables, data types, loops, conditionals, functions, and modules.
</p>

----

>### Interpreter vs Compiler:

<p style="text-align: justify;">
<b>An interpreter</b> _is a program_ that directly executes source code written in a programming language, line by line.
Python is an interpreted language, which means that the Python interpreter executes the code directly, without the
need for a compilation step.
</p>

<p style="text-align: justify;">
<b>A compiler</b> _is a program_ that translates source code into machine code that can be executed directly by the computer's
processor. Compiled languages like C and C++ require a compilation step before the code can be executed.
</p>

---
>**Abstraction** 
<p style="text-align: justify;">
In Python refers to the process of hiding complex implementation details from the user and exposing only
the essential features of a program. Abstraction can be achieved in Python through the use of classes, objects, and methods.
In object-oriented programming, abstraction is implemented through the use of classes and objects. A class is a blueprint
for creating objects, while an object is an instance of a class. By defining classes and objects, programmers can create
abstractions that hide the details of how a program works and instead provide a simplified interface for users to
interact with.
</p>

---

>**Methods** 
<p style="text-align: justify;">
are functions that are defined inside a class and are used to perform specific actions on objects.
By defining methods, programmers can further abstract away the details of how a program works and instead provide a
simple interface for users to interact with.
</p>

<p style="text-align: justify;">
For example, consider a program that models a car. The car might have various properties, such as its make, model,
and year, as well as various methods, such as start, stop, and accelerate. By defining a Car class with these properties
and methods, programmers can create an abstraction of a car that hides the details of how the car works and instead
provides a simple interface for users to interact with.
</p>

---

>**Operators**:
<p style="text-align: justify;">
In Python, operators are used to perform various operations on data. Some common operators include arithmetic
operators (+, -, *, /), assignment operators (=), comparison operators (==, !=, >, <, >=, <=), logical operators
(and, or, not), and bitwise operators (&, |, ^, ~, <<, >>).
</p>

>**Relational Operators:**
<p style="text-align: justify;">
Relational operators are used to compare two values and determine their relationship. In Python, some common relational
operators include:

| **Operator** |      **Does what?**      |
|:------------:|:------------------------:|
|      ==      |         equal to         |
|      !=      |       not equal to       |
|       >      |       greater than       |
|       <      |         less than        |
|      >=      | greater than or equal to |
|      <=      |   less than or eqyal to  |
</p>

>**Compounding operators**
<p style="text-align: justify;">
These operators can be used in various ways to compare values and make decisions in Python programs.
Python compound operators are shorthand notations used to perform an operation and assignment at the same time.
They combine an arithmetic, bitwise, or logical operator with the assignment operator.
</p>

| **Operator** | **Does what?** | **expression** | **equivalent** |
|:------------:|:--------------:|----------------|----------------|
|      +=      |   increments   |     x += 1     |    x = x + 1   |
|      -=      |   decrements   |     x -= 1     |    x = x -1    |
|      *=      |   multiplies   |     x *= 1     |    x = x * 1   |
|      /=      |     divides    |     x /= 1     |    x = x / 1   |
|      %=      |     modulus    |     x %= 1     |    x = x % 1   |
|      **=     |      power     |     x **= 1    |    x = x**1    |
|      //=     |   integer div  |     x //= 1    |   x = x // 1   |

**Note:** Using compound operators can make your code more concise and efficient, as it combines two operations into one.

---

>**Variable**
<p style="text-align: justify;">
In Python, a variable is a named reference to a value that is stored in memory. Variables are used to store data that
can be used later in a program. To create a variable in Python, we use the assignment operator (=). The syntax for
creating a variable is as follows:


`variable_name = value `
      
Here, variable_name is the name of the variable and value is the value that we want to store in the variable.


**Examples**:

* Creating a variable to store an integer value

      x = 10

* Creating a variable to store a float value

      y = 3.14

* Creating a variable to store a string value

      name = "John"

* Creating a variable to store a boolean value

      is_true = True

<p style="text-align: justify;">
<b>Note</b>: In Python, variables can be of any data type, such as integers, floats, strings, booleans, lists, tuples,
and dictionaries. We can also change the value of a variable at any point in the program by assigning a new value to it.
</p>

**Examples**:
* Changing the value of a variable

      x = 20
      print(x) # Output: 20

* Assigning a new value to a variable

      name = "Jane"
      print(name) # Output: "Jane"

<p style="text-align: justify;">
<b>Note</b>: It is important to note that Python is a dynamically typed language, which means that the data type of a 
variable is determined at runtime based on the value that it holds. This allows for greater flexibility and ease of use, 
but it also requires more careful attention to data types when writing code.
</p>

---

>**Conditional statements:**
<p style="text-align: justify;">
Conditional statements are used to execute a block of code only if a certain condition is met. In Python, we use the
"if", "elif", and "else" keywords to create conditional statements.
<p>

For example:

      x = 10
      if x > 5:
         print("x is greater than 5")
      elif x < 5:
         print("x is less than 5")
      else:
         print("x is equal to 5")

---

>**Control Flow**
<p style="text-align: justify;">
Control flow in programming refers to the order in which statements are executed. It allows you to control the execution
of your program based on certain conditions or criteria. In Python, control flow is achieved through the use of conditional
statements and loops.
</p>

**Loops:**
<p style="text-align: justify;">
Loops are used to execute a block of code repeatedly until a certain condition is met. In Python, we use the "for" and
"while" loops to create loops.
</p>

**For example:**

* **for loop**

      for i in range(1, 6):
         print(i)

* **while loop**

      x = 1
      while x <= 5:
         print(x)
         x += 1

**Break and continue statements:**
<p style="text-align: justify;">
The <b>break</b> statement is used to exit a loop prematurely if a certain condition is met, while the <b>continue</b> 
statement is used to skip a particular iteration of a loop and move on to the next iteration.
</p>

For example:

* **break statement**

      for i in range(1, 6):
         if i == 3:
            break
         print(i)

* **continue statement**

      for i in range(1, 6):
         if i == 3:
            continue
         print(i)

<p style="text-align: justify;">
Control flow is an essential aspect of programming, as it allows you to create more dynamic and flexible programs that
can respond to different conditions and inputs.
</p>