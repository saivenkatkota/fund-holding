# webpack-react-redux
A boilerplate for playing around with react, redux and react-router with the help of webpack.

Contains: 

* a working example of a filterable table which you can play around with (look below).
* ES6 - 7 Support with Babel
* Redux dev tools to help you keep track of the app's state
* Routing
* hot module replacement support so you can change modules or react components without having to reload the browser
* a webpack production config so you can build the app and make it ready for production
* Sass support, just import your styles wherever you need them
* eslint to keep your js readable
* much more...


## Run the app

1. ```npm install```
2. ```npm start```

Once running, if you want to hide the redux dev monitor: ```CTRL+H```

Yes, it takes a while to load the first time you open the app.

## Local URL
http://localhost:3000/index.html

### Is the hot module replacement really working?

Yup! Take a look:

The app updates without the browser having to reload. You don't lose state!

## Build the app
```npm run build```

This will build the app into the "dist" directory in the root of the project. It contains the index.html along with the minified assets, ready for production.