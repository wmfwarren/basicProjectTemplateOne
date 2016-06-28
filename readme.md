# Project Template One

This is a template designed to by cloned for simple projects that require JQuery, and need tasks to be automated with Gulp.


To clone this repository use the `git clone` command. It will create a new folder that you will want to rename to your project name. Then you can `cd` into the project. YOu do not need to run `git init`.

If you cloned this project you will need to change the remote in git by:
```
git remote -v #checks for all remotes and lists them
git remote rm origin #remove the origin
git remote add origin #plus the ssh url to your repo
git remote -v #verify you have an origin
```
Install Gulp Command Line Interface via NPM, then run in your project directory:
```
npm init 
npm install
```
Install bower packages (such as JQuery) by:
```
bower install
```
If you need to update packages run:
```
bower update
```

Editing this template:
This is a very basic template, it will be updated from time to time. If you need, or want, to make it your own then feel free to fork it to your GitHub by:
Click the "fork" button in the upper right-hand side of this repo on GitHub. You then navigate to your fork and run `git clone #your ssh url here` to make a local copy for yourself.  

You will want to add the folders `bower_components` and `node_modules` to your directory's `.gitignore` or to your global one if you have one. 