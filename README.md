# Reveal.js powered presentation template

Base on the work done for https://github.com/Bizzby/mobilise-meetup-show-and-tell

## Install

* `nmp install`
* `bundle install` _This step should be remove, see the TODOs file

## Run

> This sucks a bit... It should be bundled into a Makefile/Cakefile

From the root of the project run `node node_modules/jade/bin/jade.js $PWD/src/*.jade --out . --watch` to generate live the HTML. On another tab run ` sass --scss css/source/bizzby:css --watch` to generate live the CSS.

