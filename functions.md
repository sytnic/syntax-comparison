# Functions

### PHP

### Javascript

> Отличия от других языков

Порядок объявления функций для их использования имеет значение.  
Функции в JS могут переопределяться далее по коду, как переменные.  

Чтобы функцию нельзя было перепоределить, используют фагкциональное выражение с константой.  

```js
// Function expression, 
// Функциональное выражение с анонимной функцией:
const doMoreMath = function (a = 3, b = 2) {
  let c = a * b;
  return c;
};

console.log("Do more math:", doMoreMath(5, 6));
// Do more math: 30
```

### Python

### Kotlin

Create and Call Own Functions

```kotlin

fun myFunction() {
  println("I just got executed!")
}

fun main() {
  myFunction()
}

// Outputs "I just got executed!" 
```

Function Parameters

```kotlin

fun myFunction(fname: String) {
  println(fname + " Doe")
}

fun main() {
  myFunction("John")
  myFunction("Jane")
  myFunction("George")
}
  
// John Doe
// Jane Doe
// George Doe 

```

Multiple Parameters

```kotlin

fun myFunction(fname: String, age: Int) {
  println(fname + " is " + age)
}

fun main() {
  myFunction("John", 35)
  myFunction("Jane", 32)
  myFunction("George", 15)
}

// John is 35
// Jane is 32
// George is 15 

```

Return Values  
A function with one `Int` parameter, and `Int` return type: 

```kotlin

fun myFunction(x: Int): Int {
  return (x + 5)
}

fun main() {
  var result = myFunction(3)
  println(result)
}

// 8 (3 + 5) 

```

A function with two Int parameters, and Int return type:

```kotlin

fun myFunction(x: Int, y: Int): Int {
  return (x + y)
}

fun main() {
  var result = myFunction(3, 5)
  println(result)
}

// 8 (3 + 5) 

```

Shorter Syntax for Return Values  
You can use the `=` operator instead of `return` without specifying the return type.

```kotlin

fun myFunction(x: Int, y: Int) = x + y

fun main() {
  var result = myFunction(3, 5)
  println(result)
}

// 8 (3 + 5) 

```

### VB