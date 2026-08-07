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

- Python – Used to develop the application and implement the program logic.
- Antigravity – Used as the development/coding tool to build, review, and test the project.

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

## Test Result Summary

The application was tested with different input conditions, including valid and invalid inputs, absent practice days, low scores, insufficient practice attempts, low attendance, incomplete projects, and unverified profiles.

The application successfully validated user inputs, processed practice scores, calculated performance statistics, checked eligibility conditions, and generated the appropriate final status and recommended action.

## Individual Contribution

- Developed the PrepTrack application.
- Implemented student data collection and validation.
- Developed seven-day practice score processing.
- Implemented score classification and performance calculations.
- Developed placement eligibility logic.
- Implemented final status, blocker, and next-action generation.
- Tested the application with different scenarios.
- Used Antigravity during the development and code review process.

## Code Review Completed

**Status: Completed**

The code was reviewed for:

- Input validation
- Conditional logic
- Loop implementation
- Score calculation
- Eligibility conditions
- Code readability
- Output formatting

The review identified areas for future improvement, such as using functions for modularity, improving variable initialization, and removing unused variables.

## Feedback Received

The project demonstrates a clear understanding of Python fundamentals and problem-solving.

The application has a practical use case for tracking student placement preparation. The input validation, performance classification, eligibility checking, and final report make the application easy to understand and use.

Future improvements can include:

- Adding a graphical user interface (GUI).
- Storing student records in a database.
- Exporting reports to Excel or PDF.
- Adding login and authentication.
- Adding charts for performance analysis.
- Creating a web-based version of PrepTrack.

## Project Status

**Completed**

The current version successfully performs student placement readiness evaluation through a Python console-based application.
