heroku-buildpack-gifsicle
=========================

Heroku buildpack for gifsicle support.

Binary for gificle is compiled using the a release on [gifsicle's repo](https://github.com/kohler/gifsicle).

Current version: 1.87

Usage
=====

To use, checkout the usage guide on https://github.com/ddollar/heroku-buildpack-multi then add this repo in your `.buildpacks`.

Example:

    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-ruby
    https://github.com/jc4p/heroku-buildpack-gifsicle
