# 💸 Budget Tracker with Spending Chart (Python Project)

This project is a **command-line Python application** that tracks your budget by category (like Food, Clothing, Entertainment) and displays a **text-based chart** showing spending distribution.

---

## 🚀 Features

- Create and manage **multiple budget categories**
- Track **deposits**, **withdrawals**, and **transfers**
- View the current balance of each category
- Display a **spending percentage chart** using ASCII art

---

## 🧾 How It Works

Each category (e.g., Food, Clothing) has a **ledger** where all transactions are recorded. You can:
- `deposit(amount, description)`
- `withdraw(amount, description)`
- `transfer(amount, to_category)`
- `check_funds(amount)` to validate availability

A custom `__str__` method prints a formatted summary of the ledger.

The `create_spend_chart()` function builds a **vertical bar chart** that shows the percentage of total spending for each category.

---

## 📦 Project Structure

```text
budget_tracker.py
