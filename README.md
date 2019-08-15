# India-Trade-Data

A web scraper written in Python to gather trade data for India across commodities and countries

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
1. Make sure the requirements are satisfied (namely, `selenium`, `chromedriver` and `pandas`)
2. Download the `.ipynb` file
3. Change the URL to either *export* or *import*, as desired
4. Run the appropriate function (it will take time because of multiple iterations)

---
## Tools used
1. Python 3
2. Selenium
3. ChromeDriver
4. Pandas

## Source
The data is sourced from [Department of Commerce, Government of India.](https://commerce-app.gov.in/eidb/Default.asp)

## TO-DO

 - [ ] Create functions for import data
 - [ ] Try to speed up the scraping process

### Note
Because of the multitude of commodities and countries, the datasets are extremely large in terms of row number.
