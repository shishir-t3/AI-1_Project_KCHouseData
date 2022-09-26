# What Makes An House Affordable ?

### Applying Regression and Classification to predict House prices and their affordability in King County, Washington

![image](https://user-images.githubusercontent.com/99063438/192214061-d4d28c7f-80f8-43e1-b429-15b31d8bfff4.png)

The data in the King County House prices was collected from the Houses sold in the time period of May 2014 to May 2015, and it comprises of 23 different features. The different columns in the dataset are as follows:


Id - Unique ID for each house sold

Date - Date of the house sale

Price - Price of each house sold

Bedrooms - Number of bedrooms in the House

Bathrooms - Number of bathrooms, where .5 accounts for a room with a toilet but no shower.

sqft_living - Square foot area of the apartment's interior living space.

sqft_lot - Square foot area of the land space.

floors - Number of floors

waterfront - A categorical variable for whether the apartment was overlooking the waterfront or not.

view - An index from 0 to 4 of how good the view of the property was.

condition - An index from 1 to 5 on the condition of the House.

grade - An index from 1 to 13, where 1-3 falls short of building construction and design, 7 has an average level of construction and design, and 11-13 have a high quality level of construction and design.

sqft_above - The square footage of the interior housing space that is above ground level.

sqft_basement - The square footage of the interior housing space that is below ground level.

yr_built - The year the house was initially built

yr_renovated - The year of the house’s last renovation

zipcode - What zipcode area the house is located in

lat - Lattitude

long - Longitude

sqft_living15 - The square foot area of interior housing living space for the nearest 15 neighbors

sqft_lot15 - The square foot area of the land lots of the nearest 15 neighbors

## Exploratory Data Analysis

### Bar plot for Correlation with response variable

![image](https://user-images.githubusercontent.com/99063438/192214857-a20ba4ac-f6d7-4628-ab08-bde997b4b003.png)

### Price dependence on area of living and its age

![image](https://user-images.githubusercontent.com/99063438/192214771-32d823df-a2a5-4159-9e5c-ee737fcce991.png)

### How modern construction grade affect prices

![image](https://user-images.githubusercontent.com/99063438/192214974-6b2e07c4-cbea-4133-bef9-2fdd68588031.png)


## Regression Modelling

### Best regression model came out to be GradBoost with test MSE of 0.1170

![image](https://user-images.githubusercontent.com/99063438/192215896-d4626997-ca37-48f4-8582-52c20aac61f0.png)


## Affordability Classification Models

### Boosting Algorithms again perform the best on Imbalanced class set.Their ROC curves:

![image](https://user-images.githubusercontent.com/99063438/192216514-4a726772-55d8-4e65-a6fb-957e21a2c826.png)

### While KNN classifier exhibited better Recall for SMOTE upsampled set.

![image](https://user-images.githubusercontent.com/99063438/192216832-f9eb3794-24ba-4a1b-8815-b0ac1bca4bc8.png)






