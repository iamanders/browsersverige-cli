# Browsersverige cli

Node module for displaying browser stats via http://browsersverige.se from the command line.

![Screenshot](https://dl.dropboxusercontent.com/u/1162759/dump_2014-12-30_12-01-11.png)

## Install

Install the module with [npm](http://npmjs.com):

	npm install -g browsersverige-cli

## Usage

Display full list

	browsersverige

Display only top 3 browsers

	browsersverige -l 3

Help?

	browsersverige -h

Copy to clipboard (for pasting into other applications)

	browsersverige -l 3 | pbcopy

### Notes

This is just one way of measuring Browser stats. This is explained [here](http://browsersverige.se/om).

### Todo
- [ ] Add argument for filtering by Browser vendor
- [ ] Add tests

### Changelog
+ 1.0.1: Added percentage characters in the output
+ 1.0.0: No longer beta
+ 0.0.1: Published

### License
Copyright (c) 2014 Urban Sanden. Licensed under the MIT license.