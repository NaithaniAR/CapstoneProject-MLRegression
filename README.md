# NYC Taxi Trip Duration

# DOMAIN: Transportation

# By Arnav Naithani - 30 June April, 2022


The dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published by the NYC Taxi and Limousine Commission (TLC). The data was sampled and cleaned for the purposes of this playground. Based on individual trip attributes, should predict the duration of each trip.

## Source:

NYC Taxi and Limousine Commission (TLC) : http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml

Kaggle : https://www.kaggle.com/c/nyc-taxi-trip-duration/data

Download Data : https://drive.google.com/open?id=1OyOC9y2x4uyT7drXJBOEZ2yRBktiQB8H

## Details:

File descriptions :

● train.csv - the dataset (contains 1458644 trip records)

## Data fields

● id - a unique identifier for each trip

● vendor_id - a code indicating the provider associated with the trip record

● pickup_datetime - date and time when the meter was engaged

● dropoff_datetime - date and time when the meter was disengaged

● passenger_count - the number of passengers in the vehicle (driver entered value)

● pickup_longitude - the longitude where the meter was engaged

● pickup_latitude - the latitude where the meter was engaged

● dropoff_longitude - the longitude where the meter was disengaged

● dropoff_latitude - the latitude where the meter was disengaged

● store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip

● trip_duration - duration of the trip in seconds

## Pickup Locations:
![image](https://github.com/NaithaniAR/NYC-Taxi-Trip-Time-Prediction---Capstone-Project.ipynb/blob/f27c2c490e6fa97cd7667a12a534d701688c4c86/Images/Pickup.PNG)
## Dropoff Locations:
![image](https://github.com/NaithaniAR/NYC-Taxi-Trip-Time-Prediction---Capstone-Project.ipynb/blob/f180cf4e2487fd883d2601017d180914afadd2bb/Images/Dropoff%20.PNG)



## Objective:
## Build a model that predicts the total trip duration of taxi trips in New York City.
