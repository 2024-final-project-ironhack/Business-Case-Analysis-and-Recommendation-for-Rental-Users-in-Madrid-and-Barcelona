# Business Case: Analysis and Recommendation for Rental Users in Madrid and Barcelona

### Background and Purpose of the Investigation

Barcelona and Madrid are one of the major European tourist hubs, attracting millions of visitors annually. Barcelona alone recorded over 6 million visitors in the most recent year, marking a 5.7% increase from 2023, with an average of 229,531 visitors per day. This compares to 178,289 daily visitors the previous year, as per official data from the Barcelona City Council. Madrid, although receiving fewer tourists, still welcomed an impactful 4.4 million visitors so far this year, according to the Madrid City Council.

This influx of tourists has led to growing discontent among residents in both cities, particularly in central neighborhoods. Locals perceive the surge in tourism as a burden, contributing to rising housing costs, increased shop prices, and congested streets. Much of this frustration is directed at platforms like Airbnb, which are seen as exacerbating the problem.


**Purpose of the Analysis:**
The purpose of this investigation is to provide insights and recommendations for managing rental markets and tourism in Barcelona and Madrid. Specifically, it aims to propose strategies for decentralizing tourism in Barcelona, shifting the focus away from overcrowded hotspots, and to compare the rental dynamics between Barcelona and Madrid to inform better policy decisions, taking into account that tourists stay for an average of 4.6 nights in short-term accommodations.

## Steps

### 0. Data Preparation
The initial dataset extracted from airbnb oficial website contains numerous columns that are not necessary for our analysis. To streamline and focus the exploratory and comparative analysis between the datasets of Barcelona and Madrid, it is crucial to simplify the datasets by removing irrelevant columns. This process will help concentrate on variables that add real value to the analysis and improve its efficiency. Below are the names of the reduced datasets created for this purpose:

- `listing_prepared_bcn`
- `listing_prepared_mad`

### 1. Data Cleaning
Despite the first preparation dataset,a cleaning process in listing_prepared_bcn & listing_prepared_mad must be taken Before analyzing and modeing , it's essential to ensure our dataset is clean and ready. It is necessary to encoded categorical data and normalized features such latitude, longitude, price, amenities (e.g., bedrooms, AC, bathroom, balcony, etc.).

The diferents proces to cleaning data are descriptive below:

#### 1.1 Encoding Categorical Data
Convert categorical variables such as `...`, `...`, and `...` into numerical values using techniques like one-hot encoding or label encoding.

#### 1.2 Normalizing Data
Standardize features such as price and distance from the city center to have a mean of zero and a standard deviation of one. This is especially important for calculations involving distance and price.

#### 1.3 Calculating Distance
Calculate the distance of each listing from the city centers using the Haversine formula. This can be done in Python. If needed, a code snippet can be provided to perform this calculation.



### 2. Exploratory Data Analysis (EDA)
Once is the dataset cleaned is crucial explore the data to understand data structure, uncover patterns and trends, and prepare data for modeling. It helps identify relationships, detect anomalies, and guide decisions through visualizations and statistical insights. EDA supports informed, data-driven decision-making.

#### 2.1 EDA for Barcelona
Conduct exploratory data analysis specifically for the Barcelona dataset.

#### 2.2 EDA for Madrid
Conduct exploratory data analysis specifically for the Madrid dataset.

#### 2.3 Comparison between Barcelona and Madrid
Compare the findings from the EDA of Barcelona and Madrid to identify similarities, differences, and potential recommendations for rental users and policy suggestions.


