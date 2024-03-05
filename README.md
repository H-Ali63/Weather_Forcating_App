## Weather Forecasting App

**Overview**

The Weather Forecasting App is a simple yet powerful application that provides real-time weather information for a given location. It allows users to enter a city name and retrieve the current weather conditions, including temperature, timezone, and local time.

**Features**
1. Weather Information: Get detailed weather data, including temperature, timezone, and local time.
2. User-Friendly Interface: Easy-to-use interface for entering the city name and viewing weather details.
3. Real-Time Updates: The app fetches real-time weather data from the OpenWeatherMap API.

**Getting Started**

**Prerequisites**

Python 3.x
Tkinter (usually included in standard Python installations)
Additional Python libraries: **geopy**, **timezonefinder**, **pytz, requests**


**Installation**

1. Clone the repository:
   git clone https://github.com/yourusername/weather-forecast-app.git

2. Install dependencies:
pip install -r requirements.txt

**Uses**

1. Run the app:
   python weather_app.py

2. Enter the desired city name in the provided text field.

3. Click the "Get Weather" button to retrieve and display the weather information.

**Screenshots**

![image](https://github.com/H-Ali63/Weather_Forcating_App/assets/151657596/b70829d6-5e35-4e6c-886a-b4419d9c8737)


## Known Issues

1. **Incomplete Error Handling:** The current version of the app lacks comprehensive error handling. For instance, if the user enters an invalid city name or if there's a network issue during the API request, the app may not provide clear feedback to the user. Future updates will address this issue and provide more informative error messages.

2. **UI Responsiveness:** The app's user interface may not be fully responsive on smaller screens or certain devices. This issue can lead to layout problems and impact the overall user experience. We are actively working on improving the app's responsiveness in upcoming releases.

3. **Limited Forecast Data:** Currently, the app only displays the current weather information. Future enhancements will include extended forecasts, hourly forecasts, and additional weather details to provide a more comprehensive overview.

4. **Dependency Version Compatibility:** The app relies on specific versions of external libraries. In some cases, using different versions might lead to unexpected behavior. We recommend checking the `requirements.txt` file for the compatible library versions.

5. **No Unit Testing:** The current version lacks a comprehensive suite of unit tests. This makes it challenging to ensure the app's functionality in various scenarios. Future updates will include the implementation of unit tests for improved reliability.

Please check the [Issues](https://github.com/yourusername/weather-forecast-app/issues) section for any recent updates or additional known issues. Feel free to contribute by reporting issues or submitting pull requests.


License:
This project is licensed under the MIT License.

Acknowledgments:
Thanks to OpenWeatherMap for providing the weather data API.
