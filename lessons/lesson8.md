

## Welcome to Lesson Eight

#### You're doing great! Now, let’s dive into Functions in Kotlin.

Okay, let’s get started!

### What is a Function?

In Kotlin, a **function** is a block of code that performs a specific task. Functions allow you to organize your code and reuse it. You can call the function whenever you need it, instead of writing the same code again and again.

### Basic Function Structure

A simple function in Kotlin looks like this:

```kotlin
fun greet() {
    println("Hello, welcome to Kotlin!")
}
```

- `fun`: This keyword is used to declare a function.
- `greet()`: This is the function name, and it has empty parentheses because it doesn’t take any parameters.
- The code inside the curly braces `{}` is the body of the function. This is where you put the logic or actions you want the function to perform.

### Calling a Function

Once you define a function, you can call it in your program like this:

```kotlin
fun main() {
    greet()  // Calling the function
}
```

When the program runs, it will call the `greet()` function, and the output will be:

```
Hello, welcome to Kotlin!
```

### Functions with Parameters

You can also define functions that take **parameters** (values) to perform actions with. Here’s an example:

```kotlin
fun greet(name: String) {
    println("Hello, $name!")
}
```

In this case, the function `greet()` takes a **String** parameter called `name`. You need to pass a value to the function when calling it:

```kotlin
fun main() {
    greet("Yigit")  // Calling the function with a parameter
}
```

The output will be:

```
Hello, Yigit!
```

### Functions with Return Values

You can also create functions that **return values**. For example, a function that adds two numbers together and returns the result:

```kotlin
fun add(a: Int, b: Int): Int {
    return a + b
}
```

Here, `add()` takes two `Int` parameters, adds them together, and **returns** the result as an `Int`.

You can use the return value like this:

```kotlin
fun main() {
    val sum = add(5, 3)
    println("The sum is: $sum")
}
```

The output will be:

```
The sum is: 8
```

---

### Summary

- **Functions** are blocks of code that perform tasks.
- You define functions using the `fun` keyword.
- Functions can take **parameters** and can also **return values**.
- Functions make your code cleaner, reusable, and organized.

---

That’s it for **Lesson Eight**! Now you understand how functions work in Kotlin. Keep practicing, and you'll be using functions like a pro! 😊

---

