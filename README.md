# 💰 SpendDNA – Financial Transaction Analytics

## 📌 Minor Project 2

### Student Details

- **Name:** Samarpan Pandit
- **Course:** Data Analytics with Python
- **Project:** Minor Project 2
- **Dataset:** Rahul Transactions (January 2024 – June 2024)

---

# 📖 Project Overview

SpendDNA is a Python-based financial transaction analytics project inspired by real-world fintech applications. The project analyzes six months of bank/UPI transaction data to understand spending behavior, identify spending patterns, detect unusual transactions, and generate a comprehensive financial report.

The project demonstrates data cleaning, exploratory data analysis, transaction categorization, anomaly detection, and financial reporting using only Python, Pandas, and NumPy.

---

# 🎯 Project Objectives

- Parse and clean raw financial transaction data.
- Extract canonical vendor names from transaction descriptions.
- Categorize transactions into spending categories.
- Analyze monthly spending trends.
- Analyze time-of-day spending behavior.
- Detect anomalous transactions using Z-score.
- Identify spending archetypes based on financial behavior.
- Generate a formatted SpendDNA financial report.

---

# 📂 Dataset Information

- **Dataset:** Rahul Transactions
- **Duration:** January 2024 – June 2024
- **Transactions:** ~1310 (after cleaning)
- **Columns:**
  - Date
  - Time
  - Description
  - Type
  - Amount
  - Balance
  - Mode
  - Reference

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

---

# ✨ Features Implemented

## Feature 1 – Transaction Parser

- Parsed multiple date formats
- Cleaned amount values
- Standardized transaction types
- Removed duplicate records
- Handled missing values

---

## Feature 2 – Vendor Extractor

- Extracted canonical vendor names
- Handled multiple vendor variants
- Identified P2P transfers
- Identified ATM withdrawals

---

## Feature 3 – Category Tagger

Mapped vendors into spending categories such as:

- Food Delivery
- Quick Commerce
- E-Commerce
- Transport
- Groceries
- Cafe
- Restaurants
- Utilities
- Fuel
- Entertainment
- Investments
- Personal Transfer
- Cash Withdrawal

---

## Feature 4 – Spending Overview

Generated:

- Total Credits
- Total Debits
- Net Savings
- Savings Rate
- Top Categories
- Top Vendors

---

## Feature 5 – Monthly Trend Analysis

- Category-wise monthly spending
- Monthly spending trends
- Growth and decline analysis

---

## Feature 6 – Time-of-Day Analysis

- Spending by hour
- Spending by time period
- Late-night spending analysis
- Peak spending hours

---

## Feature 7 – Anomaly Detection

Implemented Z-score based anomaly detection to identify unusually high transactions within each spending category.

---

## Feature 8 – Spending Archetype Detection

Detected spending personalities including:

- The Foodie
- The Quick Commerce Junkie
- The Shopaholic
- The Investor
- The Late-Night Snacker
- The YOLO Spender

---

# 📊 Sample Output

**Insert your SpendDNA Report screenshot here**

Example:

```
images/final_report.png
```

(Upload a screenshot of your final report into an `images` folder in the repository and reference it with Markdown if desired.)

---

# 📁 Repository Structure

```
SpendDNA/
│
├── SpendDNA_SamarpanPandit.ipynb
├── Data set for DADS June.csv
├── README.md
└── images/
    └── final_report.png
```

---

# ▶️ How to Run

1. Clone the repository.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Place the dataset in the same directory as the notebook.
4. Run all cells from top to bottom.
5. View the generated SpendDNA Report.

---

# 🚫 Project Constraints

This project follows the assignment requirements.

Allowed:

- Python Fundamentals
- Pandas
- NumPy

Not Used:

- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Regex
- External FinTech APIs

---

# 📚 Learning Outcomes

Through this project I learned:

- Data Cleaning
- Exploratory Data Analysis
- Vendor Normalization
- Category Mapping
- Financial Analytics
- Time Series Analysis
- Statistical Outlier Detection
- Report Generation using Python

---

# 🤖 AI Assistance Disclosure

Some portions of this project were developed with AI assistance for:

- Understanding project requirements
- Debugging Python code
- Reviewing logic
- Improving code readability

All analysis, testing, verification, and final implementation were completed and validated by the author.

---

# 👨‍💻 Author

**Samarpan Pandit**

Minor Project 2 – SpendDNA

Data Analytics with Python
