# Bangalore-House-Price-Prediction
### Introduction 
Bangalore is a one of best cities to live in India because of its great climate, culture, beautiful greenery and abundant job opportunities. Anyone would want to live in this city! but can we afford a house in bangalore? It depends on a lot of factors like the location, the size of the property, vicinity to offices, schools, parks, restaurants, hospitals or the stereotypical white picket fence etc., 

### Purpose
Our purpose is to create a model that can give an estimate of the house price in bangalore using factors like location, number of rooms, number of bathrooms, area of the house. 

### Language & Methods
Python - Pandas, Numpy, Scikit Learn, Seaborn, Matplotlib

### Data description
Source Data: https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data
- area_type: type of area house located in (ex. Plot Area, Built-up Area)
- availability: When is house available to move-in
- location: House location
- size: BHK of the house (ex. 2,3)
- society: Type of society house located in
- total_sqft: Total Square foot of the house
- bath: Number of bathrooms in the house
- balcony: Number of balconies in the house
- price: Price of the house (in Lakhs INR)

### Machine Learning Techniques
- Data Visualization
- Data Pre Processing
- Feature Engineering
- Creating Linear Regression Model
- Improving model using log transformation & removing outliers
- Scatter Plot between predicted and actual values 
- Distribution plot on residuals for 
- Creating a valuation tool using pickle

### Model Evaluation & Conclusion

- R-square Value: 0.84 ; Mean Absolute Error: 17 Lakhs ; Mean Square Error = 786
- Upon appling these 3 improvements methods, even though there is a reduction in mean-squared-error, there was a drastric fall in R-squared value.
- Even though there a very strong correlation (0.91) between the predicted and actual price values, there are few outliers which is causing a skew (0.16) in the residual values
- Hence, we can conclude that there might have been few features like the 'view point', 'next to river', 'accessibility to IT insdustry', 'Age & Aesthitics of the building' which are missed in the original training data set.
