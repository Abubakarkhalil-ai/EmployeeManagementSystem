# Employee Management System (C# .NET)

##Project Overview
This project is a console-based Employee Management System developed in C# .NET. The system allows users to store and manage employee profiles and their leave records. It supports adding employees, searching employees, recording leave applications, and viewing employee leave history.
The project focuses on implementing a custom data structure for efficient data storage and searching.
---

## Features
- Add new employee
- Search employee by ID
- Search employee by name
- Add leave record to employee
- View employee leave history
- Display all employees
- Load employee data from file
- Save employee data to file

---

## Data Structure Used
A Binary Search Tree (BST) is used to store employee records based on Employee ID.

### Why BST?
- Efficient searching compared to linear structures
- Maintains sorted order
- Supports fast insert and search operations

### Time Complexity
Operation - Average Case - Worst Case 
Insert -> O(log n)    -  O(n)   
Search -> O(log n)    -  O(n) 
