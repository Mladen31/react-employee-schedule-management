# react-employee-schedule-management

##How to Run

###Development When you're working on project with real back-end start with:

$ npm start 
NOTE: The npm start task is alias for npm start -- --env=DEV. 

###Production build/
|- dist --> distribution source code that goes to production | |- fonts/ --> fonts | |- images/ --> image files | |- scripts/ --> js files | | |- main.min-12345.js --> concat, minify angular app js files and cached html templates
| |- styles/ --> css files | |- main.min-12345.css --> concat & minify app css files | |- index.html --> app main file |- docs/ --> app documentation

##Installation & Configuration

###Platform & Tools You need to install Node.js and then the development tools. Node.js comes with a package manager called npm (requires npm version >= 2.0.0 for this project) for installing NodeJS applications and libraries.

###E2E TODO

##How to Build The build task get app ready for production. The build task include transpilation from ES6 to ES5, concatenation, minification, compression, asset revision, template cache, cdn etc. If there have been no errors when executing the build command, the build should be located in build/dist directory and this build is ready for uploading to the server! To initiate a full build, you simply run the follow task:

$ npm run build
