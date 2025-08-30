Software Testing Project: sCalc Web Calculator
This repository contains the testing documentation for sCalc, a web-based calculator application. This project was undertaken to perform a comprehensive quality assurance assessment of the application's features.

Tester: Bharath
Project Date: July 2025

1. Project Overview
The primary objective of this project was to conduct detailed manual testing on the sCalc application. The goal was to verify its functionality, identify defects, and ensure the application meets expected quality standards. The testing process involved:

Test Case Design: Creating detailed, structured test cases covering all visible application features.

Test Execution: Manually executing the test cases against the live application.

Defect Reporting: Documenting all identified bugs and inconsistencies with clear, actionable details.

Application Under Test (AUT)
Application Name: sCalc

URL: https://dunizb.github.io/sCalc/

2. Testing Scope
The testing scope included a thorough evaluation of the following features:

Core Arithmetic Operations: Addition, Subtraction, Multiplication, and Division.

Advanced Operations: Order of Operations (BODMAS/PEMDAS) and Percentage (%) calculations.

Auxiliary Functions: Backspace (←) and Clear (CE) functionalities.

Usability & Edge Cases: Handling of decimals, negative numbers, and chained operations.

Error Handling: System response to invalid inputs, such as division by zero and improper operational sequences.

3. Test Execution Summary
The test suite consists of 40 test cases designed to ensure comprehensive coverage of the application's functionality.


Metric                                                         Count

Total Test Cases Executed                                       40

✅ Passed                                                       31

❌ Failed                                                       9

Pass Rate                                                      77.5%

While the majority of basic tests passed, several critical and major defects were discovered in the application's core logic, rendering it unsuitable for production release.

4. Summary of Critical Defects Found
The following high-priority bugs were identified during test execution:

BUG 1->Order of Operations (BODMAS) Ignored: The calculator does not follow the standard mathematical order of operations. It        processes all calculations sequentially from left to right, leading to incorrect results for complex expressions              (e.g., 5 + 3 * 2 results in 16 instead of 11)

BUG 2->Percentage (%) Function is Unstable: The percentage key is fundamentally flawed. It fails for multiplication and              subtraction, and its use makes the equals (=) key malfunction, resetting the calculation to zero.

BUG 3->Multiplication with Negative Numbers Fails: The calculator cannot multiply with negative numbers. It incorrectly              performs subtraction instead (e.g., 7 * -3 results in 4 instead of -21)

BUG 4->Incorrect Handling of Double Negatives: The calculator fails to correctly process double negative signs in subtraction        (e.g., 5 - - 2 results in 3 instead of 7).

5. Testing Artifacts
This repository contains the complete documentation for this testing project
📊 View Test Execution Report Spreadsheet
https://github.com/BHARATHMM562/PRODIGY_ST_01/blob/main/PRODIGY_ST_01.xlsx
This file contains the raw test execution data in a spreadsheet format.

This thorough testing process has successfully identified key areas for improvement and provided clear, actionable feedback for the development team.




## My Prodigy Infotech Internship Task Index

This repository is part of a series of projects completed during the Prodigy Infotech Software Testing Internship. You can explore the other tasks in the links below:

* **Task 02**: [https://github.com/BHARATHMM562/PRODIGY_ST_02](https://github.com/BHARATHMM562/PRODIGY_ST_02)
* **Task 03**: [https://github.com/BHARATHMM562/PRODIGY_ST_03](https://github.com/BHARATHMM562/PRODIGY_ST_03)
* **Task 04**: [https://github.com/BHARATHMM562/PRODIGY_ST_04](https://github.com/BHARATHMM562/PRODIGY_ST_04)
* **Task 05**: [https://github.com/BHARATHMM562/PRODIGY_ST_05](https://github.com/BHARATHMM562/PRODIGY_ST_05)

Feel free to browse through the code and documentation in each repository.
