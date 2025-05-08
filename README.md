# Azure Data Factory Project: Bank Transaction Ingestion

This sample Azure Data Factory (ADF) project demonstrates how to ingest and transform banking transaction data from a file and load it into a staging table for further analysis or ETL.

## 📚 Project Overview

The project is designed to simulate a real-world financial data ingestion pipeline. It consists of two pipelines and one data flow, demonstrating file reading, basic transformations, and loading into a staging SQL table.

---

## 🔧 Components

### 🧩 Pipelines

- **PL_Read_BankTransactions.json**  
  Reads a bank transaction file (e.g., CSV) from a data lake or blob storage and initiates validation and processing.

- **PL_Load_To_Staging.json**  
  Loads validated transactions into a staging table in an Azure SQL database or Synapse.

### 💧 Data Flow

- **DF_Transform_Transactions.json**  
  Performs transformations on the raw transaction data, such as:
  - Column renaming
  - Date parsing
  - Data type conversions
  - Null handling
---

## 🔗 Author

**Ali Parva**  
💼 Data Engineer | Expert in ETL, SSIS, Azure Data Factory  
🌍 [LinkedIn](#) | [GitHub](#)  

---

## 📝 License

This project is for demonstration and learning purposes.
