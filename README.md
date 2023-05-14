# House Price Prediction - Decision Tree Regressor
![](https://user-images.githubusercontent.com/26305084/117038955-35c4c980-acd6-11eb-9a5e-4e98d4d4b764.gif)
## Overview

House Price prediction are very stressful work as we have to consider different things while buying a house like the structure and the rooms kitchen parking space and gardens. People don’t know about the factor which influence the house price. But by using the Machine learning we can easily find the house which is to be prefect for us and helps to predict the price accurately.

## About the dataset

-   **SalePrice**  - the property's sale price in dollars. This is the target variable that you're trying to predict.
-   **MSSubClass**: The building class
-   **MSZoning**: The general zoning classification
-   **LotFrontage**: Linear feet of street connected to property
-   **LotArea**: Lot size in square feet
-   **Street**: Type of road access
-   **Alley**: Type of alley access
-   **LotShape**: General shape of property
-   **LandContour**: Flatness of the property
-   **Utilities**: Type of utilities available
-   **LotConfig**: Lot configuration
-   **LandSlope**: Slope of property
-   **Neighborhood**: Physical locations within Ames city limits
-   **Condition1**: Proximity to main road or railroad
-   **Condition2**: Proximity to main road or railroad (if a second is present)
-   **BldgType**: Type of dwelling
-   **HouseStyle**: Style of dwelling
-   **OverallQual**: Overall material and finish quality
-   **OverallCond**: Overall condition rating
-   **YearBuilt**: Original construction date
-   **YearRemodAdd**: Remodel date
-   **RoofStyle**: Type of roof
-   **RoofMatl**: Roof material
-   **Exterior1st**: Exterior covering on house
-   **Exterior2nd**: Exterior covering on house (if more than one material)
-   **MasVnrType**: Masonry veneer type
-   **MasVnrArea**: Masonry veneer area in square feet
-   **ExterQual**: Exterior material quality
-   **ExterCond**: Present condition of the material on the exterior
-   **Foundation**: Type of foundation
-   **BsmtQual**: Height of the basement
-   **BsmtCond**: General condition of the basement
-   **BsmtExposure**: Walkout or garden level basement walls
-   **BsmtFinType1**: Quality of basement finished area
-   **BsmtFinSF1**: Type 1 finished square feet
-   **BsmtFinType2**: Quality of second finished area (if present)
-   **BsmtFinSF2**: Type 2 finished square feet
-   **BsmtUnfSF**: Unfinished square feet of basement area
-   **TotalBsmtSF**: Total square feet of basement area
-   **Heating**: Type of heating
-   **HeatingQC**: Heating quality and condition
-   **CentralAir**: Central air conditioning
-   **Electrical**: Electrical system
-   **1stFlrSF**: First Floor square feet
-   **2ndFlrSF**: Second floor square feet
-   **LowQualFinSF**: Low quality finished square feet (all floors)
-   **GrLivArea**: Above grade (ground) living area square feet
-   **BsmtFullBath**: Basement full bathrooms
-   **BsmtHalfBath**: Basement half bathrooms
-   **FullBath**: Full bathrooms above grade
-   **HalfBath**: Half baths above grade
-   **Bedroom**: Number of bedrooms above basement level
-   **Kitchen**: Number of kitchens
-   **KitchenQual**: Kitchen quality
-   **TotRmsAbvGrd**: Total rooms above grade (does not include bathrooms)
-   **Functional**: Home functionality rating
-   **Fireplaces**: Number of fireplaces
-   **FireplaceQu**: Fireplace quality
-   **GarageType**: Garage location
-   **GarageYrBlt**: Year garage was built
-   **GarageFinish**: Interior finish of the garage
-   **GarageCars**: Size of garage in car capacity
-   **GarageArea**: Size of garage in square feet
-   **GarageQual**: Garage quality
-   **GarageCond**: Garage condition
-   **PavedDrive**: Paved driveway
-   **WoodDeckSF**: Wood deck area in square feet
-   **OpenPorchSF**: Open porch area in square feet
-   **EnclosedPorch**: Enclosed porch area in square feet
-   **3SsnPorch**: Three season porch area in square feet
-   **ScreenPorch**: Screen porch area in square feet
-   **PoolArea**: Pool area in square feet
-   **PoolQC**: Pool quality
-   **Fence**: Fence quality
-   **MiscFeature**: Miscellaneous feature not covered in other categories
-   **MiscVal**: $Value of miscellaneous feature
-   **MoSold**: Month Sold
-   **YrSold**: Year Sold
-   **SaleType**: Type of sale
-   **SaleCondition**: Condition of sale

## Introduction
In this project, I will pursuit a Data Science process to build and deploy a Machine Learning Model that can predict a house price, by following the steps below:

1.  Loading Data
2.  Data preprocessing and cleaning
3.  Data exploration and visualisation
4.  Data modeling
5.  Evaluating the model

## Exploratory Data Analysis

I have done Exploratory Data Analysis on this dataset which helped me gain various insights. Some of them are listed below:

- If the house has significant slope on both sides (HLS) or is nearly flat(Low), Sale Price is more.For Depressed and Banked slopes , Sale price falls down.
- For flat stones or bricks access , Price is higher and majority of houses with gravel have price around 2 lakhs.But as there is very less data for Gravel street type .
- Most of the properties are having gentle slope and are lowest priced , while properties having moderate or severe slope have higher value.
- Properties in average and excellent condition are having average price high and the properties in very bad condition will have low sale price.
- Single family detached dwellings have higher sale price compared to duplex,two family houses and townhouse dwellings.
- The houses and garage which were built and remoddeled during 90s have less Sale Price than the newer ones.

And many many more!!

## Decision Tree Modelling

For the modelling part, the following steps were followed:

1. Looking at the statistics
2. Encoding categorical columns into numerical columns
3. Splitting the dataset into training and testing
4. Predicting the training and testing values
5. Plotting the decison tree
6. Checking the training accuracy for decision tree 
7. Checking the testing accuracy for decision tree
  > **Training accuracy:  84.26%**
  > **Testing Accuracy:  68.15%**
 8. Calculating the RSME
  > **Training RSME:  66.93**
  > **Testing RSME:  95.91**


## Regression

- Fitting the model into x and y
- Predicting training and testing values
- Plotting the predictions

### Calculating scores for Multiple Linear Regression

- R square of training: 93.46%
- R square of testing: 83.32%

## Creating a python function

At last, I created a python function where i can input my values and get a prediction of whatever I are trying to predict.


