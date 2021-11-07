
# Car Price Regression Modeling
## Abstract
The goal of this project is to create a model form carvago.com to predict car sales price.

## Data
Car data were scraped from carvago.com by using beautifiulsoup and requests libraries. we were able to scrape 5959 rows and 10 columns.Features include car name,price,km_driven,first_registration,power,Automatic,Dieasal,Electruc, Hybrid and Petrol.

## Design
After scraping the data we placed it in DataFrame and cleaned it by removing null,duplicate and wrong entries. Then we had to strip and convert data types from str to int. Moreover, we checked the correlation of the data to get a better understanding of our dataset.Last step before modeling is to pickle our data.

For linear models we tried simple linear ridge and second degree polynomial and found the last to be the best model.

## Tools
- Python 
- Pandas 
- NumPy 
- BeautifulSoup 
- Matplot 
- Seaborn 
- Sklearn 
- Patsy 
- request 
- Statsmodels 
- Pickle

## Communication
The project is embedded on my github account.
