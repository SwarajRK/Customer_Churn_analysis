# Customer Churn Analysis (Netflix-style Dataset)

## 📌 Project Overview
Customer churn is a critical business problem where companies aim to understand **why customers stop using a service** and how to **reduce churn**.

In this project, I performed an **end-to-end data analysis** on a Netflix-style customer dataset to identify key factors influencing churn and derive **actionable business insights**.

This project demonstrates my ability to:
- Work with real-world datasets
- Clean and preprocess data
- Perform exploratory data analysis (EDA)
- Apply statistical reasoning
- Translate numerical results into business recommendations

---

## 🎯 Objective
The main objectives of this analysis were:
- To understand customer behavior patterns
- To identify factors associated with customer churn
- To suggest strategies to improve customer retention

---

## 🧰 Tools & Technologies
- **Python**
- **Pandas** – data manipulation and analysis
- **NumPy** – numerical computation
- **Matplotlib / Seaborn** – data visualization
- **Jupyter Notebook**

---

## 📂 Dataset Description
The dataset contains customer-level information such as:
- Customer tenure
- Subscription type
- Usage behavior
- Churn indicator (whether the customer left the service)

> Note: This dataset is used for educational and analytical purposes.

---

## 🔍 Methodology

### 1️⃣ Data Cleaning & Preprocessing
- Checked for missing values and inconsistencies
- Converted columns to appropriate data types
- Handled missing values based on data context

**Why this step?**  
Clean and reliable data is essential for accurate analysis and meaningful insights.

---

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed churn distribution
- Compared churned vs retained customers across key features
- Used visualizations to identify trends and patterns

**Why EDA?**  
EDA helps uncover hidden patterns, detect outliers, and understand customer behavior before modeling.

---

### 3️⃣ Statistical Analysis
- Used descriptive statistics (mean, median, standard deviation)
- Performed correlation analysis to identify relationships between variables and churn

**Why statistics?**  
Statistics summarize data behavior and help in selecting relevant features.

---

### 4️⃣ Predictive Modeling (Validation Step)
- Applied **Logistic Regression** to model churn probability
- Interpreted model coefficients to understand feature impact

**Why Logistic Regression?**  
Churn is a binary outcome, and logistic regression is interpretable and suitable for business analysis.

---

## 📊 Key Insights
- Customers with **shorter tenure** are more likely to churn
- Lower engagement levels are associated with higher churn
- Early-stage customer experience plays a crucial role in retention

---

## 💡 Business Recommendations
- Improve onboarding experience for new users
- Increase engagement through personalized content
- Target at-risk customers with retention campaigns

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/SwarajRK/Customer_Churn_analysis.git
2. Install required libraries
   ```bash
   pip install pandas numpy matplotlib seaborn
3. Open the Python Notebook and run cells
