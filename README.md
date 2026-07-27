# Gans Project — developed during Data Science studies at WBS CODING SCHOOL

## Project overview

Gans is an e-scooter-sharing company. This project builds an ETL pipeline that collects external data which could help Gans anticipate scooter demand and improve fleet positioning.

## ETL process

* Extract: Collect city and population data from Wikipedia, weather forecasts from OpenWeather, and flight arrivals from AeroDataBox.
* Transform: Clean and organize the data using Python and pandas.
* Load: Store the processed data in a MySQL relational database.

## Data sources

* Wikipedia — city information and population
* OpenWeather API — five-day weather forecasts
* AeroDataBox API — flight-arrival information

## Database tables

* `cities`
* `populations`
* `weather`
* `airports`
* `flights`

The tables are connected using city identifiers to support efficient querying and analysis.

## Technologies used

* Python
* pandas
* Beautiful Soup
* Requests
* SQLAlchemy
* PyMySQL
* MySQL
* Jupyter Notebook
* REST APIs

## Repository files

* `gans_project_GITHUB.ipynb` — complete ETL notebook
* `gans_schema.sql` — MySQL database structure
* `cities.csv` — city data
* `populations.csv` — population data
* `database_diagram_gans.png` — database diagram

## How to run the project

1. Download or clone this repository.
2. Import `gans_schema.sql` into MySQL.
3. Open `gans_project_GITHUB.ipynb` in Jupyter.
4. Install the required Python libraries.
5. Enter your own MySQL password and API keys when prompted.
6. Run the notebook cells in order.

API keys and passwords are intentionally not included in this repository.

## Skills demonstrated

* Web scraping
* Working with APIs and JSON
* Data cleaning and transformation
* pandas DataFrame operations
* Relational database design
* Python-to-MySQL integration
* ETL pipeline development

