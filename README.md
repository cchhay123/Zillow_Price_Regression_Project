# Zillow_Price_Regression_Project

This repository is dedicated to the final project for my Urban Analysis class. The goal of this project is to use historical data from Zillow and the U.S. Census Bureau as predictors for future rent prices in certain states across America.

### EDA
The first part of the project involves data collection and preparation. Since we are sourcing data from different places, we need to clean and combine all the information into one structured dataset. After that, we used the Simple Features package in R to gather a map of the U.S. at the county level. This allows us to merge the geographical data with the main dataset so we can visualize where the concentration of rent listings is located.

![Screenshot 2025-04-10 at 4 28 34 PM](https://github.com/user-attachments/assets/95dae078-2d34-474d-89f0-373e17268b83)

From the picture above, we determined that the top three states with the highest number of rent listings are Florida, Texas, and California. 

![Screenshot 2025-04-10 at 4 45 50 PM](https://github.com/user-attachments/assets/ae24ec71-64ac-4c31-adac-de4646c89967)
![Screenshot 2025-04-10 at 4 46 05 PM](https://github.com/user-attachments/assets/9193309f-eda8-497c-bbd7-7111cdcd297a)
![Screenshot 2025-04-10 at 4 46 18 PM](https://github.com/user-attachments/assets/3a9c24bb-5b9f-4c7c-beaa-f7a96aeff69c)

### Regression 

After graphing the states, we separate the data points to those specific states. We want to see what factors contribute to the predictive power of the linear model. We use the combination of regression and backward selection models to determine which variables are the most important to the models. 
