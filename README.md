# Credit-Card-Fraud-Forensics
This project aims to take simulated transaction data (specifically from the U.S), and build various ML algorithms of the feature of whether the transaction was fraudulent or not.

I perform initial data wrangling for EDA with various python visualizations. After identifying the most important features, more data wrangling is done to remove
non-important features to avoid multi-collinearity, and I build 9 different models. I then analyze the performance of each model with a confusion matrix, 3 statistical metrics (precision, recall, and F-1 score), and a cumulative ROC/AUC plot at the end. Ideally, one would use the highest performing model for deployment. 

Further extension of this project could look at credit card data from other regions of the world, or subset the data based on features like categories, to see if better performing models are possible with honing down the analysis.

This repo holds the Juypter Notebook file for this project, alongside a knitted PDF of the notebook alongside results for quick reference. I also briefly explain certain concepts in the notebook that may not be well known.
If you would like to run the notebook, you can using any general environment that supports Juypter notebooks. All the required packages are installed within the notebook, so there is no need to install the packages locally if you do not want to. 

However, you will have to change the file path for the data files for this project. Install them from the source link at the top of the notebook, and edit the file path accordingly. Also, I was unsuccessful with setting the random seed for reproducible results, so if you run the notebook, you will most likely get slightly different results than what is shown in my knitted PDF.
