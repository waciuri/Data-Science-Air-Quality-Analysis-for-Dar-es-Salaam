**Air Quality Analysis Project**

 **Overview**
This project is a data analysis assignment designed to explore and process air quality data using Python and a MongoDB database.
The analysis is conducted within a Jupyter Notebook environment, focusing specifically on:
Connecting to a MongoDB database.
Querying and exploring air quality data, such as finding distinct measurement sites.
Analyzing air quality metrics like PM2.5 Level.
Generating visualizations (implied by the use of Plotly configurations within the notebook's HTML export).

 **Getting Started**
Prerequisites
To run this project, you will need:
Python (3.x recommended).
A running MongoDB instance accessible on port 27017. The database must contain:
A database named air-quality.
A collection within that database named dar-es-salaam.
The required Python libraries.
Installation
Install the necessary Python library, which includes pymongo for database connectivity:
Bash
# Example assuming use of PyMongo (as suggested by the code)
pip install pymongo


**How to Run the Analysis**
Open the Notebook: Open the main project file (Air_quality_analysis.ipynb - assuming the HTML was exported from this file) in a Jupyter environment.
Configure Database Host: Locate the cell for connecting to MongoDB and update the host variable with the correct IP address of your MongoDB machine.
Note: The notebook contains a warning that the IP address is dynamic and must be checked before proceeding.
Execute Cells: Run all the notebook cells in sequential order to perform the data connection, exploration, and analysis.

 **Data Summary**
The notebook begins by connecting to the specified database and performing initial exploration tasks:
Database: air-quality
Collection: dar-es-salaam
Exploration Example: Initial queries identify the distinct measurement sites available in the data (e.g., sites 11 and 23 were present in one execution).

This project was developed as part of an academic assignment.


