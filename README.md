# Enhanced Student Record Management System

This project is an Enhanced Student Record Management System implemented in C++. The system provides various functionalities to manage student records including entering data, showing data, searching data, updating data, deleting data, saving data to a file, exporting data to CSV, and showing statistics.

## Features

- **Enter Data**: Add new student records to the system.
- **Show Data**: Display all student records in a tabular format.
- **Search Data**: Find a specific student record by roll number or name.
- **Update Data**: Modify the details of an existing student record.
- **Delete Data**: Remove all student records from the system.
- **Save Data to File**: Save all student records to a text file.
- **Export Data to CSV**: Export all student records to a CSV file.
- **Show Statistics**: Display statistics about the students such as the total number of students, students per course, and students per class.
- **Quit**: Exit the program while saving the data to a file.

## Requirements

- A C++ compiler (e.g., g++, MinGW)
- C++11 standard or later

## Installation

1. Clone the repository or download the source code files.
2. Compile the code using a C++ compiler.


// EXAMPLES::
Press 1 to Enter data
Press 2 to Show data
Press 3 to Search data
Press 4 to Update data
Press 5 to Delete data
Press 6 to Save data to file
Press 7 to Export data to CSV
Press 8 to Show statistics
Press 9 to Quit
//INPUT: ->
How many students do you want to enter?
2

Enter the Data of student 1

Enter Roll NO: 1
Enter Name: John Doe
Enter Class: 10
Enter Course: Science
Enter Mobile NO: 1234567890
Enter Admission Year: 2020

Enter the Data of student 2

Enter Roll NO: 2
Enter Name: Jane Smith
Enter Class: 12
Enter Course: Arts
Enter Mobile NO: 0987654321
Enter Admission Year: 2021
//OUTPUT:->
Roll NO   Name                Class     Course          Mobile NO       Admission Year
---------------------------------------------------------------------------------------
1         John Doe            10        Science         1234567890      2020
2         Jane Smith          12        Arts            0987654321      2021


