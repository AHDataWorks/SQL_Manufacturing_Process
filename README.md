# Manufacturing Process Optimization Project using SQL

## Project Overview
This project focuses on optimizing a hypothetical manufacturing processes through detailed SQL analysis and manipulation. 

- ### Dataset
The hypothetical dataset, manufacturing_parts.csv, comprises measurements of manufacturing parts including length, width, height, and the associated operator. 

## Environment Setup
Instructions are provided for setting up the SQL environment necessary to execute the analysis, including the installation of required software and configuration of the database.

- ### Dependencies
The project relies on several key dependencies, including:

- SQL Database: PostgreSQL (or MySQL, SQLite, etc., depending on the database used in the project)
- Python: For running the Jupyter notebook and any associated scripts
- Python Libraries: pandas for data manipulation, sqlalchemy for database connection, and potentially psycopg2 (for PostgreSQL) or another database adapter depending on the SQL database choice

**Installing Dependencies**
```
# It's recommended to use a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install required Python libraries
pip install pandas sqlalchemy psycopg2 jupyterlab
```

- ### Setting Up Environment Variables
The project may require setting up environment variables for database connection strings or API keys. Below is a method to set these up securely:
```
echo 'export DATABASE_URL="your_database_connection_string"' >> ~/.bash_profile
echo 'export API_KEY="your_api_key"' >> ~/.bash_profile
source ~/.bash_profile

# Verify the variables are set
echo $DATABASE_URL
echo $API_KEY
```

## Project Structure

- ### Creating the Database Table
Instructions are provided for creating a SQL table that accurately represents the dataset's structure, including the correct data types for each column.

- ### Executing SQL Queries

The notebook details a series of SQL queries designed to analyze the dataset. These queries cover a range of analyses from basic data overview (e.g., count of parts per operator) to more complex queries aimed at uncovering inefficiencies (e.g., variations in part dimensions).

- ### Analyzing the Results
Each query's output is followed by an analysis section, where the results are interpreted to offer insights into the manufacturing process. This includes identifying patterns, anomalies, and suggesting potential areas for process improvement.

## License

MIT License


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Copyright (c) 2024 AHData_Works
