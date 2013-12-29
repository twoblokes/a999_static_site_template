# Static site template - TwObLoKeS

### This includes Grunt which will run sass and minify images, scripts and css. It will also watch when a file has been changed and automate this for a development environment. 

#### Also using Bourbon.io as our sass mixin library.

------

#### Setup

* `git clone git@github.com:twoblokes/a999_static_site_template.git` into clean directory
* Open `package.json`, rename the `name` to clients number and name
* `npm install`
* `grunt dev` to watch files (minify js + css)
* `grunt` to minify images, js + css

_`npm` requires node.js, click the big fat install button over here [http://nodejs.org/](http://nodejs.org/)_

------

#### Break it down

This will use Grunt to:
* Concatinate and minify everything from `sass` into `public/stylesheets/application.css`
* Concatinate and minify everything from `public/javascripts/libs/` + `public/javascripts` into `public/javascripts/live/live.min.js`
* Minifies all images from `public/images/` into `public/images/live`

------

##### [WEARETWOBLOKES](http://twitter.com/wearetwoblokes)