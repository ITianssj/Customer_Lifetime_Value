# Customer_Lifetime_Value
# Buy 'Til You Die: Customer Lifetime Value Prediction

![Alt text](clv.jpg)

## Problem 

- A client should be regarded as having a higher churn risk if they used to make a purchase once every 20 days on average but have been inactive for 50 days. She might be about to choose a competitor's product line instead of our company. When our tool alerts the marketing team to consumers with high churn risks, they can consider discounts, promotions, and other outreach measures.
- We need a model that alerts us to clients who are at risk of leaving. Additionally, we want it to forecast how much each customer will spend. Additionally, it ought to determine the lifetime values of each of our clients while we're at it.


## Solution 

- These techniques are known as Buy 'Til You Die Models in data science. BTYD (Wikipedia): From a customer's "birth" (when she places her first purchase with our company) to the day of her "death" (when she chooses a rival and is hence dead to us, the firm she has spurned).

# Customer Lifetime Value Prediction using Gamma-Gamma Model

## Introduction

This repository contains the code and analysis for predicting customer lifetime value (CLV) using the Gamma-Gamma model.

## Data

The data used in this analysis is located in the `data` directory. The dataset contains customer transactions with the following columns:

* `customer_id`: Unique identifier for each customer
* `transaction_date`: Date of the transaction
* `item_id`: Unique identifier for each item purchased
* `price`: Price of the item

## Methodology

The Gamma-Gamma model is used to predict CLV. The model is implemented using the `lifetimes` library in Python. The following steps are taken to predict CLV:

1. Preprocess the data to create a summary of customer transactions
2. Fit the Gamma-Gamma model to the data
3. Calculate the expected CLV for each customer

## Results

The results of the analysis are presented in the `results` directory. The directory contains the following files:

* `clv_predictions.csv`: Contains the predicted CLV for each customer
* `clv_summary.pdf`: Contains a summary of the CLV predictions and visualizations

## Usage

To run the analysis, follow the steps below:

1. Clone the repository
2. Install the required libraries using `pip install -r requirements.txt`
3. Run the `clv_main.py` script to generate the CLV predictions

## References

* Fader, P. S., Hardie, B. G., & Lee, K. L. (2005). "Counting Your Customers" One by One: A Hierarchical Bayes Extension to the Pareto/NBD Model. Marketing Science, 24(2), 275-293.
* Lifetimes library: <https://pypi.org/project/Lifetimes/>

## License

This repository is licensed under the MIT License.
