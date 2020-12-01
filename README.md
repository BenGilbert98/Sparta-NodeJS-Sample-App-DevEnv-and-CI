# Sparta NodeJS Sample App DevEnv and CI

## Description
This repo will be a dev env you can copy and set up by running vagrant up.

## Pre requisits
- Virtual Box
- Ruby
- Vagrant
- Bundler

## Instructions and Step by Step
1) Clone this repo
2) Run `vagrant up` in the directory inside your bash or terminal
3) go to 192.168.10.100 to run the app
<To be completed>


## Getting Set up


## Running the Environment
1) Navigate to the cloned file directory and run `vagrant up`

## Running the tests

### Integration Tests

``` bash
$ cd tests
$ bundle install
$ rake spec
```
### Unit Tests

``` bash
$ vagrant ssh app
$ cd /home/ubuntu/app
$ pm2 stop app.js

$ cd /home/ubuntu/app
$ npm test
```


timeline landing page tracker