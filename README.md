## UBER MOVEMENT DATA 2019 (Quarter-3) ||  Uber-Fast Trips Any Time, Almost Anywhere
#### Uber customers typically spend far less time waiting than customers of traditional taxi services. Riders also have the option to share rides with others heading in the same direction through UberPoo. Let's go for a systematic data study of the ever super cool riding app. 

![20](https://user-images.githubusercontent.com/67545412/89116766-7bd5ce00-d4b5-11ea-8058-9cf20e38954b.jpg)




Let's indulge in an insightful analysis of the UBER MOVEMENT.


##                    UBER DATA ANALYSIS

#### Location: Bangalore Quarter-3

#### Objective: -
 1.	Given a place in the city, find all places within 30 minutes of driving distance
 2.	Given an origin and a destination, find the best and worst day of the week for commuting.

#### Data Resources: -
 1.	Data was exclusively downloaded from Ubermovement.com for they city of Bangalore, Quarter-3. The Travel Times Uber Movement data for Bangalore. 
 2.	Weekly, Hourly, Weekday, Weekend, Monthly, Wards data was downloaded to study and analyse the commute behaviour of UBER in the city of Bangalore. 


##### Converting Raw Data. 
1.	The Wards data received has void columns and empty rows till we get the value for the next feature. 
2.	Working with this data, would fetch us very poor visualisations. So, we first convert the json file to csv file online. 
3.	Following this we add alternate blank columns in between the data columns and equate a formula such that if length of the right column is greater than the right column, so the right one gets pasted else the left one. 
4.	Following this, step we fill our entire empty void datasets as shown in the below figure and save the new dataset as modified dataset. 


![1](https://user-images.githubusercontent.com/67545412/89106929-e867b300-d44a-11ea-8016-7325d6d71018.jpg)


![2](https://user-images.githubusercontent.com/67545412/89106930-eaca0d00-d44a-11ea-980e-1ec1e2db51c8.jpg)


#### Plotting the ward dataset in Bangalore Quarter-3. 

![3](https://user-images.githubusercontent.com/67545412/89106931-ebfb3a00-d44a-11ea-881d-2a02201ae748.jpg)



#### Further Plotting the ward dataset with its centroid gives us a wholistic view of the Bangalore Quarter-3.
![4](https://user-images.githubusercontent.com/67545412/89106932-ebfb3a00-d44a-11ea-8ee2-78d0f99b5591.jpg)





#### DATA DICTIONARY

![5](https://user-images.githubusercontent.com/67545412/89106933-ec93d080-d44a-11ea-9fc0-bd342f17c247.jpg)


##### 1.	Sourceid- The sourceid stands as a notation for the starting ward when the trip begins. 
##### 2.	Destid-The destid stands as a notation for the ending ward where the passenger is dropped. 
##### 3.	Hod- Acronym of Hour of the Day. This tells us the hour of the day.  
##### 4.	Mean_travel_time- Aggregate Travel Time to Commute (in Seconds)[MAX]
##### 5.	Standard_deviation_travel_time-The amount by which the aggregate time travel may be deviated in seconds. 
##### 6.	Geometric_mean_travel_time-The Central Time travel to commute{in seconds)[MIN]
##### 7.	Geometric_standard_deviation_travel_time-The amount by which the Central Time travel to commute deviates in seconds. 
##### 8.	Geometry-It simply indicates the geometry of the polygon/ward. 



#### We’re likely to get an estimate of how the delay, the travel times of commutes vary at different hours of the day through the various visualizations underneath with the objective of optimizing our travels, with an explicit inclusion of extension for a better obtained Uber Movement with suggestive plans for an even more passenger friendly travel. 



### Let's indulge in an insightful analysis of the UBER MOVEMENT. 

![6](https://user-images.githubusercontent.com/67545412/89106934-ef8ec100-d44a-11ea-9d6f-f964dfa7d0b3.jpg)


#### The Geometric mean travel time varies with different hours of the day. 

![7](https://user-images.githubusercontent.com/67545412/89106935-f0275780-d44a-11ea-9903-88a15babca1f.jpg)


#### The Mean travel time varies with different hours of the day. 

###### The above bar plot gives us an idea about the order of maximum commutes at different binned hours of the day.


#### Furthermore, we bin the dataset ‘Hour Of the Day’ into segments for better understanding of commute behavior with the different hours of the day. 

![8](https://user-images.githubusercontent.com/67545412/89106936-f0bfee00-d44a-11ea-9547-474aebe63f3a.jpg)




#### Incorporating the binning of dataset,gives the HOD column a categorical division from numeric. 

![10](https://user-images.githubusercontent.com/67545412/89106937-f1588480-d44a-11ea-9110-8066c1610232.jpg)




###### For instance, Evening is the time when maximum Uber movements occur for office-goers,school children, workers for they  return to their respective homes’.
###### The morning schedule is further divided into early morning, morning, afternoon which certainly distributes the commute movements by various professionals or children dependent on the population that’s dependency on Uber for commuting. 
###### Late Night with the lowest count is obvious for we commute at night in case of catching hold of a train, or late night workers, or attending to an event or a party. 


![12](https://user-images.githubusercontent.com/67545412/89106939-f1f11b00-d44a-11ea-8a5a-fdecaccf79c6.jpg)


###### The Geometric Mean Travel Time with different hours of the day is highest for morning, for in the morning, commute is high and there’s atraffic for it happens to be the hour of rush and commutes takes highest time for this hour travel. 
###### Following this is the afternoon , evening where office-goers, school children return back. 
###### Least is for Late-night for Uber Movement operates for firstly a constraint timing at night with limited acceptance of commutes. late night travel arises in cases of emergency, party or an event, or professionals working overnight shift. 


![UBER PHOTO GIT](https://user-images.githubusercontent.com/67545412/89104669-af264780-d438-11ea-94cd-82ed9955df0f.jpg)

###### The Mean Travel Time with different hours of the day is highest for morning, for in the morning, commute is high and there’s a traffic for it happens to be the hour of rush and commutes takes highest time for this hour travel. 
###### Following this is the afternoon , evening where office-goers, school children return back. 
###### Least is for Late-night for Uber Movement operates for firstly a constraint timing at night with limited acceptance of commutes. Late-night travel arises in cases of emergency, party or an event, or professionals working overnight shift.

![14](https://user-images.githubusercontent.com/67545412/89106941-f3224800-d44a-11ea-80cb-829e563f6263.jpg)


###### The deviation time is least for morning, following I the afternoon, early morning, evening and then the late night. 
###### Morning, Early Morning, Afternoon are times when the highways, roads, lanes, bridges open. 
###### Whereas as the evening approaches, and the late night, the bridges, the highways, the roads have a restricted movement. This results to greater deviation to the standard time for the driver opts for longer routes. 

![15](https://user-images.githubusercontent.com/67545412/89106942-f3bade80-d44a-11ea-9f08-9920de23c19d.jpg)


###### This depicts the variation in the data distribution of the mean_travel-time and the geometric_mean_travel_time .


### Applying Gradient Boost Model 

![16](https://user-images.githubusercontent.com/67545412/89116611-bccce300-d4b3-11ea-8af7-c2da9d0e0788.jpg)

#### Checking Score

![17](https://user-images.githubusercontent.com/67545412/89116612-bdfe1000-d4b3-11ea-9900-9cfd38955dc0.jpg)

### Comparing the Mean Travel Time Predicted by our Model with that of the Google Maps between the Source Wards in Bangalore with that of the Destination Ward, gives us an outlined idea about how well our model is faring in estimating the travel time between Source and Destination.  

![1234](https://user-images.githubusercontent.com/67545412/89714965-ec9e4e00-d9bf-11ea-9426-4e820066830d.jpg)



#### With comparative calculation of the predicted model and the Google maps predicted time,indicates our prediction is accurate by 71 percent as it differs from the estimated Google Map time prediction by around 25-30%. 

