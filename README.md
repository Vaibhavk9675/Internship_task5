# Air Quality Index (AQI) Data Analysis

This project performs a detailed analysis of Air Quality Index (AQI) data for Delhi year 2021. The analysis includes visualizing monthly and seasonal AQI trends, pollutant contributions, and identifying the best and worst air quality days.

---

## Dataset

- The dataset is expected to be a CSV file named `final_dataset.csv`.
- It contain daily AQI values along with pollutant concentrations and date information.
- Key columns include:
  - `Year`, `Month`, `Date` — date components
  - `AQI` — daily Air Quality Index value
  - Pollutants: `PM2.5`, `PM10`, `NO2`, `SO2`, `CO`, `Ozone`

---

## Analysis and Visualizations

1. **Average Monthly AQI (Bar Chart)**  
   Shows the average AQI for each month from January to December.

2. **January AQI (Date-wise Bar Chart)**  
   Displays daily AQI values for the month of January to observe daily fluctuations.

3. **Average AQI by Season (Bar Chart)**  
   Compares average AQI across four seasons — Winter, Spring, Summer, Autumn — to identify seasonal air quality patterns.

4. **Pollutant Share (Pie Chart)**  
   Illustrates the percentage contribution of each pollutant (`PM2.5`, `PM10`, `NO2`, `SO2`, `CO`, `Ozone`) to the overall air quality on average.

5. **Top 10 Lowest AQI Days (Bar Chart)**  
   Shows the 10 days with the best air quality, helping to identify periods of cleaner air.

6. **Top 10 Highest AQI Days (Line Chart)**  
   Highlights the 10 days with the worst air quality in chronological order, useful for identifying pollution spikes.

---

## How to Run

1. Ensure you have Python 3 installed.
2. Install required libraries (if not already installed):

   ```bash
   pip install pandas matplotlib


