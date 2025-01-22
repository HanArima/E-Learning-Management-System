# E-Learning-Management-System

This project is a University Learning Management System implemented in C++. It allows administrators to manage courses and students, and provides students with access to their registered courses.

## Features

- Add, Edit, Delete Courses
- Add, Edit, Delete Students
- Register and Unregister Courses for Students
- View All Courses and Students
- Save and Load Data from Files

  ## Keys Learnings

### 1. OOPS Concept
- Encapsulation:
  - Grouping data and functions into manageable chunks, such as:
  - Course-related validation (isValidCourseCode, isValidSemester).
  - Student-related functions (isValidStudentName, addStudent).
  - Keeping functionality modular improves maintainability and clarity.
- Abstraction:
    - Simplifying user interactions by hiding implementation details.
    - Example: The AddCourse, EditCourse, and DeleteCourse functions abstract complex checks and logic.

### 2. File I/O Operations:
  - Learned how to read from and write to files using ifstream and ofstream for persistent data storage.
  - Emphasized the importance of saving program state (saveCourses, loadStudents).

### 3. Error Handling:
  - Managed input validation and program flow even when users provide incorrect data (e.g., cin.fail() checks).
