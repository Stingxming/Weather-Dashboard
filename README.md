<!-- create search bar in HTML (input box) -->

<!-- create button for input box -->

<!-- grab value of user input -->

<!-- create function to get lat/lon of location searched (fetch coordinates) -->

<!-- https://openweathermap.org/api/geocoding-api (find a way to insert user input into API call URL)  -->

<!-- assign user input a variable, assign API call URL a variable, concatinate user input with API call URL -->

<!-- "http://api.openweathermap.org/geo/1.0/direct?q=" + CityName + "&appid="+ API key -->

<!-- create function that calls for weather data using the lat/lon -->

<!-- EXAMPLE: response.current.temp -->

# Matty C's Weather Dashboard

Deployed Url: https://stingxming.github.io/Weather-Dashboard/

Github repo: https://github.com/Stingxming/Weather-Dashboard

## User Story

```
AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly
```

## Acceptance Criteria

```
GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, and the wind speed
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city
```
