## Python OOP Assignment
Q1. What is the purpose of Python&#39;s OOP?
In Python, object-oriented Programming (OOPs) is a programming paradigm that uses objects and classes in programming. It aims to implement real-world entities like inheritance, polymorphisms, encapsulation, etc. in the programming

Q2. Where does an inheritance search look for an attribute?
An inheritance search looks for an attribute first in the instance object, then in the class the instance was created from, then in all higher superclasses, progressing from left to right (by default). The search stops at the first place the attribute is found

Q3. How do you distinguish between a class object and an instance object?
Class variables are declared inside a class but outside of any function. Instance variables are declared inside the constructor which is the __init__method

Q4. What makes the first argument in a class’s method function special?
This is the reason the first parameter of a function in class must be the object itself. Writing this parameter as self is merely a convention. It is not a keyword and has no special meaning in Python

Q5. What is the purpose of the __init__ method?
The __init__ method lets the class initialize the object's attributes and serves no other purpose. It is only used within classes

Q6. What is the process for creating a class instance?
To create instances of a class, you call the class using class name and pass in whatever arguments its __init__ method accepts

Q7. What is the process for creating a class?
Create a Class. To create a class, use the keyword class

Q8. How would you define the superclasses of a class?
The class from which a class inherits is called the parent or superclass. A class which inherits from a superclass is called a subclass, also called heir class or child class. Superclasses are sometimes called ancestors as well

Q9. What is the relationship between classes and modules?
Modules are collections of methods and constants. They cannot generate instances. Classes may generate instances (objects), and have per-instance state (instance variables)

Q10. How do you make instances and classes?
- To create a class, use the keyword class
- When you create an object, you are creating an instance of a class, therefore "instantiating" a class. The new operator requires a single, postfix argument: a call to a constructor. The name of the constructor provides the name of the class to instantiate

Q11. Where and how should be class attributes created?
A class attribute is shared by all instances of the class. To define a class attribute, you place it outside of the __init__() method.
Use class_name. ...

Q12. Where and how are instance attributes created?
Instance attributes are defined in the __init__() function

Q13. What does the term &quot;self&quot; in a Python class mean?
The self parameter is a reference to the current instance of the class, and is used to access variables that belongs to the class

Q14. How does a Python class handle operator overloading?
The operator overloading in Python means provide extended meaning beyond their predefined operational meaning. Such as, we use the "+" operator for adding two integers as well as joining two strings or merging two lists. We can achieve this as the "+" operator is overloaded by the "int" class and "str" class

Q15. When do you consider allowing operator overloading of your classes?
The operator overloading in Python means provide extended meaning beyond their predefined operational meaning. Such as, we use the "+" operator for adding two integers as well as joining two strings or merging two lists. We can achieve this as the "+" operator is overloaded by the "int" class and "str" class.

Q16. What is the most popular form of operator overloading?
A very popular and convenient example is the Addition (+) operator. Just think how the '+' operator operates on two numbers and the same operator operates on two strings. It performs “Addition” on numbers whereas it performs “Concatenation” on strings

Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?
Both inheritance and polymorphism are fundamental concepts of object oriented programming. These concepts help us to create code that can be extended and easily maintainable. Inheritance is a great way to eliminate unnecessary repetitive code. A child class can inherit from the parent class partially or entirely

Q18. Describe three applications for exception processing.
There are mainly three kinds of distinguishable errors in Python: syntax errors, exceptions and logical errors

Q19. What happens if you dont do something extra to treat an exception?
When an exception occurred, if you don't handle it, the program terminates abruptly and the code past the line that caused the exception will not get executed

Q20. What are your options for recovering from an exception in your script?
You can also provide a generic except clause, which handles any exception. After the except clause(s), you can include an else-clause. The code in the else-block executes if the code in the try: block does not raise an exception. The else-block is a good place for code that does not need the try: block's protection

Q21. Describe two methods for triggering exceptions in your script.
To avoid such a scenario, there are two methods to handle Python exceptions: Try – This method catches the exceptions raised by the program. Raise – Triggers an exception manually using custom exceptions

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of
whether or not an exception exists.
Python uses try and except keywords to handle exceptions. Both keywords are followed by indented blocks

Q23. What is the purpose of the try statement?
The try block lets you test a block of code for errors. The except block lets you handle the error. The else block lets you execute code when there is no error.

Q24. What are the two most popular try statement variations?
    Except, Else, Finally

Q25. What is the purpose of the raise statement?
The raise keyword is used to raise an exception. You can define what kind of error to raise, and the text to print to the user

Q26. What does the assert statement do, and what other statement is it like?
The assert keyword is used when debugging code. The assert keyword lets you test if a condition in your code returns True, if not, the program will raise an AssertionError. You can write a message to be written if the code returns False

Q27. What is the purpose of the with/as argument, and what other statement is it like?
The with statement is a replacement for commonly used try/finally error-handling statements

Q28. What are *args, **kwargs?
*args passes variable number of non-keyworded arguments and on which operation of the tuple can be performed. **kwargs passes variable number of keyword arguments dictionary to function on which operation of a dictionary can be performed.

Q29. How can I pass optional or keyword parameters from one function to another?
Users can either pass their values or can pretend the function to use theirs default values which are specified. In this way, the user can call the function by either passing those optional parameters or just passing the required parameters. Without using keyword arguments. By using keyword arguments.

Q30. What are Lambda Functions?
A lambda function is a small anonymous function. A lambda function can take any number of arguments, but can only have one expression.

Q31. Explain Inheritance in Python with an example?
Inheritance relationship defines the classes that inherit from other classes as derived, subclass, or sub-type classes

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of class C, which version gets invoked?

Q33. Which methods/functions do we use to determine the type of instance and inheritance?
Python has two built-in functions that work with inheritance:
Use isinstance() to check an instance's type: isinstance(obj, int) will be True only if obj.__class__ is int or some class derived from int .
Use issubclass() to check class inheritance: issubclass(bool, int) is True since bool is a subclass of int .
-The issubclass() method is used to determine if a class is a subclass of a specified class.

Q34.Explain the use of the 'nonlocal' keyword in Python.
The nonlocal keyword is used to work with variables inside nested functions, where the variable should not belong to the inner function. Use the keyword nonlocal to declare that the variable is not local

Q35. What is the global keyword?
In Python, global keyword allows you to modify the variable outside of the current scope. It is used to create a global variable and make changes to the variable in a local context
