# Amsterdam_House_Pricing_EDA


The Amsterdam Housing Price dataset provides the sales price of individual residential property in Amsterdam, Netherlands for the month of August 2021

### Dataset:
Source: Kaggle
The Amsterdam Housing Price dataset provides the sales price of individual residential property in Amsterdam, Netherlands for the month of August 2021 

### Libraries Used:
Numpy,Pandas,Matplotlib.


### Description:
We performed some data analysis and visualization on our dataset after data cleaning and adding two new columns (Price_per_sqm and Zip_number). So, here are the key findings from our data analysis:

We Choose the Amsterdam Central Station (lat 52.378901,lon 4.9005805) as Amsterdam city center.

![alt text](https://miro.medium.com/max/875/1*XmC8a-Rxun-6R-qtJpBZIA.png)

We will use this to calculate the distance of every house in the dataset from Amsterdam city centre.

### Findings: 
1. Area closer to Amsterdam's city center is particularly expensive. The reasons can be amenities, neighborhood, accessibility, etc.

    * Most of the houses sold are within 5kms of the city center.

    * Maximum house sales are at 1017 zip code.

    * Maximum houses sold are those with 3 rooms. Houses with 2-4 rooms are in great demand.

2. The more the number of rooms in a house, higher the price should be? However, that is not what our analysis shows as there are 5-rooms houses going for as little as 265000 EUR and as high as 4495000 EUR. 

3. Bigger the house , higher the price? Yes, there is a clear upwards sloping trend relationship between the surface area of the house and the price of the house.

4. Interesting observation here is as the house gets bigger, the marginal price of an additional square meter decreases.

5. The price range of around 200K-500K EUR is in the highest demand in the Amsterdam housing market.


