# Bikesharing

### Purpose
The purpose of this Bike Share analysis is to evaluate the effectiveness of the New York City Citi Bike Share program to determine how a similar program Des Moines, Iowa might work.

### Deliverable 1
Using Python and Pandas, I converted the "tripduration" column in the 201908-citibike-tripdata.csv from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After the conversion I exported the resulting Dataframe to a CSV file 201908-citibike-tripdata(mod).csv. Below is a clip of the code used to covert the column and the resulting converted column.

![image](https://github.com/blueschistrocks/bikesharing/blob/dbadb59a7e4a6617a3f4963389fbafb5c82a0b78/images/Screen%20Shot%202022-05-17%20at%208.32.41%20PM.png)<br>


### Deliverable 2

Using the converted Dataframe and Tableau I created seven visualizations of the New York City Bike Share data.


#### Check Out Time for Users
![image](https://github.com/blueschistrocks/bikesharing/blob/128d429d92d5eae7fff91066a9f767b2b6148e08/images/Screen%20Shot%202022-05-16%20at%209.17.11%20PM.png)<br>


#### Check Out Time for Users by Gender
![image](https://github.com/blueschistrocks/bikesharing/blob/128d429d92d5eae7fff91066a9f767b2b6148e08/images/Screen%20Shot%202022-05-16%20at%209.17.30%20PM.png)<br>

#### Trips by Weekday Per Hour
![image](https://github.com/blueschistrocks/bikesharing/blob/3092148142154dcee94de40b21ae12ba609cfb9b/images/Screen%20Shot%202022-05-16%20at%209.17.59%20PM.png)<br>


#### Trips by Weekday Per Hour by Gender
![image](https://github.com/blueschistrocks/bikesharing/blob/3092148142154dcee94de40b21ae12ba609cfb9b/images/Screen%20Shot%202022-05-16%20at%209.18.15%20PM.png)<br>


#### Trips by Gender by Weekday 
![image](https://github.com/blueschistrocks/bikesharing/blob/3092148142154dcee94de40b21ae12ba609cfb9b/images/Screen%20Shot%202022-05-16%20at%209.18.40%20PM.png)<br>


#### Top Starting Locations 
![image](https://github.com/blueschistrocks/bikesharing/blob/3092148142154dcee94de40b21ae12ba609cfb9b/images/Screen%20Shot%202022-05-16%20at%209.19.03%20PM.png)<br>


#### Top End Locations 
![image](https://github.com/blueschistrocks/bikesharing/blob/3092148142154dcee94de40b21ae12ba609cfb9b/images/Screen%20Shot%202022-05-16%20at%209.19.28%20PM.png)<br>



### Deliverable 3

Using the seven seven visualizations created in Deliverable 2 I created a Tableau story.  The link to the story below:

[Link to Tableau Story](https://public.tableau.com/views/Bike_share_challenge1/NCYBikeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)


### Summary
The data appears to indicate that male users are more likely to use the service. Time usage data indicates that most users are work commuters.   Subscribers to the service use bikes more often than customers. Customers appear to use the service more often on the weekends.  The service appears to be most often used in Manhattan, therefore demographics and urban density may be a factor in the increase use.  

Additional research into the demographics and urban density differences between the areas that utilized the service the most and used the service the least.  Additional visualizations that would be helpful include:
- Heat map to compare user types by weekday per hour, and
- Combine weather data to create a visualization to show any seasonal changes in service use.

