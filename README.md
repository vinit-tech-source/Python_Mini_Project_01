<div align="center">

# 💰 Personal Expense Tracker (Python Mini Project)

An intuitive and powerful Python Command-Line Interface (CLI) application for tracking everyday expenses, analyzing spending habits, and generating visual data charts using Matplotlib.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data_Visualization-orange?style=for-the-badge)
![JSON Storage](https://img.shields.io/badge/Storage-JSON-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)

</div>

---

## ✨ Features

- **📝 Add Expenses:** Easily record daily expenses with descriptions, amounts (₹), categories, and automatic date stamping.
- **📊 Interactive Data Visualization:** Generate clean bar charts and pie charts using `matplotlib` to analyze spending breakdowns across categories (*Food, Travel, Bills, Shopping, Other*).
- **💾 Persistent JSON Storage:** All records are automatically saved and organized locally in an easy-to-read `expenses.json` file.
- **📅 Monthly Reports:** Filter expenses by specific month and year to track financial trends over time.
- **⚡ Clean CLI Interface:** Formatted tabular display with clear summaries and total spending indicators.

---

## 🛠️ Project Structure

```text
📦 Python_Mini_Project_01
 ┣ 📜 EXPENCE TRACKER.py   # Main application script with CLI menu & charts
 ┣ 📜 expenses.json        # Local JSON database storing expense history
 ┗ 📜 README.md            # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have **Python 3** installed on your system along with the `matplotlib` library for chart generation:

```bash
pip install matplotlib
```

### Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/vinit-tech-source/Python_Mini_Project_01.git
   cd Python_Mini_Project_01
   ```

2. Run the script:
   ```bash
   python "EXPENCE TRACKER.py"
   ```

---

## 💻 Interactive Menu Walkthrough

When launched, you will be greeted with a structured CLI menu:

```text
========== EXPENSE TRACKER ==========
1. Add Expense
2. View All Expenses
3. Show Summary (Charts)
4. Monthly Report
5. Exit
=====================================
```

### Menu Options:
1. **Add Expense:** Prompts for item description, cost in ₹, and category classification.
2. **View All Expenses:** Displays all saved logs in a formatted table with total expenditure calculation.
3. **Show Summary (Charts):** Outputs category-wise totals in console and launches two matplotlib windows (Bar Chart & Pie Chart).
4. **Monthly Report:** Filter records for any selected `MM/YYYY`.
5. **Exit:** Safely saves data and terminates the application.

---

## 📈 Visual Analytics Sample

The application generates intuitive visualizations directly from your records:
- **Bar Chart:** Compares total ₹ expenditure side-by-side across categories.
- **Pie Chart:** Displays percentage distribution of your spending habits.

---

<div align="center">
Made with ❤️ by <a href="https://github.com/vinit-tech-source">Vinit</a>
</div>
