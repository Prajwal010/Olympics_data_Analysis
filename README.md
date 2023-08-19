# Olympics_data_Analysis

1) Olympics data in csv is loaded into source of Azure data factory using HTTP Api
2) Used copy activity to move data from source to 'raw' folder in Azure data lake gen 2 
3) Raw data is transformed in Azure Databrics and moved into Transformed folder in ADLS
4) Transformed data is loaded into Azure synapse analytics
5) Schema and Table is created out of required columns
6) Built dashboard of the anaytics queries in Tableau.


![Olympics_DF](https://github.com/Prajwal010/Olympics_data_Analysis/assets/91496751/c838dce6-f7d1-447e-bf0a-362d8ed065f0)
