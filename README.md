# Artificial Neural Networks Applications & ANN_Projects

### HW0: The dataset that I have used in this assignment is from UCI database: 
‘Concrete Compressive Strength Data Set’.
Concrete is the most important material in civil engineering. The concrete compressive strength is a highly nonlinear function of age and ingredients. Below is a brief description of the dataset.

Number of instances: 1030 
Number of Attributes: 9 
Attribute breakdown: 8 quantitative input variables, and 1 quantitative output variable 

Given are the variable name, variable type, the measurement unit and a brief description. The concrete compressive strength is the regression problem. 

Name -- Data Type -- Measurement -- Description 
Cement (component 1) -- quantitative -- kg in a m3 mixture -- Input Variable 
Blast Furnace Slag (component 2) -- quantitative -- kg in a m3 mixture -- Input Variable 
Fly Ash (component 3) -- quantitative -- kg in a m3 mixture -- Input Variable 
Water (component 4) -- quantitative -- kg in a m3 mixture -- Input Variable 
Superplasticizer (component 5) -- quantitative -- kg in a m3 mixture -- Input Variable 
Coarse Aggregate (component 6) -- quantitative -- kg in a m3 mixture -- Input Variable 
Fine Aggregate (component 7) -- quantitative -- kg in a m3 mixture -- Input Variable 
Age -- quantitative -- Day (1~365) -- Input Variable 
Concrete compressive strength -- quantitative -- MPa -- Output Variable 

### HW1: The dataset that I have used in this assignment is from Kaggle: 
‘KC_Housesales_Data’.
The aim of this dataset is to predict house prices for homes in Washington, USA.
Number of instances: 21597 
Number of Attributes: 21 


Given below are the attribute names present in the dataset:

id – independent variable
date -- independent variable
price -- dependent variable 
bedrooms  -- independent variable
bathrooms -- independent variable
sqft_living -- independent variable
sqft_lot -- independent variable
floors -- independent variable
waterfront -- independent variable
view -- independent variable
condition -- independent variable
grade -- independent variable
sqft_above -- independent variable
sqft_basement -- independent variable
yr_built -- independent variable
yr_renovated -- independent variable
zipcode -- independent variable
lat -- independent variable
long -- independent variable
sqft_living15 -- independent variable
sqft_lot15 -- independent variable


### HW2: In this assignment we will be: Selecting a data set for a forecasting or prediction problem. Compare the performance of (a) plain backpropagation (using a few recent data points to make predictions); (b) backpropagation through time; (c) LSTM; and (d) GRU networks.
Here, we will be using the dataset: Australian Beer Production - we will be forecasting the beer production using the quarterly data
Information about the dataset (AusBeer.csv): ¶
• Time: Contains a number for all the years starting from 1
• Year: Represents the year of production
• Quarter: Represents the quarter for any given year
• Beer.Production: The amount of beer produced in Australia in a given quarter for a given year


### HW3: In this assignment, we have experimented with a convolutional neural network implementation on a non-trivial image classification problem. Here, we have implemented a CNN network on a dataset that is available on Kaggle. The dataset represents a Kaggle challenge - 'Dogs vs Cats'. The dataset includes two zip files - train & test. The train archive consists of 25,000 images of dogs and cats. Test archive contains 12,500 images of dogs and cats. We have implemented several CNN models with different parameters and layers. Our models will be solving this binary classification problem - Given an input test image, the CNN model will be predicting if that image belongs to a binary class - either dogs/cats.
Dataset
This dataset can be found on Kaggle - 'Dogs vs Cats'. The dataset includes two zip files - train.zip & test1.zip
The train archive consists of 25,000 images of dogs and cats. Test archive contains 12,500 images of dogs and cats.
