Option 3: FSA table + driver (100 points)
The FSA table is located in scanner.cpp
The driver function is located in testScanner.cpp

To compile the project:
1. run 'make scanner' 
2. the program can be invoked three different ways: file specification (no extension), file redirection (with extension), and keyboard input
	file: ./scanner fileName
	redirection: ./scanner < fileName.ext
	keyboard: ./scanner 	// User then types input and presses ctrl+d to simulate EOF

Note: More than one argument will output an error message and instructions to properly run program
Note: Program output is not printed to a file
