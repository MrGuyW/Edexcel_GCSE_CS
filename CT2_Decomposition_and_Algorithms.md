# CT2 Decomposition and Algorithms

### Starter
Identify the term that means breaking a problem or solution down into
smaller parts.  (1)
- [ ] Abstraction
- [ ] Computation
- [ ] Decomposition
- [ ] Evaluation

### Learning Objectives
* Define the terms ‘decomposition’, ‘algorithm’, and 'sequence'
* Decompose a programming problem
* Sequence the pieces of an algorithm
* Interpret error messages

## Decomposition

### **Decomposition is the process of breaking a large problem or task into smaller, more manageable parts that can be solved one at a time.**


_Example_: Instead of thinking about "creating a school website", the task can be broken down into:

1. Designing the website
2. Creating the content
3. Building the pages
4. Testing the website
5. Publishing it online

By solving each smaller part separately, the overall problem becomes easier to manage and complete.

Decomposition helps us tackle complex problems by splitting them into smaller, simpler tasks.

## Decomposition in programming
_Problem: Create an algorithm that asks the user for the dimensions of a cylinder and calculates its volume._

## Level 1
- Get the dimensions
- Calculate the volume
- Display the result

## Level 2
### Get the dimensions
- Ask the user for the radius
- Ask the user for the height
 
### Calculate the volume
- Calculate the area of the circular base
- Multiply the base area by the height
 
### Display the result
- Show the volume to the user

## Algorithms

**An algorithm is a sequence of instructions or steps that can be followed to solve a problem or complete a task.**

An algorithm doesn't have to be written in a programming language:

```
Algorithm Calculate Cylinder Volume
 
  Ask the user to enter the radius of the cylinder
  Store the radius
 
  Ask the user to enter the height of the cylinder
  Store the height
 
  Calculate the area of the base by multiplying pi by the radius squared
 
  Calculate the volume by multiplying the base area by the height
 
  Display the volume of the cylinder
 
End Algorithm
```
This is an example of pseudocode. Pseudocode is a way of describing an algorithm using structured English that is easy for humans to read and is not tied to a specific programming language.

## Python task: Complete the python script to calculate the volume of a cylinder
_The script should ask the user to enter the radius and the height and return the volume_

```python
# Ask the user for the radius
cyl_radius = input("enter radius of cylinder: ")

# Ask the user for the height
cyl_height = input("enter height of cylinder: ")

# Calculate the area of the circular base (use 3.14 as pi)

# Multiply the base area by the height

# Display the volume to the user
```

## Sequence

**Sequence is the execution of instructions in the order they are written, one after another.**

Sequence is important in programming, because it controls how the lines of code are executed and means the steps MUST be in the right order.

### fix the following code to make it work:

```python
print(message)

message = name + " scored " + str(score) + " points."

score = 42

name = "Jamie"
```

### More challenge

```python
final_message = student + " achieved " + grade

grade = "Grade " + str(grade_number)

average = total / 4

grade_number = int(average / 10)

student = "Taylor"

print(final_message)

total = test1 + test2 + test3 + test4
test3 = 55
test1 = 72
test4 = 61
test2 = 80
```

# Understanding Python Error Messages
 
When a Python program crashes, Python displays an **error message**. Error messages help programmers identify what went wrong and where the problem occurred.
 
## Reading an Error Message
 
A Python error message usually tells you:
 
1. **The line number** where the error occurred.
2. **The type of error**.
3. A short description of the problem.
 
Example:
 
```text
NameError: name 'score' is not defined
```
 
This means Python tried to use a variable called `score`, but it doesn't exist.
 
## Common Errors
 
### NameError
 
Occurs when a variable has not been created.
 
```python
print(name)
```
 
Python cannot find a variable called `name`.
 
---
 
### SyntaxError
 
Occurs when Python cannot understand the code.
 
```python
print("Hello"
```
 
A closing bracket is missing.
 
---
 
### TypeError
 
Occurs when incompatible data types are used together.
 
```python
age = "15"
print(age + 5)
```
 
Python cannot add a string and an integer.
 
---
 
### ZeroDivisionError
 
Occurs when a program tries to divide by zero.
 
```python
result = 10 / 0
```
 
Division by zero is not allowed.
 
---
 
## Tips for Fixing Errors
 
- Read the error message carefully.
- Look at the line number mentioned.
- Identify the error type.
- Check variable names, spelling and punctuation.
- Fix one error at a time.

## Error messages and bug fixes

For each of the following code blocks:

1. List the line number of the error
2. Identify the type of error
3. Try to correct the error (fix the bug)


```python
duck_name = "Quackers"

words_typed = 872

message = duck + " typed " + str(words_typed) + " words today."

print(message) 
```

```python
word1 = "Correct"
word2 = "Horse"
word3 = "Battery"
word4 = "Staple"

password = word1 + word2 + word3 + word4

length = len(password)

message = "Your password is " + password + " and is " + length + " characters long."

print(message)
```
