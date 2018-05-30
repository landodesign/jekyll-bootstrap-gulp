Jekyll-Bootstrap-Gulp
=============================

A starter project including full setup for Jekyll, GulpJS, Bootstrap 3.x, JavaScript &amp; BrowserSync

## System Preparation

To use this starter project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/) - `$ gem install jekyll`
2. [NodeJS](http://nodejs.org) - use the installer.
3. [GulpJS](https://github.com/gulpjs/gulp) - `$ npm install -g gulp` (mac users may need sudo)

## Dependencies

Install the following dependencies as a minimum requirement:

* Sourcemaps
* Sourcemaps Support
* Autoprefixer
* Gulp Sass
* BrowserSync
* Concat
* Uglify
* Rename
* Sass Lint

## Local Installation

1. Clone this repo, or download it into a directory of your choice.
2. Inside the directory, run `npm install`.
3. Install required dependencies (see above).

## Usage

Add your custom styles in _scss/main.scss

Add your custom scripts in _js/scripts.js

Add your visual assets (jpg, png, svg, etc.) in assets folder

**Development mode**

To run the tasks: (file watching, browser sync, auto-rebuild, CSS and JS injecting)

```shell
$ gulp
```

**Jekyll**

Visit Jekyll [docs](http://jekyllrb.com/docs/usage/)

## TO DO

* Add support for SVG Sprites
* Add support for Async JavaScript
* Migrate from Node to Yarn 
* Move Gulp Tasks in separate folder
