# README.md

# Weather Data ETL and Analysis Project

## Project Overview

This project focuses on extracting real-time weather data for selected Nigerian cities using the OpenWeather API, transforming the data into a clean and structured format, and loading it into CSV and Excel files for further analysis.

The objective of the project is to demonstrate an end-to-end ETL (Extract, Transform, Load) workflow using Python in Jupyter Notebook while generating useful weather insights such as temperature trends, humidity levels, and wind speed variations across different cities.

---

## Data Source

The data was sourced from the OpenWeather API, which provides real-time weather information for locations around the world.

### Cities Included

* Lagos
* Abeokuta
* Osun
* Ilorin
* Abuja
* Abia
* Edo
* Port Harcourt
* Mowe

### Data Fields

* Cities
* Country
* Weather Condition
* Temperature (°C)
* Humidity (%)
* Wind Speed (m/s)
* Timestamp

---

## ETL Process

### 1. Extract

Weather data was extracted from the OpenWeather API using HTTP requests. Data for multiple Nigerian cities was collected and stored in a structured format.

### 2. Transform

The extracted data was cleaned and prepared for analysis by:

* Creating a Pandas DataFrame
* Checking data types
* Handling missing values
* Identifying and removing duplicates
* Renaming columns for consistency
* Formatting timestamp information
* Structuring data into tabular format

### 3. Load

The transformed dataset was exported into:

* CSV format (weather_data.csv)
* Excel format (weather_data.xlsx)

These files can be used for reporting, dashboard creation, and further analysis.

---

## Tools Used

### Development Environment

* Jupyter Notebook

### Python Libraries

* Pandas
* NumPy
* Requests
* OpenPyXL
* PyCountry
* Datetime
* SQLite3

---

## Steps Taken

### Step 1: Import Required Libraries

Imported Python libraries necessary for data extraction, transformation, and storage.

### Step 2: Connect to OpenWeather API

Configured API credentials and defined the list of target cities.

### Step 3: Extract Weather Data

Retrieved weather information for each city through API requests.

### Step 4: Create DataFrame

Converted the extracted JSON responses into a structured Pandas DataFrame.

### Step 5: Data Cleaning

* Checked for missing values
* Verified data types
* Removed duplicate records
* Renamed columns where necessary

### Step 6: Save Dataset

Exported the cleaned dataset into CSV and Excel formats.

### Step 7: Perform Analysis

Analyzed weather conditions, temperature distribution, humidity levels, and wind speeds across the selected cities.

---

## Key Findings

### Temperature Analysis

* Temperature varied across the selected cities, reflecting differences in weather conditions and geographical locations.
* Some cities experienced warmer conditions compared to others during the data collection period.

### Humidity Analysis

* Humidity levels were generally high across most cities, indicating moist atmospheric conditions.
* Coastal cities showed relatively higher humidity levels.

### Weather Conditions

* The most common weather conditions observed were:

  * Light Rain
  * Moderate Rain
  * Overcast Clouds

### Wind Speed Analysis

* Wind speeds varied among cities, with some locations experiencing stronger winds than others.
* Wind conditions can influence temperature perception and weather patterns.

### Overall Insight

* The weather data indicates predominantly rainy and humid conditions across the selected Nigerian cities during the period of data collection.
* Such insights can support weather monitoring, environmental analysis, and decision-making processes.

---

## Author

Bakare Joshua 
Data Analyst | Python | SQL | Excel | Power BI

---

### Project Outcome

Successfully built an ETL pipeline that extracts weather data from an external API, transforms it into a clean analytical dataset, and loads it into accessible file formats for reporting and analysis.
