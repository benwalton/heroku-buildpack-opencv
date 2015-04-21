heroku-buildpack-opencv
=======================

A Heroku buildpack that installs OpenCV (currently v2.4.11) shared libs, and then exports include and lib paths to `INCLUDE_PATH` and `LIBRARY_PATH` on the build dyno, and `LD_LIBRARY_PATH` on the production dyno.

Usage
-----

Simply add this Git repo to your `.buildpacks` file and set your Heroku config var `BUILDPACK_URL` to `https://github.com/mojodna/heroku-buildpack-multi.git#build-env`.
