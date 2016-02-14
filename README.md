# ExpressJS Get Started

### Installing

	$ mkdir myapp
	$ cd myapp
	$ npm init
	$ npm install express --save

### Basic

create file named app.js, add following code:

	var express = require('express');
	var app = express();

	app.get('/', function (req, res) {
		res.send('Hello Dyo World!');
	});

	app.listen(8000, function () {
		console.log('This app listening on port 8000');
	});

Run the app with command:

	$ node app.js

and then Open http://localhost:8000	