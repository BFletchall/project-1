# project-1

Project Goal
The goal of project 1 was to isolate projects from an active HME, Inc. data set that are currently experiencing inclement weather. Inclement weather conditions include rain, snow, extreme low temperatures below 20 deg, cold (below 32 deg) but good weather and/or high wind. 

Data Sources
-	OpenWeatherMap API guide - OpenWeatherMap
-	HME Appservices project data provided in csv format.

Analysis Outline

Questions to answer
-	Is the wind speed over 15mph at project locations? On a map, if the wind speed is over 15mph then color = yellow, else green. Is there a correlation between Latitude and wind speed?
-	Is it raining or snowing at the project locations? On a map, if it is raining or snowing then color = red, else green. If extreme low temperature below 32, then color blue. If cold (below 32 deg) but good weather, then color blue.  Is there a correlation between latitude and temperature?
-	What is the total number of projects with rain and/or winds over 15mph?
-	What is the total number of projects with predicted rain and/or winds over 15mph in the next 5 days?

Conclusions
Current weather condition totals (1/4/2024, 8:57pm)
-	148 projects reported cold but good weather.
-	49 projects reported good weather.
-	23 projects reported snow.
-	4 projects reported high wind.
-	1 project reported both wind and rain.
There is a moderate negative correlation between latitude and wind speed. There is a strong correlation between latitude and temperature.
185 of the 234 projects are experiencing rain, snow, high wind, or extreme cold temperatures.
2648 of the 5850 instances are forecasting rain, snow, high wind, or extreme cold temperatures.
Final conclusion: Project location in regards to latitude can have a negative impact on the ability to perform work and cause weather related project delays.

Contributions
-	Jon collected and parced the data from HME, Inc and open weather. Two csv’s were created for analysis, projects weather and weather 5 day forecast.
-	Bobbi created all the visualizations in the weather analysis notebook and the slide deck.
-	Adams performed the analysis.
