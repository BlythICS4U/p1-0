# p1-0 Repetition and Selection Practice

Create new NetBeans projects as you deem necessary to complete the exercises below.  Ensure that all new NetBeans projects are created inside the same directory where this repository was cloned.

(1) Write for loop statements that produce the following results (use a different for loop for each line).

```
1 12 23 34 45 56 67 78 89 100
27 32 37 42 47 52 57 62 67 72 77
32 25 18 11 4
10 9 8 7 6 5 4 3 2 1 Blastoff!
27 13 -1 -15 -29 -43 -57 -71 -85 -99
```

(2) Write a program that asks the user to type in a year (e.g. 2009) and determines and outputs whether the year is a leap year or not.

(3) Write a program that asks the user to type in their mark in Computer Science. Depending on their input, print the appropriate output from this chart:

Mark | Output
--- | ---
< 0 | Invalid Mark
0 to 49 | Extra help is always available.
50 to 59 | Check that you understand all concepts.
60 to 69 | Your Grade is a C. Keep working hard!
70 to 79 | Your Grade is a B. Good work!
80 to 100 | You have earned an A. Congratulations
\> 100 | Invalid Mark

(4) Write a program that first asks the user *how many* marks they will be entering. By using a for statement that counts from 1 to *how many*, allow the user to enter that quantity of marks. Keep a *total* of the numbers entered. Once all the numbers have been entered, calculate the average and print it out.

(5) Write a program that asks the user to input ten numbers. The program then outputs the total and the average of the numbers (average can be a truncated integer).

```
Type an integer: 14
Type an integer: 12
Type an integer: 35
Type an integer: 17
Type an integer: 21
Type an integer: 12
Type an integer: 9
Type an integer: 63
Type an integer: 22
Type an integer: 42

Total = 247
Average = 24
```
```
Type an integer: -13
Type an integer: 27
Type an integer: -6
Type an integer: -81
Type an integer: 14
Type an integer: 23
Type an integer: 16
Type an integer: 35
Type an integer: 19
Type an integer: -2

Total = 32
Average = 3
```

(6) Write a program that asks the user to input as many positive integers as they like. When a negative number is entered, this signals "no more data". Output the total of the positive numbers, how many positive numbers there are, and the average of the positive numbers (average can be a truncated integer). Assume that zero is never input. Assume that the user types at least one positive number. Declare all variables to be *int*. Use a *while* loop in this program.

```
Type and integer (negative to stop): 14
Type and integer (negative to stop): 12
Type and integer (negative to stop): 17
Type and integer (negative to stop): 22
Type and integer (negative to stop): -6

Total = 65
There are 4 numbers.
Average = 16
```
```
Type and integer (negative to stop): 3000
Type and integer (negative to stop): 2560
Type and integer (negative to stop): 1482
Type and integer (negative to stop): 1995
Type and integer (negative to stop): 1313
Type and integer (negative to stop): 1716
Type and integer (negative to stop): -5

Total = 12066
There are 6 numbers.
Average = 2011
```

(7) Write a number-guessing game. You can generate a random integer in the range [1, 100] by using the following statements:
```
Random rand = new Random(); // Make sure to import java.util.Random at the top of your class
int randomInteger = rand.nextInt(100) + 1;
```
The output of the game should look similar to the following examples:
```
Type in your guess (1 to 100): 50
Too high! Guess again: 25
Too low! Guess again: 37
Too high! Guess again: 30
Too high! Guess again: 28
Too low! Guess again: 29
That's it!
```
```
Type in your guess (1 to 100): 50
Too low! Guess again: 75
Too high! Guess again: 68
That's it!
```
