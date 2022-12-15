# NYC CitiBike Analysis 

## Overview:
This project focused on data collection, validation and visualization. First I collected data from CitiBike NYC, specfically the August 2019 trip data. Then I created a Pandas dataframe from the original file and converted the 'Trip Duration' data to a suitable Datetime Format. The clean data was then written into a CSV and used in Tableau to analyze and create multiple visualizations. 

### Resources:
* Source Code: [NYC_CitiBike_Challenge_Code](NYC_CitiBike_Challenge_Starter_Code.ipynb)
* Source Data: [201908-citibike-tripdata](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip)
* Software: [Tableau Public](https://public.tableau.com/app/discover), [Pandas](https://pandas.pydata.org/docs/index.html)

#### Deliverables:
- [x] Deliverable 1: Change Trip Duration to a Datetime Format
- [x] Deliverable 2: Create Visualizations for the Trip Analysis
- [x] Deliverable 3: Create a Story and Report for the Final Presentation

### Statistical Analysis: 
Looking at the NYC data, there is strong evidence that the CitiBike model is suitable for Des Moines, Iowa.  

Image 1: ![Checkout Times by Gender](https://github.com/caseygomez/bikesharing/blob/main/Visuals/CheckoutTime:Gender.png)

Looking at image 1, Checkout Times by Gender, males average shorter rides more frequently, but females also checkout bikes often and occassionally for longer durations. With an almost even 50% split in the Des Moines gender population breakdown, there is a large market in need for the bike share program. 

Image 2: ![Trips by Weekday per Hour](https://github.com/caseygomez/bikesharing/blob/main/Visuals/Weekday:Hour.png)

Looking at image 2, Peak Riding Hours, the data shows there are peaks in bike checkouts around morning and evening rush hour. With Des Moines economic growth and strong insurance business center there is evidence that employees need a traffic friendly afternative to driving to work. 

Image 3: ![Top Starting Location](https://github.com/caseygomez/bikesharing/blob/main/Visuals/StartingLocation.png) 

Looking at image 3, Top Starting Location, bikes are most frequently checked out at popular business and tourist locations. Identifying similar locations will be profittable in Des Moines. 

Image 4: ![Bike Utilization](https://github.com/caseygomez/bikesharing/blob/main/Visuals/BikeUtilization.png)

Looking at image 4, Bike Utilization, there are hundreds of bikes with a proportion utilized more than others. Des Moines is 88 sq mi (land) and New York City is 300 sq mi (land). That means Des Moines is smaller, and potentially more accessible by bike. 

Image 5: ![User Trips by Gender per Weekday](https://github.com/caseygomez/bikesharing/blob/main/Visuals/User:Gender:Weekday.png)

Looking at image 5, User Trips by Gender per weekday, male subscribers frequently uses bikes every day of the week. Offering membership perks and incentives for sharing sign-up codes can encourage more subscribers. This will lead to profitable growth.  


#### Results: 
To view the complete visual story checkout the [Tableau CitiBike Dashboard](https://public.tableau.com/views/NYCCitibikeAnalysis_16710565441080/NYCCitibikeAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link). Des Moines appears to be a strong economic city, with a booming business center. It's smaller square mileage is accessible by bike and even has tourist appeal with waterfront trails to bikeride. 