# codtech_Task2
Name : Viraj Desai 
Company : Codtech IT solutions
ID : CT6PP496 
Domain: Python Programming 
Duration : June to August 2024 
Mentor : Neela Santhosh Kumar

The program is designed to calculate grades and CGPA based on marks obtained in multiple subjects entered by the user.

Functionality:

Input Section:

Prompts the user to input the number of subjects they have.
Collects the names of each subject and stores them in a list a.
Asks the user to input the maximum marks (max) for the subjects.
Grade Calculation:

Defines grade boundaries (O, A+, A, B+, B, C, P, and "Fail") based on predefined percentage ranges of max.
Iterates through each subject:
Asks the user to input the marks obtained for each subject (f).
Appends the marks to list k.
Determines the corresponding grade (xx) based on the marks entered.
Output Section:

Prints a marks card displaying each subject name, marks obtained, and the corresponding grade.
Overall Percentage and CGPA Calculation:

Calculates the overall percentage based on the total marks obtained across all subjects.
Converts the overall percentage into CGPA by dividing it by 9.5 (assuming a standard CGPA calculation method).
User Interaction:

Prompts the user to press any key to exit the program.
Example Use Case:
Assume the user enters:

Number of subjects (x) as 3.
Subject names as "Maths", "Physics", and "Chemistry".
Maximum marks (max) as 100.
Marks obtained for each subject.
The program will then:

Calculate grades (O, A+, A, etc.) for each subject based on the entered marks.
Display a marks card showing subject-wise marks and grades.
Compute the overall percentage and CGPA based on the entered data.
Code Notes:
The program uses lists (a, k, xx) to store subject names, marks, and grades respectively.
It utilizes loops (for loop) for iterating over subjects and collecting input data.
Conditional statements (if, elif, else) are used to determine grades based on predefined ranges.
Basic input/output functions (input() and print()) are employed for user interaction and displaying results.
