## Assignment

In the [`data`](data) folder you will find a json that was returned from an API.

This file contains the number of searches done on bol.com for specific keywords
in the past 48 months.

The customer wants to have this data in a datawarehouse, as follows:

| search_term | country_code | period_year | period_month | n_searches |
|:---|:---:|:---:|:---:|---:|
| vloerventilator | BE | 2021 | 7 | 121 |
| vloerventilator | NL | 2021 | 7 | 782 |
| ... | ... | ... | ... | ... |

Create a csv or parquet file that has the data in the correct format.

Use [pandas](https://pandas.pydata.org/docs/) or [duckdb](https://duckdb.org/docs/stable/clients/python/overview.html) to make the transformation.