# Google Maps Geocoding API

## I. Introduction
APIs (Aplication Programming interfaces) play a crucial role in modern applications by enabling seamless data exchange between different services. One widely used API is the Google Maps Geocoding API, which allows users to convert addresses into precices geographic coordinates (latitude and longitude) and vise versa.
In this documentation, I will walk through how to retrieve location - based data usimg the Google Maps Geocoding API with **Postman**, a popular API testing tool. We will how to send API requests, interpret JSON responses, and extract useful data for real world applications.

By the end of this documentation, we will have a solid understanding of how to work with geolocation data, which is a valuable skill in fields like **web development, GIS (Geographic Information System).**

## II. Data Retrieval
To retrieve the weather data, I followed these steps:
1. Fetch Weather Data
   - Use OpenWeather API to retriev weather data for a specific city
   - Extract key informationsuch as temperature, humidity, wind speed, and weather conditions.
3. Obtain City Coordinates
   - If only the city name is provided, OpenWeather API automatically returns its coordinates
   - Alternatively, use Google Geocoding API to convert a city name into coordinates
5. Display the Data on Google Maps
   - Utilize Google Maps JavaScript API to display the city map
   - Plot the location based on the coordinates retrievedfrom OpenWeather API
   - Add an info window to display the weather details
7. Enhance UI with Styling and Interactivity
   - Use icons as map markers
   - Implement a dropdown menu to select a city
   - Ensure to responsive interface for seamless usage on both mobile and desktop devices
