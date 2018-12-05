# Neighborhood Map Project
This project was developed through the Udacity - Front-End Web Developer Nanodegree Program.

Built with: HTML, CSS, JavaScript, React and API usage.

## Project description:

- A single page application featuring a neighborhood map and a listing of Beaches in Niterói, Brazil.
- The Google Maps API is used to generate the map. The Foursquare API is used to get information to display when a marker is clicked. Information such as photos, address, rating, likes and tips are displayed.
- A filter feature and animations makes it easy to navigate between the Markers.
- This application follow this [Udacity Project Rubric](https://review.udacity.com/#!/rubrics/1351/view)

I split my App in small parts or in React as we call  **Components**. 

Put a Nav with an input search to filter locations in a unique component called **NavSearch** and I putted the **Map** component and the **List** component of my favorite locations on a **MapContainer** component.

Into the Map component I put the **Marker** component and in the List component, I rendered the list of my favorites locations as soon as they are filtered in the **NavSearch** component.

Using my 5 favorites places like a constant I interated the Markers components using them, so in the Marker component, I instantiated a **google.maps.Marker** to put them on the map and populate the infoWindow with a 3rd part **Foursquare API** bringing tips and Likes to each place.

To finish my project, I collected this Markers Objects in an Array and took him to a List component to be iterate and filtered by the NavSearch input using the state attribute in the higher parent.

## Getting Started
To test this App in your machine, just follow the steps below:
- Clone this repo in your local ```git cloneei https://github.com/strongSoda/neighbourhood-react-map-resubmit.git```
- Now into your folder project in the terminal exec ```npm install``` to install all dependencies
- After install all dependencies just execute ```npm start``` on the terminal to launching the App in the browser.
### Offline First
- The service worker is only enabled in the production environment. It's recommended that you do not enable an offline-first service worker in a development environment.
- If you need to **test your offline-first** service worker locally, build the application (using `npm run build`) and run a simple http server from your build directory.
- More information [Here](https://github.com/facebook/create-react-app/blob/master/packages/react-scripts/template/README.md#offline-first-considerations)


## Technology
- ReactJs
- HTML
- CSS
- Foursquare API
- Google Maps API


## Resources:
- [Google Maps Platform Documentation](https://developers.google.com/maps/documentation/)
- [Foursquare API](https://developer.foursquare.com/)
- [Create-react-app](https://github.com/facebook/create-react-app)
- [React-async-script-loader](https://www.npmjs.com/package/react-async-script-loader)
- [Snazzy Maps](https://snazzymaps.com/)
- [Flaticon](https://www.flaticon.com/)

## Udacity Guides:
- [Udacity CSS Style Guide](http://udacity.github.io/frontend-nanodegree-styleguide/css.html)
- [Udacity Git Commit Message Style Guide](https://udacity.github.io/git-styleguide/)
- [Udacity HTML Style Guide](http://udacity.github.io/frontend-nanodegree-styleguide/index.html)
- [Udacity JavaScript Style Guide](http://udacity.github.io/frontend-nanodegree-styleguide/javascript.html)

## License:
The content of this repository is licensed under a MIT license.




