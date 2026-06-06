# E-Commerce Customer Analytics: RFM Segmentation, Cohort Retention & Market Basket Insights

Advanced exploratory data analysis project focused on customer behavior, revenue performance, retention, segmentation, and product bundling opportunities.

## Business Objective

The goal is to help an e-commerce business answer:

- Which customers generate the most value?
- Which products/categories drive revenue?
- How does customer retention change across monthly cohorts?
- Which products are frequently bought together?
- What actions can improve retention, revenue, and cross-selling?

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

## Project Structure

```text
.
├── data/
│   ├── raw/                 # Place original dataset here
│   └── processed/           # Optional cleaned exports
├── ECommerce_Customer_Analytics_EDA.ipynb
├── README.md
├── linkedin_post_draft.md
├── requirements.txt
└── .gitignore
```

## Recommended Dataset

This notebook works best with a transactional e-commerce dataset containing:

- Order ID / Invoice ID
- Customer ID
- Order Date / Invoice Date
- Product Name / Description
- Quantity
- Unit Price
- Country / City
- Category, if available

Good examples include the UCI Online Retail dataset or Kaggle e-commerce transaction datasets.

Place your file inside `data/raw/`, then update the `DATA_PATH` variable in the notebook.

## Analysis Sections

1. Problem Statement
2. Dataset Overview
3. Data Cleaning
4. Feature Engineering
5. Core EDA
6. RFM Analysis
7. Customer Segmentation
8. Cohort Retention Analysis
9. Basic Market Basket Analysis
10. Plotly Interactive Visualizations
11. Final Business Insights
12. Business Recommendations

## Sprint Plan

### Day 1

- Load and inspect dataset
- Clean missing, duplicate, invalid, and negative values
- Convert date columns
- Engineer revenue, month, year, and customer metrics
- Build core EDA visuals

### Day 2

- Build RFM table
- Score customers by recency, frequency, and monetary value
- Create business-friendly customer segments
- Build cohort retention matrix and heatmap

### Day 3

- Identify frequently bought-together product pairs
- Create Plotly interactive charts
- Write final insights and recommendations
- Polish notebook, README, and LinkedIn post

## Key Deliverables

- Clean Jupyter Notebook
- 10-12 polished visuals
- RFM segmentation
- Cohort retention heatmap
- Basic market basket analysis
- Final insights and business actions
- GitHub README
- LinkedIn post draft

## How To Run

```bash
pip install -r requirements.txt
jupyter notebook
```

Open `ECommerce_Customer_Analytics_EDA.ipynb`, update `DATA_PATH`, and run the notebook top to bottom.

## Portfolio Notes

This project is designed for GitHub and LinkedIn sharing. Keep markdown explanations concise, place business insights under each major chart, and make sure every insight includes a recommended business action.