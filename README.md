# E2EUI-test-automation-exam
E2E User Interface testing for creating a bank account

This is an example project using cucumber-js and selenium-webdriver to run browser-based automated tests, in both desktop Chrome.

## Dependencies

tool|function|location
:---|:---|:---
`nodejs`|Node.js v8+|https://nodejs.org/
`grunt`|Grunt Javascript task runner|https://gruntjs.com/


## Running the tests on the desktop

To get going, you just need to install npm.

## Setup Config files

To run the tests you will require some config files, please let me know if you are missing them. 

# How to debug tests
In Chrome, open chrome://inspect/#devices

To debug E2E UI run 
```
$ npm run test:debug:e2eui
```

# How to run the test

Running E2E UI test suite
```
$ grunt e2eui
```

# Configurations
You can use the following arguments when running grunt tasks if you have different environment to test.
```sh
$ grunt e2eui --test-env=prod
```
