# Part One | General Data types
_research and write brief definitions of the following data types and include an example of that data type.


integer


real


Boolean


char


string


array


record

# Part Two | Python Exercise: Variables and Data Types


## Task 1: Create the Variables

Write a program that stores the following information:

- A student's name (`Alex`)
- Their age (`15`)
- Their height in metres (`1.68`)
- Whether they have completed their homework (`True`)

Print each variable.

```python
name = "Alex"
age = 15
height = 1.68
homework_complete = True

print(name)
print(age)
print(height)
print(homework_complete)
```

---

## Task 2: Investigate the Data Types

Add code to display the data type of each variable.

Example:

```python
print(type(name))
```

### Questions

1. What data type is `name`?
2. What data type is `age`?
3. What data type is `height`?
4. What data type is `homework_complete`?

---

## Task 3: Predict Before Running

Look at each variable and predict its data type before you run the program.

```python
city = "Oxford"
temperature = 18.5
year_group = 10
lunch_paid = False
```

Write your predictions, then use `type()` to check your answers.

---

## Task 4: Fix the Mistakes

Each variable has been given the wrong data type.

Change the values so they match the description.

```python
age = "15"          # Should be an integer
price = "2.99"      # Should be a float
member = "True"     # Should be a boolean
```

---

## Task 5: Create Your Own Variables

Create four variables about yourself:

- Your favourite food (string)
- Your age (integer)
- The number of hours you slept last night (float)
- Whether you like Python (boolean)

Print both the value and data type of each variable.

Example:

```python
print(favourite_food)
print(type(favourite_food))
```

---

## Task 6

Without running the code, work out what data type each variable will have.

```python
score = 100
username = "guy123"
average = 72.4
winner = False
postcode = "OX3 8DD"
```

<details>
<summary>Show Answers</summary>

```text
score      → int
username   → str
average    → float
winner     → bool
postcode   → str
```

</details>

---

## Task 7

What data type would Python assign to each of these values?

```python
"100"
100
100.0
True
"True"
```
