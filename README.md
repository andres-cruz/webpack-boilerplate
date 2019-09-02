# webpack boilerplate

### How to install this project
```sh
$ git clone https://github.com/andres-cruz/webpack-boilerplate.git
$ cd webpack-boilerplate
$ npm i
```

### This repo have the following Babel setup: ###

```javascript
"devDependencies": {
    "babel-preset-env": "^1.7.0",
    "babel-preset-react": "^6.24.1"
  },
  "dependencies": {
    "babel-cli": "^6.24.1",
    "live-server": "^1.2.1"
  }
```  

### The file package.json have the following scripts: ###

```javascript
"scripts": {
    "server": "live-server public/",
    "build": "webpack",
    "dev-server": "webpack-dev-server"
  }
```  

### How to run this project

  #### To start the server: ####

   ```sh
$ npm run dev-server
```

### Features:
This boilerplate is configured to use
- React
- CSS
- SCCS

### Tech stack & libraries:
- Babel
- webpack
- React