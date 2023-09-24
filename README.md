# sqlite_database_operations
## Week 3 Homework Assignment: Introduction to Databases with SQLite

### Loading Dataset
I loaded two different datasets; one from Stony Brook Hospital and St Joseph CHS from github
I imported pandas and numpy to start my exploratory data analysis
I filled in missing values with unknown for categorical columns and with 0 for numerical columns for both datasets
I claned white spaces and special charactors from both datasets
I obtained frequency counts of categorical columns for both datasets
I then obtained descriptive statistics of all numerical columns such as std, mean and variacne etc..

### SQLite Database Setup
I loaded packages required such as pandas and sqlite3. I also included a from sqlalchemy and import create_engine command
I created a temporary + local DB using SQLITE called health.db
I then created a table duplicating some random values from the st joe csv file using c.execute and then commiting via conn.commit
I started by creating the columns copied from the st joe csv file such as code description, price, billing codes and package description. 
Then I created the table and name of the table 
Then I inserted fake values copied randomly from the st joe csv file by creating a query variable and then using the command INSERT INTO to insert fake values for the new created earlier and then commiting.
An engine was then created to connect to sqlite database and start sqlalchemy
Using the dataframe from the st joe csv file I created a new table

