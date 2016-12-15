1. About
	The project involves following different types of matrix multiplication:-
	1. Simple multiplication with 3 for loops.
	2. Block multiplication with block size of 16 as base case.
	3. Parallel version of simple multiplication where outer for loop has been cilkified
	4. Parallel version of simple multiplication where inner for loop has been cilkified
	5. Parallel version of simple multiplication where inner & outer for loop has been cilkified
	6. Parallel version of block multiplication where block size of 16 is the base case.
	
2. System Configuration
	System configuration is:
	Processor: Intel Core i3-370M CPU M372 @ 2.40 GHz
	RAM: 3.00 GB DDR3
	Cache:	L3 Cache
		L3 Cache 3 MB

3. Environment
	The Environment in 
		Written in : visual studio 2008 (optimization turned off)
		Compiled using : Intel C++ Cilk compiler
		Operating System is : Windows 7 64 bit operating System

4. To execute:
	execute the ".\Release\Matrix Multiplication.exe" file.
	It takes two input
		1. Matrix size.
		2. Number of iterations.

5. Output:
	For the given matrix size, and number of iterations, it performs matrix multiplication and prints the estimated time taken.

6. Locate the source file:
	Goto ".\Matrix Multiplication\Main.cilk". This single source file contains all the code.