# Logical Operators
Logical operators are used to combine conditional statements. They evaluate expressions and return either `True` or `False`.
# Common Logical Operators:
- `and`: Returns True if both conditions are true.
- `or`: Returns True if at least one condition is true.
- `not`: Reverses the logical state of its operand (True becomes False, and vice versa).
**Examples:**
```python
x = 5
y = 10
z = 15

# and operator
print(x > 0 and y > 5)  # Output: True (both conditions are True)

# or operator
print(x > 10 or z > 10)  # Output: True (one of the conditions is True)

# not operator
print(not(x > 10))  # Output: True (reverses False to True)
```
