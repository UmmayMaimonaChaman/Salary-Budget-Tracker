# Salary Budget Tracker

A simple **Python-based personal budget tracker** created as part of my Python learning journey.

The program allows users to record their income and expenses, view their financial summary, and review previously recorded transactions.

## Features

* Add income transactions
* Add expense transactions
* View total income
* View total expenses
* Calculate the current balance
* View all recorded transactions
* Basic input validation
* Simple command-line interface

## How It Works

Transactions are stored as dictionaries inside a Python list. Each transaction contains:

* **Type** — income or expense
* **Amount** — transaction value
* **Description** — short description of the transaction

The program provides a menu-driven interface that allows users to perform different operations until they choose to exit.

## Main Functions

### `add_transaction()`

Records a new income or expense and adds it to the transaction list.

### `view_summary()`

Calculates and displays:

* Total income
* Total expenses
* Net balance

### `view_transactions()`

Displays all recorded transactions along with their type, amount, and description.

### `main()`

Runs the command-line interface and manages user interaction through a continuous menu.

## Getting Started

### Requirements

* Python 3.x

### Run the Program

Clone the repository:

```bash
git clone <your-repository-url>
```

Navigate to the project directory:

```bash
cd Salary-Budget-Tracker
```

Run the Python script:

```bash
python <filename>.py
```

## Example Workflow

```text
1. Add Income
2. Add Expense
3. View Summary
4. View Transactions
5. Quit
```

Users can repeatedly add transactions and review their financial summary during a session.

## Project Purpose

This project was developed as a beginner Python project to practice:

* Functions
* Lists and dictionaries
* Loops
* Conditional statements
* User input
* Basic input validation
* Command-line program design

## License

This project is available for learning and educational purposes.
