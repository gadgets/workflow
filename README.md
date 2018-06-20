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
* Install gulp |> npm install --save-dev gulp | Note - on Windows add -g to get the following to work
* Install gulp-sass |> npm install --save-dev gulp-sass
* Install browser-sync |> npm install --save-dev browser-sync
* Install gulp-autoprefixer |> npm install --save-dev gulp-autoprefixer
* Install gulp-clean |> npm install --save-dev gulp-clean
* Install gulp-concat |> npm install --save-dev gulp-concat

# Useful Settings

## gulp
* minify css -> .pipe(sass({outputStyle: 'compressed'}).on('error', sass.logError))
