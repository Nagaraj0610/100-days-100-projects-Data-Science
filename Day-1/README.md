# 💰 Personal Expense Tracker Analysis

This project is a **data analysis notebook** for tracking and visualizing personal expenses.  
It takes a CSV of transactions, cleans it, computes summary statistics, and generates insights using **Pandas** and **Matplotlib**.

---

## 📌 Features
- Clean and preprocess raw expense data (remove duplicates, fix dates, normalize categories).
- Compute basic statistics:
  - Total expense & income
  - Net balance
  - Average expense
  - Transaction counts
- Visualizations:
  - 📊 Bar chart — Expenses by category
  - 📈 Line chart — Monthly expense trend
  - 🥧 Pie chart — Expense share by category
- Save cleaned dataset + generated charts.

---

## 🛠️ Tech Stack
- **Python 3**
- **Pandas** — data wrangling
- **Matplotlib** — visualization
- **Jupyter Notebook** — interactive analysis

---

## 📂 Project Structure
```
├── expensedata.csv             # Raw input file
├── Expense_Tracker_Analysis.ipynb  # Jupyter notebook (main analysis)
├── outputs/                    # Generated outputs
│   ├── cleaned_expenses.csv    # Cleaned dataset
│   ├── expenses_by_category.png
│   ├── monthly_expenses.png
│   ├── expense_share.png
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/expense-tracker-analysis.git
cd expense-tracker-analysis
```

### 2. Install dependencies
```bash
pip install pandas matplotlib jupyter
```

### 3. Run Jupyter Notebook
```bash
jupyter notebook Expense_Tracker_Analysis.ipynb
```

---

## 📊 Example Outputs

### Expenses by Category
![Category Chart](outputs/expenses_by_category.png)

### Monthly Expenses Over Time
![Monthly Trend](outputs/monthly_expenses.png)

### Expense Share
![Pie Chart](outputs/expense_share.png)

---

## 🔮 Possible Extensions
- Add interactive dashboards (Plotly / Streamlit).
- Categorize transactions using NLP on the `Note` column.
- Automate recurring imports (Google Sheets / Bank statements).
- Add savings and budgeting insights.

---

👨‍💻 Created with Python & ❤️ to make personal finance analysis simple!
