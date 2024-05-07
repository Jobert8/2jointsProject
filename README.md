# Root Finding Methods
This Java application provides a user-friendly graphical interface for computing the roots of a function using two common root-finding methods: the Bisection Method and the False Position Method.

## SDG (Sustainable Development Goal's)
1. Quality Education - This project contributes for providing a tool that can be used for educational purposes, helping students and learn understanding and apply numerical methods for solving equations.
2. Industry, Innovation, and Insfrastruture - This project promotes innovation by providing a sofrware tool that utilizes numerical methods for solving mathematical problems, contributing to advancement of thecnology in the field of computational mathematics.
3. Responsible Consumption and production - This project promotes responsible consumption by providing a software tool that allows users to efficiently solve mathematical problems, potentially reducing the need for paper-based calculations and minimizing resource consumption.

## Overview
Root finding is a fundamental problem in mathematics and computer science, often encountered in various scientific and engineering applications. This application simplifies the process of finding roots by providing an intuitive GUI where users can input a function, specify bounds, choose a root-finding method, and view the results in a table format.
## Features
* User-friendly GUI: Intuitive graphical interface for inputting function parameters and viewing results.
* Bisection Method: Compute roots using the Bisection Method, a simple and robust numerical method for finding roots of continuous functions.
* False Position Method: Compute roots using the False Position Method, also known as the Regula Falsi method, which is a more sophisticated variant of the Bisection Method.
* Table Display: Results displayed in a tabular format, including method used, iteration number, bounds, mid-point, function values at bounds and mid-point, and percent error.
* Customization: Users can specify the maximum number of iterations for the root-finding process.
## Requirements
* Java Development Kit (JDK) installed on your system.
* Basic understanding of Java programming language.
* Familiarity with Swing GUI library for building graphical interfaces in Java.
## Installation
* Clone or download this repository to your local machine.
* Open the project in your preferred Java Integrated Development Environment (IDE).
* Ensure that you have the necessary dependencies (Swing GUI library).
* Build and run the file.
## Usage
1. Launch the application.
2. Enter the function in terms of x in the designated text field.
3. Specify the lower and upper bounds for the root.
4. Enter the maximum number of iterations for the root-finding process.
5. Choose the root-finding method (Bisection or False Position).
6. Click the "Calculate" button to compute the root.
7. View the results displayed in the table.
## Example
Suppose you want to find the root of the function f(x) = x^2 - 4 using the Bisection Method with a lower bound of 0, upper bound of 3, and maximum iterations of 10. You would input the following values:

* Function: x^2 - 4
* Lower Bound: 0
* Upper Bound: 3
* Max Iterations: 10

After clicking "CalculateBisectionMethod," the program will display the root and the calculation details in the table.
