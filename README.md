# Writing For Loops in JavaScript

## Loops 

- In JavaScript, a for loop is a control structure that allows you to execute a block of code repeatedly for a specified number of iterations. It's a fundamental loop construct used to automate repetitive tasks and iterate through a sequence of values, typically an array or a numerical range.

 ```javascript
for (initialization; condition; iteration) {
    // Code to be executed in each iteration
    // This code block can contain one or more statements
}

// Code outside the loop

 ```

- Here's how the components of the for loop work:
1. Initialization: This part is used to initialize a loop control variable (usually called an index or a counter). It's executed before the loop starts and is typically used to set the initial value of the control variable.
2. Condition: The condition is a boolean expression that determines whether the loop should continue or stop. It's evaluated before each iteration, and if the condition is true, the loop continues; if it's false, the loop terminates.
3. Iteration: The iteration part is executed after each iteration of the loop. It's typically used to update the loop control variable (e.g., increment or decrement the index).
4. Code Block: The code block contains the statements that are executed in each iteration of the loop. This is where you place the code that you want to repeat.
5. Code outside the loop: This code is executed after the loop finishes executing. It's outside the scope of the loop.


 ```javascript
for (let i = 0; i < 5; i++) {
    console.log("Iteration:", i);
}
 ```

 - In this example, the loop will execute five times because the condition i < 5 starts as true and becomes false after the fifth iteration (when i becomes 5). The output will be:
Iteration: 0
Iteration: 1
Iteration: 2
Iteration: 3
Iteration: 4

- For loops are incredibly versatile and are commonly used to iterate over arrays, generate sequences, perform calculations over time, and much more. They're a powerful tool for automating repetitive tasks in your JavaScript programs.


### Prep

1. Connect your js file to your HTML file
2. Open your code in the browser and open your console

### Activities
1. In the `js` file, complete the list of exercises. 
