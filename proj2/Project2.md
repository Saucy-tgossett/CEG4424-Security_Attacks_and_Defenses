Task 1 - Examining the code (10 Points)
•	The BOFtest.c is a source C code program. Use a text editor to examine the C source code file (but don’t change it).  
•	Which line of code in this file is the source of the buffer overflow vulnerability?  (5 points)
•	Which variable is subject to overflow? (5 points)

Task 2 - Overflowing the buffer (25 Points)
•	Compile the BOFtest.c code with the following command:     gcc BOFtest.c  -o  BOFtest   What does this command do? (5 points)
•	Now run the program a few times with various inputs (various number of characters). 
•	Are you able to cause the program to halt in an error state? What is the number of input characters when the error occurred? Why? (20 points) (Please include the screenshot for the cases when the program runs correctly, and when the error occurred. The screenshot should include your username (campus id, w123abc), current directory, the execution commands,  and the complete execution results.  ) 

Task 3 – Examine the code (15 Points)
•	The Proj2-test.cpp is a source C++ code program that used cryptopp library functions. Use a text editor to examine the C++ source code file (but don’t change it).  
•	(15 points) What is the functionality of the source c++ code? Write a short paragraph to answer this question, not just one sentence. 

Task 4 – Compile and execute (10 Points)

Unzip Proj2.zip to get 00_e, 01_e, 02_e, 03_e. 

Compile the Proj2-test.cpp code with the following command:  cryptog++  Proj2-test.cpp  -lcryptopp -o Proj2. 

execute  Proj2 using the following command: 
./Proj2 00_e 00_p

Display the contents of 00_p using cat 00_p. 

•	What is the output? Display the output using the command: cat 00_p (Please include the screenshots of the output in your submission for the input files 00_e, 01_e, 02_e. The 
