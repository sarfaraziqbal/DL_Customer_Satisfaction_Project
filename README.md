# 🛒 E-Commerce Customer Service Satisfaction Analysis & Prediction

## 📌 Project Overview
Customer service quality is a key driver of customer retention and brand loyalty in e-commerce platforms.  
This project analyzes customer support interaction data to identify factors influencing customer satisfaction and applies machine learning techniques to derive actionable business insights.

The project focuses on understanding customer behavior, predicting satisfaction trends, and recommending improvements to enhance service quality.

---

## 🎯 Objectives
- Analyze customer support interaction data
- Perform exploratory data analysis (EDA)
- Clean and preprocess real-world customer service data
- Engineer meaningful features such as response and resolution time
- Build machine learning models to predict customer satisfaction
- Provide data-driven business recommendations

---

## 📂 Dataset
- **File:** `eCommerce_Customer_support_data.csv` (inside a ZIP file)
- **Source:** Public e-commerce customer support dataset (Kaggle-style structure)
- **Type:** Structured tabular data

### Key Columns
- `channel_name`
- `category`
- `sub_category`
- `issue_reported_at`
- `issue_responded`
- `survey_response_date`
- Customer and order interaction details

> ⚠️ Note: The dataset contains missing values, reflecting real-world customer support scenarios.

---

## 🧰 Technologies & Libraries Used

### Programming Language
- Python

### Libraries
- **NumPy** – Numerical operations
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations
- **Scikit-learn** – Feature engineering, model building, and evaluation
- **SciPy** – Statistical analysis

---

## 🔍 Project Workflow

1. **Data Ingestion**
   - Extract ZIP file
   - Load CSV into Pandas DataFrame

2. **Exploratory Data Analysis (EDA)**
   - Dataset structure analysis
   - Missing value inspection
   - Channel and category-level analysis

3. **Data Cleaning**
   - Handling missing values
   - Converting date and time columns
   - Removing redundant features

4. **Feature Engineering**
   - Response time calculation
   - Resolution time analysis
   - Encoding categorical variables

5. **Visualization & Insights**
   - Channel-wise performance analysis
   - Issue category impact on satisfaction
   - Response time vs satisfaction trends

6. **Model Building**
   - Classification models for satisfaction prediction
   - Focus on interpretability and business relevance

7. **Model Evaluation**
   - Accuracy
   - Precision
   - Recall
   - Confusion Matrix

---

## 📊 Key Insights
- Longer response times are strongly associated with lower customer satisfaction
- Certain issue categories (returns, installation, cancellations) show higher dissatisfaction
- Survey participation is low, indicating feedback collection gaps
- Some customer support channels outperform others in satisfaction metrics

---

## 🛠️ Business Recommendations
- **Reduce Response Time**
  - Use AI chatbots for common queries
  - Automate initial acknowledgments

- **Improve High-Impact Issue Categories**
  - Optimize return and installation workflows
  - Improve product documentation and clarity

- **Increase Survey Participation**
  - Shorter surveys
  - Incentivized feedback

- **Optimize Support Channels**
  - Invest in high-performing channels
  - Balance workload across channels

---

## 📈 Results & Impact
This project demonstrates how data analysis and machine learning can:
- Improve customer experience
- Enable proactive customer support
- Reduce churn
- Support data-driven business decisions
This project focuses on predicting Customer Satisfaction (CSAT) scores using Deep L
