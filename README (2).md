# Positive Integer Input Using a While Loop

## Instructions

Inside `main()`, complete the following steps:

1. Declare an `int` variable named `x`.
2. Print the prompt `Please input positive number: `.
3. Use `scanf()` with `%d` and `&x` to read an integer into `x`.
4. Use a `while` loop to repeat as long as `x` is less than or equal to `0`.
5. Inside the loop, print the same prompt and read a new integer into `x`.
6. After the loop, print `You input ` followed by the value of `x` and a new line.

For this exercise, assume the user enters integers only. A positive integer is greater than zero.

## Starter Code

```c
#include <stdio.h>

int main(void) {
    // 1) Declare x

    // 2) Print the prompt
    // 3) Read an integer into x

    // 4) Write the while loop
        // 5) Print the prompt and read another integer

    // 6) Print the accepted value followed by a new line

    return 0;
}
```

## Example Interaction

The values -2, 0, and 5 below represent user input.

```text
Please input positive number: -2
Please input positive number: 0
Please input positive number: 5
You input 5
```
