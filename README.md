* Introduction
----------------
See a working demo of the Customer CRUD application on mean stack.
This demo split on the  module of Login and Registration pages out from the angular application in order to secure access to the  angular client files, so all front end angular files(including javascript, css) are only available (Dashboard) or visible to authenticated users only.I am tested this demo application on Windows 7 64 bit.

 * Requirements
 --------------------
  To test this app, You have to required
 AngularJS, NodeJS, ExpressJS and  MongoDB on your local machine. 


 * Installation
 --------------------
 
 Install NodeJS:-
 ******************
 Download the latest release of NodeJS from https://nodejs.org and install using all the default options.
 
 Install MongoDB:- 
 *******************
 Download the current  release of MongoDB from https://www.mongodb.org/downloads and install using the "Complete" setup type and all the default options.
 
 Create the MongoDB data directory
 Create an empty folder at "C:\data\db".4
  
 ExpressJS :- 
 *******************
 ExpressJS runs on top of NodeJS so it isn't installed directly on Windows, it's added via NPM (Node Package Manager) when you run "npm install" for an application. 
 
 AngularJS:- 
 ****************
 AngularJS runs in the browser and is added using the standard HTML <script> tag.
 here's an example of how to include the angular script using the Google CDN
 <script src="//ajax.googleapis.com/ajax/libs/angularjs/1.4.8/angular.min.js"></script> 


 
 * Run Application
 ---------------------
 To run the demo application run 'node server.js' from the same location to start the web server and browse to http://localhost:3000 to access the application.



