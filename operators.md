# Operators

## Python

### The Ternary Operator

```py
num = 6

x = "WEEKEND!" if num > 5 else "Workday"

print(x)
# WEEKEND!
```

Assign:
- "Fri" if num is 5
- "Sat" if num is 6
- "Sun" if num is 7
- otherwise assign "weekday":

```py
num = 6

x = "Fri" if num == 5 else "Sat" if num == 6 else "Sun" if num == 7 else "weekday"

print(x)
# Sat
```

### Chaining Comparison Operators

```py
x = 5

print(1 < x < 10)
print(1 < x and x < 10)

# True
# True
```

### Identity Operators

```py
x = ["apple", "banana"]
y = ["apple", "banana"]
z = x

print(x is z)  # True
print(x is y)  # False
print(x == y)  # True
```

```py
x = ["apple", "banana"]
y = ["apple", "banana"]

print(x is not y)  # True
```

Difference Between `is` and `==`

- `is` - Checks if both variables point to the same object in memory
- `==` - Checks if the values of both variables are equal

```py
x = [1, 2, 3]
y = [1, 2, 3]

print(x == y)  # True
print(x is y)  # False
```

```py

```

```py

```

```py

```

```py

```

```py

```