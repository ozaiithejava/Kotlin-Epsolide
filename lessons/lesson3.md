## Welcome to Lesson There

#### You are doing great! Now, we will learn how to assign variables.

```kotlin
fun main() {
    var age: Int = 25
    println(age)  // 25
    age = 30
    println(age)  // 30
}

```
Let's take a look at this code.

The initial value of age is 25, and we printed it to the console. Then, we changed the value of age to 30 and printed it to the console again. Now, the age variable holds the value 30.
```kotlin
fun main() {
    var name: String = "yigit"  
    println(name)  

    name = "efe"  
    println(name)  
}
```
Initially, our name variable holds the name 'Yigit', but we changed it to 'Efe'. The console output will be as follows:

> Yigit
> 
> Efe

Well, to make sure it only holds 'Yigit' and cannot be changed, we can use a val instead of var.
```kotlin
fun main() {
    val name: String = "Yigit"
    println(name)
}
```
Congratulations! You made a final variable.

Okay, good! But what is a final variable?

Final variables are created using val and can never be changed.
