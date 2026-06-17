# Retail Sales Customer Analytics

## Project Overview

This project analyzes transactional retail sales data to uncover customer purchasing behavior, sales trends, product performance, and revenue-driving customer segments.

Using a real-world e-commerce dataset containing over 500,000 transactions, the project transforms raw sales records into actionable business insights through data cleaning, exploratory data analysis (EDA), visualization, and customer segmentation.

## Business Impact

This analysis transformed over 500,000 retail transactions into actionable business insights by identifying revenue trends, high-value customer segments, and top-performing markets. The findings can support customer retention strategies, seasonal sales planning, targeted marketing campaigns, and international market expansion decisions.

### Business Questions Addressed

- Which countries generate the highest revenue?
- How do sales trends change over time?
- Which products contribute most to sales volume?
- Who are the most valuable customers?
- Can customers be segmented based on purchasing behavior?

### Methodology

The dataset was cleaned and prepared by:

- Removing duplicate transactions
- Removing cancelled orders
- Handling missing customer records
- Removing invalid sales entries
- Creating revenue metrics for analysis

Customer behavior was further analyzed using RFM (Recency, Frequency, Monetary) segmentation to identify high-value customer groups.

## Business KPI Summary

| KPI | Value |
|------|--------:|
| Total Revenue | £8.89M |
| Total Customers | 4,338 |
| Total Orders | 18,532 |
| Average Order Value | £479.56 |

## Key Findings
### Customer Segmentation Results

| Segment | Count |
|----------|---------:|
| Others | 2407 |
| Loyal Customers | 914 |
| Champions | 609 |
| Recent Customers | 234 |
| Frequent Customers | 174 |

### Revenue Performance
- The United Kingdom generated the majority of total revenue.
- The Netherlands, EIRE, Germany, and France emerged as the strongest international markets.

### Seasonal Trends
- Revenue increased significantly during Q4.
- November recorded the highest sales volume, indicating strong seasonal purchasing behavior.

### Customer Insights
- Identified 609 Champion customers and 914 Loyal customers.
- A large proportion of customers belonged to lower-engagement segments, presenting opportunities for retention campaigns.

### Product Insights
- Home décor and gift-oriented products dominated sales volume.
- Product demand patterns suggest a lifestyle and gifting-focused retail business.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub
- Power BI

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Feature Engineering
- Customer Segmentation (RFM)
- Data Visualization
- Business Intelligence
- Business Storytelling

## Project Structure

```text
retail-sales-customer-analytics/
│
├── data/
│   ├── cleaned_retail_data.csv
│   └── rfm_customer_segments.csv
│
├── notebooks/
│   └── retail_sales_analysis.ipynb
│
├── images/
│   ├── revenue_distribution.png
│   ├── monthly_revenue_trend.png
│   ├── top_countries_revenue.png
│   └── customer_segments.png
│
├── README.md
└── requirements.txt
```
## Dataset Information

Dataset: Online Retail Dataset

The dataset contains transactional records from a UK-based online retailer between December 2010 and December 2011. It includes invoice details, product information, customer identifiers, quantities purchased, unit prices, and country-level sales data.

Original Dataset Size:
- 541,909 transactions

Final Cleaned Dataset:
- 392,692 transactions

## Future Improvements

- Build an interactive Power BI dashboard for executive reporting.
- Perform Customer Lifetime Value (CLV) analysis.
- Develop a sales forecasting model using time-series techniques.
- Implement customer churn prediction models.
- Create product recommendation systems using customer purchase behavior.
- Deploy insights through an interactive web application.

## Visualizations
### Revenue Distribution
<img width="895" height="470" alt="image" src="https://github.com/user-attachments/assets/7ceaab9a-078d-4e21-9de9-af17581edfde" />
<img width="868" height="470" alt="image" src="https://github.com/user-attachments/assets/a7bbb930-3eff-490b-838c-a05655453548" />

**Observation:** Revenue distribution is highly right-skewed, indicating that a small number of transactions contribute disproportionately to total revenue.

### Top Countries by Revenue

<img width="988" height="644" alt="image" src="https://github.com/user-attachments/assets/8cf8b372-0bc5-4489-b761-a20c45aadce7" />

**Observation:** The United Kingdom generated the majority of total revenue, while the Netherlands, EIRE, Germany, and France emerged as key international markets.

### Monthly Revenue Trend
<img width="1169" height="563" alt="image" src="https://github.com/user-attachments/assets/415ab5e1-095b-4354-905b-54499e96349a" />

**Observation:** Revenue increased significantly during Q4, with November recording the highest sales, suggesting strong seasonal purchasing behaviour.

### Customer Segmentation
<img width="850" height="470" alt="image" src="https://github.com/user-attachments/assets/fab11ed2-cb6d-458b-9d61-9bf669f1d34a" />
<img width="859" height="583" alt="image" src="https://github.com/user-attachments/assets/7c7b6f2e-85c7-4777-8f0e-7c8103808798" />

**Observation:** RFM analysis identified 609 Champion customers and 914 Loyal customers, highlighting a valuable customer base that contributes significantly to overall revenue.

## Conclusion

This project demonstrated an end-to-end analytics workflow, from data cleaning and exploratory analysis to customer segmentation and business insight generation. The analysis revealed strong seasonal sales patterns, identified high-value customer groups through RFM segmentation, and highlighted key revenue-generating markets and products. These findings provide actionable insights that can support customer retention, sales planning, and business growth strategies.
