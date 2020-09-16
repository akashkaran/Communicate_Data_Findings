# (Bay Wheels Trip Data Exploration)
## by (Akash Karan)


## Dataset

This dataset contains data from Bike sharing service Bay Wheels fromerly known as Ford Go Bike. Data used for exploration can be found at https://s3.amazonaws.com/baywheels-data/index.html . I have manually downloaded the files for the year 2019 from given link and extracted it on my local machine after that i have merged all the 12 files using pandas asnd created a single master csv which cotains all the required data of Bay Wheels trips for the year 2019.
The dataset has total of 2506983 records and 15 features with information like user id, bike id, location co-ordinates, name, start time  , end time of the trip, rental method etc.


## Summary of Findings

The dataset had very limited featureset to look into with very  less features giving any information on the users using the service. So based on the available information below are the obsevations we have found.

Majority of rental rides are of very short duration of less than 30 minutes. Most of the rides are taken by the subscriber user types with more rides taken on weekdays than that of weekends. Majority of  rides are originated or ended from less than 5 stations so company could focus on this stations and running some campaigns might help them to attract more customer base.



## Key Insights for Presentation

* Majority of the rides almost 95% are of very short duration.
* More rides are taken on weekdays than that of weekends.
* Majority of users ( > 80% )using this rental service are subscribers of bay wheels.
* Servicce is used most in summer than in winter.
* Average duration spend on the trip varies from user types Custome and Subscriber.