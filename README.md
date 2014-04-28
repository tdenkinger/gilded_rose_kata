# The Gilded Rose Code Kata

This is a refactoring kata, so you will be starting with a legacy code base.  To work the Kata, clone this git repository and read the REQUIREMENTS for the "rules" involving this kata.

## Changes from the original

This Ruby version follows the original code very closely, but has the following changes:

* The original had no tests.  Since this is a refactoring kata, Jim Weirich felt the tests are important and provided a fairly complete test suite. Sandi Metz provided a set of tests in [Minitest format](https://gist.github.com/skmetz/7772668), and I have included those here. If you want Jim's original Rspec tests, [they can be found here](https://github.com/jimweirich/gilded_rose_kata). If you want to play as if the code is true, untested legacy code, just delete the tests.

* The original used a hard coded set of "items", presumably for testing the code.  Since Jim added a test suite, the hard coded values were not of much use.  He also changed the interface to accept a list of items as a parameter rather than a hard coded constant.

You can read
[the original kata article](http://iamnotmyself.com/2011/02/13/refactor-this-the-gilded-rose-kata/) for more details.

## Installation Hints

The easiest way is to use bundler to install the dependencies. To do so, you need to install the bundler gem if you haven't already done so

    gem install bundler

run bundler

    bundle

Have a look at the Gemfile for all dependencies.

