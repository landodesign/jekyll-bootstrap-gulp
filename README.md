Jekyll-Bootstrap-Gulp
=============================

A starter project including full setup for Jekyll, GulpJS, Bootstrap 3.x, JavaScript &amp; BrowserSync

## System Preparation

To use this starter project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/) - `$ gem install jekyll`
2. [NodeJS](http://nodejs.org) - use the installer.
3. [GulpJS](https://github.com/gulpjs/gulp) - `$ npm install -g gulp` (mac users may need sudo)

## Dependencies

Basic dependencies installed:

* Sourcemaps
* Sourcemaps Support
* Autoprefixer
* Gulp Sass
* BrowserSync
* Concat
* Uglify
* Rename


## Local Installation

1. Clone this repo, or download it into a directory of your choice.
2. Inside the directory, run `npm install`.

## Usage

**Development mode**

To run the tasks: (file watching, browser sync, auto-rebuild, CSS injecting)

```shell
$ gulp
```

**Jekyll**

As this is just a Jekyll project, you can use any of the commands listed in their [docs](http://jekyllrb.com/docs/usage/)

## Deploy with Gulp on GitHub Pages

You can easily deploy your site build to a gh-pages branch. First, follow the instructions at [gulp-gh-pages](https://github.com/rowoot/gulp-gh-pages) to get your branch prepared for the deployment and to install the module. Then, in `gulpfile.js` you'll want to include something like the code below. `gulp.src()` needs to be the path to your final site folder, which by default will be `_site`. If you change the `destination` in your `_config.yml` file, be sure to reflect that in your gulpfile.



```javascript
var deploy = require("gulp-gh-pages");

gulp.task("deploy", ["jekyll-build"], function () {
    return gulp.src("./_site/**/*")
        .pipe(deploy());
});
```
