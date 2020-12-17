# Webpack 4 

## Intro 

The hello world of webpack 4 for begginers

downloading the dependencies into the node_module 

	`$ npm install webpack webpack-cli --save-dev`

In your index.js, write a first hello world alert:
	
	`alert('Hello Webpack World !');`

Save the file, and in your terminal/console, run:
	
	`$ node_modules/.bin/webpack`

to minified the files set it to production

	`node_modules/.bin/webpack --mode=production`