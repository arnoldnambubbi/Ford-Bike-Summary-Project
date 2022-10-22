# Ford-Bike-Summary-Project
The dataset has 183412 rows and 16 columns.  Some columns have missing data like: start_station_id, start_station_name , end_station_id, end_station_name, member_birth_year, member_gender 
What features in the dataset do you think will help support your investigation into your features of interest?
user_type will assist in categorizing the analysis in terms of subscribers and customers , start_station_name  and end_station_name will assist in knowing the location. member_gender has missing values but can assist to some level in categorizing in terms of gender, bike_share_for_all_trip, member_birth_year has missing data but can assist in calculating age
Univariate:
•	Subscribers seem to be the majority of the bike users-89%
•	Males are the main customers-75%
•	Seems the bikes are mostly used during the weekdays than weekends. Tuesdays and Thursdays as the peak days
•	Seems the most busy hours are 8am and 5pm. Possible it is when people are going to work and leaving from work to home
•	91% of the trips were not shared trips

### Discuss the distribution(s) of your variable(s) of interest. Were there any unusual points? Did you need to perform any transformations?
Subscribers were 89% of the bike users. Males are 75% of the bike users. 91% of the trips were not shared trips. It seems most of the bike users use the bikes for commute. As I have observed the peak hours for bike usage is 8am and 5pm. Also, the bikes are mostly used during the week and there is a decline of users on the weekend. Log transformation was done when plotting the second distribution of bike duration.
### Of the features you investigated, were there any unusual distributions? Did you perform any operations on the data to tidy, adjust, or change the form of the data? If so, why did you do this?
I created two columns from the start_time data. One column for the hour and the other for the day of the week. The two columns have helped in identifying trends of bike usage based on hour of the day and the day of the week.  



Bivariate:
•	There is a steady decline for bike usage during the weekends for the subscribers. The customers seem to be consistent on bike usage throughout the week
•	There is a noticeable decline for non-shared trips during the weekends. Shared trips seem to be consistent on bike usage throughout the week
•	Both the customers and subscribers have similar patterns when it comes to time. The peak times are 8am and 5pm
•	The peak time for non-shared trips is 8am and 5pm. Makes sense since they are the peak hours
•	There are more male bike users than females and there are more subscribers than customers. The same is translated on the above plot
•	On average customers seem to spend more time on the bikes than subscribers
•	On average, other and females tend to spend more time on the bikes than males
•	Shared trips and non-shared trips seem to have close average duration

Multivariate:
Talk about some of the relationships you observed in this part of the investigation. How did the feature(s) of interest vary with other features in the dataset?¶
Customers tend to be spending most time with the bikes at each time of the day with the peak times being 2am and 3am
Females and Other tend to be spending most time with the bikes at each time of the day with the peak times being 2am and 3am
The peak for shared trips is 2am and 3am


Did you observe any interesting relationships between the other features (not the main feature(s) of interest)?
Customers tend to be spending most time with the bikes at each time of the day with the peak times being 2am and 3am
Females and Other tend to be spending most time with the bikes at each time of the day with the peak times being 2am and 3am.
Were there any interesting or surprising interactions between features?
The peak time where the bike riders spend most their time with the bikes is between 2am and 3am
