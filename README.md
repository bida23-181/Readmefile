# Student Management Program

## Project Purpose

The **Student Management Program** is a command-line Python application designed to help manage student records, including their names, subjects, and grades. The program allows the user to:

- Add new students with multiple subjects and grades.
- Update grades for existing students.
- Remove students from the system.
- View grades for specific subjects.
- Search for a student’s grades.
- Sort students by name or average grade.

This program provides a simple way to manage student data and is ideal for educational purposes, small-scale grade tracking, or as a starting point for building more advanced student management systems.

## Features

- **Add Student**: Allows you to add a new student, input subjects, and assign grades.
- **Update Grades**: Modify a student's grade for a particular subject.
- **Remove Student**: Delete a student’s record from the system.
- **View Subject Grades**: View all students' grades for a specific subject.
- **Search Student**: Search for a student's grades by name.
- **Sort Students**: Sort students either by their name (alphabetically) or by their average grade (highest to lowest).
- **Error Handling**: Handles invalid inputs (such as non-numeric grades or empty values) gracefully.

## How to Run the Program

1. **Install Python**:  
   This project requires Python 3.x. Make sure Python is installed on your machine. You can download Python from the official website.

2. **Download the Code**:  
   Download the Python script file to your computer.

3. **Running the Program**:  
   - Open a terminal or command prompt.
   - Navigate to the directory where the file is located.
   - Run the program 
   - The program will prompt you to enter the number of students and guide you through various menu options.

4. **Menu Options**:  
   After starting the program, you will see a menu with the following options:
   1. Add Student
   2. Update Grades
   3. Remove Student
   4. View Subject Grades
   5. Search Student
   6. Sort Students by Name
   7. Sort Students by Average Grade
   8. Exit
   

## Features and Usage Details

- **Adding a New Student**:  
   - You will be asked for the student's name and the number of subjects.
   - For each subject, input the subject name and the grade.

- **Updating Grades**:  
   - You can update the grade for an existing student in a specific subject.

- **Removing a Student**:  
   - This option allows you to delete a student's record from the system.

- **Viewing Subject Grades**:  
   - This feature allows you to view all students' grades for a specific subject (e.g., Math, Science, etc.).

- **Searching for a Student**:  
   - You can search for a student by name to view their grades.

- **Sorting Students**:  
   - Sort students alphabetically by name or by their average grade (highest to lowest).

- **Exiting the Program**:  
   - Exit the program by selecting the exit option from the menu.

## Error Handling

- **Invalid Grade Input**:  
   If you enter a grade that is not numeric or is outside the valid range (0–100), the program will prompt you to re-enter a valid grade.

- **Empty Inputs**:  
   If a user provides an empty student name or subject name, the program will prompt the user to enter a non-empty value.

- **Student Not Found**:  
   If you try to update or remove a student who doesn't exist, the program will display a "Student not found" error message.

- **Invalid Menu Choices**:  
   If an invalid menu choice is entered, the program will notify the user and prompt them to enter a valid option.

## Testing and Validation

The program has been tested thoroughly with the following cases:

- Adding, updating, and removing students.
- Viewing grades for specific subjects.
- Searching for students by name.
- Sorting students by name and average grade.
- Handling invalid inputs .

## Known Limitations

- **No Data Persistence**:  
   Once the program is exited, all student records are lost.

- **Duplicate Subject Names**:  
   There is no validation for duplicate subject names when adding grades for a student.

- **Exiting During Ongoing Operations**:  
   Exiting the program during an ongoing operation currently doesnt prompt for confirmation. A fix for this is planned for future releases.
