# Analysis of the World Integrated Trade Solution (WITS) Data

## Introduction
The World Integrated Trade Solution (WITS) is a software application that provides access to international merchandise trade, tariff and non-tariff measures data. The data is collected from official sources and includes detailed imports and exports data by country and product. The data is available in different formats, including Excel, CSV, and API. The data is used by policymakers, researchers, and analysts to analyze trade patterns, assess the impact of trade policies, and identify opportunities for trade.

## Data
### Data Source
The particular dataset used in this exercise is the Trade in Services Database for the years 1985 - 2011. This data is available in the WITS database and can be downloaded in [CSV](http://wits.worldbank.org/data/public/trade/TSD_February2015.csv) or [ZIP](http://wits.worldbank.org/data/public/trade/TSD_February2015.zip) format.

### Data Description
The data contains the following columns:
- 'REP': Reporting country
- 'PAR': Partner country
- 'YEAR': Year
- 'BOP': Balance of Payments
- 'VALUE': Value of trade
- 'DESCRIPTION': Description of trade
- 'NAME': Name of trade

Each of the columns follows a specific standard which will be explained in the data cleaning section.

## Exploratory Data Analysis
The dataset used country code for Partner countries and Reporting countries to identify the exchange of flux. 
XWD region was added to the code list which holds unallocated import and export for each country thus ensuring consistency within the data.
Although it is not present in the official list of countries provided by WITS, XWD was added with 000 as Country Code and "Unallocated I&E" as Country Name.

In addition to XWD, 5 countries had to be added to the WITS list as they were missing, these countries are:
- TLS	626	Timor-Leste
- COD	180	Congo, The Democratic Republic of 
- IMN	833	Isle of Man
- ROU	642	Romania
- MNE	198	Montenegro




### Data Exploration

### Data Cleaning

## Conclusion

## References
```
