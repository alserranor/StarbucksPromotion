# Starbucks Promotions
This project provides a Machine Learning approach to personalise Starbucks product promotions to customers based on past transactions.

The data sets contain simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. In the dataset, there are three different types of offer:
 - Informational: A mere promotion of a product without reward or minimum spending
 - BOGO (Buy One Get One): As the name states, spending a certain amount on products is rewarded by doubling the products bought
 - Discount: Spending some amount is rewarded by reducing the price of the next product to be bought

After the implementation of a K-Nearest Neighbors (chosen between 5 ML models), a prediction accuracy of 99.75% has been achieved, of the promotions that should be targeted to each specific customer demographic.

##  Contents
 - Starbucks.ipynb: Jupiter notebook with the data processing and model set-up and training <br>
 - data/portfolio.json: Dataset containing offers metadata <br>
 - data/profile.json : Dataset containing customers metadata <br>
 - data/transcript.json : Dataset containing interaction customer-offers <br>

## Libraries
 - Numpy <br>
 - Pandas <br>
 - Matplotlib <br>
 - Seaborn <br>
 - Scikit-learn <br>

## Instructions
Download the data and Starbucks.ipynb and run it using Jupyter notebook.

A blog post with the findings of the analysis can be found [here](https://medium.com/@albertoserrano/optimising-starbucks-product-promotions-7f5ebfdb8ffc).

## License
The code used in this repository is licensed under a MIT license included in LICENSE.

## Acknowledgements
Must give credit to Udacity, and Starbucks for providing the dataset.

