# Personal Expense Tracker

## Project Overview

The Personal Expense Tracker is a Python-based project that helps users record, organize, and analyze their daily expenses. It uses the Pandas and NumPy libraries to process expense data stored in a CSV file and generate useful financial summaries.

## Features

- Load expense data from a CSV file
- Calculate total expenses
- Calculate average expenses
- Find the highest expense
- Find the lowest expense
- Generate category-wise expense summary
- Generate monthly expense summary
- Save the summary to a CSV file

## Technologies Used

- Python
- Pandas
- NumPy
- Google Colab

## Project Structure

```
Personal_Expense_Tracker/
│── expense.csv
│── summary.csv
│── README.md
```

## Dataset

The project uses a CSV file named **expense.csv** with the following columns:

- Date
- Category
- Description
- Amount

## Output

The program displays:

- Total Expense
- Average Expense
- Highest Expense
- Lowest Expense
- Category-wise Expense Summary
- Monthly Expense Summary
- Confirmation message after saving the summary file

## How to Run

1. Open the project in Google Colab.
2. Upload the `expense.csv` file.
3. Run all code cells in order.
4. View the results in the output.
5. The program will create a `summary.csv` file containing the category-wise expense summary.

## Sample Output

```
Total Expense: 2800
Average Expense: 933.33
Highest Expense: 2000
Lowest Expense: 300

Category-wise Expense
Food        500
Shopping   2000
Transport   300

Monthly Expense
2026-08    2800

Summary File Saved Successfully.
```

## Future Improvements

- Add charts and graphs for expense visualization
- Build a graphical user interface (GUI)
- Connect the project to a database
- Add expense filtering by date and category

## Author

**Neha**  
BS Computer Science  
University of Narowal
