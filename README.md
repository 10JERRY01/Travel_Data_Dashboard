# Travel_Data_Dashboard

## Project Overview
The Travel Data Visualization Dashboard is an interactive tool designed to analyze and present insights from customer travel data. This project aims to identify customer behavior patterns, preferences, and factors influencing travel product uptake. The dashboard highlights key metrics such as demographics, sales pitch effectiveness, and travel preferences, enabling businesses to make data-driven decisions.

## Objectives
Understand customer demographics and their impact on travel behavior.
Visualize key metrics such as product uptake, sales pitch satisfaction, and travel patterns.
Enable actionable insights through interactive filters and visualizations.
Explore the relationships between multiple variables using statistical analysis.

## Dataset Description
The dataset includes the following columns:

CustomerID: Unique identifier for each customer.
ProdTaken: Indicates if a travel product was taken (1 for yes, 0 for no).
Age: Age of the customer.
TypeofContact: Mode of contact (online/offline).
CityTier: Tier of the city where the customer resides.
DurationOfPitch: Duration of the sales pitch (in minutes).
Occupation: Customer's occupation.
Gender: Customer's gender.
NumberOfPersonVisiting: Number of individuals traveling with the customer.
NumberOfFollowups: Number of follow-up calls made to the customer.
ProductPitched: Type of product pitched to the customer.
PreferredPropertyStar: Preferred property star rating.
MaritalStatus: Marital status of the customer.
NumberOfTrips: Number of trips taken by the customer.
Passport: Indicates if the customer has a passport (1 for yes, 0 for no).
PitchSatisfactionScore: Customer’s satisfaction score for the sales pitch.
OwnCar: Indicates if the customer owns a car (1 for yes, 0 for no).
NumberOfChildrenVisiting: Number of children traveling with the customer.
Designation: Job designation of the customer.
MonthlyIncome: Monthly income of the customer.
Exploratory Data Analysis (EDA)
## Univariate Analysis:

Objective: Explore the distribution of individual features.
Techniques: Histograms, box plots, and frequency tables.
Findings:
Most customers are aged between 30-45.
Higher preference for 3-star properties.
A majority have 1-2 follow-ups.
## Bivariate Analysis:

Objective: Study relationships between two variables.
Techniques: Scatter plots, bar charts, and correlation matrices.
Findings:
Positive correlation between pitch duration and satisfaction score.
Customers with passports have higher product uptake.
## Multivariate Analysis:

Objective: Investigate the interaction of multiple variables.
Techniques: Pair plots, heatmaps, and regression models.
Findings:
Married customers with children prefer family-friendly packages.
Higher income correlates with frequent travel and higher star ratings.
## Dashboard Design
Tools:
Programming: Python (Dash, Plotly, Pandas, Matplotlib).
Data Visualization: Plotly and Tableau.
## Features:
1. Demographic Insights:
Age and income distributions.
Travel preferences based on marital status and occupation.
2. Travel Patterns:
Preferred star ratings and destinations.
Number of trips and accompanying individuals.
3. Sales Analysis:
Correlation between pitch duration and satisfaction.
Product uptake trends.
4. Interactive Filters:
Gender, CityTier, and ProductPitched.
## Project Workflow
1. Data Preprocessing:
Handle missing values using median/mode imputation.
Convert categorical columns to appropriate types.
2. EDA:
Conducted univariate, bivariate, and multivariate analysis.
Generated insights into customer behavior.
3. Dashboard Creation:
Built interactive plots using Plotly Dash.
Integrated dropdowns and filters for dynamic visualizations.
4. Insights Reporting:
Documented findings and actionable recommendations.
## Results
1.Demographic Trends:
Majority of customers are middle-aged professionals.
Higher income groups prefer luxury packages.
2. Behavioral Insights:
Customers with higher pitch satisfaction are more likely to purchase.
Families with children tend to book 3-star properties.
3. Strategic Recommendations:
Focus marketing on middle-income groups in Tier 2 cities.
Tailor pitches to align with preferred property ratings.
## Conclusion
The Travel Data Visualization Dashboard provides a comprehensive view of customer behavior, helping businesses optimize marketing strategies and improve customer engagement. This project demonstrates the application of data analysis and visualization techniques to solve real-world problems.
