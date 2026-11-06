# Assignment 2 — Decisions and Loops

This lab practices using conditions to choose what a program does and loops to repeat calculations.

## Tools

| Tool | Version / details |
|---|---|
| Operating system | Windows 10 / Windows 11 |
| IDE | Visual Studio Code with Extension Pack for Java |
| JDK | OpenJDK 17 (Temurin-17.0.13+11) |
| Terminal | Windows PowerShell (`pwsh`) |

Compile and run each program from its question directory:

```powershell
javac Main.java
java Main
```

## Concepts

`if` and `if-else` evaluate conditions; an `else-if` chain handles multiple cases. `for`, `while`, and `do-while` loops repeat statements until their stopping condition is met. The exercises use these ideas for number checks and arithmetic, including divisibility with `%` and an iterative factorial calculation.

## Procedures

| Question | Task | Main steps |
|---|---|---|
| 1 | Even or odd | Set `n = 27`; test whether `n % 2 == 0`, then print the matching result. |
| 2 | Grade with an else-if ladder | Set `marks = 83`; check `>= 90` for A, `>= 75` for B, and otherwise print C. |
| 3 | Leap year | Set `year = 2024`; check `((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0))` and print the result. |
| 4 | Factorial with a for loop | Start with `n = 5` and `fact = 1`; multiply `fact` by each integer from 1 through `n`. |

## Inputs and outputs

| Question | Input value | Output |
|---|---|---|
| 1 | `n = 27` | `27 is odd` |
| 2 | `marks = 83` | `Grade: B` |
| 3 | `year = 2024` | `Leap year` |
| 4 | `n = 5` | `Factorial of 5 is 120` |

## Result

All four programs were written, compiled, and run in Visual Studio Code. Their outputs matched the expected results.
