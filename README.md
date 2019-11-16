#  # Project 2: part 1 "House prices" 
## Problem Statment:
House prices are often influenced by several qualities or elements.
In this project we will try to find the most important elements that affect the rise or fall of house prices significantly.

## Executive Summary:
We started this competition by focusing on getting a well understanding of the dataset.
The EDA is detailed and many visualizations are included. Then we provide four kind of modeling in order to reach to best predections.
Redge regressions performs best with a cross validation score of 0.14. 

## Datasets Description:
- [House prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)


This is a brief version of what you'll find in the data description file.

There are 1460 instances of training data and 1460 of test data. Total number of attributes equals 81,
of which 36 is quantitative, 43 categorical + Id and SalePrice.


|Feature | Dataset | Description |
|---|---|---|
|SalePrice |train|the property's sale price in dollars. This is the target variable that you're trying to predict.|
|MSSubClass|train/test| The building class|
|MSZoning|train/test|The general zoning classification|
|LotFrontage|train/test| Linear feet of street connected to property|
|LotArea|train/test|Lot size in square feet|
|Street|train/test| Type of road access|
|Alley|train/test| Type of alley access|
|LotShape|train/test| General shape of property|
|LandContour|train/test| Flatness of the property|
|Utilities|train/test| Type of utilities available|
|LotConfig|train/test|Lot configuration|
|LandSlope|train/test| Slope of property|
|Neighborhood|train/test| Physical locations within Ames city limits|
|Condition1|train/test| Proximity to main road or railroad|
|Condition2|train/test| Proximity to main road or railroad (if a second is present)|
|BldgType|train/test|Type of dwelling|
|HouseStyle|train/test| Style of dwelling|
|OverallQual|train/test| Overall material and finish quality|
|OverallCond|train/test|Overall condition rating|
|YearBuilt|train/test|Original construction date|
|YearRemodAdd|train/test|Remodel date|
|RoofStyle|train/test| Type of roof|
|RoofMatl|train/test| Roof material|
|Exterior1st|train/test| Exterior covering on house|
|Exterior2nd|train/test| Exterior covering on house (if more than one material)|
|MasVnrType|train/test| Masonry veneer type|
|MasVnrArea|train/test| Masonry veneer area in square feet|
|ExterQual|train/test| Exterior material quality|
|ExterCond|train/test| Present condition of the material on the exterior|
|Foundation|train/test|Type of foundation|
|BsmtQual|train/test| Height of the basement|
|BsmtCond|train/test|General condition of the basement|
|BsmtExposure|train/test|Walkout or garden level basement walls|
|BsmtFinType1|train/test| Quality of basement finished area|
|BsmtFinSF1|train/test| Type 1 finished square feet|
|BsmtFinType2|train/test| Quality of second finished area (if present)|
|BsmtFinSF2|train/test| Type 2 finished square feet|
|BsmtUnfSF|train/test|Unfinished square feet of basement area|
|TotalBsmtSF|train/test| Total square feet of basement area|
|Heating|train/test| Type of heating|
|HeatingQC|train/test| Heating quality and condition|
|CentralAir|train/test| Central air conditioning|
|Electrical|train/test| Electrical system|
|1stFlrSF|train/test| First Floor square feet|
|2ndFlrSF|train/test| Second floor square feet|
|LowQualFinSF|train/test| Low quality finished square feet (all floors)|
|GrLivArea|train/test| Above grade (ground) living area square feet|
|BsmtFullBath|train/test| Basement full bathrooms|
|BsmtHalfBath|train/test| Basement half bathrooms|
|FullBath|train/test| Full bathrooms above grade|
|HalfBath|train/test| Half baths above grade|
|Bedroom|train/test| Number of bedrooms above basement level|
|Kitchen|train/test| Number of kitchens|
|KitchenQual|train/test| Kitchen quality|
|TotRmsAbvGrd|train/test| Total rooms above grade (does not include bathrooms)|
|Functional|train/test| Home functionality rating|
|Fireplaces|train/test| Number of fireplaces|
|FireplaceQu|train/test| Fireplace quality|
|GarageType|train/test| Garage location|
|GarageYrBlt|train/test| Year garage was built|
|GarageFinish|train/test| Interior finish of the garage|
|GarageCars|train/test| Size of garage in car capacity|
|GarageArea|train/test| Size of garage in square feet|
|GarageQual|train/test| Garage quality|
|GarageCond|train/test| Garage condition|
|PavedDrive|train/test| Paved driveway|
|WoodDeckSF|train/test| Wood deck area in square feet|
|OpenPorchSF|train/test| Open porch area in square feet|
|EnclosedPorch|train/test| Enclosed porch area in square feet|
|3SsnPorch|train/test| Three season porch area in square feet|
|ScreenPorch|train/test| Screen porch area in square feet|
|PoolArea|train/test|Pool area in square feet|
|PoolQC|train/test|Pool quality|
|Fence|train/test| Fence quality|
|MiscFeature|train/test| Miscellaneous feature not covered in other categories|
|MiscVal|train/test| $Value of miscellaneous feature|
|MoSold|train/test| Month Sold|
|YrSold|train/test| Year Sold|
|SaleType|train/test| Type of sale|
|SaleCondition|train/test| Condition of sale|



# Kaggle :

<p>We provide four kind of modeling in order to reach to best predections.</p>
<p>Redge regressions performs best with a cross validation score of 0.14.</p> 

# Conclusion :
when we try to find the most affect  to the housing price we find that there is many feature are affect  to the price and the most three affect is Lot Frontage,
Lot Area and OverallQual .


we used four modeling to find the best predections so Redge regressions performs best with a cross validation score of 0.14 in kaggle .
