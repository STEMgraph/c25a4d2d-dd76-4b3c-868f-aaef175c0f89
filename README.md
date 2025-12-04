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

This exercise is your entry-point to the world of command-line-based execution on Linux-Systems. 
Hopefully, someone already installed a Linux-Distribution for you, if not, make sure to get yourself an old computer, a random laptop, or a Raspberry Pi with a Keyboard and a Screen! 
You don't need any additional software installed, but a basic Linux-Distribution.
If you don't know, where to start, join the [Full-Stack-Engineering Discord Community](https://discord.gg/rdwVGj4mzD) and go to the **#absolute-beginners**-Channel. There you'll find a lot of ressources and people to help you out!

### Why Command-Line Proficiency is Crucial for Engineering Beginners

Mastering command-line interfaces is essential for aspiring engineers because it builds a deep understanding of how computers operate at a fundamental level. Unlike graphical user interfaces (GUIs), which abstract away complexities, the command line demands precise instructions, fostering problem-solving skills, debugging abilities, and efficiency in automation. In engineering fields like software development, data science, and systems administration, many tools (e.g., version control with Git, package managers like npm or apt, and scripting languages) rely heavily on terminal commands. Early exposure prevents reliance on point-and-click methods, enabling beginners to troubleshoot issues, write scripts for repetitive tasks, and integrate seamlessly into professional workflows where GUIs may not suffice. Moreover, it promotes resourcefulness in constrained environments, such as remote servers or embedded systems, and lays the groundwork for advanced concepts like DevOps and cloud computing. Neglecting this foundation can lead to inefficiencies and limitations in a career where adaptability and low-level control are paramount.

Beyond software engineering, command-line proficiency is invaluable for engineers across all disciplines. Whether you're designing circuit diagrams, running SPICE simulations, working with CAD/CAM tools, scripting in cadquery, or analyzing data in R, a solid grasp of prompt-reply mechanics—the interactive cycle of issuing commands and receiving outputs—forms the bedrock of efficient tool usage. Start learning these basics today to unlock deeper control over your workflows and avoid the pitfalls of GUI limitations in complex engineering tasks.

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
