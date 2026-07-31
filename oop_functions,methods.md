# OOP methods

## Kotlin

Kotlin Class Functions

```kotlin
class Car(var brand: String, var model: String, var year: Int) {
  // Class function
  fun drive() {
    println("Wrooom!")
  }

  // Class function with parameters
  fun speed(maxSpeed: Int) {
    println("Max speed is: " + maxSpeed)
  }
}

fun main() {
  val c1 = Car("Ford", "Mustang", 1969)
  
  // Print property values
  println(c1.brand + " " + c1.model + " " + c1.year)
  // Ford Mustang 1969

  // Call the functions
  c1.drive()
  // Wrooom!

  c1.speed(200)
  // Max speed is: 200
}
```

Class Function Parameters

```kotlin
class Car(var brand: String, var model: String, var year: Int) {
  // Class function
  fun drive() {
    println("Wrooom!")
  }

  // Class function with parameters
  fun speed(maxSpeed: Int) {
    println("Max speed is: " + maxSpeed)
  }
}

fun main() {
  val c1 = Car("Ford", "Mustang", 1969)
  
  // Print property values
  println(c1.brand + " " + c1.model + " " + c1.year)  //  Ford Mustang 1969
  
  // Call the functions
  c1.drive()            // Wrooom!
  c1.speed(200)         // Max speed is: 200
}
```


```kotlin

```


## Python

```py

```

```py

```


## Kotlin

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


## VB

```vb

```