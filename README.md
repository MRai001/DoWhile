# DoWhile Program

## Description
This simple Java program demonstrates the `do-while` loop construct by printing numbers from 1 to 5.

## Code Overview
The program contains a single class `DoWhile` with a `main` method that:
1. Initializes a counter variable `i` to 1
2. Executes a `do-while` loop that:
   - Prints the current value of `i`
   - Increments `i` by 1
   - Continues as long as `i` is less than or equal to 5


## Running the Program
To compile and run this program:
```bash
javac DoWhile.java
java DoWhile
```

## Expected Output
```
Number: 1
Number: 2
Number: 3
Number: 4
Number: 5
```

## Key Differences from a While Loop
If this were implemented as a regular while loop, the condition would be checked before the first iteration. 
In this case, the result would be the same, but there are scenarios where a do-while loop is preferable when you need to 
execute the code block at least once regardless of the condition.
