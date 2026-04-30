# Title

## Python

Multiline Strings

You can use three double quotes Or three single quotes:

```py
a = '''Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.'''
print(a)
```

Looping Through a String

```py
for x in "banana":
  print(x) 
```

String Length

```py
a = "Hello, World!"
print(len(a))
# 13
```

Check String

```py
txt = "The best things in life are free!"
print("free" in txt)
# True
```

```py
txt = "The best things in life are free!"
if "free" in txt:
  print("Yes, 'free' is present.")
# Yes, 'free' is present.
```

Check if NOT

```py
txt = "The best things in life are free!"
print("expensive" not in txt)
# True
```

print only if "expensive" is NOT present:

```py
txt = "The best things in life are free!"
if "expensive" not in txt:
  print("No, 'expensive' is NOT present.")
# No, 'expensive' is NOT present.
```

### Slicing

Get the characters from position 2 to position 5 (not included).  
Note: The first character has index 0.  

```py
b = "Hello, World!"
print(b[2:5])
# llo
```

### Modify Strings

Upper Case

```py
a = "Hello, World!"
print(a.upper())
# HELLO, WORLD!
```

Lower Case

```py
a = "Hello, World!"
print(a.lower())
# hello, world!
```

The strip() method removes any whitespace from the beginning or the end:

```py
a = " Hello, World! "
print(a.strip())
# Hello, World!
```

The replace() method replaces a string with another string:

```py
a = "Hello, World!"
print(a.replace("H", "J"))
# Jello, World!
```

The split() method returns a list where the text between the specified separator becomes the list items.

```py
a = "Hello, World!"
b = a.split(",")
print(b)
# ['Hello', ' World!']
```

### String Concatenation

```py
a = "Hello"
b = "World"
c = a + " " + b
print(c)
# Hello World
```

### Format - Strings

F-Strings

As we learned in the Python Variables chapter, we cannot combine strings and numbers.  
But we can combine strings and numbers by using f-strings or the format() method!  

```py
age = 36
txt = f"My name is John, I am {age}"
print(txt)
# My name is John, I am 36
```

A placeholder { } can contain variables, operations, functions, and modifiers to format the value.  
A placeholder { } can contain Python code, like math operations:  

```py
txt = f"The price is {20 * 59} dollars"
print(txt)
# The price is 1180 dollars
```

### Escape Characters

```py

```

```py

```

```py

```

```py

```


## VB

```vb

```

## Kotlin

```kotlin

```

```kotlin

```

### 


```kotlin

```

```kotlin

```


## PHP

```php

```


## Javascript

```js

```

