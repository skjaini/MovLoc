# SF Movies Web Application

## Overview

Web application to display the locations where the movie was filmed in San Francisco utilizing the [Film
Locations](https://data.sfgov.org/Arts-Culture-and-Recreation-/Film-Locations-in-San-Francisco/yitu-d5am) data.


### Tech stack

* [node.js](http://nodejs.org) - For its ease of standing up web server that goes well with [Heroku](https://devcenter.heroku.com/articles/nodejs)
* [AngularJS](http://angularjs.org) - Impressive client-side framework providing MVVM pattern, Dependency Injection, 2-way data binding, Templating to name a few that I attempted 
  to incorporate into this SPA (Single-Page Application) in just couple of days of exposure to the framework.
* [Parse.com](http://parse.com) - Cloud app platform for building scalable backend that is used for movie data management and to demonstrate client-server architecture.
* [Twitter's Bootstrap](http://getbootstrap.com/) - For bootstraping the web page styles.


### Running the app 

One of these options can be used:

* serve this repository with your webserver
* install node.js and run `node scripts/web-server.js`


## Directory Layout

      ├── index.html                   -- the main template file for the app
      ├── 404.html                     -- 404 template file
      ├── css
      │   └── app.css                  -- app specific styles
      ├── js
      │   ├── app.js                   -- app module init file with directives injected
      │   ├── controllers.js           -- app controller
      │   └── services.js              -- app services for common/init methods
      │   ├── movie-names.json         -- app data with list of movie names
      ├── scripts
      │   └── web-server.js            -- node webserver
      ├── test                         -- tests go here
      └── views
          └── mapview.html             -- partial template file with the map view
