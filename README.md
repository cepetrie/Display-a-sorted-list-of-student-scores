# Display-a-sorted-list-of-student-scores
Console
Welcome to the Student Scores Application.

Enter number of students to enter: 4

Student 1 last name: Steelman
Student 1 first name: Andrea
Student 1 score: 95

Student 2 last name: Michaels
Student 2 first name: Joe
Student 2 score: 92

Student 3 last name: Lowe
Student 3 first name: Doug
Student 3 score: 82

Student 4 last name: Michaels
Student 4 first name: Mike
Student 4 score: 93

Lowe, Doug: 82
Michaels, Joe: 92
Michaels, Mike: 93
Steelman, Andrea: 95

Operation:
This application accepts the last name, first name, and score for one or more students and stores the results in an array. Then, it prints the students and their scores in alphabetical order by last name.

Specifications:
The program should implement a class named Student that stores the last name, first name, and score for each student. 
This class should implement the IComparable interface so the students can be sorted by name. 
If two students have the same last name, the first name should be used to determine the final sort order.

The program should use an array to store the Student objects. Then, it should sort the array prior to printing the student list. 

Validate the input so the user can enter only a positive integer for the number of students, the last or first name can’t be an empty string, and the score is an integer from 0 to 100. 

