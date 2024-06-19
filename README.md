# Salary-Budget-Tracker
Python


This Python script is designed to function as a budget tracker, enabling users to manage and monitor their personal finances efficiently. The program features a straightforward interface through which users can add transactions, view summaries, and list all recorded transactions. Transactions are categorized as either income or expenses, each stored with an associated amount and description in a list.

The main functionalities are organized into functions:

add_transaction: This function records a transaction by appending a dictionary containing the transaction type (income or expense), amount, and description to the transactions list.

view_summary: It calculates and displays the total income, total expenses, and the net balance by iterating over the transactions list, summing up income and expense amounts separately.

view_transactions: This function prints out all recorded transactions in a user-friendly format, showing the transaction type, amount, and description.

The main function operates the user interface, presenting a menu with options to add income, add expenses, view summary, view transactions, or quit the program. It uses a loop to continually display the menu until the user decides to exit, allowing multiple interactions in a single session. Input validation is incorporated to handle errors gracefully, ensuring users enter valid amounts for transactions.

This budget tracker script provides a simple yet effective tool for users to keep track of their financial activities, helping them maintain an overview of their financial status.
