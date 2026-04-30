# Ranges

## Kotlin

```kotlin
fun main() {
  for (chars in 'a'..'f') {
    print(chars)
  }
}
// abcdef
```

```kotlin
fun main() {
  for (nums in 5..10) {
    println(nums)
  }
}
/*
5
6
7
8
9
10
*/
```

### Check if a Value Exists


```kotlin
fun main() {
  val nums = arrayOf(2, 4, 6, 8)
  if (2 in nums) {
    println("It exists!")
  } else {
    println("It does not exist.")
  }
}
// It exists!
```

```kotlin
fun main() {
  val cars = arrayOf("Volvo", "BMW", "Ford", "Mazda")
  if ("Volvo" in cars) {
    println("It exists!")
  } else {
    println("It does not exist.")
  }
}
// It exists!
```

### Break or Continue a Range

```kotlin
fun main() {
  for (nums in 5..15) {
    if (nums == 10) {
      break
    }
    println(nums)
  }
}
// 56789
```

```kotlin
fun main() {
  for (nums in 5..15) {
    if (nums == 10) {
      continue
    }
    println(nums)
  }
}
/*
5
6
7
8
9
11
12
13
14
15
*/
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