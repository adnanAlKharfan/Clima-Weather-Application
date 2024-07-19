# Clima
This repository contains the source code for Clima, a weather application built using Swift. The app fetches real-time weather data for the user's current location or for a manually searched city using APIs.

## Introduction

Clima is an iOS application designed to provide real-time weather updates. The app supports both GPS-based location detection and manual city searches. It features a clean, dark-mode enabled interface and leverages several advanced Swift programming concepts.

## Features

- Real-time Weather Data: Fetches current weather data for the user's location or a manually entered city.
  
- Dark-mode Enabled: Supports dark-mode for a better user experience.
  
- GPS Integration: Uses Core Location to get the user's current location.
  
- Search Functionality: Allows users to search for weather updates by city name.
  
- Clean UI: Provides a simple and intuitive user interface.
  
## Requirements

- iOS 13.0+
  
- Xcode 11+
  
- A valid API key for the weather service
  
## Installation

To set up the project on your local machine, follow these steps:

1. Clone the repository:

```sh
git clone https://github.com/adnanAlKharfan/Clima-Weather-Application.git
```

2. Navigate to the project directory:

```sh
cd Clima-Weather-Application
```

3. Open the project in Xcode:

```sh
open Clima.xcodeproj
```

4. Install dependencies using CocoaPods:

```sh
pod install
```

5. Configure API Key:

Replace the placeholder API key in the relevant file with your own API key.

## Usage

1. Launch the app in Xcode:

- Select the target device (e.g., iPhone simulator or connected device).
  
- Click on the run button or press Cmd + R to build and run the app.

2. Fetch Weather Data:

- Allow the app to access your location to get current weather updates.
  
- Use the search functionality to get weather updates for a specific city.

## Contributing

- Contributions are welcome! Feel free to open issues or submit pull requests.
