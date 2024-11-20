## Welcome to Lesson Two

Since you've made it here, you're progressing really well. Congratulations! If you keep going, you'll succeed.


In our second lesson, we will learn about variables.

### What is the variables.

Variables are things we use to assign values to something and store these values.

Okay, how to write a variable?
```kotlin
fun main() {
    var name: String = "John"
}
```
"Great! You wrote your first variable."

this good but ı dont know a var keyword . what is a var ?

The var keyword in Kotlin is used to declare a mutable variable, meaning the value of the variable can be changed later in the program

okey i stand this keyword but i dont know a String keyword.

"Okay, don't panic. String says I'm a (variable) text type."

good. lets make a another varibale

```kotlin
fun main() {
    var age: Int = 25
}
```
great!

okey let see a variables type table

| **Type**   | **Description**                        | **Example**               |
|------------|----------------------------------------|---------------------------|
| **Int**    | Integer type (whole numbers)           | `val age: Int = 25`        |
| **Double** | Floating-point numbers (decimal)       | `val height: Double = 5.9` |
| **Float**  | Smaller floating-point numbers         | `val weight: Float = 70.5f`|
| **String** | Text or a sequence of characters       | `val name: String = "Alice"`|
| **Boolean**| True or false values                   | `val isActive: Boolean = true` |
| **Char**   | A single character                     | `val letter: Char = 'A'`   |
| **Long**   | Larger integer numbers                 | `val bigNumber: Long = 123456789L` |
| **Short**  | Smaller integer numbers                | `val smallNumber: Short = 10` |

### Explanation:
- **Int**: Whole numbers like 1, 2, 100, etc.
- **Double** and **Float**: Numbers that can have decimal places. **Double** is for larger or more precise numbers, while **Float** uses less memory and is for smaller precision.
- **String**: A sequence of characters (e.g., "Hello").
- **Boolean**: Can only be true or false.
- **Char**: A single character like 'A' or '1'.
- **Long**: Larger whole numbers that **Int** can't handle.
- **Short**: Smaller whole numbers.

No need to worry, it may seem a bit too much, but you'll mostly encounter int, float, and string.

Okay, let's go to printing my name in the console.

okey but i dont your name ?
my name is yigit
lets do it
```kotlin
fun main() {
    var name: String = "yigit"
     println(name)       
            
}
```
"Great! You learned how to print variables in the console."

[Click here to go to lesson three](https://github.com/ozaiithejava/Kotlin-Epsolide/blob/main/lessons/lesson3.md)

