# finance-tracker-project

## Personal Finance Tracker CLI
A command-line interface (CLI) application built with Python for tracking personal income and expenses. This tool allows users to manage their financial transactions, view summaries over specific periods, and visualize their financial data.

Key Features
Add Transactions: Easily record new income or expense transactions with details like date, amount, category, and a description.

View History: Filter and view all transactions within a specified date range.

Financial Summary: Automatically calculates and displays a summary of total income, total expenses, and net savings for the selected period.

Data Visualization: Generate and display a line plot of income vs. expenses over time using matplotlib to visually track financial trends.

Persistent Storage: All transaction data is saved locally to a finance_data.csv file, ensuring your data is preserved between sessions.

Technology Stack
Language: Python 3

Libraries:

Pandas: For efficient data manipulation and management.

Matplotlib: For generating data visualizations.

Setup and Installation
To run this project locally, follow these steps:

1. Clone the repository:

Bash

git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
2. Create a virtual environment (recommended):

Bash

# For Windows
python -m venv venv
venv\Scripts\activate

# For macOS/Linux
python3 -m venv venv
source venv/bin/activate
3. Install the required libraries:
Create a file named requirements.txt in your project's root directory and add the following lines:

pandas
matplotlib
Then, run the following command to install them:

Bash

pip install -r requirements.txt
Usage
To start the application, run the main.ipynb notebook or convert it to a Python script (.py) and execute it from your terminal:

Bash

python main.py
Once the application is running, you will be presented with a menu of options:

1. Add a new transaction
2. View transactions and summary within a date range
3. Exit
To add a transaction, choose option 1 and follow the on-screen prompts for the date, amount, category (Income/Expense), and description.

To view transactions, choose option 2. You will be asked to provide a start and end date. The application will display a table of transactions and a financial summary. You will then have the option to generate a plot of the data.

To close the application, choose option 3.

File Structure
.
├── finance_data.csv    # Default CSV file for storing transaction data
├── main.ipynb          # Jupyter Notebook containing the main application logic
└── README.md           # Project documentation
