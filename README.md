# Cubes-of-N-Numbers

Question: Cubes of N Numbers

Input: 4

Output: 1 8 27 64

In this coding question, you need to write a program that reads a number N and prints the cube of N numbers starting from 1. The cube of a number X is X to the power of 3 (X3).

For example, if the given number is N = 4, the program should print the cubes of the first 4 numbers (1, 2, 3, and 4) like this:
1
8
27
64

Approach
To solve this problem, we will follow these steps:

Read the input number N.
Initialize a counter variable to keep track of the current number.
Calculate and print the cube of each number from 1 to N.

Step-by-Step Explanation:

Step 1: Read the input number

First, we need to read the input number N which represents the number of cubes we need to calculate. We can use the input() function to read the input and int() to convert it into an integer.

Step 2: Initialize a counter variable

Next, we need to initialize a counter variable to keep track of the current number. We will start the counter at 0.

Step 3: Calculate and print the cube of each number

Now, we will use a while loop to calculate and print the cube of each number from 1 to N. Inside the loop, we will:

Increment the counter by 1.
Calculate the cube of the current number by raising it to the power of 3 (counter ** 3).

Print the cube of the current number.
