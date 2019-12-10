# ProgressBar 
 progress html5 element <progress> global object which is created on the page when needed
 this is written in vanillaJS
 arrayOfElements must be javascript nodeList(will be converted to array)
 
 This can be used on pages with for example: forms with multiple steps 

# Documentation progress bar

# Installation 

```shell
$ npm install
$ npm run serve
$ npm run build
$ npm run dev
```

<ul>
<li>Run 'npm install' > 
This will install the dependencies first </li> 
<li>'npm run serve' will build the project in development mode and watches the files changed, it creates a 'dist' folder and startup a static server
which listens to http://localhost:8081/</li>
<li>'npm run build' will run eslint first and will build the project in production mode using Webpack and creates a 'dist' folder with all the built files which is the root folder of localhost</li>

<li>'npm run dev' will build project in development mode </li>
</ul>

TODO setup unit testing

# Configuration

### Webpack
This project uses Webpack as a buildtool which is configured in webpack.development.config.js for local development. <br>
and webpack.production.config.js for production environment.
There are 3 loaders configured which handle the html, scss and js files.<br>
To get more information about the configuration options, see: <a href="https://webpack.js.org">https://webpack.js.org</a>

Webpack Plugins used:
- https://webpack.js.org/plugins/html-webpack-plugin/
- https://webpack.js.org/plugins/copy-webpack-plugin/
- https://webpack.js.org/plugins/uglifyjs-webpack-plugin/

### Source Folder Structure

sass/  folder which containes all the scss files

src/

It consists of a:
<ul>
<li>'javascript' folder which contains the es6 javascript partials which are bundled by webpack 
<li>'html' folder which contains the example.html
</li>


</ul>

### Config files

- .babelrc : config babel settings
- .eslintrc.js : config eslint settings
- webpack.*.config.js : config webpack settings




