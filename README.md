# JR Fullstack Developer Assessment

## -> Backend - REST API
An IP Address Management REST API on top of any database of your choice. It has the ability to add IP Addresses by CIDR block and then either acquire or release IP addresses individually. Each IP address will have a status associated with it that is either “available” or “acquired”.

#### The REST API supports four endpoints:

* Create IP addresses - take in a CIDR block (e.g. 10.0.0.1/24) and add all IP addresses within that block to the data store with status “available”
* List IP addresses - return all IP addresses in the system with their current status
* Acquire an IP - set the status of a certain IP to “acquired”
* Release an IP - set the status of a certain IP to “available”


## -> Frontend - Air Quality Assessment Tool

Create a simple Air Quality Assessment Tool using the front end technologies of your choice that utilizes Open AQ (https://docs.openaq.org/docs) Platform API. It will have the ability to compare the Air Quality of two cities.

The tool must:

Allow the user to input two cities
Display the air quality of the corresponding cities, allowing the user to compare the two
Gracefully handle any API or user errors
Tool should be easily used by the general public

## -> AI & Machine Learning
* Choose an appropriate machine learning or deep learning model for the project.
* Implement the model using a popular AI framework (e.g., TensorFlow, PyTorch).
* Train the model on the preprocessed dataset.
* Evaluate the model's performance using relevant metrics.
* Create visualizations or reports to showcase the evaluation results.


## Submission
Choose **one** of the following:
* REST API
* Frontend Application
* AI & Machine Learning

Push your code here, send a link if you deployed the application.


## Bonus
Choose one of the following:
* Deploy any of the REST API / Application / Model to a Cloud platform (ex. AWS or Azure).
