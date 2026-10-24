# Customer Churn Analysis - Exploratory Data Analysis (EDA)

An exploratory data analysis (EDA) project investigating customer churn patterns in the telecommunications domain. The objective of this project is to understand key drivers influencing customer retention and attrition to enable data-informed business strategies.

---

## 📌 Project Overview

Customer churn occurs when customers discontinue their subscription or service with a company. Retaining existing customers is significantly more cost-effective than acquiring new ones. Through exploratory analysis and statistical visualization, this project examines:
- Churn distribution and class imbalance across the dataset (~73.4% retained vs ~26.6% churned).
- Demographic indicators (Senior Citizen status, Partner, Dependents, Gender).
- Account details (Contract type, Payment Method, Paperless Billing, Tenure groupings).
- Service subscriptions (Internet service type, Tech support, Online security, Streaming services).
- Financial metrics (Monthly Charges vs Total Charges correlation and distribution with churn).

---

## 📂 Project Structure

```text
EDA-Customer_Churn_Analysis/
│
├── data/
│   └── CustomerChurn.csv            # Telecommunication customer dataset
│
├── customer_churn_analysis.ipynb    # Comprehensive EDA notebook with visualizations
├── main.py                          # Utility entry point
├── .gitignore                       # Git ignore configuration
└── README.md                        # Project documentation
```

---

## 🔍 Key Insights from Analysis

1. **Contract Type Matters Most**: Customers on Month-to-Month contracts exhibit substantially higher churn rates compared to those on One-Year or Two-Year contracts.
2. **Tenure & Loyalty**: Highest churn is observed in early customer tenure (first 1–12 months). Customers with longer tenure show significantly stronger retention.
3. **Monthly Charges Impact**: Churn is concentrated among customers with higher monthly charges, particularly those using Fiber Optic internet without bundle add-ons like Tech Support or Online Security.
4. **Payment Methods**: Customers paying via Electronic Check demonstrate noticeably higher churn compared to credit card, bank transfer, or mailed check users.

---

## 🛠️ Tech Stack & Libraries

- **Language:** Python 3.x
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Environment:** Jupyter Notebook

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/EDA-Customer_Churn_Analysis.git
cd EDA-Customer_Churn_Analysis
```

### 2. Set Up a Virtual Environment
```bash
# Windows
python -m venv .venv
.venv\Scripts\activate

# macOS / Linux
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Run the Analysis
Launch Jupyter Notebook to view and run the interactive analysis:
```bash
jupyter notebook customer_churn_analysis.ipynb
```

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
