Heroku buildpack: Bugzilla
==========================

This is a Heroku buildpack that runs Bugzilla 5.1+

Usage
-----

Example usage:

    $ heroku create --stack cedar --buildpack https://github.com/dylanwh/heroku-buildpack-bugzilla.git

    $ git push heroku master
    ...
    -----> Heroku receiving push
    -----> Fetching custom buildpack
    -----> Bugzilla detected
    -----> Installing dependencies

The buildpack will detect that your app has an `app.psgi` and `checksetup.pl` in the root.

FEATURES
--------

TODO: declare which bugzilla optional features to turn on.
