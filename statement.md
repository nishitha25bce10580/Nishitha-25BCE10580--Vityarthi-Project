# Project Statement: Personalized Budget Manager

## 1. Problem Statement

Many individuals, particularly students and young professionals, struggle with **personal financial management** due to a lack of clear visibility into their spending habits. This often leads to overspending, difficulties in achieving savings goals, and an inability to track and control expenses effectively over time. The manual process of recording transactions is tedious, while commercial solutions are often overly complex or subscription-based.

**The problem addressed** is the need for a simple, reliable, and customizable tool to **monitor, categorize, and visualize personal income and expenses** against predefined budget limits, fostering greater financial discipline.

---

## 2. Scope of the Project

The project is implemented as a **Command Line Interface (CLI)** application written in Python.

The scope encompasses:
* **Data Persistence:** Transactions and budget goals are stored locally using an **SQLite database**.
* **Core Functionality:** Tracking of income and expenses, setting of category-specific budgets, and generating analytical reports.
* **Visualization:** Providing graphical representation of spending distribution and monthly cash flow trends using the `matplotlib` library.

The project **does not** include:
* Integration with external APIs (e.g., bank account synchronization).
* User authentication or multi-user support.
* Advanced financial forecasting or investment analysis.

---

## 3. Target Users

The primary target users for this application are individuals seeking to gain better control over their daily finances:

* **Students:** To manage stipends, scholarships, and control spending on food, entertainment, and academic supplies.
* **Young Professionals:** To monitor their first salaries, allocate funds for savings, and track major expense categories like rent and transport.
* **Individuals seeking Financial Discipline:** Anyone who prefers a simple, private, and non-cloud-based tool for basic budgeting and financial review.

---

## 4. High-Level Features

The Personalized Budget Manager is built around three core functional modules:

1.  **Transaction Logging (CRUD):** Allows users to log detailed **Income** and **Expense** records, including amount, category, date, and description.
2.  **Budget Goal Setting & Tracking:** Enables users to define **monthly spending limits** for specific expense categories (e.g., Food, Entertainment). It provides a mechanism to check the current month's spending against these limits and flags overspending.
3.  **Data Reporting & Visualization:** Generates two types of visual reports using `matplotlib`:
    * A **Pie Chart** showing the percentage distribution of expenses by category.
    * A **Bar Chart** illustrating the monthly trend of total income versus total expense.
