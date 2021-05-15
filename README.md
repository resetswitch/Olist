# Olist

## About the Company
######
Olist is a Brazillian company that provides a consolidated e-commerce service to vendors. Since vendors are fracturing management on several platforms (Amazon, americanas, etc.) Olist attempts to tackles the problem by providing a single space to manage prodcuts, inventory, orders, deliveries, and messages. 

<hr>

## Olist Data Analyst Challenge

### Background:

This challenge ensure's the following:
- A working knowledge of data analysis tools and methodologies
- Experience analyzing large data sets
- Preparation and presentation of data

### Prompt:

We are using 2 data sets (linked below) from Brazillian retailer Olist.
Here are some facts:
 - It’s currently September 1st 2018 (Ignoring September 2018 and after)
 - The company’s inception was January 1st 2017 (Ignore all data before January 2017)
 - Company is based in Brazil (which is why some information is in Portuguese, inlcuding currency)
 - Summarizes the seller funnel from marketing sign up to launching products on the platform
 - Please provide Customer LTV 
 - Summarizes the current state of the business
 - What has performance been monthly
 - What are the best selling categories
 - Predicts future revenue 

### Data Sources:
##### Kaggle Dataset (These can be found in the `Olist-Dataset` folder)

- [Marketing Funnel Data Set](https://www.kaggle.com/olistbr/marketing-funnel-olist?select=olist_marketing_qualified_leads_dataset.csv)
- [E-Commerce Data Set](https://www.kaggle.com/olistbr/brazilian-ecommerce/home?select=product_category_name_translation.csv)


<hr>

## The Results

### Tableau

Tableau has been used to create most of these insights that can be found at:
- [Tableau Public - Olist](https://public.tableau.com/profile/chase.goesling#!/vizhome/OlistDataset/Home?publish=yes)
- [My Portfolio Website - Olist](http://www.chase-g.com/portfolio-Olist)


### Python

There were some shortcomings with Tableau when creating Key Performance Indices in which a Python Notebook solves, the reason behind this repository. The Python Notebook generates a pandas DataFrame which is converted to an `.xlsx` file, this can be found in `Insight-Dataset/KPI-Dataset.xlsx`. This file is then fed into Tableau to complete those insights.


