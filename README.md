# Airbnb_data

## Related blog
You can find the related blog on Medium with the link:
https://medium.com/@tylerzhang77/interesting-facts-about-airbnb-5722b2ad74c1

## Libraries used
Libraies in this project includes numpy, pandas, matplotlibs, seaborn and datetime.

## Motivation for the project
This is a project for the Udacity Data Scienties Nanodegree. The data is from Kaggle Boston Airbnb Open Data (link: https://www.kaggle.com/datasets/airbnb/boston). I intend to figure out three questions with the data available:

(1) Possible determinants of housing price;

(2) Housing availability and price trend over months;

(3) Relationship between customer ratings and housing price.

## Files in the repository
Boston_Airbnb.ipynb is the jupyter notebook that contains the code. listings.csv is the original dataset.

## Summary of the results
#### Possible determinants of housing price:

I examined the relationship between housing price and multiple categorical variables.

From the plots, we can see that housing prices vary with room type, property type, number of bedrooms and bathrooms,
neighbourhood, etc.

#### Housing availability and price trend over months:

The availability of housing has a slight decrease from January to August. During September, the availability has a sharp decrease. Then it increases
back to high level afterwards. The price trend is inversely proportional to the availability trend: price tend to go higher with low availability, and vise versa.

#### Relationship between customer ratings and housing price.  

The ratings are on a scale of 0-100. With lower price housing, there tend to be more negative reviews. As price increases, negative reviews decrease. 

## Acknowledgement

#### Data source: https://www.kaggle.com/datasets/airbnb/boston
