# RISCV-Project1
Readme - Project 1: Assembly Programming and Computer Organization
•	Name: Alex LaJoie
•	Class: CS 2160 - Assembly Programming and Computer Organization
•	Project Title: Implementation of C Programming Functions in RISC-V Assembly
•	Date: 3/7/2025
1. How to Run the Program
1.	Open the QtRVSim simulator: QtRVSim Link
2.	Click on "Start Empty" with "No Pipeline, No Cache" option selected.
3.	Click "Open Source" and load alajoie-project1.S.
4.	Open the "Terminal" window from the "Windows" menu.
5.	Click "Compile Source" and then "Run".
6.	Follow on-screen instructions to enter a message and verify the output.
2. Description of the Assignment
This project involved writing RISC-V assembly code to:
•	Implement getchar, putchar, gets, and puts functions.
•	Read user input character-by-character.
•	Echo the user input back to the terminal.
•	Follow proper memory handling, null-termination, and error checking.
The final program asks the user for input, reads it one character at a time, and prints it back using system calls.
3. Test Cases
Test Case	Description	Input	Expected Output
1	Program start	N/A	"Step 1: Program Start" prints
2	Prompt for input	N/A	"Step 2: Enter a message:"
3	Read user input	Hello	"Step 3: Input received"
4	Print user input	Hello	"Step 4: Printing user input... Hello"
5	Handling newline	Hi\n	"Hi" (on new line)
4. Resources Used
•	QtRVSim Simulator Documentation: 
•	RISC-V Instruction Set Manual
•	Course lecture slides
5. Challenges Faced
•	Printing garbage characters: Fixed by properly handling null termination.
•	Unaligned memory access errors: Fixed by ensuring proper spacing in .data.
•	Debugging puts function: Ensured iteration stops at null character.
6. Time Spent on the Project
•	Estimated Total Time: 12-15 hours
o	Debugging and fixing output issues: 6 hours
o	Writing assembly functions: 5 hours
o	Testing and documentation: 3 hours
7. Final Version Documentation
•	Functionality: Program successfully prints messages, reads input, and echoes correctly.
•	Known Bugs: None found during testing.
•	Future Improvements: Implement error handling for gets when buffer exceeds limits.
8. Screenshots
Provided on PDF
9. Additional Notes
•	Code is maintained in a public GitHub repository.
