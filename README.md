# Project-Repository-Decision-Log


Date: July 16, 2026
Dataset: Airbnb Listings — Kaggle

Project Overview:

Our team selected an Airbnb dataset from Kaggle containing more than 50,000 Airbnb properties and over 30 variables describing each listing.

We chose this dataset because it contains a large amount of real-world data and allows us to examine how different property characteristics influence Airbnb pricing.

Main Variable of Interest:

Our main variable of interest is total_price.

We selected total price because we want to understand how different characteristics of an Airbnb property contribute to its overall value. Variables such as location, property type, number of bedrooms, amenities, and guest satisfaction may help explain why some properties have higher prices than others.

Research Objective

The primary goal of this analysis is to determine:

Which property characteristics are most strongly associated with Airbnb prices?
Why are some Airbnb properties more valuable than others?
Which features contribute the most to total_price?
What characteristics are common among higher-priced properties?
Which types of properties consistently fall below the market average?
Business Application

The results could help Airbnb property owners and investors identify which property characteristics may be worth investing in to potentially increase revenue.

Conversely, identifying properties that consistently perform below the market average could help owners understand which characteristics may be limiting their property's pricing potential.

One of the most notable findings during the initial data exploration was the extreme skewness and kurtosis of total_price.

The variable had a skewness of 25.7 and kurtosis of 1,527, indicating a highly right skewed distribution with extreme high end observations.

Because extreme outliers can significantly influence statistical analysis, particularly linear regression, we examined these observations before proceeding with further modeling.

Rather than automatically removing observations solely because they were extreme, we considered whether they represented legitimate Airbnb properties or potential data quality issues.

Initial Questions

Our analysis will focus on answering the following questions:

What is the typical Airbnb total price?
How is total_price distributed?
Which variables have the strongest relationship with total price?
How do property characteristics differ between lower- and higher-priced listings?
Which variables are most useful for predicting Airbnb prices?
What insights can Airbnb owners use to potentially improve revenue?


Team Members:

[Alex Thompson]
[Helen Sun]
[Kennedy Kirk]

Conclusion

This project uses a large Airbnb dataset to investigate the factors associated with property pricing. By combining descriptive statistics, visualization, and statistical modeling, we aim to identify meaningful relationships between Airbnb property characteristics and total_price.

The ultimate goal is to translate statistical findings into actionable business insights for Airbnb owners and investors.