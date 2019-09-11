# @thomas_p/test-npm-package-example

![npm (scoped)](https://img.shields.io/npm/v/@thomas_p/test_package_example)

tutorial from https://www.freecodecamp.org/news/how-to-make-a-beautiful-tiny-npm-package-and-publish-it-2881d4307f78/

Removes all spaces from a string.

# Install
$ npm install @thomas_p/test_package_example

#Usage
const removeAllSpaces = require("@bamblehorse/tiny");

removeAllSpaces("So much space!");
//=> "Somuchspace!"

removeAllSpaces(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1