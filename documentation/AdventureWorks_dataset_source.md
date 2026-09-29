# Dataset Source

## Dataset
**AdventureWorks Sales Dataset**

## Source Used
Raw CSV files were obtained from:

https://github.com/Tahascommit/PowerBI-Advance_Adventure_Works_Bike_Sales

Only the raw CSV files were used. The Power BI report, model, transformations, DAX measures, visuals, and analysis were created independently.

## Files Used
- AdventureWorks Calendar Lookup.csv
- AdventureWorks Customer Lookup.csv
- AdventureWorks Product Categories Lookup.csv
- AdventureWorks Product Lookup.csv
- AdventureWorks Product Subcategories Lookup.csv
- AdventureWorks Returns Data.csv
- AdventureWorks Territory Lookup.csv
- AdventureWorks Sales Data 2020.csv
- AdventureWorks Sales Data 2021.csv
- AdventureWorks Sales Data 2022.csv

## Preparation Summary
- Final Sales fact table: **56,046 rows**
- Final Customers table: **18,148 valid unique CustomerKeys**
- Malformed/source-metadata customer rows were removed.
- Optional missing customer attributes were retained rather than imputed.
- The Calendar table was marked as the Date table for time intelligence.

## Usage Note
The dataset is used for educational and portfolio analysis. Refer to the source repository and any original AdventureWorks licensing terms for redistribution guidance.
