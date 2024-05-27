# Hospital Facility Management System

This Hospital Facility Management System is a web application built with Flask and MongoDB Atlas. It allows users to manage hospital facilities across Malawi. Users can create new facilities, archive existing ones, search for facilities, and filter the created list. The system also integrates with the Master Health Facility Registry (MHFR) APIs to extract data about existing facilities.

## Features

- **Flask Framework**: The web application is built using Flask, a micro web framework for Python.
- **MongoDB Atlas**: MongoDB Atlas is used as the database to store facility data.
- **API Integration**: The application integrates with the Master Health Facility Registry (MHFR) APIs to extract data about existing facilities.
- **Search Functionality**: Users can search for facilities within the application, with the search functionality implemented to include searches from the MHFR APIs.
- **Login Required**: User authentication is implemented, requiring users to create an account and log in to access the system.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/blessingsMlundira/luke_international_facility_project.git


   Set up MongoDB Atlas:

Create a MongoDB Atlas account.
Create a new cluster and database for the application.
Obtain the connection string and update the MONGO_URI variable in the Flask application accordingly. Ensure that MongoDB Atlas is configured to accept connections from a live IP address to enable user login.
then run the command "python main.py".... replace all current connection strings with your acccount connection strings to successully connect to the database


