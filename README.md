# Google Maps Geolocator Application With Flutter


This project demonstrates the integration of Google Maps and the Geolocator plugin in a Flutter application. It provides real-time location updates and displays the user's current location on the map. Users can also view their location path as a polyline on the map.

## Features

- Real-time location tracking.
- Displaying current location with a custom marker on Google Maps.
- Drawing a polyline on Google Maps based on the user's movement.
- Dynamically updating location information with minimal latency.
- Custom floating action button to re-center the map on the current location.

## Getting Started

To get started with this project, clone this repository and ensure you have Flutter installed on your machine.

### Prerequisites

- Flutter (Channel stable, latest version)
- Android Studio or VS Code with Flutter plugins
- An active Google Maps API key

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourgithub/flutter-google-maps-geolocator.git
Navigate to the project directory:

bash
Copy code
cd flutter-google-maps-geolocator
Install dependencies:

bash
Copy code
flutter pub get
Add your Google Maps API key:

Open android/app/src/main/AndroidManifest.xml.

Replace YOUR_API_KEY with your Google Maps API key in the following line:

xml
Copy code
<meta-data
  android:name="com.google.android.geo.API_KEY"
  android:value="YOUR_API_KEY"/>
Running the app
With the dependencies installed and the API key set, you can now run the app on your device or an emulator.

bash
Copy code
flutter run
Usage
The app will request location permissions on startup.
Once permissions are granted, the map will center on the user's current location.
The user's path will be drawn as they move, and the location marker will update in real-time.
Use the floating action button to re-center the map on your current location if you move the map manually.
Screenshots
I will Include a few screenshots of the app here Later.

Contributing
Contributions are welcome! Please feel free to fork this repository, make changes, and open pull requests.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Acknowledgments
Flutter documentation
Google Maps API
Geolocator package team
