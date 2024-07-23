# Student Management System

## Overview

The Student Management System is a Python-based application designed to manage student information, course registration, and grade tracking. It provides functionalities to add students and courses, register students for courses, calculate GPAs, rank students, search students by grade, and generate transcripts.

## Features

- **Add Student**: Add a new student to the system.
- **Add Course**: Add a new course to the system.
- **Register Student for Course**: Register a student for a course and input their grade.
- **Calculate Ranking**: Calculate and display the ranking of students based on their GPA.
- **Search by Grade**: Search for students by grade within a specific course.
- **Generate Transcript**: Generate a transcript for a specific student.

## Prerequisites

- Python 3.x

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Bonaparte003/grade-book-app_Bonaparte_Avellin.Ugit
   cd student-management-system
   ```

2. Ensure you have Python3 installed.

## Project Structure

```
student-management-system/
│
├── data/
│   ├── courses.txt
│   ├── registered_courses.txt
│   └── students.txt
│
├── main.py
├── grade_book.py
├── student.py
└── course.py
```

## Data Files

- **courses.txt**: Stores course information in the format `course_name,trimester,credits`.
- **registered_courses.txt**: Stores registered courses in the format `student_email,course_name,grade`.
- **students.txt**: Stores student information in the format `email,names,id`.

## Usage

1. Navigate to the project directory:
   ```bash
   cd student-management-system
   ```

2. Run the application:
   ```bash
   python main.py
   ```

3. Follow the on-screen instructions to use the various features of the application.



## Contributing

Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.