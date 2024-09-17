
# Gradescope Autograder Generator

  

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

  

## Description

  

This tool automatically generates autograders for programming assignments on Gradescope, supporting submissions in C++17, Java, and Python 3. Instructors can require submissions in a specific programming language or allow students to choose among the supported languages. The tool allows multiple problems to be included in the same assignment.

  

For each problem, students submit a .cpp, .java, or .py file with the required filename. The code must read input from standard input (stdin) and output the result to standard output (stdout). C++ and Java submissions must contain a main function, and Java submissions must implement the solution in a class with the specified name.

  

The autograder automatically reports compilation issues to students. It also includes a timeout for test cases to handle infinite loops or excessively long execution times.

  

### Demo

  

Check out the live demo here: [https://cise.ufl.edu/~p.gupta/gradescope-autograder-generator/]([https://cise.ufl.edu/~p.gupta/autograder-generator/](https://cise.ufl.edu/~p.gupta/gradescope-autograder-generator/))

  

## Table of Contents

  

-  [Installation](#installation)

-  [How It Works](#how-it-works)

-  [License](#license)

-  [Contact](#contact)

  

## Installation

  

1. Clone or download this repository.

2. Host the app on any web server.

3. Open the app in a modern web browser.

  

## How It Works

  

The tool generates an autograder zip file for Gradescope based on the instructor's specifications:

  

-  **Multiple Problems:** Add multiple problems to a singe assignment.

-  **Programming Languages:** Specify required filenames for C++, Java, and Python submissions.

-  **Test Cases:** Add test cases with custom input, expected output, point value, and visibility.

-  **Language Requirement:** Require a specific language or allow students to choose among supported languages.

  

When students submit their code, the autograder:

  

-  **Compiles Code:** Automatically compiles submissions and reports any compilation issues to students.

-  **Runs Tests:** Executes the code against provided test cases.

-  **Handles Infinite Loops:** Implements timeouts for test cases to prevent infinite loops from stalling the grading process.

-  **Provides Feedback:** Reports results back to students, including compilation errors and test case outcomes.

  

## License

  

This project is licensed under the [MIT License](LICENSE).

  

## Contact

  

If you have any questions or suggestions, feel free to contact me at [p.gupta@ufl.edu](mailto:p.gupta@ufl.edu).
