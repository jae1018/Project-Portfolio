This folder contains analyses and modeling on parts of the Bing COVID-19 dataset which is available through the Azure Open Datasets catalog (found specifically at https://learn.microsoft.com/en-us/azure/open-datasets/dataset-bing-covid-19?tabs=azure-storage). The files included are:

Covid19_ImputationsWithRegression.ipynb - Attempts at imputing poor intervals of data for U.S. Covid statistics using polynomial regression, random forests, k-nearest neighbors, and gaussian processes.

Covid19_SqlAnalysis.ipynb - Walks through an investigation and SQL Server analysis of the original dataset using Azure Synapse Analytics.

ny_df.csv - The Covid statistics by counties of New York (used with the Tableau dashboard).

us_df.csv - The national-level covid statistics for the United States (used in the imputation notebook).

A Tableau dashboard of this dataset can be found on the Tableau Public server at https://tinyurl.com/53r3d79e.
