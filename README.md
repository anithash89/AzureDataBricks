# AzureDataBricks
![Azure Data bricks](https://user-images.githubusercontent.com/100298933/182228179-9ad491e8-e2bf-4441-b3c7-b80c7d6c8502.png)

DataBricks and DataFactory
Azure Databricks: End-to-end web-based analytics platform
Azure Databricks is a data analytics platform (PaaS), specially optimised for Microsoft Azure cloud platform. Databricks is an enterprise-grade platform service that is unified for data lake architecture for large analytical operations.

**Azure Data factory**
![Azure Data factory](https://user-images.githubusercontent.com/100298933/182228873-b2ff9dd4-45ae-4043-80ac-8cc27f5c830d.png)

This repository contains :
ETL pipeline : Using Data factory and Data bricks Python notebook 

1. Created Azure storage account
2. Created Azure Resource 
3. Created and saved the source files in container

Pipeline flow 
1.  Fetch the metadata schema using Get metadata in data factory
2.  validate the source data using If condition . 
    2.1 If the validation is success then copy the file from source to validate container and Run the Python code.
    2.2 If the columns failed validation, then copy the file from source to Reject container 
3.Run the Python code in the repository 

 
              
