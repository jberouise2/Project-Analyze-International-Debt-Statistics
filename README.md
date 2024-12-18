# Project-Analyze-International-Debt-Statistics

![](image.jpg)

It's not that we humans only take debts to manage our necessities. A country may also take debt to manage its economy. For example, infrastructure spending is one costly ingredient required for a country's citizens to lead comfortable lives. [The World Bank](https://www.worldbank.org) is the organization that provides debt to countries.  

## `Task`
In this notebook, we are going to analyze international debt data collected by The World Bank. The dataset contains information about the amount of debt (in USD) owed by developing countries across several categories. We are going to find the answers to questions like: 

- What is the total amount of debt that is owed by the countries listed in the dataset?
- Which country owes the maximum amount of debt and what does that amount look like?
- What is the average amount of debt owed by countries across different debt indicators?

Below is a basic schema of the database we will be working with:

## `debt_indicators` table

| Column | Definition | Data Type |
|-|-|-|
|country_name|Name of the country|`varchar`|
|country_code|Code representing the country|`varchar`|
|indicator_name|Description of the debt indicator|`varchar`|
|indicator_code|Code representing the debt indicator|`varchar`|
|debt|Value of the debt indicator for the given country (in current US dollars)|`float`|

## `Solution`  
[sql_notebook_solution](https://github.com/jberouise2/Project-Analyze-International-Debt-Statistics/blob/379e308621115a10d3b4299277e192caaefc18f9/notebook.ipynb)
