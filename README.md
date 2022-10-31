# Data Modelling with Cassandra

This repository serves as a submission for Udacity data engineer nanodegree.

## Project Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

## How to Run?

This section describes how to get use this repositrory.

**Database setup**
To run this project you will need connectivity to a Cassandra NOSQL database with below details.
A docker container can be downloaded from here: https://hub.docker.com/_/cassandra
```
docker pull cassandra
```
Running the below command will start the container.
```
docker run --name some-cassandra -d -p 9042:9042 cassandra
```

**Python environemnt setup**
```
pip install -r requirements.txt
```

**Run the JUpyter notebook**
```
jupyter notebook
```

## Project Structure
```
\event_data --> holds the sample data for the project
\project_cassandra.ipynb --> jupyter notebook that includes the etl code
```
