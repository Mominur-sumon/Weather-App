# FlutterWeather
### Updated to Flutter 3.0 & New Updated Design

A simple weather App created using [Flutter](https://flutter.dev/) and [Dart](https://dart.dev/) and using API from [OpenWeatherMap](https://openweathermap.org/)</br></br>

<p align="center">
<img src="https://github.com/Mominur-sumon/Weather-App/blob/main/Weather%20App%201.png" width="20%"></img> 
<img src="https://github.com/Mominur-sumon/Weather-App/blob/main/Weather%20App%206.png" width="20%"></img> 
<img src="https://github.com/Mominur-sumon/Weather-App/blob/main/Weather%20App%207.png" width="20%"></img> 
<img src="https://github.com/Mominur-sumon/Weather-App/blob/main/Weather%20app%202.png" width="20%"></img>
<img src="https://github.com/Mominur-sumon/Weather-App/blob/main/Weather%20App%203.png" width="20%"></img>
<img src="https://github.com/Mominur-sumon/Weather-App/blob/main/Weather%20App%205.png" width="20%"></img>
</p>

## API Docs   
> [!IMPORTANT] 
> This project uses **_version 2.5_** of the OpenWeatherMap API</br>
> **API used in this project**:</br>
> - [Current Weather API Docs](https://openweathermap.org/current#one)</br>
> - [One Call API Docs](https://openweathermap.org/api/one-call-api#data)</br>
> - [Geocoding API Docs](https://openweathermap.org/api/geocoding-api)</br>


## Features      
- Automatically acquire user current location
- Searchable location
- Hourly weather information
- 7 days weather information          


## How to Run
1. Create an account at [OpenWeatherMap](https://openweathermap.org/).
2. Then get your API key from https://home.openweathermap.org/api_keys.
   >Sometimes after getting your OpenWeatherMap API key it won't work right away </br>
   >To test if your API key is working or not copy and paste the following link to your browser</br>
   >https://api.openweathermap.org/data/2.5/weather?lat=53.4794892&lon=-2.2451148&units=metric&appid=YOUR_API_KEY</br>
   >Then replace `YOUR_API_KEY` with your own API key from OpenWeatherMap
3. Clone the repo
   ```sh
   git clone https://github.com/Mominur-sumon/Weather-App.git
   ```
4. Install all the packages by typing
   ```sh
   flutter pub get
   ```
5. Navigate to **lib/provider/weatherProvider.dart** and paste your API key to the apiKey variable
   ```dart
   String apiKey = 'Paste Your API Key Here';
   ```
6. Run the App

## Contact
- [Md. Mominur Rahman](https://github.com/Mominur-sumon/) 


