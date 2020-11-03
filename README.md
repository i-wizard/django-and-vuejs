# django-and-vuejs
boilerplate for working with django and vuejs frontend
This is a boilerplate for developers that want to build a web app using django as the backend engine and vuejs for the frontend.
# Steps:
1. clone this project into a dummy directory
2. On your local machine, create venv, activate it, install django and create a project
3. move all the contents of the dummy directory into the root of your new project directory, i.e where the manage.py file lives.
4. ensure u have node and npm installed, then run 'npm install', this will install the required node modules you need like bootstrap, jquery, axios etc.
5. run "npm run production", this will compile all your vue files and create a main.js file located at the ~/static/js/main.js
6. The base.html template will have the "id=app" and every other page that inherits from the base.html file can now house each vue component e.g <blog></blog>
7. run "npm run watch-poll" on a new terminal while in development, this command will run continuosly and watch for relevant changes in your vue file and trigger webpack to recompile your vue files and update your main.js file in your static folder. So you don't need to run "npm run production" after u make any change to your vue files.
