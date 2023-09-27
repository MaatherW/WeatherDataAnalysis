# Weather Data Analysis

This project analyzes daily weather temperature. This dataset contains the daily weather data recorded in the capital location (based on lat, long values) of 194 countries in the world.

The shared Noteable work book link can be accessed [here](https://app.noteable.io/f/b7b624e7-1593-4df3-b4c9-3a7cd1909c28).

### Data Loading And Overview

-   Identifying Missing Values and Data Cleaning
-   Converting Data Types
-   Check For Duplicated Rows

---
![Map based on location broken down by Year.  Color shows changes in AVG temperatures.  Details are shown for Country. The view is filtered on Country, which keeps 185 of 194 countries due to lack of data in certain years.](https://i.imgur.com/qyKcQvr.png)

### Exploratory Data Analysis (EDA)

-   Descriptive Statistics
-   Distribution Visualization
-   Potential Outliers

### Data Visualization - [Tableau](https://public.tableau.com/views/DailyWeatherData/HighestTemperaturesbyCountry?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

-   Forecasting - Prophet (python)
-   Highest Temperatures/Country graph
-   AVG Temperature Timelapse/Country Map
-   AVG Temperature Increase and Decrease graph
-   AVG Temperatures Increase/Decrease Map

### Insights and Conclusions

-   **Highest Temperatures/Country graph**: highest temperature recorded 76°C in Cape Verde, west Africa.

-   **AVG Temperature Timelapse/Country Map**: The south area shows missing countries/data in certain years. These countries are removed in visualizations related to changes in average temperatures (increase/decrease).

-   **AVG Temperature Increase and Decrease graph**: The graph shows the frequency of temperature increases is higher than the frequency of decreases.

-   **AVG Temperatures Increase/Decrease Map**: Looking at this map one can witness the rise of temperatures in Europe and north Asia in the last five years.

-   **Forecasting**: python’s version (prophet) shows no critical changes in the following year (365 days), while Tableau’s version shows a rise in the average daily temperature over the next four years.
