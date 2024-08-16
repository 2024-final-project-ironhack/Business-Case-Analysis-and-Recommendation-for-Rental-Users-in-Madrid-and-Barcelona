## 1. Data Preparation

First, ensure our dataset is clean and ready for analysing and modeling. Ouyr origianal datasets includes several features like latitude, longitude, price, amenities like bedrooms, AC, bathroom, balcony etc, during the data cleaning process, we were encoding categorical data and normalizing the features.

### 1.1 Encoding Categorical Data
Convert categorical variables such as '..' '.. ' .. into numerical values using techniques like one-hot encoding or label encoding.


### 1.2 Normalizing Data
Standardize features like price and distance from the city center to have a mean of zero and a standard deviation of one. This is especially important for distance calculations and price.

### 1.3 Calculating Distance
Calculate the distance of each listing from the city centers using the haversine formula. This can be done in Python. If you need, I can provide you with a code snippet to perform this calculation.
