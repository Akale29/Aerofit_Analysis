
# Aerofit Treadmill Customer Analysis 📊

An exploratory data analysis project focused on understanding customer characteristics and purchasing behaviour across Aerofit's three treadmill models: **KP281, KP481, and KP781**.

## 🎯 Business Objective

The objective is to identify customer profiles for each treadmill model based on:

- Age
- Gender
- Education
- Marital Status
- Income
- Usage
- Fitness Level
- Expected Weekly Miles

The analysis helps understand which customer characteristics are associated with different treadmill products and supports data-driven business decisions.

## 📊 Dataset

- **Records:** 180
- **Variables:** 9
- **Products:** KP281, KP481, KP781
- **Missing Values:** None
- **Duplicate Records:** None

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Google Colab**

## 🔍 Analysis Performed

### Data Understanding
- Dataset structure and data types
- Missing-value analysis
- Duplicate-value analysis
- Descriptive statistics
- Unique-value analysis
- Categorical distribution analysis

### Exploratory Data Analysis
- Histograms
- Distribution plots
- Count plots
- Boxplots
- Correlation analysis
- Correlation heatmap

### Product Profiling

Customer characteristics were compared across KP281, KP481, and KP781 using:

- Age
- Income
- Usage frequency
- Fitness level
- Expected weekly miles

## 📈 Key Observations

- **KP281** is the most purchased model, accounting for **44.44%** of the dataset.
- **KP481** represents **33.33%** of purchases.
- **KP781** represents **22.22%** of purchases.
- Males account for **57.78%** of customers, while females account for **42.22%**.
- Partnered customers represent **59.44%** of the dataset.
- KP781 customers show higher income, usage, fitness levels, and expected weekly miles compared with the other models.
- Usage and expected weekly miles show a strong positive correlation (**0.759**).
- Fitness and expected weekly miles show a strong positive correlation (**0.786**).
- Usage and fitness also show a positive correlation (**0.669**).

## 💡 Business Insights

The analysis can help Aerofit develop customer profiles for each treadmill model and use characteristics such as income, fitness level, usage frequency, and expected miles to support product recommendations and targeted marketing.

## 📁 Project Structure

```text
Aerofit-Treadmill-Analysis/
│
├── Aerofit.ipynb
├── aerofit_treadmill.csv
├── README.md
└── Aerofit_Analysis.pdf
