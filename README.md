# Customer Shoppping Trends

This repository contains an analysis of the Customer Shopping Trends Dataset, aimed at uncovering insights into consumer behavior and purchasing patterns. The project is structured into three main components: exploratory data analysis (EDA), SQL queries for answering business questions, and a Tableau dashboard for visualizing customer segmentation.

## About the Dataset

The Customer Shopping Preferences Dataset is a synthetic dataset created for educational purposes, facilitating learning in data analysis and machine learning. It includes data on customer attributes such as age, gender, purchase history, preferred payment methods, frequency of purchases, and more. This dataset is ideal for businesses looking to understand customer preferences, optimize product offerings, and enhance customer satisfaction.

**Data Source:** https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset/data

### Dataset Details

- **Records:** 3900
- **Columns:** Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount (USD), Location, Size, Color, Season, Review Rating, Subscription Status, Shipping Type, Discount Applied, Promo Code Used, Previous Purchases, Payment Method, Frequency of Purchases.

## Project Structure

- `Exploratory_Analysis.ipynb`: A Jupyter notebook containing the exploratory data analysis (EDA) of the dataset. This notebook provides initial insights into the data, including distributions of various features and preliminary data cleaning steps.
  
- `SQL_Analysis.ipynb`: This notebook contains SQL queries used to answer specific business questions regarding customer behavior and purchasing patterns. It includes queries for analyzing aspects such as purchasing behaviors between the different customer groups, promo code usage rates, and product category preferences.

- Tableau Dashboard: A Tableau dashboard that visualizes the customer segments. This visualization helps in understanding different customer groups and their preferences, aiding in targeted marketing strategies. <br>
Dashboard: https://public.tableau.com/app/profile/vish.ramesh/viz/ShoppingTrendsDashboard_17119387864360/TheDashboard

## How to Use

1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook installed to view and interact with `.ipynb` files. You can install it via Anaconda or pip.
3. Open `Exploratory_Analysis.ipynb` and `SQL_Analysis.ipynb` in Jupyter Notebook to view the analysis.
4. To view the Tableau dashboard, click on the link above.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn (for Python notebooks)
- A SQL database setup if you wish to run the SQL queries directly (details for setup not provided here).


## Acknowledgments

This dataset and project are for educational purposes, designed to assist in learning data analysis, SQL querying, and data visualization techniques.

---

*Note: This is a synthetic dataset created for educational purposes. Any resemblance to real data is purely coincidental.*
