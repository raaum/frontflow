#frontflow
A starter application that serves as an example of how to accomplish some common frontend tasks and workflows and improve your development.

Write better code and deploy your apps more easily and efficiently by processing your Sass, Compass, and CoffeeScript sources at the development stage, prior to production, using Gulp, Git, and Browserify.

## Features
- Uses the latest NPM sources
- Processes tasks with Gulp
- Imports libraries with Browserify
- Incorporates Sass and Compass
- Issues tasks in sequence
- Watches changes to files
- Adds environmental variables
- Adds static reloads
- Processes your Sass CSS
- Minifies your CSS
- Minifies your CoffeeScript
- Minifies your JavaScript
- Minifies your HTML
- Minifies your JSON
- Compresses your images
- Includes an example application

##Example Application Notes
You need to have Ruby and Compass installed and in your system PATH to use the example application.

####Setting Paths:
- Win `$ set PATH=%PATH%;C:\Ruby200-x64\bin`
- Mac `$ export PATH=/usr/local/bin:$PATH`

####What is Ruby and Compass?
If you don't know what Ruby or Compass is, or don't know how to install it, that's okay.  The application is not the gold here.  The process is the gold.  The application is just thrown in to show you that it works, and it works.  Read and try to understand the configuration settings in `gulpfile.js` and `package.json`.  They serve as the primary example of how to construct your own frontflow.

## Installation
1. Install Gulp, Git, and Node
	- [node.js](http://nodejs.org/)
	- [git](http://git-scm.com/)
	- [gulp](http://gulpjs.com/)
2. `$ git clone https://github.com/raaum/frontflow.git`
3. `$ cd frontflow`
4. `$ npm-install`
5. `$ npm install -g gulp`
6. `$ gulp`
7. Go to `http://localhost:8080`
