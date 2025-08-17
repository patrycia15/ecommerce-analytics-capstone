# E-commerce Sales Performance Analysis
## Capstone Project - Data Analytics

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-green.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Status](https://img.shields.io/badge/Status-Complete-success.svg)

### 📊 Project Overview

This project performs comprehensive e-commerce sales performance analysis using customer transaction data. The analysis includes customer segmentation, sales trends, and business performance metrics to provide actionable insights for business decision-making.

### 🎯 Objectives

- **Customer Segmentation**: Implement RFM (Recency, Frequency, Monetary) analysis to categorize customers
- **Sales Trend Analysis**: Analyze monthly sales patterns and identify growth opportunities
- **Business Performance**: Calculate key performance indicators and business metrics
- **Data-Driven Insights**: Provide actionable recommendations for business improvement

### 📊 *Dataset Information*

*Source:* Kaggle E-Commerce Datasets (Public Domain) https://www.kaggle.com/search?q=E-Commerce+Sales+Performance+Analysis+in%3Adatasets
- *Records:* 10,000+ transactions
- *Time Period:* 12 months of sales data
- *Geographic Coverage:* Southeast Asian markets
- *Product Categories:* Electronics and tech accessories


### 📁 Project Structure

```
ecommerce-analytics-capstone/
├── README.md                           # Project documentation
├── ecommerce_analysis.ipynb           # Main analysis notebook
├── business_summary_report.csv        # Business KPIs and summary metrics
├── customer_metrics.csv              # Individual customer performance data
├── customer_rfm_analysis.csv         # RFM segmentation results
└── monthly_sales_trend.csv           # Monthly sales trend data
```

### 🔧 Technologies Used

- **Python 3.8+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib & Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive development environment
- **Google Colab** - Cloud-based notebook execution

### 📈 Analysis Components

#### 1. RFM Customer Segmentation
- **Recency**: Days since last purchase
- **Frequency**: Number of transactions
- **Monetary**: Total spending amount
- **Customer Categories**: Champions, Loyal Customers, Potential Loyalists, New Customers, At Risk, etc.

#### 2. Sales Performance Metrics
- Monthly revenue trends
- Average order value (AOV)
- Customer lifetime value (CLV)
- Purchase frequency analysis
- Revenue growth patterns

#### 3. Business Intelligence
- Top performing customer segments
- Seasonal sales patterns
- Customer retention insights
- Revenue optimization opportunities

### 📊 Key Output Files

#### `customer_rfm_analysis.csv`
Contains RFM scores and customer segments for each customer:
- Customer ID
- Recency Score (1-5)
- Frequency Score (1-5) 
- Monetary Score (1-5)
- RFM Segment Classification

#### `customer_metrics.csv`
Individual customer performance metrics:
- Total transactions
- Total revenue
- Average order value
- Customer lifetime value
- Last purchase date

#### `monthly_sales_trend.csv`
Monthly aggregated sales data:
- Monthly revenue
- Transaction count
- Average order value
- Customer acquisition
- Growth rates

#### `business_summary_report.csv`
High-level business KPIs:
- Total revenue
- Customer count
- Average customer value
- Retention rates
- Segment distribution

### 🚀 How to Run the Analysis

1. **Clone the repository:**
   ```bash
   git clone https://github.com/patrycia15/ecommerce-analytics-capstone.git
   ```

2. **Open in Google Colab:**
   - Upload `ecommerce_analysis.ipynb` to Google Colab
   - Or use the Colab link: [Open in Colab](https://colab.research.google.com/drive/your-notebook-link)

3. **Upload your data:**
   - Prepare your e-commerce transaction data in CSV format
   - Required columns: Customer ID, Transaction Date, Amount, Product details

4. **Run the notebook:**
   - Execute all cells sequentially
   - Analysis results will be automatically downloaded as CSV files

### 📋 Data Requirements

Your input data should contain:
- **Customer ID**: Unique identifier for each customer
- **Transaction Date**: Date of purchase (YYYY-MM-DD format)
- **Transaction Amount**: Purchase value in numeric format
- **Product Information**: Product names/categories (optional)

### 🎯 Key Insights & Recommendations

#### Customer Segmentation Insights:
- **Champions**: Top 5-10% of customers driving 30-40% of revenue
- **At Risk Customers**: Previously valuable customers showing declining activity
- **New Customers**: Recent acquisitions with growth potential

#### Business Recommendations:
1. **Focus on Champions**: Implement VIP programs and exclusive offers
2. **Re-engage At Risk**: Launch targeted retention campaigns
3. **Nurture New Customers**: Develop onboarding sequences
4. **Optimize Seasonal Patterns**: Prepare inventory and marketing for peak periods

### 📞 Contact & Support

**Author**: Patrycia Fillyandra Marcelline  
**Email**: patryciafillyandramarcelline@gmail.com  
**LinkedIn**: www.linkedin.com/in/patrycia-marcelline-827913356  


### 📝 License

This project is open source and available under the [MIT License](LICENSE).

### 🙏 Acknowledgments

- Data analytics methodology inspired by industry best practices
- RFM analysis framework adapted from customer segmentation literature
- Visualization techniques following modern data presentation standards

---

**⭐ If you found this analysis helpful, please consider giving it a star!**

### 📊 Sample Visualizations

*Note: Actual visualizations and detailed insights are available in the Jupyter notebook and output CSV files.*

### 🔄 Future Enhancements

- [ ] Real-time dashboard integration
- [ ] Predictive customer churn modeling
- [ ] Advanced cohort analysis
- [ ] Machine learning recommendation system
- [ ] Automated report generation
