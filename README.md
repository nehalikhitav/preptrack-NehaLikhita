# PrepTrack – Student Placement Readiness Tracker

## Project Overview

PrepTrack is a Python-based console application designed to evaluate a student's placement readiness.

The application collects student details, validates the entered information, records practice scores for seven days, analyzes the student's performance, and determines their placement readiness based on predefined eligibility conditions.

The system also provides the student's primary blocker and recommends the next action to improve placement readiness.

## Features Implemented

- Collects student details such as:
  - Student Name
  - Registration Number
  - Graduation Year
  - Attendance Percentage
- Validates user inputs.
- Accepts project completion status.
- Accepts profile verification status.
- Records practice scores for 7 days.
- Supports absent days using `-1`.
- Calculates:
  - Total Score
  - Average Score
  - Attempted Days
  - Absent Days
  - Passed Days
  - Failed Days
- Classifies practice performance into:
  - Strong
  - Satisfactory
  - Needs Improvement
  - Critical
- Identifies the highest and lowest scores.
- Records the first critical score.
- Checks placement eligibility.
- Displays the final placement readiness status.
- Provides the primary blocker and recommended next action.

## Eligibility Conditions

A student is considered ready for a mock interview when:

- Graduation year is between 2025 and 2027.
- Attendance is at least 75%.
- At least 6 practice sessions are completed.
- Average score is at least 70.
- No critical score is recorded.
- At least 4 days are passed.
- Required project is completed.
- Student profile is verified.

## Python Concepts Used

- Variables
- Data Types
- User Input and Output
- Type Casting
- Arithmetic Operators
- Comparison Operators
- Logical Operators
- `if`, `elif`, and `else`
- `for` loop
- `while` loop
- `continue` statement
- Boolean values
- Input Validation
- f-strings
- Conditional Logic

## Tools Used

- Python
- Antigravity
- VS Code / Python IDE

## How to Run

### Prerequisites

Make sure Python 3.x is installed on your system.

### Steps

1. Clone or download the project.
2. Open the project folder.
3. Open the Python file in your preferred IDE.
4. Run the Python program.
5. Enter the requested student details.
6. Enter practice scores for seven days.
7. Use `-1` when the student is absent.
8. View the final PrepTrack report.

## Sample Input

```text
Enter student name: Rahul
Enter registration number: REG101
Enter graduation year: 2026
Enter attendance percentage: 85

Has the student completed the required project? Enter yes or no: yes

Is the student profile verified? Enter yes or no: yes

Enter Day 1 score from 0 to 100, or -1 for absent: 80
Enter Day 2 score from 0 to 100, or -1 for absent: 75
Enter Day 3 score from 0 to 100, or -1 for absent: 72
Enter Day 4 score from 0 to 100, or -1 for absent: 85
Enter Day 5 score from 0 to 100, or -1 for absent: 78
Enter Day 6 score from 0 to 100, or -1 for absent: 80
Enter Day 7 score from 0 to 100, or -1 for absent: 82
