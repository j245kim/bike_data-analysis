# Seoul Bicycle Rental Dataset Analysis (2-Year Data)

This dataset contains information about bicycle rentals in Seoul over a 2-year period. The data includes hourly rentals and various environmental and temporal features that can be used for analysis. Below are the details of each column in the dataset:

## Columns Description

- **datetime**: Hourly timestamp indicating the date and time of the bicycle rental.
- **season**: The season during which the rental occurred.
  - `1` = Spring
  - `2` = Summer
  - `3` = Autumn
  - `4` = Winter
- **holiday**: Whether the day is a holiday or not.
  - `1` = Holiday (includes national holidays, excluding weekends)
  - `0` = Non-holiday (regular days)
- **workingday**: Indicates if the day is a working day (weekday and not a holiday).
  - `1` = Working day (weekdays that are not holidays)
  - `0` = Non-working day (weekends or holidays)
- **weather**: Describes the weather conditions during the rental.
  - `1` = Clear, slightly cloudy
  - `2` = Mist, fog, or light cloud cover
  - `3` = Light snow, light rain, or thunder
  - `4` = Heavy snow, heavy rain, or thunder
- **temp**: Temperature in Celsius.
- **atemp**: "Feels like" or perceived temperature in Celsius.
- **humidity**: Relative humidity percentage.
- **windspeed**: Wind speed (km/h).
- **casual**: Number of bicycle rentals by casual users (those not registered).
- **registered**: Number of bicycle rentals by registered users (those with an account).
- **count**: Total number of bicycle rentals (sum of casual and registered users).

---

## Analysis

You can use this dataset to analyze trends in bicycle rentals based on seasonal factors, weather conditions, and whether the day is a holiday or working day. It provides valuable insights into how external factors influence bike-sharing usage in Seoul.

---

## Requirements

- Python 3.12.4
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Usage

Clone this repository and use the provided Jupyter Notebooks or Python scripts to analyze the dataset and create visualizations.
