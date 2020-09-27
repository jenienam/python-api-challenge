# python-api-challenge

The purpose of this challenge was to answer the question, "What is the weather like as we approach the equator?" 
To answer this question, I utilized python APIs to display the relationships between the different components:
• Temperature (F) vs. Latitude
• Humidity (%) vs. Latitude
• Cloudiness (%) vs. Latitude
• Wind Speed (mph) vs. Latitude

Then, I ran a linear regression to show the relationships between:
• Northern Hemisphere - Temperature (F) vs. Latitude
• Southern Hemisphere - Temperature (F) vs. Latitude
• Northern Hemisphere - Humidity (%) vs. Latitude
• Southern Hemisphere - Humidity (%) vs. Latitude
• Northern Hemisphere - Cloudiness (%) vs. Latitude
• Southern Hemisphere - Cloudiness (%) vs. Latitude
• Northern Hemisphere - Wind Speed (mph) vs. Latitude
• Southern Hemisphere - Wind Speed (mph) vs. Latitude

After ETL of the raw data, building scatter plots, and performing linear regression, I was able to randomly select 500 unique cities based on lattitude and longitude and perform weather checks on them through API calls which is shown in the csv attached. 

Then, a heat map was created for every city through with the conditions:
• A max temperature lower than 80 degrees but higher than 70.
• Wind speed less than 10 mph.
• Zero cloudiness.
• Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.
 
