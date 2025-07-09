# Student-Record-Management-System-C-Linked-List-Project
A console-based Student Record Management System developed in C++ using singly linked lists. This project supports various operations like adding, deleting, searching, updating, sorting by GPA, and counting student records. It also handles duplicate ID insertion by offering options to update existing records. Designed as a Data Structures and Algorithms (DSA) mini project, it demonstrates the practical application of linked list operations and merge sort in a real-world scenario.
Project Details  
  
• Language Used: C++  
C++ is a versatile, object-oriented programming language that supports features like classes, dynamic memory allocation, and user-defined data types. Its efficiency and control over memory management make it ideal for implementing fundamental data structures like linked lists. 
• Data Structure Used: Singly Linked List 
A singly linked list is a linear data structure where each node contains: 
•	A unique student ID 
•	The student’s name 
•	The GPA (Grade Point Average) 
•	A pointer to the next node in the list 
This structure allows dynamic insertion, deletion, and traversal of student records without the need for contiguous memory allocation.  

• Operations Implemented  
 
1. Insert: 
Adds a new student record at the end of the linked list. If the entered ID already exists, the system notifies the user and offers two choices: 
•	Update the existing record (name/GPA) 
•	Cancel the insertion 
 
2.	Search: 
Searches for a Student by ID. If found, the system displays the student’s details; otherwise, it notifies that the record was not found. 
 
3.	Update: 
Allows modification of a student's name, GPA, or both after the student is found using their ID. 
 
4.	Delete: 
Removes a student record by ID from the linked list. 
Handles cases like: 
•	Deleting the head node 
•	Deleting a middle or tail node 
•	Handling an empty list gracefully 
 
5.	Display All (Traversal) 
Displays all student records in a formatted table by traversing the list from head to tail. 
 
6.	Sort by CGPA: Sorts the entire list in ascending order of GPA using merge sort, which is efficient for linked lists. 
 
7.	Count Students: Traverses the list and returns the total number of student records stored. 

# References  
 
1.	Object-Oriented Programming with C++ – E. Balagurusamy (For understanding class structure, dynamic memory management, and object-oriented principles in C++) 
 
2.	Data Structures Through C++ – Yashavant Kanetkar (Helpful in implementing linked lists, traversal techniques, and sorting algorithms like merge sort) 
 
3.	GeeksforGeeks – https://www.geeksforgeeks.org 
(Used for understanding linked list operations, node manipulation, and sorting linked lists efficiently) 
 
4.	cplusplus.com – https://www.cplusplus.com 
(For standard C++ library references, I/O stream usage, and syntax clarification) 
 
5.	Stack Overflow – https://stackoverflow.com 
(Community solutions and discussions helped debug specific issues during development) 
 
6.	W3Schools C++ Tutorial – https://www.w3schools.com/cpp/ (Basic C++ concepts, input/output functions, and control statements) 
