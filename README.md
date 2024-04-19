# Python-project-DAB
DAB 111 - Python Final Project
Group Members:
Group No. 15
•	Ayush Raj Saxena - 0832578
•	Shreyas Joshi - 0837922
Project Objective:
This project contains the usage of Python, Pandas, SQLite3, and Flask. Using Pandas, we are reading data from dataset and stored in database using SQLite3 package. Flask is used to present stored data of database on web. Website contains mainly 3 pages, Home, About Us, and Cars (data). About Us page shows the details about dataset and definition of each variable. Cars (data) page shows the data stored in database using SQLite3.
Cars Dataset
Overview
US Cars ‘data was scraped from AUCTION EXPORT.com. This dataset included Information about 28 brands of clean and used vehicles for sale in US. Twelve features were assembled for each car in the dataset. The dataset covers price, brand, model, year, title status, mileage, color, vin, lot, state, country and condition of the car.
Source of Data
The dataset is sourced from Kaggle and is named "US Cars Dataset."
Link to Source: https://www.kaggle.com/datasets/doaaalsenani/usa-cers-dataset
Definition of Variables
•	Price: The sale price of the vehicle in the ad 
•	Years: The vehicle registration year 
•	Brand: The brand of car 
•	Model: model of the vehicle 
•	Color: Color of the vehicle 
•	State/City: The location in which the car is being available for purchase. 
•	Mileage: miles travelled by vehicle 
•	Vin: The vehicle identification number is a collection of 17 characters (digits and capital letters) 
•	Title Status: This feature included binary classification, which are clean title vehicles and salvage insurance. 
•	Lot: A lot number is an identification number assigned to a particular quantity or lot of material from a single manufacturer. For cars, a lot number is combined with a serial number to form the Vehicle Identification Number. 
•	Condition: Time 
Example Usage
Download required modules first:
•	Run command "pip install -r requirements.txt"
•	This will install all required packages for this project
Run app Locally:
Step 1:
•	Clone the project first or download zip of project and extract it
(Follow next step if you not see USA_cars_dataset.csvfile in root directory)
Step 2:
•	If you not see USA_cars_dataset.csvfile in root directory, then open new terminal in 'data processing' folder
•	Run "python clean_data.py" command, this will clean up original file and generate new file called ‘USA_cars_dataset.csv’
(Follow next step if you not see 'USCars.db' file in database directory) Step 3:
•	If you not see ‘USCars.db’ file in database directory, then open new terminal in 'database' folder
•	Run "python build_db.py" command, this will create new database file, create a table and insert data from USA_cars_dataset.csvfile
Step 4:
•	Open 'terminal' or 'cmd' in root directory of the project
•	Run "python app.py" command
•	Go to http://127.0.0.1:5000
•	And explore the website


