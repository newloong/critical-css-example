# critical-css-example
This is a basic example to show how I set up my critical CSS and how I use the `postcss-critical-spit` plugin (located at https://www.npmjs.com/package/postcss-critical-split).

## Install
* Clone the repository
* Open a Terminal window in the main project folder
* run `npm install`

## Usage

### PostCSS-only example
* run `gulp css:sass` first (this is to generate the input CSS file)
* run `node postcss.js` to run the Node task that runs the direct PostCSS task without Gulp.

### Gulp example
* Run `gulp` to generate the files and run a local server with development setup
* Run 'gulp --release' to generate the files and run a local server with release (aka critically-rendered) assets
* Check out the `Gulpfile` and the `main-critical.css` file in the `build/css` folder to see what happens

