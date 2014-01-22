heroku-buildpack-gifsicle
=========================

Heroku buildpack for gifsicle support.

Binary for gificle is brought from https://github.com/l4u/gifsicle-heroku (copy pasted into the gh-pages branch of this repository).

Usage
=====
To use, checkout the usage guide on https://github.com/ddollar/heroku-buildpack-multi then add this repo in your `.buildpacks`.

Example:
    
    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-ruby
    https://github.com/jc4p/heroku-buildpack-gifsicle
