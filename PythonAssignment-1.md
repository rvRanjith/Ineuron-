## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
  Python is a object oriented language. object orient means this langauge is based around objects and high level means its easy for humans to understand

Q2. Why is Python called a dynamically typed language?
    its defined as dynamic language because the type of variable is determined only during run time 

Q3. List some pros and cons of Python programming language?
   Pros :
     easy to learn and read
     it has vast collection of libraries
  cons :
     its slow speed
     weak in mobile computing

Q4. In what all domains can we use Python?
    - machine learning , data analytics , web development, game development

Q5. What are variable and how can we declare them?
    - name given to a memeory location is called variable
    - to declare a variable in python just name the variable and assign required value to it

Q6. How can we take an input from the user in Python?
     - input () is the function used to get input value

Q7. What is the default datatype of the value that has been taken as an input using input() function?
 - the default datatype will return as a string

Q8. What is type casting?
 - the method to convert the variable data type into a certain data type in order to the operation required to be performed by users

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
 -  we can take multiple inputs from python using the split()  and map () methods

Q10. What are keywords?
- Python keywords are special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes

Q11. Can we use keywords as a variable? Support your answer with reason.
 -  No key words cant be used in python as each of them have specific meanings

Q12. What is indentation? What's the use of indentaion in Python?
  - Indentation refers to the spaces at the beginning of a code line, Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
 -using print command

Q14. What are operators in Python?
Operators are special symbols in Python that carry out arithmetic or logical computation

Q15. What is difference between / and // operators?
 - / - float division - divides left hand operand by right hand
 - // -floor division - where is the result is quotient 

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron

```

print("iNeuroniNeuroniNeuroniNeuron")

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
 num=int(input ("enter the no"))
if (num % 2) == 0 :
    print ("even")
else:
     print ("odd")

Q18. What are boolean operator?
 - The logical operators and, or and not are also referred to as boolean operators

Q19. What will the output of the following?
```
1 or 0 -  true

0 and 0 - false


1 or 0 or 0 -true
```

Q20. What are conditional statements in Python?
   - conditional statements are decision based conditions in python 

Q21. What is use of 'if', 'elif' and 'else' keywords?

   - if command is used to check a condition and provide an execution
   - elif also called as else if its the  next set of conditions used when if condition fails
   - else is executed when else conditions fails 

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
age  = input("enter the age:")
if age >= 18:
    print("I can vote")
elif age < 18:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
numbers = [12, 75, 150, 180, 145, 525, 50]
result = 0
for i in numbers:
    if not i % 2:
        result += i

print(result)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
a = int(input('Enter first number  : '))
b = int(input('Enter second number : '))
c = int(input('Enter third number  : '))

largest = 0

if a > b and a > c:
    largest = a
if b > a and b > c:
    largest = b
if c > a and c > b:
    largest = c

print(largest, "is the largest of three numbers.")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
a = [12, 75, 150, 180, 145, 525, 50]
b = []
for i in a:
    if i > 150:
        if i > 500:
            break
        continue
    if i % 5 == 0:
        b.append(i)
        
print(b)