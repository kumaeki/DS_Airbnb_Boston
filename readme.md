# Exploring the Boston Airbnb data

I will try to feagure out how the features(month in a year, host area or property type, etc) affect the price , and try to predict the price via          LinearRegression(sklearn)

you could find the dataset in the url <https://www.kaggle.com/datasets/airbnb/boston>

There are three data files in the Boston dataset, but this time I just use two files as follow:

- Listings, including full descriptions and average review score
- Calendar, including listing id and the price and availability for that day

## conclusion

- there is relationship between Neighbourhood and price, the Mattapan is the most cheap area, and the South Boston Waterfront has the most expensive average price.

- The more expensive property, the stricter Cancellation Pocily.

- The more bedrooms/bathrooms,  the higher price

- etc. （you could find the notebook for more details）


## reference url

- <https://www.kaggle.com/code/yangyax/seattle-airbnb-eda>
- <https://www.kaggle.com/code/ryanfox212/what-price-should-you-charge-for-your-airbnb>
- <https://www.kaggle.com/code/lingliboston/boston-airbnb-market-analysis>
