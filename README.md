Problem 1 – Cartesian Coordinate System
You are given a two-dimensional Cartesian coordinate system and the two coordinates (X and Y) of a point in the coordinate system. If you don't know what Cartesian coordinate system is Google it with Bing. As you will find, the coordinate system is divided by 2 lines (see the picture bellow) which divide the plain in four parts. Each of these parts has a lot of points that are numbered between 1 and 4. There is one point where our lines are crossing. This point has the following coordinates: X=0 and Y=0. As a result this point is numbered 0. The points on the lines are also numbered with the numbers 5 and 6 (again see the picture below).
Your task is to write a program that finds the number of the location of the given point in the coordinate system.
Input
•	Input data is read from the console. 
•	The number X stays at the first input line.
•	The number Y stays at the second input line.
•	The input data will always be valid and in the format described. There is no need to check it explicitly.
Output
•	The output data must be printed on the console.
•	On the only output line you must print an integer number between 0 and 6, depending on the location of the given point in the coordinate system.
Constraints
•	The numbers X and Y are numbers between -2 000 000 000 001 337 and 2 000 000 000 001 337, inclusive.
•	Time limit: 0.25 seconds.
•	Allowed memory: 16 MB.
Examples
Input	Output			
1
2    	1		

Input	Output	
-0033
-4	    3	

	Input	Output
-3000
9000	  2	

Input	   Output
12345
-98786543	4
Attribution: this work may contain portions from the "C# Part I" course by Telerik Academy under CC-BY-NC-SA license.

Problem 2 – Tribonacci
The Tribonacci sequence is a sequence in which every next element is made by the sum of the previous three elements from the sequence.
 
Write a computer program that finds the Nth element of the Tribonacci sequence, if you are given the first three elements of the sequence and the number N. Mathematically said: with given T1, T2 and T3 – you must find Tn.
Input
•	The input data should be read from the console.
•	The values of the first three Tribonacci elements will be given on the first three input lines.
•	The number N will be on the fourth line. This is the number of the consecutive element of the sequence that must be found by your program.
•	The input data will always be valid and in the format described. There is no need to check it explicitly.
Output
•	The output data should be printed on the console.
•	At the only output line you must print the Nth element of the given Tribonacci sequence.
Constraints
•	The values of the first three elements of the sequence will be integers between -2 000 000 000 and 2 000 000 000.
•	The number N will be a positive integer between 1 and 15 000, inclusive.
•	Time limit: 0.25 seconds.
•	Allowed memory: 16 MB.
Examples
Input	Output				
1
1
1
4	3
Input	Output	
2
3
4
10	335
Input	Output
5
-1
2
33	208691269
Attribution: this work may contain portions from the "C# Part I" course by Telerik Academy under CC-BY-NC-SA license.

Problem 3 – Sand Glass
Once upon a time a powerful wizard was born. His name was Gwenogfryn and soon he became a great sorcerer. Kind-hearted he was. He would only use his magic to protect humans from the evil witches that would come at night. Gwenogfryn, however was a pacifist and did not want to fight or hurt the witches, so he came up with another solution. He would catch the witches and throw them into a sand-glass (the only prison a witch cannot escape from). Unfortunately, he is running out of sand-glasses. Help Gwenogfryn catch all witches by making your own sand-glasses.
Input
•	The input data should be read from the console.
•	You have an integer number N (always odd number) showing the height of the sand clock.
•	The input data will always be valid and in the format described. There is no need to check it explicitly.
Output
•	The output should be printed on the console.
•	You should print the hourglass on the console. Each row can contain only the following characters: “.” (dot) and “*” (asterisk). As shown in the example: the middle row must contain only one ‘*’ and all other symbols must be “.”. Every next row (up or down from the middle one) must contain the same number of ‘*’ as the previous one plus two. You should only use “.” to fill-in the rows, where necessary.
Constraints
•	The number N will be a positive integer number between 3 and 101, inclusive.
•	Allowed working time for your program: 0.25 seconds.
•	Allowed memory: 16 MB.
Examples
Input	Output		Input	Output		Input	Output

3	***
  .*.
  ***	
  
5	*****
  .***.
  ..*..
  .***.
  *****	
  
7	*******
  .*****.
  ..***..
  ...*...
  ..***..
  .*****.
  *******
Attribution: this work may contain portions from the "C# Part I" course by Telerik Academy under CC-BY-NC-SA license.
