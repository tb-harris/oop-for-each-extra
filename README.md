# For Each - Optional Challenges
## RomanNumeralConverter.java - Part 1
*    **Problem:** Convert a Roman Numeral provided by the user to its numerical value. You can assume that the Roman Numeral is valid, and that the numeral does not use subtractive rotation (ie 4 is represented as IIII, not IV).
*    **Note:** You can either take in each Roman Numeral as a separate argument (ie `X X I I I` instead of `XXIII`), or use `String characters = args[0].toCharArray()` to convert the first argument provided by the user to an array that you can iterate through with a for-each loop.
*    **Command Line Arguments:** `<Roman Numeral>` _or_ <Roman Numeral digit 1> <Roman Numeral digit 2> ... 

### Example Output
```
XXIIII
24
```

```
MMXXV
2025
```

```
MDCLXVI
1666
```

## RomanNumeralConverter.java - Part 2
*   **Problem:** Update your program to account for subtractive notation. With subtractive notation, when a smaller numeral precedes a larger numeral, the smaller numeral is subtracted from the larger numeral instead of added. For example, IV represents 4, XL represents 40, XC represents 90, CD represents 400, and CM represents 900.
*   **Command Line Arguments:** `<Roman Numeral>`
*   **Hint:** Keep track of the value of the previous numeral, and compare it with the value of your current numeral to determine if you need to adjust your running total. Think carefully about how you would need to adjust your running total in that case given that the previous number was already added in.

### Example Output
```
XXIV
24
```

```
MCMXCIX
1999
```

## FibonacciChecker.java
*    **Problem:** Write a program to check if a sequence of numbers follows the pattern 1, 2, 3, 5, ... where each number is the sum of the two preceding ones.
*    **Command Line Arguments:** `<num1> <num2> <num3> ...`
*    **Hint:** You will need variables to keep track of the previous two values in the sequence. Their values could start at 0 and 1.

### Example Output
```
1 2 3 5 8
Fibonacci!
```

```
1 2 3 5 8 13 21
Fibonacci!
```

```
1 2 3 5 8 13 40
Not Fibonacci!
```

```
8 10 18
Not Fibonacci!
```

