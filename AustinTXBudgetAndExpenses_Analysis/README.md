This folder contains budgetary and expenditure data for the city government of Austin, TX for Quarter 3 of the year 2024. The dataset was downloaded from (https://data.austintexas.gov/Budget-and-Finance/Program-Budget-Operating-Budget-Vs-Expense-Raw-Dat/g5k8-8sud/about_data) on 28 Sept 2024 and is also included in this repo. The data storage (Blob Storage), processing (Data Factory), SQL server and database-hosting (SQL Server), and SQL analysis (Data Studio) of the data was all done using the Microsoft Azure ecosystem. The files here are:

Program_Budget_Operating_Budget_Vs_Expense_Raw_Data_20240928.csv - The original dataset in .csv format

AustinTxBudgetAnalysis.ipynb - Jupyter notebook walks through a Microsoft SQL Server analysis of the dataset.

austintx_powerbi.pbix - The Power BI file for the report (screenshots shown at the bottom of the Jupyter notebook). If you have Power BI Desktop on a Windows machine, you (should?) be able to load this and interact with it.

AustinTX_KPrototypesAndAgglomClust.ipynb - Jupyter Notebook made using Azure Synapse Analytics. Uses K-Prototypes, Gower's distance, and Hierarchical Agglomerative clustering to cluster the data using the budgets and expenditures of the logs.

kproto_20.pkl - Pickled instance of the trained K-Prototypes model using kmodes version 0.12.2.
