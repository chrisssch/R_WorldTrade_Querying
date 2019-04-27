# Querying Data in R using World Trade Data

International Trade was one of my favorite subjects in my economics studies, and product-level trade data lends itself well for practicing data wrangling and querying in a SQL-like fashion with the dplyr package.

The trade data was downloaded from the [UN Comtrade Database](https://comtrade.un.org/data). The dataset contains import and export volumes of 96 product categories ([HS2 classification](https://en.wikipedia.org/wiki/Harmonized_System) in USD for all countries to/from all trade partner countries (partner) in the year 2016 - 920,000 observations of pairwise trade flows in total. GDP data for the same year is also used.
