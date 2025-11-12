<!---
{
  "id": "c25a4d2d-dd76-4b3c-868f-aaef175c0f89",
  "teaches": "Basic Operations from the Terminal",
  "depends_on": [],
  "author": "Stephan Bökelmann",
  "first_used": "2025-04-01",
  "keywords": ["shell", "expressions", "terminal", "basics"]
}
--->

# Basic Operations from the Terminal

## 1) Introduction

The usage of interactive command-line interpreters began in the 1960s. Early users could interface with a computer via teletype terminals like the Teletype Model 33, sending characters as bitstreams to an input buffer through a deserializer circuit. The computer processed this data and returned results to an output buffer, which were then transmitted back through a serializer.

Today, we use **terminal emulators** instead of physical teletypes, but the underlying principle remains the same. The terminal emulator allows users to interact with the shell program, which passes commands to the operating system and returns results.

In this challenge, you’ll learn to use the terminal emulator to:

- Evaluate basic arithmetic expressions
- Use logical operators
- Experiment with parentheses and grouping
- Apply expressions to strings

## 2) Tasks

1. **Evaluating Arithmetic Expressions**

    Open your terminal emulator and type the following commands:

    ```bash
    expr 1 + 2
    expr 3 - 2
    expr 3 \* 2
    expr 1 / 2
    expr 2 / 1
    expr 2 \* 2
    expr 3 \* 2
    ```

2. **Evaluating Logical Expressions**

    Try logical comparisons:

    ```bash
    expr 3 = 3
    expr 3 != 3
    expr 2 \> 3
    expr 3 \< 6
    expr 3 \>= 3
    expr 3 \<= 3
    ```

3. **Using Parentheses for Grouping**

    Use parentheses to group operations:

    ```bash
    expr \( 3 + 2 \) \* 2
    expr \( 3 + 2 \) \* 2 = 10
    ```

4. **String Comparisons**

    Evaluate expressions on strings:

    ```bash
    expr "hello" = "hello"
    expr "hello" != "hello"
    ```

## 3) Questions

- What happens if you omit spaces in your expression?
- What happens when division would result in a decimal?
- Which comparisons return 0 and which return 1?
- Why do some comparisons require escaping characters like `>` or `<`?
- How do parentheses change the result?
- What happens if parentheses aren’t escaped correctly?
- What kind of string comparisons are useful in scripts?
- Which other operations could you imagine performing on strings?

## 4) Advice

Even though you'll later use more powerful tools for working with data, it's critical to understand these foundational concepts. Repeat the tasks with varied arguments, predict the outcomes, and experiment with invalid inputs to learn how errors are handled.
