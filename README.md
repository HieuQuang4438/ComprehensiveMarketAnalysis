# Comprehensive Market Analysis

## Data description
The original data is stored in the Excel file `sales.xlsx` (in "Data" folder). 
| Column | Description |
|---|---|
|InvoiceNumber|A 6-digit number uniquely assigned to an invoice. If the beginning of this number starts with a letter C, it means that the invoice has been cancelled. An invoice can consists of multiple rows, each row corresponds to a product.|
|ProductCode|A 5-digit number that is uniquely assigned to a product|
|ProductName|Product's name|
|Quantity|The number of orders of a product in the invoice|
|InvoiceDate|Invoice created date|
|UnitPrice|The price of a product per unit|
|CustomerId|A 5-digit number that in uniquely assigned to a customer|
|Country|The Customer's country of residence|

## Project contents
### ComprehensiveMarketAnalysis.ipynb
1. Cleaning & Processing
2. Exploration
3. Market Research
4. Customer Segmentation (RFM)
5. Retention analysis

Libraries: Numpy, Pandas, Matplotlib, Seaborn, Datetime.

### RetentionAnalysis.pdf
Providing insights and actionable suggestions based on retention analysis.

[References](https://github.com/eiliaJafari/Comprehensive-market-data-analysis/tree/main)