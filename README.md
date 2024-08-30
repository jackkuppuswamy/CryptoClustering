# Crypto Clustering
## Overview
This project aims to analyze and cluster various cryptocurrencies based on their market data, such as percentage price changes over different time periods. The analysis leverages machine learning techniques like K-Means clustering and Principal Component Analysis (PCA) to categorize cryptocurrencies into distinct groups, helping investors or analysts understand patterns or trends within the market.

## The forecast analysis is divided into four steps:

### Step 1: Find Unusual Patterns in Hourly Google Search Traffic
#### Objective: Identify anomalies or unusual patterns in the hourly Google search traffic data.
#### Tasks: 
1. Load and preprocess the hourly search traffic data.
2. Use statistical methods or visualization techniques to detect outliers and unusual trends.
# Structure of Jupyter notebook `Crypto_Clustering.ipynb`

## Importing Libraries:
- Necessary Python libraries such as pandas, scikit-learn, and os are imported.
- Environment variables are set to avoid warnings during the execution of the notebook.

## Data Loading:
- Market data for cryptocurrencies is loaded into a pandas DataFrame.

## Data Exploration:
- Summary statistics and data types of the market data are displayed to understand the structure and distribution of the data.

## Data Preprocessing:
- Data is scaled and cleaned, preparing it for the clustering process.

## Dimensionality Reduction:
- Principal Component Analysis (PCA) is applied to reduce the dimensionality of the data, making it easier to visualize and process.
## Clustering:
- K-Means clustering is performed on the preprocessed data to group cryptocurrencies into clusters.
- The optimal number of clusters is determined using the elbow method.

## Visualization:
- Clusters are visualized in a 2D plot, providing a graphical representation of how cryptocurrencies are grouped.

## Conclusion:
- The notebook concludes with insights drawn from the clustering results.

#### Tools and Libraries:

1. Python: The primary programming language for this challenge.
2. Jupyter Notebook
3. Libraries: os, pandas, and Scikit-learn.

#### Environment Setup:

1. Set up a Python environment with the necessary libraries installed.
2. Ensure you have access to a Jupyter Notebook or any other IDE for running your analysis scripts.
3. Clone the Repository:

    [[git clone https://github.com/jackkuppuswamy/CryptoClustering.git](https://github.com/jackkuppuswamy/CryptoClustering))

4. Navigate to the Project Directory:

    cd CryptoClustering

5. Run the Application: Start Jupyter Notebook Crypto_Clustering.ipynb file to interactively execute, analyze and predict the search traffic and its impact on trading the stock. 
    

# Contributing
Contributions are welcome! Fork the repository, create a branch, make your changes, and submit a pull request.