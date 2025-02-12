
# AZURE: Sales Data Ingestion and Analytics Pipeline  

## Overview  
Sales Analysis is a sales data pipeline that ingests, processes, and visualizes sales data using Azure SQL Database, SSMS, and Power BI. The project transforms raw sales data from CSV format into meaningful insights for decision-making.  

## Features  
- **Data Ingestion**: Importing sales data from CSV into Azure SQL Database using SSMS.  
- **Data Processing**: Structuring and querying data within Azure SQL.  
- **Data Visualization**: Creating interactive dashboards using Power BI.  
- **Security**: Role-based access control and data encryption in Azure SQL.  

## Tech Stack  
- **Azure SQL Database**  
- **SQL Server Management Studio (SSMS)**  
- **Power BI**  
- **CSV (Raw Data Format)**  

## Architecture  
1. **Data Source**: Sales data stored in CSV format.  
2. **Ingestion**: Data imported into Azure SQL using SSMS.  
3. **Processing**: SQL queries for data cleaning and transformation.  
4. **Visualization**: Power BI dashboard for analytics.  

## Database Schema  
The sales dataset consists of:  
- **OrderID** (INT): Unique identifier for orders.  
- **CustomerName** (VARCHAR): Name of the customer.  
- **PhoneNumber** (VARCHAR): Customer’s phone number.  
- **Location** (VARCHAR): City or region of the customer.  
- **Country** (VARCHAR): Customer’s country.  
- **StoreCode** (VARCHAR): Code identifying the store.  
- **Product** (VARCHAR): Name of the purchased product.  
- **Quantity** (INT): Number of units sold.  
- **Price** (FLOAT): Price per unit.  
- **Date** (DATE): Date of the transaction.  
- **CreditCardNumber** (Masked, VARCHAR): Customer’s masked credit card number.  
- **ExpiryDate** (DATE): Expiry date of the card.  

## How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Naren0225/Azure_SalesData-_Analysis/tree/main
   ```  
2. Set up the **Azure SQL Database** and import sales data using SSMS.  
3. Run SQL queries to clean and process data.  
4. Connect Power BI to Azure SQL and create visualizations.  

## Results  
- **Sales insights** using Power BI visualizations.  
- **Optimized SQL queries** for better data processing.  
- **Scalable database** structure using Azure SQL.  

## Future Enhancements  
- Automate data ingestion using **Azure Data Factory**.  
- Integrate **machine learning models** for sales forecasting.  
- Implement **real-time data processing** with Azure Stream Analytics.  

## Contributions  
Feel free to submit pull requests or raise issues for improvements!  

---
