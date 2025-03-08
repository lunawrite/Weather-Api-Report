# Weather Report Using OpenWeather API

## I. Introduction
Weather data is crucial for various applications, from daily forecasts to advance analytics. In this project, I used **Postman** to send requests to the **OpenWeather API** to retrieve real-time weather data for different locations. The data includes temperature, humadity, wind speed, and general weather conditions, which are formatted in JSON.

This report demonstrates how to fetch and interpret weather data using API requests. Below is an example of weather data for Jakarta.

## II. Data Retrieval Method
To retrieve weather data from OpenWeather API using **Postman**, follow these steps:
1. Open **Postman** and create a new request
2. Set **the request type** to **GET**
3. Enter the following URL in the request field:
   https://api.openweathermap.org/data/2.5/weather?q=Jakarta&appid=YOUR_API_KEY
5. Click **Send** to fetch the weather data
6. The **API** will return a JSON response containing weather details for Jakarta.

## 2.1 Respon Interpretation
When we send the API request, we will receive a JSON response similar to this:
{
  "coord": {
    "lon": 106.8451,
    "lat": -6.2146
  },
  "weather": [
    {
      "id": 802,
      "main": "Clouds",
      "description": "scattered clouds",
      "icon": "03d"
    }
  ],
  "base": "stations",
  "main": {
    "temp": 306.26,
    "feels_like": 312.23,
    "temp_min": 305.11,
    "temp_max": 306.77,
    "pressure": 1005,
    "humidity": 58,
    "sea_level": 1005,
    "grnd_level": 1002
  },
  "visibility": 8000,
  "wind": {
    "speed": 4.12,
    "deg": 210
  },
  "clouds": {
    "all": 40
  },
  "dt": 1741335200,
  "sys": {
    "type": 2,
    "id": 2073276,
    "country": "ID",
    "sunrise": 1741301890,
    "sunset": 1741345771
  },
  "timezone": 25200,
  "id": 1642911,
  "name": "Jakarta",
  "cod": 200
}

**Key Data from OpenWeather API**
This JSON contain the Key data as follows:
- **Location (name):** Jakarta
- **Coordinate (Coord):**
     - Longitude: 106.8451
     - Latitude: -6.2146
- **Weather Condition:**
     - Main: Clouds
     - Weather Description: scattered clouds
- **Temperature (Main Temperature):** 306.26 K (Kelvin to Celcius: 306.26 - 273.15= 33.11°C)
- **Feels Like (main,feels like):** 312.23 K (39.08°C)
- **Humidity (Main Humidity):** 58%
- **Wind Speed & Direction (wind.speed & wind. deg):** ➡️ 4.12 m/s from 210° (South-Southwest)

## III. Data Interpretation
This information helps interpret the raw JSON response into meaningful weather insights. From the data we can see that the weather condition in Jakarta is scattered clouds. We can say that **the temperature is 33.11°C** but **it feels like 39.08°C** due to the humidity and other other reasons. **The humidity level is about 58%**, which means the air is moderately humid but still bearable. With this level of humidity, people might feel a bit sweaty when staying outdoors for too long. 

On the other hand, the wind is blowing at a speed of **4.12 m/s from 210° (South-Southwest)**, indicating a gentle breeze moving towards **the North-Northeast (NNE)** direction. So, the wind is not too strong, making the current weather quite stable.

Also, based on the provided data, the visibility in Jakarta is around **8000 meters (8 km)**. This means that the air clarity is quite good, allowing people to see objects at a considerable distance without much obstruction. However, if pollution levels increase, visibility might decrease.

Meanwhile, the atmospheric pressure is recorded at **1005 hPa**, which is within the normal range. This indicates stable weather conditions, meaning there are no significant signs of storms or extreme weather changes at the moment.

In summary, Jakarta is currently experiencing partly cloudy weather with a warm temperature of **33.11°C**, but it feels hotter at **39.08°C** due to humidity. The gentle breeze from **South-Southwest (SSW) at 4.12 m/s** adds a slight cooling effect, making the weather a bit more comfortable.

## IV. Conclusion
To sum up, Jakarta is currently experiencing warm and partly cloudy weather with a temperature of **33.11°C**, though it feels hotter at **39.08°C** due to humidity. The air is moderately humid at 58%, which can make outdoor activities a bit uncomfortable, especially during the day.

The wind conditions remain stable, blowing gently from **South-Southwest (SSW) at 4.12 m/s**, while visibility is quite good at 8 km, ensuring clear sight across the city. Additionally, the atmospheric pressure of **1005 hPa** suggests no major weather disturbances in the near future.

Overall, the weather in Jakarta is fairly stable, with no extreme conditions at the moment. However, due to the high humidity and warm temperatures, staying hydrated and avoiding prolonged outdoor exposure is recommended, especially during peak daylight hours.



