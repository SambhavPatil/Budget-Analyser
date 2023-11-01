# Budget-Analyser

## Overview
The "Budget Analyser," is a C++ program that allows users to manage their monthly budgets and expenses. This program helps users track their spending across various categories and provides a report showing the difference between their budgeted and actual expenses.

## Features
- Input your budget for each category, including housing, utilities, household, transportation, food, medical, insurance, entertainment, clothing, and miscellaneous expenses.
- Input your actual monthly expenses for the same categories.
- View a detailed report that shows the budgeted amount, actual expenses, and the over/under difference for each category.
- Save the results to a text file for future reference.

## Usage
1. Compile the program using a C++ compiler. For example, you can use g++:

   ```bash
   g++ budget_analyser.cpp -o budget_analyser
   ```

2. Run the program:

   ```bash
   ./budget_analyser
   ```

3. Follow the on-screen prompts to input the number of months you want to analyze and your monthly budget and expenses for each category.

4. The program will generate a report on the console and save the results to a text file named "results.txt" in the same directory.

## File Description
- `main.cpp`: The C++ source code for the Expense Management System.
- `budget.bin`: Binary file to store budget information.
- `expenses.bin`: Binary file to store expense information.
- `results.txt`: Text file where the program saves the budget analysis results.
