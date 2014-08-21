# Fitness Tracker

## About
Web App to track fitness gains

## Technologies
* Jade
* Stylus
* Grunt
* Bower
* NPM

## Getting Started
1. Install grunt dependencies
```
npm install
```

2. Familiarize yourself with the file structure
	* Dev
		* Handles all raw files you are developing including Jade, Stylus and multiple JavaScript files
	* Dist
		* Contains files that should be placed on a webserver.
		* All files in this folder have been compiled and concatenated.
3. Running Grunt
	* While developing use
	``` 
	grunt
	```
	* To deploy the server to a live server
	* Note: grunt deploy will minify & uglify your JavaScript which makes debugging difficult :)
	```
	grunt deploy
	```
