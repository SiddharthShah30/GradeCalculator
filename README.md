# README

## Overview
This project contains utility functions to calculate class performance metrics and generate student feedback. The code defines the following functions:

### 1. `getAverage(scores)`
- **Purpose**: Calculates the average score from a list of scores.
- **Parameters**:
  - `scores` (array): An array of numerical scores.
- **Returns**: The average of the input scores.

### 2. `getGrade(score)`
- **Purpose**: Determines the grade corresponding to a numerical score based on predefined ranges.
- **Parameters**:
  - `score` (number): The score to evaluate.
- **Returns**: A grade (`A++`, `A`, `B`, `C`, `D`, `F`) as a string.

### 3. `hasPassingGrade(score)`
- **Purpose**: Checks if a given score is passing (not an `F`).
- **Parameters**:
  - `score` (number): The score to evaluate.
- **Returns**: A boolean value indicating whether the score is passing.

### 4. `studentMsg(totalScores, studentScore)`
- **Purpose**: Generates a feedback message for a student, including the class average, their grade, and whether they passed.
- **Parameters**:
  - `totalScores` (array): An array of all students' scores.
  - `studentScore` (number): The individual student's score.
- **Returns**: A string message with the student's performance and class average.

### Example Usage
```javascript
console.log(studentMsg([92, 88, 12, 77, 57, 100, 67, 38, 97, 89], 37));
```
- **Output**:
  ```
  Class average: 71.4. Your grade: F. You failed the course.
  ```

## Features
- Computes average scores for a class.
- Provides letter grades based on numerical scores.
- Indicates pass/fail status.
- Generates detailed student feedback.

## How to Use
1. Include the functions in your JavaScript code.
2. Pass the required inputs to the desired functions.
3. Use the returned values to display or process performance data as needed.

## Notes
- Ensure all scores are valid numerical inputs.
- Grade thresholds are:
  - **A++**: 100
  - **A**: 90-99
  - **B**: 80-89
  - **C**: 70-79
  - **D**: 60-69
  - **F**: Below 60

## License
This code is free to use and modify for personal or educational purposes.

