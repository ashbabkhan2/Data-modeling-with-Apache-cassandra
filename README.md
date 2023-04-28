# Data-modeling-with-Apache-Cassandra
## Introduction
This project demonstrates how we use Apache Cassandra for Data Modeling 
Apache Cassandra uses query first approach where first we think about the query and 
then build the table.

## Data file
We use multiple CSV files and append them together and save them as a ``event_datafile_new.csv`` then we use the data of this CSV file to insert it into our table.
Below is the structure of the data.
![reference tag](images/image_event_datafile_new.jpg "adding a reference tag")

## Files and Folders of this project
### 1. event_data (folder)
This folder contains lots of CSV that we append together

### 2. event_datafile_new.csv (file)
We appended all of the CSV files together and save them to this CSV file 

### 3. data_modeling_with_apache_cassandra
this is the main code of this project which demonstrates data modeling apache cassandra
