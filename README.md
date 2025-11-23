# Project Description: PyTrack - Personal Finance Tracker

## Project Overview

PyTrack is a functional, command-line interface (CLI) application built using Python to provide individuals with a straightforward and private tool for monitoring and analyzing their personal financial transactions. The primary goal is to promote better financial awareness by simplifying the process of tracking income, expenses, and savings over time. By leveraging the robustness of Python and the simplicity of SQLite, PyTrack ensures data persistence, integrity, and local control.

## Key Features

Transaction Management: Seamless recording of new income and expense transactions, including date, amount, category, and description.

Persistent Data Storage: Utilization of the SQLite3 embedded database to store all financial records locally, ensuring data is saved securely and accessible across sessions.

Categorization System: A flexible system allowing users to define and manage custom categories (e.g., 'Groceries', 'Utilities', 'Salary'), facilitating detailed spending analysis.

Financial Reporting: Generation of summarized reports, including monthly income/expense breakdowns, net balance calculations, and expenditure analysis by category.

Command Line Interface (CLI): A simple, menu-driven interface designed for quick and efficient data entry and navigation without the need for complex graphical dependencies.

Technology Stack

Component

Technology

Role in Project

### Backend Language

Python 3.x

Core application logic, data validation, and CLI management.

### Database

SQLite3

Lightweight, serverless database for local, persistent storage of transactions and categories.

### Data Handling

Standard Library (datetime, csv)

Managing date-time data and handling optional data import/export functionality.

### Technical Architecture

The application employs a clear separation of concerns, utilizing an Object-Oriented approach.

Data Access Layer: Handles all database connections and SQL queries, abstracted by a DatabaseManager class.

Logic Layer: Contains the main FinanceTracker class responsible for business rules, calculations (sums, differences), and data filtering for reports.

Presentation Layer: The CLI (main.py) handles user input and displays formatted output derived from the Logic Layer.

### Target Audience

This tool is ideal for developers, students, or any individual who prefers a non-cloud-based, minimalist, and scriptable tool to manage their finances directly on their local machine.
