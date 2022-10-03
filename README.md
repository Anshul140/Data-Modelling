# Data-Modelling
- Data modeling is the process of creating a visual representation of either a whole information system or parts of it to communicate connections between data points and structures

## Types of Data-Models:
### Conceptual Data Models-
![Conceptual Data Models](https://user-images.githubusercontent.com/71965548/193622923-c80b41d7-17eb-4327-a292-9bd687f2c1f7.JPG)
  - highly abstract
  - only contains entities
  - no software is needed, can be done on paper

### Logical Data Models-
![Logical Data Models](https://user-images.githubusercontent.com/71965548/193623502-24e8b6d8-cccb-4b56-937d-852b5a5a97fa.JPG)
  - adds more details to conceptual model
  - here each entity contains its attributes
  - key attributes are also specified
  - user friendly attribute names
  - generic in nature(not specific to any database)
  - softwares such as PowerDesigner, Erwin can be used for this type of model making

### Physical Data Models-
![Physical Data Models](https://user-images.githubusercontent.com/71965548/193625882-713e40a9-acfa-4767-a742-e8cde132cdd5.JPG)
  - here terminologies change
  - entities are referred as tables, attributes as columns
  - each attribute also contains its datatype
  - specific for a particular database
  - database compatible attribute(column) names
  
## What this project contains?
  - basic tutorial for how to load datasets into python using librarires such as pandas
  - (data was taken from kaggle, related to population of various countries)
  - how to connect python and database(here postgresql), library used: psycopg2
  - model making in Database according data source, and loading data of datasets into database
  - cleaning of data, before loading into Database
  
  
