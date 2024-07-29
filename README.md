# Minimal Weather App

A minimalistic weather application built with Flutter. This project demonstrates how to fetch and display weather data based on the current GPS location using the OpenWeatherMap API.

## Features

- Fetches weather data using the OpenWeatherMap API.
- Displays weather information such as city name, temperature, and main condition.
- Automatically retrieves and uses the current GPS location to get weather data.

## Dependencies

This project uses the following dependencies:

- [cupertino_icons: ^1.0.6](https://pub.dev/packages/cupertino_icons)
- [http: ^1.2.2](https://pub.dev/packages/http)
- [geolocator: ^11.1.0](https://pub.dev/packages/geolocator)
- [geocoding: ^3.0.0](https://pub.dev/packages/geocoding)
- [lottie: ^3.1.2](https://pub.dev/packages/lottie)

## Getting Started

### Prerequisites

- Flutter installed on your machine. Follow the official guide [here](https://docs.flutter.dev/get-started/install) to set up Flutter.

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/muhith7/vexana.git
   cd vexana
2. **Install dependencies:**
   ```sh
   flutter pub get
   ```
3. **Run the app:**
   ```sh
   flutter run
   ```

## Usage
1. Obtain an API Key: Sign up for an API key from OpenWeatherMap.

2. Update API Key: Replace `your_api_key_here` in the `WeatherService` class with your actual API key:
```sh
final String apiKey = 'your_api_key_here';
```

3. Run the Application: Use your preferred IDE or terminal to run the application.


## Project Structure
- `main.dart`: Entry point of the application.
- `models/weather_model.dart`: Defines the Weather model class.
- `services/weather_service.dart`: Contains the WeatherService class for fetching weather data from the API.
- `pages/weather_page.dart`: UI for displaying the weather information.


## Resources
A few resources to help you get started with Flutter:

- [Lab: Write your first Flutter app]((https://docs.flutter.dev/get-started/codelab))
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
- [Flutter Online Documentation:](https://docs.flutter.dev/) Offers tutorials, samples, guidance on mobile development, and a full API reference.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.
## Author
This code was created by `Abdul Muhith Nawawi`.

Happy coding!
```sh
This `README.md` file provides a comprehensive overview of the project, including setup instructions and other important details. You can copy and paste this directly into your `README.md` file.
```



   
