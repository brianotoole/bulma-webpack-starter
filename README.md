# Bulma / Webpack Starter Boilerplate
A boilerplate for scaffolding using Bulma, Webpack and Browsersync

## Getting Started: Installing

### Change Proxy Location
Open `webpack.config.js` file and change the proxy location for BrowserSync to work. On approx. line 37:

Change proxy location: "localhost/tma"
``` bash
proxy: 'localhost/FOLDERNAME', 
```

### Install NPM Dependencies
``` bash
npm install
```

### Watch Watch files with BrowserSync
``` bash
npm run watch
```

This will open up a browser window with local site and watch for file changes. Ex - http://localhost:3000/FOLDERNAME

### Build Public Files
``` bash
npm run build
```

This will build js files to './dist/js/bundle.js', and scss files to './dist/css/style.css'

### Bulma Styles
Bulma is being used for front-end styles. Checkout the documentation here: https://bulma.io/documentation/overview/variables/
