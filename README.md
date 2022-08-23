# Carpark-Info
A take-home coding assignment for backend developer interview. 

## Your Task
1. Given the CSV dataset (hdb-carpark-information-<timestamp>.csv) that contains details of a list of carparks, design the database to store the given information in the dataset and to support the below given user stories.
2. Write a batch job that will process and store the information into the database of your choice. This is a daily delta file that will be interfaced over from source. In the event there is an error processing the records in the file, the entire file should rollback.
3. Write the APIs that will fulfill the below given user stories.

### User Stories
* As a user, I want to be able to filter the list of carpark by the following criteria:
  - Carpark that offer free parking?
  - Carpark that offer night parking?
  - Carpark that can meet my vehicle height requirement.
* As a user, I want to be able to add a specific carpark as my favourite.

## Getting Started
Please review the information in this section before you get started with your development. 

### Tech Stack
You may choose to develop the application using either of the following stack:
* Spring Boot/Spring Batch with H2 database and Hibernate ORM
* .NET Core 6.x with SQLLite database and Entity Framework Core ORM

Note: Microsoft technologies are primarily used within the firm.

### Tools
You are free to choose the tools you are most comfortable with.

## Basic Expectation
* Ability to design data schema, apply normalisation technique and enhance query performances, if applicable.
* Write readable, performant and well-documented codes.
* Code design / architecture should support implementation of unit testing.
* Code design / architecture should be flexible to changes / open to extensions, e.g. changing of data access technology, changing of interface file format from csv to JSON etc.
* Write clear and concise commit message.

## Time Estimates
This assignment should take about 2 to 4 hours of your time depending on your level of experiences. 

## Need Help
Create a github issues. We'll get back to you.
