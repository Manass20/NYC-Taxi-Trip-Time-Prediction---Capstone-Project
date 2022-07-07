# NYC-Taxi-Trip-Time-Prediction---Capstone-Project
## Problem Statement
My task is to build a model that predicts the total ride duration of taxi trips in New York City. Your primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.
## Data Description
The dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published by the NYC Taxi and Limousine Commission (TLC). The data was sampled and cleaned for the purposes of this project. Based on individual trip attributes, you should predict the duration of each trip in the test set. NYC Taxi Data.csv - The Dataset contains 1458644 trip records.

The primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.
## Data Overview
●id - A unique identifier for each trip.

● vendor_id - A code indicating the provider associated with the trip record.

● pickup_datetime - Date and time when the meter was engaged.

● dropoff_datetime - Date and time when the meter was disengaged.

● passenger_count - The number of passengers in the vehicle. (driver entered value)

● pickup_longitude - The longitude where the meter was engaged.

● pickup_latitude - The latitude where the meter was engaged.

● dropoff_longitude - The longitude where the meter was disengaged.

● dropoff_latitude - The latitude where the meter was disengaged.

● store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle
                                  	memory before sending to the vendor because of the vehicle did not
                                  	have a connection to the server
Y=store and forward trip; 
N=not a store and forward trip.

● trip_duration - duration of the trip in seconds.
