# Variables. Переменные


### Kotlin

```kotlin
fun main() {
  var name = "John" // String
  val birthyear = 1975 // Int
  println(name)
  println(birthyear)
}
```

Разница между var и val заключается в том, что переменные, объявленные с помощью ключевого слова var, могут быть изменены, в то время как переменные val - нет.

Объявление типа переменной. Необязательно в Kotlin.

```kotlin

    var name: String = "John" // String
    val birthyear: Int = 1975 // Int

    println(name)
    println(birthyear)
```

Но обязательно, если переменная просто инициализирована без присвоения значения.

```kotlin

    var name: String
    name = "John"
    println(name)
```

### PHP

Объявление типа переменной. Необязательно в PHP.

```php

```

### Javascript

Объявление типа переменной. Необязательно в Javascript.

```js

```

### Python

Python has no command for declaring a variable.  
A variable is created the moment you first assign a value to it.  

```py
    x = 5
    y = "John"
    print(x)
    print(y)
```

Переменные не обязательно объявлять с указанием какого-либо конкретного типа, и их тип может измениться даже после присвоения.

```py
    x = 4       # x is of type int
    x = "Sally" # x is now of type str
    print(x)
```

Casting.  
If you want to specify the data type of a variable, this can be done with casting.

```py
    x = str(3)    # x will be '3'
    y = int(3)    # y will be 3
    z = float(3)  # z will be 3.0

    x = int(1)    # x будет равно 1
    y = int(2.8)  # y будет равно 2
    z = int("3")  # z будет равно 3

    x = float(1)     # x будет равно 1,0
    y = float(2.8)   # y будет равно 2,8
    z = float("3")   # z будет равно 3,0
    w = float("4.2") # w будет равно 4,2

    x = str("s1")   # x будет равно 's1'
    y = str(2)      # y будет равно '2'
    z = str(3.0)    # z будет равно '3.0'
```

You can get the data type of a variable with the type() function.

```py
    x = 5
    y = "John"
    print(type(x))
    print(type(y))
```

String variables can be declared either by using single or double quotes:

```py
    x = "John"
    # is the same as
    x = 'John'
```

Variable names are case-sensitive.

```py
    a = 4
    A = "Sally"
    #A will not overwrite a
```

### VB

Объявление типа переменной. Обязательно в VB.

```vb

```