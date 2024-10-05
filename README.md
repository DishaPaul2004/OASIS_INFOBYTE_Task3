## OASIS INFOBYTE TASK 3

# BASIC WEATHER APP

## Overview of the project

For my 3rd task in my internship in Python Programming at Oasis Infobyte, I chose to develop a basic weather app.

## Objectives of the project  

- Create a basic command-line weather app.
- It will fetch current weather data depending on the city entered by the user using a weather API.
- It will show basic information like temperature, humidity and other weather conditions.

## Implementation of the project

The implementation of this project consisted of the following steps : 
- First, I imported the module requests which is required for this task.
- Next, I took the name of the city as input from the user.
- I defined the URL string with formatting present for including the city name and API key in the final URL.
- Using the requests.get method, I fetched the current weather details.
- Using the .json method, this data was transmitted in the proper format.
- I obtained the values for actual temperature, feels like temperature, pressure, humidity and a basic description of the weather, and then displayed them.

![Screenshot (95)](https://github.com/user-attachments/assets/f770aa3c-8a18-4293-88d8-42997bc95888)
