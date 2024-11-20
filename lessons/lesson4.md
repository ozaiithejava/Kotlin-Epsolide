## Welcome to Lesson Four

#### You are doing great! Now, we will learn how to using a math operators in kotlin.


Okay, let's look at these shortcuts for the math operators.



| **Shortcut** | **Description**                 | **Example**              |
|--------------|---------------------------------|--------------------------|
| `+=`         | Addition                        | `number += 3`            |
| `-=`         | Subtraction                     | `number -= 3`            |
| `*=`         | Multiplication                  | `number *= 3`            |
| `/=`         | Division                        | `number /= 3`            |
| `%=`         | Modulus (Remainder)             | `number %= 3`            |


### Descriptions:
- **`+=`**: Adds the value to the variable and assigns the result back.
- **`-=`**: Subtracts the value from the variable and assigns the result back.
- **`*=`**: Multiplies the variable by the value and assigns the result back.
- **`/=`**: Divides the variable by the value and assigns the result back.
- **`%=`**: Assigns the remainder of the division to the variable.


lets doing the some examples

##### Example 1: Addition (+=):

```kotlin
fun main() {
    var number = 10
    number += 5  // number = number + 5
    println(number)  // Output: 15
}

```
##### Example 2: Subtraction (-=)

```kotlin
fun main() {
    var number = 20
    number -= 4  // number = number - 4
    println(number)  // Output: 16
}


```
##### Example 3: Multiplication (*=)

```kotlin
fun main() {
    var number = 3
    number *= 4  // number = number * 4
    println(number)  // Output: 12
}


```
##### Example 4: Division (/=)

```kotlin
fun main() {
    var number = 30
    number /= 5  // number = number / 5
    println(number)  // Output: 6
}


```
##### Example 5: Modulus (%=)

```kotlin
fun main() {
    var number = 17
    number %= 5  // number = number % 5
    println(number)  // Output: 2
}
```
<details>
  <summary>Explanation of Outputs(click mee!)</summary>

- **Addition**: 10 + 5 = 15
- **Subtraction**: 20 - 4 = 16
- **Multiplication**: 3 * 4 = 12
- **Division**: 30 / 5 = 6
- **Modulus**: 17 % 5 = 2 (remainder of 17 divided by 5)

</details>
