# DAB 111 - Python Final Project

### Group Members:

Group Members:

 - Shreyas Joshi - 0837922
 - Ayush Raj Saxena - 0832578
 
### Project Objective:

This project contains the usage of Python, Pandas, SQLite3, and Flask. Using Pandas, we are reading data from dataset and stored in database using SQLite3 package. Flask is used to present stored data of database on web.
Website contains mainly 3 pages, Home, About Us, and Cars (data). About Us page shows the details about dataset and defination of each variable. Cars (data) page shows the data stored in database using SQLite3.

### Source of Data

The dataset is sourced from Kaggle and is named "US Cars Dataset."

**Link to Source:** [US Cars Dataset](https://www.kaggle.com/datasets/doaaalsenani/usa-cers-dataset)

## Example Usage
 ### Download required modules first:

 - Run command "pip install -r requirements.txt"
 - This will install all required packages for this project

 ### Run app Locally:

Step 1:
- Clone the project first or download zip of project and extract it
 (Follow next step if you not see 'USCars.db' file in database directory)

Step 2:
 - If you not see 'USCars.db' file in database directory, then open new terminal in 'database' folder
 - Run "python build_db.py" command, this will create new database file, create a table and insert data from 'USA_cars_datasets.csv' file

Step 4:
 - Open 'terminal' or 'cmd' in root directory of the project
 - Run "python app.py" command
 - Go to http://127.0.0.1:5000
 - And explore the website
