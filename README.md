# VPark
This is a website that uses streamlit libraries to run. It is a parking website with all the features to reserve, pay and checkout options. It also saves the user data for future use. 

Overview

The Smart Parking System is a Python-based web application built using Streamlit. It provides a simple and interactive interface for users to book parking slots, view availability, and generate payment receipts. The system connects to a MySQL database to manage user data, parking slots, and payments in real-time.
This project aims to reduce congestion, optimize space usage, and make parking management smart and digital.

Technologies Used:
Frontend: Streamlit
Backend: Python
Database: MySQL
Libraries:
streamlit
mysql-connector-python
pillow (for image/receipt handling)
datetime (for time tracking)

Installation & Setup:
1. Set Up the Database

CREATE DATABASE parking; #Sql code

con = mysql.connector.connect(
    host="localhost", #change according to the system
    user="your_mysql_username", # change according to user
    password="your_mysql_password", #change according to user
    database="parking"
)

2. Run the Application:
#in terminal run 
streamlit run app.py


#Darshan Krishna
💼 Student / Developer
