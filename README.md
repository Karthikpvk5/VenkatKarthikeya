 Simple Budget Tracker

This is a simple command-line budget tracker written in Python. It allows you to record income and expenses, view your budget, and analyze your expenses by category. Data is stored in a `budget_data.json` file for persistence.

 Features

* **Add Transactions:** Record income and expenses with categories, descriptions, and amounts.
* **View Budget:** Calculate and display the remaining budget (income minus expenses).
* **Expense Analysis:** Analyze expenses by category and display the total spent in each category.
* **Data Persistence:** Data is stored in a JSON file (`budget_data.json`) to preserve data between sessions.
* **Command-Line Interface:** Easy-to-use command-line menu.

 Getting Started

1.  **Clone the repository (if applicable):**
    ```bash
    git clone [YOUR_REPOSITORY_URL]
    ```
    (Replace `[YOUR_REPOSITORY_URL]` with your repository's URL if you are hosting this code on Github.)
2.  **Save the Python code:** Save the provided Python code as a `.py` file (e.g., `budget_tracker.py`).
3.  **Run the script:**
    ```bash
    python budget_tracker.py
    ```
4.  **Interact with the menu:** Follow the prompts in the command-line menu to add transactions, view your budget, and analyze expenses.

 Usage

1.  **Add Transaction (Option 1):**
    * Enter `1` and press Enter.
    * Specify whether it's "Income" or "Expense".
    * Enter the category (e.g., "Salary", "Groceries").
    * Enter a description (e.g., "Monthly salary", "Weekly shopping").
    * Enter the amount.
2.  **View Budget (Option 2):**
    * Enter `2` and press Enter.
    * The remaining budget will be displayed.
3.  **Expense Analysis (Option 3):**
    * Enter `3` and press Enter.
    * A breakdown of expenses by category will be displayed.
4.  **Exit (Option 4):**
    * Enter `4` and press enter.

 Data Storage

* The program uses a `budget_data.json` file to store transaction data. This file is created automatically when you run the script for the first time.
* The json file will store the transaction in the following format:
    ```json
    [
        {
            "type": "income",
            "category": "Salary",
            "description": "Monthly salary",
            "amount": 3000.0
        },
        {
            "type": "expense",
            "category": "Groceries",
            "description": "Weekly shopping",
            "amount": 100.0
        },
        ...
    ]
    ```

 Potential Improvements

* **Date Tracking:** Add date tracking to transactions.
* **User Interface:** Implement a graphical user interface (GUI) for a better user experience.
* **Error Handling:** Improve error handling for invalid input.
* **Reporting:** Add more detailed reporting features, such as monthly or yearly summaries.
* **Database Integration:** Integrate with a database for more robust data management.
* **Input Validation:** Add more robust input validation.

## Contributing

Feel free to submit pull requests with improvements or bug fixes.

## Author

[Venkat karthikeya/Karthikpvk5]
