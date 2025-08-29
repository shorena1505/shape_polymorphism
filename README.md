# Python Shapes Project

## Overview
This project demonstrates basic **inheritance and polymorphism** in Python.

- A base class `Shape` with a `name` attribute and an `area()` method.
- Subclasses `Rectangle` and `Circle` that override the `area()` method.
- A `print_area()` function that demonstrates polymorphism by accepting any `Shape` object and printing its area.

## Usage

```python
from shapes import Shape, Rectangle, Circle, print_area

rect = Rectangle("MyRectangle", 10, 20)
circle = Circle("MyCircle", 5)

print_area(rect)    # Output: MyRectangle area: 200.00
print_area(circle)  # Output: MyCircle area: 78.54
