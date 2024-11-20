
## Welcome to Lesson Six

#### You're doing awesome! Now, we're going to dive into loops.

Okay, let's go!

What are loops?

Loops are structures that allow you to repeat a block of code multiple times. They are helpful when you need to perform the same action several times without writing the same code repeatedly.

Okay, let’s see how loops work in Kotlin!

### 1. **For Loop**

The `for` loop in Kotlin is used to iterate over a range, array, or collection. Here’s an example:

```kotlin
fun main() {
    for (i in 1..5) {
        println("Number: $i")
    }
}
```

In this example, we’re using a `for` loop to print the numbers from 1 to 5. The `1..5` is a range that goes from 1 to 5, and for each value in the range, it prints the number.

### 2. **While Loop**

A `while` loop keeps running as long as the given condition is true. Here’s how it works:

```kotlin
fun main() {
    var count = 1
    while (count <= 5) {
        println("Count: $count")
        count++
    }
}
```

In this example, the loop runs as long as `count` is less than or equal to 5. It prints the current count and then increments it.

### 3. **Do-While Loop**

A `do-while` loop is a bit different from the `while` loop. It guarantees that the code block runs at least once, even if the condition is false from the start. Let’s see an example:

```kotlin
fun main() {
    var count = 1
    do {
        println("Count: $count")
        count++
    } while (count <= 5)
}
```

In this case, the code will print the current `count`, and then it checks if `count` is less than or equal to 5. If it is, the loop runs again.

---

### Summary

- **For Loop**: Used for iterating over a range or collection.
- **While Loop**: Runs as long as the given condition is true.
- **Do-While Loop**: Always runs at least once, even if the condition is false.

Loops are really powerful for repeating tasks efficiently. You’ll be using them a lot in your programs!

[Click here to go to lesson seven](https://github.com/ozaiithejava/Kotlin-Epsolide/blob/main/lessons/lesson7.md)
