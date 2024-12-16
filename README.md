# About the Dataset

## Context
Using the **Alpha Vantage Rapid API**, weekly time series data was obtained for global equity, covering over 20 years of historical data. This dataset includes the last trading day of each week along with key metrics such as weekly open, high, low, close prices, and weekly trading volume.

---

## Content
### Index and Features of the Dataset (After Extraction and Cleaning)

| Name      | Feature/Index | Type       | Description                                                                                     |
|-----------|---------------|------------|-------------------------------------------------------------------------------------------------|
| **Index** | datetimes     | -          | Weekly date of stock traded                                                                     |
| **open**  | Feature       | float      | The price at which a stock started trading when the opening bell rang.                         |
| **high**  | Feature       | float      | The highest price at which a stock traded during a period.                                     |
| **low**   | Feature       | float      | The lowest price at which a stock traded during a period.                                      |
| **close** | Feature       | float      | The price of an individual stock when the stock exchange closed shop for the day.              |
| **volume**| Feature       | float      | The total number of shares traded in a security over a period.                                 |

---

## Acknowledgements
**RapidAPI** is a great platform to find, connect to, and manage thousands of APIs.
