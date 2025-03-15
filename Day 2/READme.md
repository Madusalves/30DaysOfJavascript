# JavaScript Counter Function Challenge

## Problem Statement

Given an integer `n`, return a counter function. This counter function initially returns `n` and then returns `1` more than the previous value every subsequent time it is called (`n`, `n + 1`, `n + 2`, etc).

## Explanation

1. The function `createCounter(n)` returns another function (a closure).
2. This inner function maintains access to the variable `n` even after `createCounter` has finished executing.
3. Each time the inner function is called, it returns the current value of `n` and then increments it.

## Key Concepts

- **Closures**: The inner function retains access to the outer function's scope even after execution.
- **Function Factories**: The outer function creates and returns a customized function.
- **Lexical Scope**: The variable `n` persists across multiple calls due to JavaScript's lexical scoping.

## Why is this Useful?

Understanding closures is crucial in JavaScript as they help in:
- Maintaining state without using global variables.
- Creating private variables and encapsulation.
- Implementing functional programming patterns effectively.

## Further Practice

Try modifying the counter function to:
1. Allow resetting to the initial `n` value.
2. Allow decrementing instead of incrementing.
3. Start from `n` but increase by a given step (e.g., `n, n + step, n + 2*step, ...`).

Happy coding! 🚀

