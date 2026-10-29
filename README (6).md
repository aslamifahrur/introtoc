# Assignment: Find All Divisors

## Objective

Write a C program that prints all positive divisors of an input positive integer named `max`, in ascending order.

A divisor is a number that divides `max` exactly, with no remainder. Print each divisor on a separate line, including `1` and `max` itself.

## Instructions

Include `<stdio.h>`. Inside `main()`, complete the following steps:

1. Declare two `int` variables named `max` and `i`.
2. Display `max? ` as the input prompt.
3. Read a positive integer into `max` using `scanf()`.
4. Use a `for` loop to check every integer `i` from `1` to `max`, inclusive.
5. Inside the loop, use an `if` statement to check whether `max` is divisible by `i`.
6. If the remainder is `0`, print `i` followed by a new line.

For this exercise, assume that the user enters a valid positive integer.

## Starter Code

```c
#include <stdio.h>

int main() {
    // 1) Declare max and i

    // 2) Display the prompt: max?

    // 3) Read max using scanf

    // 4) Write a for loop from 1 to max (inclusive)
    {
        // 5) Check whether max is divisible by i
        {
            // 6) Print i followed by a new line
        }
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
5
10
20
25
50
100
```

## Hints

- Use the remainder operator `%`.
- The condition `max % i == 0` means that `i` divides `max` exactly.
- Start `i` at `1` to avoid division by zero.
- Include `max` in the loop range because a positive integer is always a divisor of itself.
