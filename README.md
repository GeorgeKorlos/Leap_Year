# Leap Year Checker

This Python script checks if a given year is a leap year or not based on user input. 

## How It Works
1. The user enters a year.
2. The script determines if the year is a leap year using the following logic:
   - A year is a leap year if it is divisible by 4.
   - However, if the year is divisible by 100, it must also be divisible by 400 to be considered a leap year.
   - If a year is divisible by 100 but not by 400, it is **not** a leap year.

## Conditions
- **Leap year**: A year divisible by 4, but not by 100 unless it is divisible by 400.
- **Not a leap year**: A year not divisible by 4, or divisible by 100 but not by 400.
