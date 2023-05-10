Data Description
====

Raw CSV samples are [here](https://github.com/hackathonBI/CCS/tree/master/sample%20data).

## Customers

CustomerID|Segment|Currency
----------|-------|--------
        10| LAM   |EUR
       100| LAM   |EUR
      1000| KAM   |CZK
     10000| SME   |CZK
     10001| SME   |CZK

## Gas Stations

SiteID|chainID|Country|Segment
------|-------|-------|-------
   100|     10|CZE    |Other
  1000|      1|CZE    |Premium
  1001|      8|CZE    |Value for money
  1002|     24|CZE    |Discount
  1003|     13|CZE    |Value for money

## Products

ProductID|Description
---------|-----------
1        |Rucní zadání
10       |Mazadla/Tuky
100      |Membership-fee Consorcio
101      |Diesel
102      |Biodiesel

## Transactions

Date|Time|CustID|CardID|GasStationID|ProdID|Amount|Price
----|----|----------|------|------------|---------|------|-----
2012-01-01| 00:18:00| 41113| 645177| 363| 2|  93.75| 2038.575
2012-01-01| 02:05:00| 30766| 496967|1083| 2| 132.10| 3002.692
2012-01-01| 00:27:00| 31576| 618868| 109| 5|  21.35| 462.924
2012-01-01|06:56:00 |  3800| 598481|5298|322|52.500| 47.0239
2012-01-01|05:46:00 |  3493|  34405|5163|317|70.000| 61.831



## Business Questions

CCS's list of business problems: [TASKS](https://github.com/hackathonBI/CCS/blob/master/Tasks.md).
