# NYC CitiBike Analysis 

## Overview:
This project focused on data collection, validation and visualization. First I collected data from CitiBike NYC, specfically the August 2019 trip data. Then using Jupyter Notebook, I created a Pandas dataframe from the original file and converted the 'Trip Duration' data to a suitable Datetime Format. The clean data was written into a CSV file and used in Tableau to analyze and create multiple visualizations. 

------
### Resources:
* Source Code: [NYC_CitiBike_Challenge_Code](NYC_CitiBike_Challenge_Starter_Code.ipynb)
* Source Data: [201908-citibike-tripdata](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip)
* Software: [Tableau Public](https://public.tableau.com/app/discover), [Pandas](https://pandas.pydata.org/docs/index.html)

---
### Deliverables:
- [x] Deliverable 1: Change Trip Duration to a Datetime Format
- [x] Deliverable 2: Create Visualizations for the Trip Analysis
- [x] Deliverable 3: Create a Story and Report for the Final Presentation

---
### Statistical Analysis: 
Looking at the NYC data, there is strong evidence that the CitiBike model is suitable for Des Moines, Iowa.  

Image 1: ![Checkout Times for Users](https://github.com/caseygomez/bikesharing/blob/main/Visuals/CheckoutTime:Users.png)

Image 1, Checkout Times for Users, confirms most trips last five minutes. The data also shows there are several hundred trips during the month of August that last an hour or longer.  

Image 2: ![Checkout Times by Gender](https://github.com/caseygomez/bikesharing/blob/main/Visuals/CheckoutTime:Gender.png)

Looking at image 2, Checkout Times by Gender, males average shorter rides more frequently, but females also checkout bikes often and occassionally for longer durations. With the Des Moines population growing, there is a large market in need for the bike share program. 

Image 3: ![Trips by Weekday per Hour](https://github.com/caseygomez/bikesharing/blob/main/Visuals/Weekday:Hour.png)

Creating a heatmap, image 3, Peak Riding Hours, shows there are peaks in bike check-outs around morning and evening rush hour. With the Des Moines economic growth and strong insurance business center there is evidence that employees need a traffic friendly afternative to driving to work. 

Image 4: ![Trips by Gender per Weekday](https://github.com/caseygomez/bikesharing/blob/main/Visuals/Gender:Weekday:Hour.png)

Image 4, Trips by Gender per Weekday breaks the previous heatmap down by Gender. The data shows there is an increase in rides during rush hour for all groups, however males are still the most frequent users. 

Image 5: ![User Trips by Gender](https://github.com/caseygomez/bikesharing/blob/main/Visuals/User:Gender:Weekday.png)

The data shows most users are in fact subscribers. Additionally we see there are more male subscribers than female. Offering perks for subscribers and incentives for new accounts may boost growth. 

Image 6: ![Top Starting Location](https://github.com/caseygomez/bikesharing/blob/main/Visuals/StartingLocation.png) 

Top Starting Location demonstrates bikes are most frequently checked out at popular business and tourist locations. Identifying similar locations will be profitable in Des Moines. 

Image 7: ![Bike Utilization](https://github.com/caseygomez/bikesharing/blob/main/Visuals/BikeUtilization.png)

Looking at image 7, Bike Utilization, there are hundreds of bikes with a proportion utilized more than others. Des Moines is 88 sq mi (land) and New York City is 300 sq mi (land). That means Des Moines is smaller, and potentially more accessible by bike. 

---
### Results: 
To view the complete visual story checkout the [Tableau CitiBike Dashboard](https://public.tableau.com/views/NYCCitibikeAnalysis_16710565441080/NYCCitibikeAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link). Des Moines appears to be a strong economic city, with a booming business center. It's smaller square mileage is accessible by bike and even has tourist appeal with waterfront trails to bikeride. 