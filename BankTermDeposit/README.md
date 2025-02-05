# posit Prediction - Exploratory Data Analysis (EDA)

## Overview

This project performs **Exploratory Data Analysis (EDA)** on a dataset related to bank term deposit subscriptions. The dataset contains **41,188 observations and 21 columns**, including demographic, financial, and economic features that influence a customer's likelihood of subscribing to a term deposit.

## Dataset Description

The dataset consists of the following types of variables:

- **Demographic Features:** `age`, `job`, `marital`, `education`
- **Financial Status:** `default`, `housing`, `loan`
- **Campaign Information:** `contact`, `month`, `day_of_week`, `duration`, `campaign`
- **Economic Indicators:** `emp.var.rate`, `cons.price.idx`, `cons.conf.idx`, `euribor3m`, `nr.employed`
- **Target Variable:** `y` (indicates whether the customer subscribed to the term deposit)

## Key Findings from EDA

- **Age Distribution:** Customers range from **17 to 98 years**, with an average age of **40.02**.
- **Call Duration:** Highly variable, with some extreme outliers.
- **Previous Contacts (****`pdays`****)**: Most values are `999`, suggesting they were not previously contacted.
- **Employment and Interest Rates:** Economic variables like `emp.var.rate` and `euribor3m` play a role in customer decisions.
- **Most Common Job:** The most frequent job category is **"admin."**
- **Marital Status & Education:** Majority of customers are **married** and hold a **university degree**.
- **Contact Method:** Most customers were contacted via **cellular**.
- **Campaign Timing:** May is the most common month for marketing campaigns.

## Project Structure

- **`TermDepositPredictionEDA.ipynb`** - Jupyter Notebook containing the full EDA process.

## Requirements

To run this project, install the necessary Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/TermDepositPredictionEDA.git
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook TermDepositPredictionEDA.ipynb
   ```
3. Run the notebook cells to explore the dataset and visualizations.

## Future Work

- Perform **feature engineering** for predictive modeling.
- Apply **machine learning algorithms** to predict customer subscription likelihood.

## Author

## Author
👤 ABINASH SASIKUMAR\
📧 [abinash.avm@gmail.com]  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/abinashsasikumar)  
📸 [Instagram](https://www.instagram.com/cheabi17)  
💻 [GitHub Profile](https://github.com/abinashsasi)



