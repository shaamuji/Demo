# My Application - Location & Google Maps Demo

An Android application demonstrating Google Maps integration, Google Places search, and interactive location selection.

## Features

- **Customized Google Maps**: Interactive map view with custom styling and markers.
- **Google Places Integration**: Searchable location places that reposition the map camera upon selection.
- **Location Pick & Confirm**: Reposition and lock in selected map locations with visual confirmation.

## Tech Stack & Configuration

- **Language**: Java / Android SDK
- **Build System**: Gradle 8.5 with Android Gradle Plugin (AGP) 8.2.2
- **Compile SDK**: 34
- **Min SDK**: 23
- **Target SDK**: 34
- **Java Toolchain**: Java 17

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the project in **Android Studio**.
3. Set your Google Maps API key in `app/src/main/res/values/strings.xml`:
   ```xml
   <string name="google_maps_key">YOUR_API_KEY</string>
   ```
4. Sync Gradle and run the application on an emulator or connected device.
