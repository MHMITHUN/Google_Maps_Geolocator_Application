# Google Maps Geolocator Application With Flutter


# Flutter Google Maps GeoLocator

## Overview
This Flutter application integrates Google Maps and the Geolocator plugin to track and display the user's real-time location on a map. It also draws a polyline following the user's path as they move.

## Features
- Real-time location updates.
- Display of current location with a custom marker.
- Polyline drawing showing the path traveled.
- Dynamic location updates with high accuracy.
- Floating action button to re-center the map on the user's current location.

## Getting Started

### Prerequisites
- Flutter installed (latest stable channel recommended).
- Android Studio or Visual Studio Code with Flutter plugin.
- Google Maps API key.

### Setup
1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourgithub/flutter-google-maps-geolocator.git

2. **Install dependencies:**
cd flutter-google-maps-geolocator flutter pub get

3. **Add Google Maps API key:**
- Navigate to `android/app/src/main/AndroidManifest.xml`.
- Replace `YOUR_API_KEY` with your actual Google Maps API key in the meta-data tag.

### Running the Application
Execute the following command in your terminal:
flutter run


## Usage
- On startup, the app requests location permissions.
- Once granted, it will automatically focus on the user's current location.
- The map updates in real-time as the user moves.
- The floating action button allows the user to manually focus the map on their current location.

## Screenshots
> (I Will Add screenshots of the application here Later)

## Contributing
Feel free to fork this repo, make changes, and submit pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Flutter Team for comprehensive documentation.
- Google for the Maps API.
- Geolocator package developers.
