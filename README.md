# Static site template - TwObLoKeS

### This includes Grunt which will run sass then minify images, scripts and css. It will also watch when a file is changed and automate this for development. Come @ me bro!

------

#### Setup

* `git clone git@github.com:twoblokes/a999_static_site_template.git` into clean directory
* Open `package.json`, rename the `name` to clients 
* `npm install`
* `grunt dev` to watch files (minify js + css)
* `grunt` to minify images, js + css

_`npm` requires node.js, click the big fat install button over here <a href="http://nodejs.org/" target="_blank">http://nodejs.org/</a>_

------

#### Break it down

This will use Grunt to:
+ Smush sass into public/stylesheets/application.css
+ 