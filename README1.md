# Real Estate Data Analysis Project
# To to the analysis I downloaded the real estate file from Kaggle.com 

# Tools -> SQL, Python and Excel

# Business Questions ->
1) Which properties have the highest occupancy rate?
2) What is the avegarge rent by city?
3) Whick property have highest maintenance cost?

# Excel Analysis 
- Created pivot table by city to get the average rent by City.
- Chart Occupanct Rate vs Rent

# SQL Analysis
1) Which properties have the highest occupancy rate?   
SELECT Property_ID FROM Real_Estate_Data
ORDER BY Occupancy_Rate DESC;

2) What is the average rent by city?
SELECT City, AVG(Monthly_Rent_USD) as Average_Rent
From Real_Estate_Data
Group By City;

  
