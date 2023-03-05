# Loops

JavaScript loops are used to repeat a block of code multiple times. There are three main types of loops in JavaScript: **"for"**, **"while"**, and **"do-while"** loops.

A **"for"** loop is used when the number of iterations is known in advance. It consists of an initialization, a condition, and an update statement, and the loop will continue to execute as long as the condition is true.

A **"while"** loop is used when the number of iterations is not known in advance. It consists of a condition, and the loop will continue to execute as long as the condition is true.

A **"do-while"** loop is similar to a "while" loop, but the condition is checked at the end of the loop instead of the beginning. This means that the loop will always execute at least once, even if the condition is initially false.

# Example

```
const numbers = [1, 2, 3, 4, 5];

for (let i = 0; i < numbers.length; i++) {
  console.log(numbers[i]);
}
```