# India-Trade-Data

A web scraper written in Python to gather trade data for India across commodities and countries

Access the dataset on [Kaggle](https://www.kaggle.com/lakshyaag/india-trade-data)

## Dataset

The data is in tidy format, meaning there is one observation per category.

|Column|Definition|
|--|--|
|HSCode|Harmonized System (HS2) Code|
|Commodity|Name of commodity as per HS2|
|Country|Country of export|
|Year|Year of export|
|Value|Value of export (in million US$)

## How to use

1. Make sure the requirements are satisfied (`pip install -r requirements.txt`)
2. Download the `.ipynb` file
3. Run the *export* or *import* cells, as desired
4. The required file will be saved to disk.

## Source

The data is sourced from [Ministry of Commerce and Industry, Government of India.](https://tradestat.commerce.gov.in/eidb/default.asp)
