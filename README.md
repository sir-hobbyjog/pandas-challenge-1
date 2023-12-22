# pandas-challenge-1

#Data Analysis Using Pandas

##Overview

This project focuses on analyzing a dataset of client orders using Python and pandas. The analysis includes the calculation of subtotals, shipping prices, total prices, costs, profits, and provides a summary of the top clients.

##Features

- Data loading and initial exploration using pandas.
- Calculation of basic statistics and unique value counts.
- Identification of top item categories and subcategories.
- Analysis of top clients based on the number of entries.
- Computation of order subtotals, shipping prices, and total prices.
- Calculation of order costs and profits.
- Generation of a summary DataFrame for top clients with key financial metrics.

##Requirements

Python 3.x
pandas

##Installation

To set up the project environment:


git clone https://github.com/sir-hobbyjog/pandas-challenge-1
cd pandas-challenge-1
*If required, set up a virtual environment here*
pip install pandas

##Usage

To run the analysis, navigate to the project directory and execute the Jupyter notebook containing the analysis.


python your_script.py  *or open your Jupyter notebook*

##Data Description

The dataset (client_dataset.csv) contains client order information including client IDs, order IDs, item categories, quantities, prices, and weights. The data is used to derive insights into client ordering patterns and financial metrics.

##Results

The analysis script processes the dataset to output:

- The most common categories and subcategories of items ordered.
- The top clients by number of orders.
- Financial summaries for each order and client, including revenue and profit.
- A formatted summary of top clients sorted by total profit.

