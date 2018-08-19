# Neighborhood Map Project using ReactJS

# Sofia is Hungry


## Overview

The project was build with HTML, CSS, JavaScript, React and API usage.
This app uses the Google Maps API and Foursquare API to display a list of restaurants in my hometown - Sofia, Bulgaria, plus their associated map markers. Clicking on list item or a marker opens up an info window on the map with information about the venue collected from Foursquare.


## Using the app

1. Download the zip folder.

### Development Mode

2. Install all project dependencies with `npm install`

3. Start the server with `npm start`

### Production Mode

2. To create a production build use `npm run build`

3. Navigate to the build directory and start the server with `npm run deploy`

4. This mode includes a Service Worker.

## Functionality

The neighbourhood map application opens. The user can choose from any of the restaurants displayed on the list on the left or click directly on any of the markers on the map. Upon picking a restaurant from the list, the corresponding marker bounces showing the user the location of the chosen venue. A small window opens up displaying restaurant information from Foursquare. Users can filter the list of locations based on location name. The filtering of the locations starts immediately on user type. Both the venues list and their corresponding markers will be filtered according to the search criteria.


## References

[Google Maps API](https://developers.google.com/maps/documentation/javascript/tutorial)

[Foursquare API](https://developer.foursquare.com/docs/api)

[Create-react-app](https://github.com/facebook/create-react-app)

[React-async-script-loader](https://www.npmjs.com/package/react-async-script-loader)