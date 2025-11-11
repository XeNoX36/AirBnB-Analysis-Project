# Project Report

**1. Data Overview & Initial Exploration**  

The dataset contains 20,770+ listings and 22 variables:  
This dataset is representative of the current short-term rental market in NYC.

**2. Data Cleaning & Preparation**  

**Missing Values**  
A systematic check for missing values was conducted. Missing entries were either:  

Dropped (when they contributed negligible volume), or

Imputed (when necessary to preserve dataset integrity).  

This step ensured a complete dataset without analytical distortions.  

**Duplicate Removal**  
Duplicate listings were identified and removed to avoid artificial inflation of listing counts or misleading pricing patterns.  

**Data Type Corrections**
Columns such as price, last review date, and host listing count were reconverted into:  

Numeric format  

Datetime format  

Categorical (object) format  

Ensuring data types were accurate allowed for correct aggregation and plotting    

**3. Exploratory Data Analysis (EDA)**  

**Univariate Analysis**  

Price Distribution:  

![]()  

Neighbourhood Price Distribution  

![]()  

Availability-365

![]()  

**Bivariate Analysis**  
Review & Availability Patterns

![]()  


**Multivariate Analysis**  

![]()  


**4. Key Insights & Findings**  
- Manhattan dominates the premium Airbnb market, both in volume and pricing.  
- Brooklyn provides strong mid-market opportunities with balanced supply and demand.  
- Room type is one of the strongest predictors of price.  
- Hosts with multiple listings tend to price more consistently and often operate like businesses.  
- Lower-priced listings attract more reviews, suggesting high occupancy.  
- Significant right-skew in price distribution indicates the presence of a large budget-traveler market and smaller luxury segment.


**5. Recommendations**  

For Hosts  
Invest in entire-home listings in Manhattan or Brooklyn for premium returns.  

Improve review rates through guest communication to boost listing visibility.  

Optimize pricing to remain competitive during peak demand periods.  

For AirBnB  
Consider policies for commercial hosts to maintain market fairness.  

Provide dynamic pricing insights to new hosts in low-review neighbourhoods.  

For Travelers
Best affordability in Queens and Bronx.

Brooklyn offers optimal value-for-money with good accessibility.
