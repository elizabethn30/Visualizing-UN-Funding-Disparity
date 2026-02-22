# Visualizing U.N. Funding Disparity
This visualization maps out the extreme differences between the amount of humanitarian aid a country requires and the actual funding it receives. 
# include screenshot AND link to project

# How it's made 
**Technology used:** Python, Databricks

We chose to do this challenge using databricks and UN data because we were interested in creating something that could be used for social good. We first started by parsing the datasets from the Humanitarian Data Exchange and seeing how they could go together to create a mapping usable by UN representatives. The datasets consist of funding data that are pooled from countries around the world in order to provide humanitarian aid for other countries. They are specifically only from 2025 to show as current results we could. To calculate the beneficiaries-to-budget ratio, we divided the allocations of funding by the number of people in need for each of the countries that are listed in the International Rescue Committee's Watchlist. Due to missing data for some of the countries, we decided to leave off certain countries because we could not account for an accurate result. The overall result culminated in this interactive map visualization showcasing the extreme disparities in the beneficiaries-to-budget ratio. It shows where the funding should be properly allocated to improve the humanitarian aid that is given to countries. 

# What we learned
Through the cleaning and researching of the data, we learned how important this task is. Without cleaning our datasets, we would not have been able to properly merge tables together or get the correct data. While working with the data, we made sure to cross-reference with online resources, such as the Humanitarian Data Exchange website, to fully ensure our information was correct. For example, we checked to make sure that there were supposed to be no other countries on our list and found out that we were actually working with data from the ICR's Watchlist. 
