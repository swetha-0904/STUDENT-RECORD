# STUDENT-RECORD

**Overview:**

The **Student Record Management System** is a console-based application developed in C using Singly Linked Lists and File Handling. It enables efficient management of student records by allowing users to add, display, modify, delete, search, sort, save, and load student information dynamically.
The system automatically generates roll numbers, stores student details such as name and percentage, and maintains data persistence through file storage.

**Features:**

    • Add new student records 
    • Automatic roll number generation 
    • Display all student records 
    • Modify student details 
    • Delete records by roll number or name 
    • Search records by roll number or name 
    • Sort records by: 
        ◦ Name (A–Z) 
        ◦ Percentage (Highest–Lowest) 
    • Reverse display using recursion 
    • Save records to a file 
    • Load records from a file 
    • Delete all records 

**Concepts Used:**

    • C Programming 
    • Structures 
    • Singly Linked Lists 
    • Dynamic Memory Allocation (malloc, free) 
    • File Handling (fopen, fprintf, fscanf, fclose) 
    • Pointers 
    • Recursion 
    • Bubble Sort 
    • String Manipulation 

**Data Structure:**

typedef struct student
{
    int roll;
    char name[30];
    float per;
    struct student *next;
} STU;


**Learning Outcomes:**

This project demonstrates practical implementation of data structures and core C programming concepts, including linked list operations, memory management, file handling, searching, sorting, recursion, and modular programming.

**Future Enhancements:**

    • Attendance Management 
    • Fee Management 
    • Result Analysis 
    • Database Integration 
    • GUI-based Interface 

**Conclusion:**

This project provides a simple and efficient solution for managing student records while showcasing fundamental concepts of C programming, data structures, and file management in a real-world application.
