# Credit-Card-Fraud-Forensics

## Project Introduction
This project aims to take simulated transaction data (specifically from the U.S), and build various ML algorithms of the feature of whether the transaction was fraudulent or not.

# Dataset Information

I used the dataset linked here: https://www.kaggle.com/datasets/kartik2112/fraud-detection. The dataset is set up so that there is already a training and testing dataset, but I chose to concatenate these files together and do my own randomized train/test split.

## Project Overview 
I perform initial data wrangling for EDA with various python visualizations. After identifying the most important features, more data wrangling is done to remove
non-important features to avoid multi-collinearity, and I build 9 different models. I then analyze the performance of each model with a confusion matrix, 3 statistical metrics (precision, recall, and F-1 score), and a cumulative ROC/AUC plot at the end. Ideally, one would use the highest performing model for deployment. 

I have a few screenshots of the visualizations from the script as a sneak peek below.

#### EDA
<img width="407" alt="Screenshot_26" src="https://github.com/user-attachments/assets/8e39f982-d232-4cbe-b07a-fb569b07eccc">

<img width="661" alt="Screenshot_27" src="https://github.com/user-attachments/assets/7d06eb75-a0ef-49e9-a8b3-f9ead266e587">

#### Results of Decision Tree Model 

<img width="400" alt="Screenshot_28" src="https://github.com/user-attachments/assets/f8280b11-a82d-457f-b914-25e90461484c">

<img width="379" alt="Screenshot_29" src="https://github.com/user-attachments/assets/a22786b3-8d00-4833-9621-3298fd8b4095">

#### Final Model Results

<img width="435" alt="Screenshot_30" src="https://github.com/user-attachments/assets/eb564a23-d3cd-4212-b3b9-a96970ec0f6d">

## Repo Overview & Instructions For Deployment

This repo holds the Juypter Notebook file for this project, alongside a knitted PDF of the notebook alongside results for quick reference. I also briefly explain certain concepts in the notebook that may not be well known.

If you would like to run the notebook, you can using any general environment that supports Juypter notebooks. All the required packages are installed within the notebook, so there is no need to install the packages locally if you do not want to. 

However, you will have to change the file path for the data files for this project. Install them from the source link at the top of the notebook, and edit the file path accordingly. 

## Special Note

I was unsuccessful with setting the random seed for reproducible results, so if you run the notebook, you will most likely get slightly different results than what is shown in my knitted PDF.

## Future Work

Further extension of this project could look at credit card data from other regions of the world, or subset the data based on features like categories, to see if better performing models are possible with honing down the analysis.

## License

Distributed under the MIT License. See LICENSE.txt for more information.
