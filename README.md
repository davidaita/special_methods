# Python Special Methods Examples

## Overview

This project demonstrates the most commonly used **Python special methods (dunder methods)** through simple, beginner-friendly examples. Each example explains the purpose of a special method and shows how it can be implemented in a custom class.

## Topics Covered

* `__init__()` – Initialize object attributes (constructor)
* `__str__()` – Human-readable string representation
* `__repr__()` – Developer-friendly object representation
* `__len__()` – Define object length
* `__eq__()` – Compare objects for equality
* `__add__()` – Operator overloading
* `__getitem__()` – Enable indexing
* `__setitem__()` – Enable item assignment
* `__contains__()` – Support the `in` operator
* `__call__()` – Make objects callable like functions

## Learning Objectives

After completing this notebook, you will be able to:

* Understand the purpose of Python special methods.
* Create classes with custom behavior.
* Overload operators for user-defined objects.
* Implement indexing, assignment, and membership operations.
* Build more intuitive and Pythonic classes.

## Project Structure

```
special methods.ipynb   # Jupyter notebook containing explanations and examples
```

## Requirements

* Python 3.x
* Jupyter Notebook or JupyterLab

## How to Run

1. Clone or download this repository.
2. Open `special methods.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells sequentially to explore each example.

## Example

```python
class Student:
    def __init__(self, name):
        self.name = name

    def __str__(self):
        return f"Student: {self.name}"

student = Student("David")
print(student)
```

**Output**

```
Student: David
```

## Who This Project Is For

This notebook is suitable for:

* Beginners learning Object-Oriented Programming (OOP) in Python.
* Students studying Python special (dunder) methods.
* Anyone looking for practical examples of customizing Python classes.

## License

This project is provided for educational purposes and may be freely used for learning and teaching.
