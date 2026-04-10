# Arrays

## Kotlin

Access the Elements of an Array

```kotlin
fun main() {
  val cars = arrayOf("Volvo", "BMW", "Ford", "Mazda")
  println(cars[0])
}
// Outputs Volvo 
```

Change an Array Element

```kotlin
val cars = arrayOf("Volvo", "BMW", "Ford", "Mazda")
cars[0] = "Opel"
println(cars[0])
// Now outputs Opel instead of Volvo
```

Array Length / Size

```kotlin
val cars = arrayOf("Volvo", "BMW", "Ford", "Mazda")
println(cars.size)
// Outputs 4 
```

Check if an Element Exists

```kotlin
val cars = arrayOf("Volvo", "BMW", "Ford", "Mazda")
if ("Volvo" in cars) {
  println("It exists!")
} else {
  println("It does not exist.")
}
// It exists!
```

Loop Through an Array

```kotlin
val cars = arrayOf("Volvo", "BMW", "Ford", "Mazda")
for (x in cars) {
  println(x)
}
// Volvo
// BMW
// Ford
// Mazda
```

## 