# Anomaly Detection in Credit Card Transactions using Power BI

## About:-
Anomaly detection in credit card transactions refers to the process of identifying unusual or fraudulent activities in credit card transactions. It involves applying statistical, machine learning, and Power BI techniques to detect patterns and deviations from normal behavior, helping to identify potentially fraudulent transactions in real-time.

## Project Overview:
The objective of this project is to develop a Power BI dashboard for anomaly detection in credit card transactions. Anomaly detection is crucial for detecting fraudulent activities and ensuring the security of credit card transactions. By leveraging Power BI's data visualization and analytical capabilities, we can create an interactive dashboard that provides insights into transaction patterns and identifies potential anomalies.

## Project Steps:
—----------------------------------------

### Dataset Info:

**step** - maps a unit of time in the real world. In this case 1 step is 1 hour of time. Total steps 744 (30 days simulation).
**type** - CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.
**amount** - amount of the transaction in local currency.
**nameOrig** - customer who started the transaction
**oldbalanceOrg** - initial balance before the transaction
**newbalanceOrig** - new balance after the transaction
**nameDest** - customer who is the recipient of the transaction
**oldbalanceDest** - initial balance recipient before the transaction. Note that there is no information for customers that start with M (Merchants).
**newbalanceDest** - new balance recipient after the transaction. Note that there is no information for customers that start with M (Merchants).
**isFraud** - This is the transactions made by the fraudulent agents inside the simulation. In this specific dataset the fraudulent behaviour of the agents aims to profit by taking control of customers accounts and try to empty the funds by transferring to another account and then cashing out of the system.

Import the Dataset given and follow the steps to accomplish the task



### Power BI Dashboard Creation:  

Launch Power BI and connect to the preprocessed credit card transaction dataset.
Design an intuitive and visually appealing dashboard layout with appropriate charts, tables, and filters.
Create visualizations that provide an overview of transaction statistics, such as total transactions, average transaction amount, and transaction frequency.

### Data Preprocessing: 

Perform data cleaning tasks, such as handling missing values and duplicates if needed.
Transform the data into a format suitable for Power BI, ensuring proper data types.

### DAX Function:

Perform all the below questions using DAX functions:

What is the average transaction amount for normal transactions versus fraudulent transactions?
How many credit card transactions were recorded in the dataset? And How many fraudulent credit card transactions were recorded in the dataset?
What is the highest Fraud transaction amount recorded?
Is there a significant difference in the maximum transaction amount for normal transactions compared to fraudulent transactions?
What is the percentage of fraudulent transactions in the dataset?
What is the distribution of transaction amounts? (using Clustered column chart)

### Anomaly Visualisation:

Develop visualizations that highlight potential anomalies in credit card transactions.
Use line charts, scatter plots, or heat maps to display transaction patterns and identify outliers.

Which merchants have the highest number of transactions? (Only Top 10) 
Create a scatter plot to visualize the relationship between 'oldbalanceOrg' and 'amount' columns.
Use a line chart to plot the transaction amount over time (step) to identify any unusual spikes or drops in transaction amounts.
Are there any merchants with a high occurrence of fraudulent transactions?


Also, Explain why do you think the above-mentioned charts are best to visualize the problem

### Documentation and Deployment:

Create summary sections or report pages that provide key insights derived from the transaction data.
Document the project details, including data sources, preprocessing steps, and dashboard features.
Remember to comply with data privacy and security regulations while working with credit card transaction data


By following these steps, you will be able to develop a comprehensive Power BI project on anomaly detection in credit card transactions, empowering users to identify and respond to potential fraud efficiently.
