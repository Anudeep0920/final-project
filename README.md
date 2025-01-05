# The Interplay Between Crime Rates, Drug Overdose Deaths, and Life Expectancy Disparities

## Public Health and Crime Data Analysis

This project processes and analyzes public health and crime datasets using MongoDB, SQLite, and Python. The project focuses on data acquisition, transformation, preprocessing, visualization, and analysis to extract valuable insights.

## Features
- Downloads datasets from public APIs.
- Stores data in MongoDB and SQLite databases.
- Transforms raw JSON data into structured formats for analysis.
- Preprocesses datasets to handle missing or invalid values.
- Provides statistical analyses and visualizations.

# Prerequisites

## Installations
Ensure you have the following installed and running on your system:

- MongoDB: Download and install from MongoDB's official site : https://www.mongodb.com/try/download/community.
- SQLite: Pre-installed on most operating systems. For updates, visit SQLite's website : https://www.sqlite.org/download.html .

## Required Python Libraries
Install any required Python libraries using pip:

pip install pymongo pandas matplotlib requests


# Usage
## Data Acquisition

Download datasets from CDC and Los Angeles City data APIs using the main() function in the acquisition script.
- Load datasets into MongoDB collections.
- Data Transformation
- Use MongoDB to read data and convert it into CSV files.
- Load the structured data into SQLite for further analysis.

## Data Preprocessing
Execute preprocessing scripts to clean and structure data:

- Drug Overdose data
- Life Expectancy data
- Crime data

## Analysis and Visualizations

- Perform analyses like yearly trends, crime type distribution, and life expectancy statistics.
- Visualize data trends using matplotlib plots.

# Database Configuration
## Update the database paths in the code to reflect the actual paths:

python Copy code

MongoDB URI
MONGO_URI = "mongodb://localhost:27017"

SQLite Database Path
DB_PATH = "C:/path/to/PublicHealthCrimeData.db"

## File Paths
## Replace placeholders with your actual directory paths for CSV storage and other outputs:

python Copy code

Directory to store CSV files
CSV_DIR = "C:/path/to/csv_files"

# Execution
Run the scripts in order, in jupyter noteboke:

- library importationn cell
- Data acquisition script: Downloads data and loads it into MongoDB.
- Transformation script: Converts data from MongoDB to SQLite.
- Preprocessing script: Cleans and structures datasets.
- Analysis and visualization script: Generates insights and plots.



# Results
- Extracted datasets saved in MongoDB and SQLite.
- Cleaned datasets stored as CSV files.
- Visual insights from trends, distributions, and correlations.

# License
This repository is licensed under the MIT License.
