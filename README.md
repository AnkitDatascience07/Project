# EDA and RFM Customer Segmentation Analysis

## 📊 Project Overview
This project performs comprehensive **Exploratory Data Analysis (EDA)** and **RFM (Recency, Frequency, Monetary) Analysis** on UK retail transaction data to segment customers based on their purchasing behavior. The analysis enables targeted marketing strategies by identifying distinct customer groups and their characteristics.

## 🎯 Business Objective
- Segment customers into meaningful groups based on purchasing patterns
- Identify high-value customers for retention strategies
- Develop targeted marketing campaigns for different customer segments
- Provide actionable insights for business growth and customer relationship management

## 📈 Key Insights & Results
- **Customer Segmentation**: Identified 5+ distinct customer segments using RFM analysis
- **Champions**: High-value customers with recent purchases and high frequency
- **At-Risk Customers**: Previously valuable customers showing declining engagement
- **New Customers**: Recent buyers with potential for growth
- **Lost Customers**: Inactive customers requiring win-back campaigns
- **Visual Analysis**: Interactive plots showing customer distribution and behavior patterns

## 🛠️ Technologies Used
- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computations
- **plotly** - Interactive visualizations
- **matplotlib/seaborn** - Statistical plotting
- **Jupyter Notebook** - Development environment

## 📊 Dataset Information
- **Source**: UK-based online retail transaction data
- **Time Period**: 2010-2011 transaction history
- **Size**: 500K+ transaction records
- **Key Variables**: 
  - CustomerID, InvoiceNo, InvoiceDate
  - StockCode, Description, Quantity
  - UnitPrice, Country

## 🔍 Analysis Structure

### 1. **Exploratory Data Analysis (EDA)**
- Data quality assessment and cleaning
- Missing value analysis and treatment
- Statistical summary and data distribution
- Transaction patterns and trends analysis

### 2. **RFM Metrics Calculation**
- **Recency**: Days since last purchase
- **Frequency**: Total number of transactions
- **Monetary**: Total amount spent

### 3. **Customer Segmentation**
- RFM score calculation using quintile-based ranking
- Customer classification into behavioral segments
- Segment characteristics and business implications

### 4. **Visualizations**
- Customer segment distribution
- RFM score heatmaps
- Purchase behavior patterns
- Geographic analysis of customers

