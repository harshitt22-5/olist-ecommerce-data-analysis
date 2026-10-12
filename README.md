# Brazilian E-Commerce Data Analysis

## Project Overview
This project analyzes the Brazilian E-Commerce Public Dataset by Olist to explore sales performance, customer purchasing behaviour, product categories, delivery performance, and customer reviews.

The goal is to turn raw e-commerce data into useful business insights that can support better operational and customer-experience decisions.

## Business Questions
- How does delivered sales value change over time?
- Which product categories contribute the most to delivered sales value?
- How do one-time and repeat customers compare in purchasing behaviour?
- How frequently are orders delivered later than estimated?
- Is delivery timeliness associated with customer review scores?
- Which product categories have higher one-star review rates?

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook

## Analysis Performed
- Data loading, cleaning, and datetime conversion
- Order and payment aggregation
- Monthly delivered item-value analysis
- Customer purchasing and repeat-customer analysis
- Product and category performance analysis
- Delivery-time and late-delivery analysis
- Customer review-score analysis

## Key Findings
- Delivered orders accounted for 96,478 orders in the dataset.
- The on-time delivery rate was approximately 91.89% among orders with both actual and estimated delivery dates available.
- Repeat customers represented a small share of delivered customers but had higher average payment value per customer than one-time customers.
- Late-delivered orders had lower average review scores than on-time-delivered orders.
- Health and beauty, watches and gifts, and bed, bath and table were among the leading categories by delivered item value.

## Project Files
- `notebooks/ecommerce_analysis.ipynb` — notebook containing the analysis.
- `data/` — local dataset files used by the notebook; raw data is not included in the public repository.

## Dataset
Brazilian E-Commerce Public Dataset by Olist, available through [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

## How to Run
1. Clone or download this repository.
2. Install the required Python packages.
3. Download the dataset and place the required CSV files in the `data/` folder.
4. Open `notebooks/ecommerce_analysis.ipynb` in Jupyter Notebook.
5. Run the notebook cells from top to bottom.

## Notes
This is an exploratory data analysis project. The findings describe patterns and associations in the dataset and should not be interpreted as proof of causation.