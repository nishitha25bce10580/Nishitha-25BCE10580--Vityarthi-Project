# Nishitha-25BCE10580--Vityarthi-Project
# Personal Budget Manager

# 📖 Overview
A simple, command-line Python application designed to help users track their income and expenses, set monthly spending limits (budgets), and visualize their financial trends. It solves the real-life problem of disorganized personal finance management.

# ✨ Key Features (Functional Modules)
1.  **Data Input & Processing (CRUD):** Log new income and expense transactions with category, amount, date, and description.
2.  **Goal Setting & Tracking:** Set and track monthly budget limits for various expense categories, providing alerts when over budget.
3.  **Reporting & Analytics:** Generate visual reports (Pie Charts and Bar Charts) to analyze spending distribution and monthly net flow.
4.  **Data Persistence:** Transactions and budgets are stored reliably in a local SQLite database (`data/budget.db`).

# 🛠️ Technologies & Tools Used
* **Core Language:** Python 3.x
* **Database:** SQLite 3 (using Python's `sqlite3` module)
* **Data Handling:** `pandas`
* **Visualization:** `matplotlib`

##🚀 Installation & Running
1.  **Clone the repository:**
    ```bash
    git clone [Your-GitHub-Repo-Link]
    cd Personal_Budget_Manager
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas matplotlib
    ```
3.  **Run the application:**
    ```bash
    python src/main.py
    ```
