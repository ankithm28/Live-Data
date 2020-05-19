

Uses MIT - [COVID-19 Safe Paths](http://safepaths.mit.edu/)


RouteSafe is a mobile app that allows people people to see how populated public spaces are in order to safely meet basic needs that require travel.

### iOS Configuration - First Time Setup

1. Cd into the `ios` directory and run `pod install`
2. If some packages are giving you trouble please run `react-native link` from the project directory.

### MapBox API Key
You need a mapbox key in order for the mapping features to work correctly. Visit mapbox [mapbox](https://www.mapbox.com/) to create an api key.

Once you have the API key, you will need to create a .env file that looks like the following:
```
MAPBOX_ACCESS_TOKEN={ACCESS_TOKEN_HERE}
```

## Running

Install modules:
```npm install``` or ```yarn install```

To run:
```
npx react-native run-android
```
or
```
npx react-native run-ios
```


