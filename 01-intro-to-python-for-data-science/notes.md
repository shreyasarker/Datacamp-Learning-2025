
# 📘 Notes: Intro to Python for Data Science

These are concise notes from the "Intro to Python for Data Science" course on DataCamp.

---

## 1. Python Basics

- Python is a versatile, beginner-friendly programming language.
- Common data types:
  - `int` – integers
  - `float` – decimal numbers
  - `str` – text
  - `bool` – True/False values

```python
height = 1.75
weight = 70
name = "Alex"
is_student = True
```

- Arithmetic operators: `+`, `-`, `*`, `/`, `**` (power), `%` (modulo)

---

## 2. Lists

- Ordered, mutable collections.

```python
heights = [1.70, 1.65, 1.80]
heights.append(1.75)
print(heights[0])  # Indexing starts at 0
```

- List slicing: `heights[1:3]`
- Nesting: Lists can contain lists.

---

## 3. Functions

- Built-in: `print()`, `type()`, `len()`, `max()`, `round()`
- User-defined:

```python
def greet(name):
    return "Hello " + name
```

---

## 4. Methods

- Functions that belong to objects.

```python
word = "hello"
print(word.upper())  # Output: HELLO
```

- Lists also have methods: `.append()`, `.count()`, `.index()`

---

## 5. Packages

- Use `import` to bring in external tools.

```python
import math
print(math.sqrt(25))  # Output: 5.0
```

---

## 6. NumPy

- Used for efficient numeric calculations.

```python
import numpy as np

height = [1.73, 1.68, 1.71]
weight = [65, 59, 63]

np_height = np.array(height)
np_weight = np.array(weight)

bmi = np_weight / np_height ** 2
print(bmi)
```

- NumPy arrays support **element-wise operations** and are more efficient than lists for numeric data.

---

## ✅ Summary

- Python provides strong foundations for data science.
- Lists and NumPy arrays are key tools for data manipulation.
- Understanding data types, indexing, and vectorized operations is essential.
