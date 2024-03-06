# React Native Map App
<img src="https://th.bing.com/th/id/OIP.BgBqJdBnRlp1o9p0ayCD7gAAAA?rs=1&pid=ImgDetMain" alt="Girl in a jacket" >
This React Native application utilizes maps to trace routes between two locations, powered by Google Maps API. It includes an autocomplete feature for place selection and displays route information such as distance and duration.

## Table of Contents
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Usage](#usage)
- [Documentation References](#documentation-references)
  
Features
Autocomplete Input: Utilizes the Google Places Autocomplete API to provide a seamless experience for users when entering origin and destination locations.

Route Tracing: Allows users to trace routes between selected places on the map.

Distance and Duration: Displays the distance and estimated duration of the traced route.

Modal for Additional Options: A modal interface allows users to enter additional details or options before initiating route tracing.

Google Maps Image: The app includes a Google Maps image in the header for a visually appealing design.

## Getting Started

To run this application locally, follow the steps below:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/react-native-map-app.git
   cd react-native-map-app


Install dependencies:


npm install
Configure the Google Maps API key in environment.js. Replace 'YOUR_GOOGLE_MAPS_API_KEY' with your actual API key.

Start the application:


npm start
Open the application on an Android or iOS emulator or a physical device using the Expo Go app.

Dependencies
This application relies on the following key dependencies:

react-native-maps: Provides map components for React Native.
react-native-google-places-autocomplete: Implements an autocomplete input for Google Places API.
react-native-maps-directions: Renders directions between two locations on the map.
Configuration
Make sure to configure the Google Maps API key in environment.js. You can obtain an API key by following the instructions in the Google Cloud Console.

Usage
The app opens with a map and a semi-transparent search container overlaying it.
Enter the origin and destination places using the autocomplete inputs.
Press the "Trace route" button to initiate route tracing.
Confirm the destination in the modal and view the traced route on the map.
Documentation References
- [react-native-maps Documentation](https://docs.expo.dev/versions/latest/sdk/map-view/)
- [react-native-google-places-autocomplete on npm](https://www.npmjs.com/package/react-native-google-places-autocomplete)
- [react-native-maps-directions on npm](https://www.npmjs.com/package/react-native-maps-directions)




This README provides a comprehensive guide for setting up, configuring, and using the React Native Map App. It also includes references to the documentation for the key dependencies used in the project.



