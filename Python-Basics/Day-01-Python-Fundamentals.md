# Day 01 - Python Fundamentals

## Introduction

Python is a high-level, easy-to-learn programming language widely used in Artificial Intelligence, Machine Learning, Data Science, Web Development, and Automation.

---

# 1. Variables

Variables are used to store data values in memory.

### Example

```python
name = "Harsh"
age = 20
cgpa = 8.4
```

### Explanation

* `name` stores text
* `age` stores an integer value
* `cgpa` stores a decimal value

Variables help us store and reuse information throughout a program.

---

# 2. Data Types

Data types define the type of value stored in a variable.

### Common Data Types

| Data Type | Example |
| --------- | ------- |
| int       | 10      |
| float     | 8.4     |
| str       | "Harsh" |
| bool      | True    |

### Example

```python
age = 20
height = 5.9
name = "Harsh"
is_student = True
```

---

# 3. Lists

Lists are ordered collections that can store multiple values.

### Example

```python
sports = ["Football", "Basketball", "Cricket"]
```

### Accessing Elements

```python
print(sports[0])
```

Output:

```python
Football
```

### Features

* Ordered
* Mutable (can be changed)
* Allows duplicate values

---

# 4. Tuples

Tuples are similar to lists but cannot be modified after creation.

### Example

```python
languages = ("Python", "Java", "C++")
```

### Features

* Ordered
* Immutable
* Faster than lists for fixed data

---

# 5. Dictionaries

Dictionaries store data as key-value pairs.

### Example

```python
student = {
    "name": "Harsh",
    "age": 20,
    "branch": "AI/ML"
}
```

### Accessing Data

```python
print(student["name"])
```

Output:

```python
Harsh
```

### Features

* Key-value structure
* Fast lookup
* Widely used in Machine Learning and APIs

---

# 6. Sets

Sets store unique values only.

### Example

```python
numbers = {1, 2, 3, 4, 5}
```

### Duplicate Example

```python
numbers = {1, 1, 2, 2, 3}
```

Output:

```python
{1, 2, 3}
```

### Features

* No duplicates
* Unordered
* Useful for fast searching and comparisons

---

# Summary

Today I learned:

* Variables
* Data Types
* Lists
* Tuples
* Dictionaries
* Sets

These are the fundamental building blocks of Python and form the foundation for Data Science, Machine Learning, and AI development.

---

# Next Learning Goal

* Conditional Statements (if, elif, else)
* Loops (for, while)
* Functions
* List Comprehensions
