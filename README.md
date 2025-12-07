# Azure Data Factory – End-to-End ETL/ELT Pipeline (ARM Deployment)

This repository contains an **Azure Resource Manager (ARM) Template** and corresponding **parameters file** used to deploy a complete Azure Data Factory setup.  
The solution automates ingestion, transformation, and export of datasets using Azure Blob Storage, Azure SQL Database, and Mapping Data Flows.


## Project Overview

This project demonstrates a full ETL workflow built in **Azure Data Factory**, capable of:

- Copying raw data from **Azure Blob Storage**
- Loading CSV data into **Azure SQL Database** (staging schema)
- Transforming PayPal transactions using a Mapping Data Flow
- Joining datasets and filtering successful transactions
- Exporting transformed data back to Blob Storage
- Deploying all components at once using ARM templates

The repository provides a **production-ready ADF configuration** fully defined in infrastructure-as-code.



