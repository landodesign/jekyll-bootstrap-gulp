Jekyll-Bootstrap-Gulp
=============================

A starter project including full setup for Jekyll, GulpJS, Bootstrap 3.x, JavaScript &amp; BrowserSync.

## System Preparation

To use this starter project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/) - `$ gem install jekyll`
2. [Yarn](https://yarnpkg.com/en/) - use the installer.
3. [GulpJS](https://github.com/gulpjs/gulp) - `$ yarn global add gulp` (mac users may need sudo)

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
2. Inside the directory, run `yarn`.
3. Install required dependencies (see above).

If you're more familiar with NPM, see this Yarn [cheatsheet](https://devhints.io/yarn) for the equivalent commands.

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
* Move Gulp Tasks in separate folder
