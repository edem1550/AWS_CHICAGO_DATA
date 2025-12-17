# Chicago Taxi Data – An Automated Process Flow

## Short Description
This project loads Chicago taxi trip data using an automated data processing and visualization pipeline.  
The goal is to get a cleaned large database in order to explore mobility patterns, revenue distribution, temporal trends, and external factors (such as weather) that may influence taxi usage.  
The workflow covers data ingestion, cleaning, transformation, analysis, and visualization in a reproducible manner.

---

## Used Datasources
- **Chicago Taxi Trips Dataset**  
  Public dataset containing detailed information about taxi trips in Chicago, including trip timestamps, distance, fare, payment type, and service provider.
- **Weather Data**  
  Historical temperature data joined to taxi trips to analyze potential correlations between weather conditions and travel behavior.
- **Chicago Community Areas**
  Scraped data to connect available IDs in taxi dataset with their names.

---

## Used Technologies
- **Python** – Core programming language for data processing and analysis  
- **Pandas** – Data cleaning, transformation, and aggregation  
- **NumPy** – Numerical operations and array-based computations  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-learn** – Statistical analysis and linear regression modeling  
- **BeautifulSoup** – Web scraping and HTML parsing  
- **Requests** – HTTP requests for data retrieval from web APIs and sources  
- **Datetime** – Handling and manipulating date and time values  
- **Dateutil** – Advanced datetime parsing and timezone handling  
- **Typing** – Type hints for improved code readability and maintainability  
- **SQL** – Data extraction and preprocessing (if applicable)  
- **VS Code** – Development environment  
- **Git / GitHub** – Version control and documentation

---

## Process Flow

See below graph


---

## Graphs

1. AVG trip_miles per day

![Average trip miles per day](Pictures/AVG_trip_miles_per_day.png)

2. AVG fare per hour (bar chart)

![Average fare per hour](Pictures/AVG_fare_per_hour.png)

3. Share of company revenues in the examined period (donut chart)

![Share of company revenues](Pictures/Revenue_share_by_Company.png)

4. Number of taxi trips by payment type (pie chart)

![Number of taxi trips by payment type](Pictures/Number_of_taxi_trips_by_payment_type.png)

5. Correlation between temperature and trip mile data (scatterplot)

![Correlation between tips and trip miles ](Pictures/Corr_between_tips_and_trips.png)
