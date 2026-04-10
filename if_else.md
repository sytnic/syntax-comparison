# If ... Else

## Kotlin

```kotlin
fun main() {
  if (20 > 18) {
    println("20 is greater than 18")
  }
}
```

```kotlin
fun main() {
  val time = 20
  if (time < 18) {
    println("Good day.")
  } else {
    println("Good evening.")
  }
}
// Outputs "Good evening."
```

```kotlin
val time = 22
if (time < 10) {
  println("Good morning.")
} else if (time < 20) {
  println("Good day.")
} else {
  println("Good evening.")
}
// Outputs "Good evening."
```

In Kotlin, you can also use if..else statements as expressions (assign a value to a variable and return it):

```kotlin
val time = 20
val greeting = if (time < 18) {
  "Good day."
} else {         // else is required
  "Good evening."
}
println(greeting)
```

You can ommit the curly braces {} when if has only one statement:

```kotlin
fun main() {
  val time = 20
  val greeting = if (time < 18) "Good day." else "Good evening."
  println(greeting)
}
// Good evening.
```

### Kotlin When (as Switch in PHP)

```kotlin
val day = 4

val result = when (day) {
  1 -> "Monday"
  2 -> "Tuesday"
  3 -> "Wednesday"
  4 -> "Thursday"
  5 -> "Friday"
  6 -> "Saturday"
  7 -> "Sunday"
  else -> "Invalid day."
}
println(result)

// Outputs "Thursday" (day 4)
```

```kotlin

```

```kotlin

```

```kotlin

```

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

## Python

```py

```

## VB

```vb

```