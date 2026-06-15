# Telco Customer Churn Analysis

## 📌 Project Overview
Customer churn is one of the most critical metrics for any subscription-based business. This project delivers an in-depth exploratory data analysis (EDA) on a telecom customer base consisting of **7,043 unique accounts** to isolate behavioral, financial, and product-level drivers behind subscriber defection. 

As a **Junior Data Analyst**, my objective was to clean the raw data, perform extensive univariate and bivariate visualizations (countplots, histograms), and translate technical findings into high-level, actionable strategies for corporate leadership.

---

## 📊 Dataset Information
* **Source:** The dataset used in this analysis is the popular Telco Customer Churn dataset available on Kaggle.
* **Dataset Link:** [Kaggle Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
* **Scope:** 7,043 rows, 21 features including customer demographics, account details, service types, and financial metrics.

---

## 🛠️ My Role & Analysis Workflow
In this project, I took ownership of the complete data analysis lifecycle:

1. **Data Cleaning & Preprocessing:** * Handled missing/empty values in structural columns like `TotalCharges`.
   * Adjusted data types to ensure proper numerical and categorical alignment.
2. **Exploratory Data Analysis (EDA):**
   * Plotted **Histograms** to analyze distribution frequencies for baseline core metrics (Tenure, Monthly Charges, and Total Charges).
   * Leveraged **Countplots with hue separations** (`Churn` vs. `No Churn`) to identify localized friction points across account attributes.
3. **Insight Synthesis:**
   * Converted raw counts into proportional operational percentages to make insights highly digestible for executive-level presentations.

---

## 📈 Key Visual & Strategic Insights

Through extensive visual pattern analysis, I uncovered three high-risk operational pillars:

### 1. Contractual Structures & Onboarding Fractures
* **Month-to-Month Contracts:** Acting as the single largest churn vector, these fluid accounts lack long-term structural barriers or financial incentives to stay.
* **The 9-Month Inflection Window:** The first quartile ($25\%$) of the subscriber base experiences a critical risk window between $0\text{ to }9\text{ months}$ of tenure, revealing an early-stage retention bottleneck.

### 2. Product Portfolio & Technology Disconnections
* **Fiber Optic Infrastructure:** Despite delivering superior bandwidth, Fiber Optic subscribers exhibit a significantly higher propensity to churn than standard DSL users, highlighting potential issues with onboarding, localized service delivery, or pricing.
* **Value-Added Service Deficiencies:** Accounts lacking protective ecosystem overlays like **Online Security** and **Tech Support** show a steep increase in defection rates.

### 3. Financial & Transactional Friction
* **Electronic Check Payment Disruption:** Subscribers utilizing manual Electronic Checks maintain an exponentially higher churn rate compared to automated methods (Credit Cards/Bank Transfers), proving that recurring manual touchpoints increase billing awareness and friction.
* **Paperless Billing Hyper-Awareness:** Digital notifications detached from auto-pay setups act as a monthly trigger for price re-evaluation.

---

## 💡 Executive Recommendations
Based on the visualized trends, I proposed four strategic corporate initiatives:
* 🎯 **Contractual Migration Campaigns:** Deploy predictive pricing and bundle rewards targeting Month-to-Month accounts within their first 9 months to transition them into stable 1 or 2-year commitments.
* 📦 **Ecosystem Bundling:** Re-engineer Fiber Optic pricing architecture to natively wrap core value-added security features (*Online Security* and *Tech Support*) as baseline configurations rather than standalone add-ons.
* 💳 **Programmatic Auto-Pay Schemes:** Implement targeted statement credits to incentivize Electronic Check users to migrate over to Automated Bank Transfers.
* 🤝 **Early-Tenure Onboarding Workflows:** Proactively trigger Customer Success touchpoints at the 30, 60, and 90-day marks for high-risk configurations to prevent premature cancellations.

---

## 🚀 Technical Stack Used
* **Language:** Python
* **Libraries:** * `pandas` & `numpy` (Data manipulation)
  * `matplotlib.pyplot` & `seaborn` (Advanced data visualization)
* **Environment:** Jupyter Notebook

---

## 📂 How to Run This Project
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
