Download Link: https://assignmentchef.com/product/solved-computer-architecture-homework-6
<br>
1. Write a MIPS assembly language program that

a. prompts the user for a zip code (as a 5-digits unsigned integer, or 0) with the string “Give me your zip code (0 to stop): “. No error checking is necessary, assuming that the user will give correct numbers.

b. if the input is 0 stops

c. otherwise, display the leading string “The sum of all digits in your zip code is”, calculate the sum of all digits by calling two functions (see below) one at a time and then display the result with the leading string “ITERATIVE:” for the iterative version, and “RECURSIVE:” for the recursive version of the function.

d. repeats from a.

For example, if the user gave the input 75081 the program will print out The sum of all digits in your zip code is

ITERATIVE: 21

RECURSIVE: 21

This program should make use of a function that calculates and returns the sum of digits in the input argument zip code. Implement two versions of this function. one is iterative (named int_digits_sum) and the other is recursive (named rec_digits_sum). The main program should call each of these two functions to calculate and then display the sum after the user has input a ZIP code.

2. Carry out exercises 4.1. 4.2 and .4.4 of the textbook.