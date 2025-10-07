# E-Commerce-Funnel-Analysis

The dataset for this project is sourced from the UC Irvine Machine Learning Repository. You can find the detailed explanation of the dataset and links to download the dataset at the link given here : https://archive.ics.uci.edu/dataset/352/online+retail

This dataset is a real world dataset sourced from a UK-based online retailer. This is a good sized dataset that will allow for advanced analytics while not being so huge as to slow down your system. This dataset contains a single data table, which will be the fact table and provides us with the details regarding the transactions. The columns in this table are InvoiceNo, StockCode, Description, Qunatity, InvoiceDate, UnitPrice, CustomerID and Country.

In this project, I will be exploring the more advanced features of Power BI. I will be analyzing the customer's purchasing behaviour, attempting to discover patterns in the sales funnel and segment customers using RFM(Recency, Frequency, Monetary) analysis to identify high-value segments and areas for improvement.

## Data Preparation
For the purpose of this project, I will not be looking at cancellations. So, I have removed those records from the dataset. I have also removed rows with CustomerID missing. I have added a custom column to the dataset for the total amount of the order, which is calculated as Quantity * UnitPrice.

## Data Modeling
The original dataset only contains the fact table that we will using in this project. We also need to create a supporting dimension table for Calendar and Products.
