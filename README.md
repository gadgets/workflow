# workflow
My web workflow with NPM, SASS, Gulp, and more.

# Setup a Project

# Download needed software
* Git - https://git-scm.com
* Node - https://nodejs.org/en/

## Repository
* Create <empty> repository
* Clone <empty> repository |> git clone url

## Initialize
* Initialize |> npm init

## Install
* Note - on Windows add -g to get the following to work 
* Install gulp |> npm install --save-dev gulp
* Install gulp-sass |> npm install --save-dev gulp-sass
* Install browser-watch |> npm install --save-dev browser-watch
* Install gulp-clean |> npm install --save-dev gulp-clean

# Useful Settings

## gulp
* minify css -> .pipe(sass({outputStyle: 'compressed'}).on('error', sass.logError))
