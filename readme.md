# Project Template One

This is a template designed to by cloned for simple projects that require JQuery, and need tasks to be automated with Gulp.


To clone this repository use the `git clone` command. It will create a new folder that you will want to rename to your project name. Then you can `cd` into the project. YOu do not need to run `git init`.

If you cloned this project you will need to change the remote  in git by:
```
git remote -v #checks for all remotes and lists them
git remote rm origin #remove the origin
git remote add origin #plus the ssh url to your repo
git remote -v #verify you have an origin
```
Install Gulp Command Line Interface via NPM, then run in your project directory:
```
npm init 
npm install gulp jshint gulp-jshint jshint-stylish gulp-watch
touch gulpfile.js
```
Install bower packages (such as JQuery) by:
```
bower install
```

