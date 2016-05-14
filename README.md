
# A web application sample


## Objectives


## How to...

[Interactively create a Spring Boot Project Web Application](https://start.spring.io "title")

[Configure a GitHub Project](https://github.com/jonyfs/webapp#github-configuration) 
	
[Interactively create a npmjs package.json file](https://github.com/jonyfs/webapp#npmjs-configuration)
	
### Spring Boot Configuration

	Visit the SPRING INITIALIZR page https://start.spring.io to create the spring boot application skeleton
	
	For this example just select Web MongoDB and DevTools dependencies.
	
	After, download the generated code.
	

### GitHub Configuration

	echo "# A web application sample" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin https://github.com/jonyfs/webapp.git
	git push -u origin master
	
### npmjs Configuration

	npm init
	
#### npmjs Components used

	npm install bower --save
	npm install grunt --save
	npm install grunt-cli --save
    npm install grunt-contrib-clean --save
    npm install grunt-contrib-concat --save
    npm install grunt-contrib-jshint --save
    npm install grunt-contrib-uglify --save
    npm install grunt-env --save
    npm install grunt-include-source --save
    npm install grunt-ng-annotate --save
    npm install grunt-preprocess --save
    npm install grunt-contrib-less --save
	
### Bower Configuration

	bower init
	
	After, create a .bowerrc to change the default directory where the components will be installed.
	
	The .bowerrc content:
	{
	  "directory": "src/main/resources/static/bower_components"
	}
	
#### Bower Components used

*   Material Design Theme for Bootstrap:
	
	bower install bootstrap-material-design --save
	


## Tools


*   Spring Boot
*   MongoDB
* 	NodeJs
*   Bower
*   Grunt
*   Material Design Theme for Bootstrap
*   AngularJS
*   Less


