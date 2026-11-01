# Lesson 01 - Introduction to C Programming
![Language](https://img.shields.io/badge/Language-C-blue?style=flat-square&logo=c)
![Compiler](https://img.shields.io/badge/Compiler-GCC-lightgrey?style=flat-square&logo=gnu)
![Status](https://img.shields.io/badge/Status-In%20Progress-orange?style=flat-square)

## Learning Objectives

By the end of this lesson, I should be able to:

- [ ] Understand what C programming is.
- [ ] Explain what a compiler does.
- [ ] Identify the purpose of an IDE and development environment.
- [ ] Understand the basic structure of a C program.
- [ ] Write and run my first C program.
- [ ] Understand `#include`, `main()`, `printf()`, and `return 0`.
- [ ] Compile and execute a C program using GCC.

## 1. What Is C?

C is a **general-purpose programming language** used to create software and interact with computer hardware.

It is known for its: 
- Speed
- Efficiency
- Control over system resources

### Common Applications

| Area | Description |
|---|---|
| Operating Systems | System-level programming |
| Embedded Systems | Microcontrollers and hardware |
| Compilers | Programming language development |
| System Software | Low-level utilities and tools |
| Performance-Critical Applications | Software requiring efficient execution |

> **Key Takeaway:** C provides a strong foundation for understanding programming and how software interacts with computer systems.

---

## 2. Understanding the Development Tools

| Tool | Purpose |
|---|---|
| VS Code | Code editor that can be configured as an IDE |
| Notepad++ | Text editor |
| MSYS2 | Development environment and package manager |
| GCC | C compiler |

A compiler translates C source code into a form the computer can execute.

An IDE combines tools that help developers write, build, and debug programs.

## 3. Understanding the Structure of C

A basic C program looks like this:

```c
#include <stdio.h>

int main(void)
{
    printf("Hello, GitHub!");

    return 0;
}
```

### Code Breakdown

| Code | Explanation |
|---|---|
| `#include <stdio.h>` | Includes standard input/output declarations. |
| `int main(void)` | Defines the main function, where program execution begins. |
| `{ }` | Marks the beginning and end of the function body. |
| `printf()` | Displays formatted output. |
| `return 0;` | Indicates that the program finished successfully. |

### Important Concepts

- `#include` is a preprocessor directive.
- `main()` is the entry point of a C program.
- `printf()` displays output.
- A semicolon (`;`) terminates many C statements.
- `return 0` conventionally indicates successful execution.

## 4. My First C Program

```c
#include <stdio.h>

int main(void)
{
    printf("Hello, GitHub!");

    return 0;
}
```

Expected Output:

```
Hello, GitHub!
```

## 5. Experiments

### Experiment 1 — Change the Message

Change the text inside `printf()`.

```c
#include <stdio.h>

int main(void)
{
    printf("Welcome, to my repo!");

    return 0;
}
```

Expected Output:

```
Welcome, to my repo!
```


### Experiment 2 — Multiple Messages

Try displaying multiple messages.

```c
#include <stdio.h>

int main(void)
{
    printf("To Buy List\n");
    printf("Milk\n");
    printf("Egg\n");
    printf("Canned Tuna\n");
    printf("Juice\n");

    return 0;
}
```

Expected Output:

```
To Buy List
Milk
Egg
Canned Tuna
Juice
```

### Experiment 3 — Break the Program

Remove a semicolon and observe the compiler error.

```c
#include <stdio.h>

int main(void)
{
    printf("Hello, GitHub!")

    return 0;
}
```

Expected Output:

```
error: expected ';' before 'return'
```

## 6. Practice Challenges

### Challenge 1 — Personal Introduction

Create a program that displays:

- Your name
- Your age
- Your current learning goal

```c
#include <stdio.h>

int main(void)
{
    printf("Name: Rayce Manuel E. Fillon\n");
    printf("Age: 19\n");
    printf("Goal: To become proficient in C programming.\n");

    return 0;
}
```

Expected Output:

```
Name: Rayce Manuel E. Fillon
Age: 19
Goal: To become proficient in C programming.
```


### Challenge 2 — ASCII Art

Create a simple design using text characters.

```c
#include <stdio.h>

int main(void)
{
    printf("=======================\n");
    printf("|                     |\n");
    printf("|   Welcome to C!     |\n");
    printf("|                     |\n");
    printf("=======================\n");

    return 0;
}
```

Expected Output:

```
=======================
|                     |
|   Welcome to C!     |
|                     |
=======================
```

### Challenge 3 — Multi-Line Display

Use `\n` to display multiple lines of text.

Example:

```c
printf("Hello!\n");
printf("Welcome to my C journey.\n");
printf("Let's start coding!\n");
```

```
#include <stdio.h>

int main(void)
{
    printf("Hello!\n");
    printf("Welcome to my C journey.\n");
    printf("Let's start coding!\n");

    return 0;
}
```

Expected Output:

```
Hello!
Welcome to my C journey.
Let's start coding!
```

## 7. Hidden Challenge

Display `Hello, World!` without using `printf()`.

Research standard C functionality and experiment with another output method.

```c
#include <stdio.h>

int main(void)
{
    puts("Hello, World!");

    return 0;
}
```

Expected Output:

```
Hello, World!
```

## 8. Final Boss — Terminal Identity Screen

Create a terminal screen that displays your developer identity.

Include:

- Your alias
- A short introduction
- ASCII art
- Your current programming journey

```c
#include <stdio.h>

int main(void)
{
    printf("**********************");
    puts("*    Zrayce           *");
    printf("");
    puts("");
    printf("");

    return 0;
}
```
## 9. Knowledge Check

Before moving forward, make sure I can explain:

- [ ] What C programming is.
- [ ] What a compiler does.
- [ ] What an IDE is.
- [ ] What `#include <stdio.h>` does.
- [ ] Why `main()` is important.
- [ ] What `printf()` does.
- [ ] Why semicolons matter.
- [ ] What `return 0` means.

## 10. Developer Notes


### Common Escape Sequences

| Escape Sequence | Meaning |
|---|---|
| `\n` | New line |
| `\t` | Horizontal tab |
| `\\` | Backslash |
| `\"` | Double quotation mark |

### Compiling with GCC

Compile:

```bash
gcc main.c -o main
```

Run on Windows:

```bash
.\main.exe
```

### Development Log

| Date | Progress | Notes |
|---|---|---|
| 11/01/26 | Started Lesson 01 | Introduction to C |

## Lesson Completion Checklist

- [ ] Read the lesson.
- [ ] Understand the basic concepts.
- [ ] Write my first C program.
- [ ] Complete the practice challenges.
- [ ] Complete the hidden challenge.
- [ ] Complete the final boss.
- [ ] Pass the knowledge check.

---

**Next Lesson:** Variables and Data Types in C.
