# 🐍 Basic Python

A beginner-friendly **10-week Python programming course** designed for students who have little or no programming experience.

The course starts with Python fundamentals and gradually introduces variables, user input, decision making, loops, data structures, functions, and numerical computing using NumPy.

Each week contains lecture materials, examples, and hands-on exercises implemented in **Jupyter Notebook / Google Colab**.

---

# 📚 Course Overview

| Week | Topic | Learning Outcome |
|------|-------|------------------|
| 1 | Python Fundamentals | Learn Python syntax, output, strings, and numbers |
| 2 | Variables, Input & Output | Store data, receive user input, and perform calculations |
| 3 | Input–Process–Output (IPO) | Develop complete Python programs using the IPO model |
| 4 | Conditional Statements *(Suggested)* | Make decisions using `if`, `elif`, and `else` |
| 5 | For Loops | Automate repetitive tasks |
| 6 | Lists | Store and process collections of data |
| 7 | While Loops & Exception Handling | Build condition-controlled programs and validate user input |
| 8 | Dictionaries & Sets | Organize structured and unique data |
| 9 | Functions | Create reusable and modular programs |
| 10 | NumPy | Perform numerical computing with arrays |

---

# 🚀 Weekly Topics

---

## Week 1 — Python Fundamentals

### Topics

- Introduction to Python
- Hello World
- print()
- Comments
- Strings
- Escape characters
- Numbers
- Arithmetic operators
- Common syntax errors

### Example

```python
print("Hello World")

name = "Alice"

print("Hello", name)
print(5 + 3)
```

### Learning Outcome

Students can

- write their first Python program
- display information
- work with strings
- perform basic arithmetic

---

## Week 2 — Variables, Input and Output

### Topics

- Variables
- Assignment
- Data types
- int
- float
- str
- bool
- Type conversion
- input()
- Formatted output

### Example

```python
price = float(input("Price: "))
qty = int(input("Quantity: "))

total = price * qty

print(f"Total = {total}")
```

### Learning Outcome

Students can

- store information in variables
- receive input from users
- convert data types
- display formatted results

---

## Week 3 — Input–Process–Output

### Topics

- IPO Model
- Mathematical expressions
- Operator precedence
- f-strings
- Programming workflow

### IPO Model

```
Input
   ↓
Process
   ↓
Output
```

### Example

```python
kg = float(input("Kilograms: "))

lb = kg * 2.20462

print(f"{kg} kg = {lb:.2f} lb")
```

### Learning Outcome

Students can translate real-world problems into complete Python programs.

---

## Week 4 — Conditional Statements *(Suggested Topic)*

> **Note**
>
> The Week 4 notebook currently contains no readable content.
> Based on the course progression, conditional statements are recommended for this week.

### Topics

- if
- elif
- else
- Boolean expressions
- Comparison operators
- Logical operators

### Example

```python
score = 80

if score >= 80:
    print("A")
elif score >= 70:
    print("B")
else:
    print("C")
```

### Learning Outcome

Students can write programs that make decisions.

---

## Week 5 — For Loops

### Topics

- for loops
- range()
- Nested loops
- Looping through strings
- Repetition

### Example

```python
for i in range(5):
    print(i)
```

Nested loop

```python
for r in range(3):
    for c in range(4):
        print("*", end=" ")
    print()
```

### Learning Outcome

Students can automate repetitive tasks.

---

## Week 6 — Lists

### Topics

- Creating lists
- Indexing
- Slicing
- append()
- insert()
- remove()
- List comprehension
- Nested lists

### Example

```python
scores = [70, 80, 90]

scores.append(95)

for score in scores:
    print(score)
```

### Learning Outcome

Students can manage collections of data.

---

## Week 7 — While Loops & Exception Handling

### Topics

- while
- break
- continue
- else
- try
- except

### Example

```python
while True:
    try:
        age = int(input("Age: "))
        break
    except ValueError:
        print("Invalid input")
```

### Learning Outcome

Students can build programs that continue until a condition is satisfied and safely handle invalid input.

---

## Week 8 — Dictionaries & Sets

### Dictionary

```python
student = {
    "name": "Anna",
    "score": 90
}

print(student["score"])
```

### Set

```python
A = {"Python", "Java"}

B = {"Python", "C++"}

print(A & B)
```

### Learning Outcome

Students can

- organize information using key-value pairs
- perform operations on unique collections

---

## Week 9 — Functions

### Topics

- def
- Parameters
- Arguments
- return
- Local variables
- Global variables

### Example

```python
def rectangle_area(width, height):
    return width * height

print(rectangle_area(5, 10))
```

### Learning Outcome

Students can create reusable and modular programs.

---

## Week 10 — NumPy

### Topics

- ndarray
- Array creation
- Shape
- Indexing
- Slicing
- Broadcasting
- Matrix operations
- Mean
- Sum

### Example

```python
import numpy as np

scores = np.array([70, 80, 90])

print(scores.mean())
print(scores.sum())
```

### Learning Outcome

Students can perform efficient numerical computation using NumPy.

---

# 📈 Learning Progression

```text
Week 1
Python Basics
      │
      ▼
Week 2
Variables & Input
      │
      ▼
Week 3
IPO Programming
      │
      ▼
Week 4
Decision Making
      │
      ▼
Week 5
For Loops
      │
      ▼
Week 6
Lists
      │
      ▼
Week 7
While Loops
      │
      ▼
Week 8
Dictionary & Set
      │
      ▼
Week 9
Functions
      │
      ▼
Week 10
NumPy
```

---

# 🎯 Course Learning Outcomes

After completing this course, students will be able to:

- ✅ Write Python programs using correct syntax
- ✅ Solve problems using the Input–Process–Output model
- ✅ Use variables and data types effectively
- ✅ Make decisions with conditional statements
- ✅ Automate tasks using loops
- ✅ Store and process data using lists, dictionaries, and sets
- ✅ Develop reusable functions
- ✅ Perform numerical computing with NumPy
- ✅ Build a strong foundation for data science, AI, and software development

---

# 🛠️ Requirements

- Python 3.x
- Jupyter Notebook or Google Colab

---

# 📂 Repository Structure

```
basic_python/
│
├── Week01/
├── Week02/
├── Week03/
├── Week04/
├── Week05/
├── Week06/
├── Week07/
├── Week08/
├── Week09/
└── Week10/
```

---

# 💡 Recommended Learning Path

```
Python Syntax
      ↓
Variables
      ↓
Input / Output
      ↓
Decision Making
      ↓
Loops
      ↓
Collections
      ↓
Functions
      ↓
NumPy
      ↓
🚀 Ready for Intermediate Python
```

---

## 👨‍🏫 Target Audience

- Beginner programmers
- Undergraduate students
- STEM learners
- Anyone starting Python programming

---

Happy Coding! 🐍✨
