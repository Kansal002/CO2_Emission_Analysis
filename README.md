# CO2-Emissions-Analysis-and-Prediction
In this Project I analyzed and forecasted CO2 emissions of every country for the next 10 years using data of last 40 years. I got the data from [here](https://www.iea.org/data-and-statistics/data-tools/greenhouse-gas-emissions-from-energy-data-explorer). After some initial excel processing data looked like [dataset.xlsx](dataset.xlsx).

---

Tested diffrent machine learning algorithms here in [model_testing.ipynb](model_testing.ipynb) using data from India and best performing model came out to be Arima model using which then forecasted diffrent country data using the same idea and looping through all countries ([getting_forecasted_data.ipynb](getting_forecasted_data.ipynb)) and stored in [Forecasted_CO2.csv](Forecasted_CO2.csv).

---

![](video_representation_of_visualization.gif)
