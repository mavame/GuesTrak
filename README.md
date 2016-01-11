# GuesTrak™ Survey

This project is for a client.

## Features
It gives the client:
- A base project structure for using Grunt and SASS
- A few examples of form & UI elements to use within survey application
- A responsive, mobile-first layout

This uses Twitter Bootstrap as a base CSS framework. There is an implicit dependency on the framework and is achieved using concatentation and Grunt.

## Usage

### Getting Set Up
To use this code, you will need [Node](https://nodejs.org/en/ "Node.js Homepage"), [npm](https://www.npmjs.com/), and [Grunt](http://gruntjs.com/ "Grunt Homepage") installed.

Once Grunt, npm, and Node.js are installed, you must install the node modules by running `npm install` at the root of the directory.

### Making Changes to CSS
Make changes in the `src/css/scss` and then compile them by running `grunt` at the root of the project.

Grunt can watch for changes for you, type the command `grunt dev` and Grunt will watch for changes and compile.

Style changes will be minified and concatenated, along with a cusom build of Twitter Bootstrap, into the file `css/style.css` which is included in the `index.html` file.

