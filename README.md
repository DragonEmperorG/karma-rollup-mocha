# karma-rollup-mocha #
[![Build Status](https://travis-ci.org/axmand/karma-rollup-mocha.svg?branch=master)](https://travis-ci.org/axmand/karma-rollup-mocha)
[![codecov](https://codecov.io/gh/axmand/karma-rollup-mocha/branch/master/graph/badge.svg)](https://codecov.io/gh/axmand/karma-rollup-mocha)

##  Unit test  ##
>Unit test to make sure your code runs well
### first step: ###
```
npm install
```
### second step: ###
```
npm install -g karma-cli
```
>You will need to do this if you want to run Karma on Windows from the command line.

### start karam ###
```
karma start
```
##  Build  ##
>Building 'dist/bundle.js' as an output if you confirmed that all of your tests runs well.
### install rollup ###
```
npm install -g rollup 
```
>You will need to install rollup in global if you want to run rollup on Windows from the command line.
### build ###
```
rollup -c
```
>The default output folder's location : "./dist/*"
##  Npm publish  ##
```
npm publish
```
>Before publish code to npm,you need to add one user at least.
### add npm user ###
```
npm adduser
```
>Then add username/password/email

