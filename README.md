# Ternary

This project is a simple Java program that demonstrates:

- How to use traditional `if/else` statements
- How to use the ternary operator (shorthand `if/else`)

---

## Project Description

The program checks two conditions:

1. `isDiabetic` — boolean value representing if the user is diabetic.
2. `isHungry` — boolean value representing if the user is hungry.

Based on these conditions, the program decides:

- If the user should eat cake or not.

---

## Logic Explanation:

### The Long Way (Traditional If/Else)

```java
if(!isDiabetic && isHungry){
    message = "Eat the cake.";
}else{
    message = "Don't eat the cake.";
}
