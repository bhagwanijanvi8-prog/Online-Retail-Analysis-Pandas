# Online-Retail-Analysis-Pandas
#  Retail Data Analytics with AI & Fireducks

This project performs comprehensive exploratory data analysis (EDA) on a real-world dataset of UK-based online retail transactions. It combines AI-assisted coding, customer segmentation, churn prediction, and large-scale data processing using the Fireducks library.

##  Dataset

- **Source**: UK-based online retailer
- **Size**: 500,000 transactions
- **Format**: CSV
- **Fields**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

##  Key Features

### 1. Data Cleaning
- Handled missing descriptions and invalid entries (e.g., negative quantities/prices)
- Imputed missing values using most frequent description per stock code
- Consulted domain knowledge to differentiate errors from refunds/wholesale orders

### 2. Feature Engineering & Visualization
- Created time-based features for trend analysis
- Visualized monthly sales patterns (e.g., Q4 "hockey stick" spike)
- Built customer-level aggregates for segmentation

### 3. RFM Analysis
- Scored customers on Recency, Frequency, and Monetary value
- Identified high-value "gold customers"
- Enabled targeted marketing strategies

### 4. Churn Prediction
- Defined churn threshold (e.g., 90 days of inactivity)
- Flagged at-risk customers for retention campaigns

### 5. Fireducks Integration
- Scaled analysis to 32 million records
- Achieved significant speedup over pandas
- Maintained pandas compatibility with multi-threaded, JIT-compiled performance

##  AI-Assisted Coding
- Used Google Colab with AI assistant for faster development
- Contextual code suggestions improved productivity
- Emphasized human oversight to avoid over-reliance

##  Results & Insights
- Seasonal sales trends aligned with holiday shopping
- RFM scores revealed actionable customer segments
- Churn analysis enabled timely interventions
- Fireducks proved ideal for big data analytics

##  Tech Stack
- Python
- Pandas & Fireducks
- Matplotlib & Seaborn
- Google Colab
- AI Assistant (Colab)

## 📁 Repository Structure

