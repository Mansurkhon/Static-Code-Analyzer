# Code Analyzer

The Code Analyzer is a Python script that helps you identify and rectify common coding style violations in your Python code. It performs various checks and generates warnings for violations such as line length, indentation, semicolon usage, comments, and more.

## Features

- Checks for lines that are too long (S001)
- Ensures proper indentation (S002)
- Identifies unnecessary semicolons (S003)
- Requires at least two spaces before inline comments (S004)
- Detects TODO comments (S005)
- Detects excessive blank lines (S006)
- Detects too many spaces after function or class definitions (S007)
- Validates class names for CamelCase (S008)
- Validates function names for snake_case (S009)
- Validates argument names for snake_case (S010)
- Validates variable names for snake_case (S011)
- Identifies default argument values that are mutable (S012)
