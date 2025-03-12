# Retail Customer Analytics using RFM Analysis, K-Means, and CLV

# Overview
This project leverages transactional data to segment and analyze customer behavior using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering. It aims to predict future purchase frequency, profitability, and Customer Lifetime Value (CLV). The primary goal is to identify high-value customers and predict their future purchasing behaviors, enabling more informed decisions in marketing and customer retention strategies.

# Technologies Used
Programming Language: Python  
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Lifetimes & Lifelines (Specialized libraries for survival analysis and customer lifetime value modeling)

# Dataset
The dataset used in this project is the 'Online Retail II' dataset, which contains transactional data for an online retail store. The dataset is available at [Online Retail II Dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii).

# Key Steps
# 1. Data Cleaning and Preprocessing
**Notebook:** Data Cleaning and Preprocessing.ipynb  
**Objective:** Prepare the dataset for analysis by addressing data quality issues.  
**Key Actions:**  
- Removed cancelled orders, duplicate entries, and null values.
- Engineered new feature to enhance segmentation and insights.

# 2. Exploratory Data Analysis (EDA)
**Notebook:** EDA.ipynb  
**Objective:** Analyzed the dataset to uncover patterns and insights.  
**Analyses Performed:**
- **Univariate Analysis:** Examined distributions and statistics of key features such as Quantity, Price, StockCode, Description, and Country.
- **Multivariate Analysis:** Investigated relationships between multiple variables.
- **Date-Time Analysis:** Analyzed trends over time to understand seasonal effects.
- **Correlation Analysis:** Identified relationships between features to identify drivers of sales and customer behavior.

# 3. Customer Segmentation
**Notebook:** Customer Segmentation.ipynb  
**Objective:** Segment customers to better understand varying behaviors and tailor marketing efforts.  
**Techniques Used:**
- **RFM Analysis:** Segmented customers by Recency, Frequency, and Monetary values to identify groups like "Champions," "Loyal Customers," and "At-Risk Customers."
- **K-means Clustering:** Applied clustering to discover customer groupings based on purchasing patterns.
- **Market Basket Analysis:** Explored product combinations frequently purchased together.
- **Geographic and Time Series Analysis**

# 4. Predictive Modeling
**Notebook:** Customer Segmentation.ipynb  
**Objective:** Forecast future customer behaviors using advanced modeling techniques.  
**Models Applied:**
- **BG/NBD Model:** Predicted future purchase frequency.
- **Gamma-Gamma Model:** Estimated future profit and Customer Lifetime Value for each customer.

# 5. Survival Analysis
**Notebook:** Customer Segmentation.ipynb  
**Objective:** Analyze customer churn and retention rates.  
**Method:** Utilized the Kaplan-Meier estimator to model customer survival probabilities.
