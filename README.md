# Traffic-Prediction-System
A comprehensive research-based practice project where a robust model of traffic congestion prediction was constructed using advanced machine learning classification algorithms—Random Forest and Support Vector Regression.

## About Dataset
📌Date:The Date column contains the date on which the data were recorded in the format DD/MM/YYYY. This temporal data allows us to track and analyze traffic patterns over different periods.<br>
📌Day: The Day column specifies the weekday on which the data was collected. This helps in examining how traffic varies across different days of the week, providing insights into weekly traffic trends and peak periods.<br>
📌Coded Day: Each day of the week is assigned a numerical code, simplifying the data analysis and model training processes. The coding is as follows:

Monday: 1
Tuesday: 2
Wednesday: 3
Thursday: 4
Friday: 5
Saturday: 6
Sunday: 7
Using these codes, the model can easily interpret and use the day of the week as a feature, enhancing its ability to predict traffic based on the day.<br>

📌Zone: This column contains the zone number where traffic data is collected. Each zone represents a specific geographic area with distinct traffic patterns. The weather conditions within each zone are encoded based on typical scenarios, including:
Humidity: Higher humidity can affect road conditions and visibility.
Mist: Can reduce visibility and influence driving speed.
Visibility: Directly impacts driving conditions and safety.
Precipitation: Includes rain or snow, which can slow down traffic and increase congestion.
By incorporating these weather-related factors, the model can better predict how different weather conditions affect traffic in each zone.<br>

📌Temperature: This column records the temperature for each zone on a given day. Temperature can significantly impact traffic:
High temperatures might lead to increased vehicle usage as people avoid walking or cycling.
Low temperatures can lead to hazardous road conditions, affecting traffic flow.<br>

📌Traffic:This is the primary target variable for the model. Traffic levels are categorized on a five-level scale:

1: Less than 5 cars
2: 5 to 15 cars
3: 15 to 30 cars
4: 30 to 50 cars
5: More than 50 cars
These categories help the model to understand and predict varying levels of traffic congestion, from very light to very heavy.<br>


## Data Collection and Preprocessing
The dataset was compiled from various sensors and traffic monitoring systems installed across different zones. The raw data underwent several preprocessing steps, including:

1: Data Cleaning: Removing any anomalies or incorrect entries.<br>
2: Normalization: Scaling the data to ensure uniformity.<br>
3: Feature Engineering: Creating new features like day of the week, weather condition codes, and traffic density levels.<br>

## Performance Insights
### 📍Accuracy using Random Forest:<br>
Error = 13.42 %<br>
Accuracy= 86.58 %<br>
### 📍Accuracy using Support Vector Regression:
Error = 12.16 %<br>
Accuracy= 87.84 %<br>

### Reference Used
This project references the exemplary work found in the repository [Traffic Prediction using SVR and RFR](https://github.com/Nupurgopali/Traffic-Prediction-using-SVR-and-RFR) , which served as a significant inspiration and guide for our implementation.
