
# Flutter Weather <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="android" width="22" height="22"/> 

 <img alt="Awesome Flutter" src="https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square" />
A Flutter application to view current weather status.

- ## Download The App From [Here](https://bit.ly/2JJZdAV)



![android](./screenshots/android.png?raw=true 'android')
![ios](./screenshots/ios.gif?raw=true 'ios')
![ios](./screenshots/ios_chart.gif?raw=true 'ios')

## Features
- :white_check_mark: Beautiful minimal UI
- :white_check_mark: Dark and Light themes
- :white_check_mark: Current temperature, max and min temperature, sunset, sunrise
- :white_check_mark: Custom icons for each weather condition
- :white_check_mark: 5 day forecast
- :white_check_mark: Beautifully animated transitions
- :white_check_mark: BLoC pattern for API calls
- :white_check_mark: Line graph to show temperature variance

## Getting Started

### Prerequisites
**Flutter**


### Installing

**API Key**

Create a file called `api_keys.dart` in `lib/src/api/`

Make a class called `ApiKey` with your openweathermaps API key in it. Get it [here](https://openweathermap.org/api)

eg:
  ```
  class ApiKey {
    static const OPEN_WEATHER_MAP = 'your_key';
  }
  ```




## Acknowledgments

* [Weather Icon Pack](https://erikflowers.github.io/weather-icons/)
