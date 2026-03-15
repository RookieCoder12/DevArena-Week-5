# DevArena-Week-5

## Overview
This project analyzes **sales performance and customer churn trends** using transactional and customer data. The goal of the analysis is to identify patterns in sales performance across different months, product categories, and regions, as well as to examine factors contributing to customer churn.

During the preprocessing stage, the datasets were cleaned and prepared for analysis. Monthly trends for **sales, number of orders, and quantity sold** were examined to understand overall business performance. In addition, product category sales trends and regional performance were analyzed to identify fluctuations in revenue.

The project also investigates **customer churn**, including churn percentage, contract types associated with churn, and payment methods contributing the most revenue. These insights help identify potential business risks and opportunities for improving customer retention and revenue growth.

## Files
- `sales_data.csv` - <b>CSV file</b> that contains the data for the sales for the first 4 months of the year.

- `customer_churn.csv` - <b>CSV file</b> that contains the data the cutsomer, their customer id, payment menthod, whether they are senior citizen or not and whther have churned or not.

- `Analysis Report.pdf` - <b>PDF file</b> that consists of the <b>executive summary</b>, <b>insights</b> and <b>recommendation</b> for analysis in different domains for which the data were given in the dataset. 

- `customer_analysis.ipynb` – Main Python Notebook containing the exploratory data analysis (EDA), data preprocessing, and visualizations created during the analysis.

- `requirements.txt` – File containing the Python libraries required to run the project.

## Getting Started

### Prerequisites
Ensure you have Python 3.x installed on your system.

### Cloning Repository
Cloning the repository:
```zsh
git clone https://github.com/RookieCoder12/DevArena-Week-5.git
```

### Installation
Install the required dependencies:
```zsh
pip install -r requirements.txt
```

### Running the Project

#### Running the Python Notebook
1. Run jupyter notebook:
```zsh
jupyter notebook
```
2. Open ```customer_analysis.ipynb```

## Structure
In this project, **Exploratory Data Analysis (EDA)** was performed on both sales data and customer churn data to uncover trends and business insights.

During the preprocessing phase, the datasets were cleaned and prepared for analysis. The sales dataset was analyzed to evaluate **monthly revenue trends, number of orders, and quantity sold,** which revealed noticeable fluctuations across the observed period. The analysis indicated that performance was relatively strong during the initial months, followed by a decline toward the end of the period.

Further analysis was conducted on product categories, including Headphones, Laptops, Monitors, Phones, and Tablets. The results showed that some categories experienced fluctuating demand while others demonstrated a steady decline, suggesting potential changes in customer preferences.

Regional analysis was also performed to compare sales across **East, North, South, and West** regions, highlighting differences in revenue trends and order volumes across locations.

In addition to sales analysis, **customer churn analysis** was conducted to evaluate customer retention patterns. The results showed that approximately **10.6% of customers churned during the analyzed period.**

Most of the churned customers were associated with month-to-month contracts, suggesting that longer-term contracts may help improve retention.

The analysis also identified **Credit Card** as the highest revenue-generating payment method, contributing approximately **36% of total revenue**.

Overall, the insights from this analysis can help businesses understand sales trends, identify declining product demand, improve customer retention strategies, and optimize payment and contract structures.