# International Debt Statistics Analysis (SQL)

- **This is a DataCamp-guided project.**

*Click [here](https://github.com/Man-of-principle/International-Debt-Statistics-Anaysis-SQL-/blob/main/Analyze%20International%20Debt%20Statistics%20Notebook%20.ipynb) to access my solutions (notebook)*
-------
It's not that we humans only take debts to manage our necessities. A country may also take debt to manage its economy. For example, infrastructure spending is one costly ingredient required for a country's citizens to lead comfortable lives. [The World Bank](https://www.worldbank.org) is the organization that provides debt to countries.

In this notebook, we are going to analyze international debt data collected by The World Bank. The dataset contains information about the amount of debt (in USD) owed by developing countries across several categories. We are going to find the answers to questions like: 

- What is the total amount of debt that is owed by the countries listed in the dataset?
- Which country owns the maximum amount of debt and what does that amount look like?
- What is the average amount of debt owed by countries across different debt indicators?

![image](https://github.com/Man-of-principle/International-Debt-Statistics-Anaysis-SQL-/assets/126421029/66245588-dce9-45ef-9e62-d1f96bb738a1)

Below is a snapshot of the database you will be working with: Click [here](https://github.com/Man-of-principle/International-Debt-Statistics-Anaysis-SQL-/blob/main/Analyze%20International%20Debt%20Statistics%20data%20set.csv) to download/view the complete Dataset 

|country_name|country_code|indicator_name                                                    |indicator_code|debt       |
|------------|------------|------------------------------------------------------------------|--------------|-----------|
|Afghanistan |AFG         |"Disbursements on external debt, long-term (DIS, current US$)"    |DT.DIS.DLXF.CD|72894453.7 |
|Afghanistan |AFG         |"Interest payments on external debt, long-term (INT, current US$)"|DT.INT.DLXF.CD|53239440.1 |
|Afghanistan |AFG         |"PPG, bilateral (AMT, current US$)"                               |DT.AMT.BLAT.CD|61739336.9 |
|Afghanistan |AFG         |"PPG, bilateral (DIS, current US$)"                               |DT.DIS.BLAT.CD|49114729.4 |
|Afghanistan |AFG         |"PPG, bilateral (INT, current US$)"                               |DT.INT.BLAT.CD|39903620.1 |
|Afghanistan |AFG         |"PPG, multilateral (AMT, current US$)"                            |DT.AMT.MLAT.CD|39107845   |
|Afghanistan |AFG         |"PPG, multilateral (DIS, current US$)"                            |DT.DIS.MLAT.CD|23779724.3 |
|Afghanistan |AFG         |"PPG, multilateral (INT, current US$)"                            |DT.INT.MLAT.CD|13335820   |
|Afghanistan |AFG         |"PPG, official creditors (AMT, current US$)"                      |DT.AMT.OFFT.CD|100847181.9|
|Afghanistan |AFG         |"PPG, official creditors (DIS, current US$)"                      |DT.DIS.OFFT.CD|72894453.7 |

