# DAX Measures Used in Finance Analytics Dashboard

## 1. Total Amount

```DAX
Total Amount =
SUM(Finance_Transactions[Amount])
```

## 2. Total Transactions

```DAX
Total Transactions =
DISTINCTCOUNT(Finance_Transactions[Transaction ID])
```

## 3. Average Transaction Value

```DAX
Average Transaction =
AVERAGE(Finance_Transactions[Amount])
```

## 4. Total Fees

```DAX
Total Fees =
SUM(Finance_Transactions[Fee Amount])
```

## 5. Total Tax

```DAX
Total Tax =
SUM(Finance_Transactions[Tax Amount])
```
## Time Intelligence Function

## 1.Previous Year Amount

```DAX
Previous Year Amount =
CALCULATE(
    [Total Amount],
    SAMEPERIODLASTYEAR(Calendar[Date]))
```

## 2.YoY Amount

```DAX
YoY Amount =
[Total Amount] -
[Previous Year Amount]
```

## 3.YoY Amount %

```DAX
YoY Amount % =
DIVIDE(
    [YoY Amount],
    [Previous Year Amount])
```

## 4.Previous Year Transactions

```DAX
Previous Year Transactions =
CALCULATE(
    [Total Transactions],
    SAMEPERIODLASTYEAR(Calendar[Date]))
```

## 5.YoY Transactions

```DAX
YoY Transactions =
[Total Transactions] -
[Previous Year Transactions]
```

## 6.YoY Transactions %

```DAX
YoY Transactions % =
DIVIDE(
    [YoY Transactions],
    [Previous Year Transactions])
```

## 7.Previous Year Fees

```DAX
Previous Year Fees =
CALCULATE(
    [Total Fees],
    SAMEPERIODLASTYEAR(Calendar[Date]))
```

## 8.YoY Fees %

```DAX
YoY Fees % =
DIVIDE(
    [Total Fees] - [Previous Year Fees],
    [Previous Year Fees])
```

## 9.Previous Year Tax

```DAX
Previous Year Tax =
CALCULATE(
    [Total Tax],
    SAMEPERIODLASTYEAR(Calendar[Date]))
```

## 10.YoY Tax %

```DAX
YoY Tax % =
DIVIDE(
    [Total Tax] - [Previous Year Tax],
    [Previous Year Tax])

## Dynamic Metrics

## 1.Selected Year

```DAX
Selected Year =
SELECTEDVALUE(Calendar[Year])
```

## 2.Selected Dynamic Metric

```DAX
Selected Dynamic Metric =
SELECTEDVALUE('Dynamic Metric'[Dynamic Metric])
```
