DAX Measures Used in Finance Analytics Dashboard


1. Total Amount
   Total Amount = SUM(Finance_Transactions[Amount])

2. Total Transactions
   Total Transactions = DISTINCTCOUNT(Finance_Transactions[Transaction ID])

3.Average Transaction Value
  Average Transaction = AVERAGE(Finance_Transactions[Amount])

4.Total Fees
  Total Fees = SUM(Finance_Transactions[Fee Amount])

5.Total Tax
  Total Tax = SUM(Finance_Transactions[Tax Amount])

6.Previous Year Amount
  Previous Year Amount =CALCULATE([Total Amount],SAMEPERIODLASTYEAR(Calendar[Date]))

7.YoY Amount
  YoY Amount = [Total Amount] -[Previous Year Amount]

8.YoY Amount %
  YoY Amount % =DIVIDE([YoY Amount],[Previous Year Amount])

9.Previous Year Transactions
  Previous Year Transactions =CALCULATE([Total Transactions],SAMEPERIODLASTYEAR(Calendar[Date]))

10.YoY Transactions
   YoY Transactions =[Total Transactions] - [Previous Year Transactions]

11.YoY Transactions %
   YoY Transactions % = DIVIDE([YoY Transactions],[Previous Year Transactions])

12.Previous Year Fees 
   Previous Year Fees = CALCULATE([Total Fees],SAMEPERIODLASTYEAR(Calendar[Date]))

13.YoY Fees %
   YoY Fees % = DIVIDE([Total Fees] - [Previous Year Fees],[Previous Year Fees])

14.Previous Year Tax
   Previous Year Tax = CALCULATE([Total Tax],SAMEPERIODLASTYEAR(Calendar[Date]))

15. YoY Tax %
    YoY Tax % = DIVIDE([Total Tax] - [Previous Year Tax],[Previous Year Tax])

16.Selected Year
   Selected Year = SELECTEDVALUE(Calendar[Year])

17.Selected Dynamic Metric
   Selected Dynamic Metric = SELECTEDVALUE('Dynamic Metric'[Dynamic Metric])
