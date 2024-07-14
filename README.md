Finance Tracker
Overview
The Finance Tracker is a Python-based application for managing personal finances. It allows users to add transactions, view transactions within a specified date range, and visualize their income and expenses over time. The data is stored in a CSV file.

Features
Add new transactions with date, amount, category, and description.
View transactions and summaries within a specified date range.
Plot income and expenses over time.
Requirements
Python 3.x
pandas
matplotlib

Adding a New Transaction
Select option 1 from the menu.
Enter the date of the transaction in the format dd-mm-yyyy or press Enter to use today's date.
Enter the amount of the transaction.
Enter the category of the transaction (e.g., Income, Expense).
Enter a description for the transaction.
Viewing Transactions and Summary
Select option 2 from the menu.
Enter the start date in the format dd-mm-yyyy.
Enter the end date in the format dd-mm-yyyy.
The transactions within the specified date range will be displayed along with a summary of total income, total expenses  , and net savings.
Optionally, choose to plot the transactions over time.
Exiting the Application
Select option 3 from the menu.
The application will exit after a brief delay.
Code Structure
CSV Class: Manages CSV file operations such as initializing the CSV file, adding entries, and retrieving transactions within a date range.
add() Function: Handles adding new transactions by prompting the user for details.
plot_transactions(df) Function: Plots income and expenses over time using matplotlib.
main() Function: The main loop of the application, presenting the menu and handling user choices.
