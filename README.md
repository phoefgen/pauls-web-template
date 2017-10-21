# PAULS WEB TEMPLATE!

This template should kick start your website, and set you up with a build pipeline with the following features:

Pre-Configured gulpfile that has these stages:

#### Browser Updates
  - Monitors all auto-compiled files for changes, and refreshes your browser(s)
  - Implements browserSync, which allows you to connect multiple devices for responsive design (etc) testing.
  - Changes to the other section, automatically call this feature. 
  
#### CSS
  - Converts SASS to CSS
  - Auto Prefixes legacy browser support to your SASS/CSS
  - Minifies all your CSS files

#### Javascript
  - Runs JSHint to catch syntax problems.
  - Runs Babel to transpile ES6 to ES5
  - Concats all your JS files into a single file that the browser downloads. Files are currently concatted in alphabetical order.
  - minifies the JS.

#### Images
  - Compresses full res images to web res images.

#### HTML
  - Consumes Jade/Pug markup syntax, and complies it to HTML

#### Cleanup
  - A helper function that clears out the `dist` directory

#### Jasmine Tests
  - Testing Support structure in place, with test stubs.

## Setup
  - Fork a version of the template. 
  - install NPM

  `npm install gulp-ruby-sass gulp-autoprefixer gulp-cssnano gulp-jshint gulp-concat gulp-uglify gulp-imagemin gulp-notify gulp-rename gulp-livereload gulp-cache del gulp-pug pug gulp-babel gulp-pug gulp-jasmine-browser browser-sync --save-dev`




