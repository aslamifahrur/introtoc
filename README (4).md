# Assignment 1: 9 × 9 Multiplication Table

## Objective

Write a C program that prints a **9 × 9 multiplication table** using nested loops.

Use two integer variables, `i` and `j`, with the following ranges:

- `i` goes from `1` to `9` horizontally (columns).
- `j` goes from `1` to `9` vertically (rows).
- Each value in the table is `i * j`.

## Instructions

Inside `main()`, complete the following steps:

1. Declare two `int` variables named `i` and `j`.
2. Write an outer `for` loop that repeats `j` from `1` to `9`.
3. Inside the outer loop, write an inner `for` loop that repeats `i` from `1` to `9`.
4. Inside the inner loop, print `i * j`. Use `%4d` to align the columns.
5. After the inner loop, print a new line to begin the next row.

## Starter Code

```c
#include <stdio.h>

int main() {
    // 1) Declare i and j

    // 2) Write the outer loop for j (rows)
    {
        // 3) Write the inner loop for i (columns)
        {
            // 4) Print i * j using %4d
        }

        // 5) Print a new line after each row
    }

    return 0;
}
```

## Expected Output

```text
   1   2   3   4   5   6   7   8   9
   2   4   6   8  10  12  14  16  18
   3   6   9  12  15  18  21  24  27
   4   8  12  16  20  24  28  32  36
   5  10  15  20  25  30  35  40  45
   6  12  18  24  30  36  42  48  54
   7  14  21  28  35  42  49  56  63
   8  16  24  32  40  48  56  64  72
   9  18  27  36  45  54  63  72  81
```

## Hint: Start with the First Row

First, set `j` to `1` and use one loop to print `i * j` for `i = 1, 2, ..., 9`.

Once the first row works, add the outer loop to repeat the process for all nine rows.

The inner loop prints one row. The outer loop repeats it for each value of `j`.
