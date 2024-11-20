## Welcome to Lesson Five

#### You are doing great! Now, we will learn Control Structures.

okey lets goo!!

what ise the Control Structures?

Control structures are constructs that allow you to control something and take actions based on the results

okey! How to use the Control structures

let's see this.


```kotlin
fun main() {
    val age = 20

    if (age >= 18) {
        println("You are an adult.")
    } else {
        println("You are a minor.")
    }
}
```
In this example, we have a variable named age which is of type Int, and it holds the value 20. In the control part below, if age is greater than or equal to 18, it prints 'You are an adult.' Otherwise, it prints 'You are a minor.'

Good, I understand these examples.
lets go the other structures.

okey lets gooo!

Now, let's look at what when is and how it is used.

what is the when in kotlin (not a real life :=))

The when expression is like a switch-case structure, but when is considered more modern than switch-case.

okey lets make a some examples.

```kotlin
fun main() {
    val day = "Monday"

    when (day) {
        "Monday" -> println("Start of the week.")
        "Friday" -> println("End of the week.")
        else -> println("Midweek.")
    }
}
```
In this example, we have a day variable, and the when structure looks like it's holding different cases to match the value of day

If day equals 'Monday', print 'Start of the week.' in the console. If day equals 'Friday', print 'End of the week.' Otherwise, print 'Midweek.'

"Okay, this is great! Let's see the if shortcuts in use."

```kotlin
fun main() {
    val number = 10
    val result = if (number % 2 == 0) "Even" else "Odd"
    println(result)  // Output: Even
}
```
Here, we have a variable number that holds the value 10. If the remainder of dividing number by 2 is 0, meaning it’s an even number, the result variable is assigned the value 'Even'. Otherwise, it is assigned the value 'Odd'.