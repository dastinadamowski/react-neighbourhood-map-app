# Udacity Project: Neighbourhood Map

Neighbourhood Map is a single page web application. It displays a Google Map of an area in Cracow (Poland) and various points of interest with additional information presented from the Foursquare API when landmark is selected. This app is built for the No.8 Neighbourhood map project which is a part of the [Front-End Nanodegree Developer with Udacity](https://eu.udacity.com/course/front-end-web-developer-nanodegree--nd001).


## How to run the project in Development Mode

1. Download ZIP or clone the repo using git: [https://github.com/dastinadamowski/react-neighbourhood-map-app.git](https://github.com/dastinadamowski/react-neighbourhood-map-app.git).
2. Navigate to a location where you unzipped the file or cloned the repository.
3. Install all the project dependencies with `npm install`
4. Start the development server with `npm start`

A new browser window opens automatically displaying the App.  If it doesn't, just navigate to [http://localhost:3000/](http://localhost:3000/) in your browser.

***NOTE:*** *The service worker for this App will only cache the site when it is in Production Mode.*


## How to run the project in Production Mode

To run the App in Production Mode locally follow the steps below:

1. Build the production ready optimized code with `npm run build`
2. Navigate to the `build` directory and run a localhost server.  If you have Python 2.x installed you can run the Python Simple Server like by using:   
`python -m SimpleHTTPServer 8080`
3. For Python 3.x, the command will be:
`-m http.server 8080`
4. In either case navigate to [http://localhost:8000](http://localhost:8000) in your browser.
____________________________________________________________________________________________________

Or if you prefer you can use Node [serve](https://github.com/zeit/serve).  If you do not have it installed you can install it with:  
`npm install -g serve`  
and then navigate into the build directory and run:
`serve -s`  
In this particular case the site will be hosted at [http://localhost:5000](http://localhost:5000) in your browser.


## Libraries, frameworks, APIs - dependencies used

 * [Google Maps API](https://cloud.google.com/maps-platform/)

 * HTML document traversal and manipulation possible with [jQuery 3.2.1](http://jquery.com/)

 * Built with [React JS](https://reactjs.org/)

 * HTML, CSS, JavaScript ES6

 * Information about places from [Foursquare](https://foursquare.com)

 * Many thanks to the [Udacity team](https://eu.udacity.com/), [MDN Community](https://developer.mozilla.org/en-US/docs/Learn/HTML) as well as [w3schools](https://www.w3schools.com/) for precious resources, invaluable yet free-of-charge knowledge and for proving that programming can be fun, a big driver of change and a spectacularly limitless tool.


Thank you for using this app!  
By Dastin Adamowski  
