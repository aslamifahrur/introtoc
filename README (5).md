# Assignment: Powers of 2

## Objective

Write a C program that prints all powers of **2** that are **less than** an input integer named `max`, in ascending order.

Start with `1` (2 to the power of 0) and print each value on a separate line.

## Instructions

Inside `main()`, complete the following steps:

1. Declare an `int` variable named `max`.
2. Declare an `int` variable named `i` and initialize it to `1`.
3. Display `max? ` as the input prompt.
4. Read the input integer into `max` using `scanf()`.
5. Use a `while` loop to repeat as long as `i` is less than `max`.
6. Inside the loop, print `i` followed by a new line.
7. Double the value of `i` in each iteration instead of increasing it by 1.

## Starter Code

```c
#include <stdio.h>

int main() {
    // 1) Declare max

    // 2) Declare i and initialize it to 1

    // 3) Display the prompt: max?

    // 4) Read max using scanf

    // 5) Write a while loop: repeat while i is less than max
    {
        // 6) Print i followed by a new line

        // 7) Double i
    }

    return 0;
}
```

## Output Example

For an input of `100`:

```text
max? 100
1
2
4
8
16
32
64
```

## Hints

- The initial value of `i` is `1`.
- Use `i = i * 2;` to double the value in each iteration.
- Use `<`, not `<=`: if `max` is `8`, print `1`, `2`, and `4` only.
- If `max` is `1` or smaller, no powers of 2 should be printed.
