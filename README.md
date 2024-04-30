# AIRBNB-LISTING-ANALYSIS-IN-PYTHON

 ## Objective 1 :  Data Prep & QA

- Read in the AirBnB Listings Data.
- Cast any date coulmns as a datetime format.
- Filter down the data to just listings in the city of Paris.
- QA the Paris listings data: check the missing values, & calculate min, max & avg for each numeric field.

 ## Objective 2: Prepare for Visualisation
   
   - Create a DataFrame called paris_listings_neighbourhood. Group the Paris listings by neighbourhood and calculate the average price for each category. Sort by price in ascending order.
   - Create a DataFrame called paris_listings_accomodations. Filter your data down to the most expensive neighbourhood in Paris.Group it by accomodates and calculate the average price for each. Sort by price in ascending order.
   - Finally, create a DataFrame called paris_listings_over_time. Group the data by the year component of host_since. Calculate a count of rows to get the no. new hosts for each year, and the average price of listings for each year.

 ## Objective 3: Visualize the Data

- Build a horizontal bar chart of average rent price by neigbourhood. Which neigbourhoods stands out?
- Build a horizontal bar chart of average price by accommodates in the most expensive neigbourhood. Are the results intuitive?
- Finally, build line charts of new hosts per year and average price by year. What happened to new hosts in 2015? Was average price impacted? 
- Challenge : Plot both time series in a dual axis line charts!



ax.set_title("2015 Regulations Lead to Fewer New Hosts, Higher Prices")

- We can observe the decline in prices as the no. hosts rises, and then as the no. of hosts decline, the price starts to increase again.
 - In 2015, a sharp drop off in the no. of hosts which can be tied to the regulations that went into place.

