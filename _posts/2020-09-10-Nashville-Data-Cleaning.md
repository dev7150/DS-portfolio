---
title: "Nashville Housing data cleaning using SQL"
categories:
  - Blog
header:
  teaser: /assets/images/download.jfif
  image: /assets/images/sqll.png
tags:
  - SQL
  - readability
  - standard
---

Nashville housing data is used as the data source.
- Date is converted to standard format.
- Remove rows with nulls as property address.
- Use parsename and substring functions to split address into street, state and city.
- Convert 'Y' and 'N' to Yes and No.
- Remove duplicates using CTE.



### [SQL Query](https://github.com/dev7150/DataCleaningSQL)




